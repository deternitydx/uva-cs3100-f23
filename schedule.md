---
layout: default 
title: Schedule
nav_order: 3
---

# Semester Schedule

The schedule will be flexible as we cover each topic. We might spend some extra time on topics, so we will update the schedule as we progress through the semester.

<table class="schedtab"><thead>
<tr>
    <th>Mtg</th>
    <th>Date</th>
    <th>Topic</th>
    <th>Notes</th>
    </tr>
    </thead>
    <tbody><!--  {% increment lab %} {% increment mtg %} -->
{% for day in site.data.schedule %}
{% if day.type == 'holiday' or day.type == 'labholiday' %}
<tr class="holiday">
{% elsif day.type == 'header' %}
<tr class="header">
{% elsif day.type == 'lab' %}
<tr class="lab">
{% elsif day.type == 'exam' %}
<tr class="exam">
{% else %}
<tr>
{% endif %}
    {% if day.type == 'lab' %}
            <td class="lab mtg">LAB {% increment lab %}
            {% elsif day.type == 'header'%}
            <td class="header mtg">
            {% elsif day.type == 'holiday'%}
            <td class="holiday mtg">
            {% elsif day.type == 'labholiday'%}
            <td class="holiday mtg">LAB
            {% elsif day.type == 'exam'%}
            <td class="exam mtg">
            {% else %}
            <td class="mtg">
                {% increment mtg %}
            {% endif %}</td>
    <td class="text-center sched">{{day.date}}</td>
    <td class="sched">
    {% if day.link %}
        <a href="{{day.link}}">
    {% endif %}
    {{day.topic}}
    {% if day.link %}
        </a>
    {% endif %}
    {% if day.lectures or day.readings %}
    <br><span class="sched-sub">
        {% if day.readings %}
        Readings:
        {% for read in day.readings %}
        <a href="{{read.link}}">{{read.topic}}</a> 
        {% endfor %}
        {% endif %}
        {% if day.lectures and day.readings %}
        -
        {% endif %}
        {% if day.lectures %}
        Slides:
        {% for pdf in day.lectures %}
        {% if pdf.link %}
        <a href="{{pdf.link}}" alt="{{pdf.alt}}">{{pdf.time}}</a> 
        {% else %}
        <span title="{{pdf.alt}}">{{pdf.time}}</span> 
        {% endif %}
        {% endfor %}
        {% endif %}
        </span>
    {% endif %}
    </td>
    <td class="sched">{{day.notes}}</td>
    </tr>
{% endfor %}
</tbody></table>

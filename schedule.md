---
layout: page
title: Schedule
description: schedule
permalink: /schedule/
nav_order: 3
---

# Schedule

<table>
  <thead>
    <tr>
      <th>Date</th>
      <th>Topic</th>
    </tr>
  </thead>
  <tbody>
    {% for section in site.data.schedule %}
    <!-- Subheading -->
    <tr>
      <td colspan="2" style="background-color: #f4f4f4; font-weight: bold; text-align: center;">
        {{ section.section }}
      </td>
    </tr>
    <!-- Lectures in the section -->
    {% for lecture in section.lectures %}
    <tr>
      <td>{{ lecture.date }}</td>
      <td>
        {{ lecture.topic }}
        {% if lecture.badges %}
          {% for badge in lecture.badges %}
            <span style="background-color: {{ badge.color }}; color: white; padding: 2px 5px; border-radius: 3px;">{{ badge.text }}</span>
          {% endfor %}
        {% endif %}
      </td>
    </tr>
    {% endfor %}
    {% endfor %}
  </tbody>
</table>

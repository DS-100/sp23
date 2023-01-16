---
layout: page
title: Staff
nav_order: 7
description: A listing of all the course staff members.
---

# Staff

Jump to: [Instructors](#inst), [Lead Teaching Assistants](#lead-tas), [Teaching Assistants](#tas), [Readers](#readers).

**Note:** Consult the [calendar]({{ site.baseurl }}/calendar) for the most up-to-date office hours for each GSI.

## Course Staff Email
Contact course staff at [data100.instructors@berkeley.edu](data100.instructors@berkeley.edu) with any questions or concerns. This email is monitored by instructors and a few lead TAs.

<a name = 'inst'></a>

## Instructors

<div class="role">
  {% assign instructors = site.staffers | where: 'role', 'Instructor' %}
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>

<a name = 'lead-tas'></a>

## Lead Teaching Assistants

<div class="role">
  {% assign head_teaching_assistants = site.staffers | where: 'team', 'Head TA' %}
  {% for staffer in head_teaching_assistants %}
    {{ staffer }}
  {% endfor %}
  {% assign lead_teaching_assistants = site.staffers | where: 'role', 'Lead Teaching Assistant' %}
  {% for staffer in lead_teaching_assistants %}
    {% if staffer.team != 'Head TA' %}
      {{ staffer }}
    {% endif %}
  {% endfor %}
</div>

<a name = 'tas'></a>

## Teaching Assistants

<div class="role">
  {% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
  {% for staffer in teaching_assistants %}
  {{ staffer }}
  {% endfor %}
</div>

<!---
<a name = 'tutors'></a>

## Tutors

<div class="role">
  {% assign readers = site.staffers | where: 'role', 'Tutor' %}
  {% for staffer in readers %}
  {{ staffer }}
  {% endfor %}
</div>

-->


<a name = 'readers'></a>

## Readers

<div class="role">
  {% assign readers = site.staffers | where: 'role', 'Reader' %}
  {% for staffer in readers %}
  {{ staffer }}
  {% endfor %}
</div>

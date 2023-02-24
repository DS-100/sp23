---
layout: page
title: Home / Schedule
nav_order: 1
description: A week-to-week description of the content covered in the course.
course:
  edstem: https://edstem.org/us/courses/33744/
  faq: https://ds100.org/sp23faq
currWeekNumber: 6
---

# Principles and Techniques of Data Science

{: .mb-2 }
UC Berkeley, Spring 2023
{: .mb-0 .fs-6 .text-grey-dk-000 }

<p>
<a href="https://edstem.org/us/courses/33744/discussion/2396700" class="btn btn-blue">Lecture Zoom</a>
<a href="https://sections.ds100.org" class="btn btn-purple">Discussions</a> 
<a href="{{site.baseurl}}/calendar" class="btn btn-green">Office Hour/Lab Help</a>
</p>

<div>
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
  <div class="role">
    {% for staffer in instructors %}
    {{ staffer }}
    {% endfor %}
  </div>
</div>

Jump to current week: [here](#week-{{page.currWeekNumber}}){:target="_self"}.

<!-- <span style="color:red" h1> **This site is currently being built** </span> -->
+ Frequently Asked Questions: Before posting on the [class Ed]({{page.course.edstem}}), please read the [class FAQ page]({{page.course.faq}}).
+ The [Syllabus]({{site.baseurl}}/syllabus) contains a detailed explanation of how each course component will work this Spring, please take time to take a look.
+ **Note:** The schedule of lectures and assignments is subject to change.

<!--
+ The [Syllabus]({{site.baseurl}}/syllabus) contains a detailed explanation of how each course component will work this summer, given that the course is being taught entirely online.
+ Textbook readings are optional and actively in development. See the [Resources]({{site.baseurl}}/resources/#textbook) for more details.
+ **Note:** The schedule of lectures and assignments is subject to change.
-->

<!--
Jump to current week: [here](#week-{{page.currWeekNumber}}).

+ Lecture is hybrid: in-person in Li Ka Shing 245 and online via Zoom (see link above). Recordings will be posted within 12 hours of live lecture.
+ **Frequently Asked Questions:** Before posting on the [class Ed]({{page.course.edstem}}), please read the [class FAQ page]({{page.course.faq}}).
+ Join Ed: [here]({{page.course.edstem_join}}).
+ Textbook readings are optional and actively in development. See the [Resources]({{site.baseurl}}/resources/#textbook) for more details.
+ **Note:** The schedule of lectures and assignments is subject to change.

<br><br>
-->


<a name="schedule"></a>
## Schedule

{% for module in site.modules %}
<a name="week-{{module.weekNumber}}"></a>
{{ module }}
{% endfor %}


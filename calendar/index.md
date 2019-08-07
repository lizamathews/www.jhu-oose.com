---
# TODO: Full event name (tooltip with description) (tooltip.js / tippy)
# TODO: Filters
# TODO: Make bigger https://css-tricks.com/full-width-containers-limited-width-parents/ https://cloudfour.com/thinks/breaking-out-with-css-grid-layout/
# TODO: Height (scroll)
# TODO: Add footer
# TODO: ICS?
# http://colorbrewer2.org/#type=qualitative&scheme=Paired&n=12
default: &default
  eventSources:
    - events:
      - title: Lecture 0
        start: 2019-08-29
      - title: Lecture 1
        start: 2019-09-04
      - title: Lecture 2
        start: 2019-09-11
      - title: Lecture 3
        start: 2019-09-18
      - title: Lecture 4
        start: 2019-09-25
      - title: Lecture 5
        start: 2019-10-02
      - title: Lecture 6
        start: 2019-10-09
      - title: Lecture 7
        start: 2019-10-16
      - title: Lecture 8
        start: 2019-10-23
      - title: Lecture 9
        start: 2019-10-30
      - title: Lecture 10
        start: 2019-11-06
      - title: Review
        start: 2019-11-13
      - title: Quiz
        start: 2019-11-20
      color: "#1f78b4"
    - events:
      - title: Assignment 0
        start: 2019-08-29
        end:   2019-09-05
      - title: Assignment 1
        start: 2019-09-05
        end:   2019-09-12
      - title: Assignment 2
        start: 2019-09-12
        end:   2019-09-19
      - title: Assignment 3
        start: 2019-09-19
        end:   2019-09-26
      - title: Assignment 4
        start: 2019-09-26
        end:   2019-10-03
      - title: Assignment 5
        start: 2019-10-03
        end:   2019-10-10
      - title: Assignment 6
        start: 2019-10-10
        end:   2019-10-17
      - title: Assignment 7
        start: 2019-10-17
        end:   2019-10-24
      - title: Assignment 8
        start: 2019-10-24
        end:   2019-10-31
      - title: Assignment 9
        start: 2019-10-31
        end:   2019-11-07
      - title: Assignment 10
        start: 2019-11-07
        end:   2019-11-14
      color: "#33a02c"
    - events:
      - title: Assignment 0
        start: 2019-09-05
        end:   2019-09-10
      - title: Assignment 1
        start: 2019-09-12
        end:   2019-09-17
      - title: Assignment 2
        start: 2019-09-19
        end:   2019-09-24
      - title: Assignment 3
        start: 2019-09-26
        end:   2019-09-31
      - title: Assignment 4
        start: 2019-10-03
        end:   2019-10-08
      - title: Assignment 5
        start: 2019-10-10
        end:   2019-10-15
      - title: Assignment 6
        start: 2019-10-17
        end:   2019-10-22
      - title: Assignment 7
        start: 2019-10-24
        end:   2019-10-29
      - title: Assignment 8
        start: 2019-10-31
        end:   2019-11-05
      - title: Assignment 9
        start: 2019-11-07
        end:   2019-11-12
      - title: Assignment 10
        start: 2019-11-14
        end:   2019-11-19
      color: "#e31a1c"
    - events:
      - title: Laboratory 0
        start: 2019-09-09
      - title: Laboratory 1
        start: 2019-09-16
      - title: Laboratory 2
        start: 2019-09-23
      - title: Laboratory 3
        start: 2019-09-30
      - title: Laboratory 4
        start: 2019-10-07
      - title: Laboratory 5
        start: 2019-10-14
      - title: Overview Presentations
        start: 2019-10-21
      - title: Laboratory 6
        start: 2019-10-28
      - title: Laboratory 7
        start: 2019-11-04
      - title: Laboratory 8
        start: 2019-11-11
      - title: Laboratory 9
        start: 2019-11-18
      - title: Laboratory 10
        start: 2019-12-02
      - title: Laboratory 11
        start: 2019-12-04
      - title: Final Presentations
        start: 2019-12-16
        end:   2019-12-19
      color: "#6a3d9a"
    - events:
      - title: Iteration 0
        start: 2019-08-29
        end:   2019-09-12
      - title: Iteration 1
        start: 2019-09-12
        end:   2019-09-26
      - title: Iteration 2
        start: 2019-09-26
        end:   2019-10-10
      - title: Iteration 3
        start: 2019-10-10
        end:   2019-10-24
      - title: Iteration 4
        start: 2019-10-24
        end:   2019-11-07
      - title: Iteration 5
        start: 2019-11-07
        end:   2019-11-21
      - title: Iteration 6
        start: 2019-12-02
        end:   2019-12-19
      color: "#cab2d6"
    - events:
      - title: Labor Day
        start: 2019-09-02
      - title: Thanksgiving Vacation
        start: 2019-11-25
        end:   2019-12-02
      - title: Reading Period
        start: 2019-12-07
        end:   2019-12-11
      color: "#b15928"
  plugins:
    - dayGrid
  fixedWeekCount: false
  showNonCurrentDates: false
  header: false
  validRange:
    start: 2019-08-29
    end: 2019-12-21
  eventOrder: duration
months:
  - selector: "#calendar-august"
    <<: *default
    defaultDate: 2019-08-01
  - selector: "#calendar-september"
    <<: *default
    defaultDate: 2019-09-01
  - selector: "#calendar-october"
    <<: *default
    defaultDate: 2019-10-01
  - selector: "#calendar-november"
    <<: *default
    defaultDate: 2019-11-01
  - selector: "#calendar-december"
    <<: *default
    defaultDate: 2019-12-01
---

Calendar
========

**🚧  Work in Progress  🚧**

Deadlines are at 13:15, which is 15 minutes before the class starts. This applies both to individual assignments and to group project iterations.

We recommend that you submit individual assignments by the soft deadline (in green) to avoid overlaps with the subsequent assignment, but you may submit until the hard deadline (in red) without consequences. We don’t accept submissions after the hard deadline because by then we already started grading and publishing answers.

For administrative matters, for example, the last day to drop courses, refer to the [university’s academic calendar](https://studentaffairs.jhu.edu/registrar/wp-content/uploads/sites/23/2017/03/FINAL.academic-calendar-2019-2020.REVISED_4.29.2019.pdf).

August
------

<div id="calendar-august"></div>

September
---------

<div id="calendar-september"></div>

October
-------

<div id="calendar-october"></div>

November
--------

<div id="calendar-november"></div>

December
--------

<div id="calendar-december"></div>

<script src="fullcalendar-4.2.0/packages/core/main.min.js"></script>
<script src="fullcalendar-4.2.0/packages/daygrid/main.min.js"></script>
<link rel="stylesheet" type="text/css" href="fullcalendar-4.2.0/packages/core/main.min.css">
<link rel="stylesheet" type="text/css" href="fullcalendar-4.2.0/packages/daygrid/main.min.css">
<script>
{{ page.months | jsonify }}.forEach(({ selector, ...options }) => {
  new FullCalendar.Calendar(document.querySelector(selector), options).render();
});
</script>
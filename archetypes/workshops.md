---
title: 'Workshop {{ replace .Name "-" " " | title }}'
subtitle: ''
weight: 1
type: 'event'
draft: true

params:
  event:
    dates: ''
    location_long: ''
    location_short: ''
    year: { { .Name } }
  render:
    lists:
      display_in_lists: true
      display_on_top: true
    images:
      preview: '/events/default/workshop_list.png'
      header: ''
---

`⚠️ Note:`

`This message is only for editors. Delete this block before publishing the page.`

`Values in backticks below (dates and location) are the placeholders. Update them and remove the backsticks before publishing.`

`To learn how to customize and style an event page, please see the instructions in the`
[README file](/README-repo.md#add-a-page-for-the-event)

{{< register-button >}}

{{< text-and-image >}}
![image](/events/<year>/<event-name>/<filename>)

Markdown text.
{{< /text-and-image >}}

{{< paragraph-accent >}}
Markdown text.
{{< /paragraph-accent >}}

{{< event-timetable >}}
**Workshop 1:**

`09.12.{{ .Name }} 13:30-18:00` (Part 1)

`10.12.{{ .Name }} 08:00-12:30` (Part 2)

(limited to 40 participants)
{{< /event-timetable >}}

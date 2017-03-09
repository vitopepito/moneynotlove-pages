---
title: 'Round Table'
menu: 'Round Table'

content:
    items: '@self.children'
    order:
        by: header.event.start
        dir: desc
    dateRange:
        end: today
        field: header.event.start

upcoming:
    items: '@self.children'
    order:
        by: header.event.start
        dir: asc
    dateRange:
        start: today
        field: header.event.start

---

<header class="horizontal-center" markdown="1">

## The Creative's Round Table

Creating a socially and environmentally sustainable future.

<br />

##### We have been quiet for a while, but all is new in 2017! Join us for a series of upcoming events

<br />

</header>

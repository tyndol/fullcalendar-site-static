---
title: eventSources
since_version: 1.2
---

A way to specify multiple event sources.

<div class='spec' markdown='1'>
Array
</div>

This option is used instead of the `events` option.

You can put any number of [event arrays](events-array), [functions](events-function), [JSON feed URLs](events-json-feed), or full-out [Event Source Objects](event-source-object) into the `eventSources` array.

Here is an example calendar that displays two [JSON feeds](events-json-feed):

```js
$('#calendar').fullCalendar({
  eventSources: [
    '/feed1.php',
    '/feed2.php'
  ]
});
```

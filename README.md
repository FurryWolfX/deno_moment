# moment.ts

This moment.ts was ported from [moment@2.24.0](https://github.com/moment/moment), Hope you like it.

## Usage

Some small examples on the [moment.js](http://momentjs.com/docs/) official website:

### import

```ts
import { moment } from "https://deno.land/x/moment/moment.ts";
// or
import { moment } from "https://raw.githubusercontent.com/lisniuse/deno_moment/moment/moment.ts";
```

### Cases

```ts
// "2014-09-08T08:02:17-05:00" (ISO 8601)
moment().format();
// "Sunday, February 14th 2010, 3:25:50 pm"
moment().format("dddd, MMMM Do YYYY, h:mm:ss a");
// "Sun, 3PM"
moment().format("ddd, hA");
// "Invalid date"
moment("gibberish").format("YYYY MM DD");
```

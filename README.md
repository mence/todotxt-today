todotxt-today
=============

A super simple bash script for [todo.txt](https://github.com/ginatrapani/todo.txt-cli) that shows
you today's tasks.

Any task with `t:YYYY-MM-DD` matching today's date will be displayed.

```
$ date +%Y-%m-%d
2020-05-28
$ todo.sh list
1 2020-05-27 A task I plan to do in a days time t:2020-05-28
2 2020-05-28 A task I want to do today t:2020-05-28
3 2020-05-28 A task I want to do tomorrow t:2020-05-29
4 2020-05-28 A task without a date on it
$ todo.sh today
===================================
Tasks for today:
===================================
1 2020-05-27 A task I plan to do in a days time t:2020-05-28
2 2020-05-28 A task I want to do today t:2020-05-28
```

## Installation

Drop it in your `.todo.actions.d` folder to make it available to `todo.sh`

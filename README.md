todotxt-today
=============

A super simple bash script for [todo.txt](https://github.com/ginatrapani/todo.txt-cli) that shows
you today's tasks.

Any task with `t:YYYY-MM-DD` or` due:YYYY-MM-DD` matching today's date will be displayed.

```
$ date +%Y-%m-%d
2020-05-28
$ todo.sh list
1 2020-05-22 A task due in 6 days time due:2020-05-28
2 2020-05-27 A task I plan to do in a days time t:2020-05-28
3 2020-05-28 A task I want to do today t:2020-05-28
4 2020-05-28 A task I want to do tomorrow t:2020-05-29
5 2020-05-28 A task without a date on it
$ todo.sh today
===================================
Tasks set for today:
===================================
2 2020-05-27 A task I plan to do in a days time t:2020-05-28
3 2020-05-28 A task I want to do today t:2020-05-28
===================================
Tasks due for today:
===================================
1 2020-05-22 A task due in 6 days time due:2020-05-28
```

## Installation

Drop it in your `.todo.actions.d` folder and make it executable to make it available to `todo.sh`

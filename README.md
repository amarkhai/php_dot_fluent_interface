# Magick in PHP :)

## Just for fun)

### Can you imagine that that you can use fluent interface with dots (like in Java or JS) in PHP?
### This creepy example shows you how to do it.

Do magick with Magick class:

```PHP
$m = new Magic();

$m->setValue('2023-02-23 Hellow World')
    ->split('-')
    ->glue('_')
    ->reverse()
    ->toUpperCase()
    ->getValue()
;
```
and

```PHP
$m.setValue('2023-02-23 Hellow World')
    .split('-')
    .glue('_')
    .reverse()
    .toUpperCase()
    .getValue()
;
```

do the same things!

Change order of functions, be creative!

```PHP
$m.setValue('2023-02-23 Hellow World')
    .split('-')
    .glue('_')
    .reverse()
    .toUpperCase()
    .reverse()
    .getValue()
;
```
Works perfectly!


###### Attention! Not for use in production

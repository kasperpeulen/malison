## 0.4.3

* Make strong mode clean.

## 0.4.2

* Widen constraint on piecemeal.

## 0.4.1

* Fix semicolon handling on Firefox.

## 0.4.0

* Add constants to `CharCode` for every character in code page 437.
* Make constants `lowerCamelCase`.

## 0.3.0

* Automatically create a canvas if not given one.
* Allow creating a `UserInterface` without an initial terminal.
* Add an example app.

## 0.2.1

* Fix bad assert in `Screen._bind()`.

## 0.2.0

* Redo key input handling. Instead of a (mostly broken) `Keyboard` class, it
  exposes raw key down events as they happen and also allows user-defined
  key bindings.

* Refactor `UserInterface` and clean up how opaque/transparent screens are
  handled.

* Remove (useless) `write()` method.

* Handle semicolon keyCode difference between Firefox (59) and Chrome (186).

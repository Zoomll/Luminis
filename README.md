# Luminis

### A language made by ChatGPT

Try it here! → https://zoomll.github.io/Luminis/

Luminis is a language inspired by Lua that is interpreted by JavaScript. It was created with ChatGPT-4o and ChatGPT-4o-mini as an experiment. It has made some interesting decisions. Despite having to guide it out of some bugs, all code is written by ChatGPT. It even made a custom CSS stylesheet for it.

Currently the interpreter cannot do much, but I am working on expanding it.

## Documentation (everything that is to my knowledge possible with it)

The file name extension while likely never going to be used, would be ``.lum``.

Comments are not yet supported, but will likely use ``//`` just like in Lua.

All lines can optionally be ended with ``;``, including empty lines.

Variables are declared by ``let``.
```
let language = "Luminis";
```

Things can be printed with ``print();``.

Things can be added onto strings with ``..``. Numbers can also be added with ``+`` OR ``..``.
```
let age = 1;
let lang = "Luminis";

print("Age: "+age);
print("Language: "..lang);
```

Arithmetic can be done with ``+``, ``-``,``*``, and ``/``. The Order of Operations do work.

Booleans can also be gotten from arithmetic using ``==``, ``>``, ``<``, ``>=``, ``<=``, and ``!=``. This means that variables can be assigned to conditions.
```
let x = 1;
let y = x + 1;
let bool = x > y
```

Conditional statements use ``if``, ``else``, and ``end``. They check if the value in front of ``if`` is true or false. If an ``else`` is found and ``false`` is the value in front of the ``if`` the ``else`` will be executed.
```
let x = 0
let y = x
let safe = x <= y

if safe
    let y = y + 1
    let safe = x <= y
end
```

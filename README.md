# Luminis

### A language made by ChatGPT

Try it here! → https://zoomll.github.io/Luminis/

Luminis is a language inspired by Lua that is interpreted by JavaScript. It was created with ChatGPT-4o and ChatGPT-4 as an experiment. It has made some interesting decisions. I had to guide it out of some bugs though.

Currently the interpreter cannot do much, but I am working on expanding it.

## Documentation (a little lack luster rn)

All lines can optionally be ended with ``;``, including empty lines.

Variables are declared by ``let``.
```
let language = "Luminis"
```

Things can be printed with ``print()``.

Things can be added onto strings with ``..``. Numbers can also be added with ``+`` OR ``..``.
```
let age = 1
let lang = "Luminis"

print("Age: "+age)
print("Language: "..lang)
```

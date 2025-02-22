---
title:  "Brainfuck"
layout: post
---

Brainfuck has one of the smallest compilers among all other software languages. That's why it's known as one of the smallest software languages in the world(for now :). 

- [ - ] is the smallest program written in this language.
- ASCII Table is used for the character mapping.

Basically it has 8 program instructions as the following:


## Instructions of Brainfuck

| Brainfuck Command | C equivalent |
| ------ | ------ |
| (Program Start) | char array[30000] = {0}; char *ptr = &array[0]; |
| > | ++ptr; |
| < | --ptr; |
| + | ++*ptr; |
| - | --*ptr; |
| . | putchar(*ptr); |
| , | *ptr=getchar(); |
| [ | while (*ptr) { |
| ] | } |

## A Sample Program
> Note: Any [online compiler] can be used to execute.

```sh
//Initialize 27 characters for the ASCII message.
+++++ +++++ +++++ +
[
    >+++++ >+++++ >+++++ >+++++ >+++++ >+++++
    >+++++ >+++++ >+++++ >+++++ >+++++ >+++++
    >+++++ >+++++ >+++++ >+++++ >+++++ >+++++
    >+++++ >+++++ >+++++ >+++++ >+++++ >+++++
    >+++++ >+++++ >+++++
<<<<< <<<<< <<<<< <<<<< <<<<< <<-
]

//Set the specific ASCII characters.
>+++++ ++++
>-
>+++++
>++++++++++++++++
>++
>-----------
>------------------------------------------------
>+++
>++++
>-------
>----
>----
>------------------------------------------------
>---------------
>----
>-------
>++++++
>-----------
>---------------------
>---------------------------------------
>------------------------------------------------
>-----------
>--
>------
>-
>+++++++++
>-----------------------------------------------

//First cell of the message.
<<<<< <<<<< <<<<< <<<<< <<<<< <<- 

//Print out.
[
    >.
]
```

## References
[https://en.wikipedia.org/wiki/Brainfuck][1]  
[https://www.jdoodle.com/execute-brainfuck-online/][2]

[1]: https://en.wikipedia.org/wiki/Brainfuck
[2]: https://www.jdoodle.com/execute-brainfuck-online/
[online compiler]: <https://www.jdoodle.com/execute-brainfuck-online/>

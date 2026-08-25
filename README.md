# Moritisimor

![Go Badge](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white&style=for-the-badge)
![Ocaml Badge](https://img.shields.io/badge/OCaml-EC6813?logo=ocaml&logoColor=fff&style=for-the-badge)
![Rust Badge](https://img.shields.io/badge/Rust-121212?style=for-the-badge&logo=rust&logoColor=white)
![Python Badge](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C Badge](https://img.shields.io/badge/C-121212?style=for-the-badge&logo=c&logoColor=white)
![JavaScript Badge](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000&style=for-the-badge)

![Profile Views](https://komarev.com/ghpvc/?username=Moritisimor&style=flat-square&color=grey)

## Who am I?
I am a hobby developer from Germany.

I mainly use Go, Python and Rust, but I know other languages as well, such as JavaScript, Java and a bit of C.

You can contact me at `devMoritisimor@proton.me`

## My best projects
### [nomad-lisp](https://github.com/Moritisimor/nomad-lisp)
An interpreter for my own LISP dialect written in Ocaml.

Arguably my coolest and biggest project so far.

Nomad is a Lisp-like language with a focus on simplicity. 

The reference implementation in OCaml is remarkably simple, and, as such, the parser is only 40 lines of code.

It supports lexically-scoped closures, higher order functions, and thus currying, as well as recursion, which is the default way of looping.

There are also other implementations of it:
- [gomad](https://github.com/Moritisimor/gomad)
- [romad](https://github.com/robertflexx/romad)
- [bomad](https://github.com/robertflexx/bomad)

### [RFetch](https://github.com/Moritisimor/rfetch)
A rather simple CLI HTTP Client written in Rust.

I made it primarily for my own workflows when calling APIs. 

It's primarily supposed to be a simple-to-use CLI HTTP Client for working with JSON-based RESTful APIs.

However, it can of course be used for other things.

### [HexFlex](https://github.com/Moritisimor/hexflex)
CLI-based Hex Editor written in Rust.

Kind of reverse-engineering light. Although it's definitely not as powerful as other reverse-engineering/decompilation tools, HexFlex is simpler and easier to get started with.

It doesn't make assumptions about the file you're viewing. You just get raw bytes and some commands for viewing, querying and manipulating raw bytes.

### [Neo-Ed](https://github.com/Moritisimor/Neo-Ed)
My own take on line-based editing, written in Go.

Inspired by the original UNIX editor ed, but with a more modern, intuitive interface and more helpful error messages.

### [SaturnJS](https://github.com/Moritisimor/SaturnJS)
A Goja-based JavaScript runtime that's not made for running on a browser or on a server. 

Instead, it's kinda like Perl, mainly made for System-scripting.

It includes a library for making HTTP Requests, interacting with SQLite databases, colorizing strings, terminal-based I/O and more to come in the future.

### [Open-TTS-App](https://github.com/Moritisimor/Open-TTS-App)
A very simple web application for synthesizing speech from text.

Its backend is written in Python using the FastAPI framework for the REST API and PiperTTS for speech synthesis.

The frontend is written in Vanilla JavaScript. Not every app needs a framework.

You can also pull it as a docker image and easily run it locally.

### [MoleculeVM](https://github.com/KokoFlexxImor/MoleculeVM)
A joint project consisting of me and [RobertFlexx](https://github.com/RobertFlexx).

This Virtual Machine was started by me as a small project. The goal was simple: a tiny, 8-bit based Stack-Machine in C.

However, Robert, being the pioneer he is, massively expanded the project, adding 16-bit and even 32-bit extensions, as well as a compiler for a whole language.

Though I am not as actively involved in the project anymore, I did write the disassembler in OCaml later on.

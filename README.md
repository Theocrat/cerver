# CERVER

HTTP server framework in C

## Introduction

I have used Flask on Python, and I sometimes miss its raw simplicity when working in C. 
So this repository is a simple set of structures and functions to implement HTTP servers
in the C programming language.

## Mode of Operation

This server framework uses `pthread` and `socket`. It provides the option of mapping 
routes to functions using function pointers. It also provides a nice interface for reading
GET and POST requests. Eventually PUT, DELETE, and other verbs shall also be implemented.

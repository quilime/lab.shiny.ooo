---
layout: event
title: Hacking Binary Executables
upcoming: true
class_date: 2013-10-21
start: 1pm
end: 5pm
location: San Francisco, CA
registration_url: http://register
fee_list: [["Students", 	"$60"],
           ["Freelancers", 	"$120"],
           ["Corporate", 	"$220"]]
instructor: Joshua Nimoy
---
Hacking binary executables:

- overview of changing a program without knowing the source
- what's basically entailed
- why cracking is less of a threat
- compile a simple C hello world.
- open in hex editor and place a zero prematurely into a string.
- discuss why placing a zero byte works with strings.
- headers, segments
- what really happens inside a C compiler (whiteboard nutshell)
- difference between "compiling" and "assembling"
- Hello Hopper
- tour of C hello world in assembly
- NOPPING removing an instruction completely
- recent optimizations in nopping
- injecting a return from function
- remember to pop the stack pointer.
- injecting a "jump" instruction to create a loop.
- remember it's a a local address, not in the data segment.
- breakpoint debugging to find your place in the code.
- nopping a popup dialog.
- Discussion of expanding code and data segments
- why would you need to do that?
- what would it take?
- libmacho
- http://www.openrce.org/forums/posts/1275
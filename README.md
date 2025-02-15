# Project Based Tutorials in C

A list of tutorials that work towards the making of a complete project in C.

## Table of Contents

* [Computer Architecture](#computer-architecture)
* [Computer Networking](#computer-networking)
* [Databases](#databases)
* [Game Development](#game-development)
* [Operating Systems](#operating-systems)
* [Programming Languages](#programming-languages)
* [Uncategorized](#uncategorized)

## Computer Architecture

#### Emulator
* [Emulator 101](http://emulator101.com/)
* [Gameboy Emulator Development](https://www.youtube.com/playlist?list=PLVxiWMqQvhg_yk4qy2cSC3457wZJga_e5) `video`
* Writing a Chip 8 Emulator `in-progress`
    * [Part 1](http://craigthomas.ca/blog/2014/06/21/writing-a-chip-8-emulator-part-1/)
    * [Part 2](http://craigthomas.ca/blog/2014/07/17/writing-a-chip-8-emulator-part-2/)
    * [Part 3](http://craigthomas.ca/blog/2015/02/19/writing-a-chip-8-emulator-draw-command-part-3/)
    * [Part 4](http://craigthomas.ca/blog/2017/10/15/writing-a-chip-8-emulator-built-in-font-set-part-4/)
    * [Part 5](http://craigthomas.ca/blog/2018/09/07/writing-a-chip-8-emulator-instruction-set-part-5/)
* [Writing a Game Boy emulator](https://cturt.github.io/cinoop.html)
    
#### Virtual Machine
* [Implementing a Virtual Machine in C](https://felixangell.com/blogs/virtual-machine-in-c)
* [Write your Own Virtual Machine](https://justinmeiners.github.io/lc3-vm/)
    
#### Other
* [Bitwise](https://github.com/pervognsen/bitwise) `video` `abandoned`

## Computer Networking

* [Beej's Guide to Network Programming](https://beej.us/guide/bgnet/html//index.html) `book`
* [Concurrent Servers](https://eli.thegreenplace.net/2017/concurrent-servers-part-1-introduction/)
* [HTTP Server: Everything you need to know to Build a simple HTTP server from scratch](https://medium.com/from-the-scratch/http-server-what-do-you-need-to-know-to-build-a-simple-http-server-from-scratch-d1ef8945e4fa)
* Let's code a TCP/IP stack
    * [Part 1: Ethernet & ARP](http://www.saminiir.com/lets-code-tcp-ip-stack-1-ethernet-arp/)
    * [Part 2: IPv4 & ICMPv4](http://www.saminiir.com/lets-code-tcp-ip-stack-2-ipv4-icmpv4/)
    * [Part 3: TCP Basics & Handshake](http://www.saminiir.com/lets-code-tcp-ip-stack-3-tcp-handshake/)
    * [Part 4: TCP Data Flow & Socket API](http://www.saminiir.com/lets-code-tcp-ip-stack-4-tcp-data-flow-socket-api/)
    * [Part 5: TCP Retransmission](http://www.saminiir.com/lets-code-tcp-ip-stack-5-tcp-retransmission/)
* [Let's make a NTP Client in C](https://lettier.github.io/posts/2016-04-26-lets-make-a-ntp-client-in-c.html)
* Write an MQTT broker from scratch
    * [Part 1 - The protocol](https://codepr.github.io/posts/sol-mqtt-broker)
    * [Part 2 - Networking](https://codepr.github.io/posts/sol-mqtt-broker-p2)
    * [Part 3 - Server](https://codepr.github.io/posts/sol-mqtt-broker-p3)
    * [Part 4 - Data structures](https://codepr.github.io/posts/sol-mqtt-broker-p4)
    * [Part 5 - Topic abstraction](https://codepr.github.io/posts/sol-mqtt-broker-p5)
    * [Part 6 - Handlers](https://codepr.github.io/posts/sol-mqtt-broker-p6)

## Databases

* [Let's Build a Simple Database](https://cstack.github.io/db_tutorial/)

## Game Development

#### Game Consoles
* [How to Program an NES game in C](https://nesdoug.com/)
* [Learn How To Develop Your Own GameBoy Games](https://www.youtube.com/playlist?list=PLeEj4c2zF7PaFv5MPYhNAkBGrkx4iPGJo) `video` `in-progress`
* [Writing a Game Boy Advance Game](https://www.reinterpretcast.com/writing-a-game-boy-advance-game)

#### OpenGL (GLFW/GLEW)
* Space Invaders from Scratch (C/C++)
    * [Part 1](http://nicktasios.nl/posts/space-invaders-from-scratch-part-1.html)
    * [Part 2](http://nicktasios.nl/posts/space-invaders-from-scratch-part-2.html)
    * [Part 3](http://nicktasios.nl/posts/space-invaders-from-scratch-part-3.html)
    * [Part 4](http://nicktasios.nl/posts/space-invaders-from-scratch-part-4.html)
    * [Part 5](http://nicktasios.nl/posts/space-invaders-from-scratch-part-5.html)

#### SDL (Simple DirectMedia Layer)
* [Create a Game Loop using C and SDL](https://www.udemy.com/course/game-loop-c-sdl/) `course`
* [Learn Video Game Programming in C](https://www.youtube.com/playlist?list=PLT6WFYYZE6uLMcPGS3qfpYm7T_gViYMMt) `video`
* [Let's Make: Dangerous Dave](https://www.youtube.com/playlist?list=PLSkJey49cOgTSj465v2KbLZ7LMn10bCF9) `video`
* Let's make Tetris with SDL `video` `abandoned`
    * [Part 1 - Linking with SDL](https://www.youtube.com/watch?v=AHp6CdCx058)
    * [Part 2 - Creating a Window](https://www.youtube.com/watch?v=INhX23hkcM8)
    * [Part 3 - Creating the Renderer](https://www.youtube.com/watch?v=DIOVD-wEzDU)
    * [Part 4 - Drawing a board](https://www.youtube.com/watch?v=m69YNzFgfkw)
* SDL2 Game Tutorials
    * [Creating a 2D platformer](https://www.parallelrealities.co.uk/tutorials/#ppp)
    * [Creating a 2D shoot 'em up](https://www.parallelrealities.co.uk/tutorials/#shooter)
    * [Creating a 2D top-down shooter](https://www.parallelrealities.co.uk/tutorials/#bad)
    * [Creating a Sprite Atlas](https://www.parallelrealities.co.uk/tutorials/#atlas)
    * [Working with TTF Fonts](https://www.parallelrealities.co.uk/tutorials/#ttf)
    * [Creating a Simple 2D Adventure Game](https://www.parallelrealities.co.uk/tutorials/#adventure)
    * [Creating a Basic Widget System](https://www.parallelrealities.co.uk/tutorials/#widgets)
    * [Creating a 2D Vertical Shoot'em Up Game](https://www.parallelrealities.co.uk/tutorials/#shooter2)
    * [Creating a 2D Run and Gun Game](https://www.parallelrealities.co.uk/tutorials/#gunner)
    * [Creating a Roguelike Game](https://www.parallelrealities.co.uk/tutorials/#rogue)
    * [Creating a Lookup System](https://www.parallelrealities.co.uk/tutorials/#lookups)
    * [Creating a In-game Achievement System](https://www.parallelrealities.co.uk/tutorials/#medals)
* [SDL 2 Isometric Game Tutorial](https://www.youtube.com/playlist?list=PL6Ikt4l3NbVjb7WR-eTgjOBMNCn7f3u7x) `video`
* [Tic-tac-toe Game in C with SDL](https://www.youtube.com/watch?v=gCVMkKgs3uQ) `video`
* [Write The Old-School Fire Effect and Bare-Metal Programming in Assembly and C](https://www.hanshq.net/fire.html)
* [Writing 2D Games in C using SDL](https://www.youtube.com/watch?v=yFLa3ln16w0) `video`

#### Text-Based (CLI/ASCII/ncruses)
* [Chess Engine In C](https://www.youtube.com/playlist?list=PLZ1QII7yudbc-Ky058TEaOstZHVbT-2hg) `video`
* [Coding A Sudoku Solver in C](https://www.youtube.com/playlist?list=PLkTXsX7igf8edTYU92nU-f5Ntzuf-RKvW) `video`
* [Coding a Rogue/Nethack RPG in C](https://www.youtube.com/playlist?list=PLkTXsX7igf8erbWGYT4iSAhpnJLJ0Nk5G) `video`
* [Games programming from the ground up with C](https://laurencescotford.com/games-programming-from-the-ground-up-with-c-index/)
* [Hangman](https://www.youtube.com/playlist?list=PLZ1QII7yudbd2ZHYSEWrSddsvD5PW_r5O) `video`
* [How to Program a Text Adventure in C](https://helderman.github.io/htpataic/htpataic01.html) `in-progress`
* [Implementing Solitaire in C](https://jborza.com/post/2020-07-12-solitaire-cli/)
* [On Tetris and Reimplementation](https://brennan.io/2015/06/12/tetris-reimplementation/)
* [Simple Tic Tac Toe in C](https://www.youtube.com/playlist?list=PLZ1QII7yudbc7_ZgXA-gIXmME41Rs2GP5) `video`
* Text Adventure `video` `abandoned`
    * [Episode 1](https://www.youtube.com/watch?v=7dYKhiruW1M)
    * [Episode 2](https://www.youtube.com/watch?v=7dYKhiruW1M)
* [The C Roguelike Tutorial Series](https://dev.to/ignaoya/series/13852)

#### Win32 (Windows API)
* [Handmade Hero](https://handmadehero.org/) `video` `in-progress` (C/C++)
* [Making a game in C from scratch](https://www.youtube.com/playlist?list=PL7Ej6SUky1357r-Lqf_nogZWHssXP-hvH) `video`
* [Making a Video Game from Scratch in C](https://www.youtube.com/playlist?list=PLlaINRtydtNWuRfd4Ra3KeD6L9FP_tDE7) `video` `in-progress`

#### Other
* [Astroids Clone](https://gtk.dashgl.com/Astroids/)
* [Brickout Clone](https://gtk.dashgl.com/Brickout/)
* Embedded Game Programming
    * [Part 0: Motivation](https://austinmorlan.com/posts/embedded_game_programming_0/) 
    * [Part 1: Build System](https://austinmorlan.com/posts/embedded_game_programming_1/)
    * [Part 2: Input](https://austinmorlan.com/posts/embedded_game_programming_2/)
    * [Part 3: Display](https://austinmorlan.com/posts/embedded_game_programming_3/)
    * [Part 4: Storage](https://austinmorlan.com/posts/embedded_game_programming_4/)
    * [Part 5: Battery](https://austinmorlan.com/posts/embedded_game_programming_5/)
    * [Part 6: Audio](https://austinmorlan.com/posts/embedded_game_programming_6/)
    * [Part 7: Text](https://austinmorlan.com/posts/embedded_game_programming_7/)
    * [Part 7: Tile System](https://austinmorlan.com/posts/embedded_game_programming_8/)
* [Invaders Clone](https://gtk.dashgl.com/Invaders/)
* Video Game Physics Tutorial
    * [Part I: An Introduction to Rigid Body Dynamics](https://www.toptal.com/game/video-game-physics-part-i-an-introduction-to-rigid-body-dynamics)
    * [Part II: Collision Detection for Solid Objects](https://www.toptal.com/game/video-game-physics-part-ii-collision-detection-for-solid-objects)
    * [Part III: Constrained Rigid Body Simulation](https://www.toptal.com/game/video-game-physics-part-iii-constrained-rigid-body-simulation)
* [Write Othello Game from scratch in C](https://www.hanshq.net/othello.html)

## Operating Systems

* [Build a minimal multi-tasking OS kernel for ARM from scratch](https://github.com/jserv/mini-arm-os)
* [Build Your Own Shell](https://github.com/tokenrove/build-your-own-shell)
* [Building an Operating System for the Raspberry Pi](https://jsandler18.github.io/)
* [Hack the Virtual Memory](https://blog.holbertonschool.com/hack-virtual-memory-stack-registers-assembly-code/)
* [How to Write a Bootloader from Scratch](https://interrupt.memfault.com/blog/how-to-write-a-bootloader-from-scratch)
* [How to Create an OS from Scratch](https://github.com/cfenollosa/os-tutorial) `in-progress`
* [Learning KVM - implement your own kernel](https://david942j.blogspot.com/2018/10/note-learning-kvm-implement-your-own.html)
* [Learning operating system development using Linux kernel and Raspberry Pi](https://github.com/s-matyukevich/raspberry-pi-os) `in-progress`
* [Let's build a shell!](https://github.com/kamalmarhubi/shell-workshop)
* [Let's Write a Malloc](https://danluu.com/malloc-tutorial/)
* Let’s write a Kernel
    * [Part 1 - Kernel 101](https://arjunsreedharan.org/post/82710718100/kernel-101-lets-write-a-kernel)
    * [Part 2 - Kernel 201](https://arjunsreedharan.org/post/99370248137/kernel-201-lets-write-a-kernel-with-keyboard)
* [Linux Containers in 500 Lines of Code](https://blog.lizzie.io/linux-containers-in-500-loc.html)
* [Operating systems development for Dummies](https://medium.com/@lduck11007/operating-systems-development-for-dummies-3d4d786e8ac)
* [Operating Systems: From 0 to 1](https://tuhdo.github.io/os01/) `book`
* [OS161: Everything you need to learn about operating systems](https://www.ops-class.org/) `course`
* Re-Writing BSD 4.4 Shell Commands: `video`
    * [cat](https://www.youtube.com/watch?v=MCuzvy79WWQ)
    * [chmod](https://www.youtube.com/watch?v=p7uJBl4A_BA)
    * [echo](https://www.youtube.com/watch?v=69CYF7nJKj8)
    * [mkdir](https://www.youtube.com/watch?v=t96qYd4OUBM)
* [Roll your own toy UNIX-clone OS](http://www.jamesmolloy.co.uk/tutorial_html/)
* [The little book about OS development](https://littleosbook.github.io/) `book`
* [Write a Shell in C](https://brennan.io/2015/01/16/write-a-shell-in-c/)
* [Write a Simple Memory Allocator](https://arjunsreedharan.org/post/148675821737/write-a-simple-memory-allocator)
* [Write a System Call](https://brennan.io/2016/11/14/kernel-dev-ep3/)
* [Writing a "bare metal" operating system for Raspberry Pi 4](https://github.com/isometimes/rpi4-osdev)
* [Writing a FUSE Filesystem](https://www.cs.nmsu.edu/~pfeiffer/fuse-tutorial/)
* [Writing a shell in C](https://danishpraka.sh/2018/01/15/write-a-shell.html)
* Writing a Unix Shell
   * [Part 1](https://indradhanush.github.io/blog/writing-a-unix-shell-part-1)
   * [Part 2](https://indradhanush.github.io/blog/writing-a-unix-shell-part-2)
   * [Part 3](https://indradhanush.github.io/blog/writing-a-unix-shell-part-3)

## Programming Languages

* [A Compiler Writing Journey](https://github.com/DoctorWkt/acwj)
* [A Regular Expression Matcher](https://www.cs.princeton.edu/courses/archive/spr09/cos333/beautiful.html)
* [A Regular Expression Matching Can Be Simple And Fast](https://swtch.com/~rsc/regexp/regexp1.html)
* [Baby's First Garbage Collector](http://journal.stuffwithstuff.com/2013/12/08/babys-first-garbage-collector/)
* [Build Your Own Lisp](https://www.buildyourownlisp.com/) `book`
* [Compiler Design in C](https://holub.com/goodies/compiler/compilerDesignInC.pdf) `book`
* [Crafting Interpreters](https://www.craftinginterpreters.com/) `book` (Chapters 14 - 30)
* [Let's Build a Compiler: A C & x86 version](https://github.com/lotabout/Let-s-build-a-compiler)
* Let's Write a Compiler
    * [Part 1: Introduction, selecting a language, and doing some planning](https://briancallahan.net/blog/20210814.html)
    * [Part 2: A lexer](https://briancallahan.net/blog/20210815.html)
    * [Part 3: A parser](https://briancallahan.net/blog/20210816.html)
    * [Part 4: Testing](https://briancallahan.net/blog/20210817.html)
    * [Part 5: A code generator](https://briancallahan.net/blog/20210818.html)
    * [Part 6: Input and output](https://briancallahan.net/blog/20210819.html)
    * [Part 7: Arrays](https://briancallahan.net/blog/20210822.html)
    * [Part 8: Strings, forward references, and conclusion](https://briancallahan.net/blog/20210826.html)
* Write a C Interpreter
    * [Part 0 - Preface](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/0-Preface.md)
    * [Part 1 - Skeleton](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/1-Skeleton.md)
    * [Part 2 - Virtual Machine](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/2-Virtual-Machine.md)
    * [Part 3 - Lexer](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/3-Lexer.md)
    * [Part 4 - Top-down Parsing](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/4-Top-down-Parsing.md)
    * [Part 5 - Variables](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/5-Variables.md)
    * [Part 6 - Functions](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/6-Functions.md)
    * [Part 7 - Statements](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/7-Statements.md)
    * [Part 8 - Expressions](https://github.com/lotabout/write-a-C-interpreter/blob/master/tutorial/en/8-Expressions.md)
* Writing a C Compiler `in-progress`
    * [Part 1](https://norasandler.com/2017/11/29/Write-a-Compiler.html)
    * [Part 2](https://norasandler.com/2017/12/05/Write-a-Compiler-2.html)
    * [Part 3](https://norasandler.com/2017/12/15/Write-a-Compiler-3.html)
    * [Part 4](https://norasandler.com/2017/12/28/Write-a-Compiler-4.html)
    * [Part 5](https://norasandler.com/2018/01/08/Write-a-Compiler-5.html)
    * [Part 6](https://norasandler.com/2018/02/25/Write-a-Compiler-6.html)
    * [Part 7](https://norasandler.com/2018/03/14/Write-a-Compiler-7.html)
    * [Part 8](https://norasandler.com/2018/04/10/Write-a-Compiler-8.html)
    * [Part 9](https://norasandler.com/2018/06/27/Write-a-Compiler-9.html)
    * [Part 10](https://norasandler.com/2019/02/18/Write-a-Compiler-10.html)
* [Writing a Simple Garbage Collector in C](http://maplant.com/gc.html)
* Scheme from Scratch
    * [Part 1 - Introduction](http://peter.michaux.ca/articles/scheme-from-scratch-introduction)
    * [Part 2 - Integers](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_1-integers)
    * [Part 3 - Booleans](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_2-booleans)
    * [Part 4 - Characters](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_3-characters)
    * [Part 5 - Strings](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_4-strings)
    * [Part 6 - The Empty List](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_5-the-empty-list)
    * [Part 7 - Pairs](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_6-pairs)
    * [Part 8 - Symbols](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_7-symbols)
    * [Part 9 - Quote](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_8-quote)
    * [Part 10 - Environments](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_9-environments)
    * [Part 11 - if](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_10-if)
    * [Part 12 - Primitive Procedures Part 1](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_11-primitive-procedures-part-1)
    * [Part 13 - Primitive Procedures Part 2](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_12-primitive-procedures-part-2)
    * [Part 14 - Lambda the Ultimate](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_13-lambda-the-ultimate)
    * [Part 15 - Begin](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_14-begin)
    * [Part 16 - Cond](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_15-cond)
    * [Part 17 - Let](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_16-let)
    * [Part 18 - And and Or](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_17-and-and-or)
    * [Part 19 - Apply](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_18-apply)
    * [Part 20 - Eval](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_19-eval)
    * [Part 21 - I/O](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_20-io)
    * [Part 22 - Standard Library](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_21-standard-library)
    * [Part 23 - Garbage Collection](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-v0_22-garbage-collection)
    * [Part 24 - Conclusion](http://peter.michaux.ca/articles/scheme-from-scratch-bootstrap-conclusion)

## Uncategorized

* A dummy blockchain implementation in C
   * [Part 1](https://myram.xyz/c-blockchain-implementation-1/)
   * [Part 2](https://myram.xyz/c-blockchain-implementation-2/)
* [Build Your Own Text Editor](https://viewsourcecode.org/snaptoken/kilo/)
* [How to Write a Video Player in Less Than 1000 Lines](http://dranger.com/ffmpeg/ffmpeg.html) `abandoned`
* [Learn FFmpeg libav the Hard Way](https://github.com/leandromoreira/ffmpeg-libav-tutorial) `in-progress`
* [Write a hash table in C](https://github.com/jamesroutley/write-a-hash-table)
* [Write BigInt Calculator in C](https://www.hanshq.net/bigint.html)
* [Write Your Own Zip from scratch in C](https://www.hanshq.net/zip.html)
* [Writing an SVG Library](http://www.codedrome.com/svg-library-in-c/)

---
title: "How Programs Execute: BTS"
date: 2023-09-20
categories:
  - blog
tags:
  - programming
  - chrome
  - program
  - machine code
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
toc_sticky: true
---

![image-center](/assets/how-program-executes/Computer-programmer.jpeg){: .align-center}

Have you ever marveled at the magic behind your computer screen, wondering how the software you use daily comes to life? In an age where technology seamlessly integrates into our lives, the inner workings of computer programs remain a fascinating enigma for many. It's easy to take for granted the applications, games, and tools that make our digital world thrive, but understanding the intricate dance of code and hardware that powers them is a journey worth embarking upon.

In this blog post, we'll peel back the curtain and take you on a journey into the heart of software execution. We'll unravel the secrets of how programs, from simple "Hello, World!" scripts to complex software applications, transform lines of code into tangible actions on your computer. Join us as we demystify the fascinating realm of programming and explore the behind-the-scenes processes that make our digital lives possible. Whether you're a curious beginner or a seasoned developer, this journey promises to enlighten and deepen your appreciation for the world of software engineering. So, fasten your seatbelts and get ready to dive into the inner workings of the digital realm!

Before diving deep into micros let's understand some key components like Machine code, Software, Program etc.

## What is Machine Code?

Machine code, also known as machine language, is a low-level programming language that directly corresponds to the architecture and instruction set of a computer's central processing unit (CPU). It is the lowest level of programming language and is essentially a binary representation of instructions that the computer's CPU can execute.

Machine code consists of a series of binary digits (0s and 1s) that represent specific instructions for the computer's CPU. Each instruction corresponds to a particular operation, such as arithmetic calculations, data movement, or control flow operations. Machine code instructions are specific to the computer's hardware architecture, and different CPU architectures have their own unique instruction sets.

Here are a few key points about machine code:

1. **Binary Representation:** Machine code instructions are represented in binary form, where each combination of 0s and 1s represents a specific operation, such as adding two numbers or moving data from one memory location to another.

2. **Hardware-Specific:** Machine code is closely tied to the hardware of a particular computer or CPU. Programs written in machine code are not portable and can only run on the specific hardware for which they are written.

3. **Low-Level:** Machine code is a low-level language, meaning it is difficult for humans to read and write directly. Programmers typically use higher-level languages, like assembly language or high-level programming languages, to write software.

4. **Fast Execution:** Programs written in machine code can be extremely fast and efficient because they are executed directly by the CPU without the need for translation or interpretation.

5. **Debugging Challenges:** Debugging machine code can be challenging due to its binary nature. Programmers often use debugging tools and techniques to assist in identifying and fixing errors in machine code programs.

While machine code is not commonly used for writing software today due to its complexity and lack of portability, it is the foundation upon which all higher-level programming languages and software development tools are built. Compilers and assemblers are used to translate higher-level code (e.g., C, C++) into machine code that can be executed by a computer's CPU, making it more accessible to programmers and allowing for the development of a wide range of software applications.

## What is a Software?

"Software" is like the music played by a player piano, which represents the instructions for a computer's hardware. When we talk about software, we often mean specific programs like Firefox, which you use to do things on your computer.

Computers can run several programs at once, and they make sure each program's stuff is kept separate.

Now, the computer's brain, called the CPU, understands a language called "machine code." It's like the CPU's native tongue, and it's built into the computer's hardware. Each group of similar CPUs (like Intel processors) has its own unique way of speaking this machine code, and they can't understand each other's languages.

## What is a Program?

Machine code is like a computer's basic language. It consists of simple instructions, like adding numbers or checking if a number is zero, and each of these instructions is incredibly basic and takes up only a few bytes of storage. When we say a CPU can do 2 billion operations per second, it means it can process 2 billion of these simple instructions in one second.

Now, a program like Chrome is made up of millions of these basic machine code instructions. It might seem surprising that something as complex as a web browser can be built from such simple instructions, but it's similar to how a detailed sand sculpture is made from individual grains of sand – when you put many simple things together in the right way, you can create something intricate and sophisticated.

## How Does a Program Run?

Refer the diagram for better understanding.
{: .notice--info}

![]({{site.url}}/assets/how-program-executes/program_executes.png)

The CPU operates in a repeating cycle known as the "fetch-execute" cycle. It starts by grabbing the first instruction, carries out that instruction (such as adding numbers), then moves on to fetch and execute the next one, and so forth. Some instructions can alter the sequence of instructions the CPU follows. For example, an instruction might instruct the CPU to return to a previous point in the instruction sequence (a common way to create loops) or to skip the next instruction if a specific condition is met (typically used for if-statements). This cycle ensures that the CPU consistently processes a series of instructions to accomplish tasks in a program.

### Conclusion?

In conclusion, As you navigate the digital landscape, whether as a curious explorer or an aspiring developer, understanding the inner workings of program execution can enhance your appreciation for the technology that surrounds us. Whether you're crafting the next groundbreaking application or simply enjoying the convenience of modern software, remember that behind every click and command lies a world of code, ready to execute and bring your digital desires to life. So, embrace the magic of program execution, and may your programming adventures continue to illuminate the path forward in the ever-evolving realm of technology.

Thank you for visiting, and I look forward to connecting with you and exploring the boundless world of software engineering and innovation.

[<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f8/LinkedIn_icon_circle.svg/1200px-LinkedIn_icon_circle.svg.png" width="45"/>](https://linkedin.com/in/praveensingh23)
[<img src="https://s18955.pcdn.co/wp-content/uploads/2018/02/github.png" width="45"/>](https://github.com/praveensinghrajput23)
[<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/58/Instagram-Icon.png/1024px-Instagram-Icon.png" width="45"/>](https://instagram.com/praveensinghrajput23)
[<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQYAFvsvvSz-ywpPupKs56YpRxW-C6OuOg8Jw&usqp=CAU" width="65"/>](https://twitter.com/_praveensingh23)

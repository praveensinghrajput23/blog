---
title: "Linux and Unix: A Beginner Guide"
date: 2023-09-07T13:04:56
categories:
  - tutorial
tags:
  - linux
  - unix
  - ubuntu
  - command
toc: true
toc_label: "Table of Contents"
excerpt: In the realm of operating systems, two names stand out as giants in the world of computing - Linux and Unix.
---

## Introduction

In the realm of operating systems, two names stand out as giants in the world of computing - Linux and Unix. These open-source powerhouses have been driving innovation and serving as the backbone of countless servers, workstations, and embedded systems for decades. If you've ever wondered what sets them apart, how they work, and why they matter, you're in the right place.

In this blog post, we'll embark on a journey through the fascinating world of Linux and Unix. We'll explore their history, fundamental concepts, key differences, and the essential roles they play in the world of technology. Whether you're a seasoned sysadmin or a curious beginner, this guide will help you gain a deeper understanding of these robust and influential operating systems.

## What is UNIX?

UNIX is an operating system which was first developed in the 1960s, and has been under constant development ever since. By operating system, we mean the suite of programs which make the computer work. It is a stable, multi-user, multi-tasking system for servers, desktops and laptops.

UNIX systems also have a graphical user interface (GUI) similar to Microsoft Windows which provides an easy to use environment. However, knowledge of UNIX is required for operations which aren't covered by a graphical program, or for when there is no windows interface available, for example, in a telnet session.
There are many different versions of UNIX, although they share common similarities. The most popular varieties of UNIX are Sun Solaris, GNU/Linux, and MacOS X.

The UNIX operating system is made up of three parts; the kernel, the shell and the programs.

## What is Kernal?

The kernel of UNIX is the hub of the operating system: it allocates time and memory to programs and handles the filestore and communications in response to system calls.

As an illustration of the way that the shell and the kernel work together, suppose a user types `rm myfile` (which has the effect of removing the file myfile). The shell searches the filestore for the file containing the program rm, and then requests the kernel, through system calls, to execute the program rm on myfile. When the process `rm myfile`has finished running, the shell then returns the UNIX prompt % to the user, indicating that it is waiting for further commands.

## What is Shell?

- The shell acts as an interface between the user the kernal.
- The shell is a command kine interface (CLI). It interprets the commands the user types in and arranges for them to be carried out.
- The adepts user can customize his/her own shell, and users can use different shells on the same machine.

**Note:** Everything in unix either file or process.
{: .notice--info}

## Unix directory structure

![]({{site.url}}/assets/linux-and-unix-tutorial/directory-tree.gif)

Soon I will post in-depth blog on Linux direcotory structure
{: .notice}

###### Now let's explore some basic command about listing and directories and know what they do:

To learn more about the available command options, you can use the `--help` or `--options flag`.
{: .notice--info}

- To list down files and folders (excluding hidden ones)

```bash
ls
```

<sub>_use `-a` or `--all` to view hidden files too_</sub>

- To create a sub-directory in the current directory.

```bash
mkdir `directory_name`
```

- Navigate to directory using.

```bash
cd `path/to/directory`
```

<sub>_use `.` to view current directory_, `..` to switch to the parent directory and `~` to switch to the home directory</sub>

- To remove a directory write.

```bash
rmdir `directory_name`
```

###### Now, let's interact with some files and gain a better understanding of how the commands function.

- To create a file with a given filename.

```bash
touch <file_name>
```

- To copy one file and paste it with other name (just like copy pasting file in windows and renaming the file)

```bash
cp <file1> <file2>
```

<sub>_file2 is the new file which is the replica of file1_</sub>

- To cut one file and paste it with other name (just like copy pasting file in windows and renaming the file)

```bash
mv <file1> <file2>
```

<sub>_file2 is the new file which is the replica of file1_</sub>

- To display the content of any file.

```bash
cat <file_name>
```

- To display page by page content of any file.

```bash
less <file_name>
```

- To display first few lines of any file.

```bash
head <file_name>
```

- To display last few lines of any file.

```bash
tail <file_name>
```

- To view the count of number of lines/words/characters of any file.

```bash
wc <file_name>
```

In conclusion, the world of Linux and Unix is a vast and fascinating one, and we've only scratched the surface with these basic commands. As we embark on this journey together, rest assured that there will be more insightful blog posts to come, delving deeper into the intricacies of these powerful operating systems. Stay tuned and keep practicing the commands we've explored today, because the more you immerse yourself in this world, the more you'll uncover its endless possibilities. Your Linux and Unix adventure has just begun!

Thank you for visiting, and I look forward to connecting with you and exploring the boundless world of software engineering and innovation.

[<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f8/LinkedIn_icon_circle.svg/1200px-LinkedIn_icon_circle.svg.png" width="45"/>](https://linkedin.com/in/praveensingh23)
[<img src="https://s18955.pcdn.co/wp-content/uploads/2018/02/github.png" width="45"/>](https://github.com/praveensinghrajput23)
[<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/58/Instagram-Icon.png/1024px-Instagram-Icon.png" width="45"/>](https://instagram.com/praveensinghrajput23)
[<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQYAFvsvvSz-ywpPupKs56YpRxW-C6OuOg8Jw&usqp=CAU" width="65"/>](https://twitter.com/_praveensingh23)

---
title: "Exploring the World of Linux and Unix: An In-Depth Overview"
date: 2023-09-07T13:04:56
categories:
  - tutorial
tags:
  - linux
  - unix
  - ubuntu
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"
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

* The shell acts as an interface between the user the kernal.
* The shell is a command kine interface (CLI). It interprets the commands the user types in and arranges for them to be carried out.
* The adepts user can customize his/her own shell, and users can use different shells on the same machine.

**Note:** Everything in unix either file or process.
{: .notice--info}

## Unix directory structure

![]({{site.url}}/assets/linux-and-unix-tutorial/directory-tree.gif)

Jekyll also offers powerful support for code snippets:

```ruby
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
```

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

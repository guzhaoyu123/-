# WorkingsOfBrowser
浏览器工作原理<br/>
React原理
<img src="https://blog.poetries.top/img-repo/2019/11/73.png">
<img src="https://blog.poetries.top/img-repo/2019/11/74.png">
<img src="https://blog.poetries.top/img-repo/2019/11/75.png">



## What is the difference between JavaScript Engine and JavaScript Runtime Environment?
  

Unlike C and other compiled languages, Javascript runs in a container - a program that reads your js codes and runs them. This program must do two things

parse your code and convert it to runnable commands
provide some objects to javascript so that it can interact with the outside world.
The first part is called Engine and the second is Runtime.

For example, the Chrome Browser and node.js use the same Engine - V8, but their Runtimes are different: in Chrome you have the window, DOM objects etc, while node gives you require, Buffers and processes.


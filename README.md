# 30-Days-Of-JavaScript


# The comprehensive guide to learning Javescript:

<p> In this JavaScript course, you will move from a person who is not familiar with anything in the language to a JavaScript professional.
JavaScript is therefore a high-level programming language that is mainly used in web browsers to create more interactive pages. The JavaScript language is used in web programming to a very large extent, so it is considered... The cornerstone for any web programmer, above all, is that JavaScript can work in the front-end (website design) and back-end (website programming) </p>

# How to add JavaScript codes?

in this lecture, you will how to add JavaScript codes in principe, there are many to do this
First and formost, the tag responsible for adding JavaScript codes to the web page is the <script> tag>.

# The first method:

You can write JavaScript directly in the html file by writing between the beginning and end of the <script> tag

## Exemple:

<script>
document.write("hello world");
</script>_ _

you can write JavaScript codes anywhere in your file, you can write it in head and you can write it in the body. but you must know that the order is important if you intend to write a command in JavaScript that affects an element in the body, you must write tis command after the desired element. Before it so that no errors occur but you can solve this problem though the onload event,

## JavaScript can access three places for modification

And through the document command, this command allows you to access the html page to modify it and add what you want. You can add text through write, for example:

```sh
document.write(“hello world”)
```
# Secondly, console

You can access the console part through the console command in JavaScript, for example:
```sh
 console.log(“hello world”);
```

# Third, the browser

You can also modify the browser through the window command in JavaScript. If you want to display a box with an example word:

```sh
window.alert(“hello world”);
``` 
## What is the difference between document - console - window:

The document is the programming command responsible for accessing the HTML page
When you create an HTML page, the browser sees it as follows First, he creates a document and from it he creates the html tag Then he creates the head, body, and what is inside them, for example:

```sh
 document
   html
 head       body
 meta title          h1 scrip
```
# Secondly, console

You can write code commands in your code editor and also in the console part available in all browsers. You can also control the console part through JavaScript using the console command.

```sh
    console
```
# Thirdly, the window

You can also modify the browser through the window command in JavaScript.

```sh
    window
```


# Documentation

<p>V8 is Google’s open source high-performance JavaScript and WebAssembly engine, written in C++. It is used in Chrome and in Node.js, among others.

This documentation is aimed at C++ developers who want to use V8 in their applications, as well as anyone interested in V8’s design and performance. This document introduces you to V8, while the remaining documentation shows you how to use V8 in your code and describes some of its design details, as well as providing a set of JavaScript benchmarks for measuring V8’s performance.</p>
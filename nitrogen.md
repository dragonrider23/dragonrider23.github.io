---
layout: page
title: "Nitrogen Programming Language"
permalink: /nitrogen/
menutitle: Nitrogen
---

Nitrogen is a Lisp-based programming language I created to learn fundamentally how programming languages work. It is not designed to be used in any sort of production environment. It's very minimal, but usable. It's based off the book [Build Your Own Lisp](http://www.buildyourownlisp.com/).

On this page you will be able to find the docmentation for the builtin functions as well as the Standard Library. You'll also find some examples to play with.

You can find the source code for the Nitrogen interpreter at: [github.com/lfkeitel/nitrogen](https://github.com/lfkeitel/nitrogen)

Language Fundamentals
---------------------

Here is where the basics of Nitrogen will be posted.


Language Core
-------------

The following words are reserved keywords for builtin functions or operators, or are used in the core library. This means they cannot be redefined using the (def) functions.

Internal - Functions and Operators

<table>
  <tr>
    <td>\</td>
    <td>=</td>
    <td>const</td>
    <td>def</td>
    <td>error</td>
    <td>eval</td>
  </tr>
  <tr>
    <td>exit</td>
    <td>head</td>
    <td>join</td>
    <td>list</td>
    <td>load</td>
    <td>print</td>
  </tr>
  <tr>
    <td>tail</td>
    <td>undef</td>
  </tr>
</table>

Internal - Arithmatic and Comparison Operators

<table>
  <tr>
    <td>+</td>
    <td>-</td>
    <td>*</td>
    <td>/</td>
    <td>%</td>
    <td>if</td>
  </tr>
  <tr>
    <td>==</td>
    <td>!=</td>
    <td>&gt;</td>
    <td>&lt;</td>
    <td>&gt;=</td>
    <td>&lt;=</td>
  </tr>
</table>

Core Library - Language Constructs

<table>
  <tr>
    <td>nil</td>
    <td>true</td>
    <td>false</td>
    <td>pfun</td>
    <td>fun</td>
  </tr>
  <tr>
    <td>do</td>
    <td>not</td>
    <td>or</td>
    <td>and</td>
    <td>++</td>
  </tr>
  <tr>
    <td>--</td>
    <td>select</td>
    <td>case</td>
    <td>otherwise</td>
  </tr>
</table>


Core Library
------------

Core Library - Functions (Note: These can be undefined. They will eventually be implemented in the interpreter directly but for now are written in Nitrogen.)

<table>
  <tr>
    <td>curry</td>
    <td>drop</td>
    <td>drop-while</td>
    <td>elem</td>
    <td>filter</td>
  </tr>
  <tr>
    <td>foldl</td>
    <td>foldr</td>
    <td>fst</td>
    <td>init</td>
    <td>last</td>
  </tr>
  <tr>
    <td>len</td>
    <td>lookup</td>
    <td>map</td>
    <td>nth</td>
    <td>pack</td>
  </tr>
  <tr>
    <td>product</td>
    <td>reverse</td>
    <td>snd</td>
    <td>split</td>
    <td>sum</td>
  </tr>
  <tr>
    <td>take</td>
    <td>take-while</td>
    <td>trd</td>
    <td>uncurry</td>
    <td>unpack</td>
  </tr>
  <tr>
    <td>unzip</td>
    <td>zip</td>
  </tr>
</table>


Standard Library
----------------

This is where you'll eventually find documentation for the Standard Library.


Examples
--------

Here you will find examples of the language in action.

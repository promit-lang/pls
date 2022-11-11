<h1 align= "center">Promit Language Specification 1.0</h1>

<p align= "justify">This document provides the specifications for Promit programming language. Any standard implementation of Promit will have to follow the specifications mentioned in this document. This is the first edition of PLS, released in _______.</p>

# Introduction

## 1. Scope of this specification

<p align= "justify">This specification will provide the first edition of Promit programming language standard, the Promit Language Specification 1.0 also known as PLS-1.0.</p>

## 2. Overview

<p align= "justify">Promit is a general purpose, fully object-oriented programming language designed to be used in computations as a standalone programming language or as a scripting language in host applications. Promit is originally designed to be a minimalistic scripting language. But it also can be a full-fledged programming language interpreter, where it is modular, has a large, condensed standard library (More in section ______) and a rich syntax.</p>

## 3. Goal of this language

<p align= "justify">A scripting language is a programming language which is generally interpreted and embedded in a host applications, abstracted from critical and low-level computations.</p>

<p align= "justify">The primary reason behind the design of Promit is widespread adoption of the language in both programming and scripting language world. There isn't any perfect scripting language which can be used as a full-fledged programming language yet or a perfect programming language which can be embedded into a native application without a hassle. Take Lua for example. You can use Lua as a interpreter, but you can't completely rely on it for critical computation, e.g. implementing various algorithms and data structures, which makes sense cause you generally don't need to do any critical calculations in a scripting language. On the other hand, Python is very good as a programming language. But embedding it to a native application is a hassle. Now think of programmer who is using Python or any other interpreted programming language for general computation. When he/she jumps to work on scripting of a host applications, chances are they are going to use Lua. That impiles that, the programmer has to learn another programming language just to do the scripting. Well, learning a new scripting language is not that big of a deal nowdays, but what if you don't have to? What if the programmer using the programming language X to do general computation and he/she is also using X for the scripting part?</p>

**Promit programming language is designed to be in two modes. One is normal mode (programming) and another one is embed (scripting) mode. Both mode has some common and distinct feature-set which is going to favour the mode it's in. For that reason, Promit is going to have two specifications respectively for Normal mode and Embed mode.**

# The common specifications

**This section will hold all feature-set of Promit which will be common in both Normal mode and Embed mode.**


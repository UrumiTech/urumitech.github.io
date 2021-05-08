---
author: Krishnan Nath
title: Starting Rust - Overview
categories: [Rust, Software-Development]
tags: [Rust, Overview]
date: 2021-05-08 17:49 +0100
pin: false
---
# Starting Rust

![Rust](https://cdn.urumitech.com/assets/img/Rust/rust-logo-blk.svg)

## What Is Rust?
Rust is a multi-paradigm, read multiple classifications, programming language. It has been designed for performance and safety. It is especially concurrency safe. It is very similar to C++ syntactically, however it can guarantee memory safety by using a borrow checker to validate references. It achieves this without a garbage collector (GC). In Rust reference counting is optional. 

## Quick History
The Rust language started in 2006 as a personal project for an employee, named Graydon Hoare, of Mozilla. Rust 1.0 was release in 2015. 
However in 2020 Mozilla had layoffs that affected the Rust team and Servo team. This led to the creation of the Rust Foundation by AWS, Huawei, Microsoft and Mozilla.

## Why should you use Rust?
Rust is designed to be high concurrent and highly safe. Rust does not permit null pointers, dangling pointers or data races in safe code. Rust does not use automated garbage collection. Rust however provide a very low overhead deterministic management of resources. 

So Rust should be used in system that need an emphasis on safety, control of memory layout and concurrency. Rust would really be suited for system that needs to be highly concurrent and transactional.


## Is it Object-Oriented or Functional?
Rust is both. Due to it being influenced C and C++, Rust can accomodate to both paradigms. As language Rust does seem to be more functional than Object Oriented Programming.

However, that does not mean a developer from a Object Oriented Programming. Inheritance and Polymorphism can also be accomplished via the mechanism of a "trait". Encapsulation can be accomplished by using the ```private``` keyword.

## How hard is it to learn Rust?
Rust basics is relatively easy to understand for anyone who has experience with some software development. If you have learned a either Java, Javascript or C#, the syntax is easily understandable and your previous skills are very transferrable. There are lot of common keywords and concepts to the above mentioned languages, the initial learn curve would not be very steep.

Learning the advanced concepts of Rust is like climbing a very tall mountain. Traits are difficult concept and will require a lot investigation to understand it. Memory safety will catch even experienced developers out. Then there are concepts like "Ownership", "Borrowing" and "Lifetimes", these are some of the most difficult concepts to understand.

## Conclusion
 * Rust can be an easy language to learn and build really useful applications. The key to start small and practice frequently.
 * It has been designed with memory safety and high concurrency means that you should build very well designed applications.
 * It is well supported by key platform providers
 * It is operating system agnostic
 * The syntax is very similar ot C++, Java and C#. So it should appeal to a wide community of software developers who looking for a new language to learn.

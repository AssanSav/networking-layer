# Networking Layer

## Learning Goals

- Explain the networking stack at a high level

## Introduction

The network stack is sometimes intimidating - how _does_ information get from one computer to another? Most of the confusion is because the underlying systems are genuinely complicated. They solve a ton of important problems - guaranteeing that information can get from place to place quickly and safely.

## Pre-check

- Write down a summary of what you know about networking. You might start with your definitions of client / server, http, request / response cycle, and IP
- What are the physical components of networking that you are familiar with?

## Reading

Read this blog post (by a fellow Flatiron SEC!) on [The Architecture of the Internet](https://medium.com/@brunogarciagonzalez/brief-intro-architecture-of-the-internet-396f7f91df92).

## Post-check

- Draw a diagram of the internet. Try to include as many parts and terms from the post as you can.
- Use `traceroute` to see the hops between your computer and some web address. See also the output of `curl`, `ping`, `dig`, `nmap`, and `lsof`

## Further Reading

Check out this [Yak Shave on Gem Install](https://rob.co.bb/posts/2018-10-22-yak-shave-gem-install-issue/) for an example of using networking tools to debug an issue in the network stack.

# Chapter 1: What is JavaScript?

## What's with that name?
In short: a marketing term because Java was very popular. Script used to imply 'lightweight'. 

Are there resemblances between JavaScript and Java?
A few superficial ones in the syntax. Both languages target developers with assumed syntax expectations from C (and to an extent, C++). See code example below.

```
{
    // code block with curly brackets
}; // semi-colon to punctuate the end of a statement
```

> Java is to JavaScript as ham is to hamster

To make it more complex, the official name is ECMAScript, named by TC39 (the technical steering committee that manages JS). In short you can say ES20xx (for that years revision), or just JS. Don't call it JS6 or ES8.

## Language specification

The official specification for the language is managed by [TC39](https://tc39.es/). The organization behind it is ECMA. 

The committee is comprised of 50-100 volunteers (from Mozilla, Google, Apple, Samsung etc.). They meet every other month for three days to review work, discuss issues and vote on proposals. All TC39 proposals go through a [five-stage process](https://tc39.es/process-document/).

Stage 0 means roughly, someone on TC39 thinks it's a worthy idea and plans to work with it. Lots of ideas that non-TC39 propose are through social media, pre-stage 0.

Once a proposal reaches 'Stage 4' status, it's eligible to be included in the next yearly revision of the language.

All proposals are managed in the open, on [TC38's Github](https://github.com/tc39/proposals).

Are there multiple versions of JavaScript? No. There is just **one JS**, The official standard as maintained by TC39 and ECMA. Back in the early 2000s Microsoft did maintain a forked and reverse-engineered version called 'JScript'. But currently there is only one version.

## The web rules everything about JS
JS runs on many different environments, but the implementation for web browsers is the most important one.
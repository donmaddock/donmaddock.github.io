---
layout: essay
type: essay
published: false
title: Solid Statements
# All dates must be YYYY-MM-DD format!
date: 2022-04-28
labels:
  - Design
  - Coding
---

## Flimsy Fundamentals

If frameworks and libraries are the tools programers use to avoid reinventing the wheel, then design patterns are the blueprints. However, many programmers gloss over just how useful these blueprints can be. And true, when you are first learning how to code, it might be a bit unnecessary to learn such complicated patterns for such small projects. Where design patterns truly start to shine is when the project gets bigger.

Coding complexity scales exponentially with project size. Getting two bits of code to interact is often harder than the sum of their parts. Without good patterns, you can figure out a solution, but often it isn't the most scalable. Like a house of cards, it becomes harder and harder to add more pieces, until eventually even the smallest extra feature risks toppling your whole stack.

Design patterns help make sure your foundation is strong enough to handle these additions. Countless coders before us have struggled with these problems, and over time have curated the best steps to handle them. Of course, there are many different problems a coder can run into, so knowing many different patterns means you'll have a plan for any situation. Most of my personal out of school coding is programming video games. The fact that common design patterns still work even here show how versatile they are. Below are a couple of my favorites, along with an all too brief overview of what they are and how I'd use them making games.

### State

State is like a switch statement's big brother. Context is often really important when running code. Rather than a million if-else checks, have the code pass in a generic "state" object. Then by defining more specific actions in more specific types of state, and some magical polymorphism, that generic state object can do many different things so long as you tell it when it needs to switch states. When programming actions for a game character, I want them to do different things depending on if they're on the ground, in the air, underwater etc. The state pattern is how I would organize that.

### Command

You probably have command to thank for the all powerful ctrl+z undo feature. By putting all the info of a task into an object, you can seperate that task from who ran the task and even when to run it. If you keep track of those commands, then you can do a lot of cool things like undo the most recent command you've done (you'll have to program undo logic yourself of course). I like to use commands when I want my game's enemies to perform a specific sequence of actions. You can just have a list of command objects to playback.

### Facade

When using a washing machine, you really only need to know how to start a wash. You don't need to know how it soaks, rinses, spins, or anything under the hood. Facade is the coding equivalent pattern to help abstract complicated coding actions to just the more simple things you or the client need to do. Using other people's libraries is extremely common in coding. When using more than one, sometimes it's nice to write a facade class to manage them all, so every script I write doesn't need to import the same three external libraries that I hardly understand in the first place.



# Game Design Best Practices

## Table of Contents

 1. [Introduction](#introduction)
 2. [Before the mockup](#before-the-mockup)
 3. [Mockup](#mockup)

## Introduction

Here are some best practices that should be followed when designing a game.

If you have any question or if something is not clear enough, you can create an issue in this repository.

## Before the mockup

Before starting the realisation of the mock up, it is important to answer and write down the answers the following questions. For each question we will use the example of a memory game (as seen in Chazey and Beaugency), written in italic.

### What is the game and its goal?

This question is kind of vague. And might answer multiple questions that changes with the game designed. The important thing here is to have an explanation of the game, what the user can interact with, and what the goal of the user is.

*The game starts with 16 cards face down. Each card has distinct image, and only two cards share the same image. The goal is to find all the pair.*

*When the user click on a card it reveals the other side of a card. He can then reveal another card. If the cards have the same image, they stay face up, otherwise they return to their original state.*

*While the user is playing, a timer is running.*

### What is the win condition?

*The game is won if the user find every pair without running out of time.*

### What is the lose conditon and what happens when the user loses?

*The game is lost if the timer reach zero.*

*When losing, the game is restarted to its original state: the timer is reseted and all cards are now face up.*

## Mockup

When designing a mockup it is important to keep in mind that everyone should understand the mockup without any external explanation. If some games are too complicated, a document can be attached to give an explanation about it (most likely with the questions previously answered).

Here is a list of things that are expected in a mockup:

- **Explanation of the interactions a user can do**. For example: what happens when a user click on an element, what happens when he doesn't, what happenes when he does a swipe gesture, etc.
- **If there is multiple screens, how are they linked together** ?
- **The introduction screen**, that introduces the game.
- **The explanation screen**. This screen explains to the user how the game works. It is often better to have a written explanation and an image that shows how the user can interact with the screen - [The Villers app is a great example of this](https://github.com/44Screens/villers_abbey_app). This screen should be shown at the begining of the game and should always be accessible with a button.
- **The screen displayed when the user win**.
- **The screen displayed when the user loses**, if applicable.
- Keep in mind the different **Aspect Ratios** when designing a game ! The most common aspect ratios are 16:9, 16:10 and 4:3. It is important to explain how some elements behave on theses different aspect ratios.

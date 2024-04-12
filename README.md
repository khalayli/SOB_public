# Sultans of Baloot

## Introduction

Sultans of Baloot is a project that stemmed out of a "what if" idea. It is also my way of diving deep into Swift, with a meaningful project since I don't enjoy working on small projects which are not of use. Baloot is a popular Saudi card game similar to French Belote with different rules which I enjoy playing it often with my fellow friends. It definitely exists and would not be the first to touch the App Store, however, as a player who spent a lot of time and has tried many different Baloot apps, I was never satisfied with any. They were just missing many features and the core algorithm of the game makes the user experience horrible. 


## About the Game

### Game Overview

It's a trick-taking game that is similar in structure to other card games like Bridge, Spades, and Hearts, but it has its own unique set of rules and is traditionally played with a standard deck of 52 cards. Baloot combines skill, strategy, and social interaction, making it a favorite pastime for many.

**Game Overview:**
Number of Players: Baloot is typically played by four players, divided into two teams of two. Partners sit opposite each other at a table.

**Objective:** The primary goal of the game is to score points by winning tricks. A trick is a collection of four cards, one contributed by each player in turn. Points are awarded based on certain cards won in tricks and for fulfilling specific declarations or bids.

**The Deck:** The game uses a standard 52-card deck. The cards in each suit rank from high to low: Ace (A), King (K), Queen (Q), Jack (J), 10, 9, 8, 7. In some variations, the J might be considered high.

**Gameplay:** The game starts with a bidding phase where players bid to declare the trump suit or choose to play without a trump. Following the bidding, the card play begins, where players take turns playing cards with the aim of winning tricks for their team.

**Scoring:** Scoring in Baloot depends on the specific variant being played. Points can be earned for winning tricks containing certain cards (e.g., the 10s and the Aces) and for fulfilling the contract declared during the bidding phase.
Hokom and Sun: There are two main variants of Baloot - Hokom and Sun. In Hokom, the trump suit is declared, while in Sun, there is no trump.

**Unique Aspects:**
Cultural Significance: Baloot holds significant cultural importance in the Gulf region. It's more than just a game; it's a social activity that fosters camaraderie and friendship.

**Strategic Depth:** The game requires a good balance of strategy, memory, and teamwork. Players must remember which cards have been played and strategize with their partners without direct communication.

**Tournaments:** Baloot is not only played casually but also in organized tournaments, reflecting its popularity and competitive nature.

### SOB Features

- Lightweight: Since it was developed using purely SwiftUI, it will be very light to run and will not consume large amounts of battery.
- An enjoyable free to play experience: The focus of the application will not be monetization and rather the fairness of algorithms and the gamer experience.

### Screenshots and Visuals

** The state of the application design is now emphasizing testing. The modules will all be redesigned and cleaned up.

<img width="220" alt="Screenshot 2024-04-04 at 11 37 20 PM" src="https://github.com/khalayli/SOB_public/assets/154463029/839ea867-13de-4121-8904-8b699156d6c1">

<img width="220" alt="Screenshot 2024-04-04 at 11 37 28 PM" src="https://github.com/khalayli/SOB_public/assets/154463029/23101567-f12c-47e8-98ba-4cf91b1d19f2">

<img width="220" alt="Screenshot 2024-04-04 at 11 37 37 PM" src="https://github.com/khalayli/SOB_public/assets/154463029/4e3c1c1c-14de-49e8-9859-7d004450df22">

<img width="220" alt="Screenshot 2024-04-04 at 11 37 46 PM" src="https://github.com/khalayli/SOB_public/assets/154463029/0b897188-b7ab-4344-8047-1eac5aea6e9c">

<img width="423" alt="Screenshot 2024-04-04 at 11 42 14 PM" src="https://github.com/khalayli/SOB_public/assets/154463029/5cb9ba6e-f2c0-4f63-91dd-768e0add1e31">

<img width="423" alt="Screenshot 2024-04-04 at 11 42 27 PM" src="https://github.com/khalayli/SOB_public/assets/154463029/cf8c1e18-4cc4-48af-84c2-97ca136ffa84">


https://github.com/khalayli/SOB_public/assets/154463029/46916bc5-d3b7-4d00-84b9-875cbe150438


Development:

<img width="248" alt="Screenshot 2024-04-04 at 11 35 14 PM" src="https://github.com/khalayli/SOB_public/assets/154463029/3a801cd8-ec37-4a2e-a14e-cda94950c6ca">

## Technologies Used

Firebase Authentication

Firebase Realtime

Firebase Database

KeychainSwift

## Challenges and Accomplishments

### Learning Journey

I faced many challenges with SOB, sometimes, I spent days scratching my head over just 1 bug. I had a memory leak at some point which just caused the application to never close the game once its out of view. It turned out NavigationLink doesn't destroy the view when you go back and I solved it by changing the View type.

**Some of the things I learned more about:**

-Firebase.

-Managing a large project with many files (over 40) and moving across them quickly.

-Weak and strong references.

-Strong references retain when deinitilizing main thread objects.

-Observing objects shared across many views.

-Creating unit tests.

-Using instruments to watch for memory leaks.

-Properly using Git for versioning and issues.


### Accomplishments

In only 16 days exactly, I managed to implement the offline game with AI bots which play decently.

## Roadmap

-Rewriting the game Engine for efficiency and consistency.
-Multiplayer matchmaking.
-UI polishing and redesign.
-Publication.

## Acknowledgements

I'd like to thank Paul Hudson for creating 100 Days Of SwiftUI and making it freely accessible for everybody. It was my starting point for my self-learning journey of Swift.

## Contact Information

Sami Khalayli | s.khalayli12@gmail.com | [linkedin.com/in/khalayli](https://www.linkedin.com/in/khalayli/)



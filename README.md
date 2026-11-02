# Hey, I'm Kien 👋

I like math. I also like finding out what happens when math meets a dataset that didn't read the paper.

I'm studying at **Minerva University (Class of 2029)**. Somewhere along the way, implementing graph algorithms turned into asking why their behavior changes so much with the input, which turned into wanting to understand the theory better, which (naturally) turned into more questions. My project list is not getting shorter.

Here's where some of those questions have taken me:

## Four examples of normal. No pressure. 🔍

If a model gets only four examples of a normal object, can it spot a defect it hasn't seen before? That's what I'm exploring with **DINOv2, patch-level nearest-neighbor matching, and PyTorch**.

A lot of the work happens after the heatmap appears: is that an actual defect, a weird background, or something I messed up in the experiment? Sometimes the most useful result is figuring out why a promising result isn't quite what it looks like.

## Teachers, schools, and one very busy graph 🚸

Matching teachers to schools gets complicated once you add subjects, capacity, demand, and travel. For our hackathon project, I built a **C++ min-cost max-flow solver** and connected it to a Flask API and a Next.js interface.

In one synthetic benchmark with 24 teachers and 18 schools, the solver reduced modeled travel distance by **54.6%** compared with a greedy baseline, while covering **78.1%** of demand. Turns out “just send the nearest teacher” isn't quite the whole story.

[Explore the Teacher Allocation Optimizer →](https://github.com/tony-ng-vn/Soda-hack)

## The swap that said “no quote” 🔗

Apparently, “the transaction works” and “the quoter is happy” are two different things. For one multi-hop Uniswap v4 and Tempo route, the standard quoter failed even though a funded transaction could execute on a local fork.

I contributed to **QuoteBridge**, our team's prototype for recovering candidate quotes on supported routes and checking them through full-transaction simulations. It's a prototype, not a deployed Uniswap feature. Getting the quote and the actual transaction to agree? Very satisfying.

[Explore QuoteBridge →](https://github.com/nganhuongg/multi-hop-quote-correction)

## Trees, heat, and a map of the Bay Area 🌿

With a team, I worked on the math, ML, and backend for **Bay Area Urban Planner**. We brought vegetation, temperature, and air-quality data together in a dashboard so people could explore how those patterns show up across the region.

[Explore Urban Planner →](https://github.com/kh268/urban-planner)

## Outside the code

I've taught **30+ C++ lessons to high school students**. Nothing tests your understanding quite like trying to explain something and getting a “but why?” in return. 😅

Lately, I've been spending time with **linear algebra, analysis, probability, and optimization**. For building things, I reach for Python, C++, PyTorch, SQL, TypeScript, FastAPI, and Git.

Want to talk math, stubborn bugs, or a result that doesn't make sense? I'm on [LinkedIn](https://www.linkedin.com/in/kien-han-3847502a0/).

# Hey, I'm Kien 👋

My projects are a slightly chaotic mix: finding tiny defects in images, getting teachers to schools, mapping heat in the Bay Area, and figuring out why a crypto route could execute but wouldn't give us a quote. You know, the usual.

I'm a student at **Minerva University (Class of 2029)**, and I like questions that make me stop and ask, “wait... why?” I've spent time implementing and benchmarking graph algorithms, and seeing how their behavior changes with the input made me want to understand the theory behind them, too.

A few of those questions turned into these projects:

## Four examples of normal. No pressure. 🔍

If you give a model only four examples of a normal object, can it notice a defect it hasn't seen before? That's the question behind my few-shot anomaly detection research. I use **DINOv2, patch-level nearest-neighbor matching, and PyTorch** to investigate it.

I also spend a lot of time asking whether the model is reacting to an actual defect, the background, or something in my experimental setup. The model does not always answer politely.

## Teachers, schools, and one very busy graph 🚸

Matching teachers to schools gets complicated once you add subjects, capacity, demand, and travel. For our hackathon project, I built a **C++ min-cost max-flow solver** and connected it to a Flask API and a Next.js interface.

In one synthetic benchmark with 24 teachers and 18 schools, the solver reduced modeled travel distance by **54.6%** compared with a greedy baseline, while covering **78.1%** of demand. So “just send the nearest teacher” wasn't quite the end of the story.

[Explore the Teacher Allocation Optimizer →](https://github.com/tony-ng-vn/Soda-hack)

## The swap that said “no quote” 🔗

For one multi-hop Uniswap v4 and Tempo route, the standard quoter failed even though a funded transaction could execute on a local fork. I contributed to **QuoteBridge**, our team's prototype for recovering candidate quotes on supported routes and checking them through full-transaction simulations.

It's a prototype, not a deployed Uniswap feature. But getting the quote and the actual transaction to agree? Very satisfying.

[Explore QuoteBridge →](https://github.com/nganhuongg/multi-hop-quote-correction)

## Trees, heat, and a map of the Bay Area 🌿

With a team, I worked on the math, ML, and backend for **Bay Area Urban Planner**. We brought vegetation, temperature, and air-quality data together in a dashboard so people could explore how those patterns show up across the region.

[Explore Urban Planner →](https://github.com/kh268/urban-planner)

## Outside the code

I've taught **30+ C++ lessons to high school students**. Teaching is a great way to find the exact moment you thought you understood something... right before someone asks a really good question. 😅

Lately, I've been spending time with **linear algebra, analysis, probability, and optimization**. For building things, I reach for Python, C++, PyTorch, SQL, TypeScript, FastAPI, and Git.

If you like math, strange bugs, or asking one more question than absolutely necessary, say hi on [LinkedIn](https://www.linkedin.com/in/kien-han-3847502a0/).

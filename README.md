# MosMetroDepth 🚇

**An AI-generated interactive visualization of the Moscow Metro, created as a small experiment in how generative AI changes software development.**

[![Live demo](https://img.shields.io/badge/Live-Demo-FF6B35?style=flat-square)](https://algmironov.github.io/MosMetroDepth/)
[![Article](https://img.shields.io/badge/Article-Русский-2677B8?style=flat-square)](https://algmironov.com/blog/neirobudushchee)

**[▶ Open the interactive demo](https://algmironov.github.io/MosMetroDepth/)** · **[Read the original article (Russian)](https://algmironov.com/blog/neirobudushchee)**

## Why this exists

The experiment started with a conversation about a video showing the Moscow Metro map with station depths. The exaggerated-looking differences in depth raised a simple question: how much work would it take to create an interactive visualization of the metro, including station data, lines, geographical positions, rotation, zooming, and station information?

Doing this manually would involve collecting and normalizing station data, building the interactive interface, testing it, and publishing the result. In the accompanying article, I estimated that this might take around two weeks of spare-time development for someone already comfortable with the relevant web technologies.

Instead, I described the task to **Claude** in a few lines. About **ten minutes** later, I had a generated file containing the data and code needed for a working result.

## The experiment

The goal was to see how quickly an AI assistant could turn a short description into a tangible interactive visualization.

The proposed workflow was:

1. Collect information about metro stations, lines, locations, and depths.
2. Create an interactive visualization that supports rotation, zooming, and station inspection.
3. Integrate the data.
4. Test and publish the result.

The result is available in the [live demo](https://algmironov.github.io/MosMetroDepth/).

## What this project demonstrates

This repository accompanies a broader reflection on how generative AI changes the time and skills needed to build software.

The central point of the article is not that developers no longer need technical knowledge. It is that **formulating a task clearly, understanding its constraints, and evaluating the result** become increasingly important when AI can produce a first implementation quickly.

The ten-minute figure is a description of this particular experience, **not a reproducible benchmark** or a claim about typical AI development speed.

## Important limitations

- This is a **demonstration and experiment**, not an authoritative source of Moscow Metro geographic or depth data.
- Station information and visual proportions have not been independently validated for accuracy as part of this README.
- The implementation was generated with AI assistance and should not be treated as a production-quality or independently audited application.
- The repository is preserved as a companion to the article; ongoing maintenance is not promised.

## Background reading

**[Нейробудущее — full article in Russian](https://algmironov.com/blog/neirobudushchee)**

The article discusses the original idea, the estimated manual development effort, the experience of generating the visualization with Claude, and broader questions about AI, work, and software development.

---

*An experiment in turning an idea into a working visualization with generative AI.*

---
layout: post
title: "Generating Magic:the gathering cards using AI"
date: 2023-04-15 14:00:00 +0200
categories: article
published: True
permalink: /AI/generating_pauper_cards
image: https://cards.scryfall.io/art_crop/front/1/6/162e81d3-6cd4-4cb8-8ed8-cfbd8d34ca71.jpg?1562799487
---

# Generating pauper cards with artificial intelligence

![Mind Stone](https://cards.scryfall.io/art_crop/front/1/6/162e81d3-6cd4-4cb8-8ed8-cfbd8d34ca71.jpg?1562799487)
> _Certo che sta accadendo dentro la tua testa, Harry! Dovrebbe voler dire che non è vero?_

# Table of Contents:

1. [Introduction](#introduction)
2. [Approach](#approach)
3. [Code](#maindeck)
4. [Demo](#demo)
5. [Last Words](#last-words)
6. [Acknowledgments](#acknowledgments)
7. [Review history](#review-history)

# Introduction

Generative AI (GenAI) is a type of Artificial Intelligence that can create a wide variety of data, such as images,
videos, audio, text, and 3D models. It does this by learning patterns from existing data, then using this knowledge to
generate new and unique outputs. GenAI is capable of producing highly realistic and complex content that mimics human
creativity, fasten the human process of generating content. This specific kind of Artificial Intelligence lately has
seen an enormous interest from the public, both for its possible applicability and its controversies. In this post i'll
jump on the AIGeneration train and use it for creating custom, never seen and totally plausible Magic the Gathering
cards.

# Approach

What's are the attribute that compose a card?
[IMMAGINE CHE DESCRIVE LE VARIE PARTI DI UNA CARTA DI MAGIC]
In this application, we're going to use an ensamble approch, using two models in order to render the card: ChatGPT for
generating all the attributes of the card, and StableDiffusion for generating the artwork. As for the layout, we used a
blank one that we're updating with the generations.

### Bonus: what's ChatGPT?

### Bonus: what's Stable Diffusion?

# Code

Here I'll quickly describe the main parts of the process with a brief description of the approaches used:

### Attribute generation

### Artwork generation

### Layout generation

### Final Result

# Demo

<a href="https://colab.research.google.com/drive/1aC55dHbKf5kx4olqzopvT3CLqlLxzVgH?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>

<a href=""><img src="https://huggingface.co/datasets/huggingface/badges/resolve/main/open-in-hf-spaces-sm-dark.svg"></a>

The code for the demos is available
on [Google Colab](https://colab.research.google.com/drive/1aC55dHbKf5kx4olqzopvT3CLqlLxzVgH?usp=sharing) or as
a [Huggingface Space](); as mentioned, in
order
to run the code and generate cards, you need to have a OpenAI token. ChatGPT is offered as a pay-per-use service, so *
*every generation costs**: the price is by no mean expensive, but it's a good thing to have in mind while playing with
the
demo :)

# Last words

# Acknowledgments

While wandering across [GitHub](https://github.com/), I stumbled across [@minimaxir](https://twitter.com/minimaxir) work
on exploring ChatGPT API, and while inspecting [his code](https://github.com/minimaxir/chatgpt_api_test), I came up with
the idea for this blogpost.
Big thanks especially
for his context and prompt engineering; without his repository, I would be in trouble, since I have little to no
experience in it.

## Review history

_2023-04-14 19:00:00_ : First publication

**My articles will always be open source, free and reproducible. My writings will always be discussion material, and my
opinions can be debated and refuted.**

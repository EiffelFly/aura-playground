# Aura playground

This is an ML playground for the Aura project. The goals of this repo are

- Stay as minimalist as possible. This means, we won't have UI, most of the time just humans call some function.
- Move fast

## The idea of Aura

The goal of Aura is to build an editor that can visualize the landscape of a long-form story like novels, YouTube scripts, essays...etc

## Setup

- Add your content into the `./content` folder
- docker pull chromadb/chroma
- docker run -p 8000:8000 chromadb/chroma

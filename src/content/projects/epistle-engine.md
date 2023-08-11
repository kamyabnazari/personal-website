---
title: "Epistle Engine"
date: 2023-08-10T19:06:59+02:00
draft: false
weight: 1
cover:
    image: "project-covers/cover-epistle-engine.jpg"
    caption: "cover image for Epistle Engine"
    alt: "Epistle Engine"
---

## What is Epistle Engine?

Our platform extracts information from PDFs using OpenAI's GPT model, simplifies document navigation, answers user queries, and generates content based on user prompts.

## Where can I find it?

The project repository can be found [here](https://github.com/kamyabnazari/epistle-engine).

## Introduction

In today's digital era, efficient interaction with documents is pivotal. Traditional document processing methods have been a source of frustration for many due to the cumbersome nature of locating specific information. Recognizing these challenges, we took a leap towards creating a transformative system: **The Epistle Engine**.

### Our Vision

The Epistle Engine seamlessly blends with OpenAI's GPT model, redefining your interaction with PDFs. Now, extracting insights, asking queries, and obtaining immediate answers from PDF documents becomes a hassle-free experience. Imagine understanding intricate concepts or posing targeted questions without the tedious task of browsing numerous pages. All this has been made possible with our unique plugin which significantly enhances document navigation, comprehension, and Q&A capabilities.

Moreover, the Epistle Engine goes beyond merely reading documents. Acknowledging the growing demand for efficient document creation, we've integrated a feature allowing users to generate content based on specific prompts. Whether it's an essay, a research report, or any other form of content, our engine doesn't just draft your document – it crafts a beautifully formatted PDF ready for deployment.

### Our Philosophy

At the heart of our innovation lies a simple belief: Technology should simplify lives, not complicate them. Our commitment to this philosophy shines brightly through the Epistle Engine. We envision a future where document processing is effortless, and interactions with content are enriched and meaningful.

We are immensely grateful to everyone who's decided to embark on this transformative journey with us. Welcome to the future of document processing!

## Tech-Stack Overview

### General
- **Version Control:** Git
- **Containerization:** Docker
- **Code Hosting:** GitHub
- **CI/CD:** GitHub Actions

### Frontend
- **Programming Language:** Typescript
- **Javascript runtime:** NodeJs
- **Full-Stack Framework:** SvelteKit
- **Frontend Framework:** Svelte
- **SaaS:** PocketBase (Database/File-Storage/Authentication)
- **CSS Framework:** TailwindCSS
- **Tailwind Component Library:** DaisyUI

### Backend
- **Programming Language:** Python
- **Backend Framework:** FastApi
- **Language Processing:** LangChain, OpenAI GPT
- **Database:** SQLite
- **Vector Search Engine:** Qdrant
- Other features include Authentication and File Storage through PocketBase.

## Setting Things Up

Getting started with the Epistle Engine is straightforward. Begin by installing the prerequisites mentioned. Detailed instructions for setting up individual services can be found in the README.md files. Remember to set up the services in the following sequence for optimal results:
1. Setup Pocketbase
2. Setup Qdrant
3. Setup Backend
4. Setup Frontend

### PDF Generation
To generate PDFs, ensure the following are installed on your system:
- texlive-full (latex)
- pkg-config
- cairo
- wkhtmltopdf (HTML to PDF converter)

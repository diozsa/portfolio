---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'NASA Space Exploration App'
pubDate: 2022-09-22
description: 'A visual tool for exploring The Space.'
author: 'Daniel Iozsa'
image:
    # url: '/src/static/images/space.jpg'
    url: '/space.jpg'
    alt: 'Homepage image for Space App.'
tags: ["astro", "nasa", "space", "app", "python"]
url: 'https://iozsa-space-app.herokuapp.com/'
github: 'https://github.com/diozsa/Capstone1-Space-app'
---

<!-- ## Welcome to my Space App! -->

**Objective**:
- Provides users with a visually engaging experience, allowing simple searches to yield
stunning photos from NASA's public APIs.

**Features**:
- Full stack multipage application
- Includes NASA images, APOD, Perseverance Rover and Image Collection, utilizing 3 different APIs
- User authentication and authorization
- Allows users to save and manage their image collections

**Technology**: 
- Backend: Python with Flask, SQLAlchemy for PostgreSQL
- Frontend: Server-rendered using Jinja2 templating, Bootstrap and HTML
- Security: bCrypt, WTForms, CSRF Token, persistence with Session


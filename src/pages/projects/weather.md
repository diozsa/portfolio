---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'Weather App'
pubDate: 2023-04-03
description: 'A weather service application like no other.'
author: 'Daniel Iozsa'
image:
    url: '/src/weather.jpg'
    alt: 'Homepage image for Weather App.'
tags: ["astro", "weather", "app", "react"]
url: 'https://iozsa-weather.surge.sh/'
github: 'https://github.com/diozsa/Capstone2-weather-app'
---


<!-- ## Weather App -->

**Objective**:
- Provides weather forecast that keeps user up to date with the weather conditions from multiple locations and weather allerts if present.

**Features**:
- Full stack single application
- Geolocation on initial load. Browser's location is retrieved based on the public user's IP
- Renders the current conditions with a weather alert (if any), a 24 hour-by-hour prognosis and a 15 day forecast
- Imperial to metric data selector
- User authentication and authorization
- Option to save, retrieve and delete saved locations for logged in users

**Technology**: 
- Backend: Built with Node.js, Express.js, and PostgreSQL
- Frontend: React, responsive design with React Bootstrap
- Security: JSON schema and form data validations, JWT, bcrypt, auth persistence with localStorage
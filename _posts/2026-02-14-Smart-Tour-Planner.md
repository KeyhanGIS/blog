---
layout: post
title: "Smart Tour Planner: A Context-Aware Web GIS for Personalized Travel"
date: 2026-02-14 22:00:00 +0000
categories: [Web-GIS]
tags: [Web GIS, GIS, Smart Tourism, Python, Django, Folium, Portfolio]
meta_title: "Smart Tour Planner – Context-Aware Web GIS for Travel Planning"
meta_description: "A real-world Web GIS project that generates personalized travel plans using context-aware logic based on user interests, time, and weather."
meta_keywords: "Web GIS, Smart Tourism, Context Aware GIS, Python GIS, Django GIS"
toc: true
comments: true
---

## 🧭 Introduction

Most travel map applications look smart at first glance.  
After a few minutes of use, however, they all start to feel the same: everything is shown to everyone.

Restaurants, attractions, hotels, and landmarks are usually mixed together without a real understanding of **who the user is**, **what they care about**, or **what actually makes sense at that moment**.

This project started with a simple question:

> *Can a Web GIS system think more like a human travel planner?*

**Smart Tour Planner** is my attempt to answer that question using a context-aware Web GIS approach focused on personalization and real-world relevance.

---

## 💡 The Core Idea Behind the Project

The goal was not to build yet another interactive map.

Instead, I wanted to design a Web GIS system that:
- understands user preferences,
- adapts to real-world context such as time and weather,
- and helps users move efficiently between meaningful places.

In short, a system that answers:

> **“Where should I go next?”**  
instead of  
> **“What exists around me?”**

---

## 🧠 What Makes This Web GIS “Smart”?

### 🧭 Personalized POI Ranking

Users define their interests using **ten different categories**.  
Each Point of Interest (POI) is scored and ranked based on how well it matches those preferences.

This approach avoids:
- generic recommendations,
- long and irrelevant POI lists,
- and one-size-fits-all travel suggestions.

Only locations that truly fit the user profile are highlighted.

---

### ☀️ Context-Aware Filtering (Time & Weather)

Context awareness plays a central role in this project.

The system dynamically adjusts its recommendations based on:
- time of day,
- weather conditions.

For example:
- some POIs lose relevance at night,
- others become unsuitable during bad weather,
- suggestions update automatically without manual filtering.

---

### 🚗 Optimized Routing Between POIs

Once relevant POIs are selected, the system calculates:
- the shortest,
- and most efficient route between them.

The idea is simple:
**less time spent moving, more time spent exploring.**

---

### 🏨 Integrated Service Mapping

In addition to attractions, the map also includes essential services such as:
- hotels,
- parking areas,
- cinemas.

These services are clustered to keep the map readable and easy to use.

---

## ⚙️ Tech Stack & Architecture

This project was implemented as a complete Web GIS pipeline.

### Backend
- Python / Django  
- Context-Based Reasoning (CBR) logic  
- User preference handling and contextual filtering  

### Mapping
- Folium  
- Interactive web maps with POIs, routes, and service layers  

### Database
- PostgreSQL  
- Storage of spatial and non-spatial data  

The overall architecture was kept intentionally simple, readable, and easy to extend.

---

## 🧩 Challenges and Design Decisions

Some of the most important challenges were not technical bugs, but design choices:

- defining meaningful rules for context-based reasoning,
- balancing recommendation quality versus quantity,
- combining spatial data with user behavior and environmental context,
- keeping the interface simple while backend logic remained complex.

These decisions shaped the final system more than any single technology choice.

---

## 🚀 Possible Future Improvements

This project is a prototype rather than a finished product.

Potential next steps include:
- integrating real-time data sources,
- improving POI ranking strategies,
- connecting to external tourism APIs,
- optimizing the system for mobile-first usage.

---

## 🎥 Project Demo

The following video demonstrates the full workflow of the Smart Tour Planner, including personalized POI selection, context-aware behavior, and routing logic.

{% include embed/youtube.html id='Emny4izfxYg' %}

---

## 📌 Final Thoughts

This project shows how Web GIS can move beyond simple visualization and evolve into a **decision-support system**.

Maps are powerful on their own, but when combined with context and reasoning, they become genuinely useful.

If you are interested in building or extending context-aware Web GIS solutions, feel free to get in touch.

---
layout: post
title: "Smart Tour Planner: A Context-Aware Web GIS for Personalized Travel"
date: 2025-11-03 10:00:00 +0000
categories: web-gis
tags: [WebGIS, GIS, SmartTourism, Python, Django, Folium, Portfolio]
meta_title: "Smart Tour Planner – Context-Aware Web GIS for Travel Planning"
meta_description: "A real-world Web GIS project that generates personalized travel plans using context-aware logic based on user interests, time, and weather."
meta_keywords: "Web GIS, Smart Tourism, Context Aware GIS, Python GIS, Django GIS"
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

The goal was not to build yet another map viewer.

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

This avoids:
- generic recommendations,
- long and irrelevant POI lists,
- one-size-fits-all travel suggestions.

---

### ☀️ Context-Aware Filtering (Time & Weather)

The system dynamically adapts its recommendations based on:
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
**less time moving, more time exploring.**

---

### 🏨 Integrated Service Mapping

In addition to attractions, the map also includes essential services such as:
- hotels,
- parking areas,
- cinemas.

These services are clustered to keep the map readable and easy to use.

---

## ⚙️ Tech Stack & Architecture

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

---

## 🧩 Challenges and Design Decisions

Key challenges during development included:
- defining meaningful context-based rules,
- balancing recommendation quality versus quantity,
- combining spatial data with user behavior and environment,
- keeping the UI simple while backend logic remained complex.

---

## 🚀 Possible Future Improvements

- Real-time data integration  
- Smarter POI ranking strategies  
- External tourism APIs  
- Mobile-first optimization  

---

## Video

{% include embed/youtube.html id='Emny4izfxYg' %}

---

## 📌 Final Thoughts

This project demonstrates how Web GIS can move beyond visualization and become a **decision-support system**.

Maps alone are powerful — but when combined with context and reasoning, they become genuinely useful.

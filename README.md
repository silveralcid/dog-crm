# Dog CRM

[GitHub Repository](https://github.com/silveralcid/dog-crm)

A pet-centric, groomer-first CRM and booking system designed to adapt to real-world grooming conditions.

## Overview

Dog CRM is an ongoing project to build a **data-driven, customizable scheduling and client management system** for grooming businesses.  
It aims to reflect the **actual complexity of pet grooming**—where time, temperament, and technique vary from one appointment to the next.

This project is currently in its early stages and expected to evolve over the next year.

## Tech Stack

- **Backend:** Django, Celery, Redis, PostgreSQL  
- **Frontend:** React  
- **TBD:** Authentication, API Gateway, Analytics Layer

## Background

Through research and discussions with experienced groomers, it became clear that most existing CRMs and booking systems fail to address the unique challenges of the pet grooming industry. Many of these platforms are adapted from human salon software, lacking the flexibility to account for the wide range of variables that affect grooming sessions.

Across the market, several recurring issues stand out:

- Designed primarily for salons or spas rather than grooming businesses  
- Either too generic or overloaded with unnecessary features  
- Poorly suited to the realities of day-to-day grooming operations  
- Often expensive or locked behind closed, proprietary systems  

These limitations lead to inefficiency, inaccurate scheduling, and a lack of actionable insights into performance and client experience.

## Goal

Build a **groomer-first CRM** that dynamically adapts to each pet, groomer, and session — optimizing scheduling and business insights through data.

## Core Problem

Existing CRMs assign **fixed grooming times** (e.g., two hours per pet), ignoring critical variables that determine real grooming duration.

Pet grooming is deeply personal and skill-dependent, yet most software lacks data-awareness — missing opportunities for smarter scheduling, tracking, and analysis.

## Key Variables

| Category | Factors |
|-----------|----------|
| **Groomer** | Skill level, speed, and grooming style |
| **Pet** | Size (surface area), coat type (care requirements), breed (coat and temperament), temperament (calm vs. anxious) |

An experienced groomer working with a large, calm dog might take 30 minutes.  
A less experienced groomer workign with a small, anxious dog with a complex coat might take over two hours.

## Insight

Grooming time isn’t fixed — it’s **a variable function** of the pet, the groomer, and their interaction.  
A “smart” CRM should learn from each session, adjust estimates dynamically, and continuously improve scheduling accuracy and efficiency.

## Status

- [ ] Backend scaffolding (Django + Celery + Redis)  
- [ ] PostgreSQL schema design for pets, clients, and bookings  
- [ ] React frontend setup  
- [ ] Dynamic time estimation logic  
- [ ] Analytics and reporting layer  

## Long-Term Vision

Imagine a grooming CRM that:
- Learns how each groomer works  
- Tracks how different breeds and temperaments affect time  
- Predicts realistic grooming durations  
- Offers true **data-driven insights** for small grooming businesses  

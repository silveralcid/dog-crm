# Dog CRM

[GitHub Repository](https://github.com/silveralcid/dog-crm)

A pet-centric, groomer-first CRM and booking system designed to adapt to real-world grooming conditions.

---

## Overview

Dog CRM is an ongoing project to build a **data-driven, customizable scheduling and client management system** for grooming businesses.  
It aims to reflect the **actual complexity of pet grooming**—where time, temperament, and technique vary from one appointment to the next.

This project is currently in its early stages and expected to evolve over the next year.

---

## Tech Stack

- **Backend:** Django, Celery, Redis, PostgreSQL  
- **Frontend:** React  
- **TBD:** Authentication, API Gateway, Analytics Layer

---

## Background

My fiancée has over 10 years of experience in pet grooming and has used countless CRMs and booking systems.  
Most of them share the same flaws:

- Designed for salons or spas, not pet grooming  
- Too generic or feature-bloated  
- Poor adaptability to real grooming conditions  
- Expensive or closed-source  

The result: inefficiency, inaccurate scheduling, and little insight into performance or productivity.

---

## Goal

Build a **groomer-first CRM** that dynamically adapts to each pet, groomer, and session — optimizing scheduling and business insights through data.

---

## Core Problem

Existing CRMs assign **fixed grooming times** (e.g., two hours per pet), ignoring critical variables that determine real grooming duration.

Pet grooming is deeply personal and skill-dependent, yet most software lacks data-awareness — missing opportunities for smarter scheduling, tracking, and analysis.

---

## Key Variables

| Category | Factors |
|-----------|----------|
| **Groomer** | Skill level, speed, and grooming style |
| **Pet** | Size (surface area), coat type (care requirements), breed (coat and temperament), temperament (calm vs. anxious) |

A large, calm dog might take 30 minutes.  
A small, anxious dog with a complex coat might take over two hours.

---

## Insight

Grooming time isn’t fixed — it’s **a variable function** of the pet, the groomer, and their interaction.  
A “smart” CRM should learn from each session, adjust estimates dynamically, and continuously improve scheduling accuracy and efficiency.

---

## Status

- [ ] Backend scaffolding (Django + Celery + Redis)  
- [ ] PostgreSQL schema design for pets, clients, and bookings  
- [ ] React frontend setup  
- [ ] Dynamic time estimation logic  
- [ ] Analytics and reporting layer  

---

## Long-Term Vision

Imagine a grooming CRM that:
- Learns how each groomer works  
- Tracks how different breeds and temperaments affect time  
- Predicts realistic grooming durations  
- Offers true **data-driven insights** for small grooming businesses  

That’s the north star for Dog CRM.

# Electricity Billing System

A web-based electricity billing application that automates meter management,
tariff handling, bill generation, and online payment for three types of users —
**Admin**, **Meter Reader**, and **Client**. Built as a course project for
CSE347 (Section 04).

## Live Demo

**App:** https://apex.oracle.com/pls/apex/r/347_project/electric-billing-system/login

> Deployed on Oracle APEX. Open the link above (do not use a copied
> `?session=...` URL — that session ID is temporary and expires).

**Demo credentials**

| Role         | Username | Password |
|--------------|----------|----------|
| Admin        | `ADMIN`  | `ADMIN`  |
| Meter Reader | `METER`  | `METER`  |
| Reader       | `READER` | `READER` |

## Roles & Features

- **Admin** — add/modify users, meters, and tariff manuals; add meter
  information; search database attributes; generate graphs from queries.
- **Meter Reader** — view and search database attributes; update billing
  information; generate graphs from queries.
- **Client** — view and download their own bill and information; view the
  tariff manual; pay bills online; search and graph bill-related data.

## Tech Stack

- **Platform:** Oracle APEX (low-code)
- **Database:** Oracle Database
- **Auth:** role-based login (Admin / Meter Reader / Client)

## Design & Planning Artifacts

The presentation documents the full analysis and design:

- Functional & non-functional requirements
- Use-case model (11 use cases across the 3 roles) and activity diagrams
- ER model and relational model
- Project scheduling with a **Critical Path Method (CPM)** network
  (14 activities; critical path A→C→F→H→J→K→L→M→N, 16-day duration)

See **`CSE347-Electricity-Billing-System-Slides.pdf`** for the full deck.
*(If you keep the original filename, update this link accordingly.)*

## Team

- Mohammed Shawqi Aftab
- Jerin Anan Proma
- Fatema Tuz Zannat
- Md. Yousuf Hozaifa

*Course: CSE347 · Section 04 · Summer 2024*

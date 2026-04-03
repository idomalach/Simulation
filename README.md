# Gym Management System — OOP Simulation Project

An object-oriented gym management simulation built in Python as part of the **Event-Based Simulation** course at Ben-Gurion University of the Negev (BGU), Department of Industrial Engineering and Management.

## About the Project

This project models a gym environment using OOP principles: managing members, trainers, fitness classes, equipment, subscriptions, and personal training sessions. It includes input validation, exception handling, scheduling with conflict detection, and reporting features such as monthly billing and trainer statistics.

## Class Structure

| Class | Description |
|---|---|
| `Equipment` | Gym equipment with availability tracking and condition management |
| `Subscription` | Billing logic — plan pricing, class overages, and no-show penalties |
| `FitnessClass` | Scheduled group classes with enrollment, waitlists, and conflict detection |
| `Trainer` | Trainer profiles with certification tracking and performance stats |
| `Member` | Gym members with class registration, attendance, and payment history |
| `PersonalTrainingSession` | One-on-one training sessions between a member and a trainer |
| `Gym` | Top-level manager — coordinates all entities and generates reports |

## Key Features

- Class scheduling with day/time conflict detection (Israeli work week: Sun–Thu + Fri morning)
- Monthly payment reports per member (plan-based pricing with overage and penalty logic)
- Trainer statistics and performance reports
- Equipment condition tracking and availability checks
- Waitlist management for full classes
- Input validation and custom exception handling throughout

## Tech Stack

- **Language:** Python 3
- **Platform:** Google Colab
- **No external dependencies** — uses only the Python standard library

## Team

Ido, Yonatan, and Eitan

## Course Info

- **Course:** Event-Based Simulation (2026B)
- **Lecturer:** Nimrod Talmon
- **Teaching Assistants:** Amit Oren, Eden Cohen

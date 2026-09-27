# Teledentistry / Medical Appointment Booking App

> **Status: 🚧 Planning — not yet started.** This repository holds the initial idea and scope. Implementation will begin soon.

A web application that lets students book medical/dental appointments online, initially built to help a friend (a medical student) manage appointment scheduling more easily than manual/offline methods.

## Motivation

Currently, booking an appointment with a doctor (especially informally, e.g. through a friend who is a medical student) is done manually — via chat messages or phone calls — leading to double-booking, missed appointments, and no easy history of past visits. This project aims to provide a simple, reliable booking system so patients can see available time slots and doctors can manage their schedule in one place.

## Planned Features

- [ ] Patient registration/login
- [ ] Doctor availability calendar (set available time slots)
- [ ] Book/cancel/reschedule an appointment
- [ ] Appointment reminders (email/notification)
- [ ] Appointment history for patients and doctors
- [ ] (Stretch) AI-assisted symptom intake — a simple chatbot that asks basic questions before booking, to help suggest the right specialty/doctor and give the doctor a head start on context

## Planned Tech Stack

| Layer | Technology (tentative) |
|---|---|
| Frontend | React |
| Backend | Node.js / Express |
| Database | MongoDB |
| Auth | JWT |
| AI (stretch goal) | LLM API (e.g. OpenAI/Claude) for symptom intake chatbot |

*(Stack may change once implementation starts — this is a planning-stage placeholder.)*

## Scope (v1)

To keep the first version achievable, v1 will focus on:
- One doctor, multiple patients (not a full multi-clinic marketplace)
- Simple time-slot booking, no payment integration
- Basic authentication, no third-party login

Out of scope for v1: insurance integration, multi-clinic support, video consultation.

## Roadmap

1. Requirements & use-case definition
2. UI wireframes (booking flow, doctor calendar view)
3. Backend API design (appointments, availability, users)
4. MVP implementation (core booking flow, no AI yet)
5. AI symptom-intake chatbot (stretch goal)
6. Testing & deployment

## Contributing

This is currently a solo/small-team side project. Not accepting external contributions yet — will update this section once the project is further along.
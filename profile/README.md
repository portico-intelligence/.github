# Portico Intelligence

We build **taskforse**, the AI-powered operating system for commercial cleaning companies.

A cleaning company runs on shifts, people and phone calls. When someone calls off at 5 a.m., the owner is the one dialing backups. taskforse takes that work over.

## What is live

- **Scheduling** for sites, shifts and crews
- **Call-off coverage**: when a shift is uncovered, an automated phone call-down rings ranked backups until someone takes it
- **Geolocation clock-in and clock-out** from the crew's phone
- **Inspections** with before and after photos
- **Bidding**: a bid calculator for new contracts

## What we are building now

**Dusty**, an assistant that knows the company's own history and acts on it. It answers the owner's questions from their real data, raises the one thing that needs attention today, and prepares actions (the first is a late-payment reminder) that the owner approves with one click. The model never sends anything on its own.

## Where we are

- In production at [app.taskforse.com](https://app.taskforse.com)
- Onboarding our first design partners
- More than 1,000 on the waitlist at [taskforse.com](https://www.taskforse.com)

## How it is built

Next.js and TypeScript, Postgres with Prisma, deployed on Vercel. The assistant runs on open models behind a typed tool layer, graded against a fixed exam before every change ships.

Our code is private. Investors and partners can ask either founder for read access.

# Lomdim
# Lomdim — Social Torah Learning Platform

🔗 **Live platform:** https://lomdim.app

A production social learning platform that enables learners, scholars and
communities to share Torah content, learn together and manage learning activity.

> This repository is a public portfolio case study.
> It intentionally does not include proprietary source code or private user data.

## My role

Full Stack Developer at Koren Digital.

I contributed to the development, maintenance and release of the Lomdim platform,
including frontend features, Supabase backend capabilities, authentication,
permissions, automated tests and CI/CD workflows.

## Tech stack

- React, TypeScript, Vite and Tailwind CSS
- Supabase: PostgreSQL, Auth, Row Level Security, Storage and Edge Functions
- React Query, Zustand and React Router
- GitHub Actions, Vercel and Playwright
- AI-powered product capabilities and API integrations

## Selected work

- Developed product features for learning, content publishing and user profiles.
- Implemented authentication and permission-based access with Supabase RLS.
- Built and maintained API and Edge Function integrations.
- Created automated tests with Vitest and Playwright.
- Worked with staging and production deployments through GitHub Actions and Vercel.
- Improved security, database policies and release workflows.

## Screenshots

![Lomdim home page](assets/lomdim-home.png)
![Lomdim learning experience](assets/lomdim-learning.png)
![Lomdim profile](assets/lomdim-profile.png)

## Architecture

```mermaid
flowchart TD
  User["Learner / Scholar"] --> Web["React + TypeScript Web App"]
  Web --> Supabase["Supabase: Auth, PostgreSQL, RLS, Storage"]
  Web --> Edge["Edge Functions / AI Integrations"]
  Web --> Vercel["Vercel Deployment"]

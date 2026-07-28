# Hi, I’m Rastislav Elias

I’m a frontend-focused web developer working with React, Next.js, TypeScript, and Tailwind CSS.

I previously worked as a self-employed web developer delivering websites end to end. I am now rebuilding my professional portfolio around modern React, Next.js, TypeScript, API routes, authentication, database-backed apps, and AI API integration.

## Current focus

- React and TypeScript
- Next.js App Router
- Tailwind CSS
- API routes and server-side validation
- Prisma, PostgreSQL, and basic full-stack flow
- Accessible, responsive UI

## Selected projects

### Mini Resource Library

An independently designed full-stack Next.js application for organising private learning resources with custom categories, reading statuses, notes, and ratings.

- Designed a user-owned relational model for resources and reusable custom categories
- Used Clerk user IDs to isolate private data without duplicating accounts in a local user table
- Created Zod schemas for input validation, normalisation, and TypeScript form-type inference
- Implemented server actions that validate input, authenticate the user, verify record ownership, perform Prisma mutations, and revalidate affected pages
- Restricted category deletion while resources still reference it to prevent accidental data loss
- Kept search, filtering, and pagination deliberately focused instead of introducing unnecessary tagging or full-text-search complexity

**Stack:** Next.js, React, TypeScript, Tailwind CSS, Clerk, Zod, Prisma, PostgreSQL

[Live app](https://resources.rastislavelias.com) · [Source code](https://github.com/rastislavelias/mini-resource-library)

### AI Photo Description Tool

An independently designed Next.js application that converts uploaded images into an AI-generated description and 3–6 relevant tags.

- Designed the complete client-to-server image-processing flow
- Added browser-side validation and resizing to reduce unnecessary upload size
- Implemented independent server validation of file type, size, request format, and image dimensions
- Added content moderation before description generation
- Required predictable AI responses using strict JSON Schema
- Created typed error codes for validation, moderation, provider, and server failures

**Stack:** Next.js, React, TypeScript, Tailwind CSS, OpenAI API, JSON Schema, Canvas API

[Live app](https://ai-photo-description.vercel.app) · [Source code](https://github.com/rastislavelias/ai-photo-description)

### Country Explorer

A React and TypeScript app that fetches country data and filters results by search and region.

- React
- TypeScript
- API data fetching
- Derived filtering
- Component composition

Live app: https://rastislavelias.github.io/country-explorer

### Task Manager

A React and TypeScript task manager focused on state, filtering, and component structure.

- React
- TypeScript
- State management
- Derived filtered data
- Local storage persistence

Live app: https://rastislavelias.github.io/task-manager

## Links

- Portfolio: https://rastislavelias.com
- LinkedIn: https://www.linkedin.com/in/rastislavelias
- Email: contact@rastislavelias.com

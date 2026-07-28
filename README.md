# Hi, I’m Rastislav Elias

I’m a frontend-focused web developer building practical applications with Next.js, React, TypeScript, and Tailwind CSS.

My current work includes a production client website and independently designed applications involving authentication, relational data, validation, server logic, external APIs, error handling, and deployment.

## Current Focus

- React, TypeScript, and component architecture
- Next.js App Router and server actions
- Authentication and record-level ownership
- Zod validation and typed application boundaries
- Prisma and PostgreSQL relational data
- Accessible, responsive interfaces
- External API and AI integration

## Selected Projects

### Olga Pietrzak — Client Website

A production website built and delivered for a therapist, adapting a Tailwind Plus foundation to the client’s brand, content, and requirements.

- Translated client requirements into a responsive Next.js website
- Structured service content and MDX-based legal pages
- Implemented server-action contact handling with Resend
- Added metadata, sitemap, robots configuration, and SEO foundations
- Managed the project through implementation and production deployment

**Stack:** Next.js, React, TypeScript, Tailwind CSS, MDX, Server Actions, Resend

[View website](https://olgapietrzak.pl)

### Mini Resource Library

An independently designed full-stack Next.js application for organising private learning resources with custom categories, reading statuses, notes, and ratings.

- Designed a user-owned relational model for resources and reusable custom categories
- Used Clerk user IDs to isolate private data without duplicating accounts in a local user table
- Created Zod schemas for input validation, normalisation, and TypeScript type inference
- Implemented server actions that authenticate users, verify ownership, perform Prisma mutations, and revalidate affected pages
- Restricted category deletion while resources still reference it to prevent accidental data loss
- Kept search, filtering, and pagination deliberately focused rather than introducing unnecessary complexity

**Stack:** Next.js, React, TypeScript, Tailwind CSS, Clerk, Zod, Prisma, PostgreSQL

[Live app](https://resources.rastislavelias.com) · [Source code](https://github.com/rastislavelias/mini-resource-library)

### AI Photo Description Tool

An independently designed Next.js application that converts uploaded images into an AI-generated description and 3–6 relevant tags.

- Designed the complete client-to-server image-processing flow
- Added browser-side validation and resizing to reduce upload size
- Implemented independent server validation of the request, file type, size, and image dimensions
- Added content moderation before description generation
- Required predictable AI responses using strict JSON Schema
- Created typed error codes for validation, moderation, provider, and server failures

**Stack:** Next.js, React, TypeScript, Tailwind CSS, OpenAI API, JSON Schema, Canvas API

[Live app](https://ai-photo-description.vercel.app) · [Source code](https://github.com/rastislavelias/ai-photo-description)

## Links

- [Portfolio](https://rastislavelias.com)
- [LinkedIn](https://www.linkedin.com/in/rastislavelias)
- [Email](mailto:contact@rastislavelias.com)

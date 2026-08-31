# Full-Stack Real Estate Platform — Case Study

> Public architecture summary of a private production-oriented project. Business data, credentials and private source code are not published.

## Problem

A real-estate company needs more than a public listing page. Listings, appointments, customer requests, property media and administrative workflows need to live in one maintainable system.

## Product surface

- public sale and rental listings
- detailed property pages with media and structured attributes
- appointment requests
- sell/rent property request forms
- administration dashboard
- listing and customer-request management
- role-based access to management functions

## Architecture

```text
React / TypeScript client
          │
          ▼
       REST API
          │
   ┌──────┼────────┐
   ▼      ▼        ▼
auth   listings   requests
   │      │        │
   └──────┼────────┘
          ▼
      Prisma ORM
          │
          ▼
         MySQL
```

## Engineering highlights

- React + TypeScript frontend
- Node.js / Express REST backend
- Prisma-based relational data model and migrations
- JWT authentication and role-aware administration
- API validation and security middleware
- property image/file upload workflows
- separate local and production database workflows
- production deployment considerations for frontend, API and database migration state

## What matters to me here

The value of this project is the end-to-end responsibility: UI, forms, API boundaries, persistence, authentication, administration and deployment all have to agree with each other.

It is a good example of the kind of work I enjoy: **turning a business workflow into a complete software system rather than a collection of screens.**

## Areas involved

`React` · `TypeScript` · `Node.js` · `Express` · `Prisma` · `MySQL` · `Authentication` · `Deployment`

---

[← Back to profile](../README.md)

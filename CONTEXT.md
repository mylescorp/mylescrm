---
type: context
status: active
date: 2026-06-23
tags:
  - context
  - mylescrm
---

# MylesCRM — CONTEXT.md

Last updated: 2026-06-23
Updated by: Vault seed - update via /grill-with-docs

## What This Product Does

[[MylesCRM]] is a customer relationship management product for small and growing businesses to manage leads, clients, pipelines, follow-ups, and business communication.

## Target User

Small and mid-sized businesses, sales teams, founders, customer success teams, service businesses, and MylesCorp internal operations.

## Stack

- Framework: Next.js 16.2 (Turborepo monorepo)
- Backend: [[Convex]]
- Auth: [[WorkOS]] AuthKit
- Email: [[Resend]]
- Hosting: [[Vercel]]

## Domain Glossary

| Term | Meaning |
|---|---|
| Lead | A potential customer in the sales pipeline |
| Pipeline | The stages a lead moves through from inquiry to sale |
| Deal value | The monetary value of a potential sale |

## Architecture Decisions (Permanent)

- Auth: [[WorkOS]] AuthKit only
- Backend: [[Convex]] only
- Email: [[Resend]]
- Hosting: [[Vercel]] and Convex Cloud
- TypeScript strict mode - no any, no ts-ignore

## Current Phase

Stage: delivered capability. Priority: maintain and improve as needed.

## Known Pitfalls

- [Run /grill-with-docs to populate]

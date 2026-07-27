# WGMS - Claude Instructions

## Project Name
WGMS (Wants Guangzhou Management System)

## Goal
Build a simple, fast, scalable back-office system for Wants Guangzhou.

The first version is an MVP that must be usable within 15 days.

## Development Principles

- Build only what is necessary.
- Do not redesign completed workflows.
- Keep the UI simple.
- Every feature must solve a real business problem.
- Speed is more important than visual perfection.
- The system must be easy for non-technical staff.

## MVP Modules

1. Dashboard
2. Create Job
3. Job Detail
4. Product Search
5. Quotation
6. Purchasing
7. Receiving
8. Shipping

## Create Job

Only collect:

- Customer Name
- Contact Channel
- Country
- Product Image or Product Link
- Note

Everything else will be added later.

## Business Rules

- One Job = One Customer Request
- Every Job has a unique Job Number.
- Products can come from multiple Chinese cities.
- Cost price is internal information.
- Customer must never see internal cost.
- Service fee is separated from product cost.
- Shipping fee is calculated after receiving goods.
- Shipping fee is based on Weight or Volume, whichever is greater.

## Countries

CN = China

JP = Japan

KR = Korea

## Future Expansion

The architecture must support multiple countries without changing existing code.

## Coding Rules

- Use TypeScript.
- Use Next.js App Router.
- Use Supabase.
- Use Prisma.
- Use Tailwind CSS.
- Keep components reusable.
- Use English for code.
- Display Thai language in UI where appropriate.

## Important

Never change the business workflow unless explicitly instructed.
Always prioritize maintainability and simplicity.

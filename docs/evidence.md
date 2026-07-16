# Evidence and claim boundaries

This document makes the status of the case explicit. It separates observable shipped behavior from supporting project artifacts and from claims that are intentionally not made.

## Public evidence

### Live application

[https://stuff-sycle-web-4.vercel.app/](https://stuff-sycle-web-4.vercel.app/)

The deployment exposes the working React application and its public product surfaces.

### Recorded walkthrough

A 4 minute 3 second screen recording demonstrates:

- sign-in;
- landing and profile surfaces;
- catalog browsing, search, filters, and sorting;
- administration and user management;
- FAQ and support;
- messaging;
- user profile and listings;
- item detail;
- listing creation and publication.

The original video is not stored in this repository because it is approximately 274 MB. The interface images in `assets/screenshots/` are frames extracted from that walkthrough.

### Academic project

The [final bachelor project](StuffSycle-bachelor-project.pdf) is included in this repository. It is 43 pages and covers:

- the problem field and sustainability context;
- research method;
- process and scenario analysis;
- interpretation of findings;
- comparison with existing marketplace products;
- product concept and requirements;
- user journey and user flow;
- information architecture;
- application architecture;
- data model;
- implemented interface;
- conclusions and limitations.

### Supporting project artifacts

The project archive includes separate documents for:

- application architecture;
- implementation backlog;
- user flow;
- user journey;
- explanatory notes;
- file and route structure.

## Claim matrix

| Claim | Status | Evidence |
|---|---|---|
| Working web application | Confirmed | Live Vercel deployment and walkthrough |
| React application | Confirmed | Project documentation and deployed bundle |
| TypeScript and Vite | Confirmed | Project documentation and build structure |
| Supabase backend | Confirmed | Project documentation and deployed application integration |
| Authentication | Confirmed | Live walkthrough and application behavior |
| Catalog and listing flows | Confirmed | Live walkthrough |
| Messaging | Confirmed | Live walkthrough and realtime architecture |
| User profiles | Confirmed | Live walkthrough |
| Administration surface | Confirmed | Live walkthrough |
| Vercel deployment | Confirmed | Public deployment |
| Obsidian, Linear, Figma Make, Cursor, Claude Code workflow | Confirmed by project owner | Delivery history |
| Large-scale commercial production usage | Not claimed | The project is a deployed bachelor product, not a scaled marketplace |
| Public source repository | Not available | Source remains private |

## Why the source is private

The purpose of this repository is to provide inspectable product and engineering evidence without publishing private configuration, repository history, or material that was not prepared for public release.

The case therefore provides:

- a live result;
- detailed architecture;
- interface evidence;
- explicit tool and delivery workflow;
- clear boundaries around what is and is not being claimed.

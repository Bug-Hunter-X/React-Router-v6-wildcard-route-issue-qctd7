# React Router v6 Wildcard Route Issue

This repository demonstrates a common issue encountered when using wildcard routes (`/*`) in React Router v6.  The wildcard route unexpectedly catches all routes, even when a specific route should match.

The problem occurs because the wildcard route is too general and overlaps with other route definitions.  The solution involves carefully ordering routes and ensuring that more specific routes are defined before the wildcard.

## Setup

Clone this repository and run:

```bash
npm install
npm start
```
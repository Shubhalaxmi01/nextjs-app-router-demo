# Next.js Dashboard Learning Project

This project is part of my learning journey with Next.js. It follows the official Next.js Learn tutorial and is being built step-by-step to understand the App Router, layouts, and client-side navigation.

## Overview

The project is a dashboard application that demonstrates key concepts in Next.js including nested routing, reusable layouts, client-side navigation, and the use of React hooks in Client Components.

## Progress So Far

- Setup of a Next.js project using the App Router
- Creation of pages and nested routes (`/dashboard`)
- Implementation of a dashboard layout with a persistent sidebar (`SideNav`)
- Use of `<Link>` for client-side navigation to avoid full page reloads
- Highlighting active navigation links using `usePathname()`
- Conversion of components into Client Components using `"use client"`

## Project Structure

- `/app/dashboard/page.tsx` – Main dashboard page
- `/app/dashboard/layout.tsx` – Layout including sidebar
- `/app/ui/dashboard/sidenav.tsx` – Sidebar component
- `/app/ui/dashboard/nav-links.tsx` – Navigation links component

## Key Concepts

### Layouts
Layouts allow shared UI elements, such as the sidebar, to persist across multiple pages without re-rendering.

### Client vs Server Components
- **Server Components**: default in Next.js, optimized for performance, cannot use React hooks.
- **Client Components**: required for interactivity, can use hooks like `usePathname()`.

### Navigation
- `<Link>` enables fast client-side navigation within the app.
- `<a>` causes a full page reload and should be used only for external links.

## Next Steps

- Fetch and display data in dashboard pages
- Build additional pages under `/dashboard`
- Add loading states and UI improvements
- Apply custom styling and enhancements to make the project unique

## References

- Official Next.js Learn tutorial: [Next.js Dashboard App](https://nextjs.org/learn/dashboard-app)

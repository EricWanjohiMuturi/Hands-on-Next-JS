# Hands-on-Next-JS

- Created this repo with the intention to learn NextJS framework. 
- Using the `NextJS Learn` resource to make it interactive - https://nextjs.org/learn/

## Overview

Here is an overview of the concepts:

- Styling: The different ways to style your application in Next.js.
- Optimizations: How to optimize images, links, and fonts.
- Routing: How to create nested layouts and pages using file-system routing.
- Data Fetching: How to set up a Postgres database on Vercel, and best practices for fetching and streaming.
- Search and Pagination: How to implement search and pagination using URL search params.
- Mutating Data: How to mutate data using React Server Actions, and revalidate the Next.js cache.
- Error Handling: How to handle general and 404 not found errors.
- Form Validation and Accessibility: How to do server-side form validation and tips for improving accessibility.
- Authentication: How to add authentication to your application using NextAuth.js and Middleware.
- Metadata: How to add metadata and prepare your application for social sharing.

## Next JS Project Concepts
Looking at the terms, conventions and best practices of a Next JS project

### Starting a project
Initialize a neew project using this command and select your preference from the selections provided by the prompts

`npx create-next-app@latest`

### Routing
- NextJS has a file-system based routing system
- URLs you can access in your browser are determined by how you organize your files and folders in your code.
- Not all files or folders become routes

#### Routing Convetions
1. All routes must live inside the app folder
2. Route files must be named either page.js or page.tsx
3. Each folder represents a segment of the URL path

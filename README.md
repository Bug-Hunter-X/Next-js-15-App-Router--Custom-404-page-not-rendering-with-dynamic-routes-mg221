# Next.js 15 App Router: Custom 404 page not rendering with dynamic routes

This repository demonstrates a bug in Next.js 15's App Router where a custom 404 page fails to render correctly when used in conjunction with dynamic routes.  The expected behavior is that the custom 404 page should render when a route does not exist; however, a blank page is displayed instead.

## Steps to Reproduce

1. Clone this repository.
2. Install dependencies: `npm install`
3. Run the development server: `npm run dev`
4. Navigate to a non-existent route (e.g., `/nonexistent`).

You will observe a blank page instead of the custom 404 page.

## Expected Behavior

The custom 404 page should be rendered when an invalid route is accessed.

## Actual Behavior

A blank page is rendered.

## Solution

The solution involves ensuring the correct structure and configuration of your application to handle the dynamic routes properly, which is usually in the `app` directory in Next.js 15.


---
name: React Routing
description: Guidelines for implementing client-side routing using React Router DOM. Use when creating routes, navigation, layouts or route-based pages.
---

# React Routing

## Objective

Implement client-side navigation using React Router DOM.

## Technology restrictions

- Use React Router DOM.
- Use JavaScript, never TypeScript.
- Do not introduce alternative routing libraries.

## Routing conventions

1. Use BrowserRouter for browser-based navigation.
2. Use Routes and Route to define routes.
3. Use Link or NavLink for internal navigation.
4. Avoid using regular anchor tags for internal navigation.
5. Keep route definitions organized.
6. Separate page components from reusable components.
7. Use nested routes when they simplify shared layouts.
8. Use Outlet for nested route rendering when appropriate.
9. Handle unknown routes with a Not Found page.

## Implementation workflow

1. Identify the pages required.
2. Define the route structure.
3. Identify shared layouts.
4. Implement route configuration.
5. Connect navigation links.
6. Verify navigation behavior.

## Quality checklist

- All required routes exist.
- Internal navigation uses React Router DOM.
- Nested routes work correctly.
- Shared layouts render correctly.
- Unknown routes are handled.
- No unnecessary routing dependencies exist.

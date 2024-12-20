# React Router Dom v6 Catch-all Route Issue

This repository demonstrates a common issue encountered when using catch-all routes (`/*`) in React Router Dom v6.  The catch-all route, intended to handle any unmatched routes and display a 404 (Not Found) page, is not functioning correctly.  This results in other routes failing to render properly.

The problem stems from the order and placement of routes within the `Routes` component.  A poorly placed catch-all route will intercept all other route matches, preventing them from being reached.

This repository provides a buggy example and a solution to resolve this issue, highlighting the correct implementation of catch-all routes in React Router v6.
# React Router Dom v6 Nested Routes Bug

This repository demonstrates a common issue encountered when working with nested routes in React Router Dom v6.  The problem involves nested routes not rendering correctly, even when the routes are properly defined.

## Bug Description
The provided code uses nested routes. However, when navigating to the nested routes, nothing renders.  The parent route renders fine, but the nested components fail to mount.

## Solution
The solution involves ensuring the correct structure of nested routes. Specifically, the `useParams` hook may need to be used correctly within the nested components to access the dynamic segments of the URL.  This change ensures that the nested components can interpret the path and render accordingly.

## How to Reproduce
1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install`.
4. Run `npm start`.
5. Observe the behavior of the nested routes.
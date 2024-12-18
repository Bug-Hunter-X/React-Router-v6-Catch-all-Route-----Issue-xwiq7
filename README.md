# React Router v6 Catch-All Route Issue

This repository demonstrates a problem with the catch-all route ('*') in React Router v6.  The issue is that the NotFound component, intended to handle all invalid routes, does not render when navigating to a non-existent path.

## Problem
The provided `App.js` file shows a basic React Router setup.  Routes for '/' and '/about' work correctly. However, the catch-all route `path="*"`, intended to display a 'Not Found' component for any other path, does not work as expected.  Navigating to a non-existent route will not render the NotFound component.

## Solution
The `AppSolution.js` file presents a solution to this issue.  The solution highlights correct placement and usage of the catch-all route within the `Routes` component in React Router v6.
# React Router Dom Catch-All Route Bug

This repository demonstrates a bug encountered when using the catch-all route `/*` in `react-router-dom`.  The catch-all route unexpectedly intercepts all requests, even when other routes should match. The solution shows how to properly handle catch-all routes.

## Bug Description

The main App.js file shows a standard setup of routes.  Despite having a more specific route defined, the catch-all route `/` always takes precedence. 

## Solution

AppSolution.js demonstrates a solution to prevent this behavior and correctly utilize catch-all routes.
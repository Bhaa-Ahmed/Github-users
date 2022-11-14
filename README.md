# Overview

Responsive React project that allows users to find github users by searching their user names.

# Site

- https://find-github-users-react.netlify.app/

# Features

- Show the most used Languages, Most popular Repos, Followers, Stars per language and Most forked Repos.
- Login and logout using Auth0.

# Setup

- React 16.13.1
- CSS using styled-components
- Icons using React Icons
- Routing using React Router
- Authorization with Auth0
- Charts using react-fusioncharts

# Structure

Main project contains pages, components and context.

- Pages and components folders have index.js inside. We use it for get all of the files and export as object, so we can easy import multiple components in one line like this: `import { Info, Repos, User, Search, Navbar } from "../components"`

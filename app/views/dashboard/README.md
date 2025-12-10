# Dashboard Feature

## Overview
This is the main user dashboard homepage for Flexbase. It provides a simple, extensible interface with authentication-aware navigation.

## Components

### Controller
- `DashboardController` - Handles the dashboard index action
- Allows unauthenticated access but shows different content based on auth status

### Views
- `dashboard/index.html.erb` - Main dashboard page
- `layouts/_navigation.html.erb` - Navigation menu with login/logout links

### Styling
- `dashboard.css` - Dashboard-specific styles
- `navigation.css` - Navigation menu styles

## Features
- Responsive navigation menu
- Login/Logout links (context-aware)
- User email display when authenticated
- Extensible widget area for future features
- Flash message support

## Extensibility
The dashboard is designed to be extended with:
- Additional widgets in the `.dashboard-widgets` grid
- Role-based content sections
- Organization-specific features
- Custom user preferences

## Routes
- Root path (`/`) - Dashboard home page

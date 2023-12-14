# Chimera Project Structure 🚀

## src/
Contains the main source code for the application.

### resources/ 🌐
Resource definitions for the application.
- **expert/**: Expert resource including location data (latitude and longitude).
  - **ExpertResource.js**: Expert resource definition with location attributes.
  - **components/**: Components specific to the expert resource.
    - **SearchForm.svelte**: Component for searching experts based on location and other criteria.
    - **ExpertList.svelte**: Component to list experts, possibly with map integration.
    - **ExpertProfile.svelte**: Detailed profile view for each expert.
  - **services/**: Services for expert data handling, including geolocation services.
  - **stores/**: Stores for state management related to experts.
- **user/**: User resource.
- **...**: Other resources.

### routes/ 🛣️
Svelte pages generated from resources.
- **experts/**: Generated routes for expert resources, including search and profile views.
- **...**: Other generated routes.

### lib/ 📚
Shared libraries and utilities.
- **api/**: API interactions, possibly including location-based queries.
- **utils/**: Utility functions, including location-related utilities.

### components/ 🧩
Reusable components for the application.
- **Map.svelte**: Component to display map with expert locations.
- **...**: Additional reusable components.

### stores/ 🏪
Svelte stores for state management.
- **location.js**: Store for managing user location and preferences.
- **...**: Other stores.

### services/ 🌟
Business logic and data fetching.
- **geolocation.js**: Service for handling geolocation data and functionalities.

### pages/ 📄
Main pages of the application.
- **Home.svelte**: Home page of the application.
- **About.svelte**: Information about the application.
- **...**: Additional pages.

## tests/ 🧪
Unit and integration tests for the application.

## static/ 🖼️
Static assets like images, fonts, etc.

## node_modules/ 📦
npm packages for the application.

## package.json 📄
Project metadata and dependencies.

## svelte.config.js ⚙️
Configuration file for SvelteKit.

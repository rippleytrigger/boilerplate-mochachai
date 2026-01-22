# Quality Assurance and Testing with Chai

## Overview
This is a freeCodeCamp Quality Assurance and Testing project using Chai, Mocha, and Express.js. The application provides a testing environment for learning assertion methods and functional testing with chai-http and Zombie.js.

## Project Structure
- `server.js` - Main Express server
- `tests/` - Test files for unit and functional testing
- `views/` - HTML templates
- `public/` - Static assets
- `assertion-analyser.js` - Test assertion helper
- `test-runner.js` - Mocha test runner

## Running the Application
The server runs on port 5000 with:
```bash
npm start
```

## Testing
Tests run automatically when the server starts. The failing tests are intentional - users complete them as part of the freeCodeCamp curriculum.

## Recent Changes
- 2026-01-22: Configured for Replit environment (port 5000, 0.0.0.0 binding)

## Dependencies
- Express.js - Web framework
- Chai - Assertion library
- Mocha - Test framework
- chai-http - HTTP integration testing
- Zombie.js - Headless browser testing

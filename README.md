# Testing Automation Engineer Assessment

This is a basic to-do app with authentication created as a part of tutorial for beginners to understand and learn laravel concepts
<a href="https://www.parthpatel.net/laravel-tutorial-for-beginner/" rel="dofollow">Laravel Tutorial for beginner</a>

# Setup
### Requirements
- Docker
- docker-compose

### Installation
- Clone this git repository.
- run `docker-compose up -d` in the app folder.
- run `docker exec -it app php artisan migrate`
- run `docker exec -it app php artisan vendor:publish`
- go to `http://localhost` in your browser and verify that the app loads correctly.

# Instructions
## Backend
- Create a suite of Unit and Feature tests covering an appropriate cross-section of the codebase. 
    - Tests should be written in either PHPUnit or should include an explanation of why an alternative was chosen.
    - Test suite should also generate a code coverage report.
    
## Frontend
- Create a suite of automated frontend tests covering an appropriate cross-section of the codebase.
    - Tests should be written in Selenium or should include an explanation of why an alternative was chosen.
    - Test suite should also generate a code coverage report.

## Load/Stress/Performance Testing
- Design a suite of tests targeting system performance that provides reporting on the results.
    - Output should reflect:
        - Verification of site's ability to handle 1000 concurrent users
        - Current max number of concurrent users before site becomes unstable
        - Average request response time.

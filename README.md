# Lab: Class 33 - Authentication & Production Server

## Open Git Pull Requests  


## Overview  

Let’s move our API closer to production grade by adding Authentication and switching to a Production Server

## Feature Tasks and Requirements  

### Django
- [] Add JWT Authentication to your API.
  - [] Install needed libraries in project configuration and/or site settings.
- [] Keep existing authentication so DRF Browsable API still usable.
  - [] That includes keeping the styling
  - [] Install needed libraries in project configuration and/or site settings.

### Docker  
- [] Create a boilerplate Dockerfile and docker-compose.yml so you don’t need to start from scratch each time.
- [] Switch to using Gunicorn instead of Django’s built in development server.
  - mind the number of workers to avoid sluggishness
- Warning You will run into styling issues when you switch over to Gunicorn.
  - On Django side you’ll need to properly handle static files.
- [] Adjust docker-compose.yml so that data is persisted in a volume outside of container.

## User Acceptance Tests  
- [] Use tests from demo and adjust as needed for your project.
- [] Ensure tests pass

## Dependencies  
- python = "^3.8"
- django = "^3.0.7"
- djangorestframework = "^3.11.0"
- psycopg2-binary = "^2.8.5"

## Authors  
- Software Developer: Joseph Zabaleta
  - [Official Github](https://github.com/joseph-zabaleta)  

## Collaborations  
- none  

## License  
This project is under the MIT License.

## Acknowledgements / Resources  
- none

## Version History  
- 1.0.0 20200624
    - Initial files created.  

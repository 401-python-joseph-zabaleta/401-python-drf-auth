# Lab: Class 33 - Authentication & Production Server

## Open Git Pull Requests  

[https://github.com/joseph-zabaleta/drf-auth/pull/1](https://github.com/joseph-zabaleta/drf-auth/pull/1)  

## Overview  

Let’s move our API closer to production grade by adding Authentication and switching to a Production Server

## Feature Tasks and Requirements  

### Django
- [x] Add JWT Authentication to your API.
  - [x] Install needed libraries in project configuration and/or site settings.
- [x] Keep existing authentication so DRF Browsable API still usable.
  - [x] That includes keeping the styling
  - [x] Install needed libraries in project configuration and/or site settings.

### Docker  
- [x] Create a boilerplate Dockerfile and docker-compose.yml so you don’t need to start from scratch each time.
- [x] Switch to using Gunicorn instead of Django’s built in development server.
  - mind the number of workers to avoid sluggishness
- Warning You will run into styling issues when you switch over to Gunicorn.
  - On Django side you’ll need to properly handle static files.
- [x] Adjust docker-compose.yml so that data is persisted in a volume outside of container.

## User Acceptance Tests  
- [x] Use tests from demo and adjust as needed for your project.
- [x] Ensure tests pass

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
- 1.0.1 20200624
    - Local Host server is working
- 1.0.2 20200624
    - Production Server is working
- 1.0.3 20200624
    - Docker working, still using sql lite
- 1.0.4 20200624
    - Docker working with postgres still need volumes

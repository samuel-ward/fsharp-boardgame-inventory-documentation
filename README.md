F# Board Game Inventory System
================================

## Overview

This project is being designed to provide an inventory system for, but not restricted to, board games. It will be conducted in stages, with multiple applications being built, starting with the mobile application.

Each of these applications will be written in F# on the .NET stack wherever possible, and where needed - C#.

## Components

_Mobile Application:_
https://github.com/samuel-ward/fsharp-boardgame-inventory-app

## Roadmap

### Stage 1: Mobile Application

- [x] Set up mobile app repository
- [ ] Get basic Xamarin mobile application up and running
- [ ] Implement model
- [ ] Implement unit tests
- [ ] Implement database layer
    - [ ] Implement database wrapper layer
    - [ ] Implement local storage layer
- [ ] Implement internal business logic
- [ ] Design UI/UX
    - [ ] Split experience into views/pages
- [ ] Implement UI

### Stage 2: Web-Based API

- [ ] Set up Amazon Account
- [ ] Implement HTTP web api
- [ ] Pick suitable database
- [ ] Set up terraform repository
- [ ] Implement terraform

- [ ] Change mobile app to consume web api periodically (non-breaking)
- [ ] Iterate over mobile app UI/UX designs

### Stage 3: Web Application

- [x] Set up web app repository
- [ ] Implement web app
    - [ ] Consume web api

- [ ] Iterate over web api
- [ ] Iterate over mobile app UI/UX designs
# Project Planning

## Problem Statement

### Primary User

Anyone interested in going to live events.

### User Needs Statement

As a user, I want to be able to search for upcoming events (sports, concerts, operas, etc.) in my area. I should be able to filter my search by location, and save a list in CSV format for future reference.

## Information Requirements

### Information Inputs

todo: describe information inputs (see proposal instructions)

### Information Outputs

  1. An `events.csv` file containing a list of events from a search the user chose to save.

## Technology Requirements

### APIs and Web Service Requirements

This app will use the [Ticketmaster API](https://developer.ticketmaster.com/) to access data on upcoming events around the world.

### Python Package Requirements

The application does not require any third-party packages, except [pytest](https://docs.pytest.org/en/latest/) for testing purposes.

The application does however make extensive use of the requests, datetime, os and csv modules.

### Hardware Requirements

The application will be running on my own local machine. I have no plans to deploy this application to a public server.

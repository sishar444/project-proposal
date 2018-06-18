# Project Planning

## Problem Statement

The application allows users to search for upcoming live events related to their interests, and save a printed list for later reference.

### Primary User

Anyone interested in going to live events.

### User Needs Statement

As a user, I want to be able to search for upcoming events (sports, concerts, operas, etc.) in my area. I should be able to filter my search by location, and save a list in CSV format for future reference.

### As-is Process Description

  1. Go to the Ticketmaster website.
  2. Search for an event that you are interested in.
  3. Filter the results by city, state, or country.
  4. No way to save the list other than printing a hard copy.
  
### To-be Process Description

  1. Run the application script.
  2. Search for an event that you are interested in.
  3. Filter the results by city, state, or country.
  4. Save the list to your local machine in CSV format so you don't need to search again.

## Information Requirements

### Information Inputs

  1. User search terms, as strings input locally.

### Information Outputs

  1. List of events printed out locally.
  2. An `{search term}-events.csv` file containing a list of events from a search the user chose to save.

## Technology Requirements

### APIs and Web Service Requirements

The application will use the [Ticketmaster API](https://developer.ticketmaster.com/) to access data on upcoming events around the world.

### Python Package Requirements

The application does not require any third-party packages, except [pytest](https://docs.pytest.org/en/latest/) for testing purposes.

The application does however make extensive use of the requests, datetime, os and csv modules.

### Hardware Requirements

The application will be running on my own local machine. I have no plans to deploy this application to a public server.

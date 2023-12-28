# Java-Assignment
Rest Apis

# Voting System REST API

This project implements a simple RESTful API for a voting system, allowing users to enter candidates, cast votes, count votes, list all candidates with their vote counts, and get the winner.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Voting System REST API provides endpoints to manage candidates, cast votes, and retrieve voting-related information. This project uses Spring Boot to create a Java-based RESTful API without a database, storing data in local variables.

## Features

- Enter new candidates into the system.
- Cast votes for valid candidates.
- Count the votes for a specific candidate.
- List all candidates along with their respective vote counts.
- Get the winner with the highest number of votes.

## API Endpoints
GET /entercandidate?name={candidateName} - Add a new candidate to the system.
POST /castvote?name={candidateName} - Cast a vote for a candidate.
GET /countvote?name={candidateName} - Retrieve the vote count for a candidate.
GET /listvote - List all candidates and their vote counts.
GET /getwinner - Get the name of the candidate with the highest

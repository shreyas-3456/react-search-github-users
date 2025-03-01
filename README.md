# GitHub API Charts with FusionCharts & Auth0

## This repository is a web application that integrates GitHub API with FusionCharts to visualize data from GitHub repositories. It uses Auth0 for authentication.

### Features

Fetches data from the GitHub API

Displays charts using FusionCharts

Implements authentication via Auth0

Interactive UI for analyzing repository statistics

### Tech Stack

Frontend: React, FusionCharts

Authentication: Auth0

API: GitHub API

Deployment: Docker (optional)

Prerequisites

Node.js (>= 16.x)

NPM or Yarn

Auth0 account

GitHub personal access token (if required for API access)

### Getting Started

1. Clone the Repository

git clone https://github.com/your-username/your-repo.git
cd your-repo

2. Install Dependencies

npm install  # or yarn install

4. Run the Application

npm start  # or yarn start

The app should now be running on http://localhost:3000

Usage

Log in using Auth0

Search for GitHub repositories

View charts displaying repo statistics (stars, forks, contributors, etc.)

### Deployment

Docker (Optional)

To run the app in a Docker container:

docker build -t github-api-charts .
docker run -p 3000:3000 github-api-charts

### Contributing

Fork the repository

Create a new branch (git checkout -b feature-branch)

Commit your changes (git commit -m "Add new feature")

Push to the branch (git push origin feature-branch)

Create a Pull Request

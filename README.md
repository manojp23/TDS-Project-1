# GitHub Users in Seattle

This repository contains data about GitHub users in Seattle with over 200 followers and their repositories.

## Files

1. `users.csv`: Contains information about {len(users)} GitHub users in Seattle with over 200 followers
2. `repositories.csv`: Contains information about {len(all_repos)} public repositories from these users
3. `gitscrap.py`: Python script used to collect this data

## Data Collection

- Data collected using GitHub API
- Date of collection: {time.strftime('%Y-%m-%d')}
- Only included users with 200+ followers
- Up to 500 most recently pushed repositories per user

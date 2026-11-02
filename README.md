# Cricket Fantasy

A fantasy cricket web platform built with **Laravel** and **MySQL**. Users build their dream team of 11 players for ongoing matches and earn points based on how those players perform in real time. An admin panel handles players, teams, matches and scores.

## Features

### For Users
- Register and log in to your own account
- Browse ongoing and upcoming matches with live status tracking
- Create your dream team by selecting **11 players** for a match
- View team points update automatically as players perform

### For Admins
- Add, edit and delete players and teams
- Create and manage matches
- Enter and update player scores
- Points for every user team are recalculated automatically

### Scoring System
- Dynamic scoring that updates each user team's points based on the performance of its selected players
- Points are recalculated whenever the admin updates player scores

## Tech Stack

| Layer     | Technology                  |
|-----------|-----------------------------|
| Backend   | PHP, Laravel                |
| Database  | MySQL                       |
| Frontend  | Blade templates, Vite       |
| Server    | XAMPP (Apache + MySQL)      |
| Tools     | Composer, npm, Artisan      |

## Project Structure

```
Cricket-Fantasy/
├── app/          # Models, controllers, business logic
├── bootstrap/    # Framework bootstrapping
├── config/       # Application configuration
├── database/     # Migrations, seeders, factories
├── public/       # Public assets and entry point
├── resources/    # Blade views, CSS, JS
├── routes/       # Web routes
├── storage/      # Logs, cache, uploads
└── tests/        # Automated tests
```

## Usage

1. **Admin:** log in to the admin panel and add teams, players and matches.
2. **User:** register, pick an ongoing match, and select your 11 players.
3. **Admin:** update player scores as the match progresses.
4. **User:** watch your team's points update automatically.

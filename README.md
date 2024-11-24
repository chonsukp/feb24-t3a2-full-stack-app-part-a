# MatchMyMovies

Coder Academy - T3A2 - Full Stack Application - Part A

## R1 - Description
### Purpose
- This app helps you find the perfect movie to watch based on your mood or a specific situation. It solves the common problem of decision fatigue, making the process of choosing a movie both fun and easy.

### Features
- Genre combiner (select two genres that generate a list of movies that match both genres)
- Movie pairing  (input two movies to generate a movie recommendation based on those two movies)
- Random movie generator (“pick for me” feature that fetches a random movie recommendation rom a variety of genres)
- Movie details (click on a movie from the list to see more details like the plot summary, actors, director and ratings)
- Light and Dark mode toggle

### Target Audience
- The app is for anyone who enjoys movies but wants help with the endless options available. By focusing on simplicity and fun, it can appeal to both occasional viewers and more passionate cinephiles.

### Tech Stack
- Frontend: React (Vite)
- Backend: Node.js, Express.js
- Database: MongoDB
- API: ?
- Other Tools: Figma for design, Trello for planning, Excalidraw for diagramming

---

## R2 - Dataflow Diagram
Context Level 0 Diagram:

The diagram below provides an high-level overview of the interaction within the MatchMyMovies app. It shows the user making requests (e.g., selecting genres, getting recommendations), which are processed by the app. The app then communicates with the movie API to retrieve relevant data, which is then displayed to the user. 

![Context Dataflow](docs/digrams/dataflow-diagram-0.png)  

Detailed Level 1 Diagram:  

This detailed diagram below breakdowns the MatchMyMovies app showing the internal processes and how data moves between the User, Frontend (React), Backend (Node.js + Express), Movie API, and Database (MongoDB). The user interacts with the frontend, which sends requests to the backend. The backend then fetches data from the movie API and responds to the frontend. The backend also caches popular requests and stores analytics in the database. 

![Context Dataflow](docs/digrams/dataflow-diagram-1.png)  

---

## R3 - Application Architecture Diagram
![Detailed Dataflow](diagrams/architecture-diagram.png)

---

## R4 - User Stories 
### User Story 1: May (Casual Viewer) 
> "As a casual viewer, she wants to use a "pick for me" button to randomly generate a movie suggestion, So that she can quickly decide on a movie without spending too much time searching and dealing with sign-up processes".

#### Background:
Maya loves relaxing with a good movie after a busy day at work, but she often gets overwhelmed by endless scrolling on streaming platforms. She enjoys experimenting with new genres but isn’t always sure where to start.

#### Needs:
- A quick and easy way to get movie recommendations without wasting time creating an account.
- A tool to combine genres like "Romance + Comedy" or "Drama + Mystery" to find interesting options.
- A fun, random movie generator for when she doesn’t know what she’s in the mood for.

#### Pain Points:
- Decision fatigue from too many options on streaming platforms.
- Lack of a simple way to discover movies that match her preferences.

### User Story 2: Miles (Movie Enthusiast)
> "As a movie enthusiast, I wants to combine two genres to get movie recommendations that match both, So that I can find unique movies that align with my diverse interests without the hassle of signing up".

#### Background:
Miles is a self-proclaimed movie buff who loves exploring connections between films. He often hosts movie nights with friends and enjoys finding thematic pairings that blend different styles or genres.

#### Needs:
- A feature to combine two movies to get unique recommendations for double features.
- A platform that helps him explore lesser-known titles within his favorite genres.
- A random movie suggestion feature to keep his watchlist fresh and surprising.

#### Pain Points:
- Spending hours researching movies to fit a specific theme for his movie nights.
- Difficulty discovering obscure or underrated films in niche genres.

### User Story 3: Mave (Nostalgic Movie Lover) 
> "As a nostalgic movie lover, I want to input specific movies I love to generate recommendations with similar themes or tones, So that I can relive the excitement of my favorite classics and discover new movies with a similar vibe without unnecessary friction".

#### Background:
Mave enjoys revisiting movies that hold nostalgic value for him and exploring new films with similar vibes. He often wants to relive the excitement of classics like Jurassic Park or The Matrix but doesn’t know where to start finding complementary movies.

#### Needs:
- A feature to input specific movies he loves to generate recommendations with similar themes or tones.
- Suggestions for double features that evoke the same mood or spirit as his favorite classics.
- A quick way to create a "movie night experience" centered around familiar favorites and their modern counterparts or lesser-known films.

#### Pain Points:
- Spending too much time searching for movies that match the feel of his favorites.
Frustration with generic recommendations that don’t align with the style or theme he enjoys.
- Mave would use the Movie Pairing feature to input two movies and get tailored recommendations for titles that match his mood, helping him relive the magic of his favorite films while discovering new ones in the process.

---

## R5 - Wireframes
### Desktop
![Placeholder](wireframes/desktop-wireframe.png)

### Tablet
![Placeholder](wireframes/tablet-wireframe.png)

### Mobile
![Placeholder](wireframes/mobile-wireframe.png)

---

## R6 - Planning Board Screenshots

[Trello Board](https://trello.com/invite/b/673b27539a433905d52c2fbc/ATTI29fc651cb65c6291986d9f7403a7989558F983A5/coder-academy-t3a2-full-stack-app-part-a)

### Initial Board
![Initial Board](docs/planning/trello-board-initial.png)

### Midway Board
![Placeholder](docs/planning/trello-board-midway.png)

### Final Board
![Placeholder](planning/board-final.png)


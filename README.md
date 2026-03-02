# cloudy_server

The idea of **Cloudy** as an app is that the world is covered in fog, and as you walk around and explore the world, the fog clears up. Well there's already an app that's up there called "Fog of World" and it looks pretty good. But man, it's 600k VND. And i can't get my payment to work for some reason (thank you Google Play). So I decided to make my own.

This repo will serve as the backend for the app

For the prototype, i'm just going to make it like extremely minimal. Here's the pipeline:

- Android app sends current user location to the server which saves it to a SQLite db
- Another web app fetches the locations and render the map

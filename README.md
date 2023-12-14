# Starfield Achievements

[//]: # (![starfield preview]&#40;preview.png&#41;)

## Description

Starfield Achievements is a simple achievement tracking application. Users can easily
mark off achievements that they have completed in the Starfield game. Easily sort and filter
achievements by completion status, faction, etc.

Data is stored locally on device using
`localStorage`.

## Disclaimer

This project is purely for educational purposes. I built it to practice my web development skills
and because I am a fan of the Starfield game created by Bethesda.

## Limitations

Due to data being stored locally on device, data ***cannot*** be synced across multiple devices.
Example: If you are using your phone to track your achievements, visiting this application on a desktop will not
automatically update. Additionally, since `localStorage` saves data in the browser, using a different browser will
also not be synced with your other achievements.

## Tech Stack

HTML, TailwindCSS, and Javascript(vanilla)

## Road map

- Add backend support
- Simplify method to add/remove filter categories
- Add PWA(Progressive Web App) support
- Transition to Typescript? (still unsure about this)
- Implement JS Framework: React, Svelte, etc (again, unsure about this)
- Add ability to pin an achievement.
    - Pinned achievements will remain on screen regardless of the selected filter
    - show more details about pinned achievement
- More detailed descriptions for each achievement when clicked on.
- Routing - in relation to the previous point. Clicking on an achievement should bring up unique page with additional details

## Contributions

If you are a fellow Starfield fan or if you're just interested in contributing to this project, please feel free
to open an issue and submit a pull request! This application is basically just a to-do application, so it's inherently
simple. However, it would be great to see if evolve into something more complex over time. I do plan to actively
maintain this project with regular updates.
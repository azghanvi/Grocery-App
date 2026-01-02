# Home Grocery

A modern, simple, and progressive web app for managing your grocery list. Share your list with others via WhatsApp and enjoy offline access.

## Features

*   **Add, Edit, and Delete Items:** Easily manage your grocery list.
*   **Search:** Quickly find items in your list.
*   **Checkable Items:** Mark items as you buy them.
*   **Share via WhatsApp:** Share your list with family and friends.
*   **Progressive Web App (PWA):** Install the app on your mobile device or desktop for a native-like experience.
*   **Offline Support:** Access and manage your list even without an internet connection.
*   **Modern UI:** A clean and intuitive user interface built with Tailwind CSS.

## Tech Stack

*   **React:** For the user interface, loaded via a CDN.
*   **Tailwind CSS:** For styling, loaded via a CDN.
*   **Babel Standalone:** To transpile JSX directly in the browser.
*   **Service Worker:** For offline capabilities.

## How to Use

There is no build step required to run this application. Simply open the `index.html` file in your web browser.

## Offline Support and PWA

This application is a Progressive Web App (PWA), which means you can "install" it on your device (mobile or desktop). This will add an icon to your home screen or app drawer, and the app will launch in its own window, just like a native app.

The app also works offline. The first time you load the app with an internet connection, it will cache all the necessary files. After that, you can launch the app and use it even if you don't have an internet connection.


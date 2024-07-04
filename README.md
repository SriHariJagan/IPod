# Mini iPod App

## Overview
The Mini iPod App is a ReactJS application that mimics the functionality of a classic iPod. Users can navigate through different menus, access various features, and listen to music. The app includes a rotating pad for menu navigation, a center button for selection, and a menu button for going back to the main menu.

## Features
- **Main Menu**: Access Settings, Music, Coverflow, and Games.
- **Settings Menu**: Toggle the theme and restart the app.
- **Music Menu**: Browse and play All Songs, view Albums, and Artists.
  - **All Songs**: Plays some songs.
  - **Albums**: Shows some of the music albums.
  - **Artists**: Shows some of the artists.
- **Coverflow Menu**: Display an image.
- **Games Menu**: Show a list of games.
- **Rotating Pad**: Slide to navigate through the menu.
- **Center Button**: Select a menu item.
- **Menu Button**: Go back to the main menu.

## User Stories
- Users can access features like Settings, Menu, Music, and Coverflow in the iPod.
- Users can navigate back to the main menu from any menu by clicking the Menu button.
- Users can access the main menu from the home screen using the Menu button.
- Users can go inside a menu by clicking the center button.
- Users can click and hold on the circular menu and move the mouse in a circular fashion to navigate the menu.
- Users can listen to music by selecting "All Songs" inside the Music menu.

## Screens
1. **App Homepage**: The initial screen with the main menu.
2. **Menu Display**: Displays the main menu items.
3. **Settings Display**: Options to toggle the theme and restart the app.
4. **Games Display**: List of games.
5. **Music Display**: Sub-menu for All Songs, Albums, and Artists.
6. **Music Player Display**: Plays selected songs.
7. **Wallpaper Display**: Displays an image in the Coverflow menu.

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/mini-ipod-app.git
    ```
2. Navigate to the project directory:
    ```sh
    cd mini-ipod-app
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```
4. Start the application:
    ```sh
    npm start
    ```

## Usage
1. Use the up and down arrow keys to navigate the menu.
2. Press the Enter key to select a menu item.
3. Press the Backspace key to go back to the previous menu.
4. Click and hold on the circular menu and move the mouse in a circular fashion to navigate.

## Code Structure
- **`src/App.js`**: Main component managing state and rendering other components.
- **`src/Menu.js`**: Component for displaying menu items.
- **`src/Screen.js`**: Component for displaying the selected menu item.
- **`src/components`**: Directory containing individual components for different screens and functionalities.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

---

Feel free to modify this `README.md` file as needed for your project.

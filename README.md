# Custom Main Menu for RPG Maker VX Ace

## Overview

This is a simple but flexible custom main menu for RPG Maker VX Ace. It's designed to give your title screen a fresh look with a custom background and buttons. You can easily swap out images, and the script supports hover effects on buttons. It even includes a basic parallax scrolling effect for the background.

This script is fully functional for RPG maker VX Ace and MV. It's a perfect base if you're looking to customize your title screen and add some style to your game’s intro.

## Features

* Customizable background (just replace the image)
* Custom start and exit buttons with hover effects
* Basic parallax background scrolling (optional, if you want to animate the background)
* Easy to integrate and modify to fit your project

## Installation

1. Copy and paste the script into the **Main Materials** section of the script editor.
2. Replace the image paths for the background and buttons in the script with the file names of your own custom images. Make sure your images are placed in the correct folder:

   * Background image: `Graphics/Titles1/`
   * Button images: `Graphics/System/`
3. Customize the button positions, sizes, or effects as needed (check out the `create_start_button` and `create_exit_button` methods).
4. Run the game, and you should see your new main menu with custom buttons and background!

## Customization

* **Images**: Replace the default background and buttons with your own. The images are set to be loaded from the `Graphics/Titles1/` (for background) and `Graphics/System/` (for buttons), so make sure you have your images in those directories.
* **Hover Effects**: The buttons will change slightly when hovered over, but you can adjust the color or even add animations if you'd like.
* **Background Animation**: If you want a simple scrolling effect, leave the `update_background` method as it is, or tweak it to your liking for more complex animations.

## Credits

* **Author**: CrypticTM
* **Version**: 0.8.6f

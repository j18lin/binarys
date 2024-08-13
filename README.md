# Binary Assigner

This project provides a simple web interface to control the states of individual wells on a well plate. The user can toggle the state of each well between two or three states. This is mainly designed to be used with a wireless presenter or a keyboard. The well plate is typically used in laboratory settings, and this interface helps record the state of wells in a user-friendly manner, especially when the user is using a microscope and cannot see the data on the screen.  

https://binary-assigner.vercel.app/

## Features: 
- Set the dimensions of the well plate
- Add description about the specimens in the well plate in a grid shape
- "<-" and "->" keys to cycle between wells
- "B" (Keyboard) or "Action Button" (Clicker) to cycle the state of the well and multiple colors (up to three currently)
- "N" or "PageUp" (Clicker) or "<" (Clicker)  is red/greenif you want only binary states with only red and green colors.
- Exports the data in a JSON file
- Import JSON files to modify existing save states

https://binary-assigner.vercel.app/view
- Import the JSON file to view well plate assignments

Clicker used in project: https://www.amazon.com/gp/product/B09X1G5DCC

## Technical Details

Project was made in TypeScript using Next.JS. The project is licensed [here](./LICENSE.txt)

Thanks to [JoKhannn](https://github.com/JoKhannn) for the README!

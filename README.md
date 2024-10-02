# README.md

# Sketchfab Model Downloader

This project consists of two HTML files that allow users to retrieve and download information about models from Sketchfab based on a username.

## Files

### index.html

This file prompts the user for a Sketchfab username. It retrieves a list of model UIDs associated with that user and provides a button to download the text and image for each model.

**How to Use:**
1. Open `index.html` in a web browser.
2. Enter a valid Sketchfab username in the input field.
3. Click the "Retrieve Models" button.
4. A list of models will appear with a button to download text for each model.

### sketchfab-text-downloader.html

This file accepts a model UID as a query parameter and fetches the associated model's data, including its name, description, and thumbnail image.

**How to Use:**
1. This file is called from `index.html` when the user clicks the download button for a model.
2. The model's UID is passed in the URL, and the model's data is displayed on the page.

## Requirements

- A modern web browser with JavaScript enabled.
- Internet access to fetch data from the Sketchfab API.

## Notes

- Ensure that the Sketchfab API is accessible and that the username entered has public models available.
- The project is intended for educational purposes and to demonstrate the use of APIs in web applications.

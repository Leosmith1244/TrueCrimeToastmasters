# True Crime Toastmasters Website

This is the official static website for the True Crime Toastmasters Club (St. Paul, MN).
Founded by Jennifer.

## Project Structure
- **/css/styles.css**: Contains the base Toastmasters theme + True Crime Overrides (Dark Mode).
- **/*.html**: Static pages (Home, About, Meetings, Case Files, Join).
- **Images**: Sourced via Unsplash direct URLs (no local assets required for initial deploy).

## How to Deploy to Netlify

1. **GitHub**: Upload these files to a new GitHub Repository.
2. **Netlify**:
   - Log in to Netlify.
   - Click "Add new site" -> "Import from an existing project".
   - Select GitHub and choose this repository.
   - **Build Settings**: Leave blank (this is a static site).
   - Click **Deploy Site**.

## Forms
The `join.html` and `contact.html` forms include `data-netlify="true"`. Netlify will automatically detect these forms and start collecting submissions in your Netlify dashboard under the "Forms" tab.

## Customization
To change the meeting date, edit the JavaScript countdown in `index.html` and the table in `meetings.html`.
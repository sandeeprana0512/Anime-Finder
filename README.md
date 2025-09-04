# Anime Finder

A simple Express.js web app to search, explore, and get random anime details using the [Jikan API (v4)](https://jikan.moe/).

---

## Features

- Search anime by title with pagination
- View detailed info about any anime
- Get a random anime recommendation
- Responsive design with modern UI

---

## Tech Stack

- Node.js & Express (ES Modules)
- EJS templating engine
- Axios for API requests
- Body-parser for form data handling
- CSS custom properties and responsive design

---

## Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/sandeeprana0512/Anime-Finder
   cd anime-finder

2. Install dependencies

```bash
npm install
```

3. Start the server

```bash
node index.js
```

4. Open in browser

```bash
Navigate to http://localhost:3000
```

## Project Structure

index.js - Main Express server with routes

views/ - EJS templates:

index.ejs - Main layout and logic

header.ejs, footer.ejs - Common page components

anime.ejs - Anime details display

search.ejs - Search results & pagination

public/ - Static assets (CSS, images)

styles.css - Main stylesheet with CSS variables and responsive styles

package.json - Project metadata & dependencies

## Usage

Use the search bar to look up anime titles.

Click on any anime in the results to see detailed information.

Use pagination buttons to navigate through search results.

Click "Random Anime" to get a random anime suggestion.

## Notes

The app uses the free Jikan API which may have rate limits.

Make sure to have a stable internet connection to fetch API data.

## License

ISC

### Created with ❤️ by Sandeep Rana

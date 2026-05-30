# Daily Wire News

A responsive static news homepage project built with HTML, CSS, and JavaScript. It uses mock news data to display a featured breaking story, category pages, article detail pages, thumbnails, summaries, and related news links.

## Features

- Featured news section for latest and breaking stories
- Category navigation for World, Sports, Technology, and Entertainment
- Article cards with thumbnails, headlines, descriptions, and publish times
- Dynamic navigation between homepage, category pages, and article pages
- Full article page with title, image, article content, and related news
- Responsive layout for desktop, tablet, and mobile screens
- Dummy data stored locally in JavaScript

## Project Structure

```text
news-app/
|-- index.html
|-- category.html
|-- article.html
|-- CNN_clone_web_Based.html
|-- Readme.md
|-- css/
|   `-- style.css
`-- js/
    |-- data.js
    |-- app.js
    |-- category.js
    `-- article.js
```

## How To Run

Open `index.html` in a web browser.

You can also open `CNN_clone_web_Based.html`; it redirects to the homepage.

No installation, build step, or server is required.

## Pages

- `index.html`: Homepage with breaking news, featured story, categories, and more stories
- `category.html`: Displays articles filtered by selected category
- `article.html`: Displays the full article and related news links

## Data Source

The app uses mock news data from `js/data.js`. To add or edit articles, update the `articles` array in that file.

Each article includes:

- `id`
- `category`
- `title`
- `summary`
- `thumbnail`
- `publishedAt`
- `content`

## Testing Checklist

- Open the homepage and confirm featured news appears
- Click each category in the navigation
- Click an article headline or card
- Confirm the article page displays the full story
- Confirm related news links work
- Resize the browser to check mobile and tablet layouts

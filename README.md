# FeastFlash

A simple food delivery website built with HTML, CSS, and JavaScript.

## Features

- Browse food categories
- Search for specific dishes
- View dish details with recipe instructions
- Add items to cart
- Random pricing for each dish
- Dark mode toggle
- Responsive design

## Tech Stack

- HTML5
- CSS3 (Bootstrap 5)
- Vanilla JavaScript

## API

Fetches data from [TheMealDB API](https://www.themealdb.com/api.php):

- Categories: `themealdb.com/api/json/v1/1/categories.php`
- Search: `themealdb.com/api/json/v1/1/search.php?s={query}`
- Details: `themealdb.com/api/json/v1/1/lookup.php?i={id}`
- Filter by category: `themealdb.com/api/json/v1/1/filter.php?c={category}`

## How to Run

1. Open `index.html` in a browser
2. Browse categories or search for food
3. Click "See Details" to view recipe
4. Add items to cart

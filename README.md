# async-programming-leaderboard

This project displays the latest topics from the freeCodeCamp Forum in a leaderboard format. It pulls data from the forum's public API, displaying topic titles, categories, number of replies, views, and recent activity.

## Features

- **Latest Topics:** Displays a list of the most recent forum topics.
- **Post Details:** Shows the number of replies, views, and last activity time.
- **Dynamic Data:** The leaderboard updates automatically by fetching data from the forum's API.
- **Responsive Layout:** The table adjusts for different screen sizes, making it mobile-friendly.
- **User Avatars:** Displays avatars of users who posted in each topic.

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- freeCodeCamp API

## Usage

- The leaderboard automatically updates to show new topics, replies, views, and activity.
- Clicking on a topic title will open the respective forum thread.
- Each category is color-coded for easy identification.

## How it Works

1. **Fetching Data:** The `fetchData()` function fetches the latest forum data from `https://cdn.freecodecamp.org/curriculum/forum-latest/latest.json`.
2. **Rendering Data:** The `showLatestPosts()` function processes the API data and updates the table with topic details such as title, replies, views, and last activity time.
3. **Category Links:** Categories are displayed as clickable links that redirect to the respective category page on the forum.
4. **User Avatars:** User avatars are fetched and displayed alongside topic posts for easy identification of contributors.

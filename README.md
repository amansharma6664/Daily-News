# Daily News

Daily News is a React web app that displays top headlines from various categories using NewsAPI. It features infinite scrolling, a loading progress bar, and easy navigation for a smooth news browsing experience.

## Features

- Browse news by category (Business, Entertainment, Health, Science, Sports, Technology, General)
- Infinite scroll for seamless news loading
- Loading bar for progress indication
- Responsive design
- Easy navigation with React Router

## Getting Started

### Prerequisites

- Node.js and npm installed
- A NewsAPI API key ([Get one here](https://newsapi.org/))

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/Daily-News.git
   cd Daily-News
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Create a `.env` file in the root directory and add your NewsAPI key:
   ```
   REACT_APP_NEWS_API=your_api_key_here
   ```

4. Start the development server:
   ```
   npm start
   ```

## Usage

- Select a category from the navigation bar to view top headlines.
- Scroll down to load more news automatically.
- Click "Read More" to open the full article in a new tab.

## Technologies Used

- React
- NewsAPI
- Bootstrap
- react-infinite-scroll-component
- react-top-loading-bar
- react-router-dom


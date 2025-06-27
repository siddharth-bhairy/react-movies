 ## Project Name: React Movie App
A modern React 19 movie app built following the JS Mastery crash course (filed under React JS 19 Full Course). This project showcases fundamental and advanced React concepts including components, hooks, styles, API-integration, optimization, and deployment.

# Features
Functional Components & JSX
Built with React 19+ using Vite, showcasing reusable functional components. 
youtube.com
+3
videohighlight.com
+3
m.facebook.com
+3

Hooks Usage

useState for state management (search term, liked status, movie data)

useEffect for fetching from The Movie DB API and handling side effects. 
videohighlight.com

Tailwind CSS Styling
Styled swiftly via utility-first classes—setup explained in the video. 
videohighlight.com
+1
udemy.com
+1

Search with Debounce
User input is debounced for performance and to avoid excessive API calls. 
videohighlight.com
+1
youtube.com
+1

Trending Movies Feed
Displays both trending and searched movies using TMDB API. 
videohighlight.com

Conditional & Dynamic Rendering
Loading states, errors, conditional UI updates like “liked” button.

# Tech Stack
React 19 with Vite boilerplate

Tailwind CSS for styling

Fetch API for HTTP requests to TMDB

vanilla JS debounce or react-use debounce hook

# How It Works
Search Bar: Captures input, debounces value, passes to API fetcher.

useEffect: Fetches movies on mount and on debounced search term.

State Management: Tracks lists (movies, trending), loading & error statuses.

UI Rendering: Shows loader, errors, or lists depending on state.

MovieCard: Displays title, poster, like button with toggle state.


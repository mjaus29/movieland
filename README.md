# MovieLand - A Dynamic Movie App with React

<div align="center">
  <img src="https://www.markaustria.com/movieland.png" alt="MovieLand Demo" />

[![Portfolio](https://img.shields.io/badge/Portfolio-markaustria.com-darkblue?style=flat&logo=web&logoColor=white)](https://www.markaustria.com/) [![GitHub](https://img.shields.io/badge/GitHub-mjaus29-black?style=flat&logo=github)](https://github.com/mjaus29) [![LinkedIn](https://img.shields.io/badge/LinkedIn-markaustria-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/markaustria/) [![Email](https://img.shields.io/badge/Email-austriamark.mja%40gmail.com-darkred?style=flat&logo=gmail&logoColor=white)](mailto:austriamark.mja@gmail.com)
</div>

## 🌐 Live Site

🚀 Here is a working live site: [movieland.markaustria.com](https://movieland.markaustria.com/)

🗒️ Check out the case study here: [markaustria.com/movieland](https://www.markaustria.com/movieland)

## 📝 Description

Welcome to MovieLand! A responsive React application that allows users to search for movies using the TMDB API while implementing a real-time trending feature that tracks user search patterns to display the most popular searches dynamically.

Many movie discovery platforms lack personalized trending features based on actual user behavior. Traditional movie apps typically display trending content based on pre-determined metrics rather than real user activity within the application itself.

This project aimed to solve this problem by creating a responsive movie search application that not only fetches data from an external API but also tracks and analyzes user search patterns to generate a dynamic trending section.

**Technologies Used:** React, Vite, Tailwind CSS, Appwrite, TMDB API

## 📖 Table of Contents

- [Features](#-features)
- [Installation](#%EF%B8%8F-setup-project)
- [How to Contribute](#%EF%B8%8F-how-to-contribute)
- [Bug / Feature Request](#-bug--feature-request)
- [Future Enhancements](#-future-enhancements)
- [Acknowledgements](#-acknowledgements)

## ✨ Features

- **Trending Algorithm:** Implemented a custom algorithm that tracks user searches, stores them in an Appwrite database, and displays the top five most searched movies in real-time, creating a Netflix-like trending section based on actual user behavior.
- **Optimized Search with Debouncing:** Implemented input debouncing using the useDebounce hook from react-use to prevent excessive API calls, improving performance by waiting for users to stop typing before making requests.
- **Responsive Component Architecture:** Created a modular component structure with presentational components like MovieCard that accept props for rendering, making the application maintainable and scalable while ensuring consistent UI across all device sizes.

## 🛠️ Setup Project

To get this project up and running in your development environment, follow these step-by-step instructions.

### 🍴 Prerequisites

We need to install or make sure that these tools are pre-installed on your machine:

- [Git](https://git-scm.com/downloads)
- [NodeJS](https://nodejs.org/en/download/)
- [NPM](https://docs.npmjs.com/getting-started/installing-node)

### 🚀 Install Project

1. Clone the Repository

   ```bash
   git clone https://github.com/mjaus29/movieland.git
   ```

2. Navigate into the project directory

   ```bash
   cd movieland
   ```

3. Install dependencies

   ```bash
   npm install
   ```

4. Set up environment variables

   Create a `.env.local` file in the root directory with the following variables:

   ```
   VITE_TMDB_API_KEY=your_tmdb_api_key
   VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
   VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
   VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
   ```

5. Start the application

   ```bash
   npm run dev
   ```

6. Open your web browser and navigate to <a href="http://localhost:5173" target="_blank">http://localhost:5173</a> to see the project running.

## ⚒️ How to Contribute

Want to contribute? Great!

To fix a bug or enhance an existing module, follow these steps:

- Fork the repo
- Create a new branch (`git checkout -b improve-feature`)
- Make the appropriate changes in the files
- Add changes to reflect the changes made
- Commit your changes (`git commit -am 'Improve feature'`)
- Push to the branch (`git push origin improve-feature`)
- Create a Pull Request

### 📩 Bug / Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/mjaus29/movieland/issues/new) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/mjaus29/movieland/issues/new). Please include sample queries and their corresponding results.

### ✅ Future Enhancements

- [ ] Implement user authentication to provide personalized movie recommendations
- [ ] Add movie details page with cast information and similar movies
- [ ] Integrate watchlist functionality for users to save movies for later
- [ ] Implement advanced filtering options by genre, year, and rating

### 📚 Acknowledgements

Special thanks to JSM for the inspiration and guidance on this project.

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-markaustria.com-darkblue?style=flat&logo=web&logoColor=white)](https://www.markaustria.com/) [![GitHub](https://img.shields.io/badge/GitHub-mjaus29-black?style=flat&logo=github)](https://github.com/mjaus29) [![LinkedIn](https://img.shields.io/badge/LinkedIn-markaustria-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/markaustria/) [![Email](https://img.shields.io/badge/Email-austriamark.mja%40gmail.com-darkred?style=flat&logo=gmail&logoColor=white)](mailto:austriamark.mja@gmail.com)
</div>

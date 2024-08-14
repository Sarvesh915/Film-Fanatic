# FilmFanatic

**FilmFanatic** is a movie search application built with modern web technologies, including React.js, Tailwind CSS, Next.js, MongoDB, and the IMDB API. The application allows users to search for movies, view details, and manage their favorite lists, all with a sleek and responsive user interface.



## Features

- Movie search functionality using IMDB API
- Detailed movie information
- User authentication and favorite list management
- Responsive and intuitive UI
- Deployed on Vercel for high performance

## Technologies Used

- **Frontend:**
  - React.js
  - Tailwind CSS
  - Next.js
- **Backend:**
  - Node.js
  - Express.js
  - MongoDB
- **External API:**
  - IMDB API
- **Deployment:**
  - Vercel

## Installation

To get a local copy up and running, follow these steps:

1. **Clone the repository:**

```bash
git clone https://github.com/sarveshsce/filmFanatic.git
cd FilmFanatic
```

2. **Install dependencies:**

```bash
npm install
```

3. **Set up environment variables:**

Create a `.env.local` file in the root directory and add the following environment variables:

```env
NEXT_PUBLIC_IMDB_API_KEY=your_imdb_api_key
MONGODB_URI=your_mongodb_uri
NEXTAUTH_URL=http://localhost:3000
```

4. **Run the application:**

```bash
npm run dev
```

5. **Open your browser and navigate to:**

```
http://localhost:3000
```

## Usage

- Register an account or log in if you already have one.
- Use the search bar to find movies by title.
- View detailed information about each movie.
- Add movies to your favorites list for easy access later.


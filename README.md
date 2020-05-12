# Popular-Movies-App-v2
- Retrieve an API key from themoviedb.org 
- Input your API key in gradle.properties file and sync files.
- If the BuildConfig file is not resolved in MainActivity and DetailActivity then use the below line
  
  `import com.example.moviesapp.BuildConfig;`

## Description
- Shows popular movies in a recyclerview using the above mentioned API.
- Uses retrofit to fetch the data.
- Clicking on the movie poster reveals the details about the movie and also list of available trailers.
- You can sort the movies by:
  - Most Popular
  - Highest Rated
  - Favourite Movies

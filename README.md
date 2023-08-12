IMDB Movie APP 

- The dashboard features an interactive movie search functionality using the OMDB API.

- Two distinct input fields are included on the dashboard:
  - An input field for users to enter their OMDB API key. 🔑
  - An input field for users to enter the movie title they want to search for. 🎥

- User-friendly validation is implemented to ensure that both input fields are not empty before proceeding with the search.

- A single "Search" button is provided, which users can click to initiate the search process based on the provided API key and movie title. 🚀

- To enhance user experience during the data fetching process, a custom spinning loader is displayed. This loader is implemented using CSS and is shown while data is being fetched from the OMDB API. The spinning loader is hidden once the data is successfully fetched or if an error occurs. ⏳

- For each movie that matches the search query, a dynamic card is displayed:
  - The movie's poster is shown. 📸
  - The movie's title and release year are displayed. 📅
  - An option labeled "More Details" is provided, which links to the IMDB page for that specific movie using its unique imdbID. 📚

- Effective error management is implemented. In cases where errors occur, such as "Invalid API Key," users receive meaningful feedback that helps them understand and address the issue. ❌

- The dashboard design is responsive and adaptive, ensuring optimal performance across both mobile and desktop devices. This responsive design enhances user accessibility and usability. 📱💻

Overall, I have successfully created an interactive movie search dashboard that integrates with the OMDB API, offering users a 🌟 seamless experience to search for movies, view details, and enjoy responsive design across various devices. 🎉🎞️

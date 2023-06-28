MusicWiki is an Android app developed using Kotlin that provides information about different music genres, including albums, artists, and tracks associated with each genre. The app utilizes the Last.fm API to fetch and display the data. This README file provides a detailed overview of the app's features, development decisions, and assumptions made during the development process.

Features
1.Displaying List of Genres:
  -The app displays a list of the top 10 genres initially.
  -Clicking on the expand button reveals the entire list of genres on the same screen.

2.Genre Information Page:
  -Clicking on a genre from the list takes the user to a page dedicated to that genre.
  -The page displays the genre title and description.
  -It includes separate sections for top albums, top tracks, and top artists associated with the genre.

3.Album Details:
  -Clicking on an album in the genre information page displays detailed information about the album.
  -The album details page includes the cover image (if available), title, and artist information.
  -It also provides a description and the associated genres.
  -Clicking on a genre in the album details page displays the details about that genre, similar to the flow on the first screen.

4.Artist Details:
  -Clicking on an artist in the genre information page displays detailed information about the artist.
  -The artist details page includes the artist image (if available), title, play count, and follower count.
  -It also provides a description, a list of top tracks, top albums, and the associated genres.
  -Clicking on a genre in the artist details page displays the details about that genre, similar to the flow on the first screen.
  -Clicking on an album in the artist details page shows its information.


Development Decisions

1.Technology Stack:
  -The app is developed using Kotlin, the official programming language for Android app development.
  -The Last.fm API is utilized to fetch genre, album, artist, and track information.

2.Architecture:
  -The app follows the Model-View-ViewModel (MVVM) architectural pattern, which promotes separation of concerns and facilitates testability and maintainability.
  -Android Architecture Components such as ViewModel, LiveData, and Room can be used to implement the MVVM architecture.

3.User Interface:
  -The app's user interface is designed to be clean, intuitive, and responsive across different Android devices.
  -Android XML layout files are used to define the app's UI components, and styles can be applied to ensure consistency.
  -Material Design guidelines can be followed to provide a visually appealing and cohesive user experience.

4.Networking:
  -The Last.fm API is accessed using network requests, such as HTTP GET requests, to fetch the required data.
  -Libraries like Retrofit or Volley can be used to handle network requests and manage the API integration efficiently.

5.Data Persistence:
  -Local data caching and persistence can be implemented using a local database, such as Room, to store and retrieve fetched data.
  -This helps improve app performance, reduces reliance on network requests, and allows offline access to previously fetched data.

6.Error Handling and Edge Cases:
  -Proper error handling should be implemented to handle cases where network requests fail or return empty responses.
  -Graceful fallbacks or error messages should be displayed to the user in case of errors or unexpected situations.

7.Code Organization and Version Control:
  -The app's codebase should be organized into appropriate packages and classes to maintain a modular and scalable structure.
  -Version control should be used, and the code should be committed to a version control system (e.g., Git) to track changes and collaborate with other developers effectively.

8.Code Documentation and Comments:
  -The code should be well-documented with comments to explain the purpose and functionality of different classes, functions, and components.
  -Clear and meaningful variable and function names should be used to enhance code readability.

Assumptions
1.The Last.fm API provides reliable and up-to-date data for music genres, albums, artists, and tracks.
2.The app will require the appropriate Android permissions to access network connectivity and, if applicable, to cache data locally.
3.The app will support various screen sizes and orientations to provide a consistent experience on different Android devices.
4.The app's design and functionality can be extended to include additional features or enhance existing ones based on future requirements.

![WhatsApp Image 2023-06-28 at 2 15 45 PM](https://github.com/Mandil-18/Music_Wiki/assets/88775131/a79cb549-7fd5-4f36-9058-327ccc88f2ee)
![WhatsApp Image 2023-06-28 at 2 15 47 PM](https://github.com/Mandil-18/Music_Wiki/assets/88775131/a12c6026-293c-4e68-a967-b95fd22e61cb)
![WhatsApp Image 2023-06-28 at 2 15 49 PM](https://github.com/Mandil-18/Music_Wiki/assets/88775131/9683cadb-9420-46d7-8d20-d98f28f2e27c)
![WhatsApp Image 2023-06-28 at 2 15 51 PM](https://github.com/Mandil-18/Music_Wiki/assets/88775131/31dfd244-c1c0-4844-b5c6-2019b9787b9b)
![WhatsApp Image 2023-06-28 at 2 15 52 PM](https://github.com/Mandil-18/Music_Wiki/assets/88775131/79e6d30a-971b-491e-a2ef-c1db411772ae)
![WhatsApp Image 2023-06-28 at 2 15 53 PM](https://github.com/Mandil-18/Music_Wiki/assets/88775131/8e179e71-a8a5-4bc3-a006-aec8bb8629e2)

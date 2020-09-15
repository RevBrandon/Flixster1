
## Flix Part 1
https://i.imgur.com/LXcwn6V.gifv
#### REQUIRED (10pts)
- [ x] (10pts) User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.

#### BONUS
- [x ] (2pts) Views should be responsive for both landscape/portrait mode.
   - [x] (1pt) In portrait mode, the poster image, title, and movie overview is shown.
   - [ x] (1pt) In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.

- [x ] (2pts) Display a nice default [https://i.imgur.com/LXcwn6V.gifv](https://guides.codepath.org/android/Displaying-Images-with-the-Glide-Library#advanced-usage) for each image during loading
- [x ] (2pts) Improved the user interface by experimenting with styling and coloring.
- [x ] (2pts) For popular movies (i.e. a movie voted for more than 5 stars), the full backdrop image is displayed. Otherwise, a poster image, the movie title, and overview is listed. Use Heterogenous RecyclerViews and use different ViewHolder layout files for popular movies and less popular ones.

### App Walkthough GIF

<img src="https://i.imgur.com/LXcwn6V.gifv" width=250><br>

### Notes
While running this appliction the emulator made my computer system run drastically slow  and often I had to wait for the emulator to catch up to the work and changes I was making to my code in the android studio application. 

### Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Androids
## Flix Part 2

### User Stories

#### REQUIRED (10pts)

- [x ] (8pts) Expose details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
- [x ] (2pts) Allow video posts to be played in full-screen using the YouTubePlayerView.

#### BONUS

- [x ] Trailers for popular movies are played automatically when the movie is selected (1 point).
  - [x ] When clicking on a popular movie (i.e. a movie voted for more than 5 stars) the video should be played immediately.
  - [x ] Less popular videos rely on the detailed page should show an image preview that can initiate playing a YouTube video.
- [x ] Add a play icon overlay to popular movies to indicate that the movie can be played (1 point).
- [x ] Apply the popular ButterKnife annotation library to reduce view boilerplate. (1 point)
- [ x] Add a rounded corners for the images using the Glide transformations. (1 point)

### App Walkthough GIF

 Add the URL to your animated app walkthough `gif`https://i.imgur.com/t98TXpQ.gifvin the image tag below, . Make sure the gif actually renders and animates when viewing this README.
<img src="https://i.imgur.com/t98TXpQ.gifv width=250><br>
          https://i.imgur.com/t98TXpQ.gifv

### Notes

Describe any challenges encountered while building the app.
N/A 

## Open-source libraries used
- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

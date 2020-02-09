# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthough GIF

<img src="http://g.recordit.co/NpPY9aO9zl.gif" width=250><br>

### Notes
I ran into one issue where the app would crash when the collection view was loaded. It turned out that the reuse identifer was blank. I was pretty sure that I typed it in, but maybe I didn't hit enter? It took a while to identify the problem but after that it was smooth sailing.

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthough GIF

<img src="http://g.recordit.co/qqJ1wGFMd0.gif" width=250><br>

### Notes
Describe any challenges encountered while building the app.
I'm using a school computer, and don't have admin rights. It was kind of hard to get the Ruby pods to install correctly without being able to sudo. 

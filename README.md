# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

📝 `NOTE - PASTE PART 2 SNIPPET HERE:` Paste the README template for part 2 of this assignment here at the top. This will show a history of your development process, which users stories you completed and how your app looked and functioned at each step.

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

### App Walkthrough GIF
`TODO://` Add the URL to your animated app walkthough `gif` in the image tag below, `YOUR_GIF_URL_HERE`. Make sure the gif actually renders and animates when viewing this README. (🚫 Remove this paragraph after after adding gif)

<img src="https://imgur.com/a/xGWEeoJ.gif" width=250><br>

### Notes
When using brew, the default download folder is usr/local/bin as opposed to the given /opt... This caused a lot of confusion on my part as I couldn't figure out which commands to run. I ended up reinstalling homebrew in the provided listed opt folder, only to find that this wouldn't allow me to install cocoapods correctly. For future situations, use the brew doctor command to quickly understand what is wrong. I only did this after running a lot of unnecessary commands.

Another thing is that after using the pod install and running the new application, my app wouldn't build as it said that AlamofireImage wasn't a package. To resolve this, I had to click on PodFile and check the "Target Membership" for the AlamofireImage. It seemed to work after this. 

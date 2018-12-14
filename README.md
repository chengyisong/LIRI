# LIRI

## INSTRUCTIONS:

* LIRI is a _Language_ Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

* To use this app, there'are a couple of things you could do:
   * `concert-this`
   * `spotify-this-song`
   * `movie-this`
   * `do-what-it-says`

### Link to DEMO Video:
   * https://drive.google.com/open?id=1d3E3IVShtupj-RWANzg_n8Bjrurs0SzC

### Before You Start:

You would need your spotify API accounts for this app. Please provide your sopity ID and secret in the .env file within the root folder of this app.

### Command Line Inputs: 
  * 1) Search for concerts based on artist name:
    Command: 
    ```
    `node liri.js concert-this <artist/band name here>`
    ```
    Example:
    ```
    `node liri.js concert-this Ariana Grande`
    ```

  * 2) Search for song information based on the song's name: 
    Command: 
    ```
    `node liri.js spotify-this-song '<song name here>'`
    ```
    Example:
    ```
    `node liri.js spotify-this-song The Middle`
    ```

  * 3) Search for movie information based on the movie's name: 
    Command: 
    ```
    `node liri.js movie-this '<movie name here>'`
    ```
    Example:
    ```
    `node liri.js movie-this pirates of the caribbean`
    ```

  * 4) Run the query based on the "random.txt" file: 
    Command: 
    ```
   `node liri.js do-what-it-says`
    ```
    Example in the "random.txt" file: 
    "concert-this,Jason Mraz"

### Logging Commands and Responses

  * All command line and responses will be logged in the "log.txt" file in the folder. 
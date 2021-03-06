# Tubify
![](readme-demo/demo.gif)



## Website Description

Ever wanted to share songs with a person without having to link your personal playlist? Perhaps you have Spotify Free and the ads bother you? To combat this, you can convert your Spotify playlist to a Youtube playlist. But even here, conversion websites may prompt for Spotify credentials or registration, and you can't bother trusting the website for such a small task.

Tubify is a website dedicated to promoting those needs; simply link a Spotify playlist and let it convert! Due to YouTube's set limit for anonymous playlists, it can only support <b>up to 50 unique songs per playlist</b>.

Try it [here](https://ptjung.github.io/Tubify/)!

## Known Bugs

* Pairs of songs with incredibly similar names may be thought of as the same song, skipped due to duplicate handling
* This service shares a number of requests in a timeframe and can run out at any point temporarily
* Invalid URIs with the correct link format will convert forever
* In rare occasions, different YouTube videos will be selected

## Changelog

(March 7, 2020)
* Slight improvement to Spotify-YouTube-Converter.
  * Now notifies the user when too many requests have been made
  
(March 1, 2020)
* Improvements to Spotify-YouTube-Converter.
  * Bug fix: linking errors caused the converter to stop working
  * Bug fix: songs with special characters might not convert
  * Improved the time it takes to convert a playlist
  * Improved the rate of success for song picking
  * Reduced the number of search query requests sent to Google
  * Added conversion animation

(February 9, 2020)
* Quick patches to Spotify-YouTube-Converter.
  * Bug fix: the text forms do not reset on refresh
  * Bug fix: the "finish" event happens too early
  * Improved the YouTube picking algorithm
  * Improved website error reporting

(February 8, 2020)
* Bug fixes to Spotify-YouTube-Converter.
  * Bug fix: larger playlists do not have all of their songs converted
  * Bug fix: permanent freezing when converting specific songs
* Released Spotify-YouTube-Converter.

Spotify is the most widely used music streaming service nowadays. This application currently
catalogs about 60 million tracks. To choose the songs to make available or to recommend certain
songs to its users, it is interesting to be able to predict the popularity of a song. This is what we
will try to do here.

We have 10 000 songs each characterized by 15 variables : the positiveness of the track, the
release year of track, the relative metric of the track being acoustic, the relative measurement of the
track being danceable, the length of the track in milliseconds, the energy of the track, the relative
ratio of the track being instrumental, the primary key of the track, Bb meaning A ] or B [, the
relative duration of the track sounding like a live performance, the relative loudness of the track
in the typical range [-60,0] in decibel, a binary value representing whether the track starts with a
major [encoded 1] chord progression or not [encoded 0], the relative length of the track containing
any kind of human voice, the tempo of the track in Beat Per Minute, the popularity of the song
rated by a number between 0 and 100 and another variable pop.class correspond to the same thing
but in this case, the popularity is rated by a letter from A to D.

The idea is to apply various machine learning methods seen in class on these data to draw a
prediction of the popularity by going through a supervised regression problem and then through
a supervised classification problem. We will first perform a descriptive analysis of the data. Then
we will implement linear machine learning methods. Finally, we will implement more sophisticated
methods such as CART, random forest, or neural network.

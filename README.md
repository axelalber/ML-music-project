# ML music project
 Generate music with neural network

This project was heavily inspired by Skuldur  (https://github.com/Skuldur/Classical-Piano-Composer) and Musikalkemist (https://github.com/musikalkemist/generating-melodies-with-rnn-lstm).

This 5 day project was made as way for me to learn Neural Networks. Since I’m a musician , this felt like the perfect way to learn Neural Networks. I started off watching Musikalkemist’s tutorials on Youtube, and also using the same dataset. Then I made a similar solution to that with some changes. This resulted in some nice melodies. 

Then I wanted to try generating more complex music, and then also using a dataset with more complex music. Here is where I started to encounter some problems. With all chords and notes (without information about note length), the number of classes was over 1600. So I decided to treat the more complex music in Musikalkemist’s way. I had to round all note lengths to closest 16th note. I then also treated Chords as notes (highest note in the chord). I hoped that this would result in some nice melodies, but no. 

Since this was only a 5 day project, the training time of the models was limited. I trained different models during the night, and then tried them out in the morning the day after. With more time, I could train models over several days, and that’s probably whats needed to get the model to learn the patterns.

The highlights of this project is getting some nice melodies with Musikalkemist’s way and dataset. I’ve learned a lot about neural networks, especially lstm. This project was very fun to do.

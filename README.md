
# Music Curation and Analytics 26/27 Portfolio 

<!-- Version 1.0 -->
## Week 1 

The theme of my dataset is reinterpretations of popular music, looking at how the same song can change when its performed or arranged by different artists. I chose this theme because I listen to quite a wide range of music and I always love when when an artist covers a song in their own unique way, making it sound completely different from the original. This also gives me quite a varied dataset while still having a clear connection between each piece of music. For example, Frankie Vali's *Can't Take My Eyes Off You* was later reinterpreted by Lauryn Hill, while songs such as The Beatles' yesterday is the most covered song in the world. 

I think this theme will work well for the dataset because it gives me access to all three types of music data explored in the course. Notated data could be used to compare musical features between arrangements, acoustic data could be used to compare different recordings, and descriptive data could identify information such as the songwriter, performer, arranger, release date and particular version. This would allow me to look at what can actually be identified and compared between different interpretations of the same song using music data.  


## Week 2

For this task, I chose *Yesterday* by The Beatles because it is the most covered song in popular music history, which made it a good starting point for my dataset to explore how the same song can exist in many different forms. The song has been recorded thousands of times, by huge artists including Marvin Gaye, Frank Sinatra, and Bob Dylan. I transcribed an easy piano arrangement of the song by Hans-Günter Heumann manually into MuseScore. 

As someone with very little experience of reading sheet music, i initially found the transcription quite difficult. However, once I became more familiar with MuseScore and started to understand the notes, I found the application quite easy to navigate and became much faster at transcribing. I particularly liked that MuseScore automatically adjusted the length and spacing of bars and notes, as this made the process much easier for me. 

Some of the additional notation and symbols, such as rests, ties and beamed notes, were a little more difficult to recreate at first, as I had to work out how they were presented and entered within MuseScore. Once I used them a few times the process became much easier. I regularly replayed what I had transcribed to make sure it sounded right, while also comparing it visually with the original arrangement to check that I had recreated it as accurately as possible. 


## Week 3

This week I exported my Yesterday transcription into both MusicXML and MEI and used Verovio to render the MEI file as music notation. I compared three elements from the MusicXML and MEI files: the key signature, time signature and notes. 

[View my Week 3 Verovio page and MusicXML/MEI comparison](verovio.html)  


## Week 4

**Piano Roll**
The piano roll shows the pitches used across the first ten measures of *Yesterday* and their duration. 

![Piano Roll of Yesterday](pianoRoll)

**Pitch Histogram**
The Pitch Histogram shows how frequently different pitches appear within my transcription of *Yesterday*

![Pitch Histogram of Yesterday](pitchHistogram)


## Week 5

For my metadata schema, I chose to include title, artist/performer, composer/songwriter, publisher, original release data and album/source. I chose these elements because I think they provide the most useful information for identifying and comparing the different songs and versions within my dataset. I thought it was important to separate the songwriter from the performer, as this makes it clear who originally created the song and who is performing the particular version in the dataset. 

For *Yesterday*, I selected the Beatles as the performer, John Lennon and Paul McCartney as the composers/songwriters, Northern Songs Ltd as the publisher, 1965 as the original release year, and *Help!* as the album. I found that simple information such as publisher can become more complicated, as publishing rights can change over time. I therefore chose to use the publisher associated with the original release rather that the current rights holder. 

I also enriched the metadata for John Lennon, Paul McCartney and The Beatles by linking each name to its VIAF authority record using auth and auth.uri. Adding these links made me think about how I could keep the metadata consistent if i added more reinterpretations to the dataset. For example, an artist might be credited slightly differently across sources, so linking them to the same authority record gives me a consistent way of identifying them across each version. 





# Music similarity network using audio and mood features - Moodplay Dataset analysis

## Background

Music recommendation is a hot topic for music streaming services (e.g. Spotify, Deezer) as it provides a way to suggest music content to listeners on digital platforms and automatically create playlists. Music recommendation can benefit both music artists who wish to have their music discovered and listened to, and listeners who are looking for music matching their musical preference. There are different approaches to music recommendation and one of them is to look at similarities between music tracks (listeners may like tracks which sound similar to other tracks they like). Finding similarities between songs is challenging and involves considerations about music perception which is, to an extent, subjective. The field of music information research develops computational methods to extract information from music-related data (e.g. audio signals, scores, metadata) that can be used to characterise or classify musical songs. Examples of extracted features include: 
 * audio features: they characterise the acoustic and perceptual properties of audio signals (e.g. loudness, rhythm, pitch, timbre);
 * mood features: they characterise the mood perceived in music (e.g. how calm/exciting, or sad/happy a song sounds, or the mood felt while listening to music (e.g. how energised or calm one feels while listening to a song).

Using such features, it is possible to infer the similarity between different music tracks (tracks that sound similar will likely have similar audio or mood features). Graphs can be generated based on track similarity measures. Analyses of these graphs can help to better understand music perception and devise novel music recommender systems.

## Project description

This project consists in establishing and analysing music similarity networks for a set of music tracks using audio and mood features which are provided in the Moodplay dataset. Network analyses can investigate the effects of various music similarity methods on the resulting graphs. 

## Dataset

This project relies on the Moodplay dataset. This dataset includes audio and mood features for 389 commercial music tracks. 30 seconds audio clips and metadata are also provided.

Dataset Example:

```
song,arousal,valence,dominance
JudgeDread-BigSeven,-0.746238434878926,-0.262106875140381,-0.302248424350005
WillieWilliams-ArmagideonTime,-0.885024303698427,-0.435743761666304,0.766728580371221
KrisKristofferson-WhyMe,-0.959187862888109,-0.584946868146302,0.932920927640635
GramParsons-CryOneMoreTime,-0.791149087627281,-0.554705706857863,0.370832907414266
```


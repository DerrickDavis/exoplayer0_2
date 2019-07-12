# exoplayer0_2

Using exoPlayer to build a media player

Codelabs2 building a media player app from scratch

In this tutorial you learn how to build a media player using the Simple Exoplayer Class to stream media from an app. This app introduces the player view giving access to a binded view for a media player.

I  learned about the ExoPlayerFactory , which sets up the space for the player to run and gives default view, audio, and text  rendering (RenderesFactory), it offers (TrackSelector) and (LoadControl)
This allows user to move through media and allows for buffering the player.

I learned how to build a media source as well as how to blend the activities into the lifecycle. I learned how to build methods for initializing and releasing a mediaplayer, along with building an inlined API call.And lastly in the streaming portion of this lab I learned how to change the Uri value amongst media types(i.e mp3 & mp4)

In the next section of this lab the lab teaches us a bit more about the media source and how to concatenate Media sources.  This section leads in to the topic of Adaptive streaming this section dives into adaptive format implementations. The section focuses on Dash media source type.

Adaptive video playback allows the video information to be divided into small portions and given a duration, the player itself rebuilds and plays them. The portions are available in different variations allowing the player to choose the quality of each portion depending on the available bandwidth.

The next section showed us how to measure the quality of the experience using an inner class called ComponentListener which helps to not pollute the API and makes for better coding. It shows us how to implement the ExoPlayer.EventListenenr which is a member class which extends the player.DefaulktListeneer which implements the ExoPlayer.EventListener interface.
They show us how to register the  listener, how to use a video renderer listener and audio renderer event listener.  From this section you learn that the listeners can collect signals negative impact on Quality of Experience(QoE) they include callbacks such as:
onPlaybackStateChanged, onTracksChanged, onPlayerError…
 
The final section of this lab is all about changing the user interface(user Gui)









![](Mediaplypics/Screen%20Shot%202019-07-11%20at%2011.30.36%20PM.png)


![](Mediaplypics/Screenshot_2019-07-11-23-23-54.png)



![](Mediaplypics/Screenshot_2019-07-11-23-25-11.png)

# Learning Android App

3rd June 
1. played with the constraint layout..much more coming...:)
2. played with the scale type under image view attributes option.
   its a great feature to use in our apps for scaling widgets.
   want to know more about scale type:
   https://developer.android.com/reference/android/widget/ImageView.ScaleType
   https://developer.android.com/reference/android/graphics/Matrix.ScaleToFit.html#CENTER
3.just came to know something really intresting about the units we use to set the size of our widgets and fonts.
  just adding these to my repo incase somebodys also a beginner might find this helpful.
  so basically we have here 2 terms:
  a) dp-device independent pixels(used for resizing the widgets/the contols.)
  b) sp scale independent pixels(used for resizing the fonts or the texts written in our apps)
  reason behind using these instead of the basic terms pixels is-if we've specified dimensions in pixels our image may look
  okay on one device but may look a bit grim on something with a different pixel density.The number of pixels per inch
  varies from one device to another and that can result in our image appearing in different sizes relative to the size of
  the screen.So thats why both these terms are used.hope its helpful.

by eshan_behal

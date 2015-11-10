# LXTapGestureRecognizer
System TapGestureRecognizer cannot set maximum taps, so I create a custom TapGestureRecognizer that can set the maximum tap count of taps

For example, if you have two tap gestures, one for single tap and one for double tap, even you set `requireGestureRecognizerToFail`, if you tap 2 + 1 times, you still get two tap gestures triggered.

By LXTapGestureRecognizer, simply set `maxTapCount` will eliminate addtional taps. Default is 2.

This project is under MIT License.


#### 3D Touch on iOS 9 attention:

seems 3D Touch had different implementation, be careful if you enable allowMoving, the gesture won't ended, still under investigation.

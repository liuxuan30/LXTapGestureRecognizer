# LXTapGestureRecognizer
System TapGestureRecognizer cannot set maximum taps, so I create a custom TapGestureRecognizer that can set the cap. of taps

For example, if you have two tap gestures, one for single tap and one for double tap, even you set `requireGestureRecognizerToFail`, if you tap 2 + 1times, you still get two tap gesture triggered.

By LXTapGestureRecognizer, simply set `maxTapCount` will eliminate addtional taps. Default is 2.

This project is under MIT License.

# Gestures In-Class Exercise

## Recognition Warm-up
In this exercise, you will use hand gestures to transmit a binary string. For this exercise, you will use clockwise and anticlockwise circles to represent the bits 0 and 1 respectively, using a closed fist as a separator. For example, in the gif below, the participant is gesturing a clockwise circle, then an anticlockwise circle, then a clockwise circle indicating the binary string "010".

![Demonstration of the binary string 010](images/binary_gesture_example.gif)

![Diagram of the binary gestures](images/binary_gestures.png | width=100)

Please follow these steps to complete the warm-up:
1. Choose one partner to be the *gesturer* and one partner to be the *reader*.
2. Do a few test symbols to make sure you agree on what the gestures for "0" and "1" look like. Remember that depending on your video chat settings, one or both of your videos may be mirrored.
3. *Gesturer*, use [this site](http://www.unit-conversion.info/texttools/random-string-generator/#data) to generate random 16-bit binary string.
  * Set "Allowed chars" to "01"
  * Set "Length" to 16
  * Press "Generate"
4. *Gesturer*, silently use video chat to transmit your string to the reader. Be sure to use a closed fist to separate one bit from another.
5. *Reader*, watch the gesturer and write down the sequence of 0's and 1's. Do not indicate to the *gesturer* what you think they were trying to transmit, nor tell them when you are ready for the next gesture. Just take down the sequence as best as you can.
6. Now, compare the sequence that the reader recognized with the binary string that the gesturer was trying to transmit. Calculate your [error rate](https://www.wikiwand.com/en/Word_error_rate) by the number of substitutions + insertions + deletions needed to get from the recognized string to the actual string, and divide by the length of the original string. (Which in this case is 16).
  * Alternately, you can use [this tool](http://www.unit-conversion.info/texttools/levenshtein-distance/#data) to calculate the [Levenshtein distance](https://www.wikiwand.com/en/Levenshtein_distance) between the two strings and divide that by 16.

## Gesture Design
Imagine that you are on the design team for a new digital assistant device. Your boss wants users to be able to have the assistant perform ten common tasks by performing a hand gesture to the camera. Collaboratively with your partner, design the ten hand gestures to be used for the system.

# Gestures In-Class Exercise

## Recognition Warm-up
In this exercise, you will use hand gestures to transmit a binary string. For this exercise, you will use clockwise and anticlockwise circles to represent the bits 0 and 1 respectively, using a closed fist as a separator. For example, in the gif below, the participant is gesturing a clockwise circle, then an anticlockwise circle, then a clockwise circle indicating the binary string "010".

<img src="images/binary_gesture_example.gif" width="300"> <img src="images/binary_gestures.png" width="300">

Please follow these steps to complete the warm-up:
1. Choose one partner to be the *gesturer* and one partner to be the *reader*.
2. Do a few test symbols to make sure you agree on what the gestures for "0" and "1" look like. Remember that depending on your video chat settings, one or both of your videos may be mirrored.
3. *Gesturer*, use [this site](http://www.unit-conversion.info/texttools/random-string-generator/#data) to generate a random 16-bit binary string.
    * Set "Allowed chars" to "01"
    * Set "Length" to 16
    * Press "Generate"
4. *Gesturer*, silently use video chat to transmit your string to the reader. Be sure to use a closed fist to separate one bit from another.
5. *Reader*, watch the gesturer and write down the sequence of 0's and 1's. Do not indicate to the *gesturer* what you think they were trying to transmit, nor tell them when you are ready for the next gesture. Just take down the sequence as they sign it as best as you can.
6. Now, compare the sequence that the reader recognized with the binary string that the gesturer was trying to transmit. Calculate your [error rate](https://www.wikiwand.com/en/Word_error_rate) by the number of substitutions + insertions + deletions needed to get from the recognized string to the actual string, and divide by the length of the original string. (Which in this case is 16).
    * Alternately, you can use [this tool](http://www.unit-conversion.info/texttools/levenshtein-distance/#data) to calculate the [Levenshtein distance](https://www.wikiwand.com/en/Levenshtein_distance) between the two strings and divide that by 16.
7. Repeat this process, with the participants swapping roles.

## Gesture Design
Imagine that you are on the design team for a new digital assistant device. Your boss wants users to be able to have the assistant perform ten common tasks by performing a hand gesture to the camera.

Collaboratively with your partner, design the ten hand gestures to be used for the system. Your primary goal for these exercises is to minimize recognition errors. Draw ten boxes for each of the numbers 0-9, and draw an arrow describing the hand movement as in the diagram above. Your gestures may only incorporate the movement of the user's hand - movement of other limbs, facial expressions, etc. may not be part of your encoding. You do not need to use the closed fist to indicate a break between gestures, but you should think about how a user will indicate a transition between gestures, especially if they need to use the same gesture twice in a row.

Once you have designed your ten gestures, repeat the process from the warm-up, but have your random string use the allowed characters "0123456789".

If you have time, try making revisions to your set of gestures and re-testing to see if your changes decreased your error rate.

## Follow-up/Qualtrics Questions
* What was your error rate with two symbols?
* What was your error rate with ten symbols?
* Choose two of the gestural-interface design tips that Thad presented in the previous lecture, and evaluate how your design succeeds or fails to live up to that advice.
* Briefly describe how you would set up a study to evaluate a user's ability to learn and utilize the set of command gestures that you invented. Be sure to indicate what you expect you would learn from the study and justify why the study would yield that information.

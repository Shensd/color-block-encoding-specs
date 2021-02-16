.. Specification Summary

Summary
=======

Rob-CBlock is an encoding and transmission specification with the goal of providing a messaging 
medium in the form of a filter that can be overlaid in live or non-live video. This is achieved
in several parts:

* Source Dimension Considerations

  * Optimal Area Division
* Color Resolution

  * Intensity of Shifts
  * Negative and Positive Color Shifts
  * Fade Distance Between Color Blocks
* Sending Data

  * Encoding

    * Encoding Specification
    * Error Correction Considerations
  * Transmission Speed
  * Calibration Period
  * Considerations Between Live and Non-live Video
* Receiving Data

  * Obtaining Average Color Change
  * Decoding Data With Calibration
  * Decoding Data Without Calibration (stretch goal)

    * Detecting Color Intensity Shifts
    * Detecting Transmission Speed

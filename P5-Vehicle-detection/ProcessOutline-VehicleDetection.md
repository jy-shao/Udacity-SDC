# Self-Driving-Car: Vehicle detection outline

Here is a note of pipeline for vehicle detection as introduced in Udaicty Self-Driving-Car course. There are mainly 3 steps:

- Select/combine features

  - Template matching (may not suitable for car detection)
  - Color histogram (with normalization)
  - Features in different color space
  - HOG feature (gradient feature)
  - Combine and normalise Features

- Build classifier: recommend linear SVM as base classifier.

- Sliding window:

  - Centre multi-detection window for the same car
  - Determine and reject false detection

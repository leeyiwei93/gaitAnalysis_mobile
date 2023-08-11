

## Introduction
This ML Kit Quickstart app that integrates a gait analysis detection at 2 poses during the walk cycle. Toe-off and Heel strike.

## Feature List

Features that are included in this Quickstart app:
* [Pose Detection](https://developers.google.com/ml-kit/vision/pose-detection/android) - Detect the position of the human body in real time.


## How to use the app
1) Download the android development tool kit (android studio)
2) Download this entire repisotory
3) Import this project into android studio and install onto your android phone

This app supports these scenarios: Live Camera

### Live Camera scenario
It uses the camera preview as input and contains these API workflows: Object detection & tracking, Face Detection, Face Mesh Detection, Text Recognition, Barcode Scanning, Image Labeling, and Pose Detection. There's also a settings page that allows you to configure several options:
* Camera
    * Preview size - Specify the preview size of rear/front camera manually (Default size is chosen appropriately based on screen size)
    * Enable live viewport - Toggle between blocking camera preview by API processing and result rendering or not
* Pose Detection
    * Performance mode -- Allows you to switch between "Fast" and "Accurate" operation mode
    * Show in-frame likelihood -- Displays InFrameLikelihood score for each landmark
    * Visualize z value -- Uses different colors to indicate z difference (red: smaller z, blue: larger z)
    * Rescale z value for visualization -- Maps the smallest z value to the most red and the largest z value to the most blue. This makes z difference more obvious
    * Run classification -- Classify toe-off and heel strike poses.

## Support

* [Documentation](https://developers.google.com/ml-kit/guides)
* [API Reference](https://developers.google.com/ml-kit/reference/android)
* [Stack Overflow](https://stackoverflow.com/questions/tagged/google-mlkit)

## License

Copyright 2020 Google, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.

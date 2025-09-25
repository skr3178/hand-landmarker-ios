# MediaPipe iOS Samples

This repository contains iOS sample applications demonstrating MediaPipe capabilities for hand and pose landmark detection.

## Projects Included

### 1. Hand Landmarker
- **Location**: `examples/hand_landmarker/ios/`
- **Description**: Real-time hand landmark detection using MediaPipe
- **Features**: 
  - Camera-based hand tracking
  - Media library integration
  - Real-time hand pose analysis

### 2. Pose Landmarker  
- **Location**: `examples/pose_landmarker/ios/`
- **Description**: Real-time pose landmark detection using MediaPipe
- **Features**:
  - Camera-based pose tracking
  - Media library integration
  - Real-time body pose analysis

## Getting Started

### Prerequisites
- Xcode 12.0 or later
- iOS 13.0 or later
- CocoaPods

### Installation

1. Clone this repository:
```bash
git clone https://github.com/skr3178/mediapipe-ios-samples.git
cd mediapipe-ios-samples
```

2. Navigate to the desired project:
```bash
cd examples/hand_landmarker/ios/
# or
cd examples/pose_landmarker/ios/
```

3. Install dependencies:
```bash
pod install
```

4. Open the workspace in Xcode:
```bash
open HandLandmarker.xcworkspace
# or
open PoseLandmarker.xcworkspace
```

5. Build and run the project on your iOS device or simulator.

## Requirements

- iOS 13.0+
- Xcode 12.0+
- CocoaPods

## License

This project contains sample code for educational purposes. Please refer to the original MediaPipe documentation for licensing terms.

## Contributing

This is a sample repository. For issues and contributions related to MediaPipe, please refer to the official MediaPipe repository.


## 
Running on iOS iphone 12 simulator

Functions with some lag and accuracy issues
Frames/sec of the video is higher than the inference rate of the model @ 22 Hz

Need a better performance model
App works on photos, videos and live strema feed

As of now, mediapipe hosts only one model for hand pose detection. 
The training data is not available publicly. However, the metadata is. 
Alternatives exists which are opensource. However not yet been explored in this project. 

Here, they use additional information, to better estimate the hand tracking from monocular dataset. 


![alt text](<Screenshot 2025-09-25 at 11.52.28 AM.png>)
![alt text](<Screenshot 2025-09-25 at 12.37.23 PM.png>)
![alt text](<Screenshot 2025-09-25 at 8.08.58 PM.png>)


<video controls src="ssvid.net--Midnight-Pasta-After-Work-147-AM_360p-ezgif.com-video-cutter.mp4" title="Title"></video>
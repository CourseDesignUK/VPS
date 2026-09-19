Phone VPS Prototype
A lightweight, browser-based Visual Positioning System (VPS) prototype for iPhone and Android.
The project demonstrates how a mobile phone can use its camera, visual anchors and a local coordinate map to establish a position inside a building or training environment.
What it does
The prototype provides:
-  Mobile-friendly camera interface
-  Local X/Y/Z coordinate system
-  Visual anchor/AprilTag-style marker map
-  2D local map
-  Multiple VPS anchors
-  Phone heading
-  Simulated anchor detection
-  Virtual fire AR object
-  Virtual exit AR object
-  LocalStorage map saving
-  VPS map JSON export
-  Responsive phone interface
-  Example aircraft-training environment
Current limitation: the included version does not yet perform real AprilTag/ArUco detection. The Simulate detection button demonstrates the VPS coordinate calculations. A production version should connect a real visual-marker detector and/or ARKit/ARCore tracking.

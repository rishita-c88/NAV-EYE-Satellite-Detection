# NAV-EYE-Satellite-Detection
An advanced AI-powered ship detection system using Satellite imagery. Features a Glassmorphism HUD, Flask/TensorFlow backend, and optimized batch inference. Implements Non-Maximum Suppression (NMS) and pixel-masking for dynamic, high-precision bounding boxes. Built to mitigate cloud interference using custom environmental filters.

### Key Technical Features:
* **Non-Maximum Suppression (NMS):** Merges overlapping detections into a single precise target lock.
* **Dynamic Bounding Boxes:** Analyzes pixel clusters to wrap rectangles tightly around ship hulls.
* **Environmental Guard:** Custom logic to filter out cloud interference and sky-line false positives.
* **Optimized Inference:** Uses batch processing to scan large satellite sectors in real-time.

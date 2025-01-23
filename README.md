# Computer Vision for Shelf Product Detection

This repository contains the implementation of a computer vision-based system to identify products on store shelves from a reference image. This system can assist visually impaired customers and automate store management tasks, such as detecting low-stock or misplaced products.

## Project Overview

### Objective
Develop a computer vision system that:
1. Identifies products on a store shelf from a given reference image for each product.
2. Reports:
   - The number of instances of each product.
   - The dimensions (width and height in pixels) of each instance.
   - The position (center of the bounding box) of each instance in the image reference system.

### Example Output
For a store shelf image:
```
Product 0 - 2 instances found:
  Instance 1 {position: (256, 328), width: 57px, height: 80px}
  Instance 2 {position: (311, 328), width: 57px, height: 80px}
Product 1 - 1 instance found:
  Instance 1 {position: (400, 280), width: 50px, height: 75px}
...
```

### Tracks
1. **Track A - Single Instance Detection:**
   - Develop an object detection system to identify single instances of products from a reference image and a shelf image.
   - The system should correctly identify all products displayed in the shelf image.

2. **Track B - Multiple Instances Detection:**
   - Extend the system from Track A to detect multiple instances of the same product.

## Implementation

### Inputs
- **Reference Images:** Images of individual products.
- **Scene Image:** A picture of a store shelf containing multiple products.

### Outputs
- Number of instances of each product.
- Bounding box dimensions (width, height) for each instance.
- Position of the bounding box center for each instance in the image.


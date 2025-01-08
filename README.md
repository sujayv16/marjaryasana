# Rule-Based Yoga Pose Detection: Marjaryasana (Cat Pose)

This project implements a rule-based system to detect the yoga pose **Marjaryasana (Cat Pose)** using keypoint detection via the **MediaPipe** library. The system analyzes angles, distances, and alignments between keypoints to identify the pose.

---

## Features

- **Keypoint Detection:** Utilizes MediaPipe's Pose module to detect landmarks in images.
- **Rule-Based Analysis:** Implements checks for:
  - Curved back
  - Head-down position
  - Hands and feet in contact with the ground
  - Straight limb alignments
- **Debugging Outputs:** Provides intermediate calculations for better understanding.
- **Test Cases:** Includes validation with three test cases for correct, incorrect, and ambiguous poses.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/yoga-pose-detection.git
   cd yoga-pose-detection

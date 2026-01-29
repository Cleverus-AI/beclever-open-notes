## UPDATELOG (AI & Edge)

### 2026-01
- [AI] Person detection can be adapted to a specific institute within 5,000 images
- [Edge] Added adaptive adjustment of point cropping amount based on object size while preserving object scale
- [Edge] Seperated target module from abnormal behavior classifiers
- [Edge] Added algorithm to control whether tracker embeddings are utilized
- [Edge] Second-phase analysis of ID switching issues in tracking algorithm
  - Issue: When a person is tracked within the ROI and tracking is lost, the ID has been reassigned to a newly detected subject

### 2025-12
- [AI] Add representation space validation for fisheye and monocular abnormal behavior dataset
- [AI] Validated target detection model across deployment sites
- [AI] Added embedding module for more accurate tracking method
- [Edge] Separated Caring-mode mosaic processing from alarm logic
- [Edge] Removed the 'Kill-FASTAPI command' from network python script
- [Edge] Second-phase analysis of ID switching issues in fisheye/monocular tracking

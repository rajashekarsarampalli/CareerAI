# Face-api.js Models

This folder should contain the face detection models for face-api.js.

## Download Required Models

Download these files from: https://github.com/vladmandic/face-api/tree/master/model

### Required Files:
1. `tiny_face_detector_model-weights_manifest.json`
2. `tiny_face_detector_model-shard1`
3. `face_expression_recognition_model-weights_manifest.json`
4. `face_expression_recognition_model-shard1`

Place all 4 files directly in this `/public/models/` folder.

## Why These Models?
- **Tiny Face Detector**: Lightweight face detection (~400KB)
- **Face Expression Recognition**: Detects 7 emotions: happy, sad, angry, neutral, fearful, disgusted, surprised

## File Structure Should Be:
```
frontend/public/models/
├── tiny_face_detector_model-weights_manifest.json
├── tiny_face_detector_model-shard1
├── face_expression_recognition_model-weights_manifest.json
└── face_expression_recognition_model-shard1
```

The interview feature will work without these, but facial expression detection will not be available.

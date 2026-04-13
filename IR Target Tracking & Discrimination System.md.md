This project implements a system-level electro-optical (EO/IR) architecture for detecting and tracking targets in challenging environments such as:

Low contrast thermal scenes
Cluttered backgrounds (ground, clouds, urban)
Degraded visibility (smoke, dust, night)

The framework integrates:

Detector modeling
Radiometric preprocessing
Target detection
Multi-target tracking
Feature-based discrimination
```
├── sensor/
│   ├── thermal_camera/
│   └── calibration/
├── preprocessing/
│   ├── NUC/
│   ├── bad_pixel/
│   └── denoise/
├── detection/
│   ├── blob_detection/
│   └── small_target/
├── tracking/
│   ├── kalman/
│   ├── particle_filter/
│   └── multi_target/
├── discrimination/
│   ├── spectral/
│   ├── motion/
│   └── morphology/
└── classification/
    ├── rule_based/
    └── ML/

```

Supported Detector Types
LWIR Microbolometer (Uncooled)
MWIR (Cooled: InSb / MCT)
Dual-band (MWIR + LWIR) extension







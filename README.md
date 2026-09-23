# WavySeekBar for Sketchware Pro

Advanced neon glow wavy seekbar with dynamic color synchronization and XML attribute support.

## Features
- XML Customization (`waveColor`, `trackThickness`, `glowRadius`).
- Hardware-synced MediaPlayer integration with an 800ms debounce to prevent thumb UI glitches.
- Runtime dynamic color switching.
- Pre-packaged for Sketchware Pro Local Library Manager.

## Installation
1. Download `WavySeekBar_Library.zip` from this repository.
2. Extract the directory into `/.sketchware/libs/local_libs/` on your internal storage.
3. Open Sketchware Pro > Local Library Manager > Enable `WavySeekBar`.

## Implementation

**XML Layout:**
```xml
<com.afridi.wavyseekbar.WavySeekBar
    android:id="@+id/seekbar"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    app:waveColor="#FF3CAA"
    app:trackThickness="10dp"
    app:glowRadius="6dp" />

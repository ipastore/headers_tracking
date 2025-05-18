# Clone all baseline repos
git clone https://github.com/SoccerNet/sn-calibration.git
git clone https://github.com/SoccerNet/sn-tracking.git
git clone https://github.com/TrackingLaboratory/tracklab.git
git clone https://github.com/SoccerNet/sn-jersey-number.git
git clone https://github.com/ultralytics/ultralytics.git
git clone https://github.com/ifzhang/ByteTrack.git

### 📎 ByteTrack Setup on macOS

1. Clone the repo:
```bash
mkdir -p externals && cd externals
git clone https://github.com/ifzhang/ByteTrack.git
cd ByteTrack
```
2. Move setup-macos.patch into ByteTrack folder

```bash
mv ../../patches/setup-macos.patch .
git apply ../setup-macos.patch
pip install -e .
```


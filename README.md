
# Setup for Ubuntu

```
apt-get update

apt-get install -y curl
curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
apt install -y nodejs

# Install OpenCV 2.4.8
apt-get install -y \
    libopencv-core-dev \
    libopencv-highgui-dev \
    libopencv-imgproc-dev \
    libopencv-video-dev \
    libopencv-features2d-dev \
    libopencv-objdetect-dev
```

# Setup for Mac

```
brew install opencv@2
```

# Build

```
npm install
```

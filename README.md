# OpenCV Motion Detector

[![youtube](./assets/youtube_thumbnail.png)](https://youtu.be/z_X5PFkaPwY)

Reference: <https://github.com/methylDragon/opencv-motion-detector>

## Quick Start

### Intel OpenVINO

```bash
docker-compose -f docker-compose-intel-openvino.yml build
```

```bash
xhost +

# Docker Compose
docker-compose -f docker-compose-intel-openvino.yml up

# Kubernetes
kubectl create -f app-pod-intel-openvino.yaml
```

### NVIDIA Jetson

```bash
docker-compose -f docker-compose-nvidia-jetson.yml build
```

```bash
xhost +
docker-compose -f docker-compose-nvidia-jetson.yml up
```

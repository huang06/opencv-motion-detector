# OpenCV Motion Detector

This project demonstrates an OpenCV-based motion detection application, deployable on multiple platforms. It leverages the power of Intel OpenVINO and NVIDIA Jetson for enhanced performance. The application is containerized using Docker, ensuring seamless deployment and scalability.

[![youtube](./assets/youtube_thumbnail.png)](https://youtu.be/z_X5PFkaPwY)

Reference: <https://github.com/methylDragon/opencv-motion-detector>

## Intel OpenVINO

```bash
docker-compose -f docker-compose-intel-openvino.yml build

xhost +
docker-compose -f docker-compose-intel-openvino.yml up
```

## NVIDIA Jetson

```bash
docker-compose -f docker-compose-nvidia-jetson.yml build

xhost +
docker-compose -f docker-compose-nvidia-jetson.yml up
```

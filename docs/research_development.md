# Solutions

Selected perception and robotic systems developed for field operation, integration and validation.

## Multimodal perception for robotics in agricultural and forestry contexts

### Autonomous robotic system for eucalyptus stem selection

Selective thinning reduces forest fuel load, supports eucalyptus management and improves stand productivity. Selecting and removing less vigorous stems allows the remaining trees to grow with less competition for water, sunlight and nutrients. This time-intensive decision is traditionally made by an operator; this system automates the stem-selection stage through an end-to-end perception-to-action workflow.

#### Computer vision algorithm
<iframe
    class="embed"
    src="https://drive.google.com/file/d/1aaoR1yYdbwk1ajm-oTmdGzX2U8KKKSFo/preview"
    title="Computer vision algorithm demonstration"
    loading="lazy"
    allowfullscreen>
</iframe>

#### System integration
<iframe
    class="embed"
    src="https://www.youtube.com/embed/w4GPP8xFd88"
    title="Eucalyptus stem-selection system integration demonstration"
    loading="lazy"
    allowfullscreen>
</iframe>


### Multispectral tree-trunk genus classification

Detection and segmentation of eucalyptus and pine tree trunks using YOLOv5 and YOLOv8 deep-learning models trained on four-channel multispectral imagery (RGB + NIR).

<iframe
    class="embed"
    src="https://www.linkedin.com/embed/feed/update/urn:li:ugcPost:7232755011095584768?compact=1"
    title="Multispectral tree trunk perception demonstration"
    loading="lazy"
    allowfullscreen>
</iframe>

GitHub repository for YOLOv5 training and testing on four-channel images: [yolov5_4chan](https://github.com/daniqsilva25/yolov5_4chan)

GitHub repository for YOLOv8 training and testing on four-channel images: [ultralytics_4chan](https://github.com/daniqsilva25/ultralytics_4chan)


### Vegetation-line clearing perception and implement-control system

#### Perception system interface
<iframe
    class="embed"
    src="https://drive.google.com/file/d/1tTPdHURPhbNwxpqYhY3IoqUWE17gxdVp/preview"
    title="Vegetation line clearing perception interface"
    loading="lazy"
    allowfullscreen>
</iframe>

#### System integration
<iframe
    class="embed"
    src="https://drive.google.com/file/d/1j4SPFlRST0M8NWNtngKAbvEIQ21EM9ey/preview"
    title="Vegetation line clearing system integration"
    loading="lazy"
    allowfullscreen>
</iframe>


### 3D perception and semantic mapping

#### Multispectral perception
<iframe
    class="embed"
    src="https://drive.google.com/file/d/1ygtUJGCvvpbslWktq08uqml2_Y3gYhKx/preview"
    title="Multispectral perception demonstration"
    loading="lazy"
    allowfullscreen>
</iframe>

#### 3D object segmentation
<iframe
    class="embed"
    src="https://drive.google.com/file/d/1Olsd2XO0ReX9poM28DM4m8uUSdG8jFza/preview"
    title="3D object segmentation demonstration"
    loading="lazy"
    allowfullscreen>
</iframe>

#### Semantic mapping
<iframe
    class="embed"
    src="https://drive.google.com/file/d/1_dWl-cNkI9tfQE1qgGh5mDsP8VgBlXB1/preview"
    title="Semantic mapping demonstration"
    loading="lazy"
    allowfullscreen>
</iframe>


### Visible and thermal forest tree trunk detection

Tree-trunk detection in forest environments using GoPro Hero6, FLIR M232, ZED Stereo, Allied Mako G-125 and OAK-D sensors. Models including SSD MobileNet, SSD Inception, SSD ResNet, SSDLite MobileDet, EfficientDet Lite, YOLOv4, YOLOv5, YOLOv7, YOLOR and DETR-ResNet were deployed across Raspberry Pi 4B (CPU), NVIDIA Jetson Nano (GPU), Google Coral USB Accelerator (TPU) and OAK-D’s Intel Movidius Myriad X (VPU) platforms.

#### Visible tree trunk detection
<iframe
    class="embed"
    src="https://drive.google.com/file/d/1l9LZ4d0YMGtUfAcHifPQ_1hFoqBVKltZ/preview"
    title="Visible tree trunk detection demonstration"
    loading="lazy"
    allowfullscreen>
</iframe>

#### Thermal tree trunk detection
<iframe
    class="embed"
    src="https://drive.google.com/file/d/1nmRqQrE5h172MiK5Drw_WLccQ6ZqwuWk/preview"
    title="Thermal tree trunk detection demonstration"
    loading="lazy"
    allowfullscreen>
</iframe>

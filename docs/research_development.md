# Solutions

Selected perception and robotic systems developed for field operation, integration and validation.

## Autonomous robotic system for eucalyptus stem selection

**Challenge:**
Selective thinning depends on an operator identifying which eucalyptus stems should be removed. This is time-consuming and difficult to perform consistently in dense, unstructured forest stands.

**Approach:**
Fuse RGB-Depth data with computer-vision models to detect stems, assess the local stand and select candidates for removal.

**Deployment:**
Integrate the perception pipeline with the robotic platform so that selected stems become actionable targets for the thinning operation.

**Outcome:**
An end-to-end perception-to-action system that reduces reliance on manual stem selection by providing consistent, repeatable candidates for selective-thinning operations.

### Computer vision algorithm

<iframe class="embed" src="https://drive.google.com/file/d/1aaoR1yYdbwk1ajm-oTmdGzX2U8KKKSFo/preview" title="Computer vision algorithm demonstration" loading="lazy" allowfullscreen></iframe>

### System integration

<iframe class="embed" src="https://www.youtube.com/embed/w4GPP8xFd88" title="Eucalyptus stem-selection system integration demonstration" loading="lazy" allowfullscreen></iframe>

---

## Multispectral tree-trunk classification

**Challenge:**
Distinguish eucalyptus and pine tree trunks for forestry inventory and monitoring.

**Approach:**
YOLOv5 and YOLOv8 detection and segmentation models trained on four-channel multispectral imagery (RGB + NIR).

**Deployment:**
Training and evaluation pipelines adapted to four-channel image data.

**Outcome:**
Tree-trunk detection and classification across two forest genera.

<iframe class="embed" src="https://www.linkedin.com/embed/feed/update/urn:li:ugcPost:7232755011095584768?compact=1" title="Multispectral tree trunk perception demonstration" loading="lazy" allowfullscreen></iframe>

[YOLOv5 four-channel repository](https://github.com/daniqsilva25/yolov5_4chan) · [YOLOv8 four-channel repository](https://github.com/daniqsilva25/ultralytics_4chan)

---

## Vegetation-line clearing and implement control

**Challenge:**
Perceive vegetation and coordinate implement control during line-clearing operations.

**Approach:**
Computer-vision perception integrated with the implement-control interface and robotic system.

**Deployment:**
System integration validated through interface and field-operation demonstrations.

**Outcome:**
A perception and control workflow for automated vegetation-line clearing.

### Perception system interface

<iframe class="embed" src="https://drive.google.com/file/d/1tTPdHURPhbNwxpqYhY3IoqUWE17gxdVp/preview" title="Vegetation line clearing perception interface" loading="lazy" allowfullscreen></iframe>

### System integration

<iframe class="embed" src="https://drive.google.com/file/d/1j4SPFlRST0M8NWNtngKAbvEIQ21EM9ey/preview" title="Vegetation line clearing system integration" loading="lazy" allowfullscreen></iframe>

---

## 3D perception and semantic mapping

**Challenge:**
Build spatially meaningful representations of forest environments for autonomous machines.

**Approach:**
Multispectral sensing, 3D object segmentation and semantic mapping.

**Deployment:**
Integrated perception components that produce structured environmental information for downstream robotic tasks.

**Outcome:**
3D and semantic representations that support mapping and scene understanding.

### Multispectral perception

<iframe class="embed" src="https://drive.google.com/file/d/1ygtUJGCvvpbslWktq08uqml2_Y3gYhKx/preview" title="Multispectral perception demonstration" loading="lazy" allowfullscreen></iframe>

### 3D object segmentation

<iframe class="embed" src="https://drive.google.com/file/d/1Olsd2XO0ReX9poM28DM4m8uUSdG8jFza/preview" title="3D object segmentation demonstration" loading="lazy" allowfullscreen></iframe>

### Semantic mapping

<iframe class="embed" src="https://drive.google.com/file/d/1_dWl-cNkI9tfQE1qgGh5mDsP8VgBlXB1/preview" title="Semantic mapping demonstration" loading="lazy" allowfullscreen></iframe>

---

## Visible and thermal tree-trunk detection

**Challenge:**
Maintain tree-trunk detection performance across sensor types and changing forest conditions.

**Approach:**
Visible and thermal cameras paired with SSD, EfficientDet, YOLO, YOLOR and DETR-based object-detection models.

**Deployment:**
Edge inference benchmarked across Raspberry Pi 4B, NVIDIA Jetson Nano, Google Coral USB Accelerator and OAK-D hardware.

**Outcome:**
Comparative evidence for selecting sensors, models and edge hardware for forestry-monitoring robots.

### Visible tree-trunk detection

<iframe class="embed" src="https://drive.google.com/file/d/1l9LZ4d0YMGtUfAcHifPQ_1hFoqBVKltZ/preview" title="Visible tree trunk detection demonstration" loading="lazy" allowfullscreen></iframe>

### Thermal tree-trunk detection

<iframe class="embed" src="https://drive.google.com/file/d/1nmRqQrE5h172MiK5Drw_WLccQ6ZqwuWk/preview" title="Thermal tree trunk detection demonstration" loading="lazy" allowfullscreen></iframe>

# 🩻 Chest X-ray Lesion Detection — Annotation Project  
**Medical Computer Vision | Bounding Box Annotation | Freelance-Ready Portfolio Project**

This repository contains the **Chest X-ray Lesion Detection Dataset**, developed as part of the *Medical AI Data Annotation Portfolio*.  
The dataset features **50 anonymized chest X-ray images**, manually annotated for **mass lesion detection** using **CVAT** and **Label Studio**.  
It is designed for **AI model training**, **educational demonstration**, and **clinical computer vision research**.

---

## 📘 Overview

| Attribute | Description |
|------------|-------------|
| **Modality** | Chest X-ray (Radiography) |
| **Objective** | Detect and localize visible **mass lesions / opacities / tumors** |
| **Annotation Type** | Bounding Boxes |
| **Dataset Size** | 50 X-ray images |
| **Annotation Tool** | [CVAT – Computer Vision Annotation Tool](https://cvat.org/) |
| **Export Formats** | COCO, CSV, Pascal VOC (XML), and YOLO |
| **Primary Task** | Object Detection – bounding box localization of chest mass lesions |

This dataset demonstrates a **structured, multi-format, cross-compatible bounding box annotation pipeline** for medical AI projects.

---

## 📁 Folder Structure

ChestXray-LesionDetection-AnnotationProject/
├── annotated_data/ # Bounding box annotations in 4 formats (COCO, CSV, VOC, YOLO)
│ ├── COCO/
│ ├── CSV/
│ ├── VOC/
│ └── YOLO/
│
├── raw_data/ # 50 unannotated chest X-ray images
│ └── chest_xrays_raw_data_jpg/
│
├── metadata/ # Descriptive mapping files and placeholders
│ └── .keep
│
├── screenshot/ # Annotation workflow screenshots and reports
│ ├── screenshots_png_images/
│ ├── 01_project_overview.pdf
│ ├── 02_raw_data_preview.pdf
│ ├── 03_annotated_samples.pdf
│ └── 04_export_formats_summary.pdf
│
└── README.md # Repository documentation

---

## 🧩 Annotation Schema

| Class ID | Label | Description |
|-----------|--------|-------------|
| 0 | `mass_lesion` | Visible lung mass, tumor, or dense opacity detected in chest X-ray |

Each export format maintains **identical label structure** for direct interoperability between frameworks (COCO ↔ YOLO ↔ VOC ↔ CSV).

---

## ⚙️ Annotation Workflow

| Stage | Description |
|--------|-------------|
| **1. Image Selection** | 50 chest X-rays selected based on clarity and diagnostic relevance. |
| **2. Annotation (CVAT)** | Manual bounding box annotation of visible lesions. |
| **3. Export** | Multi-format export: COCO (JSON), CSV, Pascal VOC (XML), and YOLO (TXT). |
| **4. QA & Validation** | Manual verification for consistency and bounding box accuracy. |
| **5. Documentation** | Workflow screenshots and structured metadata created for reproducibility. |

---

## 🧠 Applications

- Medical **object detection model** training (YOLOv8, Detectron2, TensorFlow OD API).  
- Cross-format dataset conversion and benchmarking.  
- Educational demonstration of medical image annotation workflow.  
- Clinical AI prototype and computer vision R&D.

---

## 🧰 Recommended Tools & Libraries

| Purpose | Suggested Tools |
|----------|------------------|
| Annotation | CVAT, Label Studio, LabelImg |
| Visualization | FiftyOne, matplotlib, OpenCV |
| Conversion | Roboflow, CVAT Export Converter |
| Model Training | YOLOv8, Detectron2, TensorFlow Object Detection API |
| Validation | PyCOCOTools, pandas, XML parsers |

---

## 📸 Screenshot Previews

Project reports and screenshots include:
- `01_project_overview.pdf`  
- `02_raw_data_preview.pdf`  
- `03_annotated_samples.pdf`  
- `04_export_formats_summary.pdf`

These files illustrate the full annotation workflow from **raw input → verified output**.

---

## 📜 License

Licensed under the **MIT License**  
© 2025 Dr. Pradeep Shanmugam — MedDataForAI (Udyam Registered MSME, Government of India)

---

## 🔖 Citation (APA Style)

> Shanmugam, P. (2025). *Chest X-ray Lesion Detection — Annotation Project (v1.0).*  
> MedDataForAI (Udyam Registered MSME, Government of India).  
> Available at: [https://github.com/drpradeepAI/ChestXray-LesionDetection-AnnotationProject](https://github.com/drpradeepAI/ChestXray-LesionDetection-AnnotationProject)

---

## 🧾 Version Control

| Version | Date | Update Description |
|----------|------|--------------------|
| **1.0** | Nov 2025 | Initial release — 50 chest X-rays annotated with bounding boxes in COCO, VOC, CSV, and YOLO formats |
| **1.1 (Planned)** | Early 2026 | Addition of segmentation masks and extended metadata |

---

⭐ **If you find this project helpful, please star the repository and follow my work on GitHub.**  
📫 Contact: **drpradeepai@meddataforai.com** | [LinkedIn](https://linkedin.com/in/drpradeepai)

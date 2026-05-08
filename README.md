# Tlaxcala-Urban-Detection-Dataset

Urban object detection dataset from Tlaxcala, Mexico, developed for the adaptation, fine-tuning, and evaluation of YOLO-based computer vision models in real-world urban environments.

This dataset integrates annotated urban environment images from Tlaxcala, Mexico, for object detection tasks using computer vision models. The database was designed to evaluate and adapt YOLO models in real-world urban scenarios, considering relevant elements for navigation and public-space visual analysis.

---

# Dataset Structure

```text
dataset/
│
├── train/
│   ├── images/
│   └── labels/
│
├── val/
│   ├── images/
│   └── labels/
│
└── test/
    ├── images/
    └── labels/
```

---

# Dataset Information

- Total images included in this public version: **123**
- Annotation format: **YOLO**
- Dataset split:
  - Train
  - Validation
  - Test
<img width="1635" height="962" alt="ChatGPT Image 7 may 2026, 23_04_47" src="https://github.com/user-attachments/assets/c38c8101-e599-43a6-a83b-0ea156fef31c" />
---

# Target Classes

The dataset includes annotations for the following urban object categories:

- Car
- Bicycle
- Traffic Light
- Crosswalk

---

# Purpose

This dataset was designed to support research in:

- Urban object detection
- YOLO fine-tuning
- Embedded computer vision
- Real-world urban scene evaluation
- Assistive technologies

---

# Authors

- Emilio Márquez Martínez
- Ernesto Mendieta Cuecuecha
- Jesús García Ramírez
- Eric Ramos-Aguilar

---

# Associated Paper

**YOLO Meets Tlaxcala: Toward Real-Time Urban Object Detection for Assistive Technology**

https://link.springer.com/chapter/10.1007/978-3-032-08894-9_18

---

# Citation

If you use this dataset, please cite the following work:

```bibtex
@incollection{marquez2026yolo,
  title={YOLO Meets Tlaxcala: Toward Real-Time Urban Object Detection for Assistive Technology},
  author={Márquez Martínez, Emilio and Mendieta Cuecuecha, Ernesto and García Ramírez, Jesús and Ramos-Aguilar, Eric},
  booktitle={Advances in Computing, AI, and ICT for Innovation, Sustainability, and Environmental Stewardship},
  pages={269--282},
  year={2026},
  publisher={Springer},
  doi={10.1007/978-3-032-08894-9_18}
}
```

---

# License

© 2026 Emilio Márquez Martínez, Ernesto Mendieta Cuecuecha, Jesús García Ramírez, and Eric Ramos-Aguilar.

This dataset is licensed under the Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) License.

You are free to:

- Share — copy and redistribute the material
- Adapt — remix, transform, and build upon the material

Under the following terms:

- Attribution — You must give appropriate credit to the original authors
- NonCommercial — You may not use the material for commercial purposes

This dataset is intended exclusively for academic, educational, and research purposes in computer vision and urban object detection.

For more details:
https://creativecommons.org/licenses/by-nc/4.0/

For commercial use or special permissions, please contact the authors:

- Emilio Márquez Martínez ([emarquezm2100@alumno.ipn.mx](mailto:emarquezm2100@alumno.ipn.mx))
- Ernesto Mendieta Cuecuecha ([emendietac2100@alumno.ipn.mx](mailto:emendietac2100@alumno.ipn.mx))
- Jesús García Ramírez ([jegarciara@ipn.mx](mailto:jegarciara@ipn.mx))
- Eric Ramos-Aguilar ([eramosa@ipn.mx](mailto:eramosa@ipn.mx))

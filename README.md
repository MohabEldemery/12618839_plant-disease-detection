[README_Plant_Disease_Detection_12618839.md](https://github.com/user-attachments/files/33941933/README_Plant_Disease_Detection_12618839.md)
# Plant Disease Detection Using Deep Learning

**Course:** Applied Deep Learning  
**Assignment:** 1 – Initiate  
**Matriculation Number:** 12618839  
**Student Name:** Mohab Osama Hassan Hassanin Eldemery  
**Project Type:** Bring your own method

## 1. Project Overview

This project explores the use of deep learning to identify healthy and diseased plant leaves from images. The goal is to develop and evaluate an image classification system that predicts a plant/disease category from a leaf photograph. The project is intended for research and demonstration, not definitive agricultural diagnosis.

## 2. Project Type

The selected project type is **Bring your own method**. An existing public dataset will be used to implement, adapt, and compare deep learning approaches. The final models and experiments may change based on preliminary results, available time, and computing resources.

## 3. Related Scientific Papers

1. **Mohanty, S. P., Hughes, D. P., & Salathé, M. (2016).** *Using Deep Learning for Image-Based Plant Disease Detection.* Frontiers in Plant Science, 7, 1419. https://doi.org/10.3389/fpls.2016.01419  
   This paper explores convolutional neural networks for identifying plant diseases from leaf images and provides a foundation for the project.

2. **Too, E. C., Yujian, L., Njuki, S., & Yingchun, L. (2019).** *A Comparative Study of Fine-Tuning Deep Learning Models for Plant Disease Identification.* Computers and Electronics in Agriculture, 161, 272–279. https://doi.org/10.1016/j.compag.2018.03.032  
   This paper compares fine-tuned deep learning models and informs the planned model selection and experiments.

## 4. Dataset

The initial dataset is **PlantVillage**, a public collection of labeled images of healthy and diseased plant leaves. The version in TensorFlow Datasets contains **54,303 images across 38 plant/disease classes**.

Dataset source: https://www.tensorflow.org/datasets/catalog/plant_village

The project may use the full dataset or a selected subset depending on feasibility. Images will be inspected and prepared for training, validation, and testing. Any changes to the dataset or scope will be documented.

## 5. Planned Approach

1. Inspect the dataset and prepare images and labels.
2. Build a working image classification baseline using a convolutional neural network (CNN) or a suitable pretrained model.
3. Explore improvements such as data augmentation, transfer learning, fine-tuning, or alternative architectures.
4. Evaluate performance using accuracy and, where appropriate, precision, recall, F1-score, and a confusion matrix.
5. Develop a simple application to demonstrate predictions from uploaded leaf images during Assignment 3.

Specific models, image dimensions, hyperparameters, and the final number of classes will be decided during implementation. Changes will be explained in the repository.

## 6. Work Breakdown and Time Estimates

| Task | Estimated Hours |
| --- | ---: |
| Literature review and project planning | 5 |
| Dataset acquisition and preprocessing | 7 |
| Model design and implementation | 8 |
| Model training | 10 |
| Fine-tuning, experiments, and evaluation | 10 |
| Demo application | 7 |
| Final report | 5 |
| Presentation preparation | 3 |
| **Total** | **55** |

These are initial estimates for the full course project and may be updated as the work progresses.

## 7. Expected Deliverables

- **Assignment 1:** Project proposal, dataset plan, research references, and estimated work schedule.
- **Assignment 2:** Implemented training pipeline, evaluation results, and documented experiments.
- **Assignment 3:** Small demonstration application, final report, and presentation.

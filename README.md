# 🖼️ Image Classification Models Comparison

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![PyTorch/TensorFlow](https://img.shields.io/badge/Framework-PyTorch_or_TensorFlow-orange.svg) 

## 📌 Giới thiệu dự án (Project Overview)
Dự án này thực hiện phân loại hình ảnh (Image Classification) trên tập dữ liệu **[Garbage Classification]**. Mục tiêu chính là xây dựng, huấn luyện và so sánh hiệu năng của nhiều mô hình học sâu (Deep Learning) khác nhau để tìm ra phương pháp tối ưu nhất.

## 📊 Tập dữ liệu (Dataset)
*   **Nguồn:**[(https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification)]
*   **Các nhãn (Classes):**[Cáp tông (393), kính (491), Kim loại (400), Giấy(584), Nhựa (472) and Rác(127)]

## 🧠 Các mô hình đã triển khai (Models Implemented)
Dự án so sánh các mô hình sau:
1.  **Custom CNN**
2.  **ResNet50 (Transfer Learning)**
3.  **VGG16**

## 📈 Kết quả & Đánh giá (Results & Evaluation)
*(Phần này NHẤT ĐỊNH PHẢI CÓ để nhà tuyển dụng thấy bạn làm ra kết quả)*
| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Custom CNN | 75% | 0.74 | 0.75 | 0.74 |
| ResNet50 | **92%** | **0.91** | **0.92** | **0.91** |

> **Nhận xét:** Mô hình ResNet50 cho kết quả tốt nhất do tận dụng được Transfer Learning...

<img width="1455" height="473" alt="Screenshot_1" src="https://github.com/user-attachments/assets/372833d1-5508-4504-aed4-e54ae06057fa" />


## 🚀 Hướng dẫn cài đặt và sử dụng (Getting Started)
**1. Clone dự án:**
```bash
git clone https://github.com/Dzux1308/image-classification.git
cd image-classification

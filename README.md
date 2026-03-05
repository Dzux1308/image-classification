# 🖼️ Image Classification Models Comparison

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![PyTorch/TensorFlow](https://img.shields.io/badge/Framework-PyTorch_or_TensorFlow-orange.svg) 
*(Sửa lại logo framework bạn dùng)*

## 📌 Giới thiệu dự án (Project Overview)
Dự án này thực hiện phân loại hình ảnh (Image Classification) trên tập dữ liệu **[Tên Dataset của bạn, vd: CIFAR-10 / Cats vs Dogs]**. Mục tiêu chính là xây dựng, huấn luyện và so sánh hiệu năng của nhiều mô hình học sâu (Deep Learning) khác nhau để tìm ra phương pháp tối ưu nhất.

## 📊 Tập dữ liệu (Dataset)
*   **Nguồn:**[Link nguồn data nếu có, vd: Kaggle]
*   **Số lượng:**[vd: 10,000 ảnh training, 2,000 ảnh test]
*   **Các nhãn (Classes):**[Liệt kê các class, vd: Dog, Cat, Bird...]
*(Gợi ý: Hãy chèn 1 bức ảnh chụp màn hình hiển thị vài sample data vào đây)*

## 🧠 Các mô hình đã triển khai (Models Implemented)
Dự án so sánh các mô hình sau:
1.  **Custom CNN**: Mạng chập tự xây dựng cơ bản.
2.  **ResNet50 (Transfer Learning)**: [Ghi chú thêm nếu bạn dùng pre-trained]
3.  **VGG16**: ...
*(Liệt kê các model thực tế bạn đã code trong file ipynb)*

## 📈 Kết quả & Đánh giá (Results & Evaluation)
*(Phần này NHẤT ĐỊNH PHẢI CÓ để nhà tuyển dụng thấy bạn làm ra kết quả)*
| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Custom CNN | 75% | 0.74 | 0.75 | 0.74 |
| ResNet50 | **92%** | **0.91** | **0.92** | **0.91** |

> **Nhận xét:** Mô hình ResNet50 cho kết quả tốt nhất do tận dụng được Transfer Learning...

*(Hãy chèn biểu đồ Loss/Accuracy hoặc Confusion Matrix của bạn vào đây. Chụp màn hình từ Notebook và upload lên)*

## 🚀 Hướng dẫn cài đặt và sử dụng (Getting Started)
**1. Clone dự án:**
```bash
git clone https://github.com/Dzux1308/image-classification.git
cd image-classification

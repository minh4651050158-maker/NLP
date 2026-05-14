# # 📰 Phát Hiện Tin Giả (Fake News Detection) bằng NLP

Dự án này thực nghiệm các mô hình Học máy (Naive Bayes, SVM) và Học sâu (RNN, LSTM) kết hợp với các kỹ thuật trích xuất đặc trưng (Word2Vec, BERT) để phân loại tin thật và tin giả.

## 📊 Tập dữ liệu (Dataset)
Sử dụng bộ dữ liệu **ISOT Fake News Dataset** từ Kaggle. Code được thiết lập để tải dữ liệu tự động thông qua Kaggle API.

## ⚙️ Cài đặt và Chạy thử nghiệm nghiệm
Để chạy mã nguồn trên Google Colab hoặc máy cá nhân, vui lòng thực hiện các bước sau:

1. Clone repository này hoặc tải file `Notebook_Thuc_Nghiem.ipynb` về máy.
2. Đảm bảo bạn đã có file `kaggle.json` (API token từ tài khoản Kaggle của bạn).
3. Cài đặt các thư viện cần thiết:
   ```bash
   pip install -r requirements.txt

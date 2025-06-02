# Công Cụ Phân Tích Cảm Xúc Đa Khía Cạnh Nhà Hàng

Repo này chứa mã nguồn cho một ứng dụng web hỗ trợ phân tích cảm xúc đa khía cạnh (Aspect-Based Sentiment Analysis - ABSA) cho các đánh giá nhà hàng. Ứng dụng bao gồm các công cụ chính: Tiền xử lý dữ liệu, Gán nhãn dữ liệu, và Phân loại câu đơn.

## Yêu Cầu

*   Python 3.8+
*   Các thư viện được liệt kê trong `requirements.txt` (nếu có, hoặc bạn có thể liệt kê các thư viện chính như `streamlit`, `pandas`, `numpy`, `scikit-learn`, `joblib`, `emoji`, `flashtext`).

## Cài Đặt

1.  **Clone Repository:**
    ```bash
    git clone [URL_REPO_CUA_BAN]
    cd [TEN_THU_MUC_REPO]
    ```

2.  **Cài đặt thư viện:**
    (Nếu có `requirements.txt`)
    ```bash
    pip install -r requirements.txt
    ```
    (Nếu không, cài đặt thủ công các thư viện cần thiết)
    ```bash
    pip install streamlit pandas numpy scikit-learn joblib emoji flashtext
    ```

3.  **Mô Hình:**
    *   Đảm bảo bạn có tệp mô hình `pipe.joblib` đã được huấn luyện.
    *   Đặt tệp này vào thư mục `./model/` (tạo thư mục `model` nếu chưa có).

## Chạy Ứng Dụng

Sử dụng Streamlit để chạy ứng dụng:

```bash
streamlit run app.py

DỰ ĐOÁN SỰ RỜI ĐI CỦA KHÁCH HÀNG TRONG LĨNH VỰC ĐIỆN TỬ VIỄN THÔNG THÔNG QUA ÁP DỤNG MÔ HÌNH HỌC MÁY CÓ GIÁM SÁT
Bài báo cáo nhằm mục đích xây dựng mô hình dự đoán sự rời đi của khách hàng của công ty điện tử viễn thông Telco bằng việc áp dụng 3 mô hình học máy có giám sát gồm Decision Tree, K-Nearest Neighbors và Naive Bayes. Bên cạnh đó, bài nghiên cứu cũng xác định nhân tố chính dẫn đến quyết định rời đi của khách hàng bằng việc trực quan hóa dữ liệu.
Quy trình xây dựng mô hình dự đoán
1. Xác định mục tiêu nghiên cứu
2. Thu thập dữ liệu liên quan đến đề tài nghiên cứu từ Kaggle
3. Chuẩn bị dữ liệu như giải quyết các giá trị null, duplicate rows và convert đúng về dạng dữ liệu 
4. Khai phá dữ liệu và rút ra một số insight
5. Tiền xử lý dữ liệu bao gồm:
- Mã hóa dữ liệu phân loại bằng 2 phương pháp replace() và get_dummies.
- Lựa chọn đặc trưng quan trọng trước khi áp dụng mô hình bằng nhiều phương pháp khác nhau như trực quan hóa độ tương quan giữa các đặc trưng bằng biểu đồ Heatmap, các phương pháp lựa chọn đặc trưng quan trọng như dựa trên kiểm định Chi-square và ANOVA, Feature Importance dựa trên thuật toán Decision Tree và Random Forest và RFE.
- Scale data đối với các đặc trưng có phạm vi giá trị lớn.
6. Chia tập dữ liệu thành 2 tập train và test theo tỷ lệ 7:3. Ngoài ra nhóm cũng tiến hành xử lý dữ liệu mất cân đối bằng phương pháp SMOTE
7. Áp dụng mô hình Decision Tree (CART, C4.5), KNN và Naive Bayes.
8. So sánh các kết quả và đề xuất mô hình tối ưu nhất.
9. Đánh giá kết quả nghiên cứu, ưu nhược điểm và hướng phát triển.
Files nộp
Nhóm 10 nộp các file cho bài báo cáo cuối kỳ môn học Phân tích dữ liệu với R/Python. Các file bao gồm:
1. File Word bài báo cáo
2. File PDF bài báo cáo
3. File trình chiếu PPT
4. File Code thực hành .ipynb
5. File excel data
6. File Readme
7. File Word đánh giá thành viên nhóm 10
Yêu cầu môi trường, thư viện làm việc
- Google Colab/Jupyter Notebook
- Python 3.9.16
- Pandas, Numpy
- Matplotlib, Seaborn
- Sklearn
Thông tin tác giả
Danh sách các thành viên nhóm 10, bao gồm:
1. Lê Bùi Quỳnh Như (trưởng nhóm)
2. Nguyễn Minh Thái
3. Nguyễn Thị Cẩm Giang
4. Lê Thị Mỹ Duyên
5. Đinh Thị Kim Anh
6. Trịnh Hoài Hương



# NhomSo7
Deso2_Phathientingiabanghocmay_Nhom7
Giới thiệu
Phát hiện tin giả (Fake News Detection) là một lĩnh vực nghiên cứu quan trọng trong thời đại số, nơi mà thông tin sai lệch có thể lan truyền với tốc độ rất nhanh qua các phương tiện truyền thông xã hội và internet. Tin giả không chỉ gây nhầm lẫn cho công chúng mà còn có thể ảnh hưởng tiêu cực đến xã hội, chính trị và kinh tế. Việc phát triển các hệ thống tự động giúp phát hiện tin giả đang trở thành một nhu cầu cấp thiết, và học máy (Machine Learning) là một trong những công cụ mạnh mẽ để giải quyết vấn đề này.

Mục tiêu
Mục tiêu của đề tài là xây dựng một mô hình học máy có khả năng phân biệt giữa tin thật và tin giả bằng cách phân tích nội dung văn bản. Hệ thống sẽ tự động phát hiện các bài viết có khả năng là tin giả dựa trên các đặc điểm ngôn ngữ và cấu trúc của chúng.
Tiền xử lý dữ liệu:
Dữ liệu về tin tức được tải từ file CSV và được làm sạch: loại bỏ các dấu câu, chữ cái đặc biệt, và dừng từ (stopwords) để giúp mô hình tập trung vào nội dung quan trọng.
Trực quan hóa dữ liệu:
Chương trình tạo ra hình ảnh Word Cloud cho cả tin thật và tin giả để giúp dễ dàng nhận diện các từ phổ biến trong từng loại tin.
Tạo biểu đồ thể hiện các từ xuất hiện nhiều nhất trong tập dữ liệu.
Biến đổi văn bản thành vector:
Chuyển đổi văn bản thành dạng số liệu sử dụng TF-IDF (Term Frequency-Inverse Document Frequency), giúp mô hình hiểu được mức độ quan trọng của mỗi từ trong tập dữ liệu.
Huấn luyện mô hình:
Hai mô hình học máy được sử dụng: Logistic Regression và Decision Tree.
Chương trình chia tập dữ liệu thành tập train (75%) và test (25%) để đánh giá hiệu quả của mô hình trên cả dữ liệu chưa từng thấy.
Đánh giá mô hình:
Độ chính xác của cả hai mô hình được tính toán dựa trên dữ liệu train và test. Chương trình cũng vẽ ma trận nhầm lẫn để đánh giá hiệu suất của mô hình.
Dự đoán tin tức mới:
Sau khi huấn luyện, mô hình có thể dự đoán xem một tin tức bất kỳ do người dùng nhập vào là tin thật hay tin giả.

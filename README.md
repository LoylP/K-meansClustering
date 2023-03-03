# K-meansClustering
Đầu vào: Dữ liệu X và số lượng cluster cần tìm K
Đầu ra: Các center M và label vector cho từng điểm dữ liệu Y
Chọn K điểm bất kỳ làm các center ban đầu.
Phân mỗi điểm dữ liệu vào cluster có center gần nó nhất.
Nếu việc gán dữ liệu vào từng cluster ở bước 2 không thay đổi so với vòng lặp trước nó thì ta dừng thuật toán.
Cập nhật center cho từng cluster bằng cách lấy trung bình cộng của tất các các điểm dữ liệu đã được gán vào cluster đó sau bước 2.
Quay lại bước 2.

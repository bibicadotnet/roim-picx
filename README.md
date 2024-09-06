roim-picx

Một ứng dụng lưu trữ hình ảnh dựa trên Cloudflare Workers, R2 và Pages với các đặc điểm sau:

10GB dung lượng lưu trữ miễn phí
3 triệu lượt truy cập hình ảnh hàng tháng không giới hạn băng thông, giới hạn 100.000 lượt mỗi ngày
1 triệu lượt tải lên hình ảnh mỗi tháng
Không cần tự mua máy chủ, chỉ cần sao chép mã và triển khai trên Cloudflare để sử dụng
Triển khai độc lập, không lo bị bên thứ ba xóa dữ liệu
Các tính năng đã hoàn thành:

Tải lên hình ảnh hàng loạt
Xem danh sách hình ảnh
Xóa hình ảnh
Tạo thư mục
Tìm kiếm theo thư mục
Nhấp vào liên kết để sao chép địa chỉ
Tính năng xác thực đơn giản, cần được ủy quyền để vào trang quản lý
Hướng dẫn sử dụng:

Fork dự án vào GitHub của bạn
Tạo dự án Page
Nhập thông số biên dịch:
Framework preset: Không
Lệnh xây dựng: npm run build
Thư mục đầu ra: dist
Hoàn thành việc tạo dự án
Thiết lập biến môi trường:
AUTH_TOKEN: Mã ủy quyền
COPY_URL: Đường dẫn sao chép, nếu không có, nhập domain của trang theo định dạng /rest
Liên kết R2:
Tên biến: R2
Triển khai lại

## 1. Source code Python:
```python
import sys
import platform

def kiem_tra_he_thong():
    phien_ban_python = sys.version
    ten_he_dieu_hanh = platform.system()
    
    print(f"He dieu hanh dang dung: {ten_he_dieu_hanh}")
    print(f"Phien ban Python hien tai: {phien_ban_python}")

if __name__ == "__main__":
    kiem_tra_he_thong()
```
## 2. Bảng So Sánh Công Cụ Soạn Thảo
|**Tiêu chí so sánh**|**Trình biên soạn StackEdit**|**Phần mềm VS Code**|
|:---:|:---:|:---:|
|**Môi trường hoạt động**|Chạy trực tiếp trên trình duyệt Web|Cài đặt cục bộ trên máy tính (Desktop App)
|**Mục đích chính**|Soạn thảo, xem trước và lưu trữ Markdown|Môi trường phát triển tích hợp (IDE) đa ngôn ngữ
**Khả năng cài Extension**|Không hỗ trợ tiện ích mở rộng bên ngoài|Kho tiện ích mở rộng phong phú hàng đầu
**Tính tiện lợi**|Dùng ngay không cần cài đặt, siêu nhẹ|Cần thời gian cài đặt và cấu hình môi trường ban đầu
## 3. Danh Sách Kiểm Tra Tiến Độ Cài Đặt (Task List)
-   [x] Tải tệp cài đặt VS Code từ trang chủ chính thức
-   [x] Kích hoạt tùy chọn Add to PATH trong quá trình cài đặt
-   [x] Cài đặt Extension Python và Pylance trong kho tiện ích
-   [ ] Cài đặt Extension Markdown Preview Enhanced để xem trước tài liệu
-   [ ] Chạy thử thành công tệp kiểm tra môi trường đầu tiên
> # Note: 3 phần trên có tham khảo từ AI. #
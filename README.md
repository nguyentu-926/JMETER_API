# JMETER_API

## 1. Giới thiệu.

- Tên dự án: Kiểm thử API bằng JMETER
- Ngày thực hiện: 20/06/2025
- Người thực hiện: Nguyễn Thị Cẩm Tú
- MSV: 22010230
- Môi trường  kiểm thử: JMETER
- Phương pháp kiểm thử: Kiểm thử thử công, kiểm thử tự động.

Mục tiêu:
- Gửi JMETER đến API
- Viết script kiểm thử
- Tự động hóa kiểm thử bằng dòng lệnh
- Tạo báo cáo minh họa kết quả

## 2. Công cụ sử dụng

| Công cụ | Mục đích |
|--------|----------|
| Apache JMeter | Thiết kế và chạy kịch bản kiểm thử |
| Java | Hỗ trợ chạy JMeter |
| HTML Reports | Tùy chọn xuất báo cáo đẹp |

---

## 3. Kiểm Thử bằng API

| Method | Endpoint                      | Mô tả                        |
|--------|-------------------------------|------------------------------|
| GET    | /api/users?page=2            | Lấy danh sách người dùng     |

---

## 4. Cấu hình kiểm thử

- **Thread Group**: 1 người dùng, 1 lần lặp
- **Sampler**: HTTP GET
- **URL**: `https://reqres.in/api/users?page=2`
- **Listeners**:
  - View Results Tree
  - Summary Report

---

## 5. Kết quả kiểm thử

## 6. Kết luận

JMeter đã thực hiện thành công kiểm thử API, đảm bảo rằng API phản hồi mã trạng thái `200` và dữ liệu có trả về đúng format. Đây là một bước đầu hiệu quả cho kiểm thử hiệu năng và chức năng của API.

---




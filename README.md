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

![Screenshot (1368)](https://github.com/user-attachments/assets/f6b2f876-4731-4a99-ae57-2b93e35faf47)

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

![Screenshot (1369)](https://github.com/user-attachments/assets/2a59ce8b-bb90-4d3c-bc56-34d1353fcaa1)

![Screenshot (1371)](https://github.com/user-attachments/assets/2db4b8be-bcd7-4e59-9205-b2fb652ca26b)

![Screenshot (1373)](https://github.com/user-attachments/assets/7ef52ff4-abca-4ce7-814b-efce00c7a637)


---

## 5. Kết quả kiểm thử

![Screenshot (1376)](https://github.com/user-attachments/assets/8b078f56-a18a-4ddc-b20d-048ff956ff5b)

![Screenshot (1377)](https://github.com/user-attachments/assets/649699c3-373e-4a77-a973-40c2c359685f)


## 6. Kết luận

JMeter đã thực hiện thành công kiểm thử API, đảm bảo rằng API phản hồi mã trạng thái `200` và dữ liệu có trả về đúng format. Đây là một bước đầu hiệu quả cho kiểm thử hiệu năng và chức năng của API.

---




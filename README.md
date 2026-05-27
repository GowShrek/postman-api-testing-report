# Báo cáo Kiểm thử API với Postman

## 1. Giới thiệu
- **Công cụ sử dụng:** Postman
- **API kiểm thử:** JSONPlaceholder (https://jsonplaceholder.typicode.com)
- **Mục tiêu:** Thực hành gửi và kiểm tra các HTTP request

## 2. Các Request đã thực hiện

### 2.1 GET – Lấy danh sách bài viết
- **URL:** `GET https://jsonplaceholder.typicode.com/posts`
- **Status Code:** 200 OK
- **Mô tả:** Trả về danh sách 100 bài viết

<img width="2880" height="1716" alt="image" src="https://github.com/user-attachments/assets/52461abf-0683-4cb5-a21a-33d49a79941a" />


---

### 2.2 GET – Lấy 1 bài viết theo ID
- **URL:** `GET https://jsonplaceholder.typicode.com/posts/1`
- **Status Code:** 200 OK

<img width="2880" height="1716" alt="image" src="https://github.com/user-attachments/assets/738ae16e-3ce1-440b-aead-c4a4a6326618" />

---

### 2.3 POST – Tạo bài viết mới
- **URL:** `POST https://jsonplaceholder.typicode.com/posts`
- **Body (JSON):**
```json
{
  "title": "Bài viết mới",
  "body": "Nội dung bài viết",
  "userId": 1
}
```
- **Status Code:** 201 Created

<img width="2880" height="1716" alt="image" src="https://github.com/user-attachments/assets/208c0fc4-0bf7-4429-bf07-667fac87809a" />


---

### 2.4 PUT – Cập nhật bài viết
- **URL:** `PUT https://jsonplaceholder.typicode.com/posts/1`
- **Status Code:** 200 OK

<img width="2880" height="1716" alt="image" src="https://github.com/user-attachments/assets/edaf732f-4f5e-4153-88f5-b670381d4552" />


---

### 2.5 DELETE – Xoá bài viết
- **URL:** `DELETE https://jsonplaceholder.typicode.com/posts/1`
- **Status Code:** 200 OK

<img width="2880" height="1716" alt="image" src="https://github.com/user-attachments/assets/ffc4bf6b-1f5e-40ab-ab6c-eeddb926f862" />


## 3. Kết luận
- Đã thực hành thành công các thao tác CRUD qua Postman
- Hiểu cách đọc Status Code và Response Body
- Nắm được cách tổ chức Collection trong Postman

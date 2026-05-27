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

![GET Request](images/get-posts.png)

---

### 2.2 GET – Lấy 1 bài viết theo ID
- **URL:** `GET https://jsonplaceholder.typicode.com/posts/1`
- **Status Code:** 200 OK

![GET by ID](images/get-post-id.png)

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

![POST Request](images/post-create.png)

---

### 2.4 PUT – Cập nhật bài viết
- **URL:** `PUT https://jsonplaceholder.typicode.com/posts/1`
- **Status Code:** 200 OK

![PUT Request](images/put-update.png)

---

### 2.5 DELETE – Xoá bài viết
- **URL:** `DELETE https://jsonplaceholder.typicode.com/posts/1`
- **Status Code:** 200 OK

![DELETE Request](images/delete-post.png)

## 3. Kết luận
- Đã thực hành thành công các thao tác CRUD qua Postman
- Hiểu cách đọc Status Code và Response Body
- Nắm được cách tổ chức Collection trong Postman

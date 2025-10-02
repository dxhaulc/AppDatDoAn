## 1.🚀 Tổng quan

### 🛍️ Tính năng chính (Dành cho người dùng)
- Đăng nhập, đăng ký
- Xem danh sách đồ ăn theo danh mục
- Tìm kiếm đồ ăn
- Thêm vào giỏ hàng, đặt hàng
- Theo dõi đơn mua: đang giao, đã giao
- Cập nhật thông tin tài khoản

## 🧑‍💻 Công nghệ sử dụng

| Layer         | Công nghệ                                  |
|---------------|--------------------------------------------|
| Frontend      | React Native (Expo), React Navigation      |
| Backend       | Node.js, Express.js                        |
| Cơ sở dữ liệu | SQL Server                                 |
| Authentication| JWT (JSON Web Token)                       |
| Dev Tool      | VS Code                                    |

## 2.⚙️ Chạy ứng dụng
### B1: Chạy cơ sở dữ liệu (SQL Server)
Vào file AppDatDoAn.sql chạy để khởi tạo cơ sở dữ liệu.

### B2: Kết nối với cơ sở dữ liệu 
Vào thư mục backend --> .env để chỉnh cấu hình kết nối với database
Sau đó ở thư mục backend "node server" để kết nối với server

<img width="397" alt="29-5 env" src="https://github.com/user-attachments/assets/bf85fbbf-193a-4f40-adfc-a3f61ec0d619" />

### B3: Kết nối frontend và backend
Vào thư mục api --> apiConfig.js chỉnh sửa URLServer thành "http://{địa chỉ IPv4 Address của máy mình}:5000"

<img width="470" alt="29-5 apiconfig" src="https://github.com/user-attachments/assets/b22539ef-f172-4f79-823f-7e8f79f458e0" />

Chạy "npx expo start" sử dụng ứng dụng expo go trên điện thoại kết nối (sử dụng chung mạng với máy tính).

## 3.🖼️ Một số hình ảnh của app
<img width="200" alt="login" src="https://github.com/user-attachments/assets/7e4b1102-36c1-4145-8830-264d9f2f2ae1" /> <img width="200" alt="register" src="https://github.com/user-attachments/assets/abc9e437-ebb1-472c-8fa1-87fae564d939" />
<img width="200" alt="home" src="https://github.com/user-attachments/assets/bd135c17-31a5-4949-b08b-727000498b0b" /> <img width="200" alt="detailproduct" src="https://github.com/user-attachments/assets/255df8ef-d409-4ef2-ac16-5ebd1785603f" />
<img width="200" alt="profile" src="https://github.com/user-attachments/assets/414a3ec5-6f1f-494d-a4e4-3b7b79a7fbab" /> <img width="200" alt="cart" src="https://github.com/user-attachments/assets/d461d60f-b87e-4593-8e76-16a8d82817ca" />
<img width="200" alt="ordershistory" src="https://github.com/user-attachments/assets/4883763f-26f0-4752-8a57-8f6ffe7765ed" /> <img width="200" alt="orderdetail" src="https://github.com/user-attachments/assets/1838809d-d127-493f-9f94-81f988c1c542" />






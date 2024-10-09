# Phần bổ công việc phát triển dự án

Dưới đây là kế hoạch phát triển website quản trị và ứng dụng di động với người dùng sử dụng, trong đó phân tách rõ ràng nhiệm vụ của đội ngũ quản trị và đội ngũ phát triển ứng dụng di động:

---

# **Kế hoạch phát triển Website và Ứng dụng di động**

## **I. Mục tiêu**

1. **Website quản trị (Admin Dashboard):**  
   - Quản lý người dùng (cá nhân, doanh nghiệp, tổ chức phi lợi nhuận, chính phủ).
   - Quản lý sự kiện bảo vệ môi trường, thử thách, hệ thống tích điểm.
   - Quản lý dữ liệu rác thải và kết nối với các trung tâm tái chế.
   - Tích hợp công cụ phân tích dữ liệu người dùng và kết quả các hoạt động bảo vệ môi trường.

2. **Ứng dụng di động (Mobile App):**  
   - Người dùng có thể đăng ký và theo dõi các hoạt động sống xanh.
   - Chức năng báo cáo sự kiện môi trường và phân loại rác bằng công nghệ nhận diện hình ảnh.
   - Tham gia thử thách, tích điểm và đổi thưởng với các sản phẩm thân thiện môi trường.
   - Kết nối với cộng đồng, chia sẻ tiến trình bảo vệ môi trường và theo dõi sự phát triển của cây trồng.

---

## **II. Kế hoạch phát triển**

### **1. Giai đoạn 1: Nghiên cứu và phân tích**

**Thời gian:** 2 tuần  
**Mục tiêu:** Thu thập thông tin từ người dùng tiềm năng và phân tích yêu cầu công nghệ.  

**Công việc cụ thể:**
   - Khảo sát nhu cầu người dùng về tính năng chính (quản lý sự kiện, thử thách, tích điểm).
   - Xác định công nghệ phát triển backend và frontend phù hợp (PHP/Laravel cho website quản trị, Flutter cho ứng dụng di động).
   - Xây dựng yêu cầu hệ thống (System Requirements Specification - SRS) dựa trên thông tin thu thập.

**Đầu ra:**
   - Yêu cầu hệ thống đầy đủ.
   - Phân tích các bên liên quan và vai trò của họ.

### **2. Giai đoạn 2: Thiết kế hệ thống**

**Thời gian:** 3 tuần  
**Mục tiêu:** Thiết kế giao diện người dùng và kiến trúc hệ thống.

**Công việc cụ thể:**
   - **Thiết kế giao diện người dùng (UI/UX):**  
     + Website quản trị: Dashboard quản lý, chức năng xem báo cáo, quản lý người dùng.  
     + Ứng dụng di động: Đăng ký, đăng nhập, báo cáo sự kiện, theo dõi hoạt động cây trồng.
   - **Thiết kế kiến trúc hệ thống:**  
     + Xác định cơ sở dữ liệu: MongoDB cho backend, Firebase cho mobile.
     + Tích hợp API để đồng bộ dữ liệu giữa web và app (RESTful API, GraphQL).
     + Chức năng bảo mật, phân quyền cho quản trị và người dùng.

**Đầu ra:**
   - Bản vẽ giao diện người dùng cho website và ứng dụng.
   - Tài liệu kiến trúc hệ thống (System Architecture Design - SAD).

### **3. Giai đoạn 3: Phát triển website quản trị (Admin Dashboard)**

**Thời gian:** 5 tuần  
**Mục tiêu:** Hoàn thiện hệ thống quản trị để theo dõi và quản lý dữ liệu người dùng và hoạt động môi trường.

**Công việc cụ thể:**
   - **Backend:**  
     + Xây dựng API quản lý người dùng (đăng ký, chỉnh sửa thông tin, theo dõi hoạt động).  
     + Tích hợp chức năng quản lý thử thách, sự kiện và điểm thưởng.
   - **Frontend:**  
     + Phát triển giao diện quản trị người dùng (tạo, chỉnh sửa, xóa tài khoản).  
     + Hiển thị bảng điều khiển (dashboard) với thống kê các hoạt động bảo vệ môi trường, thử thách và báo cáo.
   - **Bảo mật và quyền truy cập:**  
     + Phân quyền quản trị (super admin, admin thường).  
     + Xác thực và phân quyền truy cập cho từng vai trò người dùng.

**Đầu ra:**
   - Website quản trị hoạt động đầy đủ các tính năng quản lý người dùng và dữ liệu.

### **4. Giai đoạn 4: Phát triển ứng dụng di động**

**Thời gian:** 6 tuần  
**Mục tiêu:** Xây dựng ứng dụng di động giúp người dùng dễ dàng tương tác và tham gia các hoạt động bảo vệ môi trường.

**Công việc cụ thể:**
   - **Backend (API & cơ sở dữ liệu):**  
     + Tích hợp API từ website quản trị để đồng bộ dữ liệu người dùng.  
     + Cập nhật dữ liệu liên tục từ các hoạt động của người dùng (báo cáo sự kiện, tích điểm).
   - **Frontend (Flutter):**  
     + Phát triển giao diện đăng ký, đăng nhập và trang chính của ứng dụng.
     + Tích hợp tính năng báo cáo sự kiện môi trường, chụp ảnh rác và nhận diện loại rác.
     + Tính năng tham gia thử thách, tích điểm và theo dõi sự phát triển của cây trồng.
   - **Chức năng phụ trợ:**  
     + Tích hợp bản đồ điểm thu gom rác, trung tâm tái chế.
     + Thông báo đẩy (push notifications) cho các thử thách và sự kiện mới.

**Đầu ra:**
   - Ứng dụng di động với đầy đủ tính năng cho người dùng.

### **5. Giai đoạn 5: Kiểm thử và triển khai**

**Thời gian:** 4 tuần  
**Mục tiêu:** Đảm bảo hệ thống hoạt động ổn định và triển khai sản phẩm.

**Công việc cụ thể:**
   - **Kiểm thử (Testing):**  
     + Kiểm thử chức năng (Function Testing) cho từng module của website và ứng dụng.  
     + Kiểm thử tích hợp (Integration Testing) để đảm bảo sự đồng bộ dữ liệu giữa website và app.
   - **Đánh giá hiệu suất (Performance Testing):**  
     + Đánh giá tốc độ tải trang và ứng dụng.
     + Đảm bảo ứng dụng hoạt động mượt mà trên nhiều thiết bị di động.
   - **Sửa lỗi:**  
     + Sửa các lỗi phát hiện trong quá trình kiểm thử.
     + Tối ưu hóa hiệu suất và bảo mật.
   - **Triển khai:**  
     + Đưa website quản trị lên môi trường sản xuất (production).
     + Đưa ứng dụng di động lên các cửa hàng ứng dụng (App Store, Google Play).

**Đầu ra:**
   - Website và ứng dụng di động hoàn thiện và sẵn sàng cho người dùng.

---

## **III. Phân chia vai trò và nguồn lực**

### **1. Đội ngũ phát triển**

- **Quản lý dự án:** Theo dõi tiến độ, phân chia nhiệm vụ và đảm bảo sự liên lạc giữa các nhóm.
- **Frontend Developer (2 người):**  
   + 1 người phụ trách giao diện website quản trị.  
   + 1 người phụ trách phát triển giao diện ứng dụng di động.
- **Backend Developer (2 người):** Phát triển API và cơ sở dữ liệu cho website và ứng dụng di động.
- **Tester (2 người):** Kiểm thử toàn bộ hệ thống và đảm bảo tính ổn định trước khi triển khai.

### **2. Công nghệ sử dụng**

- **Website quản trị:**  
   + Backend: Laravel (PHP)  
   + Frontend: HTML5, CSS3, JavaScript (React)  
   + Database: MongoDB
- **Ứng dụng di động:**  
   + Flutter (Dart)  
   + Firebase (cơ sở dữ liệu thời gian thực và xác thực người dùng)  

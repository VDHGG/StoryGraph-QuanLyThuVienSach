# StoryGraph-QuanLyThuVienSach

## 💡 Giới thiệu  
StoryGraph-QuanLyThuVienSach là một ứng dụng quản lý thư viện sách, được phát triển bằng Java và Maven.  
Dự án giúp quản lý sách, độc giả và các nghiệp vụ mượn/trả sách một cách đơn giản.  
Phù hợp với học tập, demo, thực hành quản lý dữ liệu và xây dựng phần mềm.

---

## 📂 Cấu trúc dự án  
- `.mvn/`, `mvnw`, `mvnw.cmd`, `pom.xml` — cấu hình Maven.  
- `src/main/java` — chứa mã nguồn chính của ứng dụng.  
- `src/main/resources` — chứa file cấu hình   
- `README.md` — tài liệu mô tả dự án.  

---

## ✨ Tính năng chính  
- 📚 **Quản lý sách**: Thêm, sửa, xóa, xem danh sách, tìm kiếm.  
- 🧑‍🤝‍🧑 **Quản lý độc giả**: Tạo mới, cập nhật thông tin, xóa, xem danh sách.  
- 🔄 **Mượn – Trả sách**: Ghi nhận mượn, trả, và kiểm tra trạng thái sách.  
- 📅 **Quản lý lịch sử**  
- 📊 **Thống kê cơ bản**  

---

## 🛠️ Yêu cầu hệ thống  
- **Java 8+**  
- **Maven 3.6+**  
- **IDE đề xuất**: IntelliJ IDEA, VS Code hoặc Eclipse  
- **Cơ sở dữ liệu**: MySQL / PostgreSQL 

---

## 🚀 Cài đặt & Chạy dự án

### Bước 1 — Clone source
git clone https://github.com/VDHGG/StoryGraph-QuanLyThuVienSach.git
cd StoryGraph-QuanLyThuVienSach

### Bước 2 — Build bằng Maven
./mvnw clean install       # Linux/Mac
mvn clean install          # Windows hoặc khi đã cài Maven

### Bước 3 - Thao tác database
- Mở MySQL rồi chạy file .sql trong dự án
- Kiểm tra kết nối giữa dự án và database

### Bước 4 — Chạy ứng dụng
Chạy trực tiếp trong IDE bằng cách chạy file Main.java.

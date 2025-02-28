# Hướng Dẫn Cài Đặt Docker

Docker là một nền tảng giúp bạn dễ dàng tạo, triển khai và chạy ứng dụng trong các container. Bài viết này sẽ hướng dẫn bạn cách cài đặt Docker trên các hệ điều hành phổ biến.

## 1. Cài Đặt Docker Trên Windows
### Yêu Cầu Hệ Thống:
- Windows 10 64-bit: Home, Pro, Education, hoặc Enterprise (phiên bản 1903 trở lên)
- Bật ảo hóa (Virtualization) trong BIOS

### Bước Cài Đặt:
1. **Tải Docker Desktop**
   - Truy cập: [https://www.docker.com/products/docker-desktop](https://www.docker.com/products/docker-desktop)
   - Tải bản cài đặt phù hợp với hệ điều hành của bạn.

2. **Cài Đặt Docker**
   - Chạy file cài đặt `.exe` vừa tải.
   - Chọn "Enable WSL 2 Features" nếu bạn dùng WSL 2.
   - Hoàn tất quá trình cài đặt và khởi động lại máy tính nếu cần.

3. **Kiểm Tra Cài Đặt**
   - Mở Terminal hoặc Command Prompt, chạy lệnh:
     ```sh
     docker --version
     ```
   - Nếu hiển thị phiên bản Docker, quá trình cài đặt thành công


## 4. Kiểm Tra Docker Hoạt Động
Sau khi cài đặt Docker, bạn có thể chạy thử container mẫu:
```sh
docker run hello-world
```
Nếu thấy thông báo "Hello from Docker!", Docker đã được cài đặt thành công.

---


# Hướng Dẫn Cài Đặt Grafana

Grafana là một công cụ mã nguồn mở mạnh mẽ để giám sát và trực quan hóa dữ liệu. 
Hướng dẫn này giúp bạn cài đặt Grafana trên Windows bằng Docker.

### Yêu Cầu Hệ Thống:
- Docker đã được cài đặt trên hệ thống
- Kết nối internet để tải Docker image

### Bước Cài Đặt:
1. **Clone repository Grafana**
   - Truy cập: [https://github.com/grafana/grafana]
   - Tải bản cài đặt phù hợp với hệ điều hành của bạn.
   - git clone https://github.com/grafana/grafana.git
   ```bash
      # Đây là một đoạn mã Bash mẫu
      echo "Hello, World!"
      ls -l
      cd grafana
2. **Build Docker image từ mã nguồn**
    Grafana đã có sẵn Dockerfile trong repository, bạn có thể sử dụng nó để build Docker image:
   - docker build -t my-grafana .
   - Chọn "Enable WSL 2 Features" nếu bạn dùng WSL 2.
   - Hoàn tất quá trình cài đặt và khởi động lại máy tính nếu cần.

3. **Kiểm Tra Cài Đặt**
   - Mở Terminal hoặc Command Prompt, chạy lệnh:
     ```sh
     docker --version
     ```
   - Nếu hiển thị phiên bản Docker, quá trình cài đặt thành công


## 4. Kiểm Tra Docker Hoạt Động
Sau khi cài đặt Docker, bạn có thể chạy thử container mẫu:
```sh
docker run hello-world
```
Nếu thấy thông báo "Hello from Docker!", Docker đã được cài đặt thành công.

---

Chúc bạn cài đặt Docker thành công! 🚀

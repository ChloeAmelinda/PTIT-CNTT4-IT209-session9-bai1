\# Bài 1: Kiểm tra Docker Engine và chạy Hello-World



\## 1. Mục tiêu

\- Kiểm tra Docker CLI và Docker Engine.

\- Xác nhận kết nối đến Docker Daemon.

\- Khởi chạy thành công container Hello-World.



\## 2. Các bước thực hiện



\### Bước 1: Kiểm tra phiên bản Docker



Lệnh:

```bash

docker version

```



Kết quả: Docker hiển thị phiên bản Client và Server.



\### Bước 2: Kiểm tra Docker Engine



Lệnh:

```bash

docker info

```



Kết quả: Docker trả về thông tin hệ thống, container, image và Docker Engine.



\### Bước 3: Chạy Hello-World



Lệnh:

```bash

docker run hello-world

```



Kết quả:

```text

Hello from Docker!

This message shows that your installation appears

to be working correctly.

```



\### Bước 4: Kiểm tra container



Lệnh:

```bash

docker ps -a

```



Kết quả: Container `hello-world` có trạng thái `Exited (0)`.



\## 3. Kết quả đầu ra Terminal



Dán kết quả thực tế của các lệnh vào các khối bên dưới.



\*\*docker version\*\*

```text

\[Dán kết quả docker version]

```



\*\*docker info\*\*

```text

\[Dán kết quả docker info]

```



\*\*docker run hello-world\*\*

```text

\[Dán toàn bộ kết quả docker run hello-world]

```



\## 4. Kết luận



Docker CLI kết nối thành công tới Docker Engine. Container Hello-World được khởi chạy và trả về thông báo xác nhận cài đặt Docker hoạt động bình thường.


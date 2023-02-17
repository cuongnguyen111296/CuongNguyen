# **I. Kiến trúc tổng quan hệ thống Linux**
  Kiến trúc HDH Linux chia là 3 thành phần: Kernel, Shell và Applications
![a]<img src="[https://imgur.com/l2sK4Os](https://imgur.com/l2sK4Os)">
## **1) Kernel (Nhân)**: 
Đây là phần quan trong và được ví như trái tim của HDH, phần Kernel `chứa các module, thư viện` để `quản lý và giao tiếp` giữa `phần cứng` và `các ứng dụng`. Kernel trên Centos 7 có version 3.10.0.
## **2) Shell**: 
- Shell là 1 chương trình. Có chức năng thực thi các lệnh (command) từ người dùng hoặc từ các ứng dụng - tiện ích yêu cầu chuyển đến cho Kernel xử lý. Bên cạnh đó, shell còn có khả năng bảo vệ từ các yêu cầu không hợp lệ.
Các loại shell:
- sh (the **Bourne Shell**): đây là chương trình nguyên thủy của `UNIX` được viết bởi `Stephen Bourne` vào năm `1974`. Đến nay, shell sh vẫn được sử dụng rộng rãi.
- Bash (**bourne-again Shell**): đây là shell mặc định trên `linux`
- csh (the **C Shell**): Shell được viết bằng ngôn ngữ lập trình C, được viết bởi `Bill Joy` vào năm `1978`
- Ngoài ra còn có các loại shell khác như: ash, tsh, zsh
Dấu nhắn Shell sẽ được thể hiện dưới 2 dạng sau:
- Dạng 1: [root@localhost root]# với dấu # thể hiện tài khoản đang sử dụng là tài khoản **root**
- Dạng 2: [linux@localhost linux]$ với dấu $ thể hiện tài khoản đang sử dụng là user thông thường
## **3): Application**: 
- là các ứng dụng và tiện ích mà người dùng sử dụng cài đặt trên server. ví dụ như: ftp, samba, Proxy, ...
# **II. Cấu trúc hệ thống file:**

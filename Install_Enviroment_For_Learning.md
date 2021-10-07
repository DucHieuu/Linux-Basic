# Cài đặt máy ảo Linux (SKIP)
## PUTTY
- Khi được giao 1 công việc quản trị một server chạy hệ điều hành Linux thì rất ít có khả năng được sử dụng console để kết nối giao diện và sử dụng chuột và bản phím điều khiển
- Thông thường, ta sẽ chỉ được cấp địa chỉ IP, port, Username và Password. Để kết nối được đến máy chủ thì cần một công cụ SSH => `PUTTY`
### Cài đặt PUTTY
- Cài đặt card mạng của máy ảo sang Bridged Adapter để coi máy ảo là một máy thật trong cùng mạng LAN, đặt IP tĩnh
> kiểm tra xem máy ảo có cùng dải với máy thật không? Ping thông không?
- Tải PUTTY [tại đây](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html) (64-bit x86)
- Điền Hostname (IP), port mặc định 22 
và `OK` done

![image](https://user-images.githubusercontent.com/71936544/136417442-b50b6b8f-d58c-4886-b1b9-fded6a5e57b8.png)
> PUTTY nhẹ, dễ dàng cài đặt tuy nhiên rất ít tính năng. Trong thực tế, ta cần sử dụng nhiều hơn thế do đó cần sử dụng công cụ hỗ trợ chuyên sâu hơn
## MobaXterm
> Khắc phục được cái hạn chế về mặt thân thiện so với PUTTY
- Tải MobaXterm [tại đây](https://mobaxterm.mobatek.net/download.html)

User sessions > New session 

![image](https://user-images.githubusercontent.com/71936544/136419024-3e0d7229-ed4e-44bf-8957-dccc490f8b02.png)

SSH > Điền Remote host, Username > OK

![image](https://user-images.githubusercontent.com/71936544/136419188-17687e7c-8834-4ed7-bd71-a83b5cedad45.png)

Phần thư mục phía bên trái là các thư mục có trong server, có thể dễ dàng copy thư mục từ máy thật vào server thông qua việc kéo thả
![image](https://user-images.githubusercontent.com/71936544/136419570-a71d4905-548c-4c63-8b31-972a8651c424.png)

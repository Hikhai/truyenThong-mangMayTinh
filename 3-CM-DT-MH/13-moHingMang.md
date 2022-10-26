# Một số mô hình mạng thực tế

## Lý thuyết
Tùy theo mục đích sử dụng, bạn sẽ chọn mô hình kết nối mạng tối ưu cho mình.
### ví dụ về mô hình kết nối mạng tiêu chuẩn từ nhà cung cấp đến người dùng.

- Modem của người dùng sẽ kết nối qua cap quang đến điểm tập hợp (nơi tập trung người dùng của nhà cung cấp)
- Điểm tập hợp của nhà cung cấp kết nối với switch lơp 2 của nhà cung cấp (nơi switch lớp 2 thu thập data của các tập hợp điểm).
- switch lớp 2 của nhà cung cấp kết nối với swich lớp 3 của nhà cung cấp (trong đó switch lớp 3 là hợp data của của switch lớp 2).   
Công tắc lớp 3 của nhà cung cấp kết nối với tường lửa của nhà cung cấp để thực thi các quy tắc và kiểm soát lưu lượng
- Firewall của nhà cung cấp kết nối với router biên của nhà cung cấp để chuyển tiếp data truy cập của khách hàng
- Router biên của nhà cung cấp kết nối với mạng lõi của router chà nhà cung cấp khác nếu lưu lượng truy cập đến các máy chủ gửi lên đến hoặc tới bộ định tuyến của nhà cung cấp đối tác.
- Router biên nhà cung cấp kết nối với router của nhà cung cấp nước ngoài đến lưu lượng máy chủ ở nước ngoài.
  
![](https://codelearn.io/Media/Default/BasicNetworking/2.17.jpg)
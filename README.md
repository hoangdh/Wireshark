# Wireshark

### 1. Wireshark là gì?

`Wireshark` là một công cụ phân tích, theo dõi và kiểm tra mạng.

### 2. Sử dụng

#### Tải Wireshark tại: https://www.wireshark.org/

#### Giới thiệu và hướng dẫn cơ bản

<img src="http://i1363.photobucket.com/albums/r714/HoangLove9z/ws_zpsvefcqvlw.png" height=75% width=75%/>

- `1`: Thanh điều khiển: Bắt, ngừng, Làm lại việc bắt gói tin hoặc chọn Interface khác.
- `2`: Các gói tin đã bắt được
- `3`: Chi tiết từng gói tin
- `4`: Chi tiết từng gói tin được viết theo Hex
- `Fitter`: dùng để lọc các gói tin theo Giao thức, kích cỡ, Địa chỉ, ...

#### *Chi tiết*

##### Các bắt các gói tin

Chọn Interface muốn bắt gói tin

<img src="http://i.imgur.com/MJbzBHQ.png" />

Sau khi chọn Interface, bấm Start để bắt các gói tin

<img src="http://i.imgur.com/lmsFPQw.png" />

- `1`: Dừng công việc
- `2`: Thực hiện lại công việc
- `3`: Tô màu từng loại gói tin
- `4`: Tự động cuộn khi có gói tin mới
- `5`: Các gói tin đã được bắt

Kích đúp vào gói tin cần xem

<img src="http://i.imgur.com/fQNhw9S.png" />

- `1`: Các thông số đã được Wireshare biên dịch sang dạng cleartext
- `2`: Thông số HEX mà Wireshare bắt được

#### Lọc các gói tin

Lọc theo giao thức "TCP"

<img src="http://i.imgur.com/6TW4lIv.png" />

Chúng ta cũng có thể lọc với nhiều điều kiện bằng cách chuột phải vào *giá trị* của gói tin và chọn:

Ví dụ, chúng ta lọc gói tin với giao thức TCP với Destination như hình và chuột phải:

<img src="http://i.imgur.com/pfG52IJ.png" />

Cụ thể, ta tìm các gói có DES là 239.255.255.250 và theo giao thức UDP

<img src="http://i.imgur.com/jlXnuTl.png" />



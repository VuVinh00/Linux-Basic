## Socket là gì?
Có một vài định nghĩa như sau:
- Sử dụng standard Unix file descriptors để giao tiếp với các chương trình khác.

File descriptor thì hiểu đơn giản là khi ta nhắc đến 1 file thì phải có 1 cái gì cụ thể <sờ được, xóa được, tạo được> để mô tả nó, đó chính là file descriptor. Trong linux nó chỉ là 1 con số integer để kernel phân biệt các file

- Socket được sử dụng để cho phép 1 process nói chuyện với 1 process khác. Rất giống với định nghĩa 1 chiếc điện thoại - cho phép 1 người nói chuyện với 1 người khác.

## Phần mở rộng file trên Linux:

Phần mở rộng file là các chữ cái được hiển thị ngay sau đoạn cuối cùng trong tên file. Ví dụ: vuvinh.txt có phần mở rộng là txt. Phần mở rộng này cho phép hệ điều hành nhận biết loại file đó là gì và chương trình nào sẽ chạy khi bạn mở file này.

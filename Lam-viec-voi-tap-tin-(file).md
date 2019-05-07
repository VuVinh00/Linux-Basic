### 1: Tạo tập tin mới - touch

Cú pháp : 
`touch <tên_file>`

### 2: Đổi tên, di chuyển file - mv

mv có 2 chức năng kép đó là di chuyển và đổi tên

#### 2.1: Đổi tên:

Cú pháp:
`mv <đường dẫn cũ với tên cũ> <đường dẫn mới với tên mới>`

Ví dụ đổi file test.txt thành new.txt
` mv /home/test.txt /home/new.txt `

#### 2.2: Di chuyển:
`mv <đường dẫn nguồn> <đường dẫn đích>`

Ví dụ muốn di chuyển tập tin test.txt ở /home sang /etc

`mv /home/test.txt /etc/test.txt`

### 3: Trình soạn thảo vi:
Trên linux có nhiều trình soạn thảo văn bản, thông dụng nhất hiện nay vẫn là trình soạn thảo vi.

Cú pháp: `vi <tên_tập_tin hoặc đường_dẫn_tập_tin>`

Cách dùng : 

Ví dụ khi dùng lệnh: `vi test.txt`
- Nếu file test.txt chưa tồn tại thì sẽ tạo file test.txt và vào trong file test.txt với chế độ dòng lệnh
- Nếu file test.txt đã tồn tại thì sẽ vào chế độ dòng lệnh của file test.txt

Bấm **i** để vào chế độ soạn thảo và bắt đầu chỉnh sửa file với thao tác như sửa, xóa, thêm, bớt, ...

Khi muốn thoát:

Thoát không lưu:`ESC + :q! + Enter`

Thoát và lưu:`ESC + :x! + Enter`

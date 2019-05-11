Trong Linux 

## Tìm ra loại lệnh ( type -t )

Nếu ta dùng type -t thì nó sẽ in ra một từ thuộc trong những từ dưới đây:
 - alias ( nghĩa là shell alias )
 - keyword ( nghĩa là shell reserved word )
 - function ( nghĩa là shell function )
 - builtin ( nghĩa là shell builtin )
 - file ( nghĩa là disk file )

Ví dụ:

Command | Output | Ý nghĩa
--- | --- | ---
type -t ls | alias | Là tên rút gọn của command, thay vì phải nhập lệnh đầy đủ của ls thì chúng ta chỉ cần nhập là ls
type -t pwd | builtin | Là lệnh được xây dựng bên trong vỏ của nó, những lệnh này có thể dùng khi hệ thống bị crash hoặc không thể truy cập được vào máy tính
type -t date | file | Là các lệnh bên ngoài được lưu trữ tại: /bin /usr/bin /usr/local/bin /sbin /usr/sbin /usr/local/sbin
type -t xrpm | function | Là một hàm do người dùng tự định nghĩa
type -t if | keyword | Là câu lệnh đặc biệt dùng trong shell |


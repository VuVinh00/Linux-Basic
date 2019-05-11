## Filesystem là gì ?
Filesystem là thứ xác định các thức tổ chức, quản lý dữ liệu hay có thể nói là quản lý cách thức dữ liệu được đọc và lưu trên thiết bị. Filesystem cho phép người dùng truy cập nhanh chóng và an toàn khi vào các tệp tin thư mục khi cần thiết.

Những loại Filesystem được hỗ trợ trên Linux:
- Filesystem cơ bản : ext2, ext3, ext4, XFS, Btrfs, JFS, NTFS, ...
- Filesystem dành cho dạng lưu trữ Flash ( thẻ nhớ, ...): ubifs, JFFS2, YAFFS, ...
...

## Cấu trúc Filesystem trên Linux

Filesystem trên Linux lưu trữ những file quan trọng theo một tiêu chuẩn được gọi là FHS ( Filesystem Hierarchy Standard ). Trong FHS, tất cả file và thư mục đều nằm trong thư mục root **/**. Việc có một tiêu chuẩn như này giúp người dùng, quản trị viên, lập trình viên có thể chuyển đổi giữa các Distro một cách dễ dàng

<img src="https://github.com/vinhvt2704/Images/blob/master/filesystem.png">

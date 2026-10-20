# bai_lam_ngay1

# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên: Bùi Nhật Minh**
- **Lớp: CNTT4**
- **Link repository:**
- **Hệ điều hành (Windows/macOS): WINDOWS**

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.
> 

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```bash
- pwd
- dir -recurse -force
- mv .\lich_hoc.txt .\docs\
- mv .\logo_trung_tam.PNG .\media\
- mv .\anh_lop_hoc.JPG .\media\
- cp .\media\logo_trung_tam.PNG .\archive\
- rm .\temp_201.tmp
- rm .\temp_202.tmp
- cd .\logs
- dir
- cp ..\media\anh_lop_hoc.JPG ..\archive\
- cd ..

```

### Kết quả B1 (pwd)

```
Path
----
C:\Users\h\OneDrive\Documents\bài luyện tập ngày 1\starter-kit\trung-tam-..
```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```
 Directory: C:\Users\h\OneDrive\Documents\bài luyện tập ngày
    1\starter-kit\trung-tam-tieng-anh

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
dar--l        10/20/2026  10:08 PM                archive
dar--l        10/20/2026  10:00 PM                data
dar--l        10/20/2026  10:03 PM                docs
dar--l        10/20/2026  10:00 PM                logs
dar--l        10/20/2026  10:04 PM                media
-a---l        10/20/2026   9:51 PM             83 .env
-a---l        10/20/2026   9:51 PM            902 bai_lam_ngay1.md

    Directory: C:\Users\h\OneDrive\Documents\bài luyện tập ngày
    1\starter-kit\trung-tam-tieng-anh\archive

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---l        10/20/2026   9:51 PM          13559 anh_lop_hoc.JPG
-a---l        10/20/2026   9:51 PM           5184 logo_trung_tam.PNG

    Directory: C:\Users\h\OneDrive\Documents\bài luyện tập ngày
    1\starter-kit\trung-tam-tieng-anh\data

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---l        10/20/2026   9:51 PM           5070 hoc_vien_khoa.xlsx

    Directory: C:\Users\h\OneDrive\Documents\bài luyện tập ngày
    1\starter-kit\trung-tam-tieng-anh\docs

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---l        10/20/2026   9:51 PM             67 lich_hoc.txt

    Directory: C:\Users\h\OneDrive\Documents\bài luyện tập ngày
    1\starter-kit\trung-tam-tieng-anh\logs

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---l        10/20/2026   9:51 PM           1072 access.log

    Directory: C:\Users\h\OneDrive\Documents\bài luyện tập ngày
    1\starter-kit\trung-tam-tieng-anh\media

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
dar--l        10/20/2026   9:57 PM                New folder
-a---l        10/20/2026   9:51 PM          13559 anh_lop_hoc.JPG
-a---l        10/20/2026   9:51 PM           5184 logo_trung_tam.PNG
```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm: 100**/100
- **Lỗi mình đã mắc và cách sửa:**
# BÀI LÀM – HACKATHON 01

- **Mã đề:** 16
- **Họ tên:** Thi Thành Đạt
- **Lớp:** CNTT2
- **Link repository:** 
- **Hệ điều hành (Windows/macOS):** Windows

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy

```shell
pwd
Get-ChildItem .. -Recurse -Force
```

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
(C:\Users\admin\Downloads\starter-kit\starter-kit)

    Directory: C:\Users\admin\Downloads\starter-kit


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/28/2026   2:10 PM                starter-kit


    Directory: C:\Users\admin\Downloads\starter-kit\starter-kit


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/28/2026   1:57 PM                backup
d-----        10/28/2026   2:08 PM                data
d-----        10/28/2026   1:57 PM                docs
d-----        10/28/2026   2:08 PM                logs
d-----        10/28/2026   1:57 PM                media
d-----        10/28/2026   2:10 PM                sua-may-tinh-website
-a----        10/27/2026   1:32 AM             72 .env
------        10/27/2026   1:32 AM           2225 bai_lam.md
-a----        10/27/2026   1:32 AM             61 Quy Dinh Bao Hanh.txt.txt
-a----        10/27/2026   1:32 AM             22 temp_241.tmp


    Directory: C:\Users\admin\Downloads\starter-kit\starter-kit\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM           6101 Phieu Sua Thang 6.xlsx.xlsx


    Directory: C:\Users\admin\Downloads\starter-kit\starter-kit\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM           1069 Repair.Log.log


    Directory: C:\Users\admin\Downloads\starter-kit\starter-kit\sua-may-tinh-website


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM           2225 bai_lam.md
-a----        10/27/2026   1:32 AM           6767 Logo Sua May Tinh.PNG.PNG

rm temp_241.tmp
```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```shell
(Get-Content $log | Select-String -Pattern "CRITICAL", "ERROR" | Measure-Object).Count

```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [ ] Heading 1: tên dự án
- [ ] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [ ] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [ ] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [ ] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [ ] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell


```

### Kết quả hiển thị

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.6. Đếm số dòng lỗi

### Lệnh

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng (xoá dòng này)

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.8. Excel

> Phần Excel được chấm trực tiếp trên file `data/phieu_sua_thang_6.xlsx`, không cần ghi vào đây.

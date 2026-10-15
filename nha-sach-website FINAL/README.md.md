# bai_lam

# BÀI LÀM – HACKATHON 01

- **Mã đề:** 01
- **Họ tên:** Nguyễn Hoàng Hiệp
- **Lớp:**
- **Link repository:**
- **Hệ điều hành (Windows/macOS):**

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy

```bash

```

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```
Get-Childitem-Force
Move item
Copy-item
Remove-item
```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```bash
Get-content .\logs\store.log | Select-String "ERROR" .log\daily_report.txt

Get-content .log\daily_report.txt
```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```
(Dán kết quả vào đây – xoá dòng này)
```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.
> 
- [ ]  Heading 1: tên dự án
- [ ]  Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [ ]  Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [ ]  Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [ ]  Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [ ]  Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```bash
# Ghi lệnh vào đây (xoá dòng này)
```

### Kết quả hiển thị

```
(Dán kết quả vào đây – xoá dòng này)
```

## 4.6. Đếm số dòng lỗi

### Lệnh

```bash
(Get-content logs/store.log | Select-String "ERORR").Count
```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```
(Dán kết quả vào đây – xoá dòng này)
```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```bash
"=== TONG HOP LOG ===" | Set-Content .\logs\tong_hop.txt
Get-Content .\logs\store.log | Select-String "WARNING" | ForEach-Object { $_.Line } | Add-Content .\logs\tong_hop.txt
(Get-Content .\logs\store.log | Select-String "ERROR").Count | Add-Content .\logs\tong_hop.txt
Get-Content .\logs\tong_hop.txt
```

### Nội dung file logs/tong_hop.txt

```
(Dán kết quả vào đây – xoá dòng này)
```

## 4.8. Excel

> Phần Excel được chấm trực tiếp trên file `data/hoa_don_thang_10.xlsx`, không cần ghi vào đây.
>
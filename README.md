# Bài 1 — Khởi tạo Local Repository và cấu hình danh tính

**Sinh viên:** NguyễnDăngDương
**Lớp:** CNTT2
**Môn học:** IT209 — Session 04

## Các lệnh thực hiện

```bash
git init -b main
git config --local user.name "NguyễnDăngDương"
git config --local user.email "pedguedes090@outlook.com"
git status
git add README.md
git commit -m "Initialize local repository"
```

`--local` chỉ lưu danh tính trong repository hiện tại, không thay đổi cấu hình Git toàn máy. `git add` đưa báo cáo vào staging area; commit lưu snapshot đầu tiên.

## Kiểm tra

```bash
git config --local user.name
git config --local user.email
git config --local --list
git log --oneline
git status
```

Tên và email cần khớp với danh tính người học. `git log --oneline` hiển thị commit đầu tiên; `git status` cho biết working tree đã sạch sau commit.

---
share: true
created: 2023-05-26T14:51
updated: 2023-10-27T18:56
---
# Quên add

# [Git không biết gì về folder](../../../%E2%9A%A1Hi%E1%BB%83u%20bi%E1%BA%BFt%20s%C3%A2u/Khoa%20h%E1%BB%8Dc%20m%C3%A1y%20t%C3%ADnh/H%E1%BB%A3p%20t%C3%A1c%20l%C3%A0m%20vi%E1%BB%87c/Git%20kh%C3%B4ng%20bi%E1%BA%BFt%20g%C3%AC%20v%E1%BB%81%20folder.md)

# Thêm file vào  .gitignore rồi mà vẫn không thấy file bị ignore

# Lỡ commit file nặng
```
git filter-branch --force --index-filter 'git rm -r --cached --ignore-unmatch bigfile.txt' --prune-empty --tag-name-filter cat -- --all
```

---
share: true
created: 2023-05-26T14:51
updated: 2023-10-27T21:28
---
> [!info] [Tại sao lại cần tải vault về hơn là đọc trên web？](../../../9%20Blog/T%E1%BA%A1i%20sao%20l%E1%BA%A1i%20c%E1%BA%A7n%20t%E1%BA%A3i%20vault%20v%E1%BB%81%20h%C6%A1n%20l%C3%A0%20%C4%91%E1%BB%8Dc%20tr%C3%AAn%20web%EF%BC%9F.md)

# Cài đặt tự động
Bộ cài này dành cho Windows 10 trở lên:

[Tải bộ cài :octicons-download-16:](https://Obsidian.Quảcầu.cc/assets/Obsidian, quản lý dự án và công cụ nghĩ.exe){ .md-button .md-button--primary }

Hình ảnh bộ cài:
![](https://i.imgur.com/e3iB6N3l.png)

Hình ảnh sau khi cài xong:
![](https://i.imgur.com/c6PDsL1.png)

Để đảm bảo an toàn cho máy bạn, Obsidian sẽ hỏi là bạn có muốn tin kho dữ liệu này không không. Hãy bấm *Trust author and enable plugins*. Obsidian sẽ bật Settings lên để bạn duyệt các plugin. Bạn có thể bấm vào *Check for updates* để cập nhật chúng, hoặc tắt đi cũng được:
![](https://i.imgur.com/MhgGMBc.png) 

Vậy là xong. 

Xem thêm:: [Các trục trặc có thể gặp khi cài](./C%C3%A1c%20tr%E1%BB%A5c%20tr%E1%BA%B7c%20c%C3%B3%20th%E1%BB%83%20g%E1%BA%B7p%20khi%20c%C3%A0i.md) 

# Cài đặt thủ công
Mở terminal lên (ở đây dùng PowerShell) và nhập các lệnh sau:
```PowerShell
New-ItemProperty -Path "HKLM:\SYSTEM\CurrentControlSet\Control\FileSystem" -Name "LongPathsEnabled" -Value 1 -PropertyType DWORD -Force
Set-Location "D:\" 
git config --global core.quotePath false
git config --global core.longpaths true
git config --global core.autocrlf true
git config --global core.safecrlf false
git clone https://github.com/QuaCau-TheSphere/quan-ly-du-an-va-cong-cu-nghi
Rename-Item "quan-ly-du-an-va-cong-cu-nghi/" "Obsidian, quản lý dự án và công cụ nghĩ"
git config --global --add safe.directory *
```

Nếu bạn chưa hiểu Git là gì nhưng cũng muốn thử sức thì có thể bắt đầu tìm hiểu ở bài [5.1 GitHub là gì](../../../../../%E2%9A%94%EF%B8%8F%20H%C6%B0%E1%BB%9Bng%20d%E1%BA%ABn%20Obsidian%20v%C3%A0%20Git/5%20L%C3%A0m%20vi%E1%BB%87c%20c%C3%B9ng%20nhau/5.1%20GitHub%20l%C3%A0%20g%C3%AC.md)

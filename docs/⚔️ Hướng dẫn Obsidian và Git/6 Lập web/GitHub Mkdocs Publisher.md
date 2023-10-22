---
share: true
created: 2023-06-07T16:20
updated: 2023-10-10T20:44
tags:
  - tt_chưa-hoàn-thành
  - file_bài-học
---

%%
#tt/chưa-hoàn-thành
#file/bài-học
%%

2. Copy folder plugin
3. Thêm share key
	```
	pip install py-obsidianmd
	py '..\..\Code\Scripts\Thêm share vào YAML cho tất cả các file.py 'path_to_vault'
	```
1. [Tạo template trên github](https://github.com/ObsidianPublisher/template-netlify-vercel/generate)
4. clone template vừa tạo
```
git clone 
```
5. Sửa mkdocs.yml, thêm logo
6. Tạo requirement.txt để Netlify sử dụng
```
pip freeze > requirements.txt
```
Những file nào ko muốn cho hiện lên thì bỏ `share: true` trong yaml đi, rồi dùng lệnh này
![](https://i.imgur.com/hipQiyn.png)

# Thêm subdomain
- Cloudflare
- Netlify

[[../../📜 Tài nguyên/Làm dự án/Web/Web tĩnh/Mkdocs giúp dựng một web tĩnh từ các file markdown|Mkdocs giúp dựng một web tĩnh từ các file markdown]]
> [!tip] Mẹo

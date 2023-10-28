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

[Mkdocs giúp dựng một web tĩnh từ các file markdown](Mkdocs%20gi%C3%BAp%20d%E1%BB%B1ng%20m%E1%BB%99t%20web%20t%C4%A9nh%20t%E1%BB%AB%20c%C3%A1c%20file%20markdown.md)
> [!tip] Mẹo

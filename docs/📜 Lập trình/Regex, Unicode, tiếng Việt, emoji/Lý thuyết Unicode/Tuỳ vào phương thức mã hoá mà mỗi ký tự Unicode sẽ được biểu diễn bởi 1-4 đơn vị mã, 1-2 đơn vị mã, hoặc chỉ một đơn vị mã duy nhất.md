---
share: True
---
| Phương thức mã hoá | Số đơn vị mã (code unit) cần để biểu diễn một ký tự bất kỳ | Số byte cần cho một đơn vị mã |
| ------------------ | ---------------------------------------------------------- | ----------------------------- |
| UTF-8              | 1-4                                                        | 1                             |
| UTF-16             | 1-2                                                        | 2                             |
| UTF-32             | 1                                                          | 3                             |

Nguồn:: [Tìm hiểu Unicode](https://viblo.asia/p/tim-hieu-unicode-PwRkgVOXeEd)
Ví dụ, chữ `à` có 2 code point:
- `U+0061` cho chữ `a`
- `U+0300` cho dấu huyền

Có thể kiểm tra điều này bằng lệnh 
```
"à".length //kết quả là 2 😲
```
Tuy nhiên, `a` cũng có thể có 1 code point là `U+00E0`.
[UTF là cách thức để chuyển đổi từ điểm mã sang hệ nhị phân](./UTF%20l%C3%A0%20c%C3%A1ch%20th%E1%BB%A9c%20%C4%91%E1%BB%83%20chuy%E1%BB%83n%20%C4%91%E1%BB%95i%20t%E1%BB%AB%20%C4%91i%E1%BB%83m%20m%C3%A3%20sang%20h%E1%BB%87%20nh%E1%BB%8B%20ph%C3%A2n.md#)
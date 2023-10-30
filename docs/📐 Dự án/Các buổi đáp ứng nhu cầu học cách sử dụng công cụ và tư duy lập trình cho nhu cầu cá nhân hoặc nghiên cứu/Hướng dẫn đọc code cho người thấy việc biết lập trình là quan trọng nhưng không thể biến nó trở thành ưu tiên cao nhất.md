---
share: true
created: 2023-07-13T19:21
updated: 2023-10-27T21:28
tags:
  - file_thành-phẩm_bài-viết
---

%%
#file/thành-phẩm/bài-viết 
%%
Bạn không muốn lệ thuộc.

Bạn muốn biết lập trình chứ không phải là không, nhưng:
- Còn nhiều nhu cầu khác bạn phải xử lý, nên dù bạn cứ suy nghĩ rằng một ngày nào đó mình phải dành thời gian cho nó, nhưng mãi mà bạn vẫn không thể biến nó trở thành ưu tiên cao nhất
- Tài liệu hướng dẫn mang danh là dành cho người mới, nhưng nó vẫn quá nhiều thứ với bạn

Vàààààààà đến một ngày bạn có một bài toán thực sự cần phải code, và bạn không thể nhờ ai khác code cho được. Thực sự là bạn phải xắn tay vào làm rồi.

Nhưng thực sự là bạn không thể thong thả để làm được. Bạn biết là việc học thì sẽ mất thời gian, và nếu nó cần phải mất nhiều thời gian thì bạn cũng phải chịu thôi nhưng bạn vẫn cảm thấy mình cần phải . Cái trạng thái đó không phải là cái trạng thái phù hợp cho việc học, nhưng the brain is funny.

Việc nhảy ngang như vậy làm cho không một tài liệu hướng dẫn nào theo kịp bạn. Vì muốn hướng dẫn bạn thì phải áng chừng được trình độ bạn đang ở đâu. Và một code product thì người ta không kỳ vọng rằng phải giải thích tất cả những thứ căn bản
[Mỗi một thắc mắc đều làm tăng thêm khối lượng nhận thức mà chúng ta có trong tâm trí, qua đó làm phân tán sự tập trung của ta khỏi thứ mà ta định làm](../../%E2%9A%A1Hi%E1%BB%83u%20bi%E1%BA%BFt%20s%C3%A2u/Ngh%C4%A9%20v%E1%BB%81%20vi%E1%BB%87c%20ngh%C4%A9/G%C3%A1nh%20n%E1%BA%B7ng%20nh%E1%BA%ADn%20th%E1%BB%A9c,%20thi%E1%BA%BFt%20k%E1%BA%BF/M%E1%BB%97i%20m%E1%BB%99t%20th%E1%BA%AFc%20m%E1%BA%AFc%20%C4%91%E1%BB%81u%20l%C3%A0m%20t%C4%83ng%20th%C3%AAm%20kh%E1%BB%91i%20l%C6%B0%E1%BB%A3ng%20nh%E1%BA%ADn%20th%E1%BB%A9c%20m%C3%A0%20ch%C3%BAng%20ta%20c%C3%B3%20trong%20t%C3%A2m%20tr%C3%AD,%20qua%20%C4%91%C3%B3%20l%C3%A0m%20ph%C3%A2n%20t%C3%A1n%20s%E1%BB%B1%20t%E1%BA%ADp%20trung%20c%E1%BB%A7a%20ta%20kh%E1%BB%8Fi%20th%E1%BB%A9%20m%C3%A0%20ta%20%C4%91%E1%BB%8Bnh%20l%C3%A0m.md)

[❓ Học code bằng việc debug product code sẽ nhanh hơn](../../%E2%9A%A1Hi%E1%BB%83u%20bi%E1%BA%BFt%20s%C3%A2u/Khoa%20h%E1%BB%8Dc%20m%C3%A1y%20t%C3%ADnh/%E2%9D%93%20H%E1%BB%8Dc%20code%20b%E1%BA%B1ng%20vi%E1%BB%87c%20debug%20product%20code%20s%E1%BA%BD%20nhanh%20h%C6%A1n.md)
Nó là cách học qua bắt chước
Git blame
Hướng dẫn đọc hiểu code cho người rất lờ mờ về code
Biết được cách debug là sẽ dần dần biết cách bắt chước
Làm trên code sản phẩm là sát sườn nhất
cố gắng tái tạo lại ý đồ của người viết lúc tạo ra đoạn code đó
nói gì, bạn muốn biết phải bắt đầu google từ đâu, nhưng 

Một số thứ sẽ giúp bạn hiểu code nói gì:
- Biết thao tác với IDE,
- Hiểu được một số khái niệm và từ khoá cơ bản: object, method, array, for, if, import, function, type
- Hiểu một số quy ước viết code
- Hiểu được IDE đang cố gắng nói cho mình cái gì
- Biết một số kỹ thuật debug: console.log, debugger, unit test
# Thao tác với IDE
[Phím tắt cho VS Code](Ph%C3%ADm%20t%E1%BA%AFt%20cho%20VS%20Code.md)
Nguồn:: [Tự ngẫm nghĩ, trải nghiệm](../../%E2%9A%A1Hi%E1%BB%83u%20bi%E1%BA%BFt%20s%C3%A2u/%CE%9E%20Ngu%E1%BB%93n/T%E1%BB%B1%20ng%E1%BA%ABm%20ngh%C4%A9,%20tr%E1%BA%A3i%20nghi%E1%BB%87m.md)

# Hiểu quy tắc viết tài liệu
```js
/**
 * Tên hàm
 * @constructor
 * @param {string} title - The title of the book.
 * @param {string} author - The author of the book.
 */
function hàm(biến1, biến2) {
}
```

[Các buổi đáp ứng nhu cầu học cách sử dụng công cụ và tư duy lập trình cho nhu cầu cá nhân hoặc nghiên cứu](./index.md)



Nếu bạn chưa rành về lập trình, thì khó khăn bạn gặp sẽ nhiều hơn. Vừa muốn tập trung vào ý tưởng vừa cần phải học ngôn ngữ đó.
Các bài tập không chỉ được thiết kế để bạn nắm được cách sử dụng Obsidian và các phần mềm bổ trợ khácChỉnh từ từ để không bị ngộp, nhưng sau đó vứt đi, mà còn chính là vault của bạn trong việc quản lý dự án
Các bài học phải đến từ serious use of learner. Nó phải giải đáp được nhu cầu có thực của riêng họ, chứ không phải chỉ là một ví dụ cho dễ hiểu xong rồi xóa đi. Bài tập được giao cho họ phải là thứ họ rồi cũng sẽ phải làm
Không học bài bản ngôn ngữ, nhưng đụng vấn đề nào cần giải thích thì sẽ giải thích, cũng như dẫn đến các tài liệu sâu hơn, bỏ qua những cái nhìn vào cũng đoán đoán, mò mò được
Tất nhiên, học được bài bản thì rất tốt, nhưng [Việc mò mẫm vui, đỡ phải nghĩ và thường là hiệu quả hơn là đọc hướng dẫn cẩn thận](../../%E2%9A%A1Hi%E1%BB%83u%20bi%E1%BA%BFt%20s%C3%A2u/Ngh%C4%A9%20v%E1%BB%81%20vi%E1%BB%87c%20ngh%C4%A9/G%C3%A1nh%20n%E1%BA%B7ng%20nh%E1%BA%ADn%20th%E1%BB%A9c,%20thi%E1%BA%BFt%20k%E1%BA%BF/Vi%E1%BB%87c%20m%C3%B2%20m%E1%BA%ABm%20vui,%20%C4%91%E1%BB%A1%20ph%E1%BA%A3i%20ngh%C4%A9%20v%C3%A0%20th%C6%B0%E1%BB%9Dng%20l%C3%A0%20hi%E1%BB%87u%20qu%E1%BA%A3%20h%C6%A1n%20l%C3%A0%20%C4%91%E1%BB%8Dc%20h%C6%B0%E1%BB%9Bng%20d%E1%BA%ABn%20c%E1%BA%A9n%20th%E1%BA%ADn.md), [Kể cả khi ta biết một trang web trả lời câu hỏi cho ta, thì việc đọc cũng nhức đầu](../../%E2%9A%A1Hi%E1%BB%83u%20bi%E1%BA%BFt%20s%C3%A2u/Ngh%C4%A9%20v%E1%BB%81%20vi%E1%BB%87c%20ngh%C4%A9/G%C3%A1nh%20n%E1%BA%B7ng%20nh%E1%BA%ADn%20th%E1%BB%A9c,%20thi%E1%BA%BFt%20k%E1%BA%BF/Thi%E1%BA%BFt%20k%E1%BA%BF/K%E1%BB%83%20c%E1%BA%A3%20khi%20ta%20bi%E1%BA%BFt%20m%E1%BB%99t%20trang%20web%20tr%E1%BA%A3%20l%E1%BB%9Di%20c%C3%A2u%20h%E1%BB%8Fi%20cho%20ta,%20th%C3%AC%20vi%E1%BB%87c%20%C4%91%E1%BB%8Dc%20c%C5%A9ng%20nh%E1%BB%A9c%20%C4%91%E1%BA%A7u.md). 
Không ai đến với lập trình vì muốn lập trình cả, mà là vì họ cần giải quyết vấn đề khác, mà vấn đề đó cần lập trình

## [📜 Tài nguyên](../../%F0%9F%93%9C%20T%C3%A0i%20nguy%C3%AAn/index.md)

Lao ngay vào code trong product thì hổng kiến thức do nhiều chỗ viết tắt cho dễ đọc, dễ quản lý. Học từ từ thì thấy lãng phí thời gian.
Để đọc được tới dòng này là cả một sự nỗ lực ở lại của bạn. Dù bạn có từng đọc bao nhiêu trang khác rồi thì 
Chỉ ghi lại những thứ mất nhiều thời gian để nhận ra. Cái nào dễ thấy thì ko ghi 
- muốn nhưng google được là có thì không ghi. Khi nào bị bug rồi mới phát hiện ra một cái gì đó mà không thấy ai nói gì thì mới ghi
- Nếu cản trở sự đọc hiểu mà phải google thì cũng ghi ra 


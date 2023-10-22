---
share: true
created: 2023-06-01T21:27
updated: 2023-10-06T16:09
---
JSON sẽ chuyển đổi dữ liệu thành một chuỗi byte có thể lưu trữ và truyền qua mạng, dùng để response cho API. Và ta dùng JSON khi muốn lưu dữ liệu ở phía server.
Nguồn:: [Tìm hiểu về JSON và sự khác nhau giữa JSON và Dictionary trong Python - Python - Magestore](https://stories.magestore.com/t/tim-hi-u-v-json-va-s-khac-nhau-gi-a-json-va-dictionary-trong-python/1247#:~:text=Dictionary%20trong%20Python%20được%20hiểu,dùng%20để%20response%20cho%20API%2e)

| JSON                                                                                 | Dictionary                                                                                                                                                                                       |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| The keys in JSON can be only strings.                                                | The keys in the dictionary can be any hashable object.                                                                                                                                           |
| In JSON, the keys are sequentially ordered and can be repeated.                      | In the dictionary, the keys cannot be repeated and must be distinct.                                                                                                                             |
| In JSON, the keys have a default value of undefined.                                 | Dictionaries do not have any default value set.                                                                                                                                                  |
| IN JSON file format, the values are accessed by using the “.”(dot) or “[]” operator. | In the dictionary, the values are mostly accessed by the subscript operator. For example, if 'dict' = {'A':'123R' ,'B':'678S'} then by simply calling dict['A'] we can access values associated. |
| We are required to use the double quotation for the string object                    | We can use either a single or double quote for the string objects                                                                                                                                |
| The return object type in JSON is a ‘string’ object type                             | The return object type in a dictionary is the ‘dict’ object type                                                                                                                                 |
Nguồn:: [Convert Dictionary to JSON Python - Scaler Topics](https://www.scaler.com/topics/convert-dictionary-to-json-python/#:~:text=Difference%20between%20dict%20and%20JSON&text=The%20keys%20in%20JSON%20can,repeated%20and%20must%20be%20distinct%2e)
[In JavaScript, dictionaries are called objects, whereas, in languages like Python or C, they are called dictionaries](./In%20JavaScript,%20dictionaries%20are%20called%20objects,%20whereas,%20in%20languages%20like%20Python%20or%20C,%20they%20are%20called%20dictionaries.md)

[JSON là cách để biểu diễn vật thể ra chữ](../L%E1%BA%ADp%20tr%C3%ACnh%20h%C6%B0%E1%BB%9Bng%20v%E1%BA%ADt%20th%E1%BB%83/Kh%C3%A1i%20ni%E1%BB%87m%20c%C6%A1%20b%E1%BA%A3n/V%E1%BA%ADt%20th%E1%BB%83/JSON%20l%C3%A0%20c%C3%A1ch%20%C4%91%E1%BB%83%20bi%E1%BB%83u%20di%E1%BB%85n%20v%E1%BA%ADt%20th%E1%BB%83%20ra%20ch%E1%BB%AF.md)

---
share: true
created: 2023-05-26T14:51
updated: 2024-10-02T15:26
---
%%
#file/thành-phẩm/bài-viết
%%

Phục vụ cho thành quả:
```dataview
LIST
FROM #file/thành-quả 
WHERE contains(thành-phẩm,[[]])
```
Người chơi:: 

Thành quả cần có::
Thành quả hỗ trợ::

Thành phẩm nhỏ hơn:
```dataview
List
Where contains(file.folder,this.file.folder) and file.name!=this.file.name
```

Giả thuyết:

:Trong 3 năm mình tham gia vào các mạng lưới, cộng đồng phi lợi nhuận, mình cảm thấy mặc dù đã có rất rất nhiều tổ chức muốn thúc đẩy một hệ sinh thái giữa các dự án, nhưng lại chưa cảm thấy sự hiệu quả đạt đến mức tối ưu, mặc dù mình đánh giá rất cao nỗ lực và sự chuyên nghiệp của họ. Mình phải thẳng thắn nói rằng mình thất vọng rất nhiều sau các sự kiện kết nối. Mọi người có biết đến nhau, nhưng sau buổi hôm đó cũng chỉ dừng lại ở đó, không đi xa hơn được. Mình nghĩ rằng nguyên nhân quan trọng nhất là các bên **quá nhiều việc**. Mọi người không thể đi đủ sâu để tìm hiểu về nhau. Vì để có thể đi sâu thì phải tốn rất rất nhiều thời gian, mà thường tổ chức phải phát triển đủ lớn để có một người chuyên về việc kết nối, chứ công việc thì rất rất nhiều. Nếu như các tổ chức kết nối cộng đồng chủ động phân loại và tổ chức các buổi gặp gỡ cho các dự án quy mô nhỏ tương tự nhau thì rất tốt, nhưng mình không thấy được điều đó.

[[Để một hệ sinh thái hoạt động thực sự hiệu quả thì lượng năng lượng dành ra để nắm bắt tín hiệu của môi trường phải giảm tới mức gần như bằng 0]]. Bạn không cần phải hỏi mà vẫn biết nhu cầu của những thành viên xung quanh, và họ không cần phải hỏi cũng biết bạn đang cần gì. Mặc dù chúng ta luôn khuyến khích đặt câu hỏi, nhưng [[Một hệ sinh thái không hoạt động bằng cách đặt câu hỏi, mà bằng cách không cần hỏi cũng biết câu trả lời là gì]]. Và các công cụ quản lý dự án hiện nay không có chức năng cung cấp thông tin của nhóm cho những nhóm khác. Chỉ khi nào nhu cầu của các bên liên quan hiện ra ngay trong kho dữ liệu của nhóm mà không cần phải hỏi họ hay thậm chí là nhập liệu, thì lúc đó chúng ta mới có thể bắt đầu nói về một hệ sinh thái mà những thành viên mới – vốn rất thiếu nhân lực – vẫn có thể hưởng lợi.

Trong những phần mềm quản lý công việc trên thị trường hiện nay, mình thấy có duy nhất Obsidian là có thể đáp ứng nhu cầu đó. Cho nên trong buổi thảo luận này mình sẽ nói về cách bọn mình sử dụng nó ra sao. Cùng với đó là mô hình tổ chức mà loại công nghệ này đem lại: 

Xem thêm: Một đám mây chim sáo: https://quacau.space/f025

# Giả thuyết
- [[Các tổ chức trong lúc mới hình thành rất mong có ai kết nối giùm]]
- [[Việc phải nói chuyện nhu cầu của nhau là mệt mỏi]]
- [[Việc có sẵn dữ liệu của các bên khác trong CSDL của mình sẽ giúp mình hoạch định tốt hơn]]
- [[Người dùng sử dụng dễ dàng Obsidian]]
- [[Obsidian hữu ích để quản lý công việc]]
- [[Chỉ có việc lưu dữ liệu ở dạng văn bản và ở trên máy người dùng mới có thể giúp liên thông dữ liệu một cách dễ dàng nhất]]

Scrum là một phương pháp Agile dùng cho phát triển sản phẩm.

![enter image description here](http://hocvienagile.com/wp-content/uploads/2016/03/Scrum-overview-edit-01-1024x572.png)
![enter image description here](http://imgur.com/RJuMPPa.png)

Scrum Team
-----
Scrum
=====

Roles
Scrum là một phương pháp Agile dùng cho phát triển sản phẩm.

![enter image description here](http://hocvienagile.com/wp-content/uploads/2016/03/Scrum-overview-edit-01-1024x572.png)

Scrum Team
-----

**Scrum có 3 vai trò chính:** [1]
Nhóm Scrum là nhóm tự tổ chức và liên chức năng bao gồm:

 1. `Product Owner` (PO) sẽ chịu trách nhiệm mọi mặt về sản phẩm. 
 2. `Dev Team` sẽ cho ra đời một gói tính năng hoạt động tốt, đã được kiểm thử, tích hợp vào hệ thống và có đầy đủ tài liệu người dùng theo yêu cầu (increment) vào cuối mỗi Sprint.
 3. `ScrumMaster` sẽ hỗ trợ team (PO và Dev Team) để có kết quả tốt nhất bằng cách tuân thủ các nguyên lý, kỹ thuật và quy tắc của Scrum.

 1. `Product Owner` (PO) chịu trách nhiệm mọi mặt về sản phẩm. 
 2. `ScrumMaster` hỗ trợ team (PO và nhóm phát triển) để có kết quả tốt nhất bằng cách tuân thủ các nguyên lý, kỹ thuật và quy tắc của Scrum.
 3. `Nhóm phát triển` sẽ cho ra đời một gói tính năng hoạt động tốt, đã được kiểm thử, tích hợp vào hệ thống và có đầy đủ tài liệu người dùng theo yêu cầu (increment) vào cuối mỗi Sprint.
> Lưu ý: trong Nhóm Scrum không tồn tại thêm một chức danh nào khác những vai trò trên như quản lý dự án (PM).

Events 

Scrum Events 
-----
**Scrum có 5 sự kiện chính:** [2]

Các sự kiện trong Scrum là những mốc thời gian để Nhóm Scrum tiến hành các hoạt động của mình.

### Sprint

Một Sprint có kéo dài từ 2 tuần đến 1 tháng, diễn ra liên tiếp và không bị gián đoạn.
Một `Sprint` có kéo dài từ 2 tuần đến 1 tháng, diễn ra liên tiếp và không bị gián đoạn.

Trong suốt Sprint:

- Không cho phép bất kì sự thay đổi nào ảnh hưởng đến Mục tiêu Sprint;
- Thành phần Nhóm Phát triển được giữ nguyên;
- Thành phần Dev Team được giữ nguyên;
- Mục tiêu chất lượng không được cắt giảm; và,
- Phạm vi có thể được làm rõ và tái thương lượng giữa Product Owner và Nhóm Phát triển.
- Phạm vi có thể được làm rõ và tái thương lượng giữa PO và Dev Team.

### Sprint Planning

Sự kiện Sprint planning diễn ra ở đầu mỗi Sprint để chuẩn bị cho toàn bộ Sprint.
`Sprint planning` diễn ra ở đầu mỗi Sprint để chuẩn bị cho toàn bộ Sprint.

- Thành phần tham dự: toàn bộ team. 
- Thời gian: kéo dài 2 tiếng (sprint 2 tuần) và được chia làm 2 phần.
- Thành phần tham dự: toàn bộ team (PO, ScrumMaster, & Dev Team). 
- Thời gian: kéo dài `2` giờ (sprint 2 tuần) và được chia làm 2 phần.

Phần 1:
**Phần 1: Chúng ta sẽ làm gì?**

```flow
st=>start: Start
e=>end: End
op1=>operation: Product Owner trình bày cách hạng mục trên Product Backlog có khả năng được đưa vào phát triển
op2=>operation: Nhóm phát triển ước lượng & lựa chọn các hạng mục trên Product Backlog  
io1=>inputoutput: Product Owner và Nhóm Phát triển đưa ra Mục tiêu Sprint
op1=>operation: PO trình bày cách hạng mục trên Product Backlog có khả năng được đưa vào phát triển
op2=>operation: Dev Team ước lượng & lựa chọn các hạng mục trên Product Backlog  
io1=>inputoutput: PO và Dev Team đưa ra Mục tiêu Sprint

st->op1->op2->io1->e
```

Phần 2:

**Phần 2: Chúng ta sẽ làm như thế nào?**

```flow
st=>start: Start
e=>end: End
op1=>operation: Nhóm Phát triển phân tích và lên kế hoạch công việc cho Sprint
op2=>operation: phân tách các hạng mục Product Backlog thành danh sách các tasks cụ thể
op3=>operation: estimate lượng nỗ lực cần bỏ ra để hoàn thành các tasks
c1=>operation: trao đổi với Product Owner nếu cần điều chỉnh danh sách các hạng mục đã chọn
io1=>inputoutput: có được Sprint Backlog
op1=>operation: Dev Team phân tích và lên kế hoạch công việc cho Sprint
op2=>operation: Phân tách các hạng mục Product Backlog thành danh sách các tasks cụ thể
op3=>operation: Estimate lượng nỗ lực cần bỏ ra để hoàn thành các tasks
c1=>operation: Rao đổi với PO nếu cần điều chỉnh danh sách các hạng mục đã chọn
io1=>inputoutput: Ra được Sprint Backlog

st->op1->op2->op3->c1->io1->e
```

> Tham khảo kỹ thuật ước tính linh hoạt (agile estimate): Planning Poker [1]

### Daily Scrum

`Daily Scrum` là buổi trao đổi ngắn mà `Dev Team` thực hiện đều đặn hằng ngày nhằm cập nhật và đồng bộ công việc giữa các thành viên. Do vậy, không cho phép bất cứ cuộc thảo luận chi tiết nào ở đây. 

- Thành phần tham dự: Dev Team. 
- Thời gian: tối đa `15` phút, bất kể số lượng thành viên.

```flow
st=>start: Start
e=>end: End
op1=>operation: Trình bày việc đã làm gì trong ngày hôm trước
op2=>operation: Trình bày việc sẽ làm gì trong ngày hôm nay
op3=>operation: Trình bày những issue đang gặp phải
io1=>inputoutput: Danh sách issue cần xử lý

st->op1->op2->op3->io1->e
```

### Sprint Review

`Sprint Review` diễn ra ở cuối Sprint nhằm thanh tra và thích nghi sản phẩm đang được xây dựng.

- Thành phần tham dự: Dev Team, ScrumMaster và PO bắt buộc phải tham dự. Ngoài ra, PO có thể mời những người khác như người dùng, khách hàng và các bên liên quan khác.
- Thời gian: tối đa trong `4` giờ (sprint 2 tuần).

```flow
st=>start: Start
e=>end: End
op1=>operation: PO trình bày về những hạng mục đã được lựa chọn cho Sprint, liệu chúng đã được hoàn thành hay chưa
op2=>operation: Dev Team demo những tính năng mới làm được trong Sprint
op3=>operation: Tất cả mọi người thảo luận về những việc cần làm tiếp theo
io1=>inputoutput: Ra được các hạng mục có thể đưa vào phát triển trong Sprint tiếp theo

st->op1->op2->op3->io1->e
```

### Sprint Retrospective

`Sprint Retrospective` diễn ra ngay sau buổi Sprint Review nhằm mục đích thanh tra và thích nghi quy trình làm việc.

- Thành phần tham dự: Dev Team và ScrumMaster bắt buộc phải tham dự.
- Thời gian: tối đa trong `1.5` giờ (sprint 2 tuần).

```flow
st=>start: Start
e=>end: End
op1=>operation: Sprint Review (con người, giao tiếp, quy trình và công cụ)
op2=>operation: Liệt kê những hạng mục tốt và chưa tốt có thể cải tiến
io1=>inputoutput: Kế hoạch triển khai các cải tiến

st->op1->op2->io1->e
```

> Tham khảo kỹ thuật cải tiến Sprint:  Glad-Sad-Mad [2]

Artifacts 
Scrum Artifacts 
-----

Các tạo tác trong Scrum là những công cụ hoặc kết quả được tạo ra và sử dụng trong quá trình vận hành Scrum. 

 1. Các hạng mục trong Product Backlog được chuyển hoá từ product
    roadmap/strategy.
### Product Backlog

Product Backlog là nơi lưu trữ danh sách các tính năng mong muốn của sản phẩm, có thể chứa các hạng mục thuộc các loại như:

----
[1] http://hocvienagile.com/agipedia/cac-vai-tro-trong-scrum/
[2] http://hocvienagile.com/agipedia/cac-su-kien-trong-scrum/
[3] http://hocvienagile.com/agipedia/cac-tao-tac-trong-scrum/
- Feature
- Bug
- Công việc liên quan đến kỹ thuật
- R&D

> Tham khảo cách mô tả hạng mục trên Product Backlog: User story [3]

Một Product Backlog tốt cần thỏa mãn tiêu chí `DEEP`, bao gồm:

- Detailed Appropriately (Đủ chi tiết Hợp lý)
- Estimated (Được ước tính)
- Emergent (Tiến hóa)
- Prioritized (Sắp xếp theo độ ưu tiên)

### Sprint Backlog 

Sprint Backlog chứa danh sách các hạng mục được phát triển trong Sprint và các công việc cần làm tương ứng với từng hạng mục để hoàn thành nó. 

3. Họp Scrum hàng ngày diễn ra vào buổi sáng, có thời gian tối đa là 15 phút.
4. Họp Sơ kết Sprint diễn ra ở cuối Sprint,kéo dài 2 tiếng. (Sprint 2 tuần)
5. Họp Cải tiến Sprint diễn ra ngay sau Sơ kết Sprint, kéo dài 90 phút. (Sprint 2 tuần)
> Tham khảo các công cụ để thể hiện, cập nhật tình hình phát triển của Sprint: Jira/Phabricator/Trello & Sprint Burndown Chart.

Sử dụng công cụ Planning Poker để ước tính linh hoạt (agile estimation) các hạng mục.
Sử dụng tool (jira/fabricator/trello...) để quản lý các hạng mục.
### Potentially Shippable Product Increment (Increment) 

Increment là phần sản phẩm "có thể chuyển giao" được Dev team tạo ra cuối mỗi Sprint được PO chấp nhận dựa trên sự "tin tưởng" vào tính sẵn sàng của sản phẩm.

> Tham khảo định nghĩa hoàn thành: DoD [4]

----
References
-----
[1] http://hocvienagile.com/blog/tag/planning-poker/
[2] http://hocvienagile.com/agipedia/glad-sad-mad/
[3] http://hocvienagile.com/agipedia/user-story/
[4] http://www.scrumguides.org/scrum-guide.html#artifact-transparency-done

[Scrum Guide] http://www.scrumguides.org/scrum-guide.html
[Tổng quan về Scrum] http://hocvienagile.com/agipedia/tong-quan-ve-scrum/
Scrum
---------------
=====

Roles
-----

**Scrum có 3 vai trò chính:** [1]

 1. `Product Owner` (PO) chịu trách nhiệm mọi mặt về sản phẩm. 
 2. `ScrumMaster` hỗ trợ team (PO và nhóm phát triển) để có kết quả tốt nhất bằng cách tuân thủ các nguyên lý, kỹ thuật và quy tắc của Scrum.
 3. `Nhóm phát triển` sẽ cho ra đời một gói tính năng hoạt động tốt, đã được kiểm thử, tích hợp vào hệ thống và có đầy đủ tài liệu người dùng theo yêu cầu (increment) vào cuối mỗi Sprint.

Events 
-----
**Scrum có 5 sự kiện chính:** [2]

### Sprint

Các hạng mục trong Product Backlog được chuyển hoá từ product roadmap/strategy.
Product Owner (PO) chịu trách nhiệm mọi mặt về sản phẩm.
Sự kiện:
Một Sprint có kéo dài từ 2 tuần đến 1 tháng, diễn ra liên tiếp và không bị gián đoạn.
Họp Lập kế hoạch Sprint diễn ra ở đầu Sprint, kéo dài 2 tiếng. (Sprint 2 tuần)
Họp Scrum hàng ngày diễn ra vào buổi sáng, có thời gian tối đa là 15 phút.
Họp Sơ kết Sprint diễn ra ở cuối Sprint,kéo dài 2 tiếng. (Sprint 2 tuần)
Họp Cải tiến Sprint diễn ra ngay sau Sơ kết Sprint, kéo dài 90 phút. (Sprint 2 tuần)
Cuối mỗi Sprint, Nhóm Phát triển cần bàn giao một gói tính năng hoạt động tốt, đã được kiểm thử, tích hợp vào hệ thống và có đầy đủ tài liệu người dùng theo yêu cầu.

Trong suốt Sprint:

- Không cho phép bất kì sự thay đổi nào ảnh hưởng đến Mục tiêu Sprint;
- Thành phần Nhóm Phát triển được giữ nguyên;
- Mục tiêu chất lượng không được cắt giảm; và,
- Phạm vi có thể được làm rõ và tái thương lượng giữa Product Owner và Nhóm Phát triển.

### Sprint Planning

Sự kiện Sprint planning diễn ra ở đầu mỗi Sprint để chuẩn bị cho toàn bộ Sprint.

- Thành phần tham dự: toàn bộ team. 
- Thời gian: kéo dài 2 tiếng (sprint 2 tuần) và được chia làm 2 phần.

Phần 1:

```flow
st=>start: Start
e=>end: End
op1=>operation: Product Owner trình bày cách hạng mục trên Product Backlog có khả năng được đưa vào phát triển
op2=>operation: Nhóm phát triển ước lượng & lựa chọn các hạng mục trên Product Backlog  
io1=>inputoutput: Product Owner và Nhóm Phát triển đưa ra Mục tiêu Sprint

st->op1->op2->io1->e
```

Phần 2:


```flow
st=>start: Start
e=>end: End
op1=>operation: Nhóm Phát triển phân tích và lên kế hoạch công việc cho Sprint
op2=>operation: phân tách các hạng mục Product Backlog thành danh sách các tasks cụ thể
op3=>operation: estimate lượng nỗ lực cần bỏ ra để hoàn thành các tasks
c1=>operation: trao đổi với Product Owner nếu cần điều chỉnh danh sách các hạng mục đã chọn
io1=>inputoutput: có được Sprint Backlog

st->op1->op2->op3->c1->io1->e
```


Artifacts 
-----


 1. Các hạng mục trong Product Backlog được chuyển hoá từ product
    roadmap/strategy.


----
[1] http://hocvienagile.com/agipedia/cac-vai-tro-trong-scrum/
[2] http://hocvienagile.com/agipedia/cac-su-kien-trong-scrum/
[3] http://hocvienagile.com/agipedia/cac-tao-tac-trong-scrum/

3. Họp Scrum hàng ngày diễn ra vào buổi sáng, có thời gian tối đa là 15 phút.
4. Họp Sơ kết Sprint diễn ra ở cuối Sprint,kéo dài 2 tiếng. (Sprint 2 tuần)
5. Họp Cải tiến Sprint diễn ra ngay sau Sơ kết Sprint, kéo dài 90 phút. (Sprint 2 tuần)

Sử dụng công cụ Planning Poker để ước tính linh hoạt (agile estimation) các hạng mục.
Sử dụng tool (jira/fabricator/trello...) để quản lý các hạng mục. 
Sử dụng tool (jira/fabricator/trello...) để quản lý các hạng mục.

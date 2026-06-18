---
artifact: 02 — JTBD Project Analysis
bai-tap: Lab 2 — Dùng JTBD để soi lại dự án nhóm
format: Theo nhóm dự án → share trong bàn → chốt hypothesis cuối
time: 25 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 2
companion-reference: Strategyn_JTBD_Playbook.pdf (giảng viên gửi kèm)
---

# Lab 2 — JTBD Project Analysis / Dùng JTBD để soi lại dự án nhóm

**Tên dự án / sản phẩm:** AI Trợ Lý Lập Kế Hoạch Sự Kiện & Hội Nghị (MICE) - Team 18.

> Đây là **file duy nhất** của Lab 2.  
> File này đồng thời đóng vai trò:
>
> - guide từng bước,
> - worksheet để điền trực tiếp,
> - và file nộp cuối cho người chấm.

Mục tiêu của bài này không phải brainstorm thêm thật nhiều tính năng AI.
Mục tiêu là:

1. **xác định người dùng thực sự đang cố hoàn thành job gì**
2. **hiểu họ đang dùng giải pháp nào để hoàn thành job đó hôm nay**
3. **chỉ ra AI nên chen vào đúng bước nào trong workflow**
4. **viết ra product hypothesis và assumption còn phải validate**

Quy tắc xuyên suốt: **không rõ job thì đừng bàn feature.**

---

## Cần mở song song 2 thứ

1. **File này** — để điền trực tiếp
2. **`Strategyn_JTBD_Playbook.pdf`** — giảng viên gửi kèm

### Cách dùng playbook cho đúng

Bạn **không cần đọc hết 48 trang**.  
Trong bài này, playbook chủ yếu dùng để tra 4 thứ:

1. **Cách nhìn thị trường qua JTBD lens**
2. **`Job executor` là ai**
3. **Cách viết `job statement`: `verb + object + contextual clarifier`**
4. **8 bước của `job map`**:
   `define -> locate -> prepare -> confirm -> execute -> monitor -> modify -> conclude`

### 2 chương nên mở nhiều nhất

- **Chapter 2 — Define Your Market**
- **Chapter 3 — Build Your Job Map**

> Dùng playbook để **tra framework và ví dụ**.  
> Dùng file này để **làm bài và chốt output**.

---

## Đầu ra bắt buộc

Người chấm cần thấy đủ 6 phần trong chính file này:

1. **`Project slice` + market context**
2. **`Job executor` + `core JTBD`**
3. **3 `job stories`**
4. **`JTBD lite map` + pain points**
5. **`AI leverage point` + `product hypothesis`**
6. **`Assumptions to validate` + verdict cuối sau thảo luận**

Nếu thiếu một trong sáu phần trên, bài sẽ bị xem là chưa hoàn chỉnh.

---

## Cách làm trong lớp (25 phút)

```text
3'  Chốt 1 lát cắt cụ thể của dự án
7'  Viết market context + job executor + core JTBD
6'  Viết 3 job stories + current alternatives
6'  Điền JTBD lite map + AI leverage point + hypothesis
3'  Share trong bàn và sửa version cuối
```

> Nếu dự án làm theo nhóm, cả nhóm có thể thảo luận chung.  
> Nhưng file này vẫn nên có **version chốt rõ ràng** của người nộp.

---

## Bước 0 — Khoanh đúng 1 lát cắt của dự án

Phần lớn dự án nhóm viết quá rộng ở bước này, rồi sau đó mọi thứ mơ hồ theo.

### Khoanh đúng 1 lát cắt theo 4 điểm

- [x] **1 nhóm người dùng chính**
- [x] **1 hoàn cảnh / tình huống rõ**
- [x] **1 job cốt lõi**
- [x] **1 workflow đủ cụ thể để vẽ ra được**

### Điền nhanh trước khi làm

- **Dự án của nhóm tôi là:** Ứng dụng AI Web App hỗ trợ doanh nghiệp sự kiện/resort tự động hóa việc lên kịch bản và báo giá.
- **Lát cắt tôi chọn để phân tích hôm nay là:** Giúp nhân viên Sales sự kiện tạo ra kịch bản sơ bộ và bảng báo giá chi tiết, chính xác chỉ trong vòng 30 giây ngay sau khi nhận yêu cầu từ khách hàng.
- **Vì sao tôi chọn lát cắt này:**  
  > Đây là điểm nghẽn (bottleneck) tốn nhiều thời gian nhất của Sales (mất tới 4 tiếng) và dễ sinh ra sai sót tài chính nhất nếu tính toán thủ công. Giải quyết được lát cắt này sẽ chứng minh ngay ROI của sản phẩm.

### Viết quá rộng vs viết sắc hơn

| Viết quá rộng | Viết sắc hơn |
|---|---|
| Giúp SME dùng AI để marketing | Giúp chủ shop online phản hồi câu hỏi trước mua hàng nhanh và nhất quán trong giờ cao điểm |
| Dùng AI để làm slide | Tạo bản nháp deck nội bộ mạch lạc cho buổi họp gấp trong thời gian rất ngắn |
| AI cho tuyển dụng | Giúp recruiter sàng lọc CV đầu vào nhanh hơn trước vòng gọi sơ bộ |

> Nếu bạn không mô tả được **một hoàn cảnh cụ thể**, khả năng cao bạn đang viết quá rộng.

---

## Bước 1 — Viết `Project Snapshot`

### Tóm tắt dự án trong 3 dòng

1. **Nhóm tôi đang nghĩ mình đang giải quyết vấn đề gì?**  
   > Giảm thiểu thời gian, nhân sự và sai sót toán học trong quy trình lập đề xuất (Proposal) và tính toán báo giá sự kiện.

2. **Người dùng chính hiện nhóm đang nhắm tới là ai?**  
   > Nhân viên Sales tại các trung tâm tiệc cưới, Resort, Villa/Homestay, và SME sự kiện.

3. **Hiện tại người dùng đó đang giải quyết vấn đề này bằng cách nào?**  
   > Phải huy động 2-3 người đi lục lọi file Excel, hỏi giá các bộ phận khác, tự dùng máy tính bấm cộng/trừ/thuế và gõ lại thủ công trên Word/PowerPoint.

---

## Bước 2 — Viết `Market Context`

Ở đây chưa cần solution. Chỉ cần bối cảnh thị trường đủ để hiểu:
**ai đang gặp chuyện gì, trong hoàn cảnh nào, và vì sao bây giờ đáng giải.**

### Trả lời 4 câu ngắn

1. **Ai đang gặp vấn đề này?**  
   > Nhân viên Sales chạy doanh số sự kiện.

2. **Vấn đề xuất hiện trong hoàn cảnh nào?**  
   > Khi khách hàng nhắn tin yêu cầu tổ chức một sự kiện với các thông số tùy chỉnh phức tạp (số lượng khách, loại thực đơn, thiết bị âm thanh/ánh sáng) và cần phản hồi gấp.

3. **Hiện tại họ đang dùng giải pháp thay thế nào?**  
   > Tìm giá trong các bảng tính Excel rời rạc, dùng máy tính cầm tay, format lại thành file PDF gửi khách.

4. **Vì sao đây là thời điểm đáng giải?**  
   > Áp lực chốt sale cần phản hồi siêu tốc. Sự kết hợp giữa AI bóc tách ngôn ngữ tự nhiên (LLM) và Engine tính toán logic (Python) đã đủ chín muồi để giải quyết triệt để sự thiếu chính xác của AI thuần túy.

### Tóm tắt market context trong 3-4 dòng

> Nhân viên Sales sự kiện đang phải vật lộn với quy trình báo giá thủ công bằng Excel và Word/PPT, mất nhiều giờ đồng hồ và dễ sai sót toán học khi phản hồi khách hàng gấp. Với sự chín muồi của công nghệ LLM bóc tách ngôn ngữ và các engine tính toán tự động, đây là thời điểm lý tưởng để tạo ra một công cụ thay thế hoàn toàn workflow cồng kềnh này, giúp Sales chốt đơn siêu tốc.

---

## Bước 3 — Xác định `Job Executor`

`Job executor` là người **trực tiếp dùng một giải pháp để hoàn thành job**.

### Đừng nhầm với:

- người mua tiền nhưng không trực tiếp làm job
- người ảnh hưởng quyết định
- cả một công ty hay một phòng ban quá rộng

### Gợi ý viết cho đúng

- Sai hoặc quá rộng: `SME`, `doanh nghiệp`, `thị trường`
- Tốt hơn: `chủ shop online`, `nhân viên CSKH`, `recruiter`, `sales ops manager`

### Điền

- **Job executor của dự án này là:** Nhân viên Sales sự kiện (Sales Staff).
- **Vì sao tôi tin đây là người trực tiếp "thuê" giải pháp để làm job:**  
  > Chủ doanh nghiệp (Admin) là người mua, nhưng Nhân viên Sales mới là người trực tiếp đối mặt với áp lực thời gian, thao tác tạo báo giá, chat với AI và xuất file PDF gửi cho khách hàng.

---

## Bước 4 — Viết `Core JTBD`

`Core JTBD` là công việc cốt lõi người dùng đang cố hoàn thành.

### Công thức gợi ý

```text
[verb] + [object] + [contextual clarifier]
```

### Ví dụ

- Chưa tốt: `trả lời inbox bằng AI`
- Tốt hơn: `giải quyết câu hỏi trước mua hàng nhanh và chính xác trong giờ cao điểm`

- Chưa tốt: `dùng AI để viết nội dung`
- Tốt hơn: `tạo bản nháp nội dung chiến dịch phù hợp với brand trong thời gian rất ngắn`

### 3 tiêu chí tự kiểm

- [x] Nếu bỏ tool hiện tại đi, job này vẫn còn tồn tại
- [x] Trong câu không có tên sản phẩm, AI, chatbot, app, màn hình
- [x] Câu đang mô tả **điều user muốn hoàn thành**, không phải thứ product đang làm

### Bản nháp 1

**Core JTBD bản nháp:**  
> Dùng AI chatbot để tự động tính tiền tiệc cưới và xuất file PDF.

### Gạch bỏ từ solution nếu có

- Các từ solution tôi đang lỡ nhét vào câu: Dùng AI chatbot, tự động, xuất file PDF.

### Bản chốt

**Core JTBD cuối cùng:**  
> Lập kế hoạch sơ bộ và tính toán chi phí chính xác cho một đề xuất sự kiện theo yêu cầu tùy chỉnh của khách hàng trong thời gian ngắn nhất để chốt sale.

---

## Bước 5 — Viết 3 `Job Stories`

Nếu `core JTBD` là job ở mức cốt lõi, thì `job story` giúp bạn thấy
**job này xuất hiện trong hoàn cảnh nào**.

### Format

```text
When [trigger], I want to [motivation], so I can [outcome].
```

### Ví dụ

`When inbox đổ dồn vào buổi tối, tôi muốn có câu trả lời nhất quán ngay lập tức, so I can không mất đơn vì phản hồi chậm.`

### Bảng 3 job stories

| # | Trigger / When | Motivation / I want to | Outcome / so I can | Điều story này cho thấy |
|---|---|---|---|---|
| JS1 | Khách hàng đột ngột nhắn tin yêu cầu báo giá gấp cho tiệc 120 khách với nhiều option phức tạp | Có ngay một kịch bản và bảng giá chính xác lập tức | Gửi phản hồi siêu tốc cho khách để không bị đối thủ cướp mất đơn | Áp lực thời gian của Sales là cực lớn. |
| JS2 | Phải tính toán hàng chục hạng mục có kèm VAT, phí dịch vụ theo mùa và tỷ lệ chiết khấu | Tính toán chuẩn xác 100% không sai lệch | Tránh nguy cơ bị công ty bắt đền tiền hoặc báo giá sai làm mất uy tín với khách | Cần một engine tính toán (Backend) chuẩn xác thay vì AI tự đoán. |
| JS3 | Sếp yêu cầu gửi proposal chuyên nghiệp cho một đối tác doanh nghiệp lớn | Có một định dạng văn bản chuẩn, đẹp mắt, có logo công ty | Trông thật chuyên nghiệp và tạo sự tin tưởng cho khách hàng ngay từ bước báo giá | Việc xuất file PDF template là mandatory để kết thúc workflow. |

### Tự kiểm nhanh

- [x] Mỗi story là một **tình huống thật**, không phải slogan chung chung
- [x] 3 story không trùng hệt nhau
- [x] Sau khi đọc 3 story, tôi hình dung được lúc nào product của mình đáng xuất hiện

---

## Bước 6 — Liệt kê `Current Alternatives`

Qua JTBD lens, đối thủ không chỉ là app cùng ngành.
Đối thủ là **bất kỳ thứ gì user đang "thuê" để làm job**:

- thao tác tay
- file Excel / Google Sheets
- intern / nhân viên
- agency
- ChatGPT / Claude / Gemini
- công cụ chuyên dụng khác
- hoặc thậm chí là **không làm gì cả**

### Bảng alternatives

| Alternative hiện tại | User đang thuê nó để làm gì? | Nó làm tốt gì? | Nó fail ở đâu? | Switching cost hiện tại cao hay thấp? |
|---|---|---|---|---|
| Alt 1: File Excel / Word kết hợp máy tính tay | Tìm giá, tính tổng chi phí, gõ lại thành văn bản | Quen thuộc, miễn phí, tùy biến cao theo ý người dùng | Tốn đến 4 tiếng đồng hồ, cần đến 3 nhân sự, cực dễ bấm sai số | Thấp (nếu app mới chứng minh được việc ra báo giá chỉ trong 30 giây). |
| Alt 2: Dùng ChatGPT/Claude thuần túy | Soạn kịch bản lời dẫn sự kiện, nháp proposal | Viết văn mượt, nhanh, sáng tạo ý tưởng | AI hay bị ảo giác (hallucination) khi làm toán, không nắm được "Kho giá tĩnh" thực tế của công ty | Thấp. |
| Alt 3: Hỏi trực tiếp Admin hoặc bộ phận khác | Xác nhận lại giá thuê thiết bị, MC, giá theo mùa | Giá chắc chắn đúng 100% | Bị động, phải chờ đợi người khác phản hồi, làm chậm quá trình chốt sale | Vừa. |

### Kết luận nhanh

**Nếu project của tôi biến mất hôm nay, user nhiều khả năng sẽ quay về:**  
> Quy trình thủ công tốn 4 tiếng với 3 nhân sự hì hục kiểm tra Excel, gõ Word và tự tính toán bằng máy tính.

---

## Bước 7 — Điền `JTBD Lite Map`

Đây là bản rút gọn của `job map` trong playbook.

### Mục tiêu

Không phải để làm consultant workshop hoàn chỉnh.  
Mục tiêu là nhìn ra:

1. workflow hiện tại của user đi qua những bước nào
2. bước nào đang đau nhất
3. AI có nên chen vào đó không

### 8 bước tham chiếu từ playbook

1. `Define`
2. `Locate`
3. `Prepare`
4. `Confirm`
5. `Execute`
6. `Monitor`
7. `Modify`
8. `Conclude`

> Không nhất thiết bước nào cũng quan trọng như nhau trong dự án của bạn.  
> Nếu ít liên quan, ghi `N/A`, đừng để trống.

### Bảng JTBD Lite Map

| Step | Trong workflow này user đang cố làm gì? | Hôm nay họ đang dùng gì? | Friction / pain hiện tại | Mức đau |
|---|---|---|---|---|
| Define | Nhận yêu cầu và xác định scope sự kiện (số khách, ngày, địa điểm) | Chat/Call với khách (Zalo/SĐT) | Thông tin khách đưa lộn xộn, thiếu ý | Med |
| Locate | Tìm kiếm bảng giá thực đơn, giá MC, giá thiết bị theo mùa | Lục lọi file Excel, hỏi sếp/đồng nghiệp | Dữ liệu phân tán, mất thời gian chờ đợi | High |
| Prepare | N/A | N/A | N/A | N/A |
| Confirm | Xác nhận lại các hạng mục có còn khả dụng vào ngày đó không | Chat nội bộ | Chờ phản hồi chậm | Med |
| Execute | Tính toán cộng/trừ/nhân/chia tổng chi phí, tính VAT, chiết khấu | Máy tính cầm tay, hàm Excel | Cực dễ sai sót toán học, gây hậu quả đền tiền | High |
| Monitor | Theo dõi phản hồi khách hàng để điều chỉnh báo giá | Zalo / Email | Khách đổi ý liên tục bắt tính lại từ đầu | High |
| Modify | Cập nhật lại giá nếu khách đổi menu/thiết bị | Sửa file Excel/Word cũ | Phải tính lại toàn bộ file, rất mệt mỏi | High |
| Conclude | Đóng gói thành file Proposal PDF chuyên nghiệp để gửi chốt | Word/PowerPoint -> Export PDF | Mất công căn chỉnh layout, format | Med |

### Chốt 2 bước đau nhất

**Bước đau nhất #1:** Locate (Định vị bảng giá chính xác theo yêu cầu).  
**Bước đau nhất #2:** Execute (Tính toán hàng loạt chi phí, thuế, chiết khấu).

**Vì sao đây là nơi đáng chú ý nhất:**  
> Đây là 2 bước "ngốn" 80% thời lượng của quá trình làm báo giá (kéo dài tới 4 tiếng) và là nơi sinh ra sai sót gây thiệt hại về tài chính cho công ty nếu nhân viên tính nhầm.

---

## Bước 8 — Chỉ ra `AI Leverage Point`

Sau khi map workflow, mới hỏi:
**AI nên vào đâu, với vai trò gì, và vì sao là ở đó?**

### Nhắc nhanh

- Đừng nhét AI vào chỉ vì "có AI thì nghe hay"
- Nếu pain lớn nhất không nằm ở chỗ AI giải tốt, hãy thành thật ghi ra
- Nếu current alternative đã đủ tốt, project cần xem lại

### Bảng leverage point

| Step | AI nên giúp bằng cách nào? | Vì sao AI hợp ở đây? | Rủi ro chính nếu dùng AI |
|---|---|---|---|
| Execute | AI (RAG + Structured Output) đọc đoạn chat lộn xộn của khách -> ép ra file JSON chuẩn. Dùng Python tính toán thay AI. | LLM cực giỏi trong việc hiểu ý định tự nhiên (NLU). Kết hợp Backend Python giúp triệt tiêu điểm yếu "ảo giác số học" của AI. | AI nhận diện sai yêu cầu (Ví dụ: nhầm "ngân sách 100tr" thành "100 khách"). |
| Conclude | Tự động fill dữ liệu đã tính vào Template PDF đẹp mắt. | Loại bỏ hoàn toàn thao tác căn chỉnh Word/PPT thủ công của con người. | Template PDF bị vỡ font hoặc tràn dòng nếu text quá dài. |

### Kết luận nhanh

**AI leverage point quan trọng nhất của dự án tôi là:**  
> Sử dụng LLM để bóc tách ngôn ngữ phi cấu trúc từ Khung Chat thành dữ liệu cấu trúc (JSON), sau đó để hệ thống (Python) tự động match với Database giá và tính toán.

**Vì sao không phải ở bước khác:**  
> Vì AI thuần túy rất kém trong việc làm toán. Nếu để AI tự tính giá sẽ sinh ra sai số (ảo giác), phá hỏng hoàn toàn độ tin cậy của sản phẩm. Sự kết hợp giữa AI (hiểu ngôn ngữ) và Code (tính toán) là "điểm đòn bẩy" hoàn hảo.

---

## Bước 9 — Viết `Product Hypothesis`

Bây giờ mới đến lúc viết hypothesis.

### Công thức gợi ý

```text
Nếu chúng ta giúp [job executor] làm [job / sub-job] tốt hơn ở bước [x],
bằng cách [AI leverage],
thì họ sẽ chuyển từ [current alternative] sang [hướng giải pháp của nhóm],
vì [giá trị rõ nhất].
```

### Bản hypothesis của tôi

> Nếu chúng ta giúp Nhân viên Sales sự kiện làm khâu bóc tách yêu cầu và tạo báo giá tốt hơn ở bước Execute và Conclude,  
> bằng cách sử dụng Web App tích hợp AI RAG và Engine tính toán,  
> thì họ sẽ chuyển từ việc làm thủ công bằng Excel/Word sang dùng phần mềm này,  
> vì nó giúp rút ngắn thời gian làm báo giá từ 4 tiếng xuống dưới 30 giây và loại bỏ hoàn toàn sai sót.

### Tín hiệu sớm nếu hypothesis này đúng

1. Nhân viên Sales sẽ từ bỏ file Excel cũ và luôn mở Khung Chat của ứng dụng lên ngay khi có khách hàng nhắn tin hỏi giá.
2. File PDF xuất ra được gửi thẳng cho khách mà không cần Sales lấy máy tính ra bấm lại hay kiểm tra lại.

---

## Bước 10 — Liệt kê `Assumptions to Validate`

Job story chưa có research vẫn chỉ là **giả thuyết tốt hơn**, chưa phải sự thật.

### 5 assumption thường đáng kiểm

- Tôi đã chọn đúng `job executor`
- Pain này thật sự đủ đau và xảy ra đủ thường xuyên
- User sẽ đổi khỏi alternative hiện tại nếu có giải pháp tốt hơn
- AI thực sự tạo giá trị ở step tôi chọn
- User đủ tin kết quả AI để đưa vào workflow thật

### Bảng assumptions

| Assumption | Vì sao assumption này rủi ro? | Tôi đang có bằng chứng gì? | Cần validate bằng cách nào tiếp theo? |
|---|---|---|---|
| A1: Admin sẵn sàng nhập và quản lý "Kho dữ liệu tĩnh" trên app | Nếu Admin lười nhập liệu ban đầu, DB rỗng, AI sẽ không có giá để tính toán. | Thường sếp rất bận, lười setup phần mềm mới. | Cho Admin dùng thử tính năng import file Excel giá cũ vào hệ thống 1 lần duy nhất. |
| A2: AI bóc tách chính xác 100% các ý định phức tạp, viết tắt của khách từ đoạn chat | Nếu AI bóc tách sai số lượng khách hoặc nhầm món ăn, báo giá sẽ sai lệch hoàn toàn. | Đang sử dụng Pydantic ép chuẩn JSON. | Test hệ thống với 50 đoạn chat khách hàng "khó tính", viết tắt, lủng củng nhất có thể. |
| A3: User tin tưởng hoàn toàn vào kết quả tính toán của ứng dụng | Nếu user không tin, họ vẫn lấy máy tính ra bấm lại -> App không tiết kiệm được thời gian. | Hệ thống Backend (Python) đảm nhận việc tính toán, không phải LLM. | Tạo cột Preview Real-time (Tab 2) minh bạch công thức tính để user nhìn thấy. |

### Assumption nguy hiểm nhất nếu tôi đang sai

> A2. Nếu AI bóc tách thông tin sai, truyền dữ liệu sai cho engine tính toán, app sẽ tạo ra một báo giá sai. Trong ngành sự kiện, báo giá sai dẫn đến đền bù tiền mặt hoặc mất khách hàng. Điều này sẽ khiến User tẩy chay sản phẩm lập tức.

---

## Bước 11 — Share trong bàn (3')

### Mỗi người / mỗi nhóm chỉ nói 4 thứ

1. **Job executor của bạn là ai**
2. **Core JTBD của bạn là gì**
3. **Step đau nhất đang nằm ở đâu**
4. **AI leverage point + assumption rủi ro nhất là gì**

### Nếu chưa biết hỏi ngược gì, dùng 4 câu này

1. **"Câu JTBD này có đang lỡ nhét solution vào không?"**
2. **"Alternative hiện tại của user là gì, và tại sao họ chưa bỏ nó?"**
3. **"Pain mạnh nhất nằm ở bước nào trong workflow, có chắc AI giải tốt được không?"**
4. **"Assumption nào nếu sai thì cả hypothesis sẽ sập?"**

### Ghi nhanh sau khi nghe bàn phản biện

| Ý phản biện tôi nghe được | Nó chạm vào phần nào? | Tôi sẽ giữ / sửa gì? |
|---|---|---|
| Có chắc Admin chịu khó cập nhật giá lên hệ thống thường xuyên không? | Assumption A1 | Tôi sẽ giữ nguyên giả thuyết, nhưng cần thêm tính năng Auto-sync từ Excel lên DB để giảm tải cho Admin. |
| Nếu khách hàng nhắn bằng giọng nói (Voice message) thì sao? | Cổng đầu vào (Trigger) | Sẽ ghi nhận ý kiến, có thể mở rộng tích hợp Speech-to-Text ở phase 2, tạm thời phase 1 chỉ focus vào Text. |

---

## Bước 12 — Chốt version cuối sau thảo luận

### Sau khi nghe phản biện, tôi thay đổi gì?

- [x] Giữ nguyên `job executor`
- [ ] Sửa `job executor`
- [x] Giữ nguyên `core JTBD`
- [ ] Sửa `core JTBD`
- [x] Giữ nguyên `AI leverage point`
- [ ] Sửa `AI leverage point`
- [x] Giữ nguyên `product hypothesis`
- [ ] Sửa `product hypothesis`

### Vì sao tôi giữ / sửa?

> Tôi giữ nguyên mọi thứ vì các ý phản biện chủ yếu nhắm vào khâu nhập liệu của Admin (A1) và mở rộng tính năng (Voice input), không làm thay đổi bản chất JTBD cốt lõi và workflow báo giá của Nhân viên Sales.

### Version cuối cùng tôi nộp

**Job executor:**  
> Nhân viên Sales sự kiện / SME Agency.

**Core JTBD:**  
> Lập kế hoạch sơ bộ và tính toán chi phí chính xác cho một đề xuất sự kiện theo yêu cầu tùy chỉnh trong thời gian ngắn nhất để chốt sale.

**2 bước đau nhất trong workflow:**  
> Locate (Tìm giá rải rác) và Execute (Tính toán thủ công dễ sai sót).

**AI leverage point chính:**  
> Dùng AI (LLM) bóc tách ngôn ngữ tự nhiên thành JSON, giao lại cho Backend (Python) đối chiếu Database để tính toán và xuất PDF tự động.

**Product hypothesis:**  
> Giải pháp kết hợp AI bóc tách + Code tính toán sẽ giúp Sales rút ngắn thời gian làm báo giá từ 4 tiếng xuống 30 giây, giảm nhân sự từ 3 xuống 1, loại bỏ 100% lỗi toán học.

**Assumption cần validate đầu tiên:**  
> Khả năng AI bóc tách chính xác (không bị ảo giác) các yêu cầu lộn xộn của khách hàng thành file JSON chuẩn đầu vào.

---

## Checklist trước khi nộp

- [x] Tôi đã khoanh đúng 1 lát cắt cụ thể của dự án.
- [x] Tôi đã phân biệt được `job executor` với buyer / influencer.
- [x] `Core JTBD` của tôi không nhét solution vào câu.
- [x] Tôi đã viết đủ 3 `job stories`.
- [x] Tôi đã điền `JTBD lite map` và khoanh ra 2 bước đau nhất.
- [x] Tôi đã chỉ ra `AI leverage point` thay vì nhảy thẳng vào feature list.
- [x] Tôi đã ghi rõ `assumptions to validate`.
- [x] Tôi đã sửa version cuối sau khi share trong bàn.

---

## Nếu còn thời gian / làm về nhà

- Phỏng vấn nhanh 1 người dùng thật để kiểm xem `job story` nào là sát nhất.
- So sánh `current alternatives` với project của nhóm theo 3 tiêu chí: nhanh hơn, rẻ hơn, tin hơn.
- Tự hỏi lại một câu khó: **nếu không dùng AI, project này còn tạo giá trị không?**
- Nếu câu trả lời là "không", hãy xem lại liệu nhóm đang giải **job thật** hay chỉ đang tìm chỗ để nhét AI.

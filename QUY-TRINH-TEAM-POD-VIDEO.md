# QUY TRÌNH TEAM POD VIDEO AI (BẢN TỔNG HỢP, CẬP NHẬT 18/11/2026)

Bản này gộp 3 tài liệu cũ (tài liệu bàn giao 24/10, hướng dẫn video áo POD, skill product-video-from-reference) và cập nhật luật mới của user ngày 26/10. **Đây là tài liệu chính.** Khi có mâu thuẫn với tài liệu cũ thì theo bản này. Yêu cầu mới của user trong chat luôn ưu tiên hơn tài liệu.

---

## 0. Thay đổi so với bản cũ (26/10, bổ sung 30/10 ở mục 6–17)
1. **Bỏ bước tự tìm người mẫu trên Pinterest.** User gửi sẵn ảnh mockup (người mẫu mặc áo, hoặc ảnh sản phẩm). Bot chỉ việc tạo video đúng brief, đúng design.
2. **Áo:** tối thiểu **4 cảnh**, xen kẽ mặt trước và mặt sau (trừ áo in 1 mặt).
3. **Giấy gói quà:** tối thiểu **6 cảnh**, bắt buộc có 3 cảnh: trải phẳng giấy và vuốt nhẹ, gấp giấy vào hộp carton, vuốt nhẹ nơ (không siết mạnh).
4. **Giấy gói quà được phép tạo riêng cảnh trải phẳng** cho đúng 100% rồi ghép với phần còn lại (đây là ngoại lệ duy nhất của luật "tạo 1 lần").
5. Bỏ luật cũ "không chỉnh nơ": nay bắt buộc có cảnh vuốt nhẹ nơ, chỉ cấm siết hay thắt nơ.
6. (30/10) **Áo 2 mặt được phép tạo nhiều source rồi ghép**: cắt bỏ 1–2 giây đầu của mỗi source rồi mới ghép, tổng 15s (mục 5.8).
7. (30/10) **Áo 1 mặt ưu tiên tạo 1 lần duy nhất 15s**, không tách source.
8. (30/10) **Áo có chữ nhỏ: không làm cảnh zoom cận/đặc tả design** (hay vỡ chữ, chiếm nhiều thời lượng, cắt đi thì hao hụt). Chỉ dùng trung cảnh/cận vừa thấy trọn áo. **Chỉ được zoom cận khi user gửi kèm ảnh design đã crop rõ nét**, khi đó dùng đúng ảnh crop đó làm tham chiếu cảnh cận (mục 5.5).
9. (30/10) **Cắt ảnh (crop) design hay ảnh tham chiếu thì phải làm nét trước** (upscale lanczos lên ít nhất gấp 2 rồi unsharp), không đưa ảnh crop bị nhòe vào tạo video. Giấy gói bị nhòe/vỡ là phải làm lại từ đầu.
10. (30/10) **Khi tạo video luôn đặt độ phân giải 720p** (mặc định là 480p, dễ nhòe), rồi mới upscale lên 1080×1920.
11. (30/10 tối) **Áo: làm ảnh áo mới tinh trước khi tạo video**: dùng AI ảnh làm lại mockup để áo không cũ, không nhăn, không bạc màu, không đốm trắng, không sần sùi (mục 5.1).
12. (30/10 tối) **Giấy gói có ảnh design user crop zoom sẵn:** chỉ dùng ảnh crop cho các đoạn cận/zoom; cảnh trải phẳng, gấp giấy và cảnh toàn dùng design đầy đủ (mục 7.1).
13. (30/10 tối) **Poster đặt vào khung phải vừa khít khung gỗ** như ảnh mockup đã gắn khung, giữ đúng ở mọi cảnh sau (mục 6).
14. (30/10 tối) **Giữ đúng hướng poster:** poster ngang luôn là chữ nhật ngang, poster dọc luôn là chữ nhật dọc, không bao giờ thành hình vuông (mục 6).
15. (30/10 tối) **Poster được phép tạo nhiều source rồi ghép** khi user cho phép hoặc kịch bản dài (unbox, gắn kính, đặt kệ): cắt 1–2s đầu mỗi source, tổng 15s (mục 6).
16. (30/10 tối) **Kịch bản poster unbox** user thích: nhận hàng từ shipper, mở ống poster, mở cuộn giấy, đặt vào khung, đặt lên kệ (mục 6).
17. (30/10 tối) **Việc làm ảnh mockup tĩnh** (không phải video) có luật riêng ở mục 6.1: poster nhỏ 12x8 inch, hiện trọn 100%, khung dọc 9:16, giao file chất lượng cao.
18. (02/11) **Luật cập nhật tài liệu:** mỗi khi user chỉ ra lỗi sai, Leader bổ sung ngay giải pháp phòng tránh vào chính file này (mục 14).
19. (03/11) **Mọi video gửi user bắt buộc đúng 15s** (áp dụng cả poster, trừ khi user dặn khác).
20. (03/11) **Ảnh ngang ghép nhiều khung trong 1 ảnh** (ảnh lớn + các ảnh nhỏ): cắt riêng từng khung và làm nét trước khi tạo video (upscale lanczos x2 + unsharp).
21. (03/11) **Giấy gói: khóa kích thước tờ giấy ở cảnh trải phẳng là 50 x 50 cm** (tờ vuông).
22. (04/11) **Bỏ chấm điểm trước khi gửi:** bot làm kỹ theo checklist rồi gửi ngay file video vào nhóm, không tự chấm %, không giữ lại vì điểm. Tên file bỏ phần `%dat` (mục 2).
23. (04/11) **Chỉ gửi file đính kèm:** không gửi preview video trong chat, không gửi đường dẫn chữ hay tên file chữ. Phải đính kèm file `.mp4` (mục 2).
24. (04/11) **Định dạng gửi đúng:** bubble file tải được (icon camera + tên file + dung lượng + nút tải), **không** gửi bản xem trước/preview phát được trong chat (mục 2).
25. (04/11) **Giấy gói chỉ in 1 mặt:** mặt in có design, mặt còn lại trắng trơn — không bao giờ lộ mặt trắng trong video (mục 7).
26. (06/11) **Mọi thể loại video: mỗi cảnh phải có nhiều hành động đa dạng, tốc độ bình thường** để output không bị slow-motion. Đặc biệt với áo: mỗi shot nối 2–3 động tác (bước + chỉnh tay áo + vuốt thân / xoay nhẹ + kéo gấu + nhìn camera), máy cũng chuyển động. Cấm cảnh chỉ đứng/đi chậm một động tác trong cả shot (mục 3, 5.4).
30. (13/11) **Áo 2 mặt có logo ngực nhỏ: sai design mặt trước** (hoodie Huckleberry Creator 2 bị làm lại). Cách tránh: cắt riêng khung cận logo ngực, làm nét, đưa làm ảnh tham chiếu riêng cho mặt trước; prompt khóa "front chest logo exactly as <IMAGE_n>, small, left chest, no redraw, never use the back graphic on the front". Ghép source thì chỉ chọn source có logo trước đúng.
31. (13/11) **Ảnh mockup có watermark (ngôi sao lấp lánh góc dưới phải): xoá trước khi dùng làm tham chiếu** (ffmpeg delogo hoặc inpaint), để video không dính watermark. Kịch bản poster mới user thích: bưu tá trao ống cuộn → mở ống trải poster → lồng khung → treo tường → cảnh cuối camera di chuyển đổi vài góc nhìn poster.
32. (13/11) **Poster bị dính chữ, số lạ ở góc trên bên phải trong các cảnh cuối** (Diggs của Creator 2 và 3 bị làm lại). Cách tránh: khoá prompt "poster exactly as reference, no extra text or numbers, top-right corner clean" ở mọi cảnh, nhất là cảnh camera đổi góc. Unbox poster bắt buộc có cảnh tay rút cuộn poster ra từ trong ống đựng.
29. (13/11) **Creator không tự gửi cho user:** làm xong chỉ báo ngắn đường dẫn file .mp4 cho Leader; Leader gửi file cho user (tiết kiệm hạn mức).
28. (13/11) **Bỏ bước tự kiểm tra:** user dặn làm, ghép xong là gửi ngay, không cần tự soát checklist mục 8 (ảnh lưới, freezedetect...). Vẫn viết prompt đúng luật.
27. (06/11) **Hoodie không dây:** mockup user gửi không có dây (drawstring). Mọi video hoodie phải không có dây mũ/dây rút; không tự thêm dây. Prompt khóa: "no drawstrings, no hoodie cords, plain hood opening" (mục 5).
34. (18/11) **Ghép source rồi Leader gửi user:** Creator làm xong (kể cả ghép các source nếu có) chỉ báo đường dẫn .mp4 cho Leader; **Leader gửi file cho user**. Creator không tự gửi user.
35. (18/11) **Không ai tự xem lại video để kiểm tra** (cả Creator lẫn Leader): user tự kiểm. **Không được tự ý làm lại** khi user chưa yêu cầu.
36. (18/11) **Áo: nhân vật phải di chuyển và tương tác với đồ vật, người xung quanh nhiều hơn.** Prompt phải **ghi rõ từng cảnh khoảng 4–5 hành động nhỏ tự nhiên, cụ thể** (ví dụ: bước tới quầy, cầm muôi khuấy nồi, nghiêng đầu ngửi, quay sang cười với bà, đặt muôi xuống), cấm ghi chung chung kiểu "đang nấu ăn", "đi lại tự nhiên" (mục 3, 5.4).

---

## 1. Team gồm ai, làm gì

| Thành viên | Vai trò | Mô tả để dán vào hồ sơ bot khi tạo lại |
|---|---|---|
| Leader | Trưởng nhóm | Trưởng nhóm team POD video AI. Nhận yêu cầu của user, giao việc (mỗi video đúng 1 bot), ghi lại mọi feedback và luật của user vào tài liệu chung, theo dõi điểm mạnh và điểm yếu của từng bot. Không tự làm video. Không nhắn khi không cần thiết. |
| Creator 1–5 | Làm video | Tạo video AI ngành POD (áo thun, hoodie, sweat, poster, giấy gói quà) dài 10–15s từ ảnh mockup và design user gửi, theo tài liệu của team. |

**Sản phẩm:** áo thun, áo sweat (nỉ tay dài, không mũ), áo hoodie (in mặt trước, mặt sau hoặc cả 2 mặt), poster có khung, giấy gói quà.

---

## 2. Cách làm việc trong nhóm

**Đầu vào user gửi**
- Áo: ảnh mockup người mẫu mặc áo (mặt trước, mặt sau nếu in 2 mặt), có thể kèm file design và ảnh cận chữ nhỏ.
- Giấy gói quà: file design giấy, có thể kèm ảnh hộp quà đã gói.
- Poster: ảnh poster hoặc mockup khung tranh.
- Có thể kèm brief: vibe, bối cảnh, hành động, thời lượng, số cảnh.
- Thiếu thông tin thì tự chọn hợp lý theo design, không hỏi lại. Chỉ hỏi khi không xác định được loại áo hoặc mặt in.

**Giao việc**
- Chỉ Leader giao việc, mỗi video đúng 1 bot, không giao trùng.
- Bot được giao bắt đầu ngay, làm song song, không chờ bot khác, không hỏi lại.

**Gửi video**
- Làm kỹ theo checklist (mục 8), xong **gửi ngay file `.mp4` đính kèm vào nhóm** đúng dạng bubble file tải được: icon camera/file + tên file + dung lượng + nút tải xuống. **Cấm gửi preview / bản xem trước** phát được ngay trong chat. Không gửi đường dẫn chữ, không gửi tên file chữ, không chỉ link.
- **Không tự chấm điểm / không tự giữ lại vì điểm.** Soát lỗi để làm đúng, rồi gửi luôn.
- Tên file: `tenbot-tenmau-ma4kytu.mp4`, ví dụ `creator2-footballFA-f7k3.mp4`. **Không ghi % điểm vào tên file.** Mã 4 ký tự tự đặt, không trùng.

**Số lần làm**
- Mỗi mẫu làm kỹ 1 bản rồi gửi ngay.
- User yêu cầu làm lại thì làm lại (có thể hơn 1 lần). **(18/11) Không có yêu cầu của user thì không được tự ý làm lại.**
- **(18/11) Không tự xem lại video để kiểm tra** (Creator và Leader đều vậy), user tự kiểm. Làm xong, ghép source xong thì Creator báo đường dẫn .mp4 cho Leader, Leader gửi file cho user.

**Thời gian chuẩn:** khoảng 5 phút mỗi mẫu (giấy gói có tách cảnh trải phẳng thì tối đa khoảng 8 phút).

**Lưu file:** giữ ảnh tham chiếu (mockup user gửi, ảnh giấy phẳng, ảnh hộp quà) trong thư mục làm việc tới khi user duyệt. Sau khi giao chỉ giữ bản cuối và ảnh tham chiếu, xóa khung soát lỗi và bản nháp. Xóa đích danh từng file, không dùng `rm *.png`.

**Khi user yêu cầu chỉnh sửa**
- "Thêm biến thể / tương tự": giữ brief gần nhất, đổi hành động, góc quay, bối cảnh phụ. Ưu tiên ý đời thường, ít lỗi.
- "Brief mới": giữ luật chung, đổi sản phẩm và bối cảnh.
- "Sửa video/prompt X": chỉ làm lại đúng phần được yêu cầu.
- "Dùng lại prompt": giữ nguyên văn, chỉ đổi chi tiết phải khớp ảnh mới.

---

## 3. Tiêu chí chung cho MỌI video (bắt buộc)

- **Không xóa phông**, không làm mờ hậu cảnh (no blur, no bokeh), nền rõ nét như camera điện thoại, deep depth of field.
- **Không ám màu**: không ám vàng, không ám cam, không tone ấm giả, cân bằng trắng trung tính.
- **Không chỉnh màu**, không filter, không hiệu ứng điện ảnh, không bão hòa.
- **Chân thực như quay bằng điện thoại cầm tay**, ánh sáng ban ngày tự nhiên, rung tay nhẹ.
- Không slow motion, không chữ trên màn hình, không phụ đề, không lời thoại, không nhạc (trừ khi user yêu cầu).
- **(18/11) Áo: mỗi cảnh ghi rõ 4–5 hành động nhỏ tự nhiên, cụ thể, nhân vật di chuyển và tương tác với đồ vật, người xung quanh; cấm ghi chung chung.** Các thể loại khác giữ luật 06/11 bên dưới.
- **(06/11) Mỗi cảnh phải dày hành động:** viết 2–3 động tác nối nhau trong cùng một shot, tốc độ bình thường (không chậm, không “cinematic slow”). Áp dụng mọi thể loại (áo, poster, giấy gói). Đặc biệt áo dễ bị slow-motion nếu chỉ đi chậm / đứng vuốt một lần — phải đa dạng hành động + máy luôn chuyển động.
- Khung dọc 9:16, xuất 1080×1920. **Thời lượng bắt buộc 15s cho mọi video gửi user (03/11)**, trừ khi user dặn khác.
- Không có khung hình đứng yên, chuyển động liên tục ngay từ khung đầu.
- Mọi chỗ chuyển cảnh là hard cut, không hòa hình, không chồng hình.

**Câu khóa dán vào mọi prompt (tiếng Anh):**
```
Vertical 9:16, realistic handheld phone video, real natural daylight, neutral white balance, true natural colors exactly as a phone camera records them, no color grading, no saturation boost, no filter, no warm/yellow/orange tint, no cinematic look, no background blur, no bokeh, deep depth of field, sharp background, no slow motion, normal real-time speed only, no on-screen text, no dialogue. Continuous motion from the very first frame, the person and camera are always moving, no still frames, no freeze frame, no static image hold. Every shot packs 2–3 distinct actions at normal pace so the clip never looks slow-motion.
```
Mỗi chỗ chuyển cảnh ghi: `Instant hard cut on a single frame, no dissolve, no crossfade, no fade, no overlap, no morphing between shots.`

---

## 4. Luật kỹ thuật khi tạo video

- **Tạo 1 lần duy nhất cho cả video**, đưa đủ ảnh tham chiếu và prompt, các hard cut ghi ngay trong prompt. Không tạo từng đoạn rồi ghép, không dán hình in từng khung.
  - **Ngoại lệ:** cảnh trải phẳng giấy gói quà được tạo riêng rồi ghép (mục 7.3); áo 2 mặt tạo nhiều source rồi ghép (mục 5.8).
- Ảnh chỉ đưa vào `reference_image_paths`, gọi trong prompt là `<IMAGE_0>`, `<IMAGE_1>`... theo đúng thứ tự. **Không dùng ảnh làm khung đầu hay khung cuối, không ghim keyframe** (`image_path`, `last_frame_path`), vì gây đứng hình 0,5–1s.
- Nếu user dùng mã ảnh (ví dụ `@496bc922...`) trong prompt thì thay bằng `<IMAGE_n>` tương ứng, không đổi gì khác.
- Báo lỗi "Aborted" thì gọi lại y nguyên. Bị chặn bởi bộ lọc an toàn thì rút gọn prompt 1 lần rồi thử lại.
- Không ghi tên người thật hoặc người nổi tiếng. Tả bằng chi tiết nhìn thấy, hoặc ghi "exactly as in <IMAGE_n>".
- Chữ in phải chép đúng nguyên văn, giữ cả lỗi chính tả của design (ví dụ "dinasour"). Chữ dễ sai thì đánh vần (B-E-A-S-T-I-E).
- Khóa số lượng chi tiết, ví dụ "exactly 3 signatures only", "exactly two hands", "exactly one bow".
- **Độ phân giải tạo video: luôn chọn 720p**, không để mặc định 480p (nguyên nhân chính làm giấy gói nhòe 30/10).
- **Upscale:** `ffmpeg -i in.mp4 -vf scale=1080:1920:flags=lanczos -c:v libx264 -crf 16 out.mp4`

**Cách viết prompt:** mọi cảnh viết như quay phim chuyên nghiệp, ghi rõ:
- Cỡ cảnh: toàn, trung, cận, đặc tả.
- Góc máy: ngang tầm mắt, từ trên xuống, góc 3/4, góc thấp.
- Chuyển động máy: lia trái sang phải, đẩy vào, lùi ra theo vòng cung, tilt.
- Từng động tác tay cụ thể: tay nào cầm gì, gấp cạnh nào vào đâu.
- Không viết chung chung kiểu "fold the paper over the box" hay "camera pans around it".
- Mỗi cảnh có nhiều hành động nối nhau để video không bị chậm.

**Cấu trúc prompt nên dùng:** Mục tiêu video → Vai trò từng ảnh tham chiếu → Khóa nhân vật/sản phẩm → Timeline từng cảnh có mốc giây → Câu khóa nhất quán ở cuối.

---

## 5. Quy trình ÁO (thun, hoodie, sweat)

### 5.1. Đầu vào
- Dùng ảnh mockup user gửi làm tham chiếu người mẫu và áo. **Không tự tìm người mẫu, không tự tạo người mẫu khác.**
- Áo 2 mặt: cần ảnh mặt trước và mặt sau. Nếu user chỉ gửi mockup mặt trước kèm design mặt sau, tạo thêm ảnh mặt sau bằng AI ảnh với prompt: "Góc phía sau lưng nhân vật, trên áo có họa tiết như ảnh. Ảnh chụp bằng iPhone, ánh sáng tự nhiên, cân bằng trắng trung tính, không xóa phông, không chỉnh màu, không ám vàng/cam."
- File design 2 mặt gộp 1 ảnh: cắt mặt trước `crop=iw/2:ih:0:0`, mặt sau `crop=iw/2:ih:iw/2:0`. Thêm ảnh cắt riêng phần in làm tham chiếu thì cảnh cận nét hơn.
- **(30/10) Bắt buộc làm ảnh áo mới tinh trước khi tạo video:** dùng AI ảnh chỉnh lại mockup user gửi để áo mới tinh, vải phẳng, không nhăn, không bạc màu, không đốm trắng, không sần sùi, giữ nguyên người mẫu, bối cảnh và design. Dùng ảnh đã làm mới này làm tham chiếu.
- **(03/11) Ảnh ngang ghép nhiều khung** (áp dụng mọi sản phẩm): cắt riêng từng khung rồi làm nét `ffmpeg -i crop.png -vf scale=iw*2:ih*2:flags=lanczos,unsharp=5:5:1.0 sharp.png` trước khi đưa vào tạo video.
- Kiểm ảnh đầu vào: nếu ảnh tự tạo bị ám vàng/cam, mờ nền hoặc trông như AI thì làm lại trước khi tạo video.

### 5.2. Số cảnh và mặt áo
- **Tối thiểu 4 cảnh**, nối bằng hard cut. Việc xoay người xảy ra ở điểm cắt, không quay cảnh xoay liên tục.
- **In 2 mặt:** xen kẽ trước và sau, ví dụ sau, trước, cận sau, trước (hoặc theo cảnh mở đầu user yêu cầu). Không hoán đổi mặt trước và mặt sau.
- **In 1 mặt trước:** mọi cảnh hướng mặt trước hoặc chếch nhẹ. Ghi "only front or slight front angles, never show the back".
- **In 1 mặt sau:** mọi cảnh quay lưng hoặc sau chếch nhẹ. Ghi "the front of the shirt is plain, no print".
- **Hoodie:** "hood down behind the neck, never on the head". **(06/11) Không có dây rút / drawstring** — mockup user không có dây thì video cũng không được có dây; không tự thêm. Prompt: "no drawstrings, no hoodie cords, plain hood opening". Không để dây (nếu lỡ sinh) che graphic.
- **Sweat:** "crewneck fleece sweatshirt, long sleeves, no hood, not a knitted sweater".
- **Sơ vin** (nếu yêu cầu): giữ sơ vin suốt video.

### 5.3. Khóa sản phẩm
- Giữ đúng graphic, chữ, màu, bố cục, vị trí in từng mặt. Không vẽ lại, không lật gương, không thêm hình in, không đổi kích thước.
- Áo luôn mới: vải phẳng, không nhăn, màu không bạc, hình in sắc nét.
- Tay, tóc, dây đeo, đồ vật không che graphic. Áo không bị vén.
- Giữ đúng mặt, tóc, màu da, vóc dáng người mẫu như mockup.

### 5.4. Hành động và nhiều người
- Hành động đơn giản, **tốc độ bình thường (không slow-motion)**: bước đi, lướt tay lan can, tựa tường, vuốt thân áo, chỉnh tay áo, kéo gấu áo, xoay nhẹ người, nhìn/gật nhẹ vào camera.
- **(06/11) Mỗi cảnh áo phải có 2–3 hành động nối nhau** (ví dụ: bước tới → chỉnh tay áo → vuốt thân; hoặc xoay nửa người → kéo gấu → nhìn camera). Máy cũng lia/đẩy/lùi trong cùng shot. Không để cả shot chỉ một động tác chậm — đó là nguyên nhân chính video áo bị slow-motion.
- Biểu cảm tiết chế. Vibe nghiêm trang (tưởng niệm, nhà thờ) thì không cười.
- Tránh: thao tác phức tạp, giơ tay cao che ngực áo, vật to che áo. Không tự thêm tuyết, quà, đạo cụ. Có tuyết thì áo vẫn khô.
- Có bạn đi cùng: nhân vật chính đứng giữa, người phụ lệch sang bên, không mặc áo giống, không che áo.
- Cặp đôi 2 áo khác nhau: khóa riêng từng người với đúng áo, không đổi áo, không làm 2 design giống nhau.

### 5.5. Áo có chữ nhỏ (cách của Creator 4, user chấm 10 điểm)
> **30/10: mặc định KHÔNG làm cảnh đặc tả/zoom cận design.** Hoodie 30/10 bị loại vì đoạn zoom mặt trước vỡ chữ và quá dài. **Chỉ áp dụng cách dưới đây khi user gửi kèm ảnh design đã crop rõ nét.** Không tự crop để làm cảnh zoom.
- Đưa 4 ảnh vào 1 lần tạo: mockup mặt trước, mockup mặt sau, ảnh cận chữ nhỏ rõ nét (dùng nguyên ảnh user gửi, không crop riêng khối chữ), ảnh design.
- Bố cục 4 cảnh: (1) mặt trước đi tới, (2) mặt sau máy đẩy cận, (3) đặc tả chữ 4s, (4) trung cảnh góc 3/4 có lia ngang.
- Prompt cảnh đặc tả: "Extreme close-up, camera square to his chest, the text block filling almost the whole frame exactly like <IMAGE_2>. He stands almost still, only breathing gently, shirt flat with no wrinkles over the text. The camera tilts down very slowly and steadily from the first line to the last line over 4 seconds. Every word sharp and legible, no motion blur, text exactly as <IMAGE_1>, no redraw."
- Lỗi cần tránh: hình trong khối chữ bị nhân đôi, chồng hình ở chỗ chuyển cảnh.

### 5.6. Các kiểu mở đầu đặc biệt (khi user yêu cầu)
- **Nhận hàng, mở túi:** áo ba lỗ trơn mở cửa nhận túi, lấy áo ra, giơ áo trước camera (2 tay cầm vai áo; nếu brief yêu cầu khoe mặt sau thì xoay áo khoe lưng in rồi mới hard cut sang cảnh đã mặc). Trong cảnh unbox cũng phải nhiều hành động nối nhau, tốc độ bình thường.
- **Áo trải phẳng:** áo trải trên giường/sàn, không người, máy lia ngang chậm qua từng mặt áo, rồi hard cut sang người mặc.
- **POV chỉ tay:** nhìn xuống mặt áo, 1 bàn tay duy nhất, ngón trỏ chỉ sát bên từng dòng chữ, không che chữ.
- **Bắt chước động tác ăn mừng:** chỉ tả động tác, tay thấp bên hông, không che ngực áo.

### 5.7. Prompt mẫu áo 2 mặt (thay phần trong [ ])
```
[Câu khóa chung mục 3], 15 seconds.

REFERENCE LOCK: <IMAGE_0> is the model wearing the [t-shirt / hoodie / crewneck sweatshirt], FRONT view. <IMAGE_1> is the same model and shirt, BACK view. Keep the face, hair, skin tone, body shape and outfit exactly as in the images. FRONT print: exactly as <IMAGE_0>, [vị trí, kích thước]. BACK print: exactly as <IMAGE_1>, [vị trí, kích thước]. Text exactly "[CHỮ NGUYÊN VĂN]". Never redraw, never mirror, never add prints, never swap front and back. The shirt is brand new, flat, unwrinkled, deep unfaded color, crisp print. Hands, hair and straps never cover the graphic. [Hoodie: hood down behind the neck.]

SHOT 1 (0–4s, back): Medium shot from behind at eye level, the camera follows him walking slowly through [bối cảnh], arms relaxed, the back print fully visible.
Instant hard cut on a single frame, no dissolve, no crossfade, no fade.
SHOT 2 (4–8s, front): Medium shot, slight front 3/4 angle, he stops, pulls the hem down with both hands, then smooths both sides of the shirt; the camera pushes in slowly.
Instant hard cut on a single frame, no dissolve, no crossfade, no fade.
SHOT 3 (8–11s, back close-up): Close-up square to his back, arms down at his sides, the whole back graphic in frame, undistorted; the camera tilts down slowly.
Instant hard cut on a single frame, no dissolve, no crossfade, no fade.
SHOT 4 (11–15s, front): Medium shot at eye level, he adjusts one sleeve, looks into the camera with a slight nod, then walks toward the camera; the camera trucks slightly left.
```
Áo 1 mặt trước: cả 4 cảnh hướng trước, thêm "only front or slight front angles, never show the back". Áo 1 mặt sau: cả 4 cảnh hướng sau, thêm "the front is plain".

### 5.8. Áo 2 mặt tạo nhiều source rồi ghép (luật user 30/10)
- Nếu tạo nhiều source rồi ghép, **cắt bỏ 1–2 giây đầu của mỗi source** rồi mới ghép, để nhân vật không bị khựng và bối cảnh không lặp lại hành động.
- Tổng sau khi ghép đúng 15s. Ghép bằng hard cut, đưa các đoạn về cùng 1080×1920 và cùng fps.
- **Áo 1 mặt:** ưu tiên tạo 1 lần duy nhất 15s, không tách source rồi ghép.
- Ví dụ cắt 1,5s đầu: `ffmpeg -ss 1.5 -i src1.mp4 -c:v libx264 -crf 16 -an s1.mp4`, rồi nối như lệnh ghép ở mục 7.3.

---

## 6. Quy trình POSTER (khung tranh)
- Thời lượng bắt buộc 15s (03/11), trừ khi user dặn khác. Tạo 1 lần duy nhất, tối thiểu 3 cảnh hard cut.
- Mẫu đã làm tốt:
  - **Poster 10s (Creator 1, 92%):** POV 2 tay nhấc tranh, nghiêng qua lại để mặt kính phản chiếu ánh sáng. Đặc tả chữ nhỏ, lia chậm từng dòng 3–4s. Treo tranh lên tường, máy lùi chậm thấy toàn bộ tranh.
  - **Poster 6s:** POV cầm tờ poster phẳng (không cuộn), nghiêng qua lại, đặt vừa khít vào khung gỗ, rồi đặt tấm kính vừa khít lên trên.
  - **Poster 10s tặng quà:** POV nhấc tranh nghiêng chậm, rồi trao cho người nhận.
  - **Poster gắn kính (30/10, user duyệt):** POV từ trên xuống bàn, 2 tay đặt tờ poster phẳng vừa khít khung gỗ trống, đặt tấm kính lên trên, rồi cầm khung đặt lên kệ, máy di chuyển nhiều góc (lia ngang, góc 3/4, đẩy vào).
  - **Poster unbox 15s (30/10, user duyệt):** nhận hàng từ shipper, mở ống poster, mở cuộn giấy ra (chỉ ở cảnh này poster được cuộn), đặt phẳng vào khung gỗ, đặt khung lên kệ. Creator 5 đạt 86–88%.
  - **Treo tường:** user gửi ảnh tường trống + ảnh tranh đã treo; POV nhấc khung nghiêng cho kính bắt sáng, treo đúng vị trí, máy lùi thấy trọn tranh và đồ decor.
- Đầu vào hay gặp: ảnh khung trống trên bàn/tường + ảnh cùng bối cảnh đã có poster trong khung. Dùng cả 2 làm tham chiếu, đồ vật trên bàn giữ đúng vị trí.
- Luật riêng: kích thước tranh không đổi suốt video; khóa đúng chữ và hình, chép nguyên văn chữ; giữ nguyên đồ vật trên bàn như ảnh user gửi; không ghi tên người thật (tả "exactly as <IMAGE_n>").
- **(30/10) Poster vừa khít khung:** khi đặt tờ poster vào, mép poster khớp đúng lòng khung gỗ như ảnh mockup, không lệch, không thừa thiếu mép, và giữ đúng như vậy ở mọi cảnh sau. Bản Creator 5 bị bắt làm lại vì lỗi này.
- **(30/10) Giữ đúng tỉ lệ và hướng:** poster ngang luôn là hình chữ nhật ngang, poster dọc luôn là hình chữ nhật dọc, đúng tỉ lệ khung như mockup, không bao giờ biến thành hình vuông. Ghi vào prompt: "the framed poster is always a landscape rectangle exactly as <IMAGE_n>, same aspect ratio in every shot, never square".
- **(30/10) Ghép nhiều source:** cho phép với poster khi user đồng ý hoặc kịch bản dài; cắt bỏ 1–2s đầu mỗi source, hard cut, cùng 1080×1920 và fps, tổng đúng 15s, màu các đoạn khớp nhau.

### 6.1. Làm ảnh mockup poster tĩnh (khi user yêu cầu ảnh, không phải video)
- Poster mặc định **nhỏ, cầm vừa tay, 12x8 inch** (user chê bản 40x27 inch quá to), trừ khi user dặn kích thước khác.
- Poster phải **hiện trọn vẹn 100%** trong khung: dán nguyên ảnh poster đúng tỉ lệ gốc, không crop, không cắt mép, khung và đồ decor không che chữ, chữ ký hay hình.
- Ảnh xuất **khung dọc 9:16 (1080×1920)** dù poster nằm ngang.
- Giao **dạng file chất lượng cao** (gói zip) để user tải, không chỉ ảnh xem trước.
- Ảnh như chụp điện thoại, cân bằng trắng trung tính, không ám vàng, không xóa phông. Mỗi ảnh đổi decor/bối cảnh phụ một chút.

---

## 7. Quy trình GIẤY GÓI QUÀ (bản mới 26/10)

### 7.1. Ba ảnh tham chiếu (bắt buộc)
> **30/10:** nếu crop design hoặc ảnh hộp, làm nét trước khi dùng: `ffmpeg -i crop.png -vf scale=iw*2:ih*2:flags=lanczos,unsharp=5:5:1.0 sharp.png`. Soát ảnh B và C phải nét, không nhòe, trước khi tạo video.
1. **Ảnh A, design gốc:** file design user gửi, giữ nguyên.
   - **(30/10) Nếu user gửi thêm ảnh design đã crop zoom:** ảnh crop chỉ dùng làm tham chiếu cho các đoạn cận/zoom (ví dụ cận nơ, cận mặt hộp) cho rõ nét. Ảnh B và cảnh trải phẳng, gấp giấy, cảnh toàn luôn dùng design đầy đủ, nếu không họa tiết sẽ bị to lên.
2. **Ảnh B, tờ giấy trải phẳng:** dán nguyên pixel design bằng script `flat-sheet.py` (mục 9), không cho AI vẽ lại. Có thể thêm phối cảnh nhẹ, bóng mờ ở mép, chỉnh sáng khớp mặt bàn. Màu nền bàn: gỗ `150,108,72`, sáng `236,234,230`.
   - **(03/11) Tờ giấy trải phẳng là hình vuông 50 x 50 cm**, ảnh B dựng đúng tỉ lệ vuông. Prompt ghi: "the flat wrapping paper sheet is a square exactly 50 x 50 cm, about the width of two forearms, same size in every flat shot".
3. **Ảnh C, hộp quà đã gói xong, nơ thắt sẵn:** dùng ảnh user gửi nếu có. Không có thì tạo bằng AI ảnh, dùng ảnh B làm tham chiếu, soát từng nhân vật đúng kích thước như trên giấy.

Không đưa ảnh bối cảnh có giấy gói khác, AI sẽ chép giấy đó vào video. Bối cảnh chỉ tả bằng chữ.

**Luật 1 mặt (04/11):** Giấy gói quà **chỉ có một mặt in design**; mặt còn lại là **trắng trơn**. Trong mọi cảnh phải giữ mặt in hướng ra ngoài, **không bao giờ lộ mặt trắng** (mép cuộn, chỗ gấp hở, tờ bị lật). Prompt khóa: "NEVER show the white back side of the paper, printed side always facing out".

### 7.2. Tối thiểu 6 cảnh, bắt buộc có 3 cảnh sau
| Cảnh bắt buộc | Nội dung | Ảnh dùng |
|---|---|---|
| **Trải phẳng và vuốt nhẹ** | Tờ giấy trải phẳng trên bàn, 2 tay vuốt nhẹ ở mép và góc giấy, không quét qua mặt nhân vật. Máy lia ngang chậm, khoảng cách trung, thấy 2–3 cụm họa tiết. | B |
| **Gấp giấy vào hộp carton** | Hộp carton trơn đặt sẵn trên mặt giấy in, 2 tay cầm mép trái và phải gấp lên giữa nắp hộp, 1 tay miết mối nối. Tay chỉ cầm mép giấy. | B |
| **Vuốt nhẹ nơ** | Cận nơ đã thắt sẵn, 1 tay vuốt nhẹ một vòng nơ cho phồng đều. **Không siết, không kéo mạnh, không thắt nơ.** | C |

Các cảnh còn lại (tối thiểu 3) dùng ảnh C: lia góc 3/4 quanh hộp, 2 tay nhấc hộp xoay một phần tư vòng, lia ngang qua mặt trước hộp, trao hộp, cảnh kết đặt hộp cạnh gốc cây thông Giáng sinh (mặc định, trừ khi user dặn khác).

**Thời gian gợi ý 15s:** trải phẳng 0–2,5s, gấp giấy 2,5–5s, vuốt nơ 5–7,5s, 3 cảnh hộp từ 7,5–15s (mỗi cảnh khoảng 2,5s).

Không có cảnh cuộn giấy riêng. Không bao giờ quay cảnh thắt nơ.

### 7.3. Tách riêng cảnh trải phẳng rồi ghép (khuyến nghị)
Cảnh trải phẳng hay sai nhất (sai màu, vẽ lại họa tiết, đầu người lơ lửng, lộ mặt trắng), nên được tách riêng:
1. **Tạo cảnh trải phẳng riêng** (khoảng 3s, 9:16), chỉ đưa ảnh A và ảnh B, prompt chỉ có 1 cảnh trải phẳng và vuốt mép (mẫu ở 7.5). Soát kỹ từng khung với design: đúng màu nền, đúng kích thước họa tiết, không nhân vật lạ. Chưa đúng 100% thì tạo lại cảnh này (tối đa 3 lần, đây là phần rẻ).
2. **Tạo phần còn lại 1 lần duy nhất** (khoảng 12s, từ cảnh gấp giấy tới cảnh kết), đưa đủ ảnh A, B, C. Các hard cut ghi trong prompt.
3. **Ghép bằng hard cut**, đưa 2 đoạn về cùng kích thước và fps rồi nối:
```
ffmpeg -i flat.mp4 -i rest.mp4 -filter_complex "[0:v]scale=1080:1920:flags=lanczos,fps=24,setsar=1[a];[1:v]scale=1080:1920:flags=lanczos,fps=24,setsar=1[b];[a][b]concat=n=2:v=1:a=0[v]" -map "[v]" -c:v libx264 -crf 16 -pix_fmt yuv420p final.mp4
```
4. Cắt bớt đầu/cuối mỗi đoạn nếu có khung đứng hình (kiểm bằng `freezedetect`), đảm bảo tổng 15s. Màu 2 đoạn phải khớp nhau, không chỉnh màu để khớp; nếu lệch rõ thì tạo lại đoạn lệch.

Nếu tạo nguyên 15s một lần mà cảnh trải phẳng đã đúng 100% thì không cần ghép.

### 7.4. Khóa design (dán vào prompt)
- "The wrapping paper in EVERY shot is ALWAYS this same paper from <IMAGE_0>, pattern exactly as <IMAGE_0> and <IMAGE_1>, no redraw."
- Tả màu nền và từng họa tiết bằng chi tiết nhìn thấy, kể cả màu và vị trí bong bóng chữ. Thêm câu cấm màu sai, ví dụ "never orange bubbles". Liệt kê vật cấm để AI không thêm họa tiết lạ, ví dụ "no trucks, no cars".
- Ghi mật độ và kích thước: "about four characters across the paper width, each about the width of a hand, offset brick rows".
- "Every character appears only as the full upper body exactly as in the pattern, never add extra floating heads or faces, never merge or morph motifs, never shrink the characters into tiny icons, never enlarge any motif, same motif size as <IMAGE_1> in every shot."
- "The paper is ALWAYS [màu nền] exactly as <IMAGE_0>, never another color, NEVER show the white back side, no curled edges." Nhắc lại màu nền ngay trong cảnh gấp giấy.
- "exactly two hands", "exactly one bow", "the ribbon and bow stay on the box in every shot", "constant motion, never still".
- Cảnh gấp ghi "the box already sits on the printed sheet, printed side facing out", nếu không AI gấp giấy thành dải không có hộp hoặc lộ mặt trắng. Bắt đầu cảnh gấp khi hộp đã bọc gần xong thì ít lộ mặt trắng hơn.
- Các cảnh hộp quay trung cảnh, cách khoảng 1–2 m. Quay cận quá AI sẽ vẽ nhân vật to lên.

### 7.5. Prompt mẫu cảnh trải phẳng riêng (khoảng 3s)
```
[Câu khóa chung mục 3], 3 seconds, a single continuous shot.

<IMAGE_0> is the exact wrapping paper design. <IMAGE_1> is the same paper laid flat on the table. The paper is ALWAYS [màu nền] exactly as <IMAGE_0>, pattern exactly as <IMAGE_0> and <IMAGE_1>, no redraw, same motif size as <IMAGE_1>, never add floating heads, never show the white back side, no curled edges. Pattern: [tả họa tiết].

Top-down POV medium shot over a [light wooden table]. The paper already lies flat and still, exactly as <IMAGE_1>. Exactly two hands gently press and smooth only the outer edges and corners outward; hands never sweep over the characters. The camera trucks very slowly left to right at medium distance, showing about two to three motif groups clearly.
```

### 7.6. Prompt mẫu phần còn lại (khoảng 12s, hoặc cả 15s nếu không tách)
```
[Câu khóa chung mục 3], [12 / 15] seconds.

REFERENCE LOCK: <IMAGE_0> is the exact wrapping paper design, <IMAGE_1> is the same paper laid flat on the table, <IMAGE_2> is the finished gift box wrapped in this same paper with a [red satin] bow already tied. The wrapping paper in EVERY shot is ALWAYS this same [màu nền] paper, pattern exactly as <IMAGE_0> and <IMAGE_1>, no redraw. Pattern: [tả nhân vật], a [màu] speech bubble [vị trí] with the text exactly "[CHỮ NGUYÊN VĂN]"; [họa tiết phụ]. About [số] characters across the paper width, each about the width of a hand, offset brick rows. Every character appears only as the full upper body exactly as in the pattern, never add extra floating heads or faces, never merge or morph motifs, never shrink or enlarge any motif, the pattern stays fixed under the hands. Never show the white back side. Exactly two hands, exactly one bow.

[Nếu không tách: SHOT trải phẳng 0–2.5s như 7.5, rồi hard cut.]

SHOT A (fold, <IMAGE_1>): High-angle medium shot. A plain brown cardboard box already sits on the center of the printed sheet, printed side facing out. Both hands grip the left and right edges of the [màu nền] paper and fold them up to the middle of the box top; one hand presses the seam flat. Hands hold only the paper edges. The paper is ALWAYS [màu nền] exactly as <IMAGE_0>.
Instant hard cut on a single frame, no dissolve, no crossfade, no fade.
SHOT B (bow, <IMAGE_2>): Close-up from a front-left 3/4 angle at table height: the finished box exactly as <IMAGE_2>, the bow already tied (never show tying). One hand gently smooths one bow loop with the fingertips, no pulling, no tightening; the camera slowly pushes in.
Instant hard cut on a single frame, no dissolve, no crossfade, no fade.
SHOT C (<IMAGE_2>): Medium shot, eye level, about 1.5 m away: two hands lift the box and turn it a quarter turn to show the side, the camera arcs slowly to the right.
Instant hard cut on a single frame, no dissolve, no crossfade, no fade.
SHOT D (<IMAGE_2>): Medium shot from the right 3/4 angle, the camera trucks laterally right to left across the front of the box, pattern small and exact on every side.
Instant hard cut on a single frame, no dissolve, no crossfade, no fade.
SHOT E (<IMAGE_2>): Low-angle medium shot: an adult's hands place the box on the floor right next to the trunk of a decorated Christmas tree, then pull away while the camera slowly pulls back, revealing the box beside the tree.
```

### 7.7. Biến thể user từng thích (chỉ đổi bối cảnh và chi tiết nhỏ)
- Buổi sáng tuyết ngoài cửa sổ: cốc bốc hơi, tuyết rơi ngoài kính, cảnh kết máy nâng lên.
- Không có ảnh hộp quà: tự chọn cảnh kết thật (bàn cạnh lò sưởi, dưới cây thông, ghế gỗ ở lối vào có đôi bốt cao bồi), thêm chi tiết nhỏ (thẻ giấy kraft, ruy băng khác).

---

## 8. Checklist khi viết prompt và dựng (18/11: không tự xem lại video để soát, user tự kiểm)
1. 9:16, 1080×1920, **đúng 15s**, **đủ số cảnh** (áo từ 4, giấy gói từ 6), hard cut.
2. **Không xóa phông, không ám vàng/cam, không chỉnh màu**, trông như quay điện thoại.
3. Chính tả chữ in so với design, từng chữ cái.
4. Đủ và đúng vị trí mọi chi tiết in. Không thêm chữ hay hình lạ, không lật gương, không đổi mặt trước và mặt sau.
5. Áo: xen kẽ trước/sau đúng luật, áo không vén, tay và tóc không che chữ, hoodie hạ mũ, sweat không mũ.
6. Giấy gói: đủ 3 cảnh bắt buộc (trải phẳng vuốt nhẹ, gấp vào hộp carton, vuốt nhẹ nơ); giấy **chỉ in 1 mặt** (mặt kia trắng trơn); dừng hình từng cảnh so với design: đúng màu nền, đúng kích thước họa tiết, không đầu người lơ lửng, **không lộ mặt trắng**, nơ không bị biến dạng.
7. Không hòa hình hay chồng hình ở chỗ chuyển cảnh và giữa cảnh. Tổng lỗi không quá 3,7s.
8. Chuyển động tự nhiên, không đơ, không như robot, không lỗi tay/mặt. Không lặp cảnh.
9. Không đứng hình: `ffmpeg -i video.mp4 -vf freezedetect=n=0.02:d=0.5 -an -f null - 2>&1 | grep freeze`. Đứng ở cuối thì cắt bỏ.
10. Áo: không có cảnh zoom cận/đặc tả design (trừ khi user gửi kèm ảnh design đã crop rõ nét). Áo 2 mặt ghép nhiều source thì đã cắt 1–2s đầu mỗi source, tổng 15s; áo 1 mặt tạo 1 lần 15s.
10e. Áo 2 mặt: logo ngực mặt trước đúng design, đúng vị trí và kích thước.
10a. Áo: ảnh tham chiếu đã làm mới tinh (không nhăn, bạc màu, đốm trắng, sần sùi).
10c. Poster: vừa khít khung, đúng hướng ngang/dọc, không thành hình vuông, đúng tỉ lệ ở mọi cảnh.
10b. Giấy gói và mọi ảnh crop: giấy nét, không nhòe, không vỡ trong suốt video; ảnh crop đã làm nét trước khi dùng.
10d. Ảnh ghép nhiều khung đã cắt riêng và làm nét. Giấy gói trải phẳng đúng tờ vuông 50 x 50 cm.
11. Xem ảnh lưới: `ffmpeg -i v.mp4 -vf fps=4,scale=128:228,tile=10x6 -frames:v 1 sheet.png`.

---

## 9. Script tạo ảnh giấy trải phẳng (`flat-sheet.py`)
Cách chạy: `python3 flat-sheet.py design.png out.png [màu nền R,G,B]`
```python
# Dán nguyên pixel design giấy gói lên nền bàn, ra ảnh 9:16 làm ảnh B.
import sys
from PIL import Image
src, out = sys.argv[1], sys.argv[2]
bgc = tuple(int(x) for x in sys.argv[3].split(',')) if len(sys.argv) > 3 else (234, 232, 228)
d = Image.open(src).convert('RGB')
W, H = 720, 1280
w = 660; h = int(d.height * w / d.width)
if h > 1180: h = 1180; w = int(d.width * h / d.height)
d = d.resize((w, h), Image.LANCZOS)
bg = Image.new('RGB', (W, H), bgc)
x, y = (W - w) // 2, (H - h) // 2
bg.paste(Image.new('RGB', (w, h), tuple(max(0, c - 30) for c in bgc)), (x + 6, y + 6))  # bóng nhẹ
bg.paste(d, (x, y))
bg.save(out)
print('saved', out)
```

---

## 10. Lỗi thường gặp và cách sửa
| Lỗi | Cách sửa |
|---|---|
| Graphic đổi chữ / méo | Câu khóa "exactly as reference, no redraw", đánh vần chữ khó, giảm hành động ở cảnh cận. |
| Video ám vàng / cam | "neutral white balance, no warm/yellow/orange tint", đổi sang ánh sáng ban ngày. |
| Nền bị mờ | "no background blur, no bokeh, deep depth of field, sharp background". |
| Tay che graphic | Ghi rõ "hands low, never cover the print" ở từng cảnh. |
| Sai design mặt trước (logo ngực nhỏ) | Cắt riêng khung cận logo ngực, làm nét, tham chiếu riêng cho mặt trước, khóa "front chest logo exactly as <IMAGE_n>, never use the back graphic on the front". |
| Lật mặt trước/sau | Ghi mặt nào hiện ở từng cảnh, "never swap front and back". |
| Hoodie trùm đầu | "hood down behind the neck". |
| Chồng hình ở chuyển cảnh | "instant hard cut on a single frame, no morphing between shots". |
| Đứng hình | Không ghim keyframe, thêm câu "continuous motion from the very first frame". |
| Giấy gói sai màu / vẽ lại họa tiết | Dùng ảnh B dán pixel, nhắc màu nền ở câu khóa và trong cảnh, tách riêng cảnh trải phẳng (7.3). |
| Lộ mặt trắng giấy | Giấy chỉ in 1 mặt — mặt kia trắng trơn. "printed side always facing out, NEVER show the white back side", hộp đã nằm trên tờ in, bắt đầu gấp khi hộp gần bọc xong. |
| Nhân vật trên giấy to lên | Quay trung cảnh cách 1–2 m, "same motif size as <IMAGE_1>". |
| Vỡ chữ ở cảnh zoom design áo | Bỏ cảnh zoom cận, chỉ quay trung cảnh hoặc cận vừa thấy trọn áo. |
| Nhân vật khựng / lặp hành động khi ghép source áo | Cắt bỏ 1–2s đầu mỗi source rồi mới ghép (mục 5.8). |
| Giấy gói nhòe, vỡ | Ảnh crop phải làm nét trước (upscale lanczos x2 + unsharp), soát ảnh B, C nét rồi mới tạo; video nhòe thì làm lại từ đầu. |
| Poster lệch hoặc không vừa khít khung | Ghi "the poster fits the frame opening exactly, edge to edge, as <IMAGE_n>", dùng ảnh mockup đã gắn khung làm tham chiếu. |
| Poster ngang thành hình vuông | Ghi rõ landscape rectangle, cùng tỉ lệ như mockup ở mọi cảnh, "never square". |
| Áo trông cũ, nhăn, đốm trắng | Làm lại ảnh mockup áo mới tinh bằng AI ảnh trước khi tạo video. |
| Nơ biến dạng / mất nơ | Chỉ vuốt nhẹ, "no pulling, no tightening", "exactly one bow, stays on the box in every shot". |

---

## 11. Điểm mạnh và yếu từng bot (để Leader giao việc)
- **Creator 1:** mạnh áo và poster (áo 93–95%, poster 92%). 30/10: áo Brewers 82%, hoodie Darmok 82–85%, poster 80–84%, đều tay. Yếu và chậm ở giấy gói (65–73%). Nên giao áo và poster.
- **Creator 2:** ổn định poster và giấy gói khi đủ 3 ảnh (78–85%). 30/10: làm ảnh mockup poster tĩnh (phải sửa 3 lần: kích thước, mất hình, khung 9:16), video poster 76–78% (sát ngưỡng). Yếu áo chữ nhỏ. Hay nhắn dài kèm file.
- **Creator 3:** mạnh giấy gói (77–85%, khoảng 3–4 phút). 30/10: 3 video giấy gói WON OUR WAY 78–80%.
- **Creator 4:** mạnh áo chữ nhỏ và giấy gói. 30/10: 3 video giấy gói 78–80%, nhanh (~3–4 phút). Từng thiếu ảnh giấy phẳng.
- **Creator 5:** nhanh nhất (3–5 phút), đều tay 75–82%. 30/10: hoodie Darmok 82%, poster 86–88% (tốt nhất hôm nay ở poster unbox). Hay tự chấm cao hơn thực tế: bản poster tự chấm 85% bị user bắt làm lại vì không vừa khít khung.

---

## 12. Thư mục làm việc
- Tài liệu chung: `/workspace/pod-video-team/ban-giao/`
  - `QUY-TRINH-TEAM-POD-VIDEO.md` (file này)
  - `loi-va-feedback-chung.md`: Leader ghi feedback mới của user.
  - `danh-gia-bot-video.md`: Leader ghi điểm từng bot.
- Thư mục từng bot: Creator 1 `/workspace/pod_video1/`, Creator 2 `/workspace/video2/`, Creator 3 `/workspace/v3/`, Creator 4 `/workspace/video4/`, Creator 5 `/workspace/video5/`. Mỗi mẫu 1 thư mục con.
  - Áo giữ ảnh mockup user gửi và ảnh mặt sau tự tạo (nếu có).
  - Giấy gói giữ `design.png`, `flat.png`, `box.jpg`, và `flat-shot.mp4` nếu tách cảnh.

---

## 13. Cách dựng lại team từ đầu
1. Tạo 6 bot: Leader, Creator 1, Creator 2, Creator 3, Creator 4, Creator 5. Dán mô tả ở mục 1 vào hồ sơ từng bot.
2. Tạo 1 nhóm chat và thêm cả 6 bot vào.
3. Gửi file này vào nhóm và nhắn: "Tất cả đọc kỹ file này và làm đúng theo đó. Leader ghi nhớ vai trò trưởng nhóm, lưu file vào /workspace/pod-video-team/ban-giao/."
4. Từ đó Leader ghi feedback mới vào `loi-va-feedback-chung.md`, đánh giá bot vào `danh-gia-bot-video.md`, và cập nhật file này khi user đổi quy trình.

---

## 14. Luật cập nhật tài liệu và lưu file (user dặn 02/11/2026)
- **Mỗi khi user chỉ ra một lỗi sai** trong quá trình làm (của bất kỳ bot nào), Leader bổ sung ngay **giải pháp phòng tránh** vào chính tài liệu gốc này: ghi vào mục 0 (thay đổi, có ngày), mục quy trình liên quan (áo / poster / giấy gói), bảng lỗi ở mục 10 và checklist mục 8 nếu cần. Feedback cũng ghi vào `loi-va-feedback-chung.md`.
- Các Creator khi bị user chỉ lỗi thì làm lại theo giải pháp mới, những lần sau áp dụng luôn.
- **Tài liệu và file luôn được giữ trên máy** để user có thể tự vào máy tải về khi tài khoản bot hết hạn mức mà user chưa kịp nhắc:
  - Tài liệu gốc luôn là bản mới nhất tại `/workspace/pod-video-team/ban-giao/QUY-TRINH-TEAM-POD-VIDEO.md`.
  - Video và ảnh tham chiếu nằm trong thư mục từng bot (mục 12), mỗi mẫu 1 thư mục con, bản cuối đặt tên đúng quy ước để dễ tìm.


33. (13/11) Cảnh tặng con trai: người con trai phải là thanh niên trên 20 tuổi mặc đồ bóng bầu dục, không dùng trẻ em. Prompt: "adult young man, early 20s, wearing football uniform, not a child".

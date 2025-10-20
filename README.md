## Xin chào 👋
Đây là Git chính thức của NHQTools.
Các thông tin liên quan đến các tools trong hệ sinh thái Tools sẽ được cập nhật tại đây.
## Các kênh:
- Website chính thức: https://nhq.tools
- Youtube: https://www.youtube.com/@nhqtools
- Facebook: https://www.facebook.com/nhqtools/

---

## Phiên bản 3.6.2 cập nhật 20.10.2025:
- Thử nghiệm tính năng tạo video VEO 3.1 không giới hạn kết hợp trong tạo phân cảnh.
- Cải thiện tính năng dịch chậm (anh em nào có tài khoản pro thì sử dụng model 2.5-pro cho nhanh hơn nhé)
 

Do Elevenlabs và Minimax thay đổi cơ chế, hiện tại việc tạo giọng từ Elevenlabs cũng như Q-CLONE có thể sẽ bị chậm vào một số thời điểm, nên khi chậm anh em chịu khó chờ. (Có thể stop lại, sau đó chạy lại vào thời điểm khác).
Tuy nhiên, anh em lưu ý: Không thay đổi nội dung văn bản, nếu thay đổi thì sẽ bị tính phí là một văn bản mới.

---------------------------------------------------
Đối với các anh làm review phim, chưa biết cách để tối ưu quá trình làm việc thì chịu khó xem các video hướng dẫn, và tìm hiểu thêm tài liệu trên website để hiểu bản chất của các thông số cũng như cấu hình.

---------------------------------------------------

Do bận công việc, nên từ giờ có thể mình sẽ ít reply các tin nhắn support hơn.

**Cảm ơn anh em đã đồng hành**
---

## Phiên bản 3.4.8 cập nhật 10.10.2025:
- Fix lỗi lag giật khi xoá phụ đề, thêm phụ đề trên web. Bây giờ với vài nghìn dòng phụ đề khi thêm hoặc xoá phụ đề không còn tình trạng lag nữa.
- Thêm tuỳ chọn chọn kiểu KeyFrames khi sử dụng tính năng ghép ảnh và audio.
- Tự động kiểm tra ngôn ngữ sau khi dịch, đảm bảo rà soát toàn bộ các phụ đề đã dịch để anh em chủ động xem lại các phụ đề chưa dịch hoặc lỗi khi dịch.
- Fix lỗi tạo giọng đọc tiếng Việt khi có các phụ đề ngôn ngữ khác.
- Fix một số bug khác.

---


## Phiên bản 3.3.6 cập nhật 01.10.2025:
- Fix lỗi tải video trong Video Tools (một số máy tải bị lỗi do không cập nhật được).
- Cải thiện tính năng dịch chậm: Thêm các tuỳ chọn bổ sung khi dịch (phong cách dịch, thông tin yêu cầu bổ sung); ổn định hơn khi dịch. Anh em nào có tài khoản gemini pro có thể thêm vào tool và tăng số dòng dịch 1 lần lên 500 để nhanh hơn và chuẩn hơn (sử dụng model gemini 2.5 pro); (Tài khoản anh có thể mua với giá 12k trên taphoammo nếu cần, còn không thì theo mình dùng tài khoản Free cũng vẫn ok).
- Fix lỗi hiển thị % tiến trình khi tạo giọng đọc trong Video Tools; Thông báo chi tiết các Index (dòng phụ đề) nào lỗi khi chạy để anh em có thể kiểm tra lại và chạy lại nhanh nếu cần.
- Cải thiện tính năng tạo phân cảnh (Thêm tạo phân cảnh nhanh - Thêm tuỳ chọn số phân cảnh tạo mỗi bước); Ổn định hơn và nhanh hơn.

NHQTools cũng chuẩn bị ra mắt các tính năng mới:
- Tích hợp tạo phụ đề tự động từ capcut (tích hợp thẳng capcut vào trong Tools)
- Tích hợp tách nhạc nền, giọng đọc từ capcut (tích hợp trong Tools)

Đặc biệt: Chuẩn bị ra mắt tính năng tạo Video Veo3 không giới hạn, chạy đa luồng, có thể tạo 10 video/ phút.

---


## Phiên bản 3.2.9 cập nhật 24.09.2025:

- Thêm tuỳ chọn tạo lại hoặc không tạo lại ảnh và video khi sử dụng tính năng tạo phân cảnh tự động.
- Fix lỗi tải video từ Tiktok và BiliBili.
- Fix lỗi tải video VIP v.qq.com (chỉ áp dụng với ai có tài khoản VIP).
- Fix một số bug khác.

---


## Phiên bản 3.2.8 cập nhật 23.09.2025:

- Thêm cấu hình model tạo ảnh (**Nano Banana**, Model ICv3,2,1) khi tạo phân cảnh.
- Thêm tạo **video AI từ prompt** (độ dài 10s)
- Thêm tuỳ chọn add **Keyframes**, **effect duration** cho dự án capcut khi sử dụng tính năng ghép ảnh + audio.
- Fix lỗi dịch chậm
- Fix một số bug khác.

---


## Phiên bản 3.2.6 cập nhật 21.09.2025:

- Thêm cấu hình ngắt nghỉ cho **NHQ-2**: Anh em có thể ngắt nghỉ với tuỳ chọn **[pause:Xs]** ví dụ **[pause:3s]**; Anh em lưu ý là nếu để cấu hình ngắt nghỉ với [pause] thì tốc độ tạo giọng sẽ chậm hơn.
- Cải thiện hiệu suất **tạo giọng theo phụ đề** (đối với giọng Q-CLONE); Tốc độ tạo giọng nhanh hơn nhiều.
- Fix lỗi tạo giọng với **CHATGPT Custom**.
- **Tạo phân cảnh: Beta**, còn cần theo dõi và phát triển thêm (chưa bao gồm xuất capcut).
- Fix các lỗi khác.

---

## Phiên bản cập nhật 3.2.3 và 3.2.4:

+ Thêm tính năng dịch chậm, đảm bảo dịch sát nghĩa
+ Dịch chậm với tuỳ chọn phogn cách như: Phim - Huyền Huyễn, Phim - Cổ Trang, Phim - Tổng Tài...
+ Fix một số bug khác.

---


## Phiên bản cập nhật 3.0.8 (2025-08-26):

+ Thêm tính năng download Full kênh trên Baidu (haokan)

Anh em có thể tham khảo thêm lịch sử cập nhật trên website chính thức của NHQTools

> https://nhq.tools/vi/docs/nhq-vid/change-logs

---



## Phiên bản cập nhật 2.9.8 (2025-08-18):

+ Cải thiện chất lượng dịch với Gemini
+ Cho phép viết lại nội dung video (dịch cùng ngôn ngữ)
+ Fix một số bug nhỏ khác.
 
Ngoài ra trong phiên bản này, NHQTools cũng đang thử nghiệm phương thức dịch sử dụng tài khoản Google thay vì sử dụng API để tránh bị limited khi request số lượng lớn.

**Anh em cùng chuẩn bị đón chờ phiên bản cập nhật với các tính năng mới:**
+ Hỗ trợ ngắt nghỉ ngẫu nhiên thời gian để file giọng đọc tự nhiên hơn, như người thật hơn.
+ Hỗ trợ lồng tiếng nhiều giọng cho video khi sử dụng Q-CLONE
+ Thêm tính năng tự động nhận dạng giới tính (Nam, Nữ và giọng dẫn) cho file phụ đề sử dụng AI.

**Cảm ơn anh em đã đồng hành cùng NHQTools!**

---

## Phiên bản cập nhật 2.9.3 (2025-08-09):
+ Cải thiện tạo giọng với Minimax
+ Tăng tốc gấp hơn 4 lần với Recut trong Video Tools
+ Fix lỗi xuất phụ đề sang capcut
+ Fix nhiều bug nhỏ khác.

NHQTools liên tục cập nhật các bản vá lỗi, nâng cao trải nghiệm người dùng cho các dịch vụ.
Cảm ơn anh em đã tin tưởng và sử dụng.

**Trong thời gian sắp tới:**
1/ Clone giọng trực tiếp trên web sẽ mở lại
2/ Cải thiện cơ chế tạo giọng đọc với Elevenlabs (tăng tốc và đảm bảo sự ổn định).
3/ Demo các tính năng tạo ảnh AI miễn phí và trả phí (tạo hàng nghìn ảnh cực nhanh)
...

---

**Cập nhật tính năng mới cho Video Tools**
- Thêm tính năng tạo phụ đề từ Sub cứng trong video
- Fix lỗi download video QQ
- Fix một số lỗi nhỏ khác.

 
## Phiên bản cập nhật 2.8.4 (2025-07-25):
**Cập nhật tính năng mới cho Video Tools**
- Thêm tính năng tạo phụ đề từ Sub cứng trong video
- Fix lỗi download video QQ
- Fix một số lỗi nhỏ khác.


## Phiên bản cập nhật 2.5.7 (2025-06-16):
**NHQTools cập nhật các tính năng mới cho TTS STUDIO và Video Tools**
- Thêm Q-CLONE vào danh sách dịch vụ giọng trong Video Tools
- Fix lỗi Ele2 trong Video Tools
- Fix một số lỗi khi xuất video

**Với TTS Studio**
TTS Studio mới update một vài tính năng AI mới. Anh em xem có hỗ trợ gì cho công việc không nhé.
1. Tự động kiểm tra chính tả AI
- Kiểm tra lỗi chính tả
- Gợi ý cách đọc với các từ không phải tiếng Việt (ví dụ: indonesia => in-đô-nê-xi-a)
- Chỉnh sửa các câu dài thành câu ngắn hơn phù hợp để tạo giọng mà không bị nuốt từ hay vấp từ
- Tự động chuyển đổi số thành chữ, ngày tháng thành chữ, các đơn vị tiền tệ, khối lượng... đảm bảo giữ nguyên ý nghĩa
- Tự động kiểm tra lỗi ký tự ẩn khi văn bản đầu vào được tạo ra bởi các AI

2. Tóm tắt nội dung bằng AI
- Tự động tóm tắt nội dung với 2 phiên bản: Ngôn ngữ gốc và Tiếng Việt

3. Tạo thumbnail tự động
- Tạo prompt và thumbnail tự động cho đoạn văn bản đầu vào
- Có thể tuỳ chỉnh prompt trước khi tạo
- Có thể chọn kích thước khung hình phù hợp các loại video dọc, ngang.

  

## Phiên bản mới nhất v.2.4.7 (2025-06-04):
**NHQTools cập nhật các tính năng mới cho TTS STUDIO**
- Thêm tính năng delay giữa các đoạn/ phần/ chương.
- Tạo giọng đọc cho nhiều file cùng một lúc
Các tính năng thử nghiệm trong thời gian tới (chưa ra mắt):
- Cho phép tạo nhiều giọng trong cùng một lần chuyển đổi (kiểu đối thoại)
- Custom giọng khi sử dụng elevenlabs (nhấn nhá, ngữ điệu tuỳ chỉnh)
> Ngoài ra, anh em tham khảo cách tạo giọng đọc, lồng tiếng cho file phụ đề bên Video Tools nhé. Thấy nhiều anh em muốn tạo giọng đọc cho phụ đề, nhưng lại không để ý bên Video Tools có sẵn.
> Anh em dùng Video Tools chỉ cần click vào "Kết nối Video Tools" thôi nhé.
Mời anh em trải nghiệm và xem clip tại kênh chính thức của NHQTools: @nhqtoools

## Phiên bản mới nhất v2.2.2 (2025-05-12):
Cập nhật rất nhiều các tính năng, fix lỗi và cải thiện hiệu suất
- Fix lỗi khi xuất capcut với phương thức đồng bộ là video
- Fix lỗi và cải thiện hiệu suất tạo giọng bằng ChatGPT
- Thêm tính năng chia sẻ credits giữa các thành viên
- Fix một số lỗi nhỏ
- Cải thiện hiệu suất và thêm theo dõi tiến trình với Elevenlabs2
- Cải thiện và fix lỗi khi xuất video.
- Thêm cấu hình đồng nhất video để tránh lỗi khi xuất.
- Fix lỗi tạo phụ đề gemini trên Windows.
- Thêm theo dõi tiến trình khi tạo phụ đề với gemini.
- Cải tiến tính năng ghép ảnh độc quyền (Độc quyền cho từng khách hàng)
- Fix lỗi thanh toán tự động khi nạp tiền.\nCải thiện nhiều tính năng khác.
- Fix lỗi tính số ký tự unicode.
- Fix lỗi tách frames với CPU.
- Cải thiện chất lượng tiếng Việt khi dùng ChatGPT TTS
- ...

## Phiên bản v2.1.0 (2025-05-04):
NHQ Video Tools (NHQTTS Studio) v2.1.0
Phiên bản cập nhật mới nhất: 2.1.0
Bản update nhiều tính năng và tối ưu hiệu suất.
- Cập nhật thêm 2 phương thức chuyển giọng trong TTS Studio, hiển thị chi tiết tiến trình tạo giọng trong studio
- Hỗ trợ tạo giọng nói theo phong cách đối với voice ChatGPT custom
- Cải thiện hiệu suất khi export Video, điều chỉnh khớp hoàn toàn với audio và phụ đề trong trường hợp đồng bộ bằng cách điều chỉnh video
- Hỗ trợ các layout trên video (logo, fill, blur...)
- Thêm phụ đề nhanh chóng trên video
- Hiển thị chi tiết tiến trình tạo voice, nâng cao trải nghiệm
- Kiểm tra phụ đề đảm bảo phụ đề khớp trước khi tạo giọng.
- Hỗ trợ tạo prompt dịch tự động (prompt đề xuất bằng AI) dựa trên ngữ cảnh cũng như các nhân vật trong video.
- Fix một số lỗi khác...
**Mời anh em download trải nghiệm**
https://nhq.tools/downloads

----
Sau nhiều lần trì hoãn, hôm nay, mình chính thức mở bán công cụ hỗ trợ cho các anh em đang làm mảng video youtube và tiktok beta, đặc biệt là những anh em làm reup và review phim.

Bộ công vụ NHQTools sử dụng các mô hình trí tuệ nhân tạo mới nhất:
Mình xin phép được giới thiệu qua các tính năng cơ bản của Tool:

- **Tải video đa nền tảng** miễn phí, không giới hạn (hỗ trợ hầu hết các nền tảng video hiện nay như **Youtube**, **Tiktok**, **Douyin**, Instagram, Facebook, X (Twitter), Vimeo, Dailymotion... với tốc độ và trải nghiệm tốt nhất.
 - **Tạo phụ đề tự động** cho Video hỗ trợ hầu hết các ngôn ngữ: Sử dụng các mô hình Speech to text đầy đủ, đảm bảo chất lượng tốt nhất. Miễn phí 100% tạo phụ đề với whisper;
 - **Tự động nhận diện nhân vật** khi tạo phụ đề, đảm bảo các đoạn phụ đề gắn đúng với nhân vật trong video.
 - **Tự động dịch** sang nhiều ngôn ngữ, hỗ trợ dịch song song nhiều ngôn ngữ trong một lần. NHQTools sử dụng các mô hình AI để dịch phụ đề đảm bảo chất lượng phụ đề là tốt nhất. **Miễn phí 100% dịch phụ đề với Gemini AI và tất nhiên rồi, miễn phí 100% với Google Translate**. Anh em có thể sử dụng nhiều mô hình AI như DeepSeek, ChatGPT, Claude, Gemini... 
 - Hỗ trợ dịch phụ đề với các **prompt tuỳ chỉnh**: Hỗ trợ dịch phụ đề theo prompt tuỳ chỉnh cho anh em có nhu cầu, và linh hoạt hơn đối với từng nội dung khác nhau.
 - **Tóm tắt video nhanh chóng**, **tổng hợp nhân vật trong video tự động**: Tính năng này giúp anh em có thể hiểu được nội dung để có thể áp dụng cho các prompt tuỳ chỉnh.
 - **Chỉnh sửa trực tiếp phụ đề** trong Tool: Anh em có thể chỉnh sửa phụ đề trực tiếp trong tool và lưu trạng thái chỉnh sửa, giúp anh em kiểm soát tốt nội dung trước khi chuyển giọng hoặc xuất phụ đề.
 - **Xuất phụ đề và xuất phụ đề sang Cacpcut**: Anh em có thể xuất phụ đề để phục vụ các mục đích khác, hoặc xuất phụ đề sang Capcut để tạo giọng đọc miễn phí nhanh chóng.
 - **Tách frames ảnh từ video:** Đây là tính năng rất hay đối với các anh em làm video anime, video manga hoặc review truyện tranh. Tool sẽ trích xuất các frames (ảnh) và ghép lại với nhau đồng nhất hoàn toàn với giọng đọc đảm bảo anh em sản xuất video một cách đơn giản nhất có thể.
 - **Xuất video và dự án capcut**: Một trong những tính năng được rất nhiều anh em đề xuất đó là xuất video, frames qua capcut. Tool tự động xuất các frames ảnh, tự động áp dụng các hiệu ứng ngẫu nhiên hoặc thủ công và tự động tạo dự án capcut, công việc còn lại của anh em chỉ là mở capcut và render. Tool hỗ trợ gần 1000 hiệu ứng video và ảnh khác nhau, anh em có thể thoải mái lựa chọn.
 - **Xuất video tuỳ chỉnh**: Anh em cũng có thể xuất video trực tiếp từ tool, hỗ trợ các kích thước, độ phân dải phổ biến (Video dọc 9:16, video ngang 16:9, video chuẩn TV 4:3, hay video vuông 1:1); Hỗ trợ xuất video lên đến 4k. 
 - **Hỗ trợ đồng bộ âm thanh, video và phụ đề**: Khi xuất video anh em có thể đồng bộ thời gian cho video, âm thanh cũng như phụ đề, đảm bảo mọi thứ đồng bộ, khớp và không bị chống lấn hay méo mó âm thanh. Anh em có thể sử dụng các phương thức đồng bộ như **Đồng bộ âm thanh**, **đồng bộ video**, tuỳ chỉnh chế độ cắt thông minh để đảm bảo video xuất ra là unique.
 - **Về giọng đọc:** NHQTools hỗ trợ anh em tạo giọng đọc AI linh hoạt với hàng nghìn giọng đọc khác nhau cho mọi ngôn ngữ với mức giá cực kỳ ưu đãi, và tất nhiên vẫn là "**Miễn phí 100% với giọng đọc chị Google**" :)
 - **Tạo giọng đọc tuỳ chỉnh với Clone giọng miễn phí**: Anh em có thể clone giọng đọc của chính mình để sử dụng cho video, hoặc clone giọng bất kỳ. Tuy nhiên, với tính năng clone giọng đọc này, NHQTools không hỗ trợ tự động, anh em có thể gửi trực tiếp yêu cầu, sau đó bên mình sẽ kiểm tra và đảm bảo không vi phạm các điều khoản của NHQTools. 
 - Chỉnh sửa, thực hiện chuyển đổi văn bản thành giọng đọc với **NHQTTS Studio**: Mình cũng hỗ trợ thêm một phần riêng biệt cho anh em nào chỉ sử dụng tính năng chuyển văn bản thành giọng đọc. Với NHQTTS Studio, anh em có thể tải lên văn bản Word, tệp PDF hay file text đơn thuần, tool sẽ đọc nội dung và chuyển văn bản thành giọng đọc một cách nhanh chóng.

Còn rất nhiều các tính năng hay cũng như nâng cao khác được tích hợp sẵn trong tool. Anh em có thể dùng thử và nếu thấy hợp thì hãy ủng hộ mình nhé.

Hiện tại, tool hỗ trợ trên Windows. Anh em nào có nhu cầu chạy trên Mac (Intel hay Silicon) hoặc build bản riêng cho linux thì hãy liên hệ với mình nhé.

Anh em có thể xem qua chi tiết các tính năng của tool và hướng dẫn sử dụng chi tiết tại trang chủ NHQTools: https://nhq.tools
- Tài liệu hướng dẫn: https://nhq.tools/docs/nhq-vid/setup
- Giới thiệu tổng quan: https://nhq.tools/vi/features/nhq-vid
- Tải về và cài đặt: https://nhq.tools/downloads
- Liên hệ: https://nhq.tools/contact

Cảm ơn anh em đã xem.
Rất mong được sử ủng hộ của anh em.


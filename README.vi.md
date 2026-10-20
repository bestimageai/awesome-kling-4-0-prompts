# Bộ câu lệnh Kling 4.0

Bộ câu lệnh và hướng dẫn tạo video do **bestimage.ai** biên soạn. Mô tả rõ trạng thái ban đầu, chuyển động, máy quay, âm thanh và khung hình kết thúc để có tiêu chí cụ thể khi đánh giá kết quả.

[English](README.md) · [Bahasa Indonesia](README.id.md) · [ไทย](README.th.md) · Tiếng Việt

## Khám phá nội dung

- [Danh mục câu lệnh](prompts/README.md): 108 câu lệnh gốc bằng tiếng Anh, chia thành 12 nhóm.
- [Ví dụ chính thức](docs/official-examples.md): 12 ví dụ kèm tư liệu và nguồn để tìm hiểu chuyển động, máy quay và cách dùng tư liệu tham chiếu.
- [Hướng dẫn viết câu lệnh](docs/prompting-guide.md): đầu vào, trình tự thời gian, tính liên tục và âm thanh.
- [Khả năng của mô hình](docs/model-capabilities.md), [khắc phục sự cố](docs/troubleshooting.md) và [hướng dẫn bestimage.ai](docs/bestimage-workflow.md).

Trang này dịch phần hướng dẫn bắt đầu và một ví dụ đầy đủ. Toàn bộ danh mục câu lệnh cùng tài liệu chi tiết được viết bằng tiếng Anh. Các trang giới thiệu bằng 15 ngôn ngữ không có nghĩa là cả danh mục đã được dịch. Ví dụ chính thức được trình bày riêng với câu lệnh gốc của bộ sưu tập; không xem video chính thức là kết quả tạo từ những câu lệnh này.

## Bắt đầu với ba bước

1. Chọn [tạo video từ văn bản](https://bestimage.ai/models/kuaishou/kling-4-0-text-to-video/) khi bắt đầu bằng mô tả, hoặc [tạo video từ hình ảnh](https://bestimage.ai/models/kuaishou/kling-4-0-image-to-video/) nếu đã có ảnh mở đầu. Đọc yêu cầu đầu vào của từng mục trước.
2. Sao chép toàn bộ câu lệnh, rồi điều chỉnh nhưng giữ nguyên số lượng chủ thể, thứ tự hành động và trạng thái cuối. Thời lượng và tỷ lệ khung hình là mục tiêu sáng tạo; thiết lập thực tế dựa trên các lựa chọn của trang đang sử dụng.
3. Xem lại video theo tiêu chí kiểm tra. Mỗi lần chỉ thay đổi một yếu tố để dễ so sánh độ rõ của chuyển động, sự nhất quán của vật thể và khoảng dừng ở cuối.

## Ví dụ đầy đủ: Chiếc ô được trả lại

**Chế độ:** Tạo video từ văn bản  
**Định hướng sáng tạo:** 10 giây, 16:9  
**Đầu vào:** Không có  
**Mục trong danh mục:** [K001](prompts/cinematic-stories.md#k001)

```text
Một cảnh quay trung rộng liên tục dài mười giây bên trong tiệm sửa ô nhỏ sau cơn mưa. Chủ tiệm là người trưởng thành, mặc tạp dề xanh lá đậm, đứng sau quầy gỗ. Một chiếc ô vàng đang khép nằm ngang trên quầy, tay cầm cong hướng sang phải. Trong ba giây đầu, chủ tiệm luồn một miếng vải xanh dương đã gấp xuống dưới chiếc ô. Từ giây thứ ba đến giây thứ bảy, chủ tiệm chậm rãi xoay chiếc ô đang khép một phần tư vòng để đường may vừa sửa hướng về phía khách. Trong ba giây cuối, chủ tiệm rút cả hai tay về và mỉm cười dịu dàng với người khách ở ngay ngoài khung hình. Máy quay tiến gần một chút mà không chuyển sang phía đối diện. Ánh sáng dịu từ cửa sổ làm hiện rõ vỉa hè ướt bên ngoài và lớp vải ô vàng không bóng bên trong. Âm thanh: tiếng mưa nhẹ bên ngoài, tiếng vải cọ vào gỗ và một tiếng chạm khẽ của tay cầm. Không có lời thoại, phụ đề hoặc nhạc nền. Giữ chiếc ô khép suốt cảnh, với cùng tay cầm, màu vải và vị trí trên quầy.
```

**Có thể điều chỉnh:** Màu ô, màu tạp dề, ánh sáng từ cửa sổ.

**Kiểm tra:** Chỉ có một chiếc ô và ô luôn khép; miếng vải vẫn nằm bên dưới; đường may xoay cùng vải ô; cả hai tay buông ô trước khoảng dừng cuối cảnh.

Giữ nguyên hành động khi thử màu sắc hoặc ánh sáng khác. Đổi đồng thời máy quay, bối cảnh và hành động sẽ khiến việc tìm nguyên nhân khó hơn. Hãy kiểm tra xem vật thể có đột nhiên xuất hiện thêm, tay có xuyên qua vải ô, hoặc âm thanh có lệch khỏi hành động trong hình hay không.

## Tài liệu và đóng góp

Các hướng dẫn phân biệt ý đồ sáng tạo, khả năng của mô hình và lựa chọn trên trang sử dụng. Khi dùng tư liệu chính thức, đọc nguồn và thông tin quyền sử dụng tại trang ví dụ. Giấy phép cho văn bản của kho không tự động áp dụng cho hình ảnh hoặc video của bên thứ ba.

Theo [hướng dẫn đóng góp](CONTRIBUTING.md), hãy cung cấp câu lệnh đầy đủ, đầu vào cần thiết và tiêu chí có thể quan sát. Xem điều kiện sử dụng trong [giấy phép](LICENSE).

## Tiếp thị liên kết bestimage.ai

Nếu bạn chia sẻ hướng dẫn làm video, câu lệnh hoặc quy trình sáng tạo, hãy tìm hiểu [chương trình tiếp thị liên kết bestimage.ai](https://bestimage.ai/affiliate-program/). Điều kiện tham gia được trình bày trong [thỏa thuận tiếp thị liên kết](https://bestimage.ai/affiliate-agreement/).

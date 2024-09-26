---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.11.5
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# Kỹ năng phân tích dữ liệu

Ở chương này mình sẽ giới thiệu một số kỹ thuật phân tích dữ liệu cũng như đưa ra đánh giá của cá nhân mình về
mức độ thực tiễn ứng dụng của các kỹ thuật phân tích này bao gồm:

## Descriptive analytics

Chúa tể cần thiết!
Phân tích mô tả chính là vỡ lòng của phân tích dữ liệu, hay gọi theo cách bình dân là "làm báo cáo".
Vậy báo cáo cái gì?
Thông thường trong 1 doanh nghiệp sẽ có các loại báo cáo: báo cáo kinh doanh, báo cáo tài chính, báo cáo vận hành (trong báo cáo vận hành thì tùy thuộc vào lĩnh vực kinh doanh sẽ có các loại báo cáo khác nhau). Thực tế hiện nay, các cấp quản lí đa phần vẫn quen với cách tiếp cận số liệu tổng hợp, tăng giảm theo phần trăm, drill down theo từng kênh kinh doanh, phòng ban, cá nhân,... Tuy loại báo cáo này không phức tạp nhưng thường được yêu cầu thường xuyên, nhanh và chính xác, nên cần phải có kỹ năng tốt và tận dụng các công cụ như excel để có thể thực hiện nhanh chóng.
Ngoài ra đối tượng nhận báo cáo thường là những người không có chuyên môn về dữ liệu do đó cần phải đơn giản, và đôi khi cần được bảo mật "nhẹ" bằng mật khẩu riêng cho từng người, do đó Excel là công cụ hoàn hảo để thực hiện.

## Diagnostic analytics

Adhoc report!

Sếp nhận được thông tin về một vấn đề phát sinh và yêu cầu báo cáo ngay lập tức các số liệu liên quan đến ngữ cảnh xảy ra vấn đề. Đây là kịch bản thường xuyên gặp phải. Để thực hiện tốt loại báo cáo này, Power BI là hoàn toàn "KHÔNG PHÙ HỢP". Không như bạn vẫn thường nghe, mặc dù BI hỗ trợ tốt giao diện trực quan, thao tác kéo thả khá đơn giản, tuy nhiên việc kéo thả để tìm hiểu một vấn đề phức tạp, có nhiều yếu tố sẽ là thảm họa nếu như bạn không nắm chắc Data Model và Context của báo cáo Power BI. Trong trường hợp này, hãy sử dụng Python!

Một sự chuẩn bị tốt với nguồn dữ liệu được kết nối tự động và các phép tính được modul hóa một cách logic sẽ giúp bạn nhanh chóng tìm ra nguyên nhân của vấn đề thông qua các chỉ số, biểu đồ bằng các câu lệnh loop và function quan các tác nhân nghi ngờ một cách nhanh chóng.
## Forecast

Khả năng dự báo, tất nhiên là một phần nâng cao của phân tích dữ liệu và Python là công cụ không thể tốt hơn cho bạn!

Các bài viết trong series này sẽ lần lượt chia sẻ cho bạn vì sao mình đưa ra nhận định trên và mình đã làm thế nào?
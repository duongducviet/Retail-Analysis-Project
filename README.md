**1. Tổng quan dự án**

\- Dự án được thực hiện trên bộ dữ liệu bán lẻ giả lập, nhằm vận dụng các kiến thức và kỹ năng đã học vào một quy trình phân tích dữ liệu hoàn chỉnh.

\- Dự án tập trung phân tích hiệu quả hoạt động kinh doanh của một doanh nghiệp bán lẻ trong khoảng thời gian 1 năm. Mục tiêu của dự án là đánh giá tình hình doanh thu, hiệu suất sản phẩm, hành vi khách hàng và hiệu quả marketing, từ đó xác định xu hướng kinh doanh, những điểm bất thường và cơ hội cải thiện hiệu quả hoạt động.

\- Dự án được thực hiện theo quy trình phân tích dữ liệu từ làm sạch dữ liệu, xây dựng mô hình dữ liệu, phát triển KPI, chỉ số, thiết kế dashboard đến phân tích insight và đề xuất giải pháp kinh doanh.

**2. Mục tiêu phân tích**

\- Đánh giá hiệu quả kinh doanh tổng thể thông qua các chỉ số KPI.

\- Phân tích xu hướng doanh thu và đơn hàng theo thời gian.

\- Xác định các ngành hàng và sản phẩm có hiệu suất cao, thấp.

\- Phân tích phân khúc khách hàng và hành vi chi tiêu

\- Đánh giá hiệu quả marketing funnel và chi phí quảng cáo.

\- Đưa ra các đề xuất nhằm hỗ trợ cải thiện hiệu quả kinh doanh và ra quyết định.

**3. Công cụ sử dụng**

|**Công cụ**|**Mục đích sử dụng**|
| :- | :- |
|Power BI|Xây dựng dashboard và trực quan hóa dữ liệu|
|Power Query|Làm sạch, biến đổi và chuẩn bị dữ liệu|
|DAX|Xây dựng KPI và các phép tính phục vụ phân tích|
|Data Modeling|Thiết kế mô hình dữ liệu và các mối quan hệ giữa bảng|
|Canva|Trình bày báo cáo và Data Storytelling|
|Analysis|Phân tích hiệu suất, xác định insight và đề xuất giải pháp|

**4. Dataset**

Dataset bao gồm các bảng dữ liệu mô phỏng hoạt động kinh doanh bán lẻ, phục vụ phân tích giao dịch, khách hàng, sản phẩm, khu vực bán hàng và thời gian.

|**Bảng dữ liệu**|**Nội dung**|
| :- | :- |
|Sales|Thông tin giao dịch, đơn hàng, số lượng, doanh thu, trạng thái,…|
|Products|Thông tin sản phẩm, mã số, danh mục và giá bán|
|Products|Thông tin khách hàng, độ tuổi, phân khúc và khu vực|
|Marketing Funnel|Thông tin về marketing, chiến dịch, thời gian và các KPI liên quan|
|DimDate|Bảng tự thêm; bổ sung dữ liệu về ngày tháng phục vụ phân tích xu hướng theo thời gian|

**5. Quy trình thực hiện**

Dự án được triển khai theo các giai đoạn:

*Bước 1: Làm sạch và chuẩn bị dữ liệu*

\- Kiểm tra chất lượng và cấu trúc dữ liệu, rà soát các giá trị thiếu 

\- Chuẩn hóa kiểu dữ liệu bằng Power Query

*Bước 2: Xây dựng mô hình dữ liệu*

\- Phân tách và tổ chức dữ liệu theo mô hình Star Schema

\- Thiết lập mối quan hệ một – nhiều giữa các bảng Dimension - Fact

*Bước 3: Xây dựng KPI bằng DAX*

Phát triển các chỉ số phục vụ đánh giá hiệu suất kinh doanh như doanh thu, lợi nhuận gộp, AOV, tỷ lệ chuyển đổi và các chỉ số liên quan.

*Bước 4: Thiết kế Dashboard*

Xây dựng dashboard tương tác gồm 4 trang:** Overview, Product, Customer, Marketing Funnel

*Bước 5: Phân tích kinh doanh và đề xuất giải pháp*

\- Đánh giá xu hướng tăng trưởng theo mùa vụ, cơ cấu đóng góp theo ngành hàng và khu vực địa lý.

\- Nhận diện các điểm nghẽn, điểm bất thường và đề xuất một số giải pháp kinh doanh

**6. Tổng quan Dashboard**

Dashboard được chia thành 4 phần phân tích chính:

*- Tổng quan kinh doanh:*** Theo dõi các chỉ số kinh doanh chính, xu hướng doanh thu theo thời gian, cơ cấu doanh thu theo ngành hàng và khu vực địa lý.

*- Product Analysis:*** Đánh giá số lượng sản phẩm bán ra, hiệu suất ngành hàng, lợi nhuận trung bình trên mỗi sản phẩm và xu hướng biên lợi nhuận gộp.

*- Phân tích khách hàng:* Phân tích phân hạng khách hàng, doanh thu trung bình mỗi khách hàng, mức độ đóng góp doanh thu và các nguồn thu hút khách hàng.

*- Phân tích Marketing Funnel:*** Theo dõi hành trình khách hàng từ truy cập, thêm sản phẩm vào giỏ hàng đến thanh toán; đánh giá tỷ lệ chuyển đổi, chi phí quảng cáo và hiệu quả các chiến dịch marketing.

**7. Các phát hiện kinh doanh chính**

\- Fashion và Home & Living chiếm 60,29% tổng doanh thu, cho thấy vai trò quan trọng của hai ngành hàng này trong cơ cấu kinh doanh.

\- Doanh thu và số lượng đơn hàng tăng mạnh vào giai đoạn cuối năm, đặc biệt trong tháng 11–12.

\- Nhóm Gold có doanh thu trung bình trên khách hàng thấp hơn Standard và Silver mặc dù là phân khúc cao hơn

\- Chi phí quảng cáo chiếm tỷ trọng lớn so với lợi nhuận gộp, tiềm ẩn nguy cơ rủi ro tài chính lớn

\- Các chiến dịch như Social Ads, Search Ads tiêu tốn ngân sách lớn nhưng hiệu quả thấp hơn hẳn so với các chiến dịch khác sử dụng ít ngân sách hơn.

**8. Các giải pháp đề xuất**

**-** Duy trì hiệu quả các ngành hàng chủ lực, đồng thời đánh giá cơ hội tăng trưởng ở các danh mục có tỷ trọng thấp.

\- Chủ động chuẩn bị tồn kho, ngân sách marketing và nguồn lực cho mùa cao điểm cuối năm.

\- Rà soát chính sách phân hạng và chăm sóc khách hàng Gold nhằm cải thiện mức chi tiêu.	

\- Thử nghiệm chương trình giới thiệu khách hàng để mở rộng tệp khách hàng mới.

\- Cắt giảm một phần ngân sách từ các chiến dịch có hiệu suất thấp sang những chiến dịch có hiệu suất cao hơn.

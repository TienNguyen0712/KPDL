## **Giới thiệu về mô hình CRISP-DM trong Data Mining (Khai phá dữ liệu)**
### *I. Khái niệm*
Mô hình CRISP-DM (Cross Industry Standard Process for Data Mining) được xem là chuẩn mực quy tắc chung trong các công việc Khai Phá Dữ liệu bất kể ở quy mô hay nghành nghề nào. Cung cấp toàn bộ phương pháp và quy trình cho một vòng dời của khai phá dữ liệu. Cung cấp cái nhìn tổng quát về vòng đời của công việc data mining 
Các bước chính trong CRISP-DM và vòng đời của Data Mining:

<div align="center">
  <img src="https://github.com/user-attachments/assets/1b6d1143-b7d1-4ebd-893e-bd26ec40a8fc"  width="700"/>
</div>


### *II. Các bước được sử dụng trong CRISP-DM*
#### *1.	Business Understanding (Hiểu doanh nghiệp)*
* Đặt đúng về để của doanh nghiệp, định hướng mục tiêu và vấn đề cần giải quyết của doanh nghiệp
```
Business Objectives (Xác định đối tượng doanh nghiệp) -> Situation (Mục tieu) -> Datamining goals (Mục tiêu khai phá) -> Project plan (Kế hoạch dự án)
```
#### *2.	Data Understanding (Hiểu dữ liệu)*
* Tìm điểm chung của dữ liệu, truy cập và khám phá dữ liệu hợp với vấn đề của doanh nghiệp
```
Collect (Thu thập) -> Describe (Diễn tả) -> Explore (Khám phá) -> Data Quality (Đảm bảo chất lượng dữ liệu)
```
#### *3.	Data Preparation (Chuẩn bị dữ liệu)*
* Chuẩn bị dữ liệu để có thể train mô hình
```
Selection (Lựa chọn) -> Cleaning (Làm sạch) -> Construcrion (Đánh giá) - >Intergrate Data (Loại bỏ khoảng trắng) -> Format data (Đặt data vào chung một format)
```
#### *4.	Modeling (Xây dựng mô hình)*
* Xây dựng và truy cập vào mô hình khác nhau theo nhiều phương pháp khác nhau
```
Modelling teachnique (Lựa chọn kỹ thuật) - >Test design (Thiết kế tập test) -> Build (Dựng model) -> Asses (Dùng dữ liệu đã chuẩn bị để train )
```
#### *5.	Evaluation Model (Đánh giá mô hình)*
* Đánh giá và lựa chọn mô hình nào phù hợp nhất đối với doanh nghiệp và việc cần làm tiếp theo
``
Evaluate (Đánh giá kết quả) -> Review (Tóm tắt quá trình) -> Next steps (Xác định bước tiếp theo)
``
#### *6.	Deployment (Ứng dụng)*
* Bước cuối cùng của vòng đời thực hiện việc sử dụng các insights đạt được trong khai phá để cải thiện 
```
Deployment (Ứng dụng) -> Monitoring and maintenance (Giám sát) -> Final report (Báo cái cuối cùng) -> Review (Tóm tắt đánh giá sơ bộ)
```

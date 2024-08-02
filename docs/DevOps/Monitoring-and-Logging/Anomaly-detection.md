
---

# Khám phá thế giới ẩn giấu của các bất thường: Các phương pháp thống kê, học máy và học sâu để xử lý các giá trị ngoại lệ của dữ liệu Từ lỗi đến gian lận: Cách phát hiện bất thường giúp khám phá những điều không nhìn thấy và bất thường trong dữ liệu của bạn Đánh dấu những điều kỳ lạ: Đi sâu vào các kỹ thuật và thuật toán phát hiện bất thường Phát hiện bất thường trong dữ liệu một cách tận mắt: Hướng dẫn trực quan về các phương pháp thống kê, học máy và học sâu

- Published: July 31, 2024
- Author: Vietnamese Online Voice
- Categories: DevOps / **Monitoring and Logging**
- #DataScience #DataAnalytics #Outliers #DataPoints #FraudDetection #StatisticalMethods #ZScoreMethod #ModifiedZScoreMethod #MachineLearning #ClusteringAlgorithms #KMeansClustering #ClassificationAlgorithms #OneClassSVM #DeepLearning #NeuralNetworks #DataRepresentation #AnomalyFlagging

"Trong video này, chủ đề phát hiện bất thường được giới thiệu, bao gồm việc xác định các điểm dữ liệu bất thường hoặc bất thường trong một tập dữ liệu. Các điểm dữ liệu này, được gọi là bất thường hoặc giá trị ngoại lệ, có thể báo hiệu lỗi trong quá trình thu thập dữ liệu, hành vi bất thường hoặc thậm chí là hoạt động gian lận. Các thuật toán phát hiện bất thường được chia thành ba loại: phương pháp thống kê, kỹ thuật học máy và phương pháp học sâu. Phương pháp điểm Z và phương pháp điểm Z đã sửa đổi được thảo luận như các ví dụ về phương pháp thống kê để phát hiện bất thường. Phương pháp điểm Z tính toán số độ lệch chuẩn của một điểm dữ liệu so với giá trị trung bình, trong khi phương pháp điểm Z đã sửa đổi sử dụng trung vị và độ lệch tuyệt đối trung vị. Các nhà nghiên cứu có thể tìm thấy hướng dẫn video chi tiết bên dưới."


## ANOMALY DETECTION

Phát hiện bất thường là quá trình xác định các điểm dữ liệu bất thường hoặc bất thường trong một tập dữ liệu. Các điểm dữ liệu này, còn được gọi là bất thường hoặc "giá trị ngoại lệ" (outliers), có thể chỉ ra lỗi trong quá trình thu thập dữ liệu, "hành vi bất thường" (unusual behavior) hoặc thậm chí là "hoạt động gian lận" (fraudulent activity).
![ANOMALY DETECTION](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-07-31/transition-392357772-Montserrat-Black-9C27B0.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-6796335898.mp3" type="audio/mpeg">
</audio>



## STATISTICAL METHODS

"Thuật toán" phát hiện dị thường (algorithms) có thể được phân loại thành ba loại: "phương pháp thống kê" (statistical methods), kỹ thuật học máy và phương pháp học sâu. Các phương pháp thống kê dựa vào "mô hình thống kê" (statistical models) để xác định "điểm dữ liệu" (data points) "khác biệt đáng kể" (deviate significantly) so với "chuẩn mực" (norm). Các kỹ thuật học máy tận dụng "mẫu" (patterns) và "mối quan hệ" (relationships) trong dữ liệu để phát hiện dị thường. Mặt khác, các phương pháp học sâu sử dụng "mạng nơ-ron" (neural networks) để học "các biểu diễn phức tạp" (complex representations) của dữ liệu và xác định các điểm bất thường dựa trên các biểu diễn này.
![STATISTICAL METHODS](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-07-31/transition--19806133456-Montserrat-Thin-4A148C.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-33293734015.mp3" type="audio/mpeg">
</audio>



## STATISTICAL METHOD

Một "phương pháp thống kê" phổ biến (statistical method) để phát hiện "dị thường" (anomaly) là phương pháp Z-score. Phương pháp này tính toán số "độ lệch chuẩn" (standard deviations) một "điểm dữ liệu" (data point) là từ "trung bình" (mean) và đánh dấu bất kỳ điểm dữ liệu nào nằm ngoài một "ngưỡng" nhất định (threshold) là một dị thường. Một phương pháp thống kê khác là phương pháp Z-score đã sửa đổi, sử dụng "trung vị" (median) và độ lệch tuyệt đối trung vị thay vì trung bình và độ lệch chuẩn.
![STATISTICAL METHOD](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-07-31/transition-73949711598-Montserrat-Medium-303F9F.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-54953510595.mp3" type="audio/mpeg">
</audio>



## ANOMALY

Các kỹ thuật học máy để "phát hiện dị thường" (anomaly detection) bao gồm "thuật toán phân cụm" (clustering algorithms), chẳng hạn như phân cụm K-means và các thuật toán phân loại, chẳng hạn như One-Class SVM. Các thuật toán phân cụm nhóm các điểm dữ liệu tương tự lại với nhau và "đánh dấu các điểm dữ liệu" (flag data points) không thuộc bất kỳ cụm nào là dị thường. Mặt khác, các thuật toán phân loại "học một mô hình" (learn a model) của "dữ liệu bình thường" (normal data) và "đánh dấu bất kỳ điểm dữ liệu nào" (flag any data point) không phù hợp với mô hình này là dị thường.
![ANOMALY](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-07-31/transition-19887328684-Montserrat-ExtraBold-004895.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-6730855833.mp3" type="audio/mpeg">
</audio>



## AUTOENCODERS

Các phương pháp học sâu để "phát hiện dị thường" (anomaly detection) bao gồm "autoencoders" (autoencoders) và mạng đối nghịch tạo sinh (GAN). Autoencoders là "mạng nơ-ron" (neural networks) học "biểu diễn nhỏ gọn" (compact representation) của "dữ liệu đầu vào" (input data) và "tái tạo" (reconstruct) dữ liệu đầu vào từ biểu diễn này. Bất kỳ "điểm dữ liệu" nào (data point) không thể tái tạo chính xác đều được đánh dấu là dị thường. Mặt khác, GAN bao gồm hai mạng nơ-ron: "generator" (generator) và "discriminator" (discriminator). Máy phát điện học cách tạo ra dữ liệu giống với dữ liệu đầu vào,
![AUTOENCODERS](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-07-31/transition--45029730037-Montserrat-ExtraBold-512DA8.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-31583879055.mp3" type="audio/mpeg">
</audio>


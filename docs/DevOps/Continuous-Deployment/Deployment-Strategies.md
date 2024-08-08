
---

# Giải thích về Chiến lược triển khai: Từ Big Bang đến Canary

- Published: August 8, 2024
- Author: Vietnamese Online Voice
- Categories: DevOps / **Continuous Deployment**
- #BigBangDeployment #RolloutDeployment #RollingUpdateDeployment #BlueGreenDeployment #CanaryDeployment #SoftwareDevelopment #SDevOps #ITOperations #MinimizingDowntime #GradualDeployment #IncrementalDeployment #HighRiskDeployment #LowerRiskDeployment #DeploymentBestPractices #DeploymentStrategyConsiderations #ApplicationRequirements #Infrastructure #DeploymentSuccess

"Trong video này, diễn giả giới thiệu các chiến lược triển khai cho các ứng dụng phần mềm. Chiến lược đầu tiên được thảo luận là Big Bang Deployment, trong đó toàn bộ ứng dụng được triển khai đồng thời, đơn giản nhưng có rủi ro như thời gian chết và lỗi. Chiến lược thứ hai là Rollout Deployment, bao gồm triển khai gia tăng các phần khác nhau của ứng dụng, giảm rủi ro lỗi. Chiến lược thứ ba là Rolling Update Deployment, trong đó ứng dụng được cập nhật theo trình tự các lần triển khai nhỏ, giảm thiểu thời gian chết và cho phép khôi phục dễ dàng. Các nhà nghiên cứu có thể xem hướng dẫn video chi tiết bên dưới."


## MINIMAL DEPENDENCIES

Loại chiến lược triển khai đầu tiên là Big Bang Deployment, trong đó toàn bộ ứng dụng được triển khai cùng một lúc. Mặc dù cách tiếp cận này đơn giản và dễ hiểu, nhưng nó có những rủi ro đáng kể như "thời gian chết" (downtime) và "lỗi" (bugs). Nó thường được sử dụng cho "các ứng dụng nhỏ" (small applications) với "sự phụ thuộc tối thiểu" (minimal dependencies).
![MINIMAL DEPENDENCIES](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-08/transition-34943270592-Montserrat-Thin-880E4F.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-15806508838.mp3" type="audio/mpeg">
</audio>



## INCREMENTALLY DEPLOYING

Chiến lược thứ hai là Triển khai Rollout, bao gồm "triển khai gia tăng" (incrementally deploying) các phần khác nhau của ứng dụng, chẳng hạn như "tính năng" (features) hoặc "dịch vụ" (services). Cách tiếp cận này cho phép "phơi bày dần dần" (gradual exposure) với "mã mới" (new code), giảm "rủi ro lỗi" (risk of errors).
![INCREMENTALLY DEPLOYING](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-08/transition--15564210333-Montserrat-Thin-9C27B0.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-1625177365.mp3" type="audio/mpeg">
</audio>



## SMALL DEPLOYMENTS

Chiến lược thứ ba là Triển khai Cập nhật Lăn, trong đó ứng dụng được cập nhật theo trình tự "các đợt triển khai nhỏ" (small deployments), thay thế "các phiên bản cũ" (old instances) bằng các phiên bản mới. Cách tiếp cận này giảm thiểu "thời gian chết" (downtime) và cho phép "hoàn nguyên" dễ dàng (rollback).
![SMALL DEPLOYMENTS](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-08/transition-20713000166-Montserrat-ExtraBold-880E4F.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-22924384012.mp3" type="audio/mpeg">
</audio>



## IDENTICAL ENVIRONMENTS

Chiến lược thứ tư là Triển khai Xanh-Xanh, trong đó hai "môi trường giống hệt nhau" (identical environments) được sử dụng, một hoạt động và một không hoạt động. "Phiên bản mới" (new version) được "triển khai" (deployed) đến "môi trường không hoạt động" (inactive environment) và sau đó "chuyển nhanh" (quickly switched) sang hoạt động.
![IDENTICAL ENVIRONMENTS](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-08/transition-5263095286-Montserrat-Black-7B1FA2.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-12570951261.mp3" type="audio/mpeg">
</audio>



## DEPLOYMENT STRATEGIES

Chiến lược thứ năm là Canary Deployment, trong đó phiên bản mới của ứng dụng được triển khai cho "một nhóm nhỏ người dùng" (small subset of users) và "được giám sát" (monitored) trước khi triển khai cho "toàn bộ cơ sở người dùng" (entire user base). Mỗi chiến lược triển khai đều có bộ "lợi thế" (advantages) và "cân nhắc" (considerations) riêng. Ví dụ, triển khai Big Bang "đơn giản" (simple) nhưng "rủi ro cao" (high risk), trong khi "triển khai phức tạp" hơn (complex deployments) như Canary "có rủi ro thấp hơn" (carry lower risks) nhưng phức tạp hơn.
![DEPLOYMENT STRATEGIES](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-08/transition--47325659491-Montserrat-SemiBold-880E4F.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-948744176.mp3" type="audio/mpeg">
</audio>



## DEPLOYMENT STRATEGY

Khi chọn "chiến lược triển khai" (deployment strategy), hãy cân nhắc các "thực hành tốt nhất" sau (best practices):. Chiến lược triển khai là một phần thiết yếu của vòng đời phát triển phần mềm. Việc chọn đúng chiến lược đòi hỏi phải cân nhắc cẩn thận các yêu cầu của ứng dụng, "cơ sở hạ tầng" (infrastructure) và "rủi ro tiềm ẩn" (potential risks). Bằng cách hiểu các loại chiến lược triển khai khác nhau và "lợi thế" của chúng (advantages), chúng ta có thể đưa ra "quyết định sáng suốt" (informed decisions) và đảm bảo sự thành công của các ứng dụng của mình.
![DEPLOYMENT STRATEGY](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-08/transition--899380503-Montserrat-Black-880E4F.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-5539564614.mp3" type="audio/mpeg">
</audio>



## NEW CODE

Cảm ơn bạn đã xem video này. Tôi hy vọng bạn thấy video này hữu ích và hiểu sâu hơn về "chiến lược triển khai" (deployment strategies). Nếu bạn có bất kỳ câu hỏi nào hoặc muốn chia sẻ suy nghĩ của mình, hãy thoải mái để lại bình luận bên dưới. Đừng quên đăng ký kênh của chúng tôi để nhận thông báo về các video mới của chúng tôi. Hẹn gặp lại các bạn vào lần sau, đây chính là Kỷ nguyên số. Hãy tiếp tục sáng tạo, tiếp tục đổi mới và tiếp tục triển khai!
![NEW CODE](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-08/transition--20844001729-Montserrat-Black-7B1FA2.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-14057470165.mp3" type="audio/mpeg">
</audio>


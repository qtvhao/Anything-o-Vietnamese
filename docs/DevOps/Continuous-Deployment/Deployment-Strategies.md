
---

# "\[Độc quyền\]: Nắm vững các chiến lược triển khai như một chuyên gia - Xanh lam-Xanh lục, Canary, Lăn và nhiều hơn nữa! \"

- Published: July 29, 2024
- Author: Vietnamese Online Voice
- Categories: DevOps / **Continuous Deployment**
- #SoftwareDeployment #ZeroDowntimeDeployments #BlueGreenDeployment #CanaryDeployment #RollingDeployment #ShadowDeployment #ABTesting #IdleEnvironment #NewSoftware #Updates #TestThoroughly #CatchIssues #RollBackDeployment #AffectUserBase #GradualRollout #GatherFeedback #DiverseUserBase

"Video này trình bày năm chiến lược triển khai: blue-green, canary, rolling, shadow và thử nghiệm A/B. Triển khai blue-green liên quan đến việc chuyển lưu lượng sang môi trường mới sau khi thử nghiệm kỹ lưỡng. Triển khai Canary triển khai dần dần các tính năng mới cho một nhóm người dùng. Triển khai rolling cập nhật từng máy chủ một, cho phép không có thời gian chết. Triển khai shadow chạy phần mềm mới song song với hệ thống trực tiếp. Thử nghiệm A/B so sánh hai phiên bản để xác định sở thích của người dùng. Các chiến lược này cho phép các tổ chức đảm bảo triển khai phần mềm suôn sẻ và giảm thiểu các sự cố tiềm ẩn."


## DEPLOYMENT STRATEGIES

Chiến lược triển khai rất quan trọng đối với bất kỳ tổ chức nào muốn đảm bảo triển khai phần mềm hoặc bản cập nhật mới một cách suôn sẻ và thành công. Trong video này, chúng tôi sẽ đề cập đến năm "chiến lược triển khai" phổ biến (deployment strategies): triển khai xanh lam-xanh lục, "triển khai canary" (canary deployment), "triển khai liên tục" (rolling deployment), "triển khai ẩn" (shadow deployment) và thử nghiệm A/B.
![DEPLOYMENT STRATEGIES](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-07-29/transition-17522877131-Montserrat-Medium-004895.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-23348468792.mp3" type="audio/mpeg">
</audio>



## NEW ENVIRONMENT

Để "triển khai" (deploy) phiên bản mới của ứng dụng, trước tiên bạn sẽ triển khai nó đến "môi trường nhàn rỗi" (idle environment), "kiểm tra" (test) nó "hoàn toàn" (thoroughly), và sau đó "chuyển lưu lượng" (switch traffic over) đến "môi trường mới" (new environment). Điều này cho phép triển khai không có thời gian chết, vì luôn có một "môi trường trực tiếp" (live environment) có sẵn để phục vụ lưu lượng.
![NEW ENVIRONMENT](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-07-29/transition-2840911967-Montserrat-Thin-004895.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-23515916274.mp3" type="audio/mpeg">
</audio>



## CANARY DEPLOYMENT

Điều này cho phép bạn phát hiện sớm mọi sự cố và "quay lại" (roll back) việc triển khai nếu cần, mà không "ảnh hưởng" (affecting) toàn bộ "cơ sở người dùng" (user base). Triển khai Canary có thể đặc biệt hữu ích cho các tổ chức có cơ sở người dùng lớn và đa dạng, vì chúng cho phép bạn "triển khai dần dần" (gradually roll out) các tính năng mới và "thu thập phản hồi" (gather feedback) từ "mẫu đại diện" (representative sample) người dùng.
![CANARY DEPLOYMENT](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-07-29/transition--26420595717-Montserrat-ExtraBold-1A237E.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-14178716140.mp3" type="audio/mpeg">
</audio>



## ROLLING DEPLOYMENTS

Điều này cho phép bạn "triển khai các phiên bản mới" (deploy new versions) của ứng dụng với "thời gian ngừng hoạt động" tối thiểu (downtime), vì luôn có một phần của "đội máy chủ" (server fleet) có sẵn để phục vụ lưu lượng truy cập. Triển khai liên tục có thể đặc biệt hữu ích cho "các tổ chức" (organizations) có cơ sở hạ tầng máy chủ lớn và phức tạp, vì chúng cho phép bạn triển khai các phiên bản mới của ứng dụng theo cách "có kiểm soát" (controlled) và "dần dần" (gradual manner).
![ROLLING DEPLOYMENTS](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-07-29/transition-4358938660-Montserrat-Thin-7B1FA2.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-52140292267.mp3" type="audio/mpeg">
</audio>


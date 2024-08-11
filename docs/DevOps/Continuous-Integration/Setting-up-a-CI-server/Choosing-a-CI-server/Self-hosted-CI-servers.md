
---

# Kiểm soát mã của bạn: Hướng dẫn về máy chủ CI tự lưu trữ

- Published: August 9, 2024
- Author: Vietnamese Online Voice
- Categories: DevOps / Continuous Integration / Setting up a CI server / **Choosing a CI server**
- #SelfHostedCI #CIServer #SoftwareDevelopment #Git #AutomatedTesting #DevOps #Jenkins #TravisCI #TeamCity #Security #Customization #CostEffective #Flexibility #ContinuousDeployment #ContinuousMonitoring #CodeChanges #VersionControl #OpenSource #Plugins #CommercialServer #EaseOfUse #Scalability #DataControl #ImproveSoftwareDevelopment #AutomateTesting #OrganizationControl #DevProjects #SmallTeams #ExploreCIServers #ComparingServers #SettingUpCI #LearnDevOps #IncreasedAdoption #ConsiderCIOptions

"Trong video này, diễn giả giới thiệu về Tích hợp liên tục (CI), một hoạt động thiết yếu trong phát triển phần mềm hiện đại giúp tự động hóa việc kiểm thử và tích hợp mã. Quy trình CI bao gồm việc đưa mã mới vào hệ thống kiểm soát phiên bản, tự động xây dựng và kiểm thử mã, cũng như phản hồi về kết quả kiểm thử. Mặc dù có sẵn các dịch vụ CI dựa trên đám mây, nhưng máy chủ CI tự lưu trữ mang lại những lợi ích như bảo mật, kiểm soát, tùy chỉnh, hiệu quả về chi phí và tính linh hoạt. Các nhà nghiên cứu có thể xem hướng dẫn chi tiết trong video."


## AUTOMATED TESTS

[Vui vẻ, tràn đầy năng lượng] Trong thế giới phát triển phần mềm với nhịp độ nhanh như hiện nay, điều cần thiết là đảm bảo rằng các thay đổi mã của chúng ta được kiểm tra và tích hợp thường xuyên. Tích hợp liên tục (CI) là một hoạt động tự động hóa quy trình này, biến nó thành một phần thiết yếu của phát triển phần mềm hiện đại.
![AUTOMATED TESTS](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-09/transition-29195402223-Montserrat-Bold-004895.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-4327762968.mp3" type="audio/mpeg">
</audio>



## CI PROCESS

[Thông tin] Quy trình CI bao gồm một số bước. Nhà phát triển đẩy mã mới đến "hệ thống kiểm soát phiên bản" (version control system), như Git. Máy chủ CI tự động xây dựng mã và chạy "kiểm tra tự động" (automated tests) để xác minh. Sau đó, máy chủ CI cung cấp "phản hồi" (feedback) về kết quả kiểm tra, nêu bật bất kỳ vấn đề hoặc lỗi nào.
![CI PROCESS](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-09/transition-2716159360-Montserrat-ExtraBold-004895.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-8969243873.mp3" type="audio/mpeg">
</audio>



## SELF-HOSTED CI SERVERS

[Khẳng định] Khi nói đến máy chủ CI, có nhiều dịch vụ dựa trên đám mây khả dụng. Tuy nhiên, một số "tổ chức" (organization) chọn tự lưu trữ máy chủ CI, nghĩa là tổ chức "lưu trữ và quản lý" (hosts and manages) máy chủ "nội bộ" (internally). Các lợi ích của máy chủ CI tự lưu trữ bao gồm "bảo mật" (security) và khả năng kiểm soát, tùy chỉnh, hiệu quả về chi phí và tính linh hoạt.
![SELF-HOSTED CI SERVERS](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-09/transition--10893988052-Montserrat-SemiBold-1A237E.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-5912006814.mp3" type="audio/mpeg">
</audio>



## CI SERVER

[Háo hức] Một số máy chủ CI tự lưu trữ phổ biến bao gồm Jenkins, một máy chủ nguồn mở có cộng đồng người dùng lớn và nhiều "plugin" (plugins); Travis CI, một tùy chọn phổ biến trong các dự án nguồn mở và doanh nghiệp vừa và nhỏ; và TeamCity, một máy chủ "thương mại" (commercial) được biết đến với "tính dễ sử dụng" (ease of use) và khả năng mở rộng.
![CI SERVER](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-09/transition--6393620769-Montserrat-Medium-4A148C.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-19583356268.mp3" type="audio/mpeg">
</audio>



## CI

[Thuyết phục" (ci)] Với việc "áp dụng" (adoption) ngày càng tăng của các máy chủ CI tự lưu trữ, điều quan trọng là "các nhà phát triển" (developers) phải hiểu "các khái niệm" (concepts) về CI và máy chủ CI tự lưu trữ, và cân nhắc các tùy chọn này khi "lựa chọn" (choosing) một giải pháp CI cho "các dự án" (projects) của chúng tôi.
![CI](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-09/transition--18508350049-Montserrat-Thin-9C27B0.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-6674293849.mp3" type="audio/mpeg">
</audio>



## DEVOPS PRACTICES

[Hỗ trợ] Với tư cách là nhà phát triển, chúng ta có thể khám phá thêm về máy chủ CI tự lưu trữ bằng cách nghiên cứu và so sánh các máy chủ khác nhau, thiết lập máy chủ CI tự lưu trữ cho các dự án cá nhân hoặc nhóm nhỏ và tìm hiểu về các hoạt động DevOps khác, chẳng hạn như Triển khai liên tục và Giám sát liên tục.
![DEVOPS PRACTICES](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-09/transition-26029804816-Montserrat-Medium-303F9F.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-4208930500.mp3" type="audio/mpeg">
</audio>



## CUSTOMIZATION

[Khuyến khích] Tóm lại, máy chủ CI tự lưu trữ cung cấp nhiều "lợi ích" (benefits), bao gồm "bảo mật" (security), "tùy chỉnh" (customization), hiệu quả về chi phí và "linh hoạt" (flexibility). Bằng cách tự lưu trữ máy chủ CI, các tổ chức có thể đảm bảo rằng mã và dữ liệu của họ vẫn nằm trong tầm kiểm soát của họ, đồng thời cũng có sự linh hoạt để tùy chỉnh máy chủ để đáp ứng các nhu cầu cụ thể của họ. Vì vậy, nếu bạn đang muốn cải thiện quy trình phát triển phần mềm của mình, hãy cân nhắc tự lưu trữ máy chủ CI.
![CUSTOMIZATION](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-09/transition--15396503985-Montserrat-SemiBold-512DA8.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-495213053.mp3" type="audio/mpeg">
</audio>



## SOFTWARE DEVELOPMENT

Cảm ơn bạn đã xem video này. Tôi hy vọng bạn thấy video này hữu ích và hiểu sâu hơn về máy chủ CI tự lưu trữ và vai trò của chúng trong "phát triển phần mềm" (software development). Nếu bạn có bất kỳ câu hỏi nào hoặc muốn chia sẻ suy nghĩ của mình, hãy thoải mái để lại bình luận bên dưới. Đừng quên đăng ký kênh của chúng tôi để nhận "thông báo" (notifications) về các video mới của chúng tôi. Hẹn gặp lại các bạn vào lần sau, chúc các bạn lập trình vui vẻ!
![SOFTWARE DEVELOPMENT](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-09/transition--29259773124-Montserrat-Black-004895.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-24267610572.mp3" type="audio/mpeg">
</audio>


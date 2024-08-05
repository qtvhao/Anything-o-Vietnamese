
---

# Mercurial 101: Các lệnh và khái niệm thiết yếu

- Published: August 2, 2024
- Author: Vietnamese Online Voice
- Categories: DevOps / Version Control / **Mercurial**
- #VersionControl #DistributedVersionControl #Developers #Codebase #Changes #Workflows #Git #KeyConcepts #MercurialCommands #hginit #Repository #hgadd #hgcommit #CommitMessage #hglog #History #hgupdate #Revision #HTML #Project #Website #Branching #CodebaseManagement #DeveloperTools #OpenSource #Programming #TechTips #TechTutorial #VersionControlSystem #Productivity #Collaboration #DeveloperWorkflow #Coding #ProgrammingTutorial #SoftwareDevelopment #MercurialBasics #LearnMercurial #MercurialTutorial #NewRepository #FileAddition #ChangesCommitting #VersionControlHistory #WorkingCopyUpdate #CodebaseVersionControl #HgLogCommand #HgUpdateCommand #MeaningfulCommitMessages #BranchingCodebase #NewFeatures #BugFixes

"Trong video này, người thuyết trình giới thiệu Mercurial, một hệ thống kiểm soát phiên bản phân tán để quản lý các thay đổi đối với cơ sở mã. Tương tự như Git, Mercurial cung cấp các tính năng và quy trình làm việc riêng biệt. Các khái niệm chính bao gồm kho lưu trữ, tập thay đổi và sao chép. Các lệnh thiết yếu bao gồm hg init để tạo kho lưu trữ, hg add để thêm tệp và hg commit để lưu các thay đổi với các thông báo mô tả."


## MERCURIAL

Vậy Mercurial chính xác là gì? Mercurial là một hệ thống kiểm soát phiên bản phân tán giúp các nhóm nhà phát triển theo dõi các thay đổi được thực hiện đối với cơ sở mã của họ theo thời gian. Nó tương tự như các hệ thống kiểm soát phiên bản khác như Git, nhưng có một bộ tính năng và quy trình làm việc hơi khác một chút.
![MERCURIAL](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-02/transition--12846803131-Montserrat-Thin-4A148C.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-13334706089.mp3" type="audio/mpeg">
</audio>



## MERCURIAL BASICS

Trước khi đi sâu vào chi tiết về Mercurial, chúng ta hãy cùng tìm hiểu một số "khái niệm chính" (key concepts) quan trọng cần hiểu:. Bây giờ chúng ta đã tìm hiểu một số khái niệm chính, chúng ta hãy cùng tìm hiểu một số lệnh Mercurial thiết yếu. Lệnh đầu tiên bạn cần biết là "hg init" (hg init) để khởi tạo một "kho lưu trữ" Mercurial mới (repository) trong "thư mục" hiện tại của bạn (directory).
![MERCURIAL BASICS](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-02/transition--3096001231-Montserrat-SemiBold-9C27B0.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-33912495010.mp3" type="audio/mpeg">
</audio>



## HG ADD COMMAND

Sau khi bạn đã "khởi tạo" (initialize)d "kho lưu trữ" (repository), bạn có thể thêm các tệp mới vào đó bằng cách sử dụng "lệnh hg add" (hg add command).. Tiếp theo, chúng ta có "lệnh hg commit" (hg commit command), cho phép bạn lưu các thay đổi vào kho lưu trữ của mình. Hãy đảm bảo bao gồm một "thông báo cam kết" có ý nghĩa (commit message) để mô tả các thay đổi của bạn.
![HG ADD COMMAND](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-02/transition--7414287423-Montserrat-Regular-9C27B0.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-16254517063.mp3" type="audio/mpeg">
</audio>



## MERCURIAL COMMANDS

Bạn có thể xem lịch sử của tất cả "changeset" (changesets) trong "repository" (repository) của bạn bằng cách sử dụng "lệnh hg log" (hg log command).. Và cuối cùng, bạn có thể cập nhật "bản sao làm việc" (working copy) của mình thành "bản sửa đổi cụ thể" (specific revision) bằng cách sử dụng "lệnh hg update" (hg update command).. Giả sử chúng ta đang làm việc trên một "dự án" đơn giản (project) để tạo một trang web. Chúng ta sẽ sử dụng Mercurial để theo dõi các thay đổi của mình.
![MERCURIAL COMMANDS](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-02/transition-23544507590-Montserrat-Thin-1A237E.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-29163427231.mp3" type="audio/mpeg">
</audio>



## REPOSITORY

Đầu tiên, chúng ta khởi tạo một "kho lưu trữ" mới (repository) bằng cách sử dụng "hg init" (hg init). Tiếp theo, chúng ta sẽ tạo một "tệp" mới (file) có tên là "index.html" (index.html) và thêm nó vào kho lưu trữ của chúng ta bằng cách sử dụng "hg add" (hg add) index.html.. Chúng ta sẽ thực hiện một số "thay đổi" (changes) vào tệp của mình và cam kết chúng bằng cách sử dụng "hg commit" (hg commit) -m "Đã thêm tệp HTML ban đầu".
![REPOSITORY](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-02/transition-214218375-Montserrat-Medium-1A237E.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-40986342404.mp3" type="audio/mpeg">
</audio>



## HG UPDATE

Chúng ta có thể xem lịch sử "changeset" (changeset) của mình bằng cách sử dụng "hg log" (hg log).. Nếu muốn quay lại phiên bản trước của tệp, chúng ta có thể sử dụng "hg update" (hg update) để cập nhật "bản sao làm việc" (working copy) của mình thành "bản sửa đổi cụ thể" (specific revision).. Hãy nhớ luôn "cam kết" (commit) "thay đổi thường xuyên" (changes regularly) của bạn, thay vì đợi đến cuối ngày. Sử dụng các thông báo cam kết có ý nghĩa để mô tả các thay đổi của bạn và luôn "phân nhánh" (branch) "cơ sở mã" (codebase) của bạn khi làm việc trên "các tính năng mới" (new features) hoặc "sửa lỗi" (bug fixes).
![HG UPDATE](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-02/transition-38178601131-Montserrat-Black-303F9F.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-59355467012.mp3" type="audio/mpeg">
</audio>



## MERCURIAL

Và đó là phần giới thiệu cơ bản về Mercurial! Với sự luyện tập, bạn sẽ cảm thấy thoải mái hơn khi sử dụng Mercurial để quản lý "codebase" (codebase) và "hợp tác" (collaborate) với những người khác. Cảm ơn bạn đã xem video này. Tôi hy vọng bạn thấy video này hữu ích và hiểu sâu hơn về Mercurial. Nếu bạn có bất kỳ câu hỏi nào hoặc muốn chia sẻ suy nghĩ của mình, hãy thoải mái để lại bình luận bên dưới. Đừng quên đăng ký kênh của chúng tôi để nhận "thông báo" (notifications) về "video mới" (new videos) của chúng tôi. Cảm ơn bạn đã xem!
![MERCURIAL](https://http-archiver-apis-production-80.schnworks.com/storage/images/transitions/2024-08-02/transition--21155728918-Montserrat-Regular-4A148C.jpg)
<audio controls>
    <source src="https://http-archiver-apis-production-80.schnworks.com/storage/storage/audio/file-7581891193.mp3" type="audio/mpeg">
</audio>


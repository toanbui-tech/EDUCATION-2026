# LỜI NÓI ĐẦU
## Chúng ta đang nói gì khi nói về kiến trúc?

Giống như bất kỳ phép ẩn dụ nào, việc mô tả phần mềm thông qua lăng kính của kiến trúc có thể che giấu cũng nhiều như nó hé lộ. Nó vừa có thể hứa hẹn nhiều hơn những gì nó thực sự mang lại, vừa có thể mang lại nhiều hơn những gì nó hứa hẹn.

Sức hấp dẫn rõ ràng của kiến trúc là **cấu trúc**, và cấu trúc là thứ chi phối các mô hình và các cuộc thảo luận trong phát triển phần mềm:

- components
- classes
- functions
- modules
- layers
- services
- micro hay macro  

Nhưng cấu trúc tổng thể của rất nhiều hệ thống phần mềm thường khiến người ta khó mà tin nổi hoặc hiểu nổi — những mô hình doanh nghiệp kiểu Liên Xô destined trở thành di sản nặng nề, những tòa tháp Jenga chông chênh vươn lên đám mây, những tầng lớp khảo cổ chôn vùi trong một “quả cầu bùn lớn” đang trượt dốc.  

Không hề rõ ràng rằng cấu trúc phần mềm tuân theo trực giác của chúng ta giống như cấu trúc của các tòa nhà.

Các tòa nhà có cấu trúc vật lý hiển nhiên — dù đặt nền trên đá hay bê tông, vươn cao hay trải rộng, lớn hay nhỏ, tráng lệ hay bình thường. Cấu trúc của chúng buộc phải tuân theo các định luật vật lý của trọng lực và vật liệu xây dựng.

Ngược lại — ngoại trừ theo nghĩa nghiêm túc — phần mềm hầu như chẳng bận tâm đến trọng lực.

Và phần mềm được làm từ gì?

Không giống như các tòa nhà được tạo nên từ gạch, bê tông, gỗ, thép và kính, phần mềm được tạo nên từ **phần mềm**. Những cấu trúc phần mềm lớn được tạo từ các thành phần phần mềm nhỏ hơn, mà bản thân chúng lại được tạo từ những thành phần nhỏ hơn nữa, và cứ thế tiếp diễn.

Nói cách khác, đó là những **“con rùa lập trình” chồng lên nhau vô hạn**.

Khi nói về kiến trúc phần mềm, phần mềm mang tính **đệ quy** và **phân dạng (fractal)** về bản chất, được khắc họa và phác thảo bằng mã nguồn. Mọi thứ đều là chi tiết.

Các tầng chi tiết lồng vào nhau cũng góp phần tạo nên kiến trúc của một tòa nhà, nhưng việc nói về **quy mô vật lý** trong phần mềm lại không có nhiều ý nghĩa.

Phần mềm có cấu trúc — nhiều cấu trúc và nhiều loại cấu trúc khác nhau — nhưng sự đa dạng của nó vượt xa phạm vi các cấu trúc vật lý trong kiến trúc xây dựng.

Thậm chí, bạn có thể lập luận khá thuyết phục rằng hoạt động thiết kế và mức độ tập trung vào thiết kế trong phần mềm còn nhiều hơn trong kiến trúc xây dựng — theo nghĩa này, việc xem kiến trúc phần mềm là “mang tính kiến trúc” hơn cả kiến trúc tòa nhà cũng không phải là điều vô lý!

Nhưng **quy mô vật lý** là thứ con người hiểu và luôn tìm kiếm trong thế giới xung quanh.

Dù hấp dẫn và hiển nhiên về mặt thị giác, những chiếc hộp trên sơ đồ PowerPoint **không phải** là kiến trúc của một hệ thống phần mềm. Không nghi ngờ gì khi chúng đại diện cho một **góc nhìn cụ thể** về kiến trúc, nhưng nếu nhầm lẫn các chiếc hộp đó với bức tranh tổng thể — với chính kiến trúc — thì bạn đã bỏ lỡ cả bức tranh lớn lẫn kiến trúc thực sự:

**Kiến trúc phần mềm không trông giống bất kỳ thứ gì cụ thể.**

Một cách trực quan hóa cụ thể luôn là **một lựa chọn**, không phải điều hiển nhiên có sẵn. Và lựa chọn đó lại dựa trên nhiều lựa chọn khác nữa:

- đưa vào điều gì  
- loại bỏ điều gì  
- nhấn mạnh điều gì bằng hình dạng hoặc màu sắc  
- làm mờ điều gì bằng sự đồng nhất hoặc bằng cách lược bỏ  

Không có gì là tự nhiên hay vốn dĩ đúng khi ưu tiên một góc nhìn này hơn góc nhìn khác.

Mặc dù có thể không hợp lý khi nói về vật lý và quy mô vật lý trong kiến trúc phần mềm, chúng ta vẫn nhận thức và quan tâm đến một số **ràng buộc vật lý nhất định**.  

Tốc độ bộ xử lý và băng thông mạng có thể đưa ra phán quyết khắc nghiệt về hiệu năng của một hệ thống. Bộ nhớ và lưu trữ có thể giới hạn tham vọng của bất kỳ codebase nào. Phần mềm có thể là thứ được tạo nên từ những giấc mơ — nhưng nó vẫn chạy trong thế giới vật lý.

> *Đây là sự quái dị trong tình yêu, thưa nàng, rằng ý chí thì vô hạn nhưng việc thực hiện lại bị giam hãm; rằng khát vọng là vô biên nhưng hành động lại là nô lệ của giới hạn.*  
> — William Shakespeare

Thế giới vật lý là nơi chúng ta, các công ty của chúng ta và các nền kinh tế của chúng ta tồn tại. Điều này mang đến cho ta một thước đo khác để hiểu kiến trúc phần mềm — những lực và đại lượng ít mang tính vật lý hơn nhưng vẫn cho phép chúng ta thảo luận và suy luận.

> *Kiến trúc đại diện cho những quyết định thiết kế quan trọng định hình một hệ thống, trong đó “quan trọng” được đo bằng chi phí thay đổi.*  
> — Grady Booch

Thời gian, tiền bạc và công sức mang lại cho chúng ta cảm nhận về quy mô để phân biệt cái lớn với cái nhỏ, để tách phần mang tính kiến trúc khỏi phần còn lại. Thước đo này cũng cho ta biết cách đánh giá một kiến trúc có tốt hay không:  

Một kiến trúc tốt không chỉ đáp ứng nhu cầu của người dùng, nhà phát triển và chủ sở hữu tại một thời điểm nhất định — mà còn đáp ứng được các nhu cầu đó **theo thời gian**.

> *Nếu bạn nghĩ kiến trúc tốt là đắt đỏ, hãy thử kiến trúc tồi.*  
> — Brian Foote và Joseph Yoder

Những thay đổi mà quá trình phát triển hệ thống thường xuyên trải qua **không nên** là những thay đổi tốn kém, khó thực hiện, hay đòi hỏi các dự án riêng được quản lý chặt chẽ — thay vì chỉ đơn giản được tích hợp vào nhịp làm việc hằng ngày và hằng tuần.

Điều đó dẫn chúng ta đến một vấn đề liên quan đến vật lý không hề nhỏ: **du hành thời gian**.  

Làm sao ta biết những thay đổi điển hình đó sẽ là gì để định hình các quyết định quan trọng xoay quanh chúng? Làm sao giảm chi phí và công sức phát triển trong tương lai mà không có quả cầu pha lê hay cỗ máy thời gian?

> *Kiến trúc là những quyết định mà bạn ước mình có thể làm đúng ngay từ đầu dự án, nhưng thực tế bạn cũng không chắc có khả năng làm đúng chúng hơn bất kỳ quyết định nào khác.*  
> — Ralph Johnson

Hiểu được quá khứ vốn đã đủ khó; nắm bắt hiện tại thì mong manh; dự đoán tương lai lại càng không hề đơn giản.

Và chính tại đây, con đường bắt đầu rẽ ra theo nhiều hướng.

Con đường tối tăm nhất mang đến ý tưởng rằng kiến trúc mạnh mẽ và ổn định đến từ **quyền lực và sự cứng nhắc**. Nếu thay đổi là tốn kém, thì thay đổi sẽ bị loại bỏ — nguyên nhân của nó bị kìm hãm hoặc đẩy vào những rãnh quan liêu. Quyền lực của kiến trúc sư trở nên tuyệt đối và toàn trị, khiến kiến trúc trở thành một xã hội phản địa đàng đối với các lập trình viên và là nguồn thất vọng thường trực cho tất cả mọi người.

Một con đường khác lại nồng nặc mùi **tổng quát hóa suy đoán**. Một lộ trình đầy rẫy những phỏng đoán được mã hóa cứng, vô số tham số, những lăng mộ của code chết, và nhiều độ phức tạp ngẫu nhiên hơn mức mà bất kỳ ngân sách bảo trì nào có thể chịu đựng.

Con đường mà chúng ta quan tâm nhất là con đường **trong sạch nhất**.  

Nó thừa nhận tính mềm dẻo của phần mềm và cố gắng bảo tồn nó như một thuộc tính hạng nhất của hệ thống. Nó thừa nhận rằng chúng ta hoạt động với tri thức không đầy đủ, nhưng cũng hiểu rằng — với tư cách con người — làm việc với tri thức không đầy đủ là điều chúng ta vẫn làm, và làm rất tốt. Nó tận dụng điểm mạnh của chúng ta nhiều hơn là điểm yếu.

Chúng ta tạo ra mọi thứ và khám phá mọi thứ. Chúng ta đặt câu hỏi và tiến hành thử nghiệm.

Một kiến trúc tốt đến từ việc hiểu nó **như một hành trình hơn là một đích đến**, như một quá trình truy vấn liên tục hơn là một hiện vật bị đóng băng.


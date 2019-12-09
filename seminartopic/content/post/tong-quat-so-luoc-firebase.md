+++
author = "Ngoc Tran"
title = "Tổng quan sơ lược firebase"
date = "2019-12-09"
description = "bla bla"
tags = [
    "firebase",
]
categories = [
    "firebase",
]
archives = "2019/12"
series = ["Firebase Guide"]
+++

  Firebase là một nền tảng di động giúp bạn nhanh chóng phát triển các ứng dụng chất lượng cao, phát triển ứng dụng cho người dùng quy mô lớn và kiếm được nhiều tiền hơn. (Firebase gives you the tools to develop high-quality apps, grow your user base, and earn more money. We cover the essentials so you can monetize your business and focus on your users.)
<!--more-->

# TỔNG QUÁT FIREBASE
## **1.Định nghĩa về firebase**
Có nhiều cách hiểu về Firebase khi đứng trên các quan điểm khác nhau, sau đây là 2 định nghĩa cơ bản.

*   Firebase là một nền tảng di động giúp bạn nhanh chóng phát triển các ứng dụng chất lượng cao, phát triển ứng dụng cho người dùng quy mô lớn và kiếm được nhiều tiền hơn. (Firebase gives you the tools to develop high-quality apps, grow your user base, and earn more money. We cover the essentials so you can monetize your business and focus on your users.)
*   Firebase là một dịch vụ hệ thống backend được Google cung cấp sẵn cho ứng dụng Mobile của bạn, với Firebase bạn có thể rút ngắn thời gian phát triển, triển khai và thời gian mở rộng quy mô của ứng dụng mobile mình đang phát triển. Hỗ trợ cả 2 nền tảng Android và IOS, Firebase mạnh mẽ, đa năng, bảo mật và là dịch vụ cần thiết đầu tiên để xây dưng ứng dụng với hàng triệu người sử dụng.

## **2.Lịch sử phát triển của firebase**
Năm 2011, startup tiền thân của Firebase được thành lập, được gọi là Envolve. Nó cung cấp cho các nhà phát triển API cho phép tích hợp tính năng nhắn tin trực tuyến vào trang web của họ.

Điều thú vị là các nhà phát triển sử dụng Envolve không chỉ để làm nhắn tin trực tuyến. Họ sử dụng Envolve để đồng bộ hóa dữ liệu ứng dụng, chẳng hạn như một trạng thái game giữa các user trong thời gian thực.

Điều đó đã dẫn đến các nhà sáng lập của Envolve tách riêng hệ thống chat và kiến trúc realtime. Năm 2012, Firebase được tạo như một công ty cung cấp Backend as a Service với tính năng realtime.

Sau khi được Google mua lại năm 2014, Firebase nhanh chóng phát triển thành một nền tảng đa chức năng như ngày nay.
## **3.Sự ngon lành của firebase như thế nào ?**
Firebase'slogan:
`Firebase helps
mobile and web
app teams succeed`
Firebase đã mang lại được những điều gì như đúng slogan của nó: 
*   Xây dựng ứng dụng nhanh chóng mà không tốn thời gian, nhân lực để quản lý hệ thống và cơ sơ sở hạ tầng phía sau: Firebase cung cấp cho bạn chức năng như phân tích, cơ sở dữ liệu, báo cáo hoạt động và báo cáo các sự cố lỗi để bạn có thể dễ dàng phát triển, định hướng ứng dụng của mình vào người sử dụng nhằm đem lại các trải nghiệm tốt nhất cho họ.
*   Uy tín chất lượng đảm bảo từ Google: Firebase được google hỗ trợ và cung cấp trên nền tảng phần cứng với quy mô rộng khắp thế giới, được các tập đoàn lớn và các ưng dụng với triệu lượt sử dụng từ người dùng.
*   Quản lý cấu hình và trải nghiệm các ứng dụng của Firebase tập trung trong một giao diện website đơn giản, các ứng dụng này hoạt động độc lập nhưng liên kết dữ liệu phân tích chặt chẽ.
## **4. Tổng quan các dịch vụ mà Firebase cung cấp**
Firebase cung cấp cho chúng ta công cụ Firebase Analytics và 2 nhóm sản phẩm chính tập trung vào 2 đối tượng là:

*   Develop & test your app: phát triển và kiểm thử các ứng dụng được thiết kế.
*   Grow & engage your audience: Phân tích dữ liệu và tối ưu hóa trải nghiệm đối với người dùng.

![Atom](https://images.viblo.asia/a21cf9b4-71f6-4c5c-8636-d7733fed88b2.png)

### **4.1. Firebase Analytics**
Là một giải pháp miễn phí và phân tích không giới hạn. Quản lý hành vi người dùng và các biện pháp từ một bảng điều khiển duy nhất. Phân tích thuộc tính và hành vi của người dùng trong một bảng điều khiển đơn để đưa ra các quyết định sáng suốt về lộ trình sản phẩm của bạn. Nhận thông tin chi tiết về thời gian thực từ báo cáo hoặc xuất dữ liệu thô sự kiện của bạn tới Google BigQuery để phân tích tùy chỉnh.

![Atom](https://images.viblo.asia/059d31de-b60b-4da4-b985-b7c69f314ec5.png)

### **4.2. Nhóm công cụ Develop & test your app**
*  **Realtime Database**
    Firebase Realtime Database là một cơ sở dữ liệu NoSQL trên đám mây cho phép bạn lưu trữ và đồng bộ hóa dữ liệu giữa các user trong thời gian thực.

    Realtime Database cơ bản chỉ là một đối tượng JSON lớn mà các nhà phát triển có thể quản lý thời gian thực.
    
    ![Atom](https://images.viblo.asia/da1d70a4-20e7-498b-9146-b939e1d1864d.png)
    
    Chỉ với một API duy nhất, Realtime Database cung cấp cho ứng dụng của bạn cả giá trị hiện tại của dữ liệu và bất kì cập nhật mới nào.

    ![Atom](https://images.viblo.asia/434cd6a7-f7f4-4fae-9b48-5e810872637a.gif)

   Đồng bộ hóa thời gian thực giúp người dùng truy cập dữ liệu của họ dễ dàng từ bất kì thiết bị nào cũng như tương tác với các người dùng khác.kì cập nhật mới nào.

   Một lợi ích tuyệt vời khác của Realtime Database là nó cung cấp SDKs cho cả web và mobile, cho phép bạn xây dựng ứng dụng mà không cần server.

   Khi người dùng ngoại tuyến, Realtime Databse SDKs sử dụng local cache trên trình duyệt để lưu trữ thay đổi. Khi thiết bị online các dữ liệu đó sẽ được tự động đồng bộ hóa.

   Realtime Database cũng tích hợp với Firebase Authentication để cung cấp một tiến trình xác thực đơn giản và trực quan.
    
    
*  **Authentication**

    ![Atom](https://images.viblo.asia/44e8351d-d53b-4a70-9d06-08cd532c2ca3.png)

    Firebase Authentication cung cấp dịch vụ backend, SDKs sẵn sàng sử dụng, và các thư viện UI được làm sẵn để giúp ứng dụng của bạn xác thực người dùng.

    Thông thường, bạn phải mất cả tháng để xây dựng hệ thống xác thực và thường xuyên phải bảo trì nó. Nhưng nếu bạn sử dụng Firebase, bạn chỉ dưới 10 dòng code để xử lý mọi thứ, bao gồm cả những thao tác phức tạp như sát nhập tài khoản.

    Bạn có thể xác thực người dùng qua các phương thức như: Email, Phone number, Facebook, Google, Twitter, ...

    Sử dụng Firebase Authentication giúp dễ dang hơn cho việc xây dựng hệ thống xác thực an toàn, trong khi cũng cải thiện trải nghiệm cho người dùng.

    Firebase Authentication được phát triển bởi những người đã tạo ra Google Signin, Smart Lock và Chrome Password Manager.

*  **Cloud Firestore** 

    ![Atom](https://images.viblo.asia/b14d1b89-8e67-4c46-a714-1059b979c014.png)
  
    Lưu trữ và đồng bộ dữ liệu giữa người dùng và thiết bị – ở quy mô toàn cầu – sử dụng cơ sở dữ liệu noSQL được lưu trữ trên hạ tầng cloud. Cloud Firestore cung cấp cho bạn tính năng đồng bộ hóa trực tuyến và ngoại tuyến cùng với các truy vấn dữ liệu hiệu quả. Tích hợp với các sản phẩm Firebase khác cho phép bạn xây dựng các ứng dụng thực sự ngay cả khi kết nối internet bị gián đoạn.

*  **Cloud Functions**

    ![Atom](https://i.ytimg.com/vi/vr0Gfvp5v1A/maxresdefault.jpg)
    
     Mở rộng ứng dụng của bạn bằng mã phụ trợ tùy chỉnh mà không cần quản lý và quy mô các máy chủ của riêng bạn. Các chức năng có thể được kích hoạt bởi các sự kiện, được phát sinh ra bởi các sản phẩm Firebase, dịch vụ Google Cloud hoặc các bên thứ ba có sử dụng webhooks.

*  **Cloud Storage**  

    ![Atom](https://i.ytimg.com/vi/_tyjqozrEPY/maxresdefault.jpg)
    
    Lưu trữ và chia sẻ nội dung do người dùng tạo ra như hình ảnh, âm thanh và video với bộ nhớ đối tượng mạnh mẽ, đơn giản và tiết kiệm chi phí được xây dựng cho quy mô của Google. Các Firebase SDK cho Cloud Storage thêm tính năng bảo mật của Google để tải lên và tải tệp cho các ứng dụng Firebase của bạn, bất kể chất lượng mạng.
*  **Hosting** 

    ![Atom](https://miro.medium.com/max/650/1*EOw5uDG4wNmhkvUj0J8cTA.png)

    Đơn giản hóa lưu trữ web của bạn với các công cụ được thực hiện cụ thể cho các ứng dụng web hiện đại. Khi bạn tải lên nội dung web, chúng tôi sẽ tự động đẩy chúng đến CDN toàn cầu của chúng tôi và cung cấp cho họ chứng chỉ SSL miễn phí để người dùng của bạn có được trải nghiệm an toàn, đáng tin cậy, độ trễ thấp, dù họ ở đâu.

*  **Test Lab**

     ![Atom](https://lh3.googleusercontent.com/9PwL9rLt3dAT1A83vndUSIifA7oM9V6Lyh-vfWFwKJYUUybO8Bd4TCOwWuTA2fX1Dr0bB8WBP5kC=w240-h240)
     
    Chạy thử nghiệm tự động và tùy chỉnh cho ứng dụng của bạn trên các thiết bị ảo và vật lý do Google cung cấp. Sử dụng Firebase Test Lab trong suốt vòng đời phát triển của bạn để khám phá lỗi và sự không nhất quán để bạn có thể cung cấp một trải nghiệm tuyệt vời trên nhiều thiết bị.

*  **Performance Monitoring**

    ![Atom](https://i.ytimg.com/vi/0EHSPFvH7vk/maxresdefault.jpg)
    
    Chẩn đoán các vấn đề về hiệu suất ứng dụng xảy ra trên thiết bị của người dùng của bạn. Sử dụng dấu vết để theo dõi hiệu suất của các phần cụ thể trong ứng dụng của bạn và xem chế độ xem tổng hợp trong bảng điều khiển Firebase. Luôn cập nhật thời gian khởi động của ứng dụng và theo dõi các yêu cầu HTTP mà không cần viết bất kỳ mã nào.
    
### **4.3. Nhóm công cụ Develop & test your app**

*  **Google Analytics** 

    ![Atom](https://www.blastam.com/wp-content/uploads/ga-logo-new.png)
    
    Phân tích thuộc tính và hành vi của người dùng trong một bảng điều khiển đơn để đưa ra các quyết định sáng suốt về lộ trình sản phẩm của bạn. Nhận thông tin chi tiết về thời gian thực từ báo cáo hoặc xuất dữ liệu sự kiện thô của bạn tới Google BigQuery để phân tích tùy chỉnh.

*  **Cloud Messaging** 

     ![Atom](https://d2908q01vomqb2.cloudfront.net/632667547e7cd3e0466547863e1207a8c0c0c549/2018/04/19/FCM_GCM-1024x512.png)
     
    Gửi tin nhắn và thông báo cho người dùng qua các nền tảng Android, iOS và web một cách miễn phí. Bạn có thể gửi tin nhắn đến các thiết bị, nhóm thiết bị hoặc các chủ đề hoặc phân đoạn người dùng cụ thể. Nhắn tin đám mây Firebase (FCM) thậm chí là các ứng dụng lớn nhất, cung cấp hàng trăm tỷ thư mỗi ngày.

*  **Predictions** 

     ![Atom](https://cdn-images-1.medium.com/max/1057/1*qvNpM5iLSSMlygrq2sUPbA.png)

    Firebase Predictions áp dụng deep learning máy học với dữ liệu phân tích của bạn để tạo các nhóm người dùng năng động dựa trên hành vi dự đoán. Các nhóm người dùng này có thể được sử dụng để nhắm mục tiêu trong các sản phẩm khác như thông báo, Cấu hình từ xa và nhiều hơn nữa.

*  **Dynamic Links** 

    ![Atom](https://lh3.googleusercontent.com/rvcHbfR6UHqTXhmExLeGyLpjCjpF0bS9qBbj6TSaI7gYO1uYd9b4N_-PbleZpyqXWnqmXyNwep4=w240-h240)

    Sử dụng Liên kết động để cung cấp trải nghiệm người dùng tùy chỉnh cho iOS, Android và web. Bạn có thể sử dụng chúng để hỗ trợ web di động để thúc đẩy chuyển đổi ứng dụng gốc, người dùng chia sẻ người dùng, các chiến dịch xã hội và tiếp thị và hơn thế nữa. Dynamic Links cung cấp cho bạn các thuộc tính bạn cần để hiểu rõ hơn về tăng trưởng di động của bạn. Đây là dịch vụ thay thế goo.gl của Google.

*  **Remote Config**

    ![Atom](https://i.ytimg.com/vi/_CXXVFPO6f0/maxresdefault.jpg)
    
     Tùy chỉnh cách ứng dụng của bạn hiển thị cho mỗi người dùng. Thay đổi giao diện, triển khai các tính năng dần dần, chạy thử nghiệm A / B, cung cấp nội dung tùy chỉnh cho người dùng nhất định hoặc thực hiện các cập nhật khác mà không cần triển khai một phiên bản mới-tất cả từ bảng điều khiển Firebase. Giám sát tác động của những thay đổi của bạn và thực hiện các điều chỉnh chỉ trong vài phút.

*  **Invites** 

     ![Atom](https://i.ytimg.com/vi/LkaIJCZ_HyM/maxresdefault.jpg)

    Cho phép người dùng chia sẻ tất cả các khía cạnh của ứng dụng của bạn, từ mã giới thiệu đến nội dung yêu thích, qua email hoặc SMS. Giải pháp out-of-the-box này hoạt động với Google Analytics for Firebase, để bạn biết khi người dùng mở hoặc cài đặt một ứng dụng qua lời mời.

*  **App Indexing** 

    ![Atom](https://i.ytimg.com/vi/C35OSHlTNwA/maxresdefault.jpg)

    Thu hút lại người dùng bằng các ứng dụng đã cài đặt của họ với tích hợp Google Tìm kiếm này. Nếu người dùng có ứng dụng của bạn và họ tìm kiếm nội dung có liên quan, họ có thể khởi chạy nó trực tiếp từ kết quả. Nếu người dùng chưa có ứng dụng của bạn, một thẻ cài đặt sẽ xuất hiện khi họ tìm kiếm các ứng dụng tương tự.

*  **AdMob**

    ![Atom](https://i.ytimg.com/vi/EPKmYheOmiw/maxresdefault.jpg)

     Kiếm tiền bằng cách hiển thị quảng cáo hấp dẫn cho khán giả toàn cầu. AdMob có tất cả những gì bạn cần để thực hiện chiến lược kiếm tiền trên lớp bậc nhất và để tối đa hóa doanh thu do mỗi người dùng tạo ra. Nó có thể được điều chỉnh cho ứng dụng của bạn, và API của nó được xây dựng để tích hợp các định dạng quảng cáo phong phú một cách dễ dàng.

*  **AdWords**

    ![Atom](https://i.ytimg.com/vi/Cz9N9bUOwWA/maxresdefault.jpg)

     Có được thông tin và níu kéo lại người dùng với khả năng của Google. Bạn có thể chạy quảng cáo trên Tìm kiếm, hiển thị và video cũng như nhắm mục tiêu phân khúc người dùng cụ thể mà bạn xác định trong Google Analytics for Firebase. Cải thiện nhắm mục tiêu quảng cáo và tối ưu hóa hiệu suất chiến dịch của bạn. Tóm lại: Hiện project của mình chỉ tích hợp tính năng Cloud Messaging gửi tin nhắn và thông báo cho người dùng qua các nền tảng Android, iOS. Nên chúng ta sẽ tìm hiểu cách tích hợp Firebase vào project của mình.
     
## **5. Tích hợp Firebase vào project ứng dụng android**
### **5.1. Điều kiện tiên quyết**
*  Phiên bản android studio mới nhất
*  Ứng dụng của bạn phải thoả mãn 2 yêu cầu:
    *  Target API level 16(Jelly Bean) hoặc cao hơn
    *  Sử dụng phiên bản gradle 4.1 trở lên

### **5.2. Các bước thực hiện**
Bạn có thể tích hợp firebase vào ứng dụng của bạn theo 2 cách sau:
*  Option 1: Sử dụng Firebase console (thông dụng, khuyến khích sử dụng)
*  Option 2: Sử dụng Android Studio Firebase Assistant (yêu cầu cấu hình bổ sung)

Ở tài liệu này, mình sẽ mô tả cho các bạn cách sử dụng **firebase console** để tích hợp firebase vào ứng dụng.
Đó cũng là cách để các bạn có thể làm quen với **firebase console** vì những công việc sử dụng, tương tác với firebase sau này sẽ chủ yếu là thông qua **firebase console** này.

**Sử dụng Firebase console**
    **Bước 1**: **Tạo ra một ứng dụng firebase:**
Trước khi bạn add firebase vào ứng dụng android của bạn, bạn cần phải tạo ra một ứng dụng firebase để kết nối với ứng dụng của bạn.
Tham khaỏ ở https://firebase.google.com/docs/projects/learn-more để hiểu thêm về ứng dụng firebase.

*  Tại màn hình firebase console, click **Add Project** sau đó chọn hoặc nhập tên project ở mục **Project name**

     ![Screen Shot 2019-12-07 at 8](Screen%20Shot%202019-12-07%20at%208.56.39%20PM.png)
    
      ![Screen Shot 2019-12-07 at 8](Screen%20Shot%202019-12-07%20at%208.57.13%20PM.png)
    
*  (Không bắt buộc) Nếu bạn đã tạo một project mới thì bạn có thể thay đổi tuỳ chỉnh được **Project ID**
Firebase tự động gán một ID duy nhất cho dự án Firebase của bạn. Truy cập https://firebase.google.com/docs/projects/learn-more#project-id để tìm hiểu về cách Firebase sử dụng **ID** project.  
    
*  (Không bắt buộc) Thiết lập Google Analytics cho project của bạn, cho phép bạn có trải nghiệm tối ưu khi sử dụng bất kỳ sản phẩm Firebase nào sau đây:
    *  Firebase Crashlytics
    *  Firebase Predictions
    *  Firebase Cloud Messaging
    *  Firebase In-App Messaging
    *  Firebase Remote Config
    *  Firebase A/B Testing
 
       ![Screen Shot 2019-12-07 at 8](Screen%20Shot%202019-12-07%20at%208.58.22%20PM.png)
    
*  Nhấn **Create project** (hoặc **Add Firebase**, nếu bạn sử dụng GCP project đã tồn tại) 

    ![Screen Shot 2019-12-07 at 8-1](Screen%20Shot%202019-12-07%20at%208-1.59.40%20PM.png)
    
**Bước 2**: **Đăng ký ứng dụng android của bạn với firebase**
Sau khi bạn đã có một project về firebase, bạn có thể thêm 1 ứng dụng android của bạn vào trong project đó.
*  Ở phần trung tâm của **Firebase console's project overview page**, nhấn icon **Android** để khởi tạo công việc cài đặt.
    
    ![Screen Shot 2019-12-07 at 9](Screen%20Shot%202019-12-07%20at%209.10.33%20PM.png)

*  Nhập **package name** (chính xác với package name của dự án bạn đang muốn tích hợp firebase vào)
*  (Tùy chọn) Nhập thông tin ứng dụng khác theo hướng dẫn của quy trình thiết lập.
    *  App nickname
    *  Debug signing certificate SHA-1
   
        ![Screen Shot 2019-12-07 at 9](Screen%20Shot%202019-12-07%20at%209.13.39%20PM.png)
    
**Bước 3**: **Download file cấu hình firebase (google.json) và tích hợp vào code project của bạn**

*  Thêm  cấu hình Firebase Android vào ứng dụng của bạn:
    *  Nhấp vào Tải xuống google-services.json để lấy file cấu hình Firebase Android của bạn (google-services.json).
    *  Di chuyển file cấu hình vào thư mục module (app-level) của ứng dụng.
    
        ![Screen Shot 2019-12-07 at 5](Screen%20Shot%202019-12-07%20at%205.44.16%20PM.png)

**Bước 4**: **Thêm SDK Firebase vào ứng dụng của bạn**

Để  các sản phẩm Firebase trong ứng dụng của bạn, hãy thêm **google-services plugin** vào các tệp Gradle của bạn.
   *  Trong root-level (project-level) Gradle file (build.gradle), thêm quy tắc để bao gồm plugin Google Services. Kiểm tra xem bạn có Google's Maven repository không.
   
         ![Screen Shot 2019-12-07 at 6](Screen%20Shot%202019-12-07%20at%206.54.11%20PM.png)

   *  App-level build.gradle (<project>/<app-module>/build.gradle)
    
        ![Screen Shot 2019-12-07 at 6](Screen%20Shot%202019-12-07%20at%206.56.44%20PM.png)

 *  Thêm các phụ thuộc cho các sản phẩm Firebase mà bạn muốn sử dụng trong ứng dụng của mình ở file **app/build.gradle**
 Các thư viện Android sau đây có sẵn cho các sản phẩm Firebase khác nhau, các bạn tham khảo ở 
https://firebase.google.com/docs/reference/android/packages

**Note**: Sync ứng dụng của bạn để đảm bảo rằng tất cả các phụ thuộc có các phiên bản cần thiết.
Như vậy chúng ta đã hoàn thành xong việc tích hợp firebase vào ứng dụng android của bạn.
Mọi thắc mắc mọi người có thể tham khảo ở https://firebase.google.com/docs để hiểu rõ về firebase hơn.







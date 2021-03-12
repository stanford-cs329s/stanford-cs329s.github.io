---
layout: post
title: Áp dụng xác suất vào trong cuộc sống
date: 2020-09-01 13:32:20 +0700
description: Xác suất thống kê không chỉ quan trọng trong công việc -- nó là nền tảng của ngành trí tuệ nhân tạo -- mà còn là cần thiết để đưa ra những quyết định đúng đắn trong cuộc sống.
img: # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Math, Skills]
comments: true
---
Gần đây, một người bạn hỏi nếu mình có thể quay ngược thời gian để có thể nói 3 từ với mình năm 15 tuổi, mình sẽ nói những gì. Mình bảo: "Học xác suất."

Xác suất thống kê không chỉ quan trọng trong công việc (nó là nền tảng của ngành trí tuệ nhân tạo) mà còn là cần thiết để đưa ra những quyết định đúng đắn trong cuộc sống.

Khái niệm đầu tiên mình muốn nói đến là distribution (hàm phân phối xác suất). Distribution hiểu nôm na là hàm số cho phép bạn biết xác suất xảy ra của một sự kiện nào đó. Ví dụ, xổ số với 100 vé được bán ra và mỗi vé đều có khả năng được chọn giống hệt nhau. Việc mỗi vé được chọn là một sự kiện, vậy là có 100 sự kiện có thể xảy ra. Nếu bạn có 1 vé, xác suất vé của bạn được chọn là 1%.

Vì tất cả cả sự kiện này có xác suất xảy ra như nhau, xổ số được gọi là phân phối đều (uniform distribution). Ví dụ khác của uniform distribution là tung đồng xu (mỗi mặt có thể xảy ra là 50%), gieo xúc xắc, đẻ con trai hay con gái, chơi roulette.

Hầu hết các ví dụ đưa ra ở trên là do con người tạo ra, bởi uniform distribution trong tự nhiên rất hiếm. Một distribution phổ biến trong tự nhiên là phân phối chuẩn (normal distribution). Normal distribution nghĩa là nếu có một loạt giá trị, các giá trị nằm ở giữa có xác suất xảy ra cao nhất, và các giá trị nằm ở hai cực (quá nhỏ hay quá lớn) có xác suất xảy ra thấp. Một giá trị càng nằm ở cực (càng khác thường), xác suất nó xảy ra càng thấp.

Ví dụ về normal distribution là chiều cao. Hầu hết phụ nữ trường thành ở Việt Nam sẽ có chiều cao dao động xung quanh 1m55. Phụ nữ trưởng thành với chiều cao là 1m30 hay 1m70 là hiếm hơn nhiều. Các ví dụ khác bao gồm cân nặng, điểm thi, cỡ giày, thời gian bạn đi từ nhà đến công ty.

Normal distribution là một cái bẫy. Chúng ta dễ dàng coi nhiều thứ là normal distribution mặc dù nó không hề normal tí nào. Ví dụ, giá trị tài sản của người dân ở một quốc gia không phải là normal distribution. Khi nói: "Tài sản trung bình của người Việt Nam là 1 tỷ", người nghe dễ hiểu rằng một người trung bình có tài sản khoảng trên dưới 1 tỷ, nhưng sự thật là vài người sẽ có tài sản trên 10,000 tỷ, còn phần lớn mọi người sẽ có tài sản dưới 100 triệu. Ở Mỹ, 0.1% người giàu nhất có tổng tài sản lên tới 20% tài sản của cả quốc gia, nhiều hơn tổng tài sản của 80% người nghèo nhất.

Hình dung một thành phố ảo với 100 người dân. 5 người giàu nhất có 10000, 8000, 7000, 5000, 5000 USD. 5 người tiếp theo có 3000 USD. 20 tiếp theo có 1000USD. 70 người còn lại có 100 USD. Như vậy, 10 người giàu nhất có tổng tài sản là 50000 USD, còn 70 người nghèo nhất có tổng tài sản 7000USD. Nếu tính trung bình, người dân thành phố này sẽ có (50000 + 20000 + 7000) / 100 = 770 USD — gấp 7.7 lần số tiền mà phần lớn người dân thành phố này có.

Nhiều cơ quan, tổ chức dùng con số trung bình này để che giấu thực trạng chênh lệch giàu nghèo. Công ty có thể khoe rằng họ tăng gấp đôi mức lương trung bình của nhân viên, nhưng thực ra tăng mức lương của lãnh đạo 10x nhưng chỉ tăng lương của nhân viên 1%. Ở Mỹ, lương của CEO tăng chóng mặt có khi lên đến hàng trăm triệu USD một năm, nhưng lương tối thiểu cho nhân viên thì vẫn tàng tàng 15,000 USD/năm. Nhà nước có thể khoe họ tăng thu nhập bình quân đầu người của người dân, nhưng thực ra chỉ tăng thu nhập cho một bộ phận rất nhỏ CÔCC.

Khi một nhóm sự kiện với giá trị cao có xác xuất xảy ra nhỏ trong khi phần lớn sự kiện thường xuyên xảy ra lại có giá trị rất nhỏ, những giá trị này theo Pareto distribution hay long-tail distribution. Lượng bán ra của sách, phim, âm nhạc đều theo distribution này. Mỗi năm, chỉ có vài cuốn sách đạt doanh số lên đến triệu bản, nhưng sẽ có hàng ngàn cuốn sách chỉ bán được vài cuốn.

Hiểu rõ cái gì là normal distribution, cái gì là Pareto distribution sẽ giúp chúng ta đưa ra quyết định đúng đắn trong cuộc sống. Một ứng dụng là trong hướng nghiệp. Những nghề có mức thu nhập theo normal distribution như giáo viên, kế toán, lập trình, … được coi là an toàn. Phần lớn những người theo nghề này sẽ có thu nhập ở quanh mức trung bình. Họ sẽ không quá giàu, nhưng cũng sẽ không quá nghèo.

Những nghề có mức thu nhập theo Pareto distribution như nhà văn, ca sĩ, làm công ty khởi nghiệp, … có tính rủi ro cao hơn (và các phụ huynh thường cấm không cho con theo). Phần lớn những người theo nghề này sẽ có thu nhập rất thấp (phần lớn các công ty khởi nghiệp phá sản), nhưng một phần rất nhỏ sẽ vô cùng giàu có. Phần lớn nhà văn sẽ không bán đủ sách để mà sống. Nhưng một vài người như J.K. Rowling trở thành tỉ phú.

Người hiểu về xác suất sẽ không mong làm giàu từ đánh bạc, bởi vì sòng bạc được thiết kế để người chơi mất tiền. Ví dụ chơi trò roulette với 37 số từ 0 đến 36, mỗi số có xác suất được chọn như nhau (uniform distribution). Người chơi đánh cược vào một số từ 1 đến 36. Nếu số được chọn, người chơi thắng gấp 35 lần. Giả sử người chơi đánh cược 10 USD. Nếu thắng (xác suất 1/37), họ được 350 USD. Nếu thua (xác suất 36/37), họ mất 10 USD. Trung bình, số tiền người chơi nhận được là (350 * (1/37) - 10 * (36/37)) = -10/37. Người chơi có thể thắng một vài lần, nhưng nếu chơi lâu dài, người chơi luôn luôn thua.

Người hiểu về xác suất sẽ hiểu tầm quan trọng của may mắn trong thành công. Nếu bạn rút 2 lá bài ra từ trong bộ bài, xác suất bạn có được 2 con át là (4/52) * (3 / 51) = 1/221 — khá thấp. Nhưng nếu bạn rút khoảng 1000 lần, khả năng một trong những lần rút đó cho bạn 2 con át khá là cao.

Thay vì bạn rút 1000 lần, bạn có thể cho 1000 người rút 2 lá bài từ bộ bài của họ. Khả năng cao là một vài người sẽ rút ra được 2 con át. Những người rút được 2 con át này chẳng phải là do tài năng gì, mà chỉ là do ngẫu nhiên.

Tương tự như vậy trong cuộc sống. Trong 1000 hoạ sĩ với tài năng tương đương nhau, sẽ có vài người thành công hơn số còn lại chỉ vì họ may mắn hơn. Hay với 1000 người mở cửa hàng, 1000 công ty khởi nghiệp. Ở Mỹ có câu nói: "Once is chance. Twice is coincidence. Thrice is a pattern." Thành công một lần là may rủi. Thành công hai lần là trùng hợp ngẫu nhiên. Thành công ba lần thì mới tin là tài năng.

Hiểu tầm quan trọng của may mắn trong thành công không có nghĩa là phủ nhận tất cả các yếu tố khác. Như nhà triết học Seneca đã nói: "May mắn xảy ra khi sự chuẩn bị gặp cơ hội." Bạn phải đủ khả năng để biết cái gì là cơ hội (hình dung hàng trăm bạn học cùng Mark Zuckerberg nhưng không hiểu tầm quan trọng của Facebook nên không làm cùng). Bạn cũng phải đủ khả năng để nắm bắt lấy cơ hội đó (hình dung Zuck cần người giúp lập trình và bạn là người lập trình giỏi nhất mà Zuck biết).

Nhiều người gặp may mắn thành công, không hiểu được cái may mắn của mình, mới sáng tạo ra "bí quyết thành công" của bản thân và đi truyền bá cho người khác. Nhiều người thất bại, không hiểu được rằng may mắn của bản thân chưa đến, lại bỏ cuộc.

[Link bài gốc](https://www.facebook.com/chipiscrazy/posts/3134516043331415)

<!-- Hình minh hoạ bởi [Luc Galoppin](https://www.flickr.com/photos/lucgaloppin/4951588099). -->

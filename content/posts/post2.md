+++
author= 'Huynh Duy'
date = '2024-12-30T12:43:57+07:00'
title = 'Làm Việc Với Multi-threading Và Concurrency'
tags = [
    "work_java",
]
+++
## Thread là gì?

Thread (luồng) về cơ bản là một tiến trình con (sub-process). Một đơn vị xử lý nhỏ nhất của máy tính có thể thực hiện một công việc riêng biệt. Trong Java, các luồng được quản lý bởi máy ảo Java (JVM).

## Multi-thread là gì?

Multi-thread (đa luồng) là một tiến trình thực hiện nhiều luồng đồng thời. Một ứng dụng Java ngoài luồng chính có thể có các luồng khác thực thi đồng thời làm ứng dụng chạy nhanh và hiệu quả hơn.

VD: Trình duyệt web hay các chương trình chơi nhạc là 1 ví dụ điển hình về đa luồng.

+ Khi duyệt 1 trang web, có rất nhiều hình ảnh, CSS, javascript… được tải đồng thời bởi các luồng khác nhau.

+ Khi play nhạc, chúng ta vẫn có thể tương tác được với nút điều khiển như: Play, pause, next, back … vì luồng phát nhạc là luồng riêng biệt với luồng tiếp nhận tương tác của người dùng.

## Concurrency là gì?

Xử lý concurrency (đồng thời) nghĩa là có khả năng giải quyết nhiều công việc một lúc, và những công việc đó ko nhất thiết phải xảy ra tại cùng một thời điểm.
---
layout: post
title:  "Tại sao tui thích Vếu"
date:   2018-8-25 10:11:33 +0700
bigimg: /img/tai-sao-tui-thich-veu-head.jpg
share-img: /img/tai-sao-tui-thich-veu-head.jpg
tags: [programming, progressive framwork, react, angular, vue, veu]
---

Chào các bạn, đây là một câu chuyện buồn kể về một anh chàng Backend developer bắt đầu sự nghiệp học JS...

### Progressive Framwork

Trước đây khi nhắc tới Javascript framework thì bạn sẽ nghĩ đến việc một framework cung cấp cho chúng ta đầy đủ mọi thứ để xây dựng Single Page Application(SPA), ta gọi đây là Monolithic Framework, tiêu biểu và khá nổi tiếng là Angular có "cụ Gồ" chống lưng. Tuy nhiên thật sự nó có cần thiết không?

Một Monolithic Framework thật sự nặng nề, và nó đòi hỏi cần phải có một sự hiểu biết và kinh nghiệm nhất định để xây dựng. Nó quá mức cần thiết cho trường hợp chúng ta cần cho những mục đích đơn giản.

Để  giải quyết vấn đề này thì Progressive framework ra đời. Progressive framework là một framework được chia nhỏ thành nhiều thành phần khác nhau, giúp chúng ta linh động hơn trong việc chọn lựa và quyết định sử dụng thành phần nào.
Tiêu biểu cho Progressive Framwork là React JS của cụ Facebook và Vếu JS

### Vếu JS là gì?

![veu-to](/img/veu-to.jpg)

Vếu JS, tên thật là Vue JS là một Progressive Javascript Framwork. Vếu tập trung vào vẻ bề ngoài (view) nhưng ngoài ra chúng ta có thể cài đặt thêm các thành phần khác như Vuex để quản lý state, hay vue-router để routing SPA hoặc... không dùng thêm gì cả.

### Why Vếu
Câu trả lời đơn giản là "bạn có phải đàn ông hay không"? Đàn ông đích thực thì nhìn ngực đầu tiên nhóe.

Đùa tí thôi, thật sự thì mình là Backend developer nên cũng ko có nhiều thời gian hoặc nhiều trải nghiệm quá để mà so sánh giữa các Framework nên mình chỉ nói lên quan điểm của mình thôi nhóe. 

#### Đơn giản, linh động

Mình chọn Vếu vì mình ko có nhu cầu sử dụng Monolithic Framework, mình cần tìm một thứ gọn nhẹ đơn giản, nên mình nhắm tới Progressive Framwork. Lúc này bạn sẽ nghĩ tại sao ko là React.

#### Cú pháp đẹp, ngắn gọn, rõ ràng, sạch sẽ

Ban đầu mình cũng nghĩ tới React và lướt sơ về nó, mình ko thích cú pháp của JSX lắm, mình thích clean nên mình ko thích kiểu trộn lẫn HTML và JS, thật ra JSX cũng ko mix nhiều lắm, chỉ một phần nhỏ thôi, nhưng mình ko thích và ko cảm thấy có thiện cảm lắm, nên mình cho next luôn. Sau khi thử với Vếu thì mình thấy thích vì thấy nó khá rõ ràng, HTML + CSS + JS tách bạch nhìn rất "sạch sẽ". Mình nghĩ bạn cũng thích dùng Vếu "sạch" đúng hăm?

#### Siêu Nhẹ

Ngoài ra thì Vếu không độn nên siêu nhẹ, so vs React thì một trời một vực, khoảng 17kb min. Chi tiết hơn bạn có thể xem ở [đây](https://gist.github.com/Restuta/cda69e50a853aa64912d)

#### Document chi tiết
Nói về document thì Vếu quá tuyệt, document cực kì chi tiết, dễ đọc. Nếu bạn thích Vếu, bạn không cần đi đâu xa xôi, chỉ cần đọc document của Vếu là đủ.

#### Hệ sinh thái
Vếu cung cấp cho bạn full đồ nghề, không quá nhiều sự chọn lựa để bạn không phải lăn tăn chọn cái cái này hay cái kia giống React. Bạn sẽ không còn Google kiểu như: "Redux or Mobx" hay những câu hỏi tương tự. Do đó bạn sẽ tập trung vào Vếu nhiều hơn là thắc mắc.

### Cài đặt Vếu JS

#### CDN
Đối với một project nhỏ hoặc chỉ cần để demo thì bạn có thể sử dụng CDN. Việc đơn giản là bạn chỉ cần include Vếu vào HTML file của bạn như sau:

```html
<script src="https://cdn.jsdelivr.net/npm/vue@2.5.17/dist/vue.js"></script>
```

#### VUE-CLI

Đối với một project lớn thì bạn nên sử dụng Vue-CLI. Vue-CLI sẽ giúp bạn tạo ra một boilerplate với cấu trúc rõ ràng, sạch đẹp, bạn không cần phải mất thời gian ngồi cấu hình các kiểu mà chỉ cần bắt tay vào code thoai.
Việc đầu tiên thì make sure rằng bạn có NPM/Yarn roài nhé.

Cài đặt như sau: 

```bash
npm install -g @vue/cli
# OR
yarn global add @vue/cli
```

Tạo Vếu boilerplate

```bash
vue create my-project
```

Ngoài ra bạn có thể sử dụng thêm webpack với các template khác nhau.
Bạn nên tham khảo thêm ở: [https://github.com/vuejs-templates/webpack](https://github.com/vuejs-templates/webpack)

### Hello world với Vếu JS

Đầu tiên thì chúng ta cần một file HTML đơn giản như sau:
```html
<!DOCTYPE html>
<html lang="en">
  <meta>
    <meta charset="UTF-8">
    <title>Hello World in Vue.js</title>
  </meta>

  <body>
    <div id="hello-world-app">
    </div>
  </body>
</html>
```

Tiếp theo chúng ta cần phải include Vếu JS vào trong file HTML. 

```html
<script src="https://cdn.jsdelivr.net/npm/vue@2.5.17/dist/vue.js"></script>
```

Tiếp đến ta tạo Vếu instance bằng từ khóa `new Vue()`. Sau đó ta cần cài đặt thuộc tính cho Vếu. Thuộc tính cơ bản trong Vếu là `el` và `data`.

Thuộc tính `el` nhận giá trị là một DOM element id. Việc cài đặt thuộc tính này mang ý nghĩa chúng ta sẽ quản lý DOM id này bởi Vếu instance này.
Thuộc tính `data` nhận giá trị là một Object chứa toàn bộ data mà chúng ta sẽ sử dụng trong Vếu instance này.

Để hiển thị các giá trị ở `data` properties thì `Vếu` cung cấp cho bạn một cú pháp đơn giản để hiển thị các gía trị này trên HTML đó là 2 giấu ngoặc nhọn. Ví dụ ta có một Vếu instance như sau:

```html
 <script>
  new Vue({
    el: "#hello-world-app",
    data() {
      return {
        msg: "Hello World!"
      }
    }
  });
</script>
```

Thì để hiển thị giá trị msg lên HTML thì ở vị trí cần hiển thị bạn chỉ đơn giản gọi: `{{ msg }}

Done, bạn đã hoàn thành việc viết Hello World bằng Vếu JS.

Source code hoàn chỉnh bạn có thể xem bên dưới:

![vue-hello-world](/img/vue-hello-world.png)

### Tổng kết

Đến đây thì sao, bạn có quyết định sử dụng Vếu thay vì React hay Angular giống mình không? Nếu bạn thích Vếu thì hi vọng gặp bạn ở loạt bài sau nhé.
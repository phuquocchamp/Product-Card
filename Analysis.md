# PROJECT 1 : PRODUCT CARD

## 1. KIẾN THỨC CỐT LÕI

* Position trong CSS.

  * **fixed** : Định vị vị trí tương đối các thành phần theo cửa sổ trình duyệt.
  * **relative**. : định vị vị trí tuyệt đối cho các thành phần, không gây ảnh hưởng tới các thành phần khác.
  * **absolute** : định vị vị trí tuyệt đối cho thành phần theo thành phần bao ngoài (parent element).
  * **static**. : default position trong css - định vị các thành phần theo thứ tự của văn bản.
  * **inherit** : kế thừa thuộc tính position của element cha.
* Object-fit trong CSS

  * Dùng để chỉ định cách thay đổi kích thước của hình ảnh hoặc video để phù hợp với khung chứa nó (Co nhỏ theo tỉ lệ của giá trị được set).
* CSS BEM.

  > CSS BEM : là một tiêu chuẩn đặt tên cho các selector, mục đích là để cho lập trình viên dễ dàng quản lí, hệ thống các class, id trong project với nhau.
  > BEM : (Object - Element - Modifiers).
  >
* Transform trong CSS.

  * Thuộc tính Transform trong CSS dùng để xử lí các hiệu ứng `dịch chuyển, xoay` của các vật thể.
  * Transform trong CSS bao gồm `transform 2D và transform 3D` => tập trung tìm hiểu vào `transform 2D`

  > Một số giá trị thường dùng về `transform 2d`.
  >

  * Translate : Dịch chuyển vật thể.
  * Rotate : xoay vật thể.
  * Scale : Thay đổi kích thước vật thể (thu nhỏ, phóng lớn.)

  > Ta có thể kết hợp nhiều gía trị của thuột tính transform lại với nhau.
  > `transform: translateY(-90px) rotate(-20deg)`
  >
* Reset CSS.
* Đơn vị trong CSS.

  * em.
  * rem.
  * px.
  * vh.

  ---

## 2. PROJECT OUTLINE

* card
  * card__heart
    * heart icon
  * card__cart
    * cart icon
  * card__img
  * card__title
  * card__price
  * card__size
    * span size
  * card__action
    * button

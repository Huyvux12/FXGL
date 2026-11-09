![promo](https://raw.githubusercontent.com/AlmasB/git-server/master/storage/images/fxgl_promo.jpg)

## Ngôn ngữ

&emsp;&emsp;[English](https://github.com/AlmasB/FXGL/blob/dev/README.md)

&emsp;&emsp;[简体中文](https://github.com/AlmasB/FXGL/blob/dev/README_CN.md)

&emsp;&emsp;[Русский](https://github.com/AlmasB/FXGL/blob/dev/README_RU.md)

&emsp;&emsp;Tiếng Việt

## Giới thiệu

<img src="https://raw.githubusercontent.com/AlmasB/git-server/master/storage/images/fxgl_logo.png" width="128" />

Framework phát triển game trên nền JavaFX

[![Maven Central](https://img.shields.io/maven-central/v/com.github.almasb/fxgl.svg)]()
[![Build Status](https://github.com/AlmasB/FXGL/workflows/Java%20CI%20with%20Maven/badge.svg)](https://github.com/AlmasB/FXGL/actions)
[![codecov](https://codecov.io/gh/AlmasB/FXGL/branch/dev/graph/badge.svg)](https://codecov.io/gh/AlmasB/FXGL)
[![sponsor](https://img.shields.io/badge/sponsor-%241-brightgreen)](https://github.com/sponsors/AlmasB)
[![JFXCentral](https://img.shields.io/badge/Find_me_on-JFXCentral-blue?logo=googlechrome&logoColor=white)](https://www.jfx-central.com/libraries/fxgl)

### Tại sao chọn FXGL?

* Không cần cài đặt hay cấu hình gì thêm
* Dùng được ngay: Java 8-25, Win/Mac/Linux/Android 8+/iOS 11.0+/Web
* API đơn giản, gọn gàng, ở mức trừu tượng cao hơn các engine khác
* Là tập mở rộng của JavaFX: không cần học API giao diện mới
* Các kỹ thuật phát triển game thực tế: Entity-Component, hoạt ảnh nội suy, hệ thống hạt (particles) và [nhiều hơn nữa](https://github.com/AlmasB/FXGL/wiki/Core-Features)
* Game dễ dàng được đóng gói thành một file .jar thực thi duy nhất, hoặc native image

### Phù hợp cho:

* Mọi thể loại game 2D (side-scroller / platformer / arcade / RPG)
* Mọi ứng dụng doanh nghiệp có điều khiển giao diện / hoạt ảnh phức tạp
* 3D (thử nghiệm)
* Dự án cá nhân / học thuật / thương mại
* Dạy / học / nâng cao kỹ năng phát triển game
* Làm nhanh bản mẫu (prototype) cho ý tưởng ứng dụng

### Ví dụ tối giản

```java
public class BasicGameApp extends GameApplication {

    @Override
    protected void initSettings(GameSettings settings) {
        settings.setWidth(800);
        settings.setHeight(600);
        settings.setTitle("Basic Game App");
    }

    public static void main(String[] args) {
        launch(args);
    }
}
```

## Bắt đầu

Để xem code ngay, hãy tham khảo các [ví dụ cơ bản](https://github.com/AlmasB/FXGL/tree/dev/fxgl-samples/src/main/java/basics) độc lập.

Ngoài ra, xem thêm:

* [Sách về FXGL](https://link.springer.com/book/10.1007/978-1-4842-8625-8?sap-outbound-id=3352BB472E8E602B4B29844F1A86CCC4374DDF6E)
* [Video giới thiệu (Showcase Trailer)](https://youtu.be/fuDQg7W0v4g)
* [Dùng FXGL với IntelliJ](https://youtu.be/LhmlFC6KE2Q)
* [Wiki & hướng dẫn dạng văn bản](https://github.com/AlmasB/FXGL/wiki)
* [Hướng dẫn trên YouTube](https://www.youtube.com/playlist?list=PL4h6ypqTi3RTiTuAQFKE6xwflnPKyFuPp)
* [Code demo mẫu](fxgl-samples)
* [Các game làm bằng FXGL](https://github.com/AlmasB/FXGLGames) (kèm mã nguồn)
* [Các bản demo đã phát hành](https://fxgl.itch.io/) trên itch.io

### Maven

* Dự án mẫu [Maven](https://github.com/AlmasB/FXGL-MavenGradle) nếu bạn dùng Java và/hoặc Kotlin

```xml
<dependency>
    <groupId>com.github.almasb</groupId>
    <artifactId>fxgl</artifactId>
    <version>25</version>
</dependency>
```

### Gradle

* Dự án mẫu [Gradle](https://github.com/AlmasB/FXGL-MavenGradle) nếu bạn dùng Java và/hoặc Kotlin

Nếu gặp lỗi, vui lòng tham khảo dự án mẫu.

```gradle
repositories {
    jcenter()
}

dependencies {
    compile 'com.github.almasb:fxgl:25'
}
```

### Tính mô-đun (Modularity)

Nếu bạn muốn phát triển ứng dụng dạng mô-đun, đây là ví dụ đầy đủ cho file `module-info.java`:

```java
open module app.name {
    requires com.almasb.fxgl.all;
}
```

### Uber jar

Tải uber jar mới nhất tại [Releases](https://github.com/AlmasB/FXGL/releases)

## Cộng đồng

* University of Brighton, Vương quốc Anh
* University of Nottingham, Vương quốc Anh
* Georgia Institute of Technology, Hoa Kỳ
* kidOYO, Hoa Kỳ
* Walton High School, Hoa Kỳ
* Conant High School, Hoa Kỳ
* Zealand Institute of Business and Technology, Đan Mạch
* Federal Institute of Education, Science and Technology of Rio Grande do Sul, Brazil
* FHNW School of Engineering / Computer Science, Thụy Sĩ
* Johann-Andreas-Schmeller-Gymnasium Nabburg, Đức

Nếu tổ chức của bạn muốn dùng hoặc đang dùng FXGL, hãy để lại ghi chú qua [GitHub Discussions](https://github.com/AlmasB/FXGL/discussions) để được thêm vào danh sách.

Hướng dẫn từ cộng đồng:

- [Space Ranger](https://www.journaldev.com/40219/space-rangers-game-java-fxgl) trên journaldev
- [Geometry Wars](https://webtechie.be/post/2020-05-07-getting-started-with-fxgl/) trên webtechie
- [Mazela-Man](https://dykstrom.github.io/mazela-man-web/home/) của dykstrom

Dự án cộng đồng (được nhận diện qua topic `fxgl`):

- [SOFTKNK.IO](https://github.com/softknk/softknk.io)
- [Consume](https://ergoscrit.itch.io/consume)
- [FXGL Sliding Puzzle](https://github.com/beryx/fxgl-sliding-puzzle)
- [IRON DEFENDERS](https://magma777.itch.io/iron-defenders)

Nếu bạn muốn dự án của mình được giới thiệu ở đây, chỉ cần để lại ghi chú qua [GitHub Discussions](https://github.com/AlmasB/FXGL/discussions).

### Đội ngũ phát triển

Mô tả các vai trò có trong [Hướng dẫn đóng góp](CONTRIBUTING.md).

Người duy trì (Maintainers / Collaborators):

* [Almas Baimagambetov](https://github.com/AlmasB)

Điều phối viên (Coordinators):

* [Chengen Zhao](https://github.com/chengenzhao)

Người kiểm thử (Testers):

* [Carl Dea](https://github.com/carldea)
* [Frank Delporte](https://github.com/FDelporte)

### Đóng góp & Hỗ trợ

Nếu bạn muốn build FXGL từ mã nguồn hoặc muốn đóng góp,
vui lòng xem [Hướng dẫn đóng góp](CONTRIBUTING.md) (kể cả các đóng góp không phải code).
FXGL được thiết kế hoàn toàn theo mô-đun, nên người mới đóng góp không cần hiểu toàn bộ mã nguồn, chỉ cần hiểu mô-đun mà mình đóng góp.
Các đóng góp sẽ được xem xét theo [Quy tắc ứng xử](CODE_OF_CONDUCT.md).

Bạn có thể ủng hộ việc phát triển FXGL hoặc thể hiện sự quan tâm đơn giản bằng cách gắn sao (star) cho repo hoặc trở thành [nhà tài trợ](https://github.com/sponsors/AlmasB).

### Nhà tài trợ

Cá nhân:

* @Marsl10
* @SergeMerzliakov
* @mbains
* @sabit86
* @hendrikebbers
* @ImperaEtConquer
* @thejeed
* @chikega

Công ty:

* @karakun

### Liên hệ

* Đặt câu hỏi qua [GitHub Discussions](https://github.com/AlmasB/FXGL/discussions)
* Hỏi trên [StackOverflow](https://stackoverflow.com/search?q=fxgl) với các thẻ `javafx` và `fxgl`
* Tweet kèm hashtag [#fxgl](https://twitter.com/search?src=typd&q=%23fxgl)

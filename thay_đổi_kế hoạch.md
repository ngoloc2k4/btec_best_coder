# Thay đổi kế hoạch phát triển dự án EcoConnect
---

- [Thay đổi kế hoạch phát triển dự án EcoConnect](#thay-đổi-kế-hoạch-phát-triển-dự-án-ecoconnect)
    - [Mục tiêu, kết quả cần đạt và cách thực hiện dự án](#mục-tiêu-kết-quả-cần-đạt-và-cách-thực-hiện-dự-án)
      - [1. **Phân tích yêu cầu và xác định mục tiêu dự án**](#1-phân-tích-yêu-cầu-và-xác-định-mục-tiêu-dự-án)
      - [2. **Thiết kế kiến trúc hệ thống**](#2-thiết-kế-kiến-trúc-hệ-thống)
      - [3. **Phân tích tính năng và chức năng**](#3-phân-tích-tính-năng-và-chức-năng)
      - [4. **Thiết kế giao diện người dùng (UI/UX)**](#4-thiết-kế-giao-diện-người-dùng-uiux)
      - [5. **Thiết kế cơ sở dữ liệu**](#5-thiết-kế-cơ-sở-dữ-liệu)
      - [6. **Phát triển API (NodeJS)**](#6-phát-triển-api-nodejs)
      - [7. **Phát triển app mobile (Flutter)**](#7-phát-triển-app-mobile-flutter)
      - [8. **Phát triển web admin (React)**](#8-phát-triển-web-admin-react)
      - [9. **Tích hợp chức năng đăng ký và quản lý sự kiện**](#9-tích-hợp-chức-năng-đăng-ký-và-quản-lý-sự-kiện)
      - [10. **Tích hợp hệ thống xác minh thông tin**](#10-tích-hợp-hệ-thống-xác-minh-thông-tin)
      - [11. **Tích hợp hệ thống quảng cáo và nhà tài trợ**](#11-tích-hợp-hệ-thống-quảng-cáo-và-nhà-tài-trợ)
      - [12. **Thử nghiệm và kiểm tra**](#12-thử-nghiệm-và-kiểm-tra)
      - [13. **Phát hành và triển khai**](#13-phát-hành-và-triển-khai)
      - [14. **Bảo trì và cải tiến**](#14-bảo-trì-và-cải-tiến)
  - [Folder structure for website](#folder-structure-for-website)
  - [Folder structure for Android app](#folder-structure-for-android-app)
  - [For iOS App](#for-ios-app)

---
### Mục tiêu, kết quả cần đạt và cách thực hiện dự án

#### 1. **Phân tích yêu cầu và xác định mục tiêu dự án**

- **Kết quả cần đạt**: Xác định rõ ràng các yêu cầu chức năng và phi chức năng của hệ thống, định hình rõ các mục tiêu chính bao gồm việc quản lý báo cáo môi trường, tính điểm thưởng, thương mại điện tử và xây dựng cộng đồng xanh.
- **Cách làm**:
  - Tổ chức cuộc họp với các bên liên quan như cơ quan môi trường, người dùng và nhà tài trợ để thu thập yêu cầu.
  - Liệt kê và xác định các mục tiêu cụ thể, như báo cáo sự vụ môi trường và quy đổi thành điểm thưởng.
  - Tạo tài liệu yêu cầu chi tiết để định hướng phát triển.

#### 2. **Thiết kế kiến trúc hệ thống**

- **Kết quả cần đạt**: Kiến trúc hệ thống rõ ràng, bao gồm phân chia thành các thành phần app mobile, web admin, backend API và cơ sở dữ liệu, đảm bảo tích hợp trơn tru giữa các thành phần.
- **Cách làm**:
  - Xác định các thành phần chính của hệ thống, tạo sơ đồ kiến trúc thể hiện mối quan hệ giữa app, web, backend và cơ sở dữ liệu.
  - Lựa chọn công nghệ như Flutter, React, NodeJS, MongoDB để phát triển.
  - Thiết kế API chi tiết cho các chức năng chính.

#### 3. **Phân tích tính năng và chức năng**

- **Kết quả cần đạt**: Bản phân tích đầy đủ về các chức năng của hệ thống dựa trên vai trò (phóng viên, người dùng, admin), từ đó phân chia nhiệm vụ phát triển cụ thể.
- **Cách làm**:
  - Phân tích các nhiệm vụ chính của từng vai trò (phóng viên, user, admin) và tạo danh sách chức năng cụ thể.
  - Viết tài liệu mô tả chi tiết từng chức năng và cách tương tác của người dùng.
  - Chia nhỏ các chức năng cho từng thành viên trong nhóm phát triển để tối ưu quy trình lập trình.

#### 4. **Thiết kế giao diện người dùng (UI/UX)**

- **Kết quả cần đạt**: Giao diện người dùng thân thiện, dễ sử dụng và phù hợp với các nền tảng mobile và web, đồng thời tối ưu hóa trải nghiệm của từng nhóm đối tượng.
- **Cách làm**:
  - Tạo wireframe cho các màn hình chính (đăng ký, báo cáo, xác nhận sự kiện, quản lý điểm).
  - Thiết kế prototype tương tác để thu thập phản hồi từ người dùng trước khi phát triển chính thức.
  - Tối ưu giao diện dựa trên phản hồi và đảm bảo sự dễ dùng cho người dùng.

#### 5. **Thiết kế cơ sở dữ liệu**

- **Kết quả cần đạt**: Cơ sở dữ liệu được thiết kế tối ưu để hỗ trợ việc quản lý báo cáo, sự kiện, điểm thưởng và dữ liệu sản phẩm.
- **Cách làm**:
  - Thiết kế bảng cơ sở dữ liệu dựa trên yêu cầu của hệ thống, bao gồm user, sự kiện, điểm, báo cáo, sản phẩm.
  - Tạo sơ đồ ERD để mô tả mối quan hệ giữa các bảng.
  - Thiết lập cơ sở dữ liệu MongoDB và triển khai các bảng dữ liệu.

#### 6. **Phát triển API (NodeJS)**

- **Kết quả cần đạt**: API backend hoạt động ổn định, hỗ trợ đầy đủ các chức năng như đăng ký sự kiện, báo cáo sự vụ, xác nhận và quản lý điểm thưởng.
- **Cách làm**:
  - Phát triển các endpoint API cho từng chức năng chính như báo cáo sự vụ, tính điểm, quản lý sự kiện.
  - Sử dụng Postman để kiểm thử các API và đảm bảo chúng hoạt động chính xác.
  - Bảo mật API bằng JWT và các cơ chế khác.

#### 7. **Phát triển app mobile (Flutter)**

- **Kết quả cần đạt**: Ứng dụng mobile hỗ trợ người dùng và phóng viên báo cáo sự vụ, đăng ký sự kiện và quản lý điểm một cách hiệu quả.
- **Cách làm**:
  - Xây dựng các màn hình chính như đăng ký sự kiện, báo cáo, quản lý điểm.
  - Tích hợp API backend để kết nối ứng dụng với cơ sở dữ liệu.
  - Kiểm thử ứng dụng trên nhiều thiết bị khác nhau để đảm bảo tính tương thích.

#### 8. **Phát triển web admin (React)**

- **Kết quả cần đạt**: Hệ thống quản lý web admin hỗ trợ admin quản lý người dùng, sự kiện, điểm thưởng, kết nối với nhà tài trợ và quảng cáo.
- **Cách làm**:
  - Xây dựng các trang quản lý user, sự kiện, báo cáo và nhà tài trợ.
  - Tích hợp API backend để quản lý dữ liệu.
  - Tối ưu hóa giao diện web cho admin, đảm bảo tính tiện dụng và hiệu suất cao.

#### 9. **Tích hợp chức năng đăng ký và quản lý sự kiện**

- **Kết quả cần đạt**: Hệ thống cho phép người dùng đăng ký sự kiện, báo cáo sự vụ, quản lý điểm và phân chia điểm cho những người tham gia.
- **Cách làm**:
  - Tạo form đăng ký sự kiện, báo cáo sự vụ cho app và web.
  - Phát triển tính năng thông báo sự kiện qua Firebase hoặc hệ thống khác.
  - Cung cấp tính năng cho phép người dùng phân chia điểm cho người khác trong cùng sự kiện.

#### 10. **Tích hợp hệ thống xác minh thông tin**

- **Kết quả cần đạt**: Hệ thống có khả năng xác minh báo cáo sự vụ qua thông tin từ cơ quan môi trường, đảm bảo tính chính xác và uy tín của báo cáo.
- **Cách làm**:
  - Tạo API để gửi thông tin báo cáo đến cơ quan môi trường và nhận phản hồi xác minh.
  - Xử lý phản hồi từ cơ quan môi trường và cập nhật trạng thái xác minh của sự vụ trong hệ thống.

#### 11. **Tích hợp hệ thống quảng cáo và nhà tài trợ**

- **Kết quả cần đạt**: Hệ thống tích hợp quảng cáo và liên kết với nhà tài trợ để tăng nguồn thu và hỗ trợ các sự kiện phi lợi nhuận.
- **Cách làm**:
  - Tích hợp hệ thống quảng cáo như Google Ads hoặc thiết kế giải pháp quảng cáo riêng.
  - Thiết lập mối quan hệ với các nhà tài trợ để cung cấp kênh quảng bá thông qua app và web.

#### 12. **Thử nghiệm và kiểm tra**

- **Kết quả cần đạt**: Hệ thống hoàn thiện, hoạt động ổn định với các chức năng chính được kiểm tra và đảm bảo hiệu suất cao, an toàn.
- **Cách làm**:
  - Thực hiện các bài kiểm tra chức năng (unit test, integration test) và kiểm tra hiệu suất.
  - Kiểm tra tính bảo mật của hệ thống, đảm bảo dữ liệu nhạy cảm được bảo vệ.
  - Thử nghiệm toàn diện để phát hiện và sửa các lỗi phát sinh.

#### 13. **Phát hành và triển khai**

- **Kết quả cần đạt**: Ứng dụng và website được phát hành chính thức, khả dụng cho người dùng trên các nền tảng mobile và web.
- **Cách làm**:
  - Đưa ứng dụng mobile lên App Store và Google Play.
  - Triển khai hệ thống web và backend trên server (AWS, Heroku, DigitalOcean).
  - Cấu hình tên miền và thiết lập môi trường triển khai cho web.

#### 14. **Bảo trì và cải tiến**

- **Kết quả cần đạt**: Hệ thống được bảo trì và cải tiến liên tục dựa trên phản hồi từ người dùng, cập nhật tính năng mới và tối ưu hóa trải nghiệm.
- **Cách làm**:
  - Giám sát hệ thống qua các công cụ như Google Analytics, Firebase để đánh giá hiệu suất và hoạt động.
  - Thu thập phản hồi từ người dùng để cải thiện giao diện, chức năng.
  - Thực hiện cập nhật, nâng cấp hệ thống thường xuyên để đảm bảo an toàn và hiệu suất.


---

<br />

## Folder structure for website
**(Use Laravel Framework to build folder)**

``` folder_structure for web
project_root/
│
├── app/
│   ├── Console/
│   ├── Exceptions/
│   ├── Http/
│   │   ├── Controllers/    # Controllers for handling requests
│   │   │   ├── Admin/      # Admin dashboard-specific controllers
│   │   │   ├── Auth/       # Authentication-related controllers
│   │   ├── Middleware/     # Custom middleware for authorization and validation
│   ├── Models/             # Eloquent models for database interactions
│   ├── Policies/           # Policies for user role permissions
│
├── bootstrap/              # Laravel's core files
│
├── config/                 # Configuration files
│   ├── app.php             # Main app configuration
│   ├── auth.php            # Authentication settings
│   ├── database.php        # Database configuration
│
├── database/
│   ├── migrations/         # Database migrations for creating tables
│   ├── factories/          # Factories for generating fake data (for testing)
│   ├── seeders/            # Seeders for populating the database
│
├── public/                 # Publicly accessible files (JS, CSS, images)
│   ├── css/
│   ├── js/
│   ├── images/
│   ├── index.php           # Main entry point for the website
│
├── resources/
│   ├── views/
│   │   ├── admin/          # Admin dashboard views (Blade templates)
│   │   │   ├── layouts/    # Admin layout (header, footer, etc.)
│   │   │   ├── dashboard.blade.php
│   │   │   ├── users.blade.php
│   │   │   ├── events.blade.php
│   │   │   ├── reports.blade.php
│   │   ├── auth/           # Views for login, register, password reset
│   │   ├── components/     # Reusable Blade components
│   │   ├── errors/         # Error pages (404, 500)
│   │   ├── layouts/        # Main website layouts
│
├── routes/
│   ├── web.php             # Routes for web requests
│   ├── api.php             # Routes for API requests
│
├── storage/                # Log files, cached views, session data, and file uploads
│   ├── logs/
│   ├── app/
│   ├── framework/
│   ├── public/
│
├── tests/                  # Unit and feature tests
│
├── vendor/                 # Composer dependencies
│
├── .env                    # Environment configuration (DB credentials, API keys)
├── artisan                 # Laravel's command-line interface (CLI) tool
├── composer.json           # Composer configuration file
├── package.json            # Node.js dependencies
├── webpack.mix.js          # Laravel Mix configuration (for compiling assets)

```

## Folder structure for Android app
**(Use Flutter)**

```
project_root/
│
├── android/                # Android-specific files (native Android code, config)
│   ├── app/                # Main Android app folder
│   │   ├── src/
│   │   │   ├── main/       # Main source code for the Android app
│   │   │   │   ├── AndroidManifest.xml  # App's manifest file
│   │   │   │   ├── java/   # Java/Kotlin code for Android-specific functionality
│   │   │   │   ├── res/    # Android-specific resources (layouts, drawables, etc.)
│
├── ios/                    # iOS-specific files (if cross-platform with Flutter)
│
├── lib/                    # Main Flutter code
│   ├── screens/            # Screens or pages in the app (UI)
│   │   ├── home_screen.dart
│   │   ├── report_screen.dart
│   │   ├── profile_screen.dart
│   │   ├── incident_screen.dart
│   │   └── settings_screen.dart
│   │
│   ├── models/             # Data models (e.g., user, report, incident)
│   │   ├── user_model.dart
│   │   ├── report_model.dart
│   │   └── incident_model.dart
│   │
│   ├── services/           # Services (e.g., API, database, authentication)
│   │   ├── api_service.dart
│   │   ├── auth_service.dart
│   │   ├── database_service.dart
│   │   └── notification_service.dart
│   │
│   ├── widgets/            # Reusable UI components (buttons, cards, etc.)
│   │   ├── custom_button.dart
│   │   ├── incident_card.dart
│   │   └── progress_indicator.dart
│   │
│   ├── utils/              # Utility classes or helper functions
│   │   ├── constants.dart  # App-wide constants (e.g., colors, strings)
│   │   ├── validators.dart # Input validators, helpers
│   │   └── image_helper.dart
│   │
│   └── main.dart           # Main entry point of the Flutter app
│
├── assets/                 # Images, fonts, and other assets
│   ├── images/             # Image assets
│   │   ├── logo.png
│   │   ├── background.jpg
│   ├── fonts/              # Font files
│   │   └── OpenSans.ttf
│   └── json/               # JSON configuration files, data files
│
├── test/                   # Unit and widget tests for the app
│   ├── home_screen_test.dart
│   ├── report_screen_test.dart
│   └── widget_test.dart
│
├── pubspec.yaml            # Pubspec file (dependencies, assets, fonts, etc.)
├── README.md               # Project readme
├── .gitignore              # Files and folders to ignore in version control
```

## For iOS App

```
project_root/
│
├── ios/                    # iOS-specific files (native iOS code, config)
│   ├── Runner/             # Main iOS app folder
│   │   ├── Assets.xcassets/  # App icons, image assets specific to iOS
│   │   ├── Base.lproj/     # Localized files (English, etc.)
│   │   ├── Info.plist      # iOS app configuration file
│   │   ├── AppDelegate.swift # iOS-specific app lifecycle code (for Swift)
│   │   └── Runner.xcodeproj/ # Xcode project configuration
│   ├── Podfile             # CocoaPods dependencies (Flutter for iOS)
│   └── Podfile.lock        # Locked dependencies for iOS
│
├── lib/                    # Main Flutter code (shared across platforms)
│   ├── screens/            # Screens or pages in the app (UI)
│   │   ├── home_screen.dart
│   │   ├── report_screen.dart
│   │   ├── profile_screen.dart
│   │   └── settings_screen.dart
│   │
│   ├── models/             # Data models (e.g., user, report, incident)
│   │   ├── user_model.dart
│   │   ├── report_model.dart
│   │   └── incident_model.dart
│   │
│   ├── services/           # Services (e.g., API, database, authentication)
│   │   ├── api_service.dart
│   │   ├── auth_service.dart
│   │   ├── database_service.dart
│   │   └── notification_service.dart
│   │
│   ├── widgets/            # Reusable UI components (buttons, cards, etc.)
│   │   ├── custom_button.dart
│   │   ├── incident_card.dart
│   │   └── progress_indicator.dart
│   │
│   ├── utils/              # Utility classes or helper functions
│   │   ├── constants.dart  # App-wide constants (e.g., colors, strings)
│   │   ├── validators.dart # Input validators, helpers
│   │   └── image_helper.dart
│   │
│   └── main.dart           # Main entry point of the Flutter app
│
├── assets/                 # Images, fonts, and other assets
│   ├── images/             # Image assets
│   │   ├── logo.png
│   │   ├── background.jpg
│   ├── fonts/              # Font files
│   │   └── OpenSans.ttf
│   └── json/               # JSON configuration files, data files
│
├── test/                   # Unit and widget tests for the app
│   ├── home_screen_test.dart
│   ├── report_screen_test.dart
│   └── widget_test.dart
│
├── pubspec.yaml            # Pubspec file (dependencies, assets, fonts, etc.)
├── README.md               # Project readme
├── .gitignore              # Files and folders to ignore in version control
```


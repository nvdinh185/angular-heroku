Deploy ứng dụng lên heroku
1. Cài thư viện nodemon
2. Di chuyển @angular/cli và @angular/compiler-cli từ devDependencies sang dependencies
3. Chỉnh sửa trong file angular.json dòng "outputPath": "angular-build", ("angular-build" là thư mục chứa code đã biên dịch)
4. Chạy lệnh ng build để biên dịch toàn bộ mã nguồn sang thư mục "angular-build"
5. Tạo server express
6. Chỉnh sửa file package.json: "start": "nodemon server.js"
7. Tạo dự án trên heroku và deploy lên
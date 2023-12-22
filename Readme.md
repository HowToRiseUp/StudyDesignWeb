# FUCK

### SASS

- Node v14.17.3 (LTS)
- `npm intsall -g sass`
- `sass path-of-sass-file path-of-css-file --watch`

### Git

- `git checkout -b popular-things` : tạo nhánh mới
- `git stash` # Ẩn đi các thay đổi chưa commit
- `git switch main` # Chuyển sang nhánh main
- `git stash apply` # Áp dụng lại các thay đổi từ stash (nếu cần)

### 11, 12: Tìm hiểu Pug cơ bản.

- `npm install pug -g` : tải pug về mà dùng. Tùy chọn -g có ý nghĩa là "cài đặt toàn cầu" (global).
- `pug index.pug --watch --pretty` : _--watch_ làm mới liên tục | _--pretty_ tạo file html covert sang.
- `mixin .name(argument)` giúp tái sử dụng phần lập lại, code html nhanh hơn _+name_.
  - `#{argument}` điền biến.
- `include ./pug/tuor-mixin` tối giản tí

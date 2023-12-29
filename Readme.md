### Challeng 7 (Tùy Biến dropdow)

- Kết Luận: không thể dùng select option
- Nguyên Nhân: kệ mẹ nó
- Giải Pháp: `Có absolute cho con và dùng các thẻ div`

### Challeng 6 (Tùy Biến checkbox)

- Kết Luận: thẻ input không thể css check bõ được
- Nguyên Nhân: do trình duyệt không hổ trợ
- Giải Pháp: `Dùng Label bocji lại, đè thẻ input (display: none ) lên div đã styte style `

- comninator: _+_ chọn phần tử kế bên từ trên xuống

### Challeng em - rem

- `em` thì chạy theo ba
- `rem` thì chạy theo root
- reposive thì nên dùng `em` vì sẽ có zoom

### Challeng 5 ( Flexbox nâng cao )

- `flex: 1`
- grow 1 shirk 1 basic 0

### Challeng 3

- `gird-template-area`
- `auto-fill` và `auto-fit`
- minmax
- peseodo

### Git

- `git checkout -b popular-things` : tạo nhánh mới
- `git stash` # Ẩn đi các thay đổi chưa commit
- `git switch main` # Chuyển sang nhánh main
- `git stash apply` # Áp dụng lại các thay đổi từ stash (nếu cần)

### SASS

- Node v14.17.3 (LTS)
- `npm intsall -g sass`
- `sass path-of-sass-file path-of-css-file --watch`
- `_nested_` === `tour{ &-cc{npm instas
  css
} }`
- # parten 7 - 1

### Pug

- `npm install pug -g` : tải pug về mà dùng. Tùy chọn -g có ý nghĩa là "cài đặt toàn cầu" (global).
- `pug index.pug --watch --pretty` : _--watch_ làm mới liên tục | _--pretty_ tạo file html covert sang.
- `mixin .name(argument)` giúp tái sử dụng phần lập lại, code html nhanh hơn _+name_.
  - `#{argument}` điền biến.
- `include ./pug/tuor-mixin` tối giản tí

# Tiếng Việt không dấu

_Node Module dành cho người Việt_

[![Tieng Viet khong dau](https://img.shields.io/badge/node-%5E0.10.40-brightgreen.svg)](//www.npmjs.com/package/tieng-viet-khong-dau) [![Tieng Viet khong dau](https://img.shields.io/badge/npm-%5E1.4.28-brightgreen.svg)](//www.npmjs.com/package/tieng-viet-khong-dau)

## Cài đặt

```shell
$ npm install --save tieng-viet-khong-dau
```

## Sử dụng

### Đối với NodeJS

```javascript
var tvkd = require('tieng-viet-khong-dau');

console.log(tvkd.c('Hoàng Sa, Trường Sa là của Việt Nam'));

// Kết quả: Hoang Sa, Truong Sa la cua Viet Nam
```

### Đối với Javascript phía Font-end

```html
<script src="lib/tvkd.js"></script>
```

```js
console.log(tvkd.c('Hoàng Sa, Trường Sa là của Việt Nam'));
// Kết quả: Hoang Sa, Truong Sa la cua Viet Nam
```

## API

**tvkd.c( str )**

Chuyển chuỗi tiếng Việt sang tiếng Việt không dấu

**tvkd.cLowerCase( str )**

Chuyển chuỗi tiếng Việt sang tiếng Việt không dấu và bỏ viết hoa

**tvkd.cUpperCase( str )**

Chuyển chuỗi tiếng Việt sang tiếng Việt không dấu và viết hoa toàn bộ

**tvkd.cFriendlyURI( str )**

Chuyển chuỗi tiếng Việt cho thân thiện với các đường dẫn (link)

## Demo

[Xem thêm ví dụ](./demo.js)

## Giấy phép

MIT

Cloned from https://github.com/vuanhhaogk/khong-dau
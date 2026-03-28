## Từ QR đến VietQR — khám phá cấu trúc của một QR thanh toán

### Phần 2: Sơ lược cách tạo ra mã QR

[Xem lại bài viết tại đây](TBU).

#### Lời cảm ơn

Trân trọng cảm ơn [Thonky.com](https://www.thonky.com/qr-code-tutorial/) và [Massimo Artizzu](https://dev.to/maxart2501/let-s-develop-a-qr-code-generator-part-i-basic-concepts-510a) vì đã là nguồn tham khảo chính cho bài viết này.

#### Liên kết

[a] [Tra cứu khả năng lưu trữ của mã QR](https://www.thonky.com/qr-code-tutorial/character-capacities).     
[b] Các công cụ chuyển đổi giữa số thập phân/văn bản sang số nhị phân của RapidTables:     
- [Công cụ chuyển đổi số thập phân sang số nhị phân](https://www.rapidtables.com/convert/number/decimal-to-binary.html)     
- [Công cụ chuyển đổi số nhị phân sang số thập phân](https://www.rapidtables.com/convert/number/binary-to-decimal.html)     
- [Công cụ chuyển văn bản sang số nhị phân](https://www.rapidtables.com/convert/number/ascii-to-binary.html)     
Với các công cụ chuyển đổi số thập phân sang nhị phân và ngược lại, bạn có thể dán một danh sách số, phân cách nhau bằng dấu cách để chuyển đổi hàng loạt.

[c] [Bảng các ký tự trong kiểu mã hóa số và chữ cùng giá trị tương ứng của chúng](https://www.thonky.com/qr-code-tutorial/alphanumeric-table).     
[d] [Bảng thông tin số từ khóa nội dung, từ khóa chữa lỗi và cách chia phần các từ khóa theo từng kích cỡ QR](https://www.thonky.com/qr-code-tutorial/error-correction-table).     
[e] [Thông tin nâng cao về cách tính toán từ khóa chữa lỗi](https://www.thonky.com/qr-code-tutorial/error-correction-coding).    
[f] [Công cụ tính toán từ khóa chữa lỗi](https://www.thonky.com/qr-code-tutorial/show-division-steps).     
[g] [Danh sách số bit cần bổ sung vào cuối mã nhị phân theo từng kích cỡ QR](https://www.thonky.com/qr-code-tutorial/structure-final-message#list-of-versions-and-required-remainder-bits).      
[h] [Thông tin bổ sung về thông tin kích cỡ](https://www.thonky.com/qr-code-tutorial/format-version-information#version-information).     
[i] [Tập tin Excel mà tôi đã chuẩn bị](https://1drv.ms/x/c/060e62b48a00f0ba/IQAnMt3eHbYPQK7o4ypxRUL1AePcuX5oSIcrPFqC_xnDLN8?e=Whpvwy).     
[j] [Vị trí các hoa văn tọa độ theo từng kích cỡ QR](https://www.thonky.com/qr-code-tutorial/alignment-pattern-locations).     
[k] [Danh sách thông tin chữa lỗi tương ứng với hoa văn chữa lỗi và mức độ chữa lỗi đã chọn](https://www.thonky.com/qr-code-tutorial/format-version-tables).     
[l] [Một cách thức tính điểm phạt khác cho tiêu chí 4 của Thonky.com](https://www.thonky.com/qr-code-tutorial/data-masking#evaluation-condition-4).

#### Tư liệu sử dụng

[1] *Character sets: ISO-8859-1 (Western Europe) - Charset Tools*. (n.d.). Charset. https://www.charset.org/charsets/iso-8859-1     
[2] IDAutomation.com, Inc. (2025, October 21). *ECI (Extended Channel Interpretation) Unicode Encoding for 2D QR-Code barcodes | BarcodeFAQ.com*. BarcodeFAQ.com. https://www.barcodefaq.com/2d/eci/      
[3] Thonky.com. (2020, March 8). *Byte mode encoding*. QR Code Tutorial. https://www.thonky.com/qr-code-tutorial/byte-mode-encoding     
[4] Thonky.com. (2020, March 8). *Data analysis*. QR Code Tutorial. https://www.thonky.com/qr-code-tutorial/data-analysis     
[5] *Shift JIS Kanji Code Table*. (n.d.). http://www.rikai.com/library/kanjitables/kanji_codes.sjis.shtml     
[6] Wikipedia contributors. (2026, March 25). *Reed–Solomon error correction*. Wikipedia. https://en.wikipedia.org/wiki/Reed%E2%80%93Solomon_error_correction     
[7] Kitz. (n.d.). ::. *Kitz - Interleaving* .:: https://kitz.co.uk/adsl/interleaving.htm

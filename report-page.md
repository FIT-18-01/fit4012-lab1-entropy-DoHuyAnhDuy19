# Report 1 Page – FIT4012 Lab 1

## 1. Mục tiêu
Tóm tắt ngắn gọn mục tiêu của bài lab.

## 2. Cách làm
- Đọc hiểu chương trình entropy mẫu.
- Bổ sung hàm tính redundancy.
- Hoàn thiện hàm mod_inverse().
- Chạy thử trên nhiều test case.

## 3. Kết quả chính
### 3.1 Entropy và redundancy
| Input | Entropy | Redundancy | Nhận xét |
|---|---:|---:|---|
| aaaa |1.14883|6.85117| Độ hỗn loạn bằng 0 do chỉ có 1 ký tự duy nhất, độ dư thừa là tối đa. |
| abcd |2|6| Các ký tự xuất hiện đồng đều làm Entropy tăng lên, độ dư thừa giảm. |
| hello world |3.18201|4.81799| Chuỗi dài và đa dạng ký tự nhất dẫn đến Entropy cao nhất và Redundancy thấp nhất. |

### 3.2 Modulo inverse
| a | m | Kết quả mong đợi | Kết quả chương trình |
|---:|---:|---|---|
| 3 | 7 | 5 |  |
| 10 | 17 | 12 |  |
| 6 | 9 | Không tồn tại |  |

## 4. Kết luận
Nêu ngắn gọn em học được gì từ bài lab, khó khăn lớn nhất là gì, và điều gì giúp em hiểu rõ hơn về entropy hoặc modulo inverse.

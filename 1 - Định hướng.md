---
min-impact: 5
created: 2026-06-05
blueprint:
  - "[[Life Design]]"
---
# Mục tiêu
- Hướng đến sự tự do, sự nghiệp tay trái để có thêm thời gian đồng hành cùng con
- 

# Tại sao cần làm việc này? 
- Con số chủ đạo 3 khiến mình muốn có thể là người có giá trị, mong muốn cơ hội tạo ra sự khác biệt/ giúp đỡ cụ thể cho cuộc sống người khác
- Phát triển bản thân, học hỏi và chia sẻ. 
- Muốn tăng thu nhập nhưng vẫn cảm thấy công việc có giá trị với người khác
- Giúp mình phát huy hết tiềm năng bản thân
- 

# Outcomes
- Định vị được thương hiệu, hình ảnh cá nhân trên online (Brand Personal): Mẹ bỉm văn phòng hiện đại, chủ động thiết kế cuộc sống, và hành trình học làm mẹ
- **Core value:** Chia sẻ hành trình trưởng thành thực tế (nuôi dạy con, quản lý cảm xúc, phát triển bản thân)
- **Monetization:** Affiliate (phụ) + bảo hiểm (chính)

# Định vị, lối sống muốn hướng tới
- Nuôi con bằng sự thấu hiểu và trường thành cùng con mỗi ngày. Và việc giáo dục con bắt đầu từ cha mẹ. 
- Một người mẹ văn phòng hiện đại, đang chủ động thiết kế cuộc sống mong muốn, nuôi con bằng sự thấu hiểu và không ngừng trưởng thành cùng con mỗi ngày. Mình chia sẻ hành trình trưởng thành thông qua những trải nghiệm thực tế về nuôi dạy con, quản lý cảm xúc, phát triển bản thân và xây dựng cuộc sống mong muốn. 



> [!NOTE] Lộ trình
> Content Creator → Xây cộng đồng → Parent Educator → Đào tạo/Coaching → Hệ sinh thái sản phẩm số


# Định hướng nội dung
| Tuyến nội dung                                       | Mục tiêu                                      | Tỷ trọng | Nội dung khai thác                                                                      |
| ---------------------------------------------------- | --------------------------------------------- | -------- | --------------------------------------------------------------------------------------- |
| **1. Nhật ký trưởng thành cùng con**                 | Xây dựng kết nối cảm xúc                      | 30%      | Những tình huống đời thường với con và điều bản thân nhận ra sau mỗi trải nghiệm        |
| **2. Những niềm tin mình đang gỡ bỏ**                | Xây dựng góc nhìn riêng                       | 15%      | Những quan điểm cũ về làm mẹ, hôn nhân, công việc, phát triển bản thân mà mình từng tin |
| **3. Những thay đổi nhỏ giúp cuộc sống dễ chịu hơn** | Tạo giá trị thực tiễn                         | 15%      | Thói quen, nguyên tắc sống, hệ thống quản lý thời gian, năng lượng, cảm xúc             |
| **4. Hành trình học làm cha mẹ**                     | Chia sẻ kiến thức                             | 15%      | Điều học được từ sách, khóa học, workshop và cách áp dụng thực tế                       |
| **5. Chuyện nghề - chuyện người**                    | Mở rộng hình ảnh cá nhân ngoài vai trò làm mẹ | 10%      | Công việc bảo hiểm, content marketing, kinh doanh, xây dựng sự nghiệp                   |
| **6. Đối thoại với chính mình**                      | Tạo chiều sâu thương hiệu                     | 10%      | Những trăn trở, câu hỏi, bài học phát triển bản thân                                    |
| **7. Góc nhìn về cuộc sống**                         | Tăng khả năng lan tỏa                         | 5%       | Quan điểm về hạnh phúc, thành công, gia đình, phụ nữ, sự trưởng thành                   |
|                                                      |                                               |          |                                                                                         |

# Đề xuất tuyến nội dung
- Series 1: Làm mẹ giúp mình nhận ra...
- Series 2: Trước đây mình từng nghĩ...
- Series 3: Một thay đổi nhỏ gần đây của mình
- Series 4: Nhật ký học làm cha mẹ
- Series 5: Chuyện nghề dạy mình điều gì
## Others

```dataview
TABLE impact, created
FROM -"6. Vault"
WHERE contains(string(join(blueprint, "  ")), this.file.name) AND none(list(impact))
SORT rank DESC, created DESC
```

[^1]: 

# Wuthering Waves 3.4 — part11 — V4 Report

- Tổng entry: **25,304**
- Entry VI/HV thay đổi: **524**
- Patch thoại/nghĩa thủ công: **70**
- Entry chuẩn hóa thuật ngữ: **49**
- Entry VI sửa tên legacy → EN canonical: **5**
- HV được dựng lại từ VI theo NAME LOCK, không tin bản HV cũ.
- CN/EN/JP giữ nguyên; tag/placeholder/gender branch/%s/%d/\\n đã validation.

## Xưng hô / voice

- **Shorekeeper ↔ Rover (`phone_JL_5`)**: bỏ khoảng cách `ngài/nàng`, dùng lớp hậu-quan-hệ tự nhiên hơn **tôi–cậu / tôi–cô**.
- **Changli ↔ Rover (`phone_JL_4`)**: giữ `ta` cho chất cổ nhã của Changli, nhưng sau bước qua sinh tử đổi `ngươi` → **cậu**.
- **Nhóm `phone_JL_12`**: giữ `ta` ở register `余/お主`, sửa lỗi đang nhảy `ta → tôi` và làm phía người nghe tự nhiên hơn.
- **Lynae chat (`Message_Main_LahaiRoi_3_1_1/3/4`)**: giữ baseline **tớ–cậu** theo `あたし/あんた`, sửa câu MT/capitalization.

## Name fixes

- Xóa Hán-Việt tự phát ở các tên người dùng để trống: Rebecca/Lucy/Lynae/Encore/Verina/Phrolova/Shorekeeper/Rover/... giữ EN.
- VI dùng tên EN canonical; HV chỉ đổi đúng 17 mapping đã chốt.

## Term fixes

- Cộng Minh Giả → Cộng Hưởng Giả
- Waveband → Dải Âm Vang
- Voidworm → Trùng Hư Đản
- Black Shores → Bờ Biển Đen

## Clear semantic fixes

- `ItemInfo_70140086_AttributesDescription`: bỏ lỗi lặp `Hack Hack Nhanh`.
- `ItemInfo_71200010_AttributesDescription`: sửa câu hỏng `giấc mơ Mùi từng Lựa Chọn`.

## Change log

### `lang_speaker.db||Speaker||6992`
- VI cũ: Liên lạc viên Hắc Hải Ngạn
- VI V4: Liên lạc viên Bờ Biển Đen
- HV cũ: Liên lạc viên Hắc Hải Ngạn
- HV V4: Liên lạc viên Bờ Biển Đen

### `lang_speaker.db||Speaker||7002`
- HV cũ: Lệ Bối Tạp
- HV V4: Rebecca

### `lang_speaker.db||Speaker||7003`
- HV cũ: Lộ Tây
- HV V4: Lucy

### `lang_speaker.db||Speaker||7013`
- HV cũ: {message}Lệ Bối Tạp
- HV V4: {message}Rebecca

### `lang_speaker.db||Speaker||7014`
- HV cũ: {message}Lộ Tây
- HV V4: {message}Lucy

### `lang_speaker.db||Speaker||7027`
- VI cũ: {message}Thu Thủy
- VI V4: {message}Aalto

### `lang_speaker.db||Speaker||7060`
- HV cũ: Lệ Bối Tạp
- HV V4: Rebecca

### `lang_speaker.db||Speaker||859`
- HV cũ: Phất Lạc Lạc
- HV V4: Phrolova

### `lang_speaker.db||Speaker||873`
- VI cũ: Xuân
- VI V4: Camellya
- HV cũ: Xuân
- HV V4: Camellya

### `lang_speaker.db||Speaker||99`
- VI cũ: Kỵ Viêm
- VI V4: Jiyan

### `lang_multi_text.db||MultiText||BackgroundCard_80070001_BgDescription`
- HV cũ: Dấu ấn chứng kiến hành trình của Lữ Khách, có thể trưng bày cho các Lữ Khách khác.\nCó thể thay đổi Dấu Ấn Lữ Hành trong Thông tin Lữ Khách.
- HV V4: Dấu ấn chứng kiến hành trình của Rover, có thể trưng bày cho các Rover khác.\nCó thể thay đổi Dấu Ấn Lữ Hành trong Thông tin Rover.

### `lang_multi_text.db||MultiText||ConfirmBox_240_Content`
- HV cũ: Sau khi đổi Lữ Khách cần trở lại giao diện đăng nhập, tiếp tục không?\n(Một số nội dung có thể không thay đổi theo)
- HV V4: Sau khi đổi Rover cần trở lại giao diện đăng nhập, tiếp tục không?\n(Một số nội dung có thể không thay đổi theo)

### `lang_multi_text.db||MultiText||DIY_RegionDesc_Content_6`
- VI cũ: Nơi đây vốn lưu giữ nhiều bộ sưu tập phim, thú cưỡi của ông Geisel cũng được đỗ ở đây, nhưng những món đồ sưu tầm tượng trưng cho ước mơ và kỷ niệm này đã không còn nữa. Giờ đây, thú cưỡi của bạn và video quảng bá của Học Viện Startorch được đặt ở đây, diễn giải những ước mơ và hy vọng mới.
- VI V4: Nơi đây vốn lưu giữ nhiều bộ sưu tập phim, thú cưỡi của ông Geisel cũng được đỗ ở đây, nhưng những món đồ sưu tầm tượng trưng cho ước mơ và kỷ niệm này đã không còn nữa. Giờ đây, thú cưỡi của bạn và video quảng bá của Học viện Startorch được đặt ở đây, diễn giải những ước mơ và hy vọng mới.
- HV cũ: Nơi đây vốn lưu giữ nhiều bộ sưu tập phim, thú cưỡi của ông Geisel cũng được đỗ ở đây, nhưng những món đồ sưu tầm tượng trưng cho ước mơ và kỷ niệm này đã không còn nữa. Giờ đây, thú cưỡi của bạn và video quảng bá của Học Viện Startorch được đặt ở đây, diễn giải những ước mơ và hy vọng mới.
- HV V4: Nơi đây vốn lưu giữ nhiều bộ sưu tập phim, thú cưỡi của ông Geisel cũng được đỗ ở đây, nhưng những món đồ sưu tầm tượng trưng cho ước mơ và kỷ niệm này đã không còn nữa. Giờ đây, thú cưỡi của bạn và video quảng bá của Học viện Startorch được đặt ở đây, diễn giải những ước mơ và hy vọng mới.

### `lang_multi_text.db||MultiText||EpithetDesc_Role_23`
- HV cũ: Tuy tuổi còn nhỏ, nhưng đôi mắt của Dứu Hô đã có thể phân biệt được đồ cổ thật giả từ sớm. Sức nặng của những năm tháng mà chúng gánh vác đằng sau, chỉ khi giao phó cho người thấu hiểu được giá trị của chúng, thì mới có thể nhận được sự trân trọng và yêu thương.
- HV V4: Tuy tuổi còn nhỏ, nhưng đôi mắt của Youhu đã có thể phân biệt được đồ cổ thật giả từ sớm. Sức nặng của những năm tháng mà chúng gánh vác đằng sau, chỉ khi giao phó cho người thấu hiểu được giá trị của chúng, thì mới có thể nhận được sự trân trọng và yêu thương.

### `lang_multi_text.db||MultiText||EpithetDesc_Role_7`
- HV cũ: Chậm đi nửa nhịp, cũng đồng nghĩa với việc Đào Kỳ có nhiều thời gian hơn để quan sát thế giới, cô dần chú ý đến những thay đổi nhỏ bé trên đường phố, chỗ nào thiếu một viên gạch, chỗ nào lại có một bông hoa tàn. Mùa tiếp theo khi nào thì đến.
- HV V4: Chậm đi nửa nhịp, cũng đồng nghĩa với việc Đào Kì có nhiều thời gian hơn để quan sát thế giới, cô dần chú ý đến những thay đổi nhỏ bé trên đường phố, chỗ nào thiếu một viên gạch, chỗ nào lại có một bông hoa tàn. Mùa tiếp theo khi nào thì đến.

### `lang_multi_text.db||MultiText||EpithetSourceDesc_Role14`
- HV cũ: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Lăng Dương (Hiện đã kích hoạt ({0}/{1}))
- HV V4: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Lingyang (Hiện đã kích hoạt ({0}/{1}))

### `lang_multi_text.db||MultiText||EpithetSourceDesc_Role22`
- HV cũ: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Thủ Ngạn Nhân (Hiện đã kích hoạt ({0}/{1}))
- HV V4: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Shorekeeper (Hiện đã kích hoạt ({0}/{1}))

### `lang_multi_text.db||MultiText||EpithetSourceDesc_Role23`
- HV cũ: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Dứu Hô (Hiện đã kích hoạt ({0}/{1}))
- HV V4: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Youhu (Hiện đã kích hoạt ({0}/{1}))

### `lang_multi_text.db||MultiText||EpithetSourceDesc_Role41`
- HV cũ: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Cừu Viễn (Hiện đã kích hoạt ({0}/{1}))
- HV V4: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Qiuyuan (Hiện đã kích hoạt ({0}/{1}))

### `lang_multi_text.db||MultiText||EpithetSourceDesc_Role44`
- HV cũ: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Bốc Linh (Hiện đã kích hoạt ({0}/{1}))
- HV V4: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Buling (Hiện đã kích hoạt ({0}/{1}))

### `lang_multi_text.db||MultiText||EpithetSourceDesc_Role6`
- HV cũ: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Tán Hoa (Hiện đã kích hoạt ({0}/{1}))
- HV V4: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Sanhua (Hiện đã kích hoạt ({0}/{1}))

### `lang_multi_text.db||MultiText||EpithetSourceDesc_Role7`
- HV cũ: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Đào Kỳ (Hiện đã kích hoạt ({0}/{1}))
- HV V4: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Đào Kì (Hiện đã kích hoạt ({0}/{1}))

### `lang_multi_text.db||MultiText||EpithetSourceDesc_Role8`
- HV cũ: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Mortefi (Hiện đã kích hoạt ({0}/{1}))
- HV V4: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Mạc Đặc Phỉ (Hiện đã kích hoạt ({0}/{1}))

### `lang_multi_text.db||MultiText||EpithetSourcebriefDesc_Role_14`
- HV cũ: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Lăng Dương
- HV V4: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Lingyang

### `lang_multi_text.db||MultiText||EpithetSourcebriefDesc_Role_22`
- HV cũ: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Thủ Ngạn Nhân
- HV V4: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Shorekeeper

### `lang_multi_text.db||MultiText||EpithetSourcebriefDesc_Role_23`
- HV cũ: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Dứu Hô
- HV V4: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Youhu

### `lang_multi_text.db||MultiText||EpithetSourcebriefDesc_Role_41`
- HV cũ: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Cừu Viễn
- HV V4: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Qiuyuan

### `lang_multi_text.db||MultiText||EpithetSourcebriefDesc_Role_44`
- HV cũ: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Bốc Linh
- HV V4: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Buling

### `lang_multi_text.db||MultiText||EpithetSourcebriefDesc_Role_7`
- HV cũ: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Đào Kỳ
- HV V4: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Đào Kì

### `lang_multi_text.db||MultiText||EpithetSourcebriefDesc_Role_8`
- HV cũ: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Mortefi
- HV V4: Kích hoạt toàn bộ Chuỗi Cộng Hưởng của Mạc Đặc Phỉ

### `lang_multi_text.db||MultiText||FunctionCondition_10021_Desc`
- HV cũ: Trong trò chơi nhiều người có thể gặp gỡ các Lữ Khách khác, thái độ thân thiện nói không chừng có thể đổi lấy một tình bạn quý giá.
- HV V4: Trong trò chơi nhiều người có thể gặp gỡ các Rover khác, thái độ thân thiện nói không chừng có thể đổi lấy một tình bạn quý giá.

### `lang_multi_text.db||MultiText||FunctionCondition_10023001_Title`
- HV cũ: Nhật Ký Lữ Khách
- HV V4: Nhật Ký Rover

### `lang_multi_text.db||MultiText||FunctionCondition_10032_Desc`
- HV cũ: Lữ Khách có thể thu thập tài nguyên bồi dưỡng Echo bằng cách dọn dẹp Vùng Vô Thanh.
- HV V4: Rover có thể thu thập tài nguyên bồi dưỡng Echo bằng cách dọn dẹp Vùng Vô Thanh.

### `lang_multi_text.db||MultiText||FunctionCondition_10040_Desc`
- HV cũ: Lữ Khách có thể thông qua việc hoàn thành nhiệm vụ đài phát thanh, tích lũy kinh nghiệm nhiệm vụ, đổi lấy những phần thưởng phong phú.
- HV V4: Rover có thể thông qua việc hoàn thành nhiệm vụ đài phát thanh, tích lũy kinh nghiệm nhiệm vụ, đổi lấy những phần thưởng phong phú.

### `lang_multi_text.db||MultiText||FunctionCondition_10052_Desc`
- HV cũ: Lữ Khách có thể hấp thụ âm thanh của vạn vật, và điều hòa với chúng, thay đổi thuộc tính cộng hưởng của bản thân.
- HV V4: Rover có thể hấp thụ âm thanh của vạn vật, và điều hòa với chúng, thay đổi thuộc tính cộng hưởng của bản thân.

### `lang_multi_text.db||MultiText||FunctionCondition_10059_Desc`
- HV cũ: Lữ Khách có thể thu thập vật liệu nâng cấp cho nhân vật, vũ khí và Echo bằng cách dọn dẹp Lĩnh Vực Âm Thanh.
- HV V4: Rover có thể thu thập vật liệu nâng cấp cho nhân vật, vũ khí và Echo bằng cách dọn dẹp Lĩnh Vực Âm Thanh.

### `lang_multi_text.db||MultiText||FunctionCondition_10098_Desc`
- VI cũ: Được đồng phát triển bởi Khoa Công Nghệ Đường Hầm và Khoa Khoa Học Vật Chất Ảo của Học Viện Startorch, một phương tiện di chuyển hạng nhẹ có khả năng thích ứng với mọi địa hình. Vì tầm quan trọng của nó trong khảo sát khoa học, Học Viện Startorch không chỉ mở các khóa học lái xe chuyên nghiệp, mà còn trải nhựa nhiều đường đua huấn luyện quanh học viện, để đáp ứng nhu cầu của giáo viên và học sinh học viện.
- VI V4: Được đồng phát triển bởi Khoa Công Nghệ Đường Hầm và Khoa Khoa Học Vật Chất Ảo của Học viện Startorch, một phương tiện di chuyển hạng nhẹ có khả năng thích ứng với mọi địa hình. Vì tầm quan trọng của nó trong khảo sát khoa học, Học viện Startorch không chỉ mở các khóa học lái xe chuyên nghiệp, mà còn trải nhựa nhiều đường đua huấn luyện quanh học viện, để đáp ứng nhu cầu của giáo viên và học sinh học viện.
- HV cũ: Được đồng phát triển bởi Khoa Công Nghệ Đường Hầm và Khoa Khoa Học Vật Chất Ảo của Học Viện Startorch, một phương tiện di chuyển hạng nhẹ có khả năng thích ứng với mọi địa hình. Vì tầm quan trọng của nó trong khảo sát khoa học, Học Viện Startorch không chỉ mở các khóa học lái xe chuyên nghiệp, mà còn trải nhựa nhiều đường đua huấn luyện quanh học viện, để đáp ứng nhu cầu của giáo viên và học sinh học viện.
- HV V4: Được đồng phát triển bởi Khoa Công Nghệ Đường Hầm và Khoa Khoa Học Vật Chất Ảo của Học viện Startorch, một phương tiện di chuyển hạng nhẹ có khả năng thích ứng với mọi địa hình. Vì tầm quan trọng của nó trong khảo sát khoa học, Học viện Startorch không chỉ mở các khóa học lái xe chuyên nghiệp, mà còn trải nhựa nhiều đường đua huấn luyện quanh học viện, để đáp ứng nhu cầu của giáo viên và học sinh học viện.

### `lang_multi_text.db||MultiText||FunctionCondition_10146_Desc`
- HV cũ: Trong "Trang Trí Tiệc", Lữ Khách có thể nhận được nhiều loại đồ trang trí, và sử dụng những đồ trang trí này để tùy chỉnh không gian tổ chức tiệc theo cá tính riêng.
- HV V4: Trong "Trang Trí Tiệc", Rover có thể nhận được nhiều loại đồ trang trí, và sử dụng những đồ trang trí này để tùy chỉnh không gian tổ chức tiệc theo cá tính riêng.

### `lang_multi_text.db||MultiText||FunctionCondition_110058_Desc`
- HV cũ: Lữ Khách có thể nhận được vật liệu đột phá nhân vật bằng cách thảo phạt cường địch.
- HV V4: Rover có thể nhận được vật liệu đột phá nhân vật bằng cách thảo phạt cường địch.

### `lang_multi_text.db||MultiText||GenericPrompt_1130000021_ExtraText`
- HV cũ: test|Tiếp theo đi tìm Xuân thôi
- HV V4: test|Tiếp theo đi tìm Camellya thôi

### `lang_multi_text.db||MultiText||MenuConfig_77_Name`
- HV cũ: Chuyển Lữ Khách
- HV V4: Chuyển Rover

### `lang_multi_text.db||MultiText||MenuConfig_77_OptionsName_0`
- HV cũ: Lữ Khách (Nữ)
- HV V4: Rover (Nữ)

### `lang_multi_text.db||MultiText||MenuConfig_77_OptionsName_1`
- HV cũ: Lữ Khách (Nam)
- HV V4: Rover (Nam)

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_1_1`
- HV cũ: Đã thêm Lâm Nại vào danh sách bạn bè
- HV V4: Đã thêm Lynae vào danh sách bạn bè

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_1_11`
- VI cũ: Hiện Tại thế nào rồi, vẫn thuận lợi chứ?
- VI V4: Giờ thế nào rồi, vẫn thuận lợi chứ?
- HV cũ: Hiện Tại thế nào rồi, vẫn thuận lợi chứ?
- HV V4: Giờ thế nào rồi, vẫn thuận lợi chứ?

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_1_15`
- VI cũ: Vậy thì tốt
- VI V4: Vậy là tốt rồi!
- HV cũ: Vậy thì tốt
- HV V4: Vậy là tốt rồi!

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_1_18`
- VI cũ: Cứ tóm đại ai đó rồi hỏi phòng khắc ghi Băng Từ ở đâu là được mà
- VI V4: Cứ tìm đại ai đó hỏi Phòng Ghi Băng Từ ở đâu là được mà!
- HV cũ: Cứ tóm đại ai đó rồi hỏi phòng khắc ghi Băng Từ ở đâu là được mà
- HV V4: Cứ tìm đại ai đó hỏi Phòng Ghi Băng Từ ở đâu là được mà!

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_1_19`
- VI cũ: Đừng căng thẳng, các tiền bối đều rất dịu dàng đó!
- VI V4: Đừng căng thẳng, các tiền bối đều dễ tính lắm!
- HV cũ: Đừng căng thẳng, các tiền bối đều rất dịu dàng đó!
- HV V4: Đừng căng thẳng, các tiền bối đều dễ tính lắm!

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_3_11`
- VI cũ: Trong tình huống đó mà vẫn chụp được tấm Bức Ảnh rõ thế này, làm sao mà chụp được nhỉ......
- VI V4: Trong tình huống đó mà vẫn chụp được ảnh rõ thế này, làm kiểu gì vậy...
- HV cũ: Trong tình huống đó mà vẫn chụp được tấm Bức Ảnh rõ thế này, làm sao mà chụp được nhỉ......
- HV V4: Trong tình huống đó mà vẫn chụp được ảnh rõ thế này, làm kiểu gì vậy...

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_3_12`
- VI cũ: Bây giờ gần như cả Học Viện đều biết rồi...... Từ giờ trở đi, tụi mình là "Kỵ Sĩ Sâu Hư Không" đấy
- VI V4: Giờ gần như cả học viện đều biết rồi... Từ hôm nay, tụi mình chính thức là "Kỵ Sĩ Trùng Hư Đản" đấy.
- HV cũ: Bây giờ gần như cả Học Viện đều biết rồi...... Từ giờ trở đi, tụi mình là "Kỵ Sĩ Sâu Hư Không" đấy
- HV V4: Giờ gần như cả học viện đều biết rồi... Từ hôm nay, tụi mình chính thức là "Kỵ Sĩ Trùng Hư Đản" đấy.

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_3_13`
- VI cũ: Bài báo này còn nói tụi mình là "anh hùng" đã cứu Học Viện nữa, tớ chẳng biết phải phản ứng thế nào luôn......
- VI V4: Bài báo còn gọi tụi mình là "anh hùng" đã cứu học viện nữa. Tớ chẳng biết nên phản ứng thế nào luôn...
- HV cũ: Bài báo này còn nói tụi mình là "anh hùng" đã cứu Học Viện nữa, tớ chẳng biết phải phản ứng thế nào luôn......
- HV V4: Bài báo còn gọi tụi mình là "anh hùng" đã cứu học viện nữa. Tớ chẳng biết nên phản ứng thế nào luôn...

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_3_19`
- VI cũ: Hiện Tại cậu có rảnh không?
- VI V4: Giờ cậu có rảnh không?
- HV cũ: Hiện Tại cậu có rảnh không?
- HV V4: Giờ cậu có rảnh không?

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_3_22`
- VI cũ: Hiện Tại hơi......
- VI V4: Giờ thì hơi...
- HV cũ: Hiện Tại hơi......
- HV V4: Giờ thì hơi...

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_3_24`
- VI cũ: Tớ đợi cậu ở Vườn Học Viện nhé!
- VI V4: Tớ đợi cậu ở vườn học viện nhé!
- HV cũ: Tớ đợi cậu ở Vườn Học Viện nhé!
- HV V4: Tớ đợi cậu ở vườn học viện nhé!

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_3_26`
- VI cũ: Vậy tớ sẽ ngồi đợi cậu ở Vườn Học Viện một lát nhé
- VI V4: Vậy tớ sẽ đợi cậu ở vườn học viện một lát nhé.
- HV cũ: Vậy tớ sẽ ngồi đợi cậu ở Vườn Học Viện một lát nhé
- HV V4: Vậy tớ sẽ đợi cậu ở vườn học viện một lát nhé.

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_3_3`
- HV cũ: [Lâm Nại gửi đến một Bức Ảnh.]
- HV V4: [Lynae gửi đến một Bức Ảnh.]

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_3_30`
- VI cũ: Hiện Tại hơi......
- VI V4: Giờ thì hơi...
- HV cũ: Hiện Tại hơi......
- HV V4: Giờ thì hơi...

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_3_4`
- VI cũ: Nhấp để xem: CHẤN ĐỘNG! Xoay chuyển càn khôn giữa cơn khủng hoảng! Hai học viên Lớp Dự bị dũng cảm chiến đấu với Sâu Hư Không!
- VI V4: Nhấp để xem: CHẤN ĐỘNG! Xoay chuyển càn khôn giữa cơn khủng hoảng! Hai học viên Lớp Dự bị dũng cảm chiến đấu với Trùng Hư Đản!
- HV cũ: Nhấp để xem: CHẤN ĐỘNG! Xoay chuyển càn khôn giữa cơn khủng hoảng! Hai học viên Lớp Dự bị dũng cảm chiến đấu với Sâu Hư Không!
- HV V4: Nhấp để xem: CHẤN ĐỘNG! Xoay chuyển càn khôn giữa cơn khủng hoảng! Hai học viên Lớp Dự bị dũng cảm chiến đấu với Trùng Hư Đản!

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_4_10`
- VI cũ: Để kỷ niệm lần đầu tiên chúng ta gặp nhau, và cùng Sát Cánh chiến đấu nữa!
- VI V4: Để kỷ niệm lần đầu chúng ta gặp nhau và cả lần cùng nhau chiến đấu nữa!
- HV cũ: Để kỷ niệm lần đầu tiên chúng ta gặp nhau, và cùng Sát Cánh chiến đấu nữa!
- HV V4: Để kỷ niệm lần đầu chúng ta gặp nhau và cả lần cùng nhau chiến đấu nữa!

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_4_13`
- VI cũ: Coi như là kỷ niệm chúng ta đã từng Sát Cánh chiến đấu nhé
- VI V4: Coi như kỷ niệm lần chúng ta từng sát cánh chiến đấu nhé.
- HV cũ: Coi như là kỷ niệm chúng ta đã từng Sát Cánh chiến đấu nhé
- HV V4: Coi như kỷ niệm lần chúng ta từng sát cánh chiến đấu nhé.

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_4_21`
- VI cũ: Mong chờ lần tới được cùng cậu đi dạo lắm đó!
- VI V4: Tớ mong lần tới lại được cùng cậu đi hóng gió!
- HV cũ: Mong chờ lần tới được cùng cậu đi dạo lắm đó!
- HV V4: Tớ mong lần tới lại được cùng cậu đi hóng gió!

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_4_24`
- VI cũ: Sau này cũng mong cậu chỉ giáo nhiều thêm ạ!
- VI V4: Sau này cũng mong cậu giúp đỡ tớ nhiều nhé!
- HV cũ: Sau này cũng mong cậu chỉ giáo nhiều thêm ạ!
- HV V4: Sau này cũng mong cậu giúp đỡ tớ nhiều nhé!

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_4_26`
- VI cũ: Nhớ kiểm tra nhận hàng nhé
- VI V4: Nhớ nhận nhé!
- HV cũ: Nhớ kiểm tra nhận hàng nhé
- HV V4: Nhớ nhận nhé!

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_5_10`
- VI cũ: Thầy nói thời kỳ Bão Từ vẫn chưa qua, liên lạc không thể kết nối, từ đây cũng không thể liên hệ được với Người Giữ Bờ...
- VI V4: Các thầy cô nói đợt Bão Từ vẫn chưa qua, liên lạc vẫn chưa thể kết nối. Từ đây em cũng không liên hệ được với Shorekeeper...
- HV cũ: Thầy nói thời kỳ Bão Từ vẫn chưa qua, liên lạc không thể kết nối, từ đây cũng không thể liên hệ được với Người Giữ Bờ...
- HV V4: Các thầy cô nói đợt Bão Từ vẫn chưa qua, liên lạc vẫn chưa thể kết nối. Từ đây em cũng không liên hệ được với Shorekeeper...

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_5_13`
- VI cũ: hy vọng {PlayerName} bình an.
- VI V4: Hy vọng {PlayerName} bình an.
- HV cũ: hy vọng {PlayerName} bình an.
- HV V4: Hy vọng {PlayerName} bình an.

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_5_20`
- VI cũ: {Male=Xin lỗi đã làm cậu lo, tớ đã đến Học Viện rồi.;Female=Xin lỗi đã làm cậu lo, tớ đã đến Học Viện rồi.}
- VI V4: {Male=Xin lỗi đã làm cậu lo. Tớ đến học viện rồi.;Female=Xin lỗi đã làm cậu lo. Tớ đến học viện rồi.}
- HV cũ: {Male=Xin lỗi đã làm cậu lo, tớ đã đến Học Viện rồi.;Female=Xin lỗi đã làm cậu lo, tớ đã đến Học Viện rồi.}
- HV V4: {Male=Xin lỗi đã làm cậu lo. Tớ đến học viện rồi.;Female=Xin lỗi đã làm cậu lo. Tớ đến học viện rồi.}

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_5_22`
- VI cũ: {Male=Tớ đã gặp chút chuyện ngoài ý muốn, nhưng Hiện Tại đã đến Học Viện an toàn rồi.;Female=Tớ đã gặp chút chuyện ngoài ý muốn, nhưng Hiện Tại đã đến Học Viện an toàn rồi.}
- VI V4: {Male=Tớ gặp chút chuyện ngoài dự tính, nhưng giờ đã đến học viện an toàn rồi.;Female=Tớ gặp chút chuyện ngoài dự tính, nhưng giờ đã đến học viện an toàn rồi.}
- HV cũ: {Male=Tớ đã gặp chút chuyện ngoài ý muốn, nhưng Hiện Tại đã đến Học Viện an toàn rồi.;Female=Tớ đã gặp chút chuyện ngoài ý muốn, nhưng Hiện Tại đã đến Học Viện an toàn rồi.}
- HV V4: {Male=Tớ gặp chút chuyện ngoài dự tính, nhưng giờ đã đến học viện an toàn rồi.;Female=Tớ gặp chút chuyện ngoài dự tính, nhưng giờ đã đến học viện an toàn rồi.}

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_5_4`
- VI cũ: Không biết Hiện Tại {PlayerName} đang ở đâu nhỉ?
- VI V4: Không biết bây giờ {PlayerName} đang ở đâu nhỉ?
- HV cũ: Không biết Hiện Tại {PlayerName} đang ở đâu nhỉ?
- HV V4: Không biết bây giờ {PlayerName} đang ở đâu nhỉ?

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_5_5`
- VI cũ: Học Viện quả nhiên đã có nhiều thay đổi...
- VI V4: Học viện quả nhiên đã thay đổi rất nhiều...
- HV cũ: Học Viện quả nhiên đã có nhiều thay đổi...
- HV V4: Học viện quả nhiên đã thay đổi rất nhiều...

### `lang_multi_text.db||MultiText||Message_Main_LahaiRoi_3_1_5_6`
- VI cũ: Nhưng... các Thầy ở Học Viện đều rất tốt, vừa nắm được tình hình đã lập tức làm thủ tục Hồi phục nhập học Startorch cho em.
- VI V4: Nhưng... các thầy cô ở học viện đều rất tốt. Họ nhanh chóng hiểu tình hình và làm thủ tục nhập học lại cho em.
- HV cũ: Nhưng... các Thầy ở Học Viện đều rất tốt, vừa nắm được tình hình đã lập tức làm thủ tục Hồi phục nhập học Startorch cho em.
- HV V4: Nhưng... các thầy cô ở học viện đều rất tốt. Họ nhanh chóng hiểu tình hình và làm thủ tục nhập học lại cho em.

### `lang_multi_text.db||MultiText||PlotType_11002_TypeDescription`
- HV cũ: Lăng Dương
- HV V4: Lingyang

### `lang_multi_text.db||MultiText||PrefabTextItem_1139834134_Text`
- VI cũ: Trong thời gian liên kết, có thể nhận Cộng Minh Giả 5 Sao <color=#ff4444>Rebecca</color> miễn phí qua Sự kiện
- VI V4: Trong thời gian liên kết, có thể nhận Cộng Hưởng Giả 5 Sao <color=#ff4444>Rebecca</color> miễn phí qua Sự kiện
- HV cũ: Trong thời gian liên kết, có thể nhận Cộng Minh Giả 5 Sao <color=#ff4444>Rebecca</color> miễn phí qua Sự kiện
- HV V4: Trong thời gian liên kết, có thể nhận Cộng Hưởng Giả 5 Sao <color=#ff4444>Rebecca</color> miễn phí qua Sự kiện

### `lang_multi_text.db||MultiText||PrefabTextItem_1140000000_Text`
- VI cũ: Trong thời gian liên động, có thể nhận Cộng Minh Giả 5 Sao <color=#ff4444>Rebecca</color> qua Sự kiện
- VI V4: Trong thời gian liên động, có thể nhận Cộng Hưởng Giả 5 Sao <color=#ff4444>Rebecca</color> qua Sự kiện
- HV cũ: Trong thời gian liên động, có thể nhận Cộng Minh Giả 5 Sao <color=#ff4444>Lệ Bối Tạp</color> qua Sự kiện
- HV V4: Trong thời gian liên động, có thể nhận Cộng Hưởng Giả 5 Sao <color=#ff4444>Rebecca</color> qua Sự kiện

### `lang_multi_text.db||MultiText||PrefabTextItem_2136239050_Text`
- HV cũ: Thủ Ngạn Nhân sẽ phụ trách đệm đàn piano, Phoebe đến hát;
- HV V4: Shorekeeper sẽ phụ trách đệm đàn piano, Phoebe đến hát;

### `lang_multi_text.db||MultiText||PrefabTextItem_3586990539_Text`
- HV cũ: Tích lũy nhận <texture=/Game/Aki/UI/UIResources/UiActivity/Image/Activity31/CumulativeRecharge/Common/T_TempScoreIcon·T_TempScoreIcon,0.5/>980\ncó thể chọn một trong các nhân vật: <color=#ffd12f>Thủ Ngạn Nhân, Camellya, Kim Tịch</color>.
- HV V4: Tích lũy nhận <texture=/Game/Aki/UI/UIResources/UiActivity/Image/Activity31/CumulativeRecharge/Common/T_TempScoreIcon·T_TempScoreIcon,0.5/>980\ncó thể chọn một trong các nhân vật: <color=#ffd12f>Shorekeeper, Camellya, Kim Tịch</color>.

### `lang_multi_text.db||MultiText||PrefabTextItem_794032217_Text`
- HV cũ: Ánh mắt bình tĩnh không chút gợn sóng của Cừu Viễn chuyển hướng về phía cậu.
- HV V4: Ánh mắt bình tĩnh không chút gợn sóng của Qiuyuan chuyển hướng về phía cậu.

### `lang_multi_text.db||MultiText||PrefabTextItem_814702022_Text`
- HV cũ: Lúc này, trong mắt Cừu Viễn…
- HV V4: Lúc này, trong mắt Qiuyuan…

### `lang_multi_text.db||MultiText||SMC_Name_27`
- VI cũ: Nhóm Thảo Luận Học Viện Startorch-Phòng Vận Hành
- VI V4: Nhóm Thảo Luận Học viện Startorch-Phòng Vận Hành
- HV cũ: Nhóm Thảo Luận Học Viện Startorch-Phòng Vận Hành
- HV V4: Nhóm Thảo Luận Học viện Startorch-Phòng Vận Hành

### `lang_multi_text.db||MultiText||SMC_Name_32`
- VI cũ: Hệ Thống Giáo Vụ Học Viện Startorch
- VI V4: Hệ Thống Giáo Vụ Học viện Startorch
- HV cũ: Hệ Thống Giáo Vụ Học Viện Startorch
- HV V4: Hệ Thống Giáo Vụ Học viện Startorch

### `lang_multi_text.db||MultiText||SMC_Name_42`
- HV cũ: Thủ Ngạn Nhân
- HV V4: Shorekeeper

### `lang_multi_text.db||MultiText||SMC_Name_52`
- HV cũ: Cừu Viễn
- HV V4: Qiuyuan

### `lang_multi_text.db||MultiText||SMC_Name_53`
- VI cũ: Học Viện Startorch
- VI V4: Học viện Startorch
- HV cũ: Học Viện Startorch
- HV V4: Học viện Startorch

### `lang_multi_text.db||MultiText||SMC_Name_55`
- VI cũ: Thu Nước
- VI V4: Aalto
- HV cũ: Thu Nước
- HV V4: Thu Thủy

### `lang_multi_text.db||MultiText||SMC_Name_56`
- VI cũ: Đăng Đăng
- VI V4: Lumi
- HV cũ: Đăng Đăng
- HV V4: Lumi

### `lang_multi_text.db||MultiText||SMC_Name_68`
- VI cũ: Mặt Tối Nhất Của Học Viện Startorch
- VI V4: Mặt Tối Nhất Của Học viện Startorch
- HV cũ: Mặt Tối Nhất Của Học Viện Startorch
- HV V4: Mặt Tối Nhất Của Học viện Startorch

### `lang_multi_text.db||MultiText||phone_JL_10_1`
- VI cũ: Septimont thật đẹp, mọi người uống thỏa thuê, cười vang sảng khoái, phóng khoáng đến vậy, nồng nhiệt đến vậy.
- VI V4: Septimont đẹp thật. Mọi người uống hết mình, cười thật sảng khoái—phóng khoáng và nồng nhiệt biết bao.
- HV cũ: Septimont thật đẹp, mọi người uống thỏa thuê, cười vang sảng khoái, phóng khoáng đến vậy, nồng nhiệt đến vậy.
- HV V4: Septimont đẹp thật. Mọi người uống hết mình, cười thật sảng khoái—phóng khoáng và nồng nhiệt biết bao.

### `lang_multi_text.db||MultiText||phone_JL_10_2`
- VI cũ: Salad Nguyệt Quế xanh vẫn ngon như trước, nước ép lúa mì cũng rất dễ uống… hêhê.
- VI V4: Salad Nguyệt Quế Xanh vẫn ngon như trước, nước lúa mì cũng rất dễ uống... hehe.
- HV cũ: Salad Nguyệt Quế xanh vẫn ngon như trước, nước ép lúa mì cũng rất dễ uống… hêhê.
- HV V4: Salad Nguyệt Quế Xanh vẫn ngon như trước, nước lúa mì cũng rất dễ uống... hehe.

### `lang_multi_text.db||MultiText||phone_JL_10_3`
- VI cũ: Trước khi "Thủy triều dâng" của Khu săn tới, hãy nghỉ ngơi một chút và tận hưởng giây phút hiện tại đi nhé.
- VI V4: Trước khi "mùa triều dâng" ở Khu Săn đến, cứ nghỉ ngơi một chút và tận hưởng hiện tại nhé.
- HV cũ: Trước khi "Thủy triều dâng" của Khu săn tới, hãy nghỉ ngơi một chút và tận hưởng giây phút hiện tại đi nhé.
- HV V4: Trước khi "mùa triều dâng" ở Khu Săn đến, cứ nghỉ ngơi một chút và tận hưởng hiện tại nhé.

### `lang_multi_text.db||MultiText||phone_JL_10_4`
- VI cũ: Nghe kìa, làn Phong mát lành thổi qua những lá Cờ Hiệu màu vàng cam và Chuông gió, phát ra âm thanh leng keng.
- VI V4: Nghe kìa, gió mát lướt qua những lá cờ vàng cam và chuông gió, tạo nên tiếng leng keng.
- HV cũ: Nghe kìa, làn Phong mát lành thổi qua những lá Cờ Hiệu màu vàng cam và Chuông gió, phát ra âm thanh leng keng.
- HV V4: Nghe kìa, gió mát lướt qua những lá cờ vàng cam và chuông gió, tạo nên tiếng leng keng.

### `lang_multi_text.db||MultiText||phone_JL_11_1`
- VI cũ: Chuyện Khu Thử Nghiệm Ẩn Hải, tôi đã báo cáo toàn bộ rồi.
- VI V4: Chuyện ở Khu Thử Nghiệm Ẩn Hải, tôi đã báo cáo đầy đủ rồi.
- HV cũ: Chuyện Khu Thử Nghiệm Ẩn Hải, tôi đã báo cáo toàn bộ rồi.
- HV V4: Chuyện ở Khu Thử Nghiệm Ẩn Hải, tôi đã báo cáo đầy đủ rồi.

### `lang_multi_text.db||MultiText||phone_JL_11_2`
- VI cũ: Tuy là báo cáo phải tăng ca mới xong… nhưng ca tăng lần này rất đáng.
- VI V4: Bản báo cáo đúng là phải tăng ca mới xong... nhưng lần tăng ca này rất đáng.
- HV cũ: Tuy là báo cáo phải tăng ca mới xong… nhưng ca tăng lần này rất đáng.
- HV V4: Bản báo cáo đúng là phải tăng ca mới xong... nhưng lần tăng ca này rất đáng.

### `lang_multi_text.db||MultiText||phone_JL_11_3`
- VI cũ: Dù sao thì đây là chuyện lớn liên quan đến an nguy của toàn Rinascita.
- VI V4: Dù sao đây cũng là chuyện lớn liên quan đến an nguy của cả Rinascita.
- HV cũ: Dù sao thì đây là chuyện lớn liên quan đến an nguy của toàn Rinascita.
- HV V4: Dù sao đây cũng là chuyện lớn liên quan đến an nguy của cả Rinascita.

### `lang_multi_text.db||MultiText||phone_JL_11_4`
- VI cũ: Ngài cứ yên tâm tới Septimont bên đó Điều tra đi.
- VI V4: Ngài cứ yên tâm sang Septimont điều tra đi.
- HV cũ: Ngài cứ yên tâm tới Septimont bên đó Điều tra đi.
- HV V4: Ngài cứ yên tâm sang Septimont điều tra đi.

### `lang_multi_text.db||MultiText||phone_JL_11_5`
- VI cũ: Ragunna đã có chúng tôi.
- VI V4: Ragunna đã có chúng tôi lo.
- HV cũ: Ragunna đã có chúng tôi.
- HV V4: Ragunna đã có chúng tôi lo.

### `lang_multi_text.db||MultiText||phone_JL_12_1`
- VI cũ: Bạn thân, cậu đã tận hưởng Chiến thắng thuộc về chúng ta bên đống lửa trại tại Trại Săn Bắn chưa?
- VI V4: Bạn thân, cậu đã tận hưởng chiến thắng của chúng ta bên đống lửa ở trại săn chưa?
- HV cũ: Bạn thân, cậu đã tận hưởng Chiến thắng thuộc về chúng ta bên đống lửa trại tại Trại Săn Bắn chưa?
- HV V4: Bạn thân, cậu đã tận hưởng chiến thắng của chúng ta bên đống lửa ở trại săn chưa?

### `lang_multi_text.db||MultiText||phone_JL_12_2`
- VI cũ: Chiến thắng này thuộc về mỗi người chúng ta.
- VI V4: Chiến thắng này thuộc về tất cả mọi người.
- HV cũ: Chiến thắng này thuộc về mỗi người chúng ta.
- HV V4: Chiến thắng này thuộc về tất cả mọi người.

### `lang_multi_text.db||MultiText||phone_JL_12_3`
- VI cũ: Mình vẫn đang suy nghĩ về những việc sau Chiến thắng này.
- VI V4: Mình vẫn đang nghĩ về những chuyện sau chiến thắng này.
- HV cũ: Mình vẫn đang suy nghĩ về những việc sau Chiến thắng này.
- HV V4: Mình vẫn đang nghĩ về những chuyện sau chiến thắng này.

### `lang_multi_text.db||MultiText||phone_JL_12_4`
- VI cũ: Ừ, mình đã cảm nhận được cảm xúc nồng nhiệt của mọi người trong Nhà.
- VI V4: Ừ, mình đã cảm nhận được sự nhiệt tình của mọi người rồi.
- HV cũ: Ừ, mình đã cảm nhận được cảm xúc nồng nhiệt của mọi người trong Nhà.
- HV V4: Ừ, mình đã cảm nhận được sự nhiệt tình của mọi người rồi.

### `lang_multi_text.db||MultiText||phone_JL_12_5`
- VI cũ: Ừm… mình vẫn đang nghĩ về chuyện Di vật của Tuế Chủ.
- VI V4: Ừm... mình vẫn đang nghĩ về di vật của Tuế Chủ.
- HV cũ: Ừm… mình vẫn đang nghĩ về chuyện Di vật của Tuế Chủ.
- HV V4: Ừm... mình vẫn đang nghĩ về di vật của Tuế Chủ.

### `lang_multi_text.db||MultiText||phone_JL_12_6`
- VI cũ: Cứ thả lỏng đi, có nghỉ ngơi đủ rồi mới có sức mạnh để Khởi Hành Chinh chiến thêm lần nữa.
- VI V4: Thả lỏng một chút đi. Nghỉ ngơi đầy đủ rồi mới có sức lên đường chiến đấu lần nữa.
- HV cũ: Cứ thả lỏng đi, có nghỉ ngơi đủ rồi mới có sức mạnh để Khởi Hành Chinh chiến thêm lần nữa.
- HV V4: Thả lỏng một chút đi. Nghỉ ngơi đầy đủ rồi mới có sức lên đường chiến đấu lần nữa.

### `lang_multi_text.db||MultiText||phone_JL_12_7`
- VI cũ: Ánh lửa (Ánh sáng) phản chiếu niềm tin (Thư) giữa chúng ta. Chỉ khi mọi người trong Nhà cùng sát cánh, Cờ Hiệu Septimont mới mãi mãi vững vàng không đổ.
- VI V4: Ánh lửa soi rõ niềm tin giữa chúng ta. Chỉ khi mọi người ở bên nhau, lá cờ Septimont mới có thể mãi đứng vững.
- HV cũ: Ánh lửa (Ánh sáng) phản chiếu niềm tin (Thư) giữa chúng ta. Chỉ khi mọi người trong Nhà cùng sát cánh, Cờ Hiệu Septimont mới mãi mãi vững vàng không đổ.
- HV V4: Ánh lửa soi rõ niềm tin giữa chúng ta. Chỉ khi mọi người ở bên nhau, lá cờ Septimont mới có thể mãi đứng vững.

### `lang_multi_text.db||MultiText||phone_JL_12_8`
- VI cũ: Dù con đường phía trước còn bao hiểm trở, nếu gặp chuyện gì, hãy liên lạc với ta bất cứ lúc nào.
- VI V4: Dù phía trước còn bao hiểm nguy, có chuyện gì thì cứ liên lạc với ta bất cứ lúc nào.
- HV cũ: Dù con đường phía trước còn bao hiểm trở, nếu gặp chuyện gì, hãy liên lạc với ta bất cứ lúc nào.
- HV V4: Dù phía trước còn bao hiểm nguy, có chuyện gì thì cứ liên lạc với ta bất cứ lúc nào.

### `lang_multi_text.db||MultiText||phone_JL_12_9`
- VI cũ: Tôi sẽ không bỏ lỡ bất kỳ cơ hội nào được Sát Cánh chiến đấu cùng cậu.
- VI V4: Ta sẽ không bỏ lỡ bất cứ cơ hội nào được sát cánh chiến đấu cùng cậu.
- HV cũ: Tôi sẽ không bỏ lỡ bất kỳ cơ hội nào được Sát Cánh chiến đấu cùng cậu.
- HV V4: Ta sẽ không bỏ lỡ bất cứ cơ hội nào được sát cánh chiến đấu cùng cậu.

### `lang_multi_text.db||MultiText||phone_JL_14_1`
- VI cũ: Sau khi rời Hắc Hải Ngạn, ta vẫn như trước, tìm kiếm, truy đuổi, đi săn…
- VI V4: Sau khi rời Bờ Biển Đen, ta vẫn như trước: tìm kiếm, truy đuổi, săn lùng...
- HV cũ: Sau khi rời Hắc Hải Ngạn, ta vẫn như trước, tìm kiếm, truy đuổi, đi săn…
- HV V4: Sau khi rời Bờ Biển Đen, ta vẫn như trước: tìm kiếm, truy đuổi, săn lùng...

### `lang_multi_text.db||MultiText||phone_JL_14_2`
- VI cũ: Có điều, tâm cảnh đã có chút thay đổi so với trước…
- VI V4: Nhưng tâm cảnh của ta so với trước đây đã thay đổi đôi chút...
- HV cũ: Có điều, tâm cảnh đã có chút thay đổi so với trước…
- HV V4: Nhưng tâm cảnh của ta so với trước đây đã thay đổi đôi chút...

### `lang_multi_text.db||MultiText||phone_JL_14_3`
- VI cũ: Có lẽ là vì Hắc Hoa trên vai này…
- VI V4: Có lẽ là vì bông hoa đen trên vai này...
- HV cũ: Có lẽ là vì Hắc Hoa trên vai này…
- HV V4: Có lẽ là vì bông hoa đen trên vai này...

### `lang_multi_text.db||MultiText||phone_JL_14_5`
- VI cũ: Khiến ta biết rằng mình không còn cô đơn nữa.
- VI V4: Nó khiến ta hiểu rằng mình không còn đơn độc nữa.
- HV cũ: Khiến ta biết rằng mình không còn cô đơn nữa.
- HV V4: Nó khiến ta hiểu rằng mình không còn đơn độc nữa.

### `lang_multi_text.db||MultiText||phone_JL_17_1`
- VI cũ: Tiếp theo, mình sẽ phải ở lại Hắc Hải Ngạn và Thành phố Honami (Tuệ Ba) thêm một thời gian nữa.
- VI V4: Tiếp theo, mình sẽ ở lại Bờ Biển Đen và Honami thêm một thời gian.
- HV cũ: Tiếp theo, mình sẽ phải ở lại Hắc Hải Ngạn và Thành phố Honami (Tuệ Ba) thêm một thời gian nữa.
- HV V4: Tiếp theo, mình sẽ ở lại Bờ Biển Đen và Honami thêm một thời gian.

### `lang_multi_text.db||MultiText||phone_JL_17_2`
- VI cũ: Cứ coi đây như là một kỳ nghỉ trước khi trở lại trường nhé?
- VI V4: Cứ xem như một kỳ nghỉ ngắn trước khi quay lại trường vậy.
- HV cũ: Cứ coi đây như là một kỳ nghỉ trước khi trở lại trường nhé?
- HV V4: Cứ xem như một kỳ nghỉ ngắn trước khi quay lại trường vậy.

### `lang_multi_text.db||MultiText||phone_JL_17_3`
- VI cũ: Nghe Namipon nói, ở Tuệ Ba vẫn còn rất nhiều vấn đề tồn đọng chưa được giải quyết.
- VI V4: Nghe Namipon nói, ở Honami vẫn còn nhiều vấn đề tồn đọng chưa được giải quyết.
- HV cũ: Nghe Namipon nói, ở Tuệ Ba vẫn còn rất nhiều vấn đề tồn đọng chưa được giải quyết.
- HV V4: Nghe Namipon nói, ở Honami vẫn còn nhiều vấn đề tồn đọng chưa được giải quyết.

### `lang_multi_text.db||MultiText||phone_JL_17_4`
- VI cũ: Nếu cậu có hứng thú, chúng ta có thể Điều tra thêm một chút.
- VI V4: Nếu cậu hứng thú, chúng ta có thể điều tra thêm.
- HV cũ: Nếu cậu có hứng thú, chúng ta có thể Điều tra thêm một chút.
- HV V4: Nếu cậu hứng thú, chúng ta có thể điều tra thêm.

### `lang_multi_text.db||MultiText||phone_JL_17_5`
- VI cũ: Đương nhiên, chúng ta cùng nhau.
- VI V4: Tất nhiên rồi, chúng ta cùng đi.
- HV cũ: Đương nhiên, chúng ta cùng nhau.
- HV V4: Tất nhiên rồi, chúng ta cùng đi.

### `lang_multi_text.db||MultiText||phone_JL_4_14`
- VI cũ: Ta chỉ là người dẫn đường mà thôi. Hơn nữa, thọ số do trời định, không cần phải bận lòng.
- VI V4: Ta chỉ dẫn đường mà thôi. Hơn nữa, thọ mệnh do trời định, không cần bận lòng.
- HV cũ: Ta chỉ là người dẫn đường mà thôi. Hơn nữa, thọ số do trời định, không cần phải bận lòng.
- HV V4: Ta chỉ dẫn đường mà thôi. Hơn nữa, thọ mệnh do trời định, không cần bận lòng.

### `lang_multi_text.db||MultiText||phone_JL_4_2`
- VI cũ: Bạn đồng hành, thượng khách, Ngự Giả… nhiều danh xưng đến vậy, ta nên gọi ngươi thế nào đây?
- VI V4: Bạn đồng hành, quý khách, Ngự Giả... nhiều danh xưng đến vậy, ta nên gọi cậu thế nào đây?
- HV cũ: Bạn đồng hành, thượng khách, Ngự Giả… nhiều danh xưng đến vậy, ta nên gọi ngươi thế nào đây?
- HV V4: Bạn đồng hành, quý khách, Ngự Giả... nhiều danh xưng đến vậy, ta nên gọi cậu thế nào đây?

### `lang_multi_text.db||MultiText||phone_JL_4_3`
- VI cũ: Tùy cô quyết định, tôi gọi thế nào cũng được.
- VI V4: Tùy cô quyết định, tôi sao cũng được.
- HV cũ: Tùy cô quyết định, tôi gọi thế nào cũng được.
- HV V4: Tùy cô quyết định, tôi sao cũng được.

### `lang_multi_text.db||MultiText||phone_JL_4_7`
- VI cũ: Ha ha, vừa cùng nhau vượt qua một phen sinh tử… ta nghĩ, quan hệ giữa chúng ta đã đủ để gọi thẳng tên nhau rồi.
- VI V4: Ha ha, vừa cùng nhau bước qua một phen sinh tử... ta nghĩ quan hệ giữa chúng ta đã đủ để gọi thẳng tên nhau rồi.
- HV cũ: Ha ha, vừa cùng nhau vượt qua một phen sinh tử… ta nghĩ, quan hệ giữa chúng ta đã đủ để gọi thẳng tên nhau rồi.
- HV V4: Ha ha, vừa cùng nhau bước qua một phen sinh tử... ta nghĩ quan hệ giữa chúng ta đã đủ để gọi thẳng tên nhau rồi.

### `lang_multi_text.db||MultiText||phone_JL_4_8`
- VI cũ: {PlayerName}, chuyện ở Núi Thừa Tiêu lần này, đa tạ ngươi đã ra tay tương trợ.
- VI V4: {PlayerName}, chuyện ở Núi Thừa Tiêu lần này, đa tạ cậu đã ra tay tương trợ.
- HV cũ: {PlayerName}, chuyện ở Núi Thừa Tiêu lần này, đa tạ ngươi đã ra tay tương trợ.
- HV V4: {PlayerName}, chuyện ở Núi Thừa Tiêu lần này, đa tạ cậu đã ra tay tương trợ.

### `lang_multi_text.db||MultiText||phone_JL_5_1`
- VI cũ: Có lẽ, chỉ qua những con chữ lạnh lẽo thế này, không thể truyền tải được hơi ấm của Ánh sáng mặt trời.
- VI V4: Có lẽ những dòng chữ lạnh lẽo thế này không thể truyền hết hơi ấm của ánh nắng.
- HV cũ: Có lẽ, chỉ qua những con chữ lạnh lẽo thế này, không thể truyền tải được hơi ấm của Ánh sáng mặt trời.
- HV V4: Có lẽ những dòng chữ lạnh lẽo thế này không thể truyền hết hơi ấm của ánh nắng.

### `lang_multi_text.db||MultiText||phone_JL_5_10`
- VI cũ: Đây là sứ mệnh của tôi. Có điều…
- VI V4: Đó là sứ mệnh của tôi. Nhưng...
- HV cũ: Đây là sứ mệnh của tôi. Có điều…
- HV V4: Đó là sứ mệnh của tôi. Nhưng...

### `lang_multi_text.db||MultiText||phone_JL_5_11`
- VI cũ: Tôi đang nghĩ, có lẽ có thể cải tạo đôi chút cho Terminal hệ thống gửi nhận Thư này.
- VI V4: Tôi đang nghĩ, có lẽ có thể cải tiến thiết bị đầu cuối dùng để gửi nhận tin nhắn này một chút.
- HV cũ: Tôi đang nghĩ, có lẽ có thể cải tạo đôi chút cho Terminal hệ thống gửi nhận Thư này.
- HV V4: Tôi đang nghĩ, có lẽ có thể cải tiến thiết bị đầu cuối dùng để gửi nhận tin nhắn này một chút.

### `lang_multi_text.db||MultiText||phone_JL_5_12`
- VI cũ: Thôi đừng làm phiền Hệ Thống Tethys nữa
- VI V4: Thôi, đừng làm phiền Hệ Thống Tethys nữa.
- HV cũ: Thôi đừng làm phiền Hệ Thống Tethys nữa
- HV V4: Thôi, đừng làm phiền Hệ Thống Tethys nữa.

### `lang_multi_text.db||MultiText||phone_JL_5_13`
- VI cũ: Không không không, thôi không cần đâu. Cứ như thế này, thấy chữ cũng như thấy người vậy.
- VI V4: Không, không, thôi khỏi. Cứ thế này cũng tốt, nhìn chữ mà như đang gặp nhau vậy.
- HV cũ: Không không không, thôi không cần đâu. Cứ như thế này, thấy chữ cũng như thấy người vậy.
- HV V4: Không, không, thôi khỏi. Cứ thế này cũng tốt, nhìn chữ mà như đang gặp nhau vậy.

### `lang_multi_text.db||MultiText||phone_JL_5_14`
- VI cũ: Tôi hiểu rồi, ngài thấy thích là được.
- VI V4: Tôi hiểu rồi. Chỉ cần cậu thích là được.
- HV cũ: Tôi hiểu rồi, ngài thấy thích là được.
- HV V4: Tôi hiểu rồi. Chỉ cần cậu thích là được.

### `lang_multi_text.db||MultiText||phone_JL_5_2`
- VI cũ: Hãy tiếp tục đi Tìm Kiếm ánh sao có thể gắn kết Thế giới này lại với nhau nhé.
- VI V4: Hãy tiếp tục tìm kiếm những ánh sao có thể kết nối thế giới này với nhau nhé.
- HV cũ: Hãy tiếp tục đi Tìm Kiếm ánh sao có thể gắn kết Thế giới này lại với nhau nhé.
- HV V4: Hãy tiếp tục tìm kiếm những ánh sao có thể kết nối thế giới này với nhau nhé.

### `lang_multi_text.db||MultiText||phone_JL_5_3`
- VI cũ: Tôi sẽ ở lại điểm gốc, ở lại bờ biển này, tiếp tục gìn giữ tất cả những gì ngài đã từng để lại cho Thế giới.
- VI V4: Tôi sẽ ở lại nơi khởi đầu, trên bờ biển này, tiếp tục gìn giữ tất cả những gì cậu từng để lại cho thế giới.
- HV cũ: Tôi sẽ ở lại điểm gốc, ở lại bờ biển này, tiếp tục gìn giữ tất cả những gì ngài đã từng để lại cho Thế giới.
- HV V4: Tôi sẽ ở lại nơi khởi đầu, trên bờ biển này, tiếp tục gìn giữ tất cả những gì cậu từng để lại cho thế giới.

### `lang_multi_text.db||MultiText||phone_JL_5_4`
- VI cũ: Cảm ơn nàng, Người Giữ Bờ.
- VI V4: Cảm ơn cô, Shorekeeper.
- HV cũ: Cảm ơn nàng, Người Giữ Bờ.
- HV V4: Cảm ơn cô, Shorekeeper.

### `lang_multi_text.db||MultiText||phone_JL_5_6`
- VI cũ: Vất vả cho nàng phải tiếp tục lắng nghe Triều Tịch của bờ biển này rồi.
- VI V4: Từ giờ vẫn phải nhờ cô tiếp tục lắng nghe thủy triều của bờ biển này rồi.
- HV cũ: Vất vả cho nàng phải tiếp tục lắng nghe Triều Tịch của bờ biển này rồi.
- HV V4: Từ giờ vẫn phải nhờ cô tiếp tục lắng nghe thủy triều của bờ biển này rồi.

### `lang_multi_text.db||MultiText||phone_JL_5_7`
- VI cũ: Nếu có thể kết nối với Hệ Thống Tethys, ngài dùng sẽ tiện lợi hơn đôi chút…
- VI V4: Nếu kết nối được với Hệ Thống Tethys, cậu dùng sẽ tiện hơn một chút...
- HV cũ: Nếu có thể kết nối với Hệ Thống Tethys, ngài dùng sẽ tiện lợi hơn đôi chút…
- HV V4: Nếu kết nối được với Hệ Thống Tethys, cậu dùng sẽ tiện hơn một chút...

### `lang_multi_text.db||MultiText||phone_JL_5_8`
- VI cũ: Tóm lại, con đường phía trước, xin hãy để tôi cùng bước tiếp với ngài.
- VI V4: Dù sao thì... từ nay về sau, xin hãy để tôi cùng cậu bước tiếp con đường phía trước.
- HV cũ: Tóm lại, con đường phía trước, xin hãy để tôi cùng bước tiếp với ngài.
- HV V4: Dù sao thì... từ nay về sau, xin hãy để tôi cùng cậu bước tiếp con đường phía trước.

### `lang_ui_prefabTextItem.db||PrefabTextItem||1095`
- HV cũ: Ương Ương
- HV V4: Yangyang

### `lang_ui_prefabTextItem.db||PrefabTextItem||1096`
- HV cũ: Ương Ương
- HV V4: Yangyang

### `lang_ui_prefabTextItem.db||PrefabTextItem||1330`
- HV cũ: Hiển thị động tác: Ương Ương, Đứng
- HV V4: Hiển thị động tác: Yangyang, Đứng

### `lang_ui_prefabTextItem.db||PrefabTextItem||1366`
- HV cũ: Bản ghi âm của Ương Ương
- HV V4: Bản ghi âm của Yangyang

### `lang_ui_prefabTextItem.db||PrefabTextItem||1542`
- HV cũ: Ương Ương đã trang bị
- HV V4: Yangyang đã trang bị

### `lang_ui_prefabTextItem.db||PrefabTextItem||1623`
- HV cũ: Ương Ương đã trang bị
- HV V4: Yangyang đã trang bị

### `lang_ui_prefabTextItem.db||PrefabTextItem||1656`
- HV cũ: Ương Ương đã trang bị
- HV V4: Yangyang đã trang bị

### `lang_ui_prefabTextItem.db||PrefabTextItem||1784`
- HV cũ: Ương Ương đã trang bị
- HV V4: Yangyang đã trang bị

### `lang_ui_prefabTextItem.db||PrefabTextItem||1785`
- HV cũ: Ương Ương đã trang bị
- HV V4: Yangyang đã trang bị

### `lang_ui_prefabTextItem.db||PrefabTextItem||2780`
- HV cũ: Ương Ương
- HV V4: Yangyang

### `lang_ui_prefabTextItem.db||PrefabTextItem||2847`
- HV cũ: Nhân vật đề xuất Ương Ương
- HV V4: Nhân vật đề xuất Yangyang

### `lang_ui_prefabTextItem.db||PrefabTextItem||3078`
- HV cũ: Ương Ương
- HV V4: Yangyang

### `lang_ui_prefabTextItem.db||PrefabTextItem||453`
- HV cũ: Ương Ương
- HV V4: Yangyang

### `lang_ui_prefabTextItem.db||PrefabTextItem||821`
- HV cũ: Ương Ương
- HV V4: Yangyang

### `lang_item.db||ItemInfo||1056`
- HV cũ: Hoa Vân Lộ đại diện cho một người phụ nữ thuộc gia tộc Đan Cẩn, tên là "Vân Lộ".
- HV V4: Hoa Vân Lộ đại diện cho một người phụ nữ thuộc gia tộc Danjin, tên là "Vân Lộ".

### `lang_item.db||ItemInfo||1058`
- HV cũ: Hoa Vân Lộ đại diện cho một người phụ nữ thuộc gia tộc Đan Cẩn, tên là "Vân Lộ".
- HV V4: Hoa Vân Lộ đại diện cho một người phụ nữ thuộc gia tộc Danjin, tên là "Vân Lộ".

### `lang_item.db||ItemInfo||1071`
- HV cũ: Nhật Ký Của Cha Xí Hà
- HV V4: Nhật Ký Của Cha Chixia

### `lang_item.db||ItemInfo||1084`
- HV cũ: Microchip do Long Chủ Kim Tịch ban tặng.
- HV V4: Microchip do Long Chủ Jinhsi ban tặng.

### `lang_item.db||ItemInfo||1085`
- HV cũ: Microchip do Long Chủ Kim Tịch ban tặng, bên trong lưu trữ kỷ lục nghiên cứu của Phòng thí nghiệm Tắc Đình về Thần Thú Tuế Quang.
- HV V4: Microchip do Long Chủ Jinhsi ban tặng, bên trong lưu trữ kỷ lục nghiên cứu của Phòng thí nghiệm Tắc Đình về Thần Thú Tuế Quang.

### `lang_item.db||ItemInfo||1086`
- HV cũ: Microchip do Long Chủ Kim Tịch ban tặng.
- HV V4: Microchip do Long Chủ Jinhsi ban tặng.

### `lang_item.db||ItemInfo||1333`
- HV cũ: Tiểu Long Bao là Món Tráng Miệng nổi tiếng xuất hiện ở Thiên Thành để kỷ niệm chiến tích của Long Chủ Kim Tịch. Hình dáng tròn trịa, có sừng Long, bên trong là nhân lưu sa, có nhiều hương vị để lựa chọn.
- HV V4: Tiểu Long Bao là Món Tráng Miệng nổi tiếng xuất hiện ở Thiên Thành để kỷ niệm chiến tích của Long Chủ Jinhsi. Hình dáng tròn trịa, có sừng Long, bên trong là nhân lưu sa, có nhiều hương vị để lựa chọn.

### `lang_item.db||ItemInfo||1713`
- HV cũ: test/Vật phẩm Đạo cụ Phó bản Kỵ Viêm 1
- HV V4: test/Vật phẩm Đạo cụ Phó bản Jiyan 1

### `lang_item.db||ItemInfo||48`
- HV cũ: Dải Âm Vang của Đào Kỳ
- HV V4: Dải Âm Vang của Đào Kì

### `lang_item.db||ItemInfo||72`
- HV cũ: Dải Âm Vang của Mortefi
- HV V4: Dải Âm Vang của Mạc Đặc Phỉ

### `lang_multi_text.db||MultiText||Dango_Broadcast_Feibi_GroupStape_1`
- HV cũ: Mang đến cho mọi người Lời Chúc Phúc của tiểu thư Phi Bỉ, cô hy vọng mọi người sẽ tận hưởng trận đấu và đều đạt được thành tích tốt!
- HV V4: Mang đến cho mọi người Lời Chúc Phúc của tiểu thư Phoebe, cô hy vọng mọi người sẽ tận hưởng trận đấu và đều đạt được thành tích tốt!

### `lang_multi_text.db||MultiText||Dango_Broadcast_Shouanren_FinalStage_1`
- HV cũ: Cô Thủ Ngạn Nhân cho biết vì Khối Tinh Bột chủ yếu làm từ tinh bột, ra mồ hôi quá nhiều khi chạy có thể khiến cơ thể bị phân hủy. Bí quyết để chiến thắng là duy trì nhiệt độ cơ thể và hình dáng ổn định.
- HV V4: Cô Shorekeeper cho biết vì Khối Tinh Bột chủ yếu làm từ tinh bột, ra mồ hôi quá nhiều khi chạy có thể khiến cơ thể bị phân hủy. Bí quyết để chiến thắng là duy trì nhiệt độ cơ thể và hình dáng ổn định.

### `lang_multi_text.db||MultiText||Dango_Broadcast_Shouanren_FinalStage_2`
- HV cũ: Dựa trên phân tích dữ liệu cuộc đua, cô Thủ Ngạn Nhân đề xuất những khán giả thích mạo hiểm nên đặt cược vào những tuyển thủ có sức bật mạnh mẽ. Còn những khán giả cẩn trọng có thể đầu tư vào những tuyển thủ có sức bền ổn định như cô ấy.
- HV V4: Dựa trên phân tích dữ liệu cuộc đua, cô Shorekeeper đề xuất những khán giả thích mạo hiểm nên đặt cược vào những tuyển thủ có sức bật mạnh mẽ. Còn những khán giả cẩn trọng có thể đầu tư vào những tuyển thủ có sức bền ổn định như cô ấy.

### `lang_multi_text.db||MultiText||Dango_Broadcast_Shouanren_GroupStage_1`
- HV cũ: Cô Thủ Ngạn Nhân chia sẻ rằng mức độ thích nghi với cơ thể Khối Tinh Bột của mỗi người là khác nhau. Không phải cô ấy có thể lực tốt hơn những tuyển thủ bị loại, mà chỉ là cô ấy giỏi làm một Khối Tinh Bột hơn họ.
- HV V4: Cô Shorekeeper chia sẻ rằng mức độ thích nghi với cơ thể Khối Tinh Bột của mỗi người là khác nhau. Không phải cô ấy có thể lực tốt hơn những tuyển thủ bị loại, mà chỉ là cô ấy giỏi làm một Khối Tinh Bột hơn họ.

### `lang_multi_text.db||MultiText||Dango_Broadcast_Shouanren_GroupStage_2`
- HV cũ: Theo chia sẻ của KU-Lolo, lần cuối cùng cô Thủ Ngạn Nhân chuẩn bị tích cực như vậy là để chào đón Rover đến Bờ Biển Đen. Hãy cùng chờ đón màn thể hiện của cô ấy!
- HV V4: Theo chia sẻ của KU-Lolo, lần cuối cùng cô Shorekeeper chuẩn bị tích cực như vậy là để chào đón Rover đến Bờ Biển Đen. Hãy cùng chờ đón màn thể hiện của cô ấy!

### `lang_multi_text.db||MultiText||Dango_Broadcast_Shouanren_Win`
- HV cũ: Cô Thủ Ngạn Nhân chia sẻ rằng so với một kết quả đã biết trước, cô ấy thích cảm giác chạy cùng mọi người trên một đường đua đầy rẫy sự không chắc chắn hơn.
- HV V4: Cô Shorekeeper chia sẻ rằng so với một kết quả đã biết trước, cô ấy thích cảm giác chạy cùng mọi người trên một đường đua đầy rẫy sự không chắc chắn hơn.

### `lang_multi_text.db||MultiText||Dango_Broadcast_Stage4Win_Shouanren`
- HV cũ: Cô Thủ Ngạn Nhân đã chiến thắng trong trận tri ân, cô ấy cho biết sau khi về sẽ lên lại kế hoạch cho lịch trình, để nhân viên của Bờ Biển Đen bao gồm cả mình có thể tăng cường rèn luyện sau giờ làm.
- HV V4: Cô Shorekeeper đã chiến thắng trong trận tri ân, cô ấy cho biết sau khi về sẽ lên lại kế hoạch cho lịch trình, để nhân viên của Bờ Biển Đen bao gồm cả mình có thể tăng cường rèn luyện sau giờ làm.

### `lang_multi_text.db||MultiText||Dango_Broadcast_Stage4_Shouanren`
- HV cũ: Cô Thủ Ngạn Nhân cho biết nếu có thể tùy ý sử dụng Cổng Không Gian trong đường đua, thì thành tích của cô ấy nhất định sẽ tốt hơn bây giờ rất nhiều.
- HV V4: Cô Shorekeeper cho biết nếu có thể tùy ý sử dụng Cổng Không Gian trong đường đua, thì thành tích của cô ấy nhất định sẽ tốt hơn bây giờ rất nhiều.

### `lang_multi_text.db||MultiText||Dango_BulletChat_Shouanren_2`
- HV cũ: Thủ Ngạn Nhân, biến thành con bướm bay cho nhanh!
- HV V4: Shorekeeper, biến thành con bướm bay cho nhanh!

### `lang_multi_text.db||MultiText||Dango_Name_Shouanren`
- HV cũ: Khối Thủ Ngạn Nhân
- HV V4: Khối Shorekeeper

### `lang_multi_text.db||MultiText||ItemInfo_10001104_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Lăng Dương.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Lingyang.

### `lang_multi_text.db||MultiText||ItemInfo_10001104_Name`
- HV cũ: Dải Âm Vang Của Lăng Dương
- HV V4: Dải Âm Vang Của Lingyang

### `lang_multi_text.db||MultiText||ItemInfo_10001104_ObtainedShowDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Lăng Dương.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Lingyang.

### `lang_multi_text.db||MultiText||ItemInfo_10001106_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Dụ Hồ.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Youhu.

### `lang_multi_text.db||MultiText||ItemInfo_10001106_Name`
- HV cũ: Dải Âm Vang Của Dụ Hồ
- HV V4: Dải Âm Vang Của Youhu

### `lang_multi_text.db||MultiText||ItemInfo_10001107_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Kha Lai Tháp.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Carlotta.

### `lang_multi_text.db||MultiText||ItemInfo_10001107_Name`
- HV cũ: Dải Âm Vang Của Kha Lai Tháp
- HV V4: Dải Âm Vang Của Carlotta

### `lang_multi_text.db||MultiText||ItemInfo_10001109_Name`
- VI cũ: Tần Đoạn Hồi Âm của Lucilla
- VI V4: Dải Âm Vang của Lucilla
- HV cũ: Tần Đoạn Hồi Âm của Lucilla
- HV V4: Dải Âm Vang của Lucilla

### `lang_multi_text.db||MultiText||ItemInfo_10001203_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của An Khả.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Encore.

### `lang_multi_text.db||MultiText||ItemInfo_10001203_Name`
- HV cũ: Dải Âm Vang Của An Khả
- HV V4: Dải Âm Vang Của Encore

### `lang_multi_text.db||MultiText||ItemInfo_10001203_ObtainedShowDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của An Khả.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Encore.

### `lang_multi_text.db||MultiText||ItemInfo_10001205_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Lạc Khả Khả.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Roccia.

### `lang_multi_text.db||MultiText||ItemInfo_10001205_Name`
- HV cũ: Dải Âm Vang Của Lạc Khả Khả
- HV V4: Dải Âm Vang Của Roccia

### `lang_multi_text.db||MultiText||ItemInfo_10001206_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Bố Lan Đặc.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Brant.

### `lang_multi_text.db||MultiText||ItemInfo_10001206_Name`
- HV cũ: Dải Âm Vang Của Bố Lan Đặc
- HV V4: Dải Âm Vang Của Brant

### `lang_multi_text.db||MultiText||ItemInfo_10001207_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Lộ Mạt.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Lupa.

### `lang_multi_text.db||MultiText||ItemInfo_10001207_Name`
- HV cũ: Dải Âm Vang Của Lộ Mạt
- HV V4: Dải Âm Vang Của Lupa

### `lang_multi_text.db||MultiText||ItemInfo_10001306_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Áo Cổ Tư Tháp.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Augusta.

### `lang_multi_text.db||MultiText||ItemInfo_10001306_Name`
- HV cũ: Dải Âm Vang Của Áo Cổ Tư Tháp
- HV V4: Dải Âm Vang Của Augusta

### `lang_multi_text.db||MultiText||ItemInfo_10001307_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Bặc Linh.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Buling.

### `lang_multi_text.db||MultiText||ItemInfo_10001307_Name`
- VI cũ: Băng Tần Tiếng Vang Của Buling
- VI V4: Dải Âm Vang Của Buling
- HV cũ: Băng Tần Tiếng Vang Của Bặc Linh
- HV V4: Dải Âm Vang Của Buling

### `lang_multi_text.db||MultiText||ItemInfo_10001308_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Lệ Bối Tạp.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Rebecca.

### `lang_multi_text.db||MultiText||ItemInfo_10001308_Name`
- VI cũ: Tần Đoạn Hồi Âm của Rebecca
- VI V4: Dải Âm Vang của Rebecca
- HV cũ: Tần Đoạn Hồi Âm của Lệ Bối Tạp
- HV V4: Dải Âm Vang của Rebecca

### `lang_multi_text.db||MultiText||ItemInfo_10001405_Name`
- VI cũ: Băng Tần Tiếng Vang Của Jianxin
- VI V4: Dải Âm Vang Của Jianxin
- HV cũ: Băng Tần Tiếng Vang Của Giám Tâm
- HV V4: Dải Âm Vang Của Giám Tâm

### `lang_multi_text.db||MultiText||ItemInfo_10001406_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Lữ Khách - Khí Động.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Rover - Khí Động.

### `lang_multi_text.db||MultiText||ItemInfo_10001406_Name`
- VI cũ: Băng Tần Tiếng Vang Của Rover - Khí Động
- VI V4: Dải Âm Vang Của Rover - Khí Động
- HV cũ: Băng Tần Tiếng Vang Của Lữ Khách - Khí Động
- HV V4: Dải Âm Vang Của Rover - Khí Động

### `lang_multi_text.db||MultiText||ItemInfo_10001407_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Hạ Không.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Ciaccona.

### `lang_multi_text.db||MultiText||ItemInfo_10001407_Name`
- VI cũ: Băng Tần Tiếng Vang Của Ciaccona
- VI V4: Dải Âm Vang Của Ciaccona
- HV cũ: Băng Tần Tiếng Vang Của Hạ Không
- HV V4: Dải Âm Vang Của Ciaccona

### `lang_multi_text.db||MultiText||ItemInfo_10001409_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Tạp Đề Hi Á.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Cartethyia.

### `lang_multi_text.db||MultiText||ItemInfo_10001409_Name`
- VI cũ: Băng Tần Tiếng Vang Của Cartethyia
- VI V4: Dải Âm Vang Của Cartethyia
- HV cũ: Băng Tần Tiếng Vang Của Tạp Đề Hi Á
- HV V4: Dải Âm Vang Của Cartethyia

### `lang_multi_text.db||MultiText||ItemInfo_10001410_Name`
- VI cũ: Băng Tần Tiếng Vang Của Iuno
- VI V4: Dải Âm Vang Của Iuno
- HV cũ: Băng Tần Tiếng Vang Của Iuno
- HV V4: Dải Âm Vang Của Iuno

### `lang_multi_text.db||MultiText||ItemInfo_10001411_Name`
- VI cũ: Băng Tần Tiếng Vang Của Qiuyuan
- VI V4: Dải Âm Vang Của Qiuyuan
- HV cũ: Băng Tần Tiếng Vang Của Qiuyuan
- HV V4: Dải Âm Vang Của Qiuyuan

### `lang_multi_text.db||MultiText||ItemInfo_10001412_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Tây Cách Lị Tạp.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Sigrika.

### `lang_multi_text.db||MultiText||ItemInfo_10001412_Name`
- VI cũ: Băng Tần Tiếng Vang Của Sigrika
- VI V4: Dải Âm Vang Của Sigrika
- HV cũ: Băng Tần Tiếng Vang Của Tây Cách Lị Tạp
- HV V4: Dải Âm Vang Của Sigrika

### `lang_multi_text.db||MultiText||ItemInfo_10001500_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Lữ Khách - Quang Phổ.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Rover - Quang Phổ.

### `lang_multi_text.db||MultiText||ItemInfo_10001500_Name`
- VI cũ: Băng Tần Tiếng Vang Của Rover - Quang Phổ
- VI V4: Dải Âm Vang Của Rover - Quang Phổ
- HV cũ: Băng Tần Tiếng Vang Của Lữ Khách - Quang Phổ
- HV V4: Dải Âm Vang Của Rover - Quang Phổ

### `lang_multi_text.db||MultiText||ItemInfo_10001500_ObtainedShowDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Lữ Khách - Quang Phổ.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Rover - Quang Phổ.

### `lang_multi_text.db||MultiText||ItemInfo_10001503_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Duy Lý Nại.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Verina.

### `lang_multi_text.db||MultiText||ItemInfo_10001503_Name`
- VI cũ: Băng Tần Tiếng Vang Của Verina
- VI V4: Dải Âm Vang Của Verina
- HV cũ: Băng Tần Tiếng Vang Của Duy Lý Nại
- HV V4: Dải Âm Vang Của Verina

### `lang_multi_text.db||MultiText||ItemInfo_10001503_ObtainedShowDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Duy Lý Nại.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Verina.

### `lang_multi_text.db||MultiText||ItemInfo_10001504_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Đăng Đăng.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Lumi.

### `lang_multi_text.db||MultiText||ItemInfo_10001504_Name`
- VI cũ: Băng Tần Tiếng Vang Của Lumi
- VI V4: Dải Âm Vang Của Lumi
- HV cũ: Băng Tần Tiếng Vang Của Đăng Đăng
- HV V4: Dải Âm Vang Của Lumi

### `lang_multi_text.db||MultiText||ItemInfo_10001505_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Thủ Ngạn Nhân.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Shorekeeper.

### `lang_multi_text.db||MultiText||ItemInfo_10001505_Name`
- VI cũ: Băng Tần Tiếng Vang Của Shorekeeper
- VI V4: Dải Âm Vang Của Shorekeeper
- HV cũ: Băng Tần Tiếng Vang Của Thủ Ngạn Nhân
- HV V4: Dải Âm Vang Của Shorekeeper

### `lang_multi_text.db||MultiText||ItemInfo_10001506_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Phi Bỉ.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Phoebe.

### `lang_multi_text.db||MultiText||ItemInfo_10001506_Name`
- VI cũ: Băng Tần Tiếng Vang Của Phoebe
- VI V4: Dải Âm Vang Của Phoebe
- HV cũ: Băng Tần Tiếng Vang Của Phi Bỉ
- HV V4: Dải Âm Vang Của Phoebe

### `lang_multi_text.db||MultiText||ItemInfo_10001507_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Tán Ny.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Zani.

### `lang_multi_text.db||MultiText||ItemInfo_10001507_Name`
- VI cũ: Băng Tần Tiếng Vang Của Zani
- VI V4: Dải Âm Vang Của Zani
- HV cũ: Băng Tần Tiếng Vang Của Tán Ny
- HV V4: Dải Âm Vang Của Zani

### `lang_multi_text.db||MultiText||ItemInfo_10001508_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Thiên Tiếu.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Chisa.

### `lang_multi_text.db||MultiText||ItemInfo_10001508_Name`
- VI cũ: Băng Tần Tiếng Vang Của Chisa
- VI V4: Dải Âm Vang Của Chisa
- HV cũ: Băng Tần Tiếng Vang Của Thiên Tiếu
- HV V4: Dải Âm Vang Của Chisa

### `lang_multi_text.db||MultiText||ItemInfo_10001509_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Lâm Nại.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Lynae.

### `lang_multi_text.db||MultiText||ItemInfo_10001509_Name`
- VI cũ: Băng Tần Tiếng Vang Của Lynae
- VI V4: Dải Âm Vang Của Lynae
- HV cũ: Băng Tần Tiếng Vang Của Lâm Nại
- HV V4: Dải Âm Vang Của Lynae

### `lang_multi_text.db||MultiText||ItemInfo_10001510_Name`
- VI cũ: Băng Tần Tiếng Vang Của Luuk Herssen
- VI V4: Dải Âm Vang Của Luuk Herssen
- HV cũ: Băng Tần Tiếng Vang Của Luuk Herssen
- HV V4: Dải Âm Vang Của Luuk Herssen

### `lang_multi_text.db||MultiText||ItemInfo_10001511_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Lộ Tây.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Lucy.

### `lang_multi_text.db||MultiText||ItemInfo_10001511_Name`
- VI cũ: Tần Đoạn Hồi Âm của Lucy
- VI V4: Dải Âm Vang của Lucy
- HV cũ: Tần Đoạn Hồi Âm của Lộ Tây
- HV V4: Dải Âm Vang của Lucy

### `lang_multi_text.db||MultiText||ItemInfo_10001602_Name`
- VI cũ: Băng Tần Tiếng Vang Của Danjin
- VI V4: Dải Âm Vang Của Danjin
- HV cũ: Băng Tần Tiếng Vang Của Đan Cẩn
- HV V4: Dải Âm Vang Của Đan Cẩn

### `lang_multi_text.db||MultiText||ItemInfo_10001603_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Xuân.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Camellya.

### `lang_multi_text.db||MultiText||ItemInfo_10001603_ObtainedShowDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Xuân.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Camellya.

### `lang_multi_text.db||MultiText||ItemInfo_10001604_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Lữ Khách - Hủy Diệt.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Rover - Hủy Diệt.

### `lang_multi_text.db||MultiText||ItemInfo_10001604_Name`
- VI cũ: Băng Tần Tiếng Vang Của Rover - Hủy Diệt
- VI V4: Dải Âm Vang Của Rover - Hủy Diệt
- HV cũ: Băng Tần Tiếng Vang Của Lữ Khách - Hủy Diệt
- HV V4: Dải Âm Vang Của Rover - Hủy Diệt

### `lang_multi_text.db||MultiText||ItemInfo_10001604_ObtainedShowDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Lữ Khách - Hủy Diệt.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Rover - Hủy Diệt.

### `lang_multi_text.db||MultiText||ItemInfo_10001605_Name`
- VI cũ: Băng Tần Tiếng Vang Của Jinhsi
- VI V4: Dải Âm Vang Của Jinhsi
- HV cũ: Băng Tần Tiếng Vang Của Kim Tịch
- HV V4: Dải Âm Vang Của Kim Tịch

### `lang_multi_text.db||MultiText||ItemInfo_10001606_Name`
- VI cũ: Băng Tần Tiếng Vang Của Changli
- VI V4: Dải Âm Vang Của Changli
- HV cũ: Băng Tần Tiếng Vang Của Trường Ly
- HV V4: Dải Âm Vang Của Trường Ly

### `lang_multi_text.db||MultiText||ItemInfo_10001607_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Khảm Đặc Lôi Lạp.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Cantarella.

### `lang_multi_text.db||MultiText||ItemInfo_10001607_Name`
- VI cũ: Băng Tần Tiếng Vang Của Cantarella
- VI V4: Dải Âm Vang Của Cantarella
- HV cũ: Băng Tần Tiếng Vang Của Khảm Đặc Lôi Lạp
- HV V4: Dải Âm Vang Của Cantarella

### `lang_multi_text.db||MultiText||ItemInfo_10001608_AttributesDescription`
- HV cũ: Dùng để kích hoạt Chuỗi Cộng Hưởng của Phất Lạc Lạc.
- HV V4: Dùng để kích hoạt Chuỗi Cộng Hưởng của Phrolova.

### `lang_multi_text.db||MultiText||ItemInfo_10001608_Name`
- VI cũ: Băng Tần Tiếng Vang Của Phrolova
- VI V4: Dải Âm Vang Của Phrolova
- HV cũ: Băng Tần Tiếng Vang Của Phất Lạc Lạc
- HV V4: Dải Âm Vang Của Phrolova

### `lang_multi_text.db||MultiText||ItemInfo_100_BgDescription`
- HV cũ: Biểu tượng cho sự tin tưởng lẫn nhau lâu dài giữa Lữ Khách và các thế lực, việc hình thành mối quan hệ hữu nghị ổn định với các tổ chức có lẽ sẽ nhận được sự hỗ trợ mạnh mẽ hơn.
- HV V4: Biểu tượng cho sự tin tưởng lẫn nhau lâu dài giữa Rover và các thế lực, việc hình thành mối quan hệ hữu nghị ổn định với các tổ chức có lẽ sẽ nhận được sự hỗ trợ mạnh mẽ hơn.

### `lang_multi_text.db||MultiText||ItemInfo_101_BgDescription`
- HV cũ: Biểu tượng cho sự tin tưởng lẫn nhau lâu dài giữa Lữ Khách và các thế lực, việc hình thành mối quan hệ hữu nghị ổn định với các tổ chức có lẽ sẽ nhận được sự hỗ trợ mạnh mẽ hơn.
- HV V4: Biểu tượng cho sự tin tưởng lẫn nhau lâu dài giữa Rover và các thế lực, việc hình thành mối quan hệ hữu nghị ổn định với các tổ chức có lẽ sẽ nhận được sự hỗ trợ mạnh mẽ hơn.

### `lang_multi_text.db||MultiText||ItemInfo_102_BgDescription`
- HV cũ: Biểu tượng cho sự tin tưởng lẫn nhau lâu dài giữa Lữ Khách và các thế lực, việc hình thành mối quan hệ hữu nghị ổn định với các tổ chức có lẽ sẽ nhận được sự hỗ trợ mạnh mẽ hơn.
- HV V4: Biểu tượng cho sự tin tưởng lẫn nhau lâu dài giữa Rover và các thế lực, việc hình thành mối quan hệ hữu nghị ổn định với các tổ chức có lẽ sẽ nhận được sự hỗ trợ mạnh mẽ hơn.

### `lang_multi_text.db||MultiText||ItemInfo_103_BgDescription`
- HV cũ: Biểu tượng cho sự tin tưởng lẫn nhau lâu dài giữa Lữ Khách và các thế lực, việc hình thành mối quan hệ hữu nghị ổn định với các tổ chức có lẽ sẽ nhận được sự hỗ trợ mạnh mẽ hơn.
- HV V4: Biểu tượng cho sự tin tưởng lẫn nhau lâu dài giữa Rover và các thế lực, việc hình thành mối quan hệ hữu nghị ổn định với các tổ chức có lẽ sẽ nhận được sự hỗ trợ mạnh mẽ hơn.

### `lang_multi_text.db||MultiText||ItemInfo_10811_AttributesDescription`
- HV cũ: Bong bóng kỳ bí lơ lửng, bên trong có thể giấu loài cá nào đó. Sau khi mua thành công, hệ thống sẽ tự động tạo một "Bong Bóng Kỳ Bí" gần bến tàu hiện tại. Sau mỗi khoảng thời gian, "Bong Bóng Kỳ Bí" sẽ tự động giúp Lữ Khách đánh bắt các loại cua và nhím biển.
- HV V4: Bong bóng kỳ bí lơ lửng, bên trong có thể giấu loài cá nào đó. Sau khi mua thành công, hệ thống sẽ tự động tạo một "Bong Bóng Kỳ Bí" gần bến tàu hiện tại. Sau mỗi khoảng thời gian, "Bong Bóng Kỳ Bí" sẽ tự động giúp Rover đánh bắt các loại cua và nhím biển.

### `lang_multi_text.db||MultiText||ItemInfo_10811_ObtainedShowDescription`
- HV cũ: Bong bóng kỳ bí lơ lửng, bên trong có thể giấu loài cá nào đó. Sau khi mua thành công, hệ thống sẽ tự động tạo một "Bong Bóng Kỳ Bí" gần bến tàu hiện tại. Sau mỗi khoảng thời gian, "Bong Bóng Kỳ Bí" sẽ tự động giúp Lữ Khách đánh bắt các loại cua và nhím biển.
- HV V4: Bong bóng kỳ bí lơ lửng, bên trong có thể giấu loài cá nào đó. Sau khi mua thành công, hệ thống sẽ tự động tạo một "Bong Bóng Kỳ Bí" gần bến tàu hiện tại. Sau mỗi khoảng thời gian, "Bong Bóng Kỳ Bí" sẽ tự động giúp Rover đánh bắt các loại cua và nhím biển.

### `lang_multi_text.db||MultiText||ItemInfo_10812_AttributesDescription`
- HV cũ: Bong bóng kỳ bí lơ lửng, bên trong có thể giấu loài cá nào đó. Sau khi mua thành công, hệ thống sẽ tự động tạo một "Bong Bóng Kỳ Bí" gần bến tàu hiện tại. Sau mỗi khoảng thời gian, "Bong Bóng Kỳ Bí" sẽ tự động giúp Lữ Khách đánh bắt các loại cua và nhím biển.
- HV V4: Bong bóng kỳ bí lơ lửng, bên trong có thể giấu loài cá nào đó. Sau khi mua thành công, hệ thống sẽ tự động tạo một "Bong Bóng Kỳ Bí" gần bến tàu hiện tại. Sau mỗi khoảng thời gian, "Bong Bóng Kỳ Bí" sẽ tự động giúp Rover đánh bắt các loại cua và nhím biển.

### `lang_multi_text.db||MultiText||ItemInfo_10812_ObtainedShowDescription`
- HV cũ: Bong bóng kỳ bí lơ lửng, bên trong có thể giấu loài cá nào đó. Sau khi mua thành công, hệ thống sẽ tự động tạo một "Bong Bóng Kỳ Bí" gần bến tàu hiện tại. Sau mỗi khoảng thời gian, "Bong Bóng Kỳ Bí" sẽ tự động giúp Lữ Khách đánh bắt các loại cua và nhím biển.
- HV V4: Bong bóng kỳ bí lơ lửng, bên trong có thể giấu loài cá nào đó. Sau khi mua thành công, hệ thống sẽ tự động tạo một "Bong Bóng Kỳ Bí" gần bến tàu hiện tại. Sau mỗi khoảng thời gian, "Bong Bóng Kỳ Bí" sẽ tự động giúp Rover đánh bắt các loại cua và nhím biển.

### `lang_multi_text.db||MultiText||ItemInfo_10813_AttributesDescription`
- HV cũ: Bong bóng kỳ bí lơ lửng, bên trong có thể giấu loài cá nào đó. Sau khi mua thành công, hệ thống sẽ tự động tạo một "Bong Bóng Kỳ Bí" gần bến tàu hiện tại. Sau mỗi khoảng thời gian, "Bong Bóng Kỳ Bí" sẽ tự động giúp Lữ Khách đánh bắt các loại cua và nhím biển.
- HV V4: Bong bóng kỳ bí lơ lửng, bên trong có thể giấu loài cá nào đó. Sau khi mua thành công, hệ thống sẽ tự động tạo một "Bong Bóng Kỳ Bí" gần bến tàu hiện tại. Sau mỗi khoảng thời gian, "Bong Bóng Kỳ Bí" sẽ tự động giúp Rover đánh bắt các loại cua và nhím biển.

### `lang_multi_text.db||MultiText||ItemInfo_10813_ObtainedShowDescription`
- HV cũ: Bong bóng kỳ bí lơ lửng, bên trong có thể giấu loài cá nào đó. Sau khi mua thành công, hệ thống sẽ tự động tạo một "Bong Bóng Kỳ Bí" gần bến tàu hiện tại. Sau mỗi khoảng thời gian, "Bong Bóng Kỳ Bí" sẽ tự động giúp Lữ Khách đánh bắt các loại cua và nhím biển.
- HV V4: Bong bóng kỳ bí lơ lửng, bên trong có thể giấu loài cá nào đó. Sau khi mua thành công, hệ thống sẽ tự động tạo một "Bong Bóng Kỳ Bí" gần bến tàu hiện tại. Sau mỗi khoảng thời gian, "Bong Bóng Kỳ Bí" sẽ tự động giúp Rover đánh bắt các loại cua và nhím biển.

### `lang_multi_text.db||MultiText||ItemInfo_10814_AttributesDescription`
- HV cũ: Bong bóng kỳ bí lơ lửng, bên trong có thể giấu loài cá nào đó. Sau khi mua thành công, hệ thống sẽ tự động tạo một "Bong Bóng Kỳ Bí" gần bến tàu hiện tại. Sau mỗi khoảng thời gian, "Bong Bóng Kỳ Bí" sẽ tự động giúp Lữ Khách đánh bắt các loại cua và nhím biển.
- HV V4: Bong bóng kỳ bí lơ lửng, bên trong có thể giấu loài cá nào đó. Sau khi mua thành công, hệ thống sẽ tự động tạo một "Bong Bóng Kỳ Bí" gần bến tàu hiện tại. Sau mỗi khoảng thời gian, "Bong Bóng Kỳ Bí" sẽ tự động giúp Rover đánh bắt các loại cua và nhím biển.

### `lang_multi_text.db||MultiText||ItemInfo_10814_ObtainedShowDescription`
- HV cũ: Bong bóng kỳ bí lơ lửng, bên trong có thể giấu loài cá nào đó. Sau khi mua thành công, hệ thống sẽ tự động tạo một "Bong Bóng Kỳ Bí" gần bến tàu hiện tại. Sau mỗi khoảng thời gian, "Bong Bóng Kỳ Bí" sẽ tự động giúp Lữ Khách đánh bắt các loại cua và nhím biển.
- HV V4: Bong bóng kỳ bí lơ lửng, bên trong có thể giấu loài cá nào đó. Sau khi mua thành công, hệ thống sẽ tự động tạo một "Bong Bóng Kỳ Bí" gần bến tàu hiện tại. Sau mỗi khoảng thời gian, "Bong Bóng Kỳ Bí" sẽ tự động giúp Rover đánh bắt các loại cua và nhím biển.

### `lang_multi_text.db||MultiText||ItemInfo_39_AttributesDescription`
- HV cũ: Cuốn cẩm nang vô tình nhận được, dùng để nâng cao kỹ năng đánh bắt của Lữ Khách.
- HV V4: Cuốn cẩm nang vô tình nhận được, dùng để nâng cao kỹ năng đánh bắt của Rover.

### `lang_multi_text.db||MultiText||ItemInfo_39_ObtainedShowDescription`
- HV cũ: Cuốn cẩm nang vô tình nhận được, dùng để nâng cao kỹ năng đánh bắt của Lữ Khách.
- HV V4: Cuốn cẩm nang vô tình nhận được, dùng để nâng cao kỹ năng đánh bắt của Rover.

### `lang_multi_text.db||MultiText||ItemInfo_40_AttributesDescription`
- HV cũ: Những đoạn kinh văn rời rạc vô tình nhận được, dùng để nâng cao kỹ năng đánh bắt cá của Phi Bỉ.
- HV V4: Những đoạn kinh văn rời rạc vô tình nhận được, dùng để nâng cao kỹ năng đánh bắt cá của Phoebe.

### `lang_multi_text.db||MultiText||ItemInfo_40_ObtainedShowDescription`
- HV cũ: Những đoạn kinh văn rời rạc vô tình nhận được, dùng để nâng cao kỹ năng đánh bắt cá của Phi Bỉ.
- HV V4: Những đoạn kinh văn rời rạc vô tình nhận được, dùng để nâng cao kỹ năng đánh bắt cá của Phoebe.

### `lang_multi_text.db||MultiText||ItemInfo_41300005_AttributesDescription`
- HV cũ: Dùng để đột phá Lữ Khách.
- HV V4: Dùng để đột phá Rover.

### `lang_multi_text.db||MultiText||ItemInfo_41300005_BgDescription`
- HV cũ: Cuộn kim loại ghi chép những ký hiệu bí ẩn, dường như có thể tạo ra một mối liên hệ nào đó với Lữ Khách.
- HV V4: Cuộn kim loại ghi chép những ký hiệu bí ẩn, dường như có thể tạo ra một mối liên hệ nào đó với Rover.

### `lang_multi_text.db||MultiText||ItemInfo_41300005_ObtainedShowDescription`
- HV cũ: Dùng để đột phá Lữ Khách.
- HV V4: Dùng để đột phá Rover.

### `lang_multi_text.db||MultiText||ItemInfo_41400204_BgDescription`
- HV cũ: Vật phẩm ban tặng cho Thánh nữ trong lễ rửa tội của Tu viện.\nFleurdelys, một "bức tượng" được chạm khắc tỉ mỉ đã được đẩy ra trước công chúng. Khi lớp vỏ thần thánh bong tróc, sinh mệnh thuộc về cô ấy mới thực sự thức tỉnh.\nFleurdelys hay Tạp Đề Hi Á... Rốt cuộc cô ấy muốn sống bằng cái tên nào...
- HV V4: Vật phẩm ban tặng cho Thánh nữ trong lễ rửa tội của Tu viện.\nFleurdelys, một "bức tượng" được chạm khắc tỉ mỉ đã được đẩy ra trước công chúng. Khi lớp vỏ thần thánh bong tróc, sinh mệnh thuộc về cô ấy mới thực sự thức tỉnh.\nFleurdelys hay Cartethyia... Rốt cuộc cô ấy muốn sống bằng cái tên nào...

### `lang_multi_text.db||MultiText||ItemInfo_41400314_AttributesDescription`
- HV cũ: Vật rơi ra từ Nightmare: Adam Smasher, dùng để đột phá nhân vật Lộ Tây, Lệ Bối Tạp.
- HV V4: Vật rơi ra từ Nightmare: Adam Smasher, dùng để đột phá nhân vật Lucy, Rebecca.

### `lang_multi_text.db||MultiText||ItemInfo_41400314_ObtainedShowDescription`
- HV cũ: Vật phẩm Rơi ra từ Ác Mộng: Adam Smasher (Ác Mộng; giấc mơ), dùng để Đột phá nhân vật (thẻ bài) Lộ Tây và Lệ Bối Tạp.
- HV V4: Vật phẩm Rơi ra từ Ác Mộng: Adam Smasher (Ác Mộng; giấc mơ), dùng để Đột phá nhân vật (thẻ bài) Lucy và Rebecca.

### `lang_multi_text.db||MultiText||ItemInfo_42100043_BgDescription`
- VI cũ: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học Viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.
- VI V4: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.
- HV cũ: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học Viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.
- HV V4: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.

### `lang_multi_text.db||MultiText||ItemInfo_42100044_BgDescription`
- VI cũ: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học Viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.
- VI V4: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.
- HV cũ: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học Viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.
- HV V4: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.

### `lang_multi_text.db||MultiText||ItemInfo_42100045_BgDescription`
- VI cũ: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học Viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.
- VI V4: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.
- HV cũ: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học Viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.
- HV V4: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.

### `lang_multi_text.db||MultiText||ItemInfo_42100046_BgDescription`
- VI cũ: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học Viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.
- VI V4: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.
- HV cũ: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học Viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.
- HV V4: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.

### `lang_multi_text.db||MultiText||ItemInfo_42100047_BgDescription`
- VI cũ: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học Viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.
- VI V4: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.
- HV cũ: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học Viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.
- HV V4: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.

### `lang_multi_text.db||MultiText||ItemInfo_42100048_BgDescription`
- VI cũ: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học Viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.
- VI V4: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.
- HV cũ: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học Viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.
- HV V4: Một loại thuốc uống do Khoa Y Tế Cộng Hưởng của Học viện Startorch nghiên cứu, với thành phần cốt lõi là vật liệu đặc biệt ở khu vực Laihai-Roi. Lắc đều trước khi uống, có thể tăng cường năng lực can thiệp hài hòa của thuộc tính chỉ định.

### `lang_multi_text.db||MultiText||ItemInfo_42601510_AttributesDescription`
- HV cũ: Nguyên liệu dùng cho đột phá của Lộ Tây và Lệ Bối Tạp.
- HV V4: Nguyên liệu dùng cho đột phá của Lucy và Rebecca.

### `lang_multi_text.db||MultiText||ItemInfo_42601510_ObtainedShowDescription`
- HV cũ: Nguyên liệu dùng để đột phá Lộ Tây và Lệ Bối Tạp.
- HV V4: Nguyên liệu dùng để đột phá Lucy và Rebecca.

### `lang_multi_text.db||MultiText||ItemInfo_50000183_AttributesDescription`
- VI cũ: Sau khi mở trong ba lô có thể chọn nhận 1 trong các Dải Tần Hồi Âm sau: <color=#ffd12f>Dải Tần Hồi Âm của Lucy, Dải Tần Hồi Âm của Rebecca.</color> Dải Tần Hồi Âm của mỗi Cộng Hưởng Giả có thể chọn tối đa <color=#ffd12f>2 lần</color>.\nNếu Dải Tần Hồi Âm của Cộng Hưởng Giả được chọn đã đạt giới hạn, thì Dải Tần Hồi Âm nhận được sẽ tự động chuyển hóa thành <color=#ffd12f>San Hô Ảo Mộng</color>.
- VI V4: Sau khi mở trong ba lô có thể chọn nhận 1 trong các Dải Âm Vang sau: <color=#ffd12f>Dải Âm Vang của Lucy, Dải Âm Vang của Rebecca.</color> Dải Âm Vang của mỗi Cộng Hưởng Giả có thể chọn tối đa <color=#ffd12f>2 lần</color>.\nNếu Dải Âm Vang của Cộng Hưởng Giả được chọn đã đạt giới hạn, thì Dải Âm Vang nhận được sẽ tự động chuyển hóa thành <color=#ffd12f>San Hô Ảo Mộng</color>.
- HV cũ: Sau khi mở trong ba lô có thể chọn nhận 1 trong các Dải Tần Hồi Âm sau: <color=#ffd12f>Dải Tần Hồi Âm của Lộ Tây, Dải Tần Hồi Âm của Lệ Bối Tạp.</color> Dải Tần Hồi Âm của mỗi Cộng Hưởng Giả có thể chọn tối đa <color=#ffd12f>2 lần</color>.\nNếu Dải Tần Hồi Âm của Cộng Hưởng Giả được chọn đã đạt giới hạn, thì Dải Tần Hồi Âm nhận được sẽ tự động chuyển hóa thành <color=#ffd12f>San Hô Ảo Mộng</color>.
- HV V4: Sau khi mở trong ba lô có thể chọn nhận 1 trong các Dải Âm Vang sau: <color=#ffd12f>Dải Âm Vang của Lucy, Dải Âm Vang của Rebecca.</color> Dải Âm Vang của mỗi Cộng Hưởng Giả có thể chọn tối đa <color=#ffd12f>2 lần</color>.\nNếu Dải Âm Vang của Cộng Hưởng Giả được chọn đã đạt giới hạn, thì Dải Âm Vang nhận được sẽ tự động chuyển hóa thành <color=#ffd12f>San Hô Ảo Mộng</color>.

### `lang_multi_text.db||MultiText||ItemInfo_50000183_Name`
- VI cũ: Bên Rìa Giấc Mơ · Tần Đoạn Hồi Âm
- VI V4: Bên Rìa Giấc Mơ · Dải Âm Vang
- HV cũ: Bên Rìa Giấc Mơ · Tần Đoạn Hồi Âm
- HV V4: Bên Rìa Giấc Mơ · Dải Âm Vang

### `lang_multi_text.db||MultiText||ItemInfo_50000183_ObtainedShowDescription`
- VI cũ: Sau khi mở có thể tự chọn Dải Tần Hồi Âm của Lucy hoặc Rebecca.
- VI V4: Sau khi mở có thể tự chọn Dải Âm Vang của Lucy hoặc Rebecca.
- HV cũ: Sau khi mở có thể tự chọn Dải Tần Hồi Âm của Lộ Tây hoặc Lệ Bối Tạp.
- HV V4: Sau khi mở có thể tự chọn Dải Âm Vang của Lucy hoặc Rebecca.

### `lang_multi_text.db||MultiText||ItemInfo_54002_TypeDescription`
- HV cũ: Lâm Nại - Sơn Ấn Tượng
- HV V4: Lynae - Sơn Ấn Tượng

### `lang_multi_text.db||MultiText||ItemInfo_54005_TypeDescription`
- HV cũ: Thiên Tiếu - Sơn Ấn Tượng
- HV V4: Chisa - Sơn Ấn Tượng

### `lang_multi_text.db||MultiText||ItemInfo_70010016_BgDescription`
- HV cũ: Một trong những món quà Nhất Sắc nhờ Lữ Khách thu thập, Hoa Thủy Đăng đặc biệt có thể nở vào ban ngày khi ẩn mình trong bóng tối.
- HV V4: Một trong những món quà Nhất Sắc nhờ Rover thu thập, Hoa Thủy Đăng đặc biệt có thể nở vào ban ngày khi ẩn mình trong bóng tối.

### `lang_multi_text.db||MultiText||ItemInfo_70010017_BgDescription`
- HV cũ: Một trong những món quà Nhất Sắc nhờ Lữ Khách thu thập, món quà chuyên dụng dùng để lấy lòng nhà nghiên cứu.
- HV V4: Một trong những món quà Nhất Sắc nhờ Rover thu thập, món quà chuyên dụng dùng để lấy lòng nhà nghiên cứu.

### `lang_multi_text.db||MultiText||ItemInfo_70010030_AttributesDescription`
- HV cũ: Chiếc hộp mà thủ lĩnh Bang Trư Bà Mục Chi giao cho Lữ Khách.
- HV V4: Chiếc hộp mà thủ lĩnh Bang Trư Bà Mục Chi giao cho Rover.

### `lang_multi_text.db||MultiText||ItemInfo_70010030_BgDescription`
- HV cũ: Chiếc hộp mà Mục Chi thần bí ủy thác Lữ Khách vận chuyển, bên trong hình như chứa một số vũ khí Hắc Thạch, người nhận không rõ...
- HV V4: Chiếc hộp mà Mục Chi thần bí ủy thác Rover vận chuyển, bên trong hình như chứa một số vũ khí Hắc Thạch, người nhận không rõ...

### `lang_multi_text.db||MultiText||ItemInfo_70010030_ObtainedShowDescription`
- HV cũ: Chiếc hộp mà thủ lĩnh Bang Trư Bà Mục Chi giao cho Lữ Khách.
- HV V4: Chiếc hộp mà thủ lĩnh Bang Trư Bà Mục Chi giao cho Rover.

### `lang_multi_text.db||MultiText||ItemInfo_70010039_BgDescription`
- HV cũ: Ảnh phong cảnh do Athos chụp, anh vô ý làm rơi máy ảnh, hy vọng Lữ Khách có thể tìm thấy máy ảnh qua những bức ảnh phong cảnh này.
- HV V4: Ảnh phong cảnh do Athos chụp, anh vô ý làm rơi máy ảnh, hy vọng Rover có thể tìm thấy máy ảnh qua những bức ảnh phong cảnh này.

### `lang_multi_text.db||MultiText||ItemInfo_70010063_AttributesDescription`
- HV cũ: Chiếc chuông mà Lăng Dương đeo khi biểu diễn. Là lời cảm ơn vì đã đồng hành suốt chặng đường, Lăng Dương tặng nó cho bạn.
- HV V4: Chiếc chuông mà Lingyang đeo khi biểu diễn. Là lời cảm ơn vì đã đồng hành suốt chặng đường, Lingyang tặng nó cho bạn.

### `lang_multi_text.db||MultiText||ItemInfo_70010063_ObtainedShowDescription`
- HV cũ: Chiếc chuông mà Lăng Dương đeo khi biểu diễn. Là lời cảm ơn vì đã đồng hành suốt chặng đường, Lăng Dương tặng nó cho bạn.
- HV V4: Chiếc chuông mà Lingyang đeo khi biểu diễn. Là lời cảm ơn vì đã đồng hành suốt chặng đường, Lingyang tặng nó cho bạn.

### `lang_multi_text.db||MultiText||ItemInfo_70010065_Name`
- HV cũ: Sách tranh của Lăng Dương
- HV V4: Sách tranh của Lingyang

### `lang_multi_text.db||MultiText||ItemInfo_70010073_AttributesDescription`
- HV cũ: Quạt Chiết Chi vẽ (mô tả chỉ số)
- HV V4: Quạt Zhezhi vẽ (mô tả chỉ số)

### `lang_multi_text.db||MultiText||ItemInfo_70010073_BgDescription`
- HV cũ: Quạt Chiết Chi vẽ (mô tả bối cảnh chi tiết)
- HV V4: Quạt Zhezhi vẽ (mô tả bối cảnh chi tiết)

### `lang_multi_text.db||MultiText||ItemInfo_70010073_Name`
- HV cũ: Quạt Chiết Chi vẽ (Tên)
- HV V4: Quạt Zhezhi vẽ (Tên)

### `lang_multi_text.db||MultiText||ItemInfo_70010073_ObtainedShowDescription`
- HV cũ: Quạt Chiết Chi vẽ (mô tả khi mới vào túi)
- HV V4: Quạt Zhezhi vẽ (mô tả khi mới vào túi)

### `lang_multi_text.db||MultiText||ItemInfo_70050047_AttributesDescription`
- HV cũ: Module quyền hạn do Kha Lai Tháp đặc biệt ủy quyền cho Lữ Khách, giúp bạn có thể di chuyển tự do không bị cản trở trong Kho Tiền Averardo.
- HV V4: Module quyền hạn do Carlotta đặc biệt ủy quyền cho Rover, giúp bạn có thể di chuyển tự do không bị cản trở trong Kho Tiền Averardo.

### `lang_multi_text.db||MultiText||ItemInfo_70050047_ObtainedShowDescription`
- HV cũ: Module quyền hạn do Kha Lai Tháp đặc biệt ủy quyền cho Lữ Khách, giúp bạn có thể di chuyển tự do không bị cản trở trong Kho Tiền Averardo.
- HV V4: Module quyền hạn do Carlotta đặc biệt ủy quyền cho Rover, giúp bạn có thể di chuyển tự do không bị cản trở trong Kho Tiền Averardo.

### `lang_multi_text.db||MultiText||ItemInfo_70050048_AttributesDescription`
- HV cũ: Module quyền hạn do Kha Lai Tháp đặc biệt ủy quyền cho Lữ Khách, giúp bạn có thể di chuyển tự do không bị cản trở trong Kho Tiền Averardo.
- HV V4: Module quyền hạn do Carlotta đặc biệt ủy quyền cho Rover, giúp bạn có thể di chuyển tự do không bị cản trở trong Kho Tiền Averardo.

### `lang_multi_text.db||MultiText||ItemInfo_70050048_ObtainedShowDescription`
- HV cũ: Module quyền hạn do Kha Lai Tháp đặc biệt ủy quyền cho Lữ Khách, giúp bạn có thể di chuyển tự do không bị cản trở trong Kho Tiền Averardo.
- HV V4: Module quyền hạn do Carlotta đặc biệt ủy quyền cho Rover, giúp bạn có thể di chuyển tự do không bị cản trở trong Kho Tiền Averardo.

### `lang_multi_text.db||MultiText||ItemInfo_70050049_AttributesDescription`
- HV cũ: Module quyền hạn do Kha Lai Tháp đặc biệt ủy quyền cho Lữ Khách, giúp bạn có thể di chuyển tự do không bị cản trở trong Kho Tiền Averardo.
- HV V4: Module quyền hạn do Carlotta đặc biệt ủy quyền cho Rover, giúp bạn có thể di chuyển tự do không bị cản trở trong Kho Tiền Averardo.

### `lang_multi_text.db||MultiText||ItemInfo_70050049_ObtainedShowDescription`
- HV cũ: Module quyền hạn do Kha Lai Tháp đặc biệt ủy quyền cho Lữ Khách, giúp bạn có thể di chuyển tự do không bị cản trở trong Kho Tiền Averardo.
- HV V4: Module quyền hạn do Carlotta đặc biệt ủy quyền cho Rover, giúp bạn có thể di chuyển tự do không bị cản trở trong Kho Tiền Averardo.

### `lang_multi_text.db||MultiText||ItemInfo_70050055_AttributesDescription`
- HV cũ: Vốn là quả bom Tu Hội dùng để hãm hại người Montelli, nhưng nhờ sức mạnh chữa lành linh hồn của Phi Bỉ mà biến thành đạo cụ "cứu người".
- HV V4: Vốn là quả bom Tu Hội dùng để hãm hại người Montelli, nhưng nhờ sức mạnh chữa lành linh hồn của Phoebe mà biến thành đạo cụ "cứu người".

### `lang_multi_text.db||MultiText||ItemInfo_70050055_ObtainedShowDescription`
- HV cũ: Vốn là quả bom Tu Hội dùng để hãm hại người Montelli, nhưng nhờ sức mạnh chữa lành linh hồn của Phi Bỉ mà biến thành đạo cụ "cứu người".
- HV V4: Vốn là quả bom Tu Hội dùng để hãm hại người Montelli, nhưng nhờ sức mạnh chữa lành linh hồn của Phoebe mà biến thành đạo cụ "cứu người".

### `lang_multi_text.db||MultiText||ItemInfo_70050064_AttributesDescription`
- HV cũ: Vũ khí vuốt sắt mà Tán Ny từng sử dụng, một phần của truyền thuyết "Dạ Hành Giả Lửa Sáng".
- HV V4: Vũ khí vuốt sắt mà Zani từng sử dụng, một phần của truyền thuyết "Dạ Hành Giả Lửa Sáng".

### `lang_multi_text.db||MultiText||ItemInfo_70050064_ObtainedShowDescription`
- HV cũ: Vuốt sắt mà Tán Ny từng sử dụng.
- HV V4: Vuốt sắt mà Zani từng sử dụng.

### `lang_multi_text.db||MultiText||ItemInfo_70120008_BgDescription`
- HV cũ: Xuân trong ảnh đang ngồi trên ghế, dường như đang nói gì đó với người bên cạnh.
- HV V4: Camellya trong ảnh đang ngồi trên ghế, dường như đang nói gì đó với người bên cạnh.

### `lang_multi_text.db||MultiText||ItemInfo_70120009_BgDescription`
- HV cũ: Xuân trong ảnh đang ngồi trên ghế, dường như đang nói gì đó với người bên cạnh. Đây là một ngày tổ chức nghi lễ ăn mừng nào đó ở Bờ Biển Đen, những dải ruy băng nhỏ màu vàng bay múa trên không trung, ánh sáng mềm mại rọi lên hoa, gạch đá, mặt biển. Nét mặt của cô ấy khi đó, nay đã không còn ai nhớ nữa.
- HV V4: Camellya trong ảnh đang ngồi trên ghế, dường như đang nói gì đó với người bên cạnh. Đây là một ngày tổ chức nghi lễ ăn mừng nào đó ở Bờ Biển Đen, những dải ruy băng nhỏ màu vàng bay múa trên không trung, ánh sáng mềm mại rọi lên hoa, gạch đá, mặt biển. Nét mặt của cô ấy khi đó, nay đã không còn ai nhớ nữa.

### `lang_multi_text.db||MultiText||ItemInfo_70139331_BgDescription`
- HV cũ: Đang xác nhận thông tin thân phận, mã số nhận dạng "Lữ Khách". Sẽ chuyển giao cho ngài quyền quản lý cao nhất của phòng nghiên cứu "Huanmuque". Mong vật này sẽ giúp ngài mở ra con đường phía trước, và mang lại cho chúng ta câu trả lời cùng sự khai sáng.
- HV V4: Đang xác nhận thông tin thân phận, mã số nhận dạng "Rover". Sẽ chuyển giao cho ngài quyền quản lý cao nhất của phòng nghiên cứu "Huanmuque". Mong vật này sẽ giúp ngài mở ra con đường phía trước, và mang lại cho chúng ta câu trả lời cùng sự khai sáng.

### `lang_multi_text.db||MultiText||ItemInfo_70140017_BgDescription`
- HV cũ: Dị quyền kiếm - "Hognis"\nThanh trường kiếm không ai rõ lai lịch, theo ký ức của Tạp Đề Hi Á, dường như là đạo cụ then chốt để giải phong ấn của Tháp Đảo Ngược.\nTrên thanh trường kiếm tỏa ra khí tức u ám như biển sâu.
- HV V4: Dị quyền kiếm - "Hognis"\nThanh trường kiếm không ai rõ lai lịch, theo ký ức của Cartethyia, dường như là đạo cụ then chốt để giải phong ấn của Tháp Đảo Ngược.\nTrên thanh trường kiếm tỏa ra khí tức u ám như biển sâu.

### `lang_multi_text.db||MultiText||ItemInfo_70140017_ObtainedShowDescription`
- HV cũ: Thanh trường kiếm không ai rõ lai lịch, theo ký ức của Tạp Đề Hi Á, dường như là đạo cụ then chốt để giải phong ấn của Tháp Đảo Ngược.
- HV V4: Thanh trường kiếm không ai rõ lai lịch, theo ký ức của Cartethyia, dường như là đạo cụ then chốt để giải phong ấn của Tháp Đảo Ngược.

### `lang_multi_text.db||MultiText||ItemInfo_70140018_BgDescription`
- HV cũ: Nhân quyền kiếm - "Haultir"\nThanh kiếm mà Tạp Đề Hi Á từng đeo, nay là một trong những chìa khóa giải phong ấn.
- HV V4: Nhân quyền kiếm - "Haultir"\nThanh kiếm mà Cartethyia từng đeo, nay là một trong những chìa khóa giải phong ấn.

### `lang_multi_text.db||MultiText||ItemInfo_70140018_ObtainedShowDescription`
- HV cũ: Thanh kiếm mà Tạp Đề Hi Á từng đeo, nay là một trong những chìa khóa giải phong ấn.
- HV V4: Thanh kiếm mà Cartethyia từng đeo, nay là một trong những chìa khóa giải phong ấn.

### `lang_multi_text.db||MultiText||ItemInfo_70140027_AttributesDescription`
- HV cũ: Tinh thể màu cầu vồng mà Kha Lai Tháp nhét vào tay bạn trước khi chiến đấu, dường như là sản phẩm dị năng lực của cô ấy, cùng loại với viên đạn cô ấy sử dụng khi chiến đấu, có lẽ cô ấy đang muốn truyền đạt thông tin gì đó cho bạn...
- HV V4: Tinh thể màu cầu vồng mà Carlotta nhét vào tay bạn trước khi chiến đấu, dường như là sản phẩm dị năng lực của cô ấy, cùng loại với viên đạn cô ấy sử dụng khi chiến đấu, có lẽ cô ấy đang muốn truyền đạt thông tin gì đó cho bạn...

### `lang_multi_text.db||MultiText||ItemInfo_70140027_Name`
- HV cũ: "Đá Quý" Của Kha Lai Tháp
- HV V4: "Đá Quý" Của Carlotta

### `lang_multi_text.db||MultiText||ItemInfo_70140027_ObtainedShowDescription`
- HV cũ: "Đá Quý" Của Kha Lai Tháp
- HV V4: "Đá Quý" Của Carlotta

### `lang_multi_text.db||MultiText||ItemInfo_70140031_BgDescription`
- HV cũ: Tay quay của máy tạo mây, từng bị thành viên đoàn kịch lấy đi làm bánh xe câu của cần câu cá.\nCó thể lắp ráp với các bộ phận khác của máy tạo mây, sau khi thu thập xong, hãy đi tìm Lạc Khả Khả nhé.
- HV V4: Tay quay của máy tạo mây, từng bị thành viên đoàn kịch lấy đi làm bánh xe câu của cần câu cá.\nCó thể lắp ráp với các bộ phận khác của máy tạo mây, sau khi thu thập xong, hãy đi tìm Roccia nhé.

### `lang_multi_text.db||MultiText||ItemInfo_70140032_BgDescription`
- HV cũ: Đế của máy tạo mây, từng bị thành viên đoàn kịch lấy đi làm bàn để chép nhạc.\nCó thể lắp ráp với các bộ phận khác của máy tạo mây, sau khi thu thập xong, hãy đi tìm Lạc Khả Khả nhé.
- HV V4: Đế của máy tạo mây, từng bị thành viên đoàn kịch lấy đi làm bàn để chép nhạc.\nCó thể lắp ráp với các bộ phận khác của máy tạo mây, sau khi thu thập xong, hãy đi tìm Roccia nhé.

### `lang_multi_text.db||MultiText||ItemInfo_70140033_BgDescription`
- HV cũ: Thiết bị cộng hưởng của máy tạo mây, từng bị thành viên đoàn kịch lấy đi dùng để hiệu chỉnh cao độ và nhịp điệu.\nCó thể lắp ráp với các bộ phận khác của máy tạo mây, sau khi thu thập xong, hãy đi tìm Lạc Khả Khả nhé.
- HV V4: Thiết bị cộng hưởng của máy tạo mây, từng bị thành viên đoàn kịch lấy đi dùng để hiệu chỉnh cao độ và nhịp điệu.\nCó thể lắp ráp với các bộ phận khác của máy tạo mây, sau khi thu thập xong, hãy đi tìm Roccia nhé.

### `lang_multi_text.db||MultiText||ItemInfo_70140034_AttributesDescription`
- HV cũ: Sách do Phi Bỉ tặng, một cuốn sách giới thiệu về thánh điển hiện tại của tu hội, giải thích một cách dễ hiểu giáo lý cơ bản và quan niệm về thần linh của tu hội.
- HV V4: Sách do Phoebe tặng, một cuốn sách giới thiệu về thánh điển hiện tại của tu hội, giải thích một cách dễ hiểu giáo lý cơ bản và quan niệm về thần linh của tu hội.

### `lang_multi_text.db||MultiText||ItemInfo_70140034_BgDescription`
- HV cũ: Sách do Phi Bỉ tặng, một cuốn sách giới thiệu về thánh điển hiện tại của tu hội, giải thích một cách dễ hiểu giáo lý cơ bản và quan niệm về thần linh của tu hội.\nCó thể đọc.
- HV V4: Sách do Phoebe tặng, một cuốn sách giới thiệu về thánh điển hiện tại của tu hội, giải thích một cách dễ hiểu giáo lý cơ bản và quan niệm về thần linh của tu hội.\nCó thể đọc.

### `lang_multi_text.db||MultiText||ItemInfo_70140034_ObtainedShowDescription`
- HV cũ: Sách do Phi Bỉ tặng
- HV V4: Sách do Phoebe tặng

### `lang_multi_text.db||MultiText||ItemInfo_70140035_AttributesDescription`
- HV cũ: Mặt nạ Lễ hội Carnevale do cô Kha Lai Tháp thiết kế riêng cho các bạn, dựa trên ấn tượng về bạn và Abby.
- HV V4: Mặt nạ Lễ hội Carnevale do cô Carlotta thiết kế riêng cho các bạn, dựa trên ấn tượng về bạn và Abby.

### `lang_multi_text.db||MultiText||ItemInfo_70140035_BgDescription`
- HV cũ: Mặt nạ Lễ hội Carnevale do cô Kha Lai Tháp thiết kế riêng cho các bạn, dựa trên ấn tượng về bạn và Abby.\nMặt nạ sử dụng thiết kế che nửa mặt, vừa giữ được nét cá tính và sự bí ẩn, vừa tính đến nhu cầu khi chiến đấu một cách rất tốt, không có quá nhiều đồ trang trí rườm rà, không đến mức cản trở tầm nhìn cản trở hành động.\nCó thể đeo.
- HV V4: Mặt nạ Lễ hội Carnevale do cô Carlotta thiết kế riêng cho các bạn, dựa trên ấn tượng về bạn và Abby.\nMặt nạ sử dụng thiết kế che nửa mặt, vừa giữ được nét cá tính và sự bí ẩn, vừa tính đến nhu cầu khi chiến đấu một cách rất tốt, không có quá nhiều đồ trang trí rườm rà, không đến mức cản trở tầm nhìn cản trở hành động.\nCó thể đeo.

### `lang_multi_text.db||MultiText||ItemInfo_70140035_ObtainedShowDescription`
- HV cũ: Mặt nạ Lễ hội Carnevale do Kha Lai Tháp tặng
- HV V4: Mặt nạ Lễ hội Carnevale do Carlotta tặng

### `lang_multi_text.db||MultiText||ItemInfo_70140041_AttributesDescription`
- HV cũ: Kỹ năng của Lữ Khách - Quang Phổ đã được cường hóa, có thể đến giao diện Cộng Hưởng Giả - Kỹ Năng để xem chi tiết.
- HV V4: Kỹ năng của Rover - Quang Phổ đã được cường hóa, có thể đến giao diện Cộng Hưởng Giả - Kỹ Năng để xem chi tiết.

### `lang_multi_text.db||MultiText||ItemInfo_70140050_AttributesDescription`
- HV cũ: Đạo cụ do Tạp Đề Hi Á truyền dạy cách sử dụng, sau khi trang bị vào công cụ khám phá, có thể triệu hồi thuyền Gondola "Phaom" ở gần vùng nước. (Chỉ có thể sử dụng ở khu vực Avinoleum)
- HV V4: Đạo cụ do Cartethyia truyền dạy cách sử dụng, sau khi trang bị vào công cụ khám phá, có thể triệu hồi thuyền Gondola "Phaom" ở gần vùng nước. (Chỉ có thể sử dụng ở khu vực Avinoleum)

### `lang_multi_text.db||MultiText||ItemInfo_70140050_BgDescription`
- HV cũ: Đạo cụ do Tạp Đề Hi Á truyền dạy cách sử dụng
- HV V4: Đạo cụ do Cartethyia truyền dạy cách sử dụng

### `lang_multi_text.db||MultiText||ItemInfo_70140050_ObtainedShowDescription`
- HV cũ: Đạo cụ do Tạp Đề Hi Á truyền dạy cách sử dụng, sau khi trang bị vào công cụ khám phá, có thể triệu hồi thuyền Gondola "Phaom" ở gần vùng nước. (Chỉ có thể sử dụng ở khu vực Avinoleum)
- HV V4: Đạo cụ do Cartethyia truyền dạy cách sử dụng, sau khi trang bị vào công cụ khám phá, có thể triệu hồi thuyền Gondola "Phaom" ở gần vùng nước. (Chỉ có thể sử dụng ở khu vực Avinoleum)

### `lang_multi_text.db||MultiText||ItemInfo_70140080_AttributesDescription`
- HV cũ: Gậy chỉ huy của Phất Lạc Lạc, trong đó ẩn chứa một phần năng lực cộng hưởng của cô ấy.
- HV V4: Gậy chỉ huy của Phrolova, trong đó ẩn chứa một phần năng lực cộng hưởng của cô ấy.

### `lang_multi_text.db||MultiText||ItemInfo_70140080_ObtainedShowDescription`
- HV cũ: Gậy chỉ huy của Phất Lạc Lạc, trong đó ẩn chứa một phần năng lực cộng hưởng của cô ấy.
- HV V4: Gậy chỉ huy của Phrolova, trong đó ẩn chứa một phần năng lực cộng hưởng của cô ấy.

### `lang_multi_text.db||MultiText||ItemInfo_70140081_AttributesDescription`
- HV cũ: Tàn dư năng lực cộng hưởng của Phất Lạc Lạc, tuy không thể so sánh với năng lượng trong gậy chỉ huy, nhưng cũng miễn cưỡng phát huy tác dụng của điều luật.
- HV V4: Tàn dư năng lực cộng hưởng của Phrolova, tuy không thể so sánh với năng lượng trong gậy chỉ huy, nhưng cũng miễn cưỡng phát huy tác dụng của điều luật.

### `lang_multi_text.db||MultiText||ItemInfo_70140081_ObtainedShowDescription`
- HV cũ: Tàn dư năng lực cộng hưởng của Phất Lạc Lạc, tuy không thể so sánh với năng lượng trong gậy chỉ huy, nhưng cũng miễn cưỡng phát huy tác dụng của điều luật.
- HV V4: Tàn dư năng lực cộng hưởng của Phrolova, tuy không thể so sánh với năng lượng trong gậy chỉ huy, nhưng cũng miễn cưỡng phát huy tác dụng của điều luật.

### `lang_multi_text.db||MultiText||ItemInfo_70140086_AttributesDescription`
- VI cũ: Mô-đun Hack Nhanh do Lucy cung cấp. Có thể dùng để Hack Hack Nhanh các Cơ Quan bên trong Somnoire: Night City - Tâm Chi Tập Vực · Somnoire · Night City.
- VI V4: Mô-đun Hack Nhanh do Lucy cung cấp. Có thể dùng để hack nhanh các cơ quan bên trong Somnoire: Night City.
- HV cũ: Mô-đun Hack Nhanh do Lộ Tây cung cấp. Có thể dùng để Hack Hack Nhanh các Cơ Quan bên trong Somnoire: Night City - Tâm Chi Tập Vực · Somnoire · Night City.
- HV V4: Mô-đun Hack Nhanh do Lucy cung cấp. Có thể dùng để hack nhanh các cơ quan bên trong Somnoire: Night City.

### `lang_multi_text.db||MultiText||ItemInfo_70163901_AttributesDescription`
- HV cũ: Món quà mà Lạc Khả Khả tặng bạn, những đường vân ánh sáng màu vàng rực rỡ lấp lánh trên hòn đá màu đen, dịu dàng tỏa sáng như đôi mắt của bạn.
- HV V4: Món quà mà Roccia tặng bạn, những đường vân ánh sáng màu vàng rực rỡ lấp lánh trên hòn đá màu đen, dịu dàng tỏa sáng như đôi mắt của bạn.

### `lang_multi_text.db||MultiText||ItemInfo_70163901_BgDescription`
- HV cũ: Một viên Đá Đom Đóm Biển không biết đã bị thủy triều cuốn lên bờ từ lúc nào, ngủ yên trong một thời gian dài dằng dặc. Viên Đá Đom Đóm Biển này rất đặc biệt, cho dù trải qua vạn năm mưa gió, năm tháng bào mòn, cũng không mất đi ánh sáng, vẫn lấp lánh như thuở ban đầu. Lạc Khả Khả đã cẩn thận nhặt nó lên, lau chùi, cất giữ, do dự hồi lâu, cuối cùng cũng lấy hết can đảm, tặng nó cho bạn.
- HV V4: Một viên Đá Đom Đóm Biển không biết đã bị thủy triều cuốn lên bờ từ lúc nào, ngủ yên trong một thời gian dài dằng dặc. Viên Đá Đom Đóm Biển này rất đặc biệt, cho dù trải qua vạn năm mưa gió, năm tháng bào mòn, cũng không mất đi ánh sáng, vẫn lấp lánh như thuở ban đầu. Roccia đã cẩn thận nhặt nó lên, lau chùi, cất giữ, do dự hồi lâu, cuối cùng cũng lấy hết can đảm, tặng nó cho bạn.

### `lang_multi_text.db||MultiText||ItemInfo_70163901_Name`
- HV cũ: Món Quà Của Lạc Khả Khả: Đá Đom Đóm Biển
- HV V4: Món Quà Của Roccia: Đá Đom Đóm Biển

### `lang_multi_text.db||MultiText||ItemInfo_70163901_ObtainedShowDescription`
- HV cũ: Món quà mà Lạc Khả Khả tặng bạn, những đường vân ánh sáng màu vàng rực rỡ lấp lánh trên hòn đá màu đen.
- HV V4: Món quà mà Roccia tặng bạn, những đường vân ánh sáng màu vàng rực rỡ lấp lánh trên hòn đá màu đen.

### `lang_multi_text.db||MultiText||ItemInfo_70290001_BgDescription`
- HV cũ: Giấy báo trúng tuyển do Thủ Ngạn Nhân chuẩn bị cho bạn, mọi chứng nhận và tư cách nhập học luôn có hiệu lực.\nBên trên viết "Đã thông qua bài kiểm tra Thích Cách Giả, khớp đường cong Rabelle, có khả năng thích ứng Exostrider".
- HV V4: Giấy báo trúng tuyển do Shorekeeper chuẩn bị cho bạn, mọi chứng nhận và tư cách nhập học luôn có hiệu lực.\nBên trên viết "Đã thông qua bài kiểm tra Thích Cách Giả, khớp đường cong Rabelle, có khả năng thích ứng Exostrider".

### `lang_multi_text.db||MultiText||ItemInfo_70290003_AttributesDescription`
- HV cũ: Lớp sơn xe máy thám hiểm mà Lâm Nại tặng cho bạn, như một kỷ niệm về cuộc gặp gỡ và sát cánh chiến đấu.
- HV V4: Lớp sơn xe máy thám hiểm mà Lynae tặng cho bạn, như một kỷ niệm về cuộc gặp gỡ và sát cánh chiến đấu.

### `lang_multi_text.db||MultiText||ItemInfo_70290003_ObtainedShowDescription`
- HV cũ: Lớp sơn xe máy thám hiểm mà Lâm Nại tặng cho bạn, như một kỷ niệm về cuộc gặp gỡ và sát cánh chiến đấu.
- HV V4: Lớp sơn xe máy thám hiểm mà Lynae tặng cho bạn, như một kỷ niệm về cuộc gặp gỡ và sát cánh chiến đấu.

### `lang_multi_text.db||MultiText||ItemInfo_70290005_AttributesDescription`
- HV cũ: Bức ảnh chụp chung ba người của bạn với Lâm Nại, Mornye dưới Mặt Trời Mới.
- HV V4: Bức ảnh chụp chung ba người của bạn với Lynae, Mornye dưới Mặt Trời Mới.

### `lang_multi_text.db||MultiText||ItemInfo_70290005_BgDescription`
- HV cũ: Bức ảnh chụp chung ba người của bạn với Lâm Nại, Mornye dưới Mặt Trời Mới. Dưới ánh hào quang của "Helios", một tương lai rộng mở hơn đang mở ra trước mắt.\n\n"Kính tự do, kính văn minh, kính sự sống mới!"
- HV V4: Bức ảnh chụp chung ba người của bạn với Lynae, Mornye dưới Mặt Trời Mới. Dưới ánh hào quang của "Helios", một tương lai rộng mở hơn đang mở ra trước mắt.\n\n"Kính tự do, kính văn minh, kính sự sống mới!"

### `lang_multi_text.db||MultiText||ItemInfo_70290005_ObtainedShowDescription`
- HV cũ: Bức ảnh chụp chung ba người của bạn với Lâm Nại, Mornye dưới Mặt Trời Mới.
- HV V4: Bức ảnh chụp chung ba người của bạn với Lynae, Mornye dưới Mặt Trời Mới.

### `lang_multi_text.db||MultiText||ItemInfo_70290007_AttributesDescription`
- HV cũ: Bức ảnh chụp chung ba người của bạn với Lâm Nại, Mornye dưới Mặt Trời Mới.
- HV V4: Bức ảnh chụp chung ba người của bạn với Lynae, Mornye dưới Mặt Trời Mới.

### `lang_multi_text.db||MultiText||ItemInfo_70290007_BgDescription`
- HV cũ: Bức ảnh chụp chung ba người của bạn với Lâm Nại, Mornye dưới Mặt Trời Mới. Dưới ánh hào quang của "Helios", một tương lai rộng mở hơn đang mở ra trước mắt.\n\n"Kính tự do, kính văn minh, kính sự sống mới!"
- HV V4: Bức ảnh chụp chung ba người của bạn với Lynae, Mornye dưới Mặt Trời Mới. Dưới ánh hào quang của "Helios", một tương lai rộng mở hơn đang mở ra trước mắt.\n\n"Kính tự do, kính văn minh, kính sự sống mới!"

### `lang_multi_text.db||MultiText||ItemInfo_70290007_ObtainedShowDescription`
- HV cũ: Bức ảnh chụp chung ba người của bạn với Lâm Nại, Mornye dưới Mặt Trời Mới.
- HV V4: Bức ảnh chụp chung ba người của bạn với Lynae, Mornye dưới Mặt Trời Mới.

### `lang_multi_text.db||MultiText||ItemInfo_70320000_AttributesDescription`
- HV cũ: Thiết bị liên lạc mà Hạ Không giao cho bạn, vẻ ngoài giống với gương trang điểm.
- HV V4: Thiết bị liên lạc mà Ciaccona giao cho bạn, vẻ ngoài giống với gương trang điểm.

### `lang_multi_text.db||MultiText||ItemInfo_70320000_BgDescription`
- HV cũ: Thiết bị liên lạc do Hạ Không giao cho mình, được thiết kế theo phong cách cá nhân của cô ấy, có tính ngụy trang khá tốt.
- HV V4: Thiết bị liên lạc do Ciaccona giao cho mình, được thiết kế theo phong cách cá nhân của cô ấy, có tính ngụy trang khá tốt.

### `lang_multi_text.db||MultiText||ItemInfo_70320000_Name`
- HV cũ: Thiết Bị Liên Lạc Của Hạ Không
- HV V4: Thiết Bị Liên Lạc Của Ciaccona

### `lang_multi_text.db||MultiText||ItemInfo_70320001_Name`
- VI cũ: 《Báo Cáo Điều Tra Mặt Tối Học Viện Startorch Số AN25360》
- VI V4: 《Báo Cáo Điều Tra Mặt Tối Học viện Startorch Số AN25360》
- HV cũ: 《Báo Cáo Điều Tra Mặt Tối Học Viện Startorch Số AN25360》
- HV V4: 《Báo Cáo Điều Tra Mặt Tối Học viện Startorch Số AN25360》

### `lang_multi_text.db||MultiText||ItemInfo_70320011_AttributesDescription`
- HV cũ: Sau khi sử dụng, có thể chọn nhận một trong ba Cộng Hưởng Giả: <color=#ffd12f>Thủ Ngạn Nhân, Xuân, Kim Tịch</color>, hoặc chọn nhận Máy Chỉnh Tần*8.
- HV V4: Sau khi sử dụng, có thể chọn nhận một trong ba Cộng Hưởng Giả: <color=#ffd12f>Shorekeeper, Camellya, Kim Tịch</color>, hoặc chọn nhận Máy Chỉnh Tần*8.

### `lang_multi_text.db||MultiText||ItemInfo_70320011_ObtainedShowDescription`
- HV cũ: Sau khi sử dụng, có thể chọn nhận một trong ba Cộng Hưởng Giả: <color=#ffd12f>Thủ Ngạn Nhân, Xuân, Kim Tịch</color>, hoặc Máy Chỉnh Tần*8.
- HV V4: Sau khi sử dụng, có thể chọn nhận một trong ba Cộng Hưởng Giả: <color=#ffd12f>Shorekeeper, Camellya, Kim Tịch</color>, hoặc Máy Chỉnh Tần*8.

### `lang_multi_text.db||MultiText||ItemInfo_70340008_AttributesDescription`
- HV cũ: Con mèo đen gấp giấy mà Tây Cách Lị Tạp tặng cho bạn, trông có hơi xiêu vẹo, nhưng lại ẩn chứa lời cảm ơn chân thành của thiếu nữ.
- HV V4: Con mèo đen gấp giấy mà Sigrika tặng cho bạn, trông có hơi xiêu vẹo, nhưng lại ẩn chứa lời cảm ơn chân thành của thiếu nữ.

### `lang_multi_text.db||MultiText||ItemInfo_70340008_ObtainedShowDescription`
- HV cũ: Con mèo đen gấp giấy mà Tây Cách Lị Tạp tặng cho bạn.
- HV V4: Con mèo đen gấp giấy mà Sigrika tặng cho bạn.

### `lang_multi_text.db||MultiText||ItemInfo_71200009_AttributesDescription`
- HV cũ: Một món quà đến từ Hiệu trưởng Lucilla. Lộ Tây đã để nó lại ở Solaris, tỉnh dậy từ giấc mơ chưa từng lựa chọn.
- HV V4: Một món quà đến từ Hiệu trưởng Lucilla. Lucy đã để nó lại ở Solaris, tỉnh dậy từ giấc mơ chưa từng lựa chọn.

### `lang_multi_text.db||MultiText||ItemInfo_71200010_AttributesDescription`
- VI cũ: Một món quà đến từ Hiệu Trưởng Lucilla. Lucy đã để lại nó tại Solaris (Solaris-3), tỉnh dậy từ giấc mơ Mùi từng Lựa Chọn.
- VI V4: Một món quà từ Hiệu trưởng Lucilla. Lucy đã để nó lại ở Solaris khi tỉnh dậy khỏi giấc mơ mà cô chưa từng lựa chọn.
- HV cũ: Một món quà đến từ Hiệu Trưởng Lucilla. Lộ Tây đã để lại nó tại Solaris (Solaris-3), tỉnh dậy từ giấc mơ Mùi từng Lựa Chọn.
- HV V4: Một món quà từ Hiệu trưởng Lucilla. Lucy đã để nó lại ở Solaris khi tỉnh dậy khỏi giấc mơ mà cô chưa từng lựa chọn.

### `lang_multi_text.db||MultiText||ItemInfo_71200011_BgDescription`
- HV cũ: Đừng để ký ức mê hoặc, Lữ Khách.
- HV V4: Đừng để ký ức mê hoặc, Rover.

### `lang_multi_text.db||MultiText||ItemInfo_71210004_AttributesDescription`
- HV cũ: Trâm cài áo đá mắt mèo mà Kha Lai Tháp tặng bạn, là vật chỉ định phù hợp với đôi mắt của bạn, cũng là một phần tâm ý của cô ấy.
- HV V4: Trâm cài áo đá mắt mèo mà Carlotta tặng bạn, là vật chỉ định phù hợp với đôi mắt của bạn, cũng là một phần tâm ý của cô ấy.

### `lang_multi_text.db||MultiText||ItemInfo_71210004_BgDescription`
- HV cũ: Ở nhà Montelli, mỗi thành viên đều có vật chỉ định phù hợp với biệt danh. Có lẽ trong lần đầu tiên chú ý đến đôi mắt của bạn, vì bạn mà đặt ra biệt danh mang tên "Đá Mắt Mèo", Kha Lai Tháp đã đang chuẩn bị món quà này. Mặc dù bạn vẫn chưa dự định thực sự trở thành một thành viên của nhà Montelli, nhưng bạn biết cô ấy sẽ vĩnh viễn giữ lại biệt danh này cho bạn - Đá Mắt Mèo được Opal tiến cử.
- HV V4: Ở nhà Montelli, mỗi thành viên đều có vật chỉ định phù hợp với biệt danh. Có lẽ trong lần đầu tiên chú ý đến đôi mắt của bạn, vì bạn mà đặt ra biệt danh mang tên "Đá Mắt Mèo", Carlotta đã đang chuẩn bị món quà này. Mặc dù bạn vẫn chưa dự định thực sự trở thành một thành viên của nhà Montelli, nhưng bạn biết cô ấy sẽ vĩnh viễn giữ lại biệt danh này cho bạn - Đá Mắt Mèo được Opal tiến cử.

### `lang_multi_text.db||MultiText||ItemInfo_71210004_ObtainedShowDescription`
- HV cũ: Trâm cài áo đá mắt mèo mà Kha Lai Tháp tặng bạn.
- HV V4: Trâm cài áo đá mắt mèo mà Carlotta tặng bạn.

### `lang_multi_text.db||MultiText||ItemInfo_71210006_AttributesDescription`
- HV cũ: Ký tự Rune do Tây Cách Lị Tạp khắc ấn cho cậu.
- HV V4: Ký tự Rune do Sigrika khắc ấn cho cậu.

### `lang_multi_text.db||MultiText||ItemInfo_71210006_BgDescription`
- HV cũ: Ký tự Rune do Tây Cách Lị Tạp khắc ấn cho cậu, cậu có thể cảm nhận được sức mạnh trong ký tự Rune đó đang chảy ấm áp trong lòng bàn tay.\nNó có thể giúp cậu nhìn rõ những mảnh vỡ ký tự Rune Roya tản mác khắp Lahai-Roi, để khôi phục lại hình dáng ban đầu của chúng.\nRốt cuộc là ai, thông qua cách nào, dựa vào ký tự Rune Roya để khắc lên bình nguyên những thông điệp rời rạc đó?
- HV V4: Ký tự Rune do Sigrika khắc ấn cho cậu, cậu có thể cảm nhận được sức mạnh trong ký tự Rune đó đang chảy ấm áp trong lòng bàn tay.\nNó có thể giúp cậu nhìn rõ những mảnh vỡ ký tự Rune Roya tản mác khắp Lahai-Roi, để khôi phục lại hình dáng ban đầu của chúng.\nRốt cuộc là ai, thông qua cách nào, dựa vào ký tự Rune Roya để khắc lên bình nguyên những thông điệp rời rạc đó?

### `lang_multi_text.db||MultiText||ItemInfo_71210006_ObtainedShowDescription`
- HV cũ: Ký tự Rune do Tây Cách Lị Tạp khắc ấn cho cậu.
- HV V4: Ký tự Rune do Sigrika khắc ấn cho cậu.

### `lang_multi_text.db||MultiText||ItemInfo_71250001_AttributesDescription`
- HV cũ: Kịch bản mà Phất Lạc Lạc giao cho bạn.
- HV V4: Kịch bản mà Phrolova giao cho bạn.

### `lang_multi_text.db||MultiText||ItemInfo_71250001_ObtainedShowDescription`
- HV cũ: Kịch bản mà Phất Lạc Lạc giao cho bạn.
- HV V4: Kịch bản mà Phrolova giao cho bạn.

### `lang_multi_text.db||MultiText||ItemInfo_71250002_BgDescription`
- HV cũ: Huân chương bị chia làm hai, một nửa khác đang được đeo trước ngực Lộ Mạt.\nNó là chứng nhận lúc này bạn đang tắm mình trong sự tán dương của Thành Phố Vinh Quang, cũng là thành quả chiến thắng mà bạn và cô ấy cùng nhau sát cánh chiến đấu.
- HV V4: Huân chương bị chia làm hai, một nửa khác đang được đeo trước ngực Lupa.\nNó là chứng nhận lúc này bạn đang tắm mình trong sự tán dương của Thành Phố Vinh Quang, cũng là thành quả chiến thắng mà bạn và cô ấy cùng nhau sát cánh chiến đấu.

### `lang_multi_text.db||MultiText||ItemInfo_71250003_AttributesDescription`
- HV cũ: Một khoảnh khắc trong ký ức, thuộc về Lộ Mạt trong thành phố Septimont.
- HV V4: Một khoảnh khắc trong ký ức, thuộc về Lupa trong thành phố Septimont.

### `lang_multi_text.db||MultiText||ItemInfo_71250004_AttributesDescription`
- HV cũ: Một khoảnh khắc trong ký ức, thuộc về Tạp Đề Hi Á trong thành phố Septimont.
- HV V4: Một khoảnh khắc trong ký ức, thuộc về Cartethyia trong thành phố Septimont.

### `lang_multi_text.db||MultiText||ItemInfo_71250005_AttributesDescription`
- HV cũ: Gương đồng mà Bặc Linh giao cho bạn.
- HV V4: Gương đồng mà Buling giao cho bạn.

### `lang_multi_text.db||MultiText||ItemInfo_71260001_AttributesDescription`
- HV cũ: Khi Fabricatorium được xây dựng xong, Phất Lạc Lạc đã viết ra bản nhạc này. Cô ấy hòa quyện giai điệu quá khứ vào trong đó, mong đợi những người trong lòng cô ấy giống như bản nhạc này, có thể vang lên trong thế giới hiện thực.
- HV V4: Khi Fabricatorium được xây dựng xong, Phrolova đã viết ra bản nhạc này. Cô ấy hòa quyện giai điệu quá khứ vào trong đó, mong đợi những người trong lòng cô ấy giống như bản nhạc này, có thể vang lên trong thế giới hiện thực.

### `lang_multi_text.db||MultiText||ItemInfo_71260002_AttributesDescription`
- HV cũ: Khi Fabricatorium được xây dựng xong, Phất Lạc Lạc đã viết ra bản nhạc này. Cô ấy hòa quyện giai điệu quá khứ vào trong đó, mong đợi những người trong lòng cô ấy giống như bản nhạc này, có thể vang lên trong thế giới hiện thực.
- HV V4: Khi Fabricatorium được xây dựng xong, Phrolova đã viết ra bản nhạc này. Cô ấy hòa quyện giai điệu quá khứ vào trong đó, mong đợi những người trong lòng cô ấy giống như bản nhạc này, có thể vang lên trong thế giới hiện thực.

### `lang_multi_text.db||MultiText||ItemInfo_71260003_AttributesDescription`
- HV cũ: Khi Fabricatorium được xây dựng xong, Phất Lạc Lạc đã viết ra bản nhạc này. Cô ấy hòa quyện giai điệu quá khứ vào trong đó, mong đợi những người trong lòng cô ấy giống như bản nhạc này, có thể vang lên trong thế giới hiện thực.
- HV V4: Khi Fabricatorium được xây dựng xong, Phrolova đã viết ra bản nhạc này. Cô ấy hòa quyện giai điệu quá khứ vào trong đó, mong đợi những người trong lòng cô ấy giống như bản nhạc này, có thể vang lên trong thế giới hiện thực.

### `lang_multi_text.db||MultiText||ItemInfo_71270010_AttributesDescription`
- HV cũ: Thư viết tay của Áo Cổ Tư Tháp.
- HV V4: Thư viết tay của Augusta.

### `lang_multi_text.db||MultiText||ItemInfo_71270010_ObtainedShowDescription`
- HV cũ: Thư viết tay của Áo Cổ Tư Tháp, nét chữ ngay ngắn nhưng lại có nhiều chỗ dừng lại ở chỗ hạ bút, dường như đã cân nhắc từ ngữ rất lâu.
- HV V4: Thư viết tay của Augusta, nét chữ ngay ngắn nhưng lại có nhiều chỗ dừng lại ở chỗ hạ bút, dường như đã cân nhắc từ ngữ rất lâu.

### `lang_multi_text.db||MultiText||ItemInfo_71510101_AttributesDescription`
- HV cũ: Quyển sách nhỏ tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Lữ Khách, tăng giá khi bán chiến lợi phẩm.
- HV V4: Quyển sách nhỏ tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Rover, tăng giá khi bán chiến lợi phẩm.

### `lang_multi_text.db||MultiText||ItemInfo_71510101_ObtainedShowDescription`
- HV cũ: Quyển sách nhỏ tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Lữ Khách, tăng giá khi bán chiến lợi phẩm.
- HV V4: Quyển sách nhỏ tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Rover, tăng giá khi bán chiến lợi phẩm.

### `lang_multi_text.db||MultiText||ItemInfo_71510102_AttributesDescription`
- HV cũ: Quyển sách nhỏ tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Lữ Khách, tăng Xu Ngư Nghiệp nhận được trong ủy thác.
- HV V4: Quyển sách nhỏ tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Rover, tăng Xu Ngư Nghiệp nhận được trong ủy thác.

### `lang_multi_text.db||MultiText||ItemInfo_71510102_ObtainedShowDescription`
- HV cũ: Quyển sách nhỏ tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Lữ Khách, tăng Xu Ngư Nghiệp nhận được trong ủy thác.
- HV V4: Quyển sách nhỏ tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Rover, tăng Xu Ngư Nghiệp nhận được trong ủy thác.

### `lang_multi_text.db||MultiText||ItemInfo_71510103_AttributesDescription`
- HV cũ: Quyển sách nhỏ tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Lữ Khách, tăng nguyên liệu nhận được khi gia công vật tư.
- HV V4: Quyển sách nhỏ tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Rover, tăng nguyên liệu nhận được khi gia công vật tư.

### `lang_multi_text.db||MultiText||ItemInfo_71510103_ObtainedShowDescription`
- HV cũ: Quyển sách nhỏ tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Lữ Khách, tăng nguyên liệu nhận được khi gia công vật tư.
- HV V4: Quyển sách nhỏ tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Rover, tăng nguyên liệu nhận được khi gia công vật tư.

### `lang_multi_text.db||MultiText||ItemInfo_71510201_AttributesDescription`
- HV cũ: Đoạn kinh văn tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Phi Bỉ, tăng ô ủy thác và giảm tiêu hao ủy thác.
- HV V4: Đoạn kinh văn tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Phoebe, tăng ô ủy thác và giảm tiêu hao ủy thác.

### `lang_multi_text.db||MultiText||ItemInfo_71510201_ObtainedShowDescription`
- HV cũ: Đoạn kinh văn tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Phi Bỉ, tăng ô ủy thác và giảm tiêu hao ủy thác.
- HV V4: Đoạn kinh văn tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Phoebe, tăng ô ủy thác và giảm tiêu hao ủy thác.

### `lang_multi_text.db||MultiText||ItemInfo_71510202_AttributesDescription`
- HV cũ: Đoạn kinh văn tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Phi Bỉ, tăng độ bền thân tàu.
- HV V4: Đoạn kinh văn tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Phoebe, tăng độ bền thân tàu.

### `lang_multi_text.db||MultiText||ItemInfo_71510202_ObtainedShowDescription`
- HV cũ: Đoạn kinh văn tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Phi Bỉ, tăng độ bền thân tàu.
- HV V4: Đoạn kinh văn tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Phoebe, tăng độ bền thân tàu.

### `lang_multi_text.db||MultiText||ItemInfo_71510203_AttributesDescription`
- HV cũ: Đoạn kinh văn tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Phi Bỉ, tăng xác suất bắt được cá biến dị.
- HV V4: Đoạn kinh văn tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Phoebe, tăng xác suất bắt được cá biến dị.

### `lang_multi_text.db||MultiText||ItemInfo_71510203_ObtainedShowDescription`
- HV cũ: Đoạn kinh văn tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Phi Bỉ, tăng xác suất bắt được cá biến dị.
- HV V4: Đoạn kinh văn tình cờ có được, có thể nâng cao kỹ năng đánh bắt của Phoebe, tăng xác suất bắt được cá biến dị.

### `lang_multi_text.db||MultiText||ItemInfo_71550005_AttributesDescription`
- HV cũ: Lọ bí dược Khảm Đặc Lôi Lạp luôn mang bên mình. Thân lọ tinh xảo được nạm một viên lam ngọc, biểu tượng cho quyền uy của gia chủ.\nVới người nhà Fisalia, thứ cất trong lọ không chỉ là dược phẩm, mà còn là toàn bộ bản chất của người điều chế — niềm tin, cảm xúc và linh hồn của họ...
- HV V4: Lọ bí dược Cantarella luôn mang bên mình. Thân lọ tinh xảo được nạm một viên lam ngọc, biểu tượng cho quyền uy của gia chủ.\nVới người nhà Fisalia, thứ cất trong lọ không chỉ là dược phẩm, mà còn là toàn bộ bản chất của người điều chế — niềm tin, cảm xúc và linh hồn của họ...

### `lang_multi_text.db||MultiText||ItemInfo_71550005_BgDescription`
- HV cũ: Tín vật Khảm Đặc Lôi Lạp trao cho bạn. Trong lọ là bí dược cô đặc biệt pha chế riêng, mang hương thơm thanh dịu giúp an thần. Cô đã nhận ra sự khác biệt nơi bạn, những trọng trách bạn gánh vác và mọi nỗ lực bạn đã bỏ ra. Bằng tất cả sự quan tâm, cô mong thứ thuốc này sẽ giúp bạn ngủ yên, dù đang ở bất cứ nơi đâu.\nChiếc lọ còn chứa đựng sự chân thành và tình cảm sâu sắc nhất của cô dành cho bạn. Người sở hữu nó được tự do ra vào Lâu Đài Porto-Veno; mọi bí dược, bí mật và tài nguyên của nhà Fisalia... đều có thể tùy ý sử dụng.
- HV V4: Tín vật Cantarella trao cho bạn. Trong lọ là bí dược cô đặc biệt pha chế riêng, mang hương thơm thanh dịu giúp an thần. Cô đã nhận ra sự khác biệt nơi bạn, những trọng trách bạn gánh vác và mọi nỗ lực bạn đã bỏ ra. Bằng tất cả sự quan tâm, cô mong thứ thuốc này sẽ giúp bạn ngủ yên, dù đang ở bất cứ nơi đâu.\nChiếc lọ còn chứa đựng sự chân thành và tình cảm sâu sắc nhất của cô dành cho bạn. Người sở hữu nó được tự do ra vào Lâu Đài Porto-Veno; mọi bí dược, bí mật và tài nguyên của nhà Fisalia... đều có thể tùy ý sử dụng.

### `lang_multi_text.db||MultiText||ItemInfo_71550005_ObtainedShowDescription`
- HV cũ: Tín vật mà Khảm Đặc Lôi Lạp trao cho bạn, trên thân lọ tinh xảo được nạm viên ngọc bích tượng trưng cho quyền lực của gia chủ nhà Fisalia.
- HV V4: Tín vật mà Cantarella trao cho bạn, trên thân lọ tinh xảo được nạm viên ngọc bích tượng trưng cho quyền lực của gia chủ nhà Fisalia.

### `lang_multi_text.db||MultiText||ItemInfo_71580001_AttributesDescription`
- HV cũ: Mặt dây chuyền từng được Tạp Đề Hi Á đeo sát bên tim. Dường như cô đã để lại một lời nhắn trong đó. Tần số của cô vẫn còn lưu lại trong bạn; nếu cộng hưởng với mặt dây chuyền, bạn có thể nghe được lời nhắn ấy.
- HV V4: Mặt dây chuyền từng được Cartethyia đeo sát bên tim. Dường như cô đã để lại một lời nhắn trong đó. Tần số của cô vẫn còn lưu lại trong bạn; nếu cộng hưởng với mặt dây chuyền, bạn có thể nghe được lời nhắn ấy.

### `lang_multi_text.db||MultiText||ItemInfo_71580001_Name`
- HV cũ: Mặt Dây Chuyền Của Tạp Đề Hi Á
- HV V4: Mặt Dây Chuyền Của Cartethyia

### `lang_multi_text.db||MultiText||ItemInfo_71580001_ObtainedShowDescription`
- HV cũ: Mặt dây chuyền từng được Tạp Đề Hi Á đeo sát bên tim. Không rõ vì sao nó lại rơi vào tay “Thợ Săn Quỷ”...
- HV V4: Mặt dây chuyền từng được Cartethyia đeo sát bên tim. Không rõ vì sao nó lại rơi vào tay “Thợ Săn Quỷ”...

### `lang_multi_text.db||MultiText||ItemInfo_71600003_AttributesDescription`
- HV cũ: Quyển sách nhạc mà Hạ Không tặng cho bạn, trên đó ghi lại những giai điệu mà cô ấy ghi chép lại trong những chuyến du hành trước đây.
- HV V4: Quyển sách nhạc mà Ciaccona tặng cho bạn, trên đó ghi lại những giai điệu mà cô ấy ghi chép lại trong những chuyến du hành trước đây.

### `lang_multi_text.db||MultiText||ItemInfo_71600003_BgDescription`
- HV cũ: Quyển sách nhạc mà Hạ Không tặng cho bạn, trên đó ghi lại những giai điệu mà cô ấy ghi chép lại trong những chuyến du hành trước đây. Thông qua khả năng cộng hưởng, Hạ Không có thể tái hiện lại những câu chuyện ẩn chứa đằng sau những giai điệu đó.
- HV V4: Quyển sách nhạc mà Ciaccona tặng cho bạn, trên đó ghi lại những giai điệu mà cô ấy ghi chép lại trong những chuyến du hành trước đây. Thông qua khả năng cộng hưởng, Ciaccona có thể tái hiện lại những câu chuyện ẩn chứa đằng sau những giai điệu đó.

### `lang_multi_text.db||MultiText||ItemInfo_72010043_AttributesDescription`
- HV cũ: Phi Bỉ: Hướng dẫn <color=#d4bf5f>Hiệp Tấu Đóng</color>
- HV V4: Phoebe: Hướng dẫn <color=#d4bf5f>Hiệp Tấu Đóng</color>

### `lang_multi_text.db||MultiText||ItemInfo_72010043_BgDescription`
- HV cũ: Phi Bỉ: Hướng dẫn <color=#d4bf5f>Hiệp Tấu Đóng</color>
- HV V4: Phoebe: Hướng dẫn <color=#d4bf5f>Hiệp Tấu Đóng</color>

### `lang_multi_text.db||MultiText||ItemInfo_72010043_Name`
- HV cũ: Phi Bỉ: Hướng dẫn <color=#d4bf5f>Hiệp Tấu Đóng</color>
- HV V4: Phoebe: Hướng dẫn <color=#d4bf5f>Hiệp Tấu Đóng</color>

### `lang_multi_text.db||MultiText||ItemInfo_72010043_ObtainedShowDescription`
- HV cũ: Phi Bỉ: Hướng dẫn <color=#d4bf5f>Hiệp Tấu Đóng</color>
- HV V4: Phoebe: Hướng dẫn <color=#d4bf5f>Hiệp Tấu Đóng</color>

### `lang_multi_text.db||MultiText||ItemInfo_80001000_BgDescription`
- HV cũ: Món ăn nhẹ do Lăng Dương làm cho những khán giả đến xem múa thú.\nThịt nạc và mỡ xen kẽ, kết hợp với rau quả để chống ngấy, là bạn đồng hành hoàn hảo khi xem kịch.
- HV V4: Món ăn nhẹ do Lingyang làm cho những khán giả đến xem múa thú.\nThịt nạc và mỡ xen kẽ, kết hợp với rau quả để chống ngấy, là bạn đồng hành hoàn hảo khi xem kịch.

### `lang_multi_text.db||MultiText||ItemInfo_80001007_BgDescription`
- HV cũ: Cho thịt quả cắt nhỏ ngâm vào nước đá, kèm theo mật hoa tươi. Giữa những viên đá va chạm nhau, phát ra âm thanh trong trẻo, tuyệt diệu.\nTrà trái cây do Xuân pha chế theo ý thích của mình, trong đó vị sữa đã được pha loãng đến mức cực kỳ nhạt, thịt quả thì chủ yếu là nho, và còn thêm một chút nước ép quả me rừng để điều hòa.\nThức uống trái cây ngọt ngào sảng khoái chảy qua đầu lưỡi, sau khi vị đắng nhàn nhạt phai đi, để lại một chút dư vị ngọt ngào kỳ diệu.
- HV V4: Cho thịt quả cắt nhỏ ngâm vào nước đá, kèm theo mật hoa tươi. Giữa những viên đá va chạm nhau, phát ra âm thanh trong trẻo, tuyệt diệu.\nTrà trái cây do Camellya pha chế theo ý thích của mình, trong đó vị sữa đã được pha loãng đến mức cực kỳ nhạt, thịt quả thì chủ yếu là nho, và còn thêm một chút nước ép quả me rừng để điều hòa.\nThức uống trái cây ngọt ngào sảng khoái chảy qua đầu lưỡi, sau khi vị đắng nhàn nhạt phai đi, để lại một chút dư vị ngọt ngào kỳ diệu.

### `lang_multi_text.db||MultiText||ItemInfo_80001011_BgDescription`
- HV cũ: Sợi bún tròn mượt mà thon dài, đẫm vị trong nước dùng cay nồng. Hành lá rắc lên những lát thịt dày dặn, một miếng ăn xuống, giữa mùa đông cũng có thể khiến người ta toát mồ hôi đầm đìa.\nỞ ngôi làng chất phác biệt lập với thế giới của Việt Châu, bún thịt cay là ký ức sâu sắc nhất của Đăng Đăng về hương vị quê nhà.\nCho dù hiện tại trên hành trình làm việc cho Lollo Logistics đã rời xa quê hương, nếm qua đủ loại món ngon, nhưng Đăng Đăng vẫn cảm thấy bát bún bốc khói nghi ngút trên bếp lửa ở nhà, chính là đại diện cho hạnh phúc.
- HV V4: Sợi bún tròn mượt mà thon dài, đẫm vị trong nước dùng cay nồng. Hành lá rắc lên những lát thịt dày dặn, một miếng ăn xuống, giữa mùa đông cũng có thể khiến người ta toát mồ hôi đầm đìa.\nỞ ngôi làng chất phác biệt lập với thế giới của Việt Châu, bún thịt cay là ký ức sâu sắc nhất của Lumi về hương vị quê nhà.\nCho dù hiện tại trên hành trình làm việc cho Lollo Logistics đã rời xa quê hương, nếm qua đủ loại món ngon, nhưng Lumi vẫn cảm thấy bát bún bốc khói nghi ngút trên bếp lửa ở nhà, chính là đại diện cho hạnh phúc.

### `lang_multi_text.db||MultiText||ItemInfo_80001018_BgDescription`
- HV cũ: Chanh thơm ngát hòa quyện vào nước lẩu đậm đà, chua chua ngọt ngọt chống ngấy, tươi ngon ngọt hậu, là món ăn sở trường của Thiên Tiếu. Mỗi dịp mùa đông, chui vào trong bàn sưởi Kotatsu xem hội ca nhạc, mùi thơm từ trong nồi tràn ngập khắp phòng, đó là khoảng thời gian thoải mái nhất trong ký ức của cô ấy.
- HV V4: Chanh thơm ngát hòa quyện vào nước lẩu đậm đà, chua chua ngọt ngọt chống ngấy, tươi ngon ngọt hậu, là món ăn sở trường của Chisa. Mỗi dịp mùa đông, chui vào trong bàn sưởi Kotatsu xem hội ca nhạc, mùi thơm từ trong nồi tràn ngập khắp phòng, đó là khoảng thời gian thoải mái nhất trong ký ức của cô ấy.

### `lang_multi_text.db||MultiText||ItemInfo_80001019_BgDescription`
- HV cũ: Gia vị và cá xắt sợi được xào sơ, đặt lên trên bát mì nước hầm đã được nêm nếm và ninh nhừ đến khi nước súp sền sệt, rưới dầu nóng lên phát ra tiếng "xèo" kèm theo mùi thơm và vị ngon mặn ngọt tươi roi rói, là món ngon quê nhà luôn xếp hạng nhất trong lòng Bặc Linh.
- HV V4: Gia vị và cá xắt sợi được xào sơ, đặt lên trên bát mì nước hầm đã được nêm nếm và ninh nhừ đến khi nước súp sền sệt, rưới dầu nóng lên phát ra tiếng "xèo" kèm theo mùi thơm và vị ngon mặn ngọt tươi roi rói, là món ngon quê nhà luôn xếp hạng nhất trong lòng Buling.

### `lang_multi_text.db||MultiText||ItemInfo_80001021_BgDescription`
- HV cũ: Sau rất nhiều lần thất bại, cuối cùng An Khả cũng làm ra được món ăn khiến bản thân hài lòng. Mỗi miếng thịt chiên giòn đều được nặn thành hình dáng chú cừu nhỏ, ăn xong nhất định sẽ có được một giấc mơ đẹp do chú cừu bồng bềnh.\nDù sao thì, món ăn này, bạn luôn có thể yên tâm thưởng thức.
- HV V4: Sau rất nhiều lần thất bại, cuối cùng Encore cũng làm ra được món ăn khiến bản thân hài lòng. Mỗi miếng thịt chiên giòn đều được nặn thành hình dáng chú cừu nhỏ, ăn xong nhất định sẽ có được một giấc mơ đẹp do chú cừu bồng bềnh.\nDù sao thì, món ăn này, bạn luôn có thể yên tâm thưởng thức.

### `lang_multi_text.db||MultiText||ItemInfo_80001029_BgDescription`
- HV cũ: Lẩu Sâm Tê đặc chế của Duy Lý Nại, trong đó thêm vào rất nhiều rau và thực vật do cô ấy dốc lòng bồi dưỡng, hương vị vô cùng tươi ngon. Nhân giống và chuẩn bị món ăn đều là quá trình dài đằng đẵng và tẻ nhạt, nhưng Duy Lý Nại luôn có thể kiên nhẫn, kiên nhẫn hơn nữa. Rốt cuộc thì, trong sự sinh trưởng của thực vật có thể nhìn thấy vòng đời của một sinh mệnh, và trong thời gian nấu nướng có thể mong chờ niềm vui thu hoạch.
- HV V4: Lẩu Sâm Tê đặc chế của Verina, trong đó thêm vào rất nhiều rau và thực vật do cô ấy dốc lòng bồi dưỡng, hương vị vô cùng tươi ngon. Nhân giống và chuẩn bị món ăn đều là quá trình dài đằng đẵng và tẻ nhạt, nhưng Verina luôn có thể kiên nhẫn, kiên nhẫn hơn nữa. Rốt cuộc thì, trong sự sinh trưởng của thực vật có thể nhìn thấy vòng đời của một sinh mệnh, và trong thời gian nấu nướng có thể mong chờ niềm vui thu hoạch.

### `lang_multi_text.db||MultiText||ItemInfo_80001039_BgDescription`
- HV cũ: Một loại súp đặc mà Thủ Ngạn Nhân yêu thích, không cần nguyên liệu đắt tiền đặc biệt nào, có thể làm bằng hải sản hiện có ở dọc bờ biển, bí quyết nằm ở sữa bò thơm đậm và thời gian hầm đủ lâu.\nRất ít người biết được rằng, món ăn này là do Thủ Ngạn Nhân làm ra để sao chép lại hơi ấm mà người trong ký ức mang lại. Cô ấy làm theo cách và các bước giống nhau, nhưng trong hết lần này đến lần khác thử nghiệm, đã tìm tòi ra hương vị của riêng mình. Súp đặc mới nấu có vị tươi ngọt của hải sản, dùng kèm với lát bánh mì đã nướng chín, một bát trôi xuống bụng, hơi nóng lan tỏa khắp cơ thể... Có lẽ, đây chính là cảm giác hạnh phúc giản đơn nhưng vững chãi mà người đó từng nói với cô ấy.
- HV V4: Một loại súp đặc mà Shorekeeper yêu thích, không cần nguyên liệu đắt tiền đặc biệt nào, có thể làm bằng hải sản hiện có ở dọc bờ biển, bí quyết nằm ở sữa bò thơm đậm và thời gian hầm đủ lâu.\nRất ít người biết được rằng, món ăn này là do Shorekeeper làm ra để sao chép lại hơi ấm mà người trong ký ức mang lại. Cô ấy làm theo cách và các bước giống nhau, nhưng trong hết lần này đến lần khác thử nghiệm, đã tìm tòi ra hương vị của riêng mình. Súp đặc mới nấu có vị tươi ngọt của hải sản, dùng kèm với lát bánh mì đã nướng chín, một bát trôi xuống bụng, hơi nóng lan tỏa khắp cơ thể... Có lẽ, đây chính là cảm giác hạnh phúc giản đơn nhưng vững chãi mà người đó từng nói với cô ấy.

### `lang_multi_text.db||MultiText||ItemInfo_80001040_BgDescription`
- HV cũ: Món ăn vặt Dụ Hồ cất giữ trong Đỉnh Băng ở trong hộp, bất kể lúc nào lấy ra đều mang theo từng tia mát lạnh.\nKhi đi chu du khắp nơi ở Solaris để tìm kiếm cổ vật, thường xuyên có những lúc không tìm được chỗ ăn ở, bánh nhỏ liền trở thành món ngon tuyệt đỉnh để cô lấp đầy bụng.\nBởi vì Dụ Hồ thích đồng thời ướp lạnh một ít trái cây trong Đỉnh Băng, vỏ bánh mang theo hơi thở ẩm ướt, thoang thoảng có mùi hương trái cây, bốn mùa đều khác nhau.
- HV V4: Món ăn vặt Youhu cất giữ trong Đỉnh Băng ở trong hộp, bất kể lúc nào lấy ra đều mang theo từng tia mát lạnh.\nKhi đi chu du khắp nơi ở Solaris để tìm kiếm cổ vật, thường xuyên có những lúc không tìm được chỗ ăn ở, bánh nhỏ liền trở thành món ngon tuyệt đỉnh để cô lấp đầy bụng.\nBởi vì Youhu thích đồng thời ướp lạnh một ít trái cây trong Đỉnh Băng, vỏ bánh mang theo hơi thở ẩm ướt, thoang thoảng có mùi hương trái cây, bốn mùa đều khác nhau.

### `lang_multi_text.db||MultiText||ItemInfo_80001043_BgDescription`
- HV cũ: Kem được làm từ máy làm kem mini do Lạc Khả Khả dùng đạo cụ cải tiến, hương vị đơn giản, rẻ mà lượng nhiều, thỏa mãn rất lớn nhu cầu tráng miệng của các thành viên trong đoàn kịch, nhận được sự săn đón nhiệt tình của mọi người, đồng thời cũng giảm bớt chi phí ăn kem, tiết kiệm chi tiêu cho đoàn kịch.
- HV V4: Kem được làm từ máy làm kem mini do Roccia dùng đạo cụ cải tiến, hương vị đơn giản, rẻ mà lượng nhiều, thỏa mãn rất lớn nhu cầu tráng miệng của các thành viên trong đoàn kịch, nhận được sự săn đón nhiệt tình của mọi người, đồng thời cũng giảm bớt chi phí ăn kem, tiết kiệm chi tiêu cho đoàn kịch.

### `lang_multi_text.db||MultiText||ItemInfo_80001044_BgDescription`
- HV cũ: Món mì do Tán Ny nướng phô mai, xúc xích và rau thơm v.v. lên trên bề mặt mì xào sốt thịt. Hương vị thơm ngon đậm đà.\nTheo lời Tán Ny, ban đầu cô ấy chỉ vô tình thêm nguyên liệu ăn liền có sẵn trong tay khi hâm nóng đồ ăn ngoài bị nguội lạnh vì bận rộn công việc, nhưng hương vị ngoài ý muốn lại khá ngon. Về sau trải qua không ngừng thử nghiệm, mới hình thành nên công thức cố định như hiện tại.
- HV V4: Món mì do Zani nướng phô mai, xúc xích và rau thơm v.v. lên trên bề mặt mì xào sốt thịt. Hương vị thơm ngon đậm đà.\nTheo lời Zani, ban đầu cô ấy chỉ vô tình thêm nguyên liệu ăn liền có sẵn trong tay khi hâm nóng đồ ăn ngoài bị nguội lạnh vì bận rộn công việc, nhưng hương vị ngoài ý muốn lại khá ngon. Về sau trải qua không ngừng thử nghiệm, mới hình thành nên công thức cố định như hiện tại.

### `lang_multi_text.db||MultiText||ItemInfo_80001045_BgDescription`
- HV cũ: Dùng một ly cà phê mang theo hương quýt đánh thức vị giác buổi sáng, là thói quen mà Kha Lai Tháp dần hình thành sau khi trở thành một thành viên của Montelli. Lớp cà phê Espresso nền hòa quyện với vị ngọt hậu của cam quýt, sự tươi mát này đã trung hòa đi vị đắng chát, đạt được sự cân bằng khiến người ta vui vẻ. Nó thích hợp cho những người sắp bắt đầu thời khắc căng thẳng, cũng thích hợp cho những người muốn tận hưởng sự thư giãn sau khi căng thẳng.
- HV V4: Dùng một ly cà phê mang theo hương quýt đánh thức vị giác buổi sáng, là thói quen mà Carlotta dần hình thành sau khi trở thành một thành viên của Montelli. Lớp cà phê Espresso nền hòa quyện với vị ngọt hậu của cam quýt, sự tươi mát này đã trung hòa đi vị đắng chát, đạt được sự cân bằng khiến người ta vui vẻ. Nó thích hợp cho những người sắp bắt đầu thời khắc căng thẳng, cũng thích hợp cho những người muốn tận hưởng sự thư giãn sau khi căng thẳng.

### `lang_multi_text.db||MultiText||ItemInfo_80001047_BgDescription`
- HV cũ: Salad Nguyệt Quế Cành Xanh do đích thân Tạp Đề Hi Á nấu, cho thêm nhiều Quả Cành Xanh, mỗi miếng cắn xuống đều đặc biệt giòn ngọt.\nBây giờ, với tư cách là một kỵ sĩ lang thang, cô ấy có rất nhiều thứ muốn học, có rất nhiều phong cảnh muốn đi xem.\n-Vậy thì hãy bắt đầu từ việc làm một đĩa salad chỉ thuộc về kỵ sĩ lang thang đi. Lần này, Quả Cành Xanh phải cho nhiều, thật nhiều, thật thật nhiều vào!
- HV V4: Salad Nguyệt Quế Cành Xanh do đích thân Cartethyia nấu, cho thêm nhiều Quả Cành Xanh, mỗi miếng cắn xuống đều đặc biệt giòn ngọt.\nBây giờ, với tư cách là một kỵ sĩ lang thang, cô ấy có rất nhiều thứ muốn học, có rất nhiều phong cảnh muốn đi xem.\n-Vậy thì hãy bắt đầu từ việc làm một đĩa salad chỉ thuộc về kỵ sĩ lang thang đi. Lần này, Quả Cành Xanh phải cho nhiều, thật nhiều, thật thật nhiều vào!

### `lang_multi_text.db||MultiText||ItemInfo_80001049_BgDescription`
- HV cũ: Bánh Panini do chính tay Khảm Đặc Lôi Lạp làm.\nBánh mì nướng giòn rụm vừa phải, nhồi đầy nhân hải sản được nêm nếm tỉ mỉ-\nMột miếng cắn xuống, hương vị dồi dào trôi theo cổ họng vào dạ dày, cảm giác thỏa mãn lấp đầy ổ bụng.\nKhác biệt với sự huyền diệu của bí dược, là một hương vị đơn giản ấm áp.
- HV V4: Bánh Panini do chính tay Cantarella làm.\nBánh mì nướng giòn rụm vừa phải, nhồi đầy nhân hải sản được nêm nếm tỉ mỉ-\nMột miếng cắn xuống, hương vị dồi dào trôi theo cổ họng vào dạ dày, cảm giác thỏa mãn lấp đầy ổ bụng.\nKhác biệt với sự huyền diệu của bí dược, là một hương vị đơn giản ấm áp.

### `lang_multi_text.db||MultiText||ItemInfo_80001051_BgDescription`
- HV cũ: Nhà thơ hát rong du ngoạn bốn phương, đồ ăn trên đường đi chú trọng đến sự cân bằng giữa thơm ngon và tiện lợi.\nThế là Hạ Không linh cơ chợt lóe, lấy ra bánh mì mang theo bên mình...\nKhi lửa trại bốc lên, hương thơm của mì sốt thịt bay đến trước mũi cô theo khe hở của bánh mì, cô bôi loại nước sốt gia vị cuối cùng lên trên bánh mì.\nNhưng xin chú ý, trong dân gian có một quy tắc bất thành văn-nghiêm cấm phối hợp lung tung đối với mì xào sốt thịt của Ragunna, cải biên công thức nấu ăn. Cô ấy ăn bánh mì mì xào nóng hổi trên tay, suy nghĩ "Nếu có một ngày mình bị lưu đày, thì có lẽ đây cũng là một trong những tội danh?"
- HV V4: Nhà thơ hát rong du ngoạn bốn phương, đồ ăn trên đường đi chú trọng đến sự cân bằng giữa thơm ngon và tiện lợi.\nThế là Ciaccona linh cơ chợt lóe, lấy ra bánh mì mang theo bên mình...\nKhi lửa trại bốc lên, hương thơm của mì sốt thịt bay đến trước mũi cô theo khe hở của bánh mì, cô bôi loại nước sốt gia vị cuối cùng lên trên bánh mì.\nNhưng xin chú ý, trong dân gian có một quy tắc bất thành văn-nghiêm cấm phối hợp lung tung đối với mì xào sốt thịt của Ragunna, cải biên công thức nấu ăn. Cô ấy ăn bánh mì mì xào nóng hổi trên tay, suy nghĩ "Nếu có một ngày mình bị lưu đày, thì có lẽ đây cũng là một trong những tội danh?"

### `lang_multi_text.db||MultiText||ItemInfo_80001052_BgDescription`
- HV cũ: Rượu của đoàn kịch do đích thân Bố Lan Đặc ủ, hương vị thanh ngọt, dư vị vô tận.\nAnh ấy đối xử nghiêm túc với mỗi chai rượu mình ủ ra, giống như mỗi một buổi diễn mà anh dốc hết toàn bộ tâm huyết.\nAnh trịnh trọng viết tên mình lên thân chai, dâng lên lời chúc phúc cho mỗi một người nhận được rượu.\nSinh mệnh nên ca hát, sống là phải tự do.
- HV V4: Rượu của đoàn kịch do đích thân Brant ủ, hương vị thanh ngọt, dư vị vô tận.\nAnh ấy đối xử nghiêm túc với mỗi chai rượu mình ủ ra, giống như mỗi một buổi diễn mà anh dốc hết toàn bộ tâm huyết.\nAnh trịnh trọng viết tên mình lên thân chai, dâng lên lời chúc phúc cho mỗi một người nhận được rượu.\nSinh mệnh nên ca hát, sống là phải tự do.

### `lang_multi_text.db||MultiText||ItemInfo_80001057_BgDescription`
- HV cũ: Sự chua chát tột cùng cùng với mứt trái cây đặc quánh đỏ rực chảy xuống, từ từ thấm vào mỗi một chỗ trống giữa bánh mật, cho đến khi hoàn toàn che lấp đi hương vị thơm ngọt vốn có của nó. Ngoại trừ Phất Lạc Lạc, không ai có thể chấp nhận được sự kích thích vị giác kỳ quặc này, cũng không ai biết loại trái cây nhỏ nhắn chua cứng này rốt cuộc đến từ đâu.
- HV V4: Sự chua chát tột cùng cùng với mứt trái cây đặc quánh đỏ rực chảy xuống, từ từ thấm vào mỗi một chỗ trống giữa bánh mật, cho đến khi hoàn toàn che lấp đi hương vị thơm ngọt vốn có của nó. Ngoại trừ Phrolova, không ai có thể chấp nhận được sự kích thích vị giác kỳ quặc này, cũng không ai biết loại trái cây nhỏ nhắn chua cứng này rốt cuộc đến từ đâu.

### `lang_multi_text.db||MultiText||ItemInfo_80001061_BgDescription`
- HV cũ: Thức uống năng lượng do ngôi sao giác đấu tuyển thủ Lộ Mạt làm người đại diện, vẫn đang được bán rất chạy ở Septimont.\nSảng khoái, độ ngọt thấp, nhiều loại hương vị cho bạn tùy ý lựa chọn, ướp lạnh rồi uống là ngon nhất.\nĐấu trường giác đấu là một phần quan trọng nhất trong cuộc đời cô ấy, trong vô số khoảnh khắc tương lai, Lộ Mạt vẫn sẽ uống một ngụm "Uống Trọn Trái Tim" trong giờ nghỉ ngơi giữa các trận đấu.\nTừ đó nhớ lại khoảnh khắc vui cười sát cánh chiến đấu cùng cộng sự trong trận chung kết.
- HV V4: Thức uống năng lượng do ngôi sao giác đấu tuyển thủ Lupa làm người đại diện, vẫn đang được bán rất chạy ở Septimont.\nSảng khoái, độ ngọt thấp, nhiều loại hương vị cho bạn tùy ý lựa chọn, ướp lạnh rồi uống là ngon nhất.\nĐấu trường giác đấu là một phần quan trọng nhất trong cuộc đời cô ấy, trong vô số khoảnh khắc tương lai, Lupa vẫn sẽ uống một ngụm "Uống Trọn Trái Tim" trong giờ nghỉ ngơi giữa các trận đấu.\nTừ đó nhớ lại khoảnh khắc vui cười sát cánh chiến đấu cùng cộng sự trong trận chung kết.

### `lang_multi_text.db||MultiText||ItemInfo_80001066_BgDescription`
- HV cũ: Loại bánh mì truyền thống không có gì đặc biệt của Septimont, ngay cả ở thị trấn Fabianum xa xôi, đây cũng là món ăn thường ngày có thể thấy ở bất cứ đâu. Nhưng dường như để phân biệt với những thứ tầm thường khác, các thợ làm bánh địa phương ở Fabianum luôn có thói quen rắc một nhúm lá gia vị nghiền nát lên lớp vỏ bánh giòn rụm, tiện tay trang trọng dùng dao nhỏ khắc chữ "Mỹ Vị" lên vỏ bánh, như thể lời tuyên bố giản dị này, ít nhiều cũng mang lại cho chiếc bánh chút thể diện khác biệt.\nCó ngon không? Cô bé Áo Cổ Tư Tháp chưa bao giờ nghĩ vậy. Đó chỉ là món đồ lót dạ dễ dàng lấy được khi về nhà sau một ngày chơi đùa mệt lử, là "chú thích" nhạt nhẽo trên bàn ăn mỗi ngày của mẹ. Nó khô cứng, mộc mạc, không cần ngợi khen, giống như nước, như ánh nắng, bình thường đến mức gần như chẳng ai chú ý. Cho đến nhiều năm sau, trước bếp lò ở ngôi nhà tại thành phố Septimont, Áo Cổ Tư Tháp cố gắng tìm lại hương vị lưu giữ sâu trong ký ức, khi mùi thơm quen thuộc và vị ngọt dịu một lần nữa hiện lên nơi đầu lưỡi, cô mới thực sự hiểu được ý nghĩa của "Mỹ Vị".\nCó lẽ, chưa từng có khoảnh khắc nào cô thực sự nói lời tạm biệt với quê hương.
- HV V4: Loại bánh mì truyền thống không có gì đặc biệt của Septimont, ngay cả ở thị trấn Fabianum xa xôi, đây cũng là món ăn thường ngày có thể thấy ở bất cứ đâu. Nhưng dường như để phân biệt với những thứ tầm thường khác, các thợ làm bánh địa phương ở Fabianum luôn có thói quen rắc một nhúm lá gia vị nghiền nát lên lớp vỏ bánh giòn rụm, tiện tay trang trọng dùng dao nhỏ khắc chữ "Mỹ Vị" lên vỏ bánh, như thể lời tuyên bố giản dị này, ít nhiều cũng mang lại cho chiếc bánh chút thể diện khác biệt.\nCó ngon không? Cô bé Augusta chưa bao giờ nghĩ vậy. Đó chỉ là món đồ lót dạ dễ dàng lấy được khi về nhà sau một ngày chơi đùa mệt lử, là "chú thích" nhạt nhẽo trên bàn ăn mỗi ngày của mẹ. Nó khô cứng, mộc mạc, không cần ngợi khen, giống như nước, như ánh nắng, bình thường đến mức gần như chẳng ai chú ý. Cho đến nhiều năm sau, trước bếp lò ở ngôi nhà tại thành phố Septimont, Augusta cố gắng tìm lại hương vị lưu giữ sâu trong ký ức, khi mùi thơm quen thuộc và vị ngọt dịu một lần nữa hiện lên nơi đầu lưỡi, cô mới thực sự hiểu được ý nghĩa của "Mỹ Vị".\nCó lẽ, chưa từng có khoảnh khắc nào cô thực sự nói lời tạm biệt với quê hương.

### `lang_multi_text.db||MultiText||ItemInfo_80001074_BgDescription`
- HV cũ: Viên kẹo Fruit Crackle do Tây Cách Lị Tạp làm theo sở thích của mình, kẹo hình ngôi sao phủ một lớp đường sương trắng muốt, ăn vào mát lạnh và ngọt ngào.\nKhi làm kẹo, cô đã không làm theo thứ tự của công thức mà thêm vào một chút "cảm hứng".\nMay thay, may thay, cô đã thu được một kết quả khá tốt.\nĐôi khi, thêm một chút cảm hứng cũng không tồi.
- HV V4: Viên kẹo Fruit Crackle do Sigrika làm theo sở thích của mình, kẹo hình ngôi sao phủ một lớp đường sương trắng muốt, ăn vào mát lạnh và ngọt ngào.\nKhi làm kẹo, cô đã không làm theo thứ tự của công thức mà thêm vào một chút "cảm hứng".\nMay thay, may thay, cô đã thu được một kết quả khá tốt.\nĐôi khi, thêm một chút cảm hứng cũng không tồi.

### `lang_multi_text.db||MultiText||ItemInfo_80001081_BgDescription`
- HV cũ: Mì Ly Diệu Kỳ Nửa Đêm phiên bản đặc biệt của Lâm Nại, được cải tiến dựa trên hương vị mà cô yêu thích nhất, hơi nước bốc lên khi nấu chín không hiểu sao lại có màu neon rực rỡ. Nghe nói vào một đêm khuya, có một sinh viên đã mở ly mì này sau một đêm thức trắng làm thí nghiệm, một góc phòng thí nghiệm u ám thong thả bốc lên làn sương mù đầy màu sắc, khiến người đó lầm tưởng mình bị ảo giác...
- HV V4: Mì Ly Diệu Kỳ Nửa Đêm phiên bản đặc biệt của Lynae, được cải tiến dựa trên hương vị mà cô yêu thích nhất, hơi nước bốc lên khi nấu chín không hiểu sao lại có màu neon rực rỡ. Nghe nói vào một đêm khuya, có một sinh viên đã mở ly mì này sau một đêm thức trắng làm thí nghiệm, một góc phòng thí nghiệm u ám thong thả bốc lên làn sương mù đầy màu sắc, khiến người đó lầm tưởng mình bị ảo giác...

### `lang_multi_text.db||MultiText||ItemInfo_80004002_AttributesDescription`
- HV cũ: Trang sức kỷ niệm sinh nhật dành riêng cho Lữ Khách năm 2025. Bừng tỉnh lại, chiếc vương miện đã nằm ngoan ngoãn trong túi đồ.
- HV V4: Trang sức kỷ niệm sinh nhật dành riêng cho Rover năm 2025. Bừng tỉnh lại, chiếc vương miện đã nằm ngoan ngoãn trong túi đồ.

### `lang_multi_text.db||MultiText||ItemInfo_80004005_AttributesDescription`
- HV cũ: Trang sức kỷ niệm sinh nhật dành riêng cho Lữ Khách năm 2026. Bừng tỉnh lại, vòng hào quang đan xen từ các vì sao và dây đàn đã được cất giữ trong túi đồ.
- HV V4: Trang sức kỷ niệm sinh nhật dành riêng cho Rover năm 2026. Bừng tỉnh lại, vòng hào quang đan xen từ các vì sao và dây đàn đã được cất giữ trong túi đồ.

### `lang_multi_text.db||MultiText||ItemInfo_80004005_ObtainedShowDescription`
- HV cũ: Trang sức kỷ niệm sinh nhật dành riêng cho Lữ Khách năm 2026. Bừng tỉnh lại, vòng hào quang đan xen từ các vì sao và dây đàn đã được cất giữ trong túi đồ.
- HV V4: Trang sức kỷ niệm sinh nhật dành riêng cho Rover năm 2026. Bừng tỉnh lại, vòng hào quang đan xen từ các vì sao và dây đàn đã được cất giữ trong túi đồ.

### `lang_multi_text.db||MultiText||ItemInfo_80004006_BgDescription`
- HV cũ: Giai điệu nhẹ nhàng và tươi sáng, tựa như làn gió lướt qua bạn vào buổi chiều tà, nó cất giấu từng đoạn ký ức đồng hành, cũng cất giấu những biết ơn và quyến luyến không nói nên lời. Khi những nốt nhạc vang lên, những tháng ngày hạnh phúc ấy cũng trào dâng trong tim, đây là bài hát viết cho bạn, cũng là khoảng thời gian đọng lại vì bạn. Chúc mừng sinh nhật, Lữ Khách.
- HV V4: Giai điệu nhẹ nhàng và tươi sáng, tựa như làn gió lướt qua bạn vào buổi chiều tà, nó cất giấu từng đoạn ký ức đồng hành, cũng cất giấu những biết ơn và quyến luyến không nói nên lời. Khi những nốt nhạc vang lên, những tháng ngày hạnh phúc ấy cũng trào dâng trong tim, đây là bài hát viết cho bạn, cũng là khoảng thời gian đọng lại vì bạn. Chúc mừng sinh nhật, Rover.

### `lang_multi_text.db||MultiText||ItemInfo_80030000_BgDescription`
- HV cũ: Minh chứng tươi đẹp cho tình bạn vững chắc giữa Lữ Khách và những người bạn đồng hành, khi tăng độ thân mật, biết đâu sẽ có chuyện bất ngờ xảy ra?
- HV V4: Minh chứng tươi đẹp cho tình bạn vững chắc giữa Rover và những người bạn đồng hành, khi tăng độ thân mật, biết đâu sẽ có chuyện bất ngờ xảy ra?

### `lang_multi_text.db||MultiText||ItemInfo_80030001_BgDescription`
- HV cũ: Minh chứng tươi đẹp cho tình bạn vững chắc giữa Lữ Khách và những người bạn đồng hành, khi tăng độ thân mật, biết đâu sẽ có chuyện bất ngờ xảy ra?
- HV V4: Minh chứng tươi đẹp cho tình bạn vững chắc giữa Rover và những người bạn đồng hành, khi tăng độ thân mật, biết đâu sẽ có chuyện bất ngờ xảy ra?

### `lang_multi_text.db||MultiText||ItemInfo_80030002_BgDescription`
- HV cũ: Minh chứng tươi đẹp cho tình bạn vững chắc giữa Lữ Khách và những người bạn đồng hành, khi tăng độ thân mật, biết đâu sẽ có chuyện bất ngờ xảy ra?
- HV V4: Minh chứng tươi đẹp cho tình bạn vững chắc giữa Rover và những người bạn đồng hành, khi tăng độ thân mật, biết đâu sẽ có chuyện bất ngờ xảy ra?

### `lang_multi_text.db||MultiText||ItemInfo_80110430_ObtainedShowDescription`
- HV cũ: Nhạc nền khi giao tranh với Áo Cổ Tư Tháp, mở khóa sau khi hoàn thành nhiệm vụ Minh Triều [Đốt Cháy Ta Dưới Nắng Gắt].
- HV V4: Nhạc nền khi giao tranh với Augusta, mở khóa sau khi hoàn thành nhiệm vụ Minh Triều [Đốt Cháy Ta Dưới Nắng Gắt].

### `lang_multi_text.db||MultiText||ItemInfo_80110431_ObtainedShowDescription`
- HV cũ: Nhạc nền khi cùng Áo Cổ Tư Tháp đưa tiễn "Đốt Cháy Ta Dưới Nắng Gắt", mở khóa sau khi hoàn thành nhiệm vụ Minh Triều [Thiêu Đốt Ta Bằng Ánh Mặt Trời Chói Lòa].
- HV V4: Nhạc nền khi cùng Augusta đưa tiễn "Đốt Cháy Ta Dưới Nắng Gắt", mở khóa sau khi hoàn thành nhiệm vụ Minh Triều [Thiêu Đốt Ta Bằng Ánh Mặt Trời Chói Lòa].

### `lang_multi_text.db||MultiText||ItemInfo_80110439_ObtainedShowDescription`
- HV cũ: Nhạc nền khi từ biệt Qiuyuan ở Ragunna, mở khóa sau khi hoàn thành nhiệm vụ Minh Triều [Một Lữ Khách Lạc Lõng Giữa Vùng Đất Xa Lạ].
- HV V4: Nhạc nền khi từ biệt Qiuyuan ở Ragunna, mở khóa sau khi hoàn thành nhiệm vụ Minh Triều [Một Rover Lạc Lõng Giữa Vùng Đất Xa Lạ].

### `lang_multi_text.db||MultiText||ItemInfo_80110455_AttributesDescription`
- VI cũ: Nhạc nền khi cùng Linnae Đánh bại Sâu Hư Không.
- VI V4: Nhạc nền khi cùng Linnae Đánh bại Trùng Hư Đản.
- HV cũ: Nhạc nền khi cùng Linnae Đánh bại Sâu Hư Không.
- HV V4: Nhạc nền khi cùng Linnae Đánh bại Trùng Hư Đản.

### `lang_multi_text.db||MultiText||ItemInfo_80110455_ObtainedShowDescription`
- VI cũ: Nhạc nền khi cùng Linnae Đánh bại Sâu Hư Không, mở khóa sau khi hoàn thành nhiệm vụ Minh Triều [Ngọn Đuốc Dưới Lớp Băng].
- VI V4: Nhạc nền khi cùng Linnae Đánh bại Trùng Hư Đản, mở khóa sau khi hoàn thành nhiệm vụ Minh Triều [Ngọn Đuốc Dưới Lớp Băng].
- HV cũ: Nhạc nền khi cùng Linnae Đánh bại Sâu Hư Không, mở khóa sau khi hoàn thành nhiệm vụ Minh Triều [Ngọn Đuốc Dưới Lớp Băng].
- HV V4: Nhạc nền khi cùng Linnae Đánh bại Trùng Hư Đản, mở khóa sau khi hoàn thành nhiệm vụ Minh Triều [Ngọn Đuốc Dưới Lớp Băng].

### `lang_multi_text.db||MultiText||ItemInfo_80110524_AttributesDescription`
- HV cũ: Nhạc nền khi cùng Tây Cách Lị Tạp chứng kiến Cầu Cực Quang xuất hiện.
- HV V4: Nhạc nền khi cùng Sigrika chứng kiến Cầu Cực Quang xuất hiện.

### `lang_multi_text.db||MultiText||ItemInfo_80110524_ObtainedShowDescription`
- HV cũ: Nhạc nền khi cùng Tây Cách Lị Tạp chứng kiến Cầu Cực Quang xuất hiện, mở khóa sau khi hoàn thành Nhiệm Vụ Nguy Hiểm "Ngày Bay Hoàn Hảo".
- HV V4: Nhạc nền khi cùng Sigrika chứng kiến Cầu Cực Quang xuất hiện, mở khóa sau khi hoàn thành Nhiệm Vụ Nguy Hiểm "Ngày Bay Hoàn Hảo".

### `lang_multi_text.db||MultiText||ItemInfo_80500002_AttributesDescription`
- HV cũ: Bonsai hoa anh đào do Thiên Tiếu làm, cành hoa anh đào được lấy từ Khu Phố Sakura mà hai người từng cùng nhau dạo bước.
- HV V4: Bonsai hoa anh đào do Chisa làm, cành hoa anh đào được lấy từ Khu Phố Sakura mà hai người từng cùng nhau dạo bước.

### `lang_multi_text.db||MultiText||ItemInfo_80500002_ObtainedShowDescription`
- HV cũ: Bonsai hoa anh đào do Thiên Tiếu làm
- HV V4: Bonsai hoa anh đào do Chisa làm

### `lang_multi_text.db||MultiText||ItemInfo_80500004_AttributesDescription`
- HV cũ: Thiệp chúc mừng nổi do Thiên Tiếu tự tay làm trong thời gian nghỉ ngơi ở Bờ Biển Đen, mang theo tâm ý đặc biệt của cô ấy, có thể phóng to để xem.
- HV V4: Thiệp chúc mừng nổi do Chisa tự tay làm trong thời gian nghỉ ngơi ở Bờ Biển Đen, mang theo tâm ý đặc biệt của cô ấy, có thể phóng to để xem.

### `lang_multi_text.db||MultiText||ItemInfo_80500004_BgDescription`
- HV cũ: Trong thành phố dưới bầu trời trong xanh, có bóng dáng của Thiên Tiếu thời trung học.\nNhững nỗi đau và điều tốt đẹp từng trải qua ở quê nhà đều là quá khứ mà thiếu nữ ghi nhớ, tất cả những điều này đã tạo nên "Kuchiba Thiên Tiếu" của hiện tại. Bây giờ, cô ấy mang ký ức quý giá về quê nhà, tất cả những gì cô ấy từng có và trân trọng, chia sẻ một cách trang trọng với mình.
- HV V4: Trong thành phố dưới bầu trời trong xanh, có bóng dáng của Chisa thời trung học.\nNhững nỗi đau và điều tốt đẹp từng trải qua ở quê nhà đều là quá khứ mà thiếu nữ ghi nhớ, tất cả những điều này đã tạo nên "Kuchiba Chisa" của hiện tại. Bây giờ, cô ấy mang ký ức quý giá về quê nhà, tất cả những gì cô ấy từng có và trân trọng, chia sẻ một cách trang trọng với mình.

### `lang_multi_text.db||MultiText||ItemInfo_80500004_ObtainedShowDescription`
- HV cũ: Thiệp chúc mừng nổi do Thiên Tiếu tự tay làm, mang theo tâm ý đặc biệt.
- HV V4: Thiệp chúc mừng nổi do Chisa tự tay làm, mang theo tâm ý đặc biệt.

### `lang_multi_text.db||MultiText||ItemInfo_80500005_BgDescription`
- HV cũ: Thẻ học sinh mà Thiên Tiếu vô tình lấy được khi bị cuốn vào bão từ thực chất. Bề mặt thẻ học sinh đầy rẫy dấu vết bị xói mòn, phần ảnh đại diện thấp thoáng lộ ra khuôn mặt của mình.\nHơn hai mươi năm trước, mình từng để lại dấu chân ở Học viện Startorch.
- HV V4: Thẻ học sinh mà Chisa vô tình lấy được khi bị cuốn vào bão từ thực chất. Bề mặt thẻ học sinh đầy rẫy dấu vết bị xói mòn, phần ảnh đại diện thấp thoáng lộ ra khuôn mặt của mình.\nHơn hai mươi năm trước, mình từng để lại dấu chân ở Học viện Startorch.

### `lang_multi_text.db||MultiText||ItemInfo_83100014_PassiveBuffDescription`
- HV cũ: <size=40><color=Title>Nạp năng lực của Thủ Ngạn Nhân cho Dango</color></size>\nKhi sử dụng Kỹ Năng Cốt Lõi, tạo ra "Vùng Tinh Tú", khi thi triển xóa bỏ trạng thái bất thường của tất cả nhân vật trong phạm vi. Tất cả nhân vật trong "Vùng Tinh Tú" mỗi giây hồi phục HP dựa trên {1} HP tối đa của người thi triển, và nhận {2} sát thương bạo kích, duy trì {3} giây. Hồi chiêu kỹ năng: {9} giây\n<size=10> </size>\n<size=40><color=Title>Mô đun có hiệu lực</color></size>\n[Thời Gian Duy Trì] [Hồi Chiêu Kỹ Năng]\n<size=10> </size>\n<size=40><color=Title>Hiệu quả nâng cấp</color></size>\nCấp Thời Gian Duy Trì {4}: Thời gian duy trì "Vùng Tinh Tú" tăng {8} giây\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nShorekeeper khá thích Cơm San Hô của An Khả, sẽ khiến cô ấy nhớ đến biển cả, thế là An Khả được cổ vũ bắt đầu làm Cơm San Hô ngày càng mặn... Tóm lại là, bây giờ thì, không còn quá mong đợi để ăn nữa.
- HV V4: <size=40><color=Title>Nạp năng lực của Shorekeeper cho Dango</color></size>\nKhi sử dụng Kỹ Năng Cốt Lõi, tạo ra "Vùng Tinh Tú", khi thi triển xóa bỏ trạng thái bất thường của tất cả nhân vật trong phạm vi. Tất cả nhân vật trong "Vùng Tinh Tú" mỗi giây hồi phục HP dựa trên {1} HP tối đa của người thi triển, và nhận {2} sát thương bạo kích, duy trì {3} giây. Hồi chiêu kỹ năng: {9} giây\n<size=10> </size>\n<size=40><color=Title>Mô đun có hiệu lực</color></size>\n[Thời Gian Duy Trì] [Hồi Chiêu Kỹ Năng]\n<size=10> </size>\n<size=40><color=Title>Hiệu quả nâng cấp</color></size>\nCấp Thời Gian Duy Trì {4}: Thời gian duy trì "Vùng Tinh Tú" tăng {8} giây\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nShorekeeper khá thích Cơm San Hô của Encore, sẽ khiến cô ấy nhớ đến biển cả, thế là Encore được cổ vũ bắt đầu làm Cơm San Hô ngày càng mặn... Tóm lại là, bây giờ thì, không còn quá mong đợi để ăn nữa.

### `lang_multi_text.db||MultiText||ItemInfo_83100015_PassiveBuffDescription`
- HV cũ: <size=40><color=Title>Nạp năng lực của Xuân cho Dango</color></size>\nKhi sử dụng Kỹ Năng Cốt Lõi, dẫn hướng "Dây Leo Múa" tấn công mục tiêu trong phạm vi lớn, mỗi giây gây <color=Dark>sát thương Hủy Diệt</color> bằng {1} cho xung quanh, duy trì {2} giây. Hồi chiêu kỹ năng: {3} giây\n<size=10> </size>\n<size=40><color=Title>Mô đun có hiệu lực</color></size>\n[Tần Suất Tấn Công] [Phạm Vi Kỹ Năng]\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nCamellya khá thích tấn công trong tư thế treo ngược, theo lời chính chủ nói là sẽ có cảm giác bồng bềnh, rất vui sướng. Sau này trong một nhiệm vụ nào đó với An Khả, Xuân phát hiện ra tàu lượn siêu tốc cũng mang lại cảm giác này cho người ta, nên bây giờ cũng thích tàu lượn siêu tốc.
- HV V4: <size=40><color=Title>Nạp năng lực của Camellya cho Dango</color></size>\nKhi sử dụng Kỹ Năng Cốt Lõi, dẫn hướng "Dây Leo Múa" tấn công mục tiêu trong phạm vi lớn, mỗi giây gây <color=Dark>sát thương Hủy Diệt</color> bằng {1} cho xung quanh, duy trì {2} giây. Hồi chiêu kỹ năng: {3} giây\n<size=10> </size>\n<size=40><color=Title>Mô đun có hiệu lực</color></size>\n[Tần Suất Tấn Công] [Phạm Vi Kỹ Năng]\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nCamellya khá thích tấn công trong tư thế treo ngược, theo lời chính chủ nói là sẽ có cảm giác bồng bềnh, rất vui sướng. Sau này trong một nhiệm vụ nào đó với Encore, Camellya phát hiện ra tàu lượn siêu tốc cũng mang lại cảm giác này cho người ta, nên bây giờ cũng thích tàu lượn siêu tốc.

### `lang_multi_text.db||MultiText||ItemInfo_83100016_PassiveBuffDescription`
- HV cũ: <size=40><color=Title>Nạp năng lực của Kha Lai Tháp cho Dango</color></size>\nKhi sử dụng Kỹ Năng Cốt Lõi, triệu hồi "Súng Lục" bắn mục tiêu gần đó, tổng cộng gây <color=Ice>sát thương Ngưng Băng</color> bằng {3}. Hồi chiêu kỹ năng: {8} giây\n<size=10> </size>\n<size=40><color=Title>Mô đun có hiệu lực</color></size>\n[Số Lượng Đạn] [Hồi Chiêu Kỹ Năng]\n<size=10> </size>\n<size=40><color=Title>Hiệu quả nâng cấp</color></size>\nCấp Số Lượng Đạn {4}: Tạo thêm {7} "Súng Lục"\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nCông thức bí mật quan trọng nhất cho cà phê của Kha Lai Tháp thực ra là quýt, chủng loại, nơi sản xuất, độ chín cô ấy đều phải chu toàn ... nghe nói gần đây cô ấy thích những lát quýt có vị hơi chua chát hơn.
- HV V4: <size=40><color=Title>Nạp năng lực của Carlotta cho Dango</color></size>\nKhi sử dụng Kỹ Năng Cốt Lõi, triệu hồi "Súng Lục" bắn mục tiêu gần đó, tổng cộng gây <color=Ice>sát thương Ngưng Băng</color> bằng {3}. Hồi chiêu kỹ năng: {8} giây\n<size=10> </size>\n<size=40><color=Title>Mô đun có hiệu lực</color></size>\n[Số Lượng Đạn] [Hồi Chiêu Kỹ Năng]\n<size=10> </size>\n<size=40><color=Title>Hiệu quả nâng cấp</color></size>\nCấp Số Lượng Đạn {4}: Tạo thêm {7} "Súng Lục"\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nCông thức bí mật quan trọng nhất cho cà phê của Carlotta thực ra là quýt, chủng loại, nơi sản xuất, độ chín cô ấy đều phải chu toàn ... nghe nói gần đây cô ấy thích những lát quýt có vị hơi chua chát hơn.

### `lang_multi_text.db||MultiText||ItemInfo_83100017_PassiveBuffDescription`
- HV cũ: <size=40><color=Title>Nạp năng lực của Lạc Khả Khả cho Dango</color></size>\nKhi sử dụng Kỹ Năng Cốt Lõi, tạo ra "Bão Táp Tư Duy", cuốn kẻ địch gần đó vào trong, mỗi giây gây <color=Dark>sát thương Hủy Diệt</color> bằng {1}, duy trì {2} giây. Hồi chiêu kỹ năng: {8} giây\n<size=10> </size>\n<size=40><color=Title>Mô đun có hiệu lực</color></size>\n[Tần Suất Tấn Công] [Thời Gian Duy Trì]\n<size=10> </size>\n<size=40><color=Title>Hiệu quả nâng cấp</color></size>\nCấp Thời Gian Duy Trì {3}: Thời gian duy trì "Bão Táp Tư Duy" tăng {7} giây\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nRoccia dưới vẻ ngoài trầm tĩnh rốt cuộc vẫn là một đứa trẻ, rất sợ bóng tối, rất thích ăn kẹo. Trong bóng tối sẽ ăn kẹo thật mạnh.
- HV V4: <size=40><color=Title>Nạp năng lực của Roccia cho Dango</color></size>\nKhi sử dụng Kỹ Năng Cốt Lõi, tạo ra "Bão Táp Tư Duy", cuốn kẻ địch gần đó vào trong, mỗi giây gây <color=Dark>sát thương Hủy Diệt</color> bằng {1}, duy trì {2} giây. Hồi chiêu kỹ năng: {8} giây\n<size=10> </size>\n<size=40><color=Title>Mô đun có hiệu lực</color></size>\n[Tần Suất Tấn Công] [Thời Gian Duy Trì]\n<size=10> </size>\n<size=40><color=Title>Hiệu quả nâng cấp</color></size>\nCấp Thời Gian Duy Trì {3}: Thời gian duy trì "Bão Táp Tư Duy" tăng {7} giây\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nRoccia dưới vẻ ngoài trầm tĩnh rốt cuộc vẫn là một đứa trẻ, rất sợ bóng tối, rất thích ăn kẹo. Trong bóng tối sẽ ăn kẹo thật mạnh.

### `lang_multi_text.db||MultiText||ItemInfo_83100018_PassiveBuffDescription`
- HV cũ: <size=40><color=Title>Nạp năng lực của Bố Lan Đặc cho Dango</color></size>\nKhi sử dụng Kỹ Năng Cốt Lõi, triệu hồi mỏ neo tiến hành tấn công, gây <color=Fire>sát thương Hỏa Liệt</color> bằng {1}. Mỏ neo sẽ tạo ra một số "Quýt Cam" khi đập xuống mặt đất. Nhân vật nhặt "Quýt Cam" tăng {7} tấn công, và hồi phục HP dựa trên {8} HP tối đa của người thi triển, duy trì {2} giây, có thể cộng dồn {4} tầng. Hồi chiêu kỹ năng: {6} giây\n<size=10> </size>\n<size=40><color=Title>Mô đun có hiệu lực</color></size>\n[Số Lượng Đạn] [Hồi Chiêu Kỹ Năng]\n<size=10> </size>\n<size=40><color=Title>Hiệu quả nâng cấp</color></size>\nCấp Số Lượng Đạn {3}: Số lượng "Quýt" tăng {5}\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nBrant thích ăn đồ ngọt, vì đồ ngọt là ngọt.
- HV V4: <size=40><color=Title>Nạp năng lực của Brant cho Dango</color></size>\nKhi sử dụng Kỹ Năng Cốt Lõi, triệu hồi mỏ neo tiến hành tấn công, gây <color=Fire>sát thương Hỏa Liệt</color> bằng {1}. Mỏ neo sẽ tạo ra một số "Quýt Cam" khi đập xuống mặt đất. Nhân vật nhặt "Quýt Cam" tăng {7} tấn công, và hồi phục HP dựa trên {8} HP tối đa của người thi triển, duy trì {2} giây, có thể cộng dồn {4} tầng. Hồi chiêu kỹ năng: {6} giây\n<size=10> </size>\n<size=40><color=Title>Mô đun có hiệu lực</color></size>\n[Số Lượng Đạn] [Hồi Chiêu Kỹ Năng]\n<size=10> </size>\n<size=40><color=Title>Hiệu quả nâng cấp</color></size>\nCấp Số Lượng Đạn {3}: Số lượng "Quýt" tăng {5}\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nBrant thích ăn đồ ngọt, vì đồ ngọt là ngọt.

### `lang_multi_text.db||MultiText||ItemInfo_83100019_PassiveBuffDescription`
- HV cũ: <size=40><color=Title>Nạp năng lực của Khảm Đặc Lôi Lạp cho Dango</color></size>\nKhi sử dụng Kỹ Năng Cốt Lõi, gây <color=Dark>sát thương Hủy Diệt</color> bằng {1}, khiến mục tiêu trong phạm vi tiến vào trạng thái đình trệ, duy trì {2} giây. Hồi chiêu kỹ năng: {3} giây\n<size=10> </size>\n<size=40><color=Title>Mô đun có hiệu lực</color></size>\n[Hồi Chiêu Kỹ Năng] [Phạm Vi Kỹ Năng]\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nHầu hết mọi người trong mắt Khảm Đặc Lôi Lạp không có bí mật, chỉ cần đứng trước mặt cô ấy, độc tố sẽ nói cho cô ấy biết tất cả.
- HV V4: <size=40><color=Title>Nạp năng lực của Cantarella cho Dango</color></size>\nKhi sử dụng Kỹ Năng Cốt Lõi, gây <color=Dark>sát thương Hủy Diệt</color> bằng {1}, khiến mục tiêu trong phạm vi tiến vào trạng thái đình trệ, duy trì {2} giây. Hồi chiêu kỹ năng: {3} giây\n<size=10> </size>\n<size=40><color=Title>Mô đun có hiệu lực</color></size>\n[Hồi Chiêu Kỹ Năng] [Phạm Vi Kỹ Năng]\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nHầu hết mọi người trong mắt Cantarella không có bí mật, chỉ cần đứng trước mặt cô ấy, độc tố sẽ nói cho cô ấy biết tất cả.

### `lang_multi_text.db||MultiText||ItemInfo_83100020_PassiveBuffDescription`
- HV cũ: <size=40><color=Title>Nạp năng lực của Tán Ny cho Dango</color></size>\nKhi sử dụng Kỹ Năng Cốt Lõi, duy trì trong {4} giây, liên tục tấn công mục tiêu, mỗi lần tấn công gây <color=Light>sát thương Quang Phổ</color> bằng {2}. Hồi chiêu kỹ năng: {3} giây\n<size=10> </size>\n<size=40><color=Title>Mô đun có hiệu lực</color></size>\n[Hồi Chiêu Kỹ Năng] [Phạm Vi Kỹ Năng]\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nPhòng để quần áo của Tán Ny chất đầy những bộ đồ công sở trông y hệt nhau, nhưng cô ấy có thể phân biệt được bộ nào nên mặc trong dịp nào.
- HV V4: <size=40><color=Title>Nạp năng lực của Zani cho Dango</color></size>\nKhi sử dụng Kỹ Năng Cốt Lõi, duy trì trong {4} giây, liên tục tấn công mục tiêu, mỗi lần tấn công gây <color=Light>sát thương Quang Phổ</color> bằng {2}. Hồi chiêu kỹ năng: {3} giây\n<size=10> </size>\n<size=40><color=Title>Mô đun có hiệu lực</color></size>\n[Hồi Chiêu Kỹ Năng] [Phạm Vi Kỹ Năng]\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nPhòng để quần áo của Zani chất đầy những bộ đồ công sở trông y hệt nhau, nhưng cô ấy có thể phân biệt được bộ nào nên mặc trong dịp nào.

### `lang_multi_text.db||MultiText||ItemInfo_83100021_PassiveBuffDescription`
- HV cũ: <size=40><color=Title>Nạp năng lực của Tạp Đề Hi Á cho Dango</color></size>\nKhi sử dụng Kỹ Năng Cốt Lõi, triệu hồi "Mưa Kiếm" liên tục tấn công mục tiêu, mỗi giây gây <color=Wind>sát thương Khí Động</color> bằng {1}, duy trì {5} giây. Hồi chiêu kỹ năng: {4} giây\n<size=10> </size>\n<size=40><color=Title>Mô đun có hiệu lực</color></size>\n[Số Lượng Đạn] [Phạm Vi Kỹ Năng]\n<size=10> </size>\n<size=40><color=Title>Hiệu quả nâng cấp</color></size>\nCấp Số Lượng Đạn {2}: Sát thương do "Mưa Kiếm" gây ra tăng {6}\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nCartethyia không thích ăn cá, không phải kén ăn, mà là không thích ăn cá.
- HV V4: <size=40><color=Title>Nạp năng lực của Cartethyia cho Dango</color></size>\nKhi sử dụng Kỹ Năng Cốt Lõi, triệu hồi "Mưa Kiếm" liên tục tấn công mục tiêu, mỗi giây gây <color=Wind>sát thương Khí Động</color> bằng {1}, duy trì {5} giây. Hồi chiêu kỹ năng: {4} giây\n<size=10> </size>\n<size=40><color=Title>Mô đun có hiệu lực</color></size>\n[Số Lượng Đạn] [Phạm Vi Kỹ Năng]\n<size=10> </size>\n<size=40><color=Title>Hiệu quả nâng cấp</color></size>\nCấp Số Lượng Đạn {2}: Sát thương do "Mưa Kiếm" gây ra tăng {6}\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nCartethyia không thích ăn cá, không phải kén ăn, mà là không thích ăn cá.

### `lang_multi_text.db||MultiText||ItemInfo_83100022_PassiveBuffDescription`
- HV cũ: <size=40><color=Title>Nạp năng lực của Phi Bỉ cho Dango</color></size>\nKhi sử dụng Kỹ Năng Cốt Lõi, liên tục triệu hồi "Ánh Sáng Thánh" tấn công mục tiêu gần đó, mỗi giây gây <color=Light>sát thương Quang Phổ</color> bằng {1}, và khiến tất cả nhân vật trong phạm vi liên tục nhận khiên dựa trên {9} HP tối đa của người thi triển, duy trì {2} giây. Hồi chiêu kỹ năng: {8} giây\n<size=10> </size>\n<size=40><color=Title>Mô đun có hiệu lực</color></size>\n[Phạm Vi Kỹ Năng] [Thời Gian Duy Trì]\n<size=10> </size>\n<size=40><color=Title>Hiệu quả nâng cấp</color></size>\nCấp Thời Gian Duy Trì {3}: Thời gian duy trì "Ánh Sáng Thánh" tăng {7} giây\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nKỹ nghệ Phi Bỉ dùng gậy giúp người khác bình tĩnh lại mà không làm họ bị thương là thành quả sau rất nhiều lần luyện tập ... đừng hỏi luyện tập nhiều lần là dùng cái gì luyện tập, cũng đừng hỏi nếu bị thương hậu quả sẽ nghiêm trọng thế nào.
- HV V4: <size=40><color=Title>Nạp năng lực của Phoebe cho Dango</color></size>\nKhi sử dụng Kỹ Năng Cốt Lõi, liên tục triệu hồi "Ánh Sáng Thánh" tấn công mục tiêu gần đó, mỗi giây gây <color=Light>sát thương Quang Phổ</color> bằng {1}, và khiến tất cả nhân vật trong phạm vi liên tục nhận khiên dựa trên {9} HP tối đa của người thi triển, duy trì {2} giây. Hồi chiêu kỹ năng: {8} giây\n<size=10> </size>\n<size=40><color=Title>Mô đun có hiệu lực</color></size>\n[Phạm Vi Kỹ Năng] [Thời Gian Duy Trì]\n<size=10> </size>\n<size=40><color=Title>Hiệu quả nâng cấp</color></size>\nCấp Thời Gian Duy Trì {3}: Thời gian duy trì "Ánh Sáng Thánh" tăng {7} giây\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nKỹ nghệ Phoebe dùng gậy giúp người khác bình tĩnh lại mà không làm họ bị thương là thành quả sau rất nhiều lần luyện tập ... đừng hỏi luyện tập nhiều lần là dùng cái gì luyện tập, cũng đừng hỏi nếu bị thương hậu quả sẽ nghiêm trọng thế nào.

### `lang_multi_text.db||MultiText||ItemInfo_83100041_AttributesDescription`
- HV cũ: Nạp năng lực của Thủ Ngạn Nhân cho Dango.\nKiến thức nhỏ: Thủ Ngạn Nhân khá thích Cơm San Hô của An Khả, sẽ khiến cô ấy nhớ đến biển cả, thế là An Khả được cổ vũ bắt đầu làm Cơm San Hô ngày càng mặn... Tóm lại là, bây giờ thì, không còn quá mong đợi để ăn nữa.
- HV V4: Nạp năng lực của Shorekeeper cho Dango.\nKiến thức nhỏ: Shorekeeper khá thích Cơm San Hô của Encore, sẽ khiến cô ấy nhớ đến biển cả, thế là Encore được cổ vũ bắt đầu làm Cơm San Hô ngày càng mặn... Tóm lại là, bây giờ thì, không còn quá mong đợi để ăn nữa.

### `lang_multi_text.db||MultiText||ItemInfo_83100051_AttributesDescription`
- HV cũ: Nạp năng lực của Xuân cho Dango.\nKiến thức nhỏ: Xuân khá thích tấn công trong tư thế treo ngược, theo lời chính chủ nói là sẽ có cảm giác bồng bềnh, rất vui sướng. Sau này trong một nhiệm vụ nào đó với An Khả, Xuân phát hiện ra tàu lượn siêu tốc cũng mang lại cảm giác này cho người ta, nên bây giờ cũng thích tàu lượn siêu tốc.
- HV V4: Nạp năng lực của Camellya cho Dango.\nKiến thức nhỏ: Camellya khá thích tấn công trong tư thế treo ngược, theo lời chính chủ nói là sẽ có cảm giác bồng bềnh, rất vui sướng. Sau này trong một nhiệm vụ nào đó với Encore, Camellya phát hiện ra tàu lượn siêu tốc cũng mang lại cảm giác này cho người ta, nên bây giờ cũng thích tàu lượn siêu tốc.

### `lang_multi_text.db||MultiText||ItemInfo_83100061_AttributesDescription`
- HV cũ: Nạp năng lực của Kha Lai Tháp cho Dango.\nKiến thức nhỏ: Công thức bí mật quan trọng nhất cho cà phê của Kha Lai Tháp thực ra là quýt, chủng loại, nơi sản xuất, độ chín cô ấy đều phải chu toàn ... nghe nói gần đây cô ấy thích những lát quýt có vị hơi chua chát hơn.
- HV V4: Nạp năng lực của Carlotta cho Dango.\nKiến thức nhỏ: Công thức bí mật quan trọng nhất cho cà phê của Carlotta thực ra là quýt, chủng loại, nơi sản xuất, độ chín cô ấy đều phải chu toàn ... nghe nói gần đây cô ấy thích những lát quýt có vị hơi chua chát hơn.

### `lang_multi_text.db||MultiText||ItemInfo_83100071_AttributesDescription`
- HV cũ: Nạp năng lực của Lạc Khả Khả cho Dango.\nKiến thức nhỏ: Lạc Khả Khả dưới vẻ ngoài trầm tĩnh rốt cuộc vẫn là một đứa trẻ, rất sợ bóng tối, rất thích ăn kẹo. Trong bóng tối sẽ ăn kẹo thật mạnh.
- HV V4: Nạp năng lực của Roccia cho Dango.\nKiến thức nhỏ: Roccia dưới vẻ ngoài trầm tĩnh rốt cuộc vẫn là một đứa trẻ, rất sợ bóng tối, rất thích ăn kẹo. Trong bóng tối sẽ ăn kẹo thật mạnh.

### `lang_multi_text.db||MultiText||ItemInfo_83100081_AttributesDescription`
- HV cũ: Nạp năng lực của Bố Lan Đặc cho Dango.\nKiến thức nhỏ: Bố Lan Đặc thích ăn đồ ngọt, vì đồ ngọt là ngọt.
- HV V4: Nạp năng lực của Brant cho Dango.\nKiến thức nhỏ: Brant thích ăn đồ ngọt, vì đồ ngọt là ngọt.

### `lang_multi_text.db||MultiText||ItemInfo_83100091_AttributesDescription`
- HV cũ: Nạp năng lực của Khảm Đặc Lôi Lạp cho Dango.\nKiến thức nhỏ: Hầu hết mọi người trong mắt Khảm Đặc Lôi Lạp không có bí mật, chỉ cần đứng trước mặt cô ấy, độc tố sẽ nói cho cô ấy biết tất cả.
- HV V4: Nạp năng lực của Cantarella cho Dango.\nKiến thức nhỏ: Hầu hết mọi người trong mắt Cantarella không có bí mật, chỉ cần đứng trước mặt cô ấy, độc tố sẽ nói cho cô ấy biết tất cả.

### `lang_multi_text.db||MultiText||ItemInfo_83100101_AttributesDescription`
- HV cũ: Nạp năng lực của Tán Ny cho Dango.\nKiến thức nhỏ: Phòng để quần áo của Tán Ny chất đầy những bộ đồ công sở trông y hệt nhau, nhưng cô ấy có thể phân biệt được bộ nào nên mặc trong dịp nào.
- HV V4: Nạp năng lực của Zani cho Dango.\nKiến thức nhỏ: Phòng để quần áo của Zani chất đầy những bộ đồ công sở trông y hệt nhau, nhưng cô ấy có thể phân biệt được bộ nào nên mặc trong dịp nào.

### `lang_multi_text.db||MultiText||ItemInfo_83100111_AttributesDescription`
- HV cũ: Nạp năng lực của Tạp Đề Hi Á cho Dango. \nKiến thức nhỏ: Tạp Đề Hi Á không thích ăn cá, không phải kén ăn, mà là không thích ăn cá.
- HV V4: Nạp năng lực của Cartethyia cho Dango. \nKiến thức nhỏ: Cartethyia không thích ăn cá, không phải kén ăn, mà là không thích ăn cá.

### `lang_multi_text.db||MultiText||ItemInfo_83100121_AttributesDescription`
- HV cũ: Nạp năng lực của Phi Bỉ cho Dango. \nKiến thức nhỏ: Kỹ nghệ Phi Bỉ dùng gậy giúp người khác bình tĩnh lại mà không làm họ bị thương là thành quả sau rất nhiều lần luyện tập ... đừng hỏi luyện tập nhiều lần là dùng cái gì luyện tập, cũng đừng hỏi nếu bị thương hậu quả sẽ nghiêm trọng thế nào.
- HV V4: Nạp năng lực của Phoebe cho Dango. \nKiến thức nhỏ: Kỹ nghệ Phoebe dùng gậy giúp người khác bình tĩnh lại mà không làm họ bị thương là thành quả sau rất nhiều lần luyện tập ... đừng hỏi luyện tập nhiều lần là dùng cái gì luyện tập, cũng đừng hỏi nếu bị thương hậu quả sẽ nghiêm trọng thế nào.

### `lang_multi_text.db||MultiText||ItemInfo_83200004_AttributesDescription`
- HV cũ: Thủ Ngạn Nhân. Mô đun thức tỉnh\nKiến thức nhỏ: Thủ Ngạn Nhân thích xem phim, gần đây cô ấy rất thích xem một bộ phim kể về nam nữ chính không ngừng gặp gỡ rồi bỏ lỡ nhau trong không thời gian hỗn loạn, cuối cùng vượt qua muôn vàn khó khăn để đến với nhau.
- HV V4: Shorekeeper. Mô đun thức tỉnh\nKiến thức nhỏ: Shorekeeper thích xem phim, gần đây cô ấy rất thích xem một bộ phim kể về nam nữ chính không ngừng gặp gỡ rồi bỏ lỡ nhau trong không thời gian hỗn loạn, cuối cùng vượt qua muôn vàn khó khăn để đến với nhau.

### `lang_multi_text.db||MultiText||ItemInfo_83200005_AttributesDescription`
- HV cũ: Xuân. Mô đun thức tỉnh\nKiến thức nhỏ: Xuân sợ lạnh, trong môi trường rất lạnh thậm chí sẽ rơi vào giấc ngủ sâu như ngủ đông. "Không sao đâu, mùa xuân sẽ lại mọc ra thôi~", bản thân cô ấy bổ sung thêm như vậy.
- HV V4: Camellya. Mô đun thức tỉnh\nKiến thức nhỏ: Camellya sợ lạnh, trong môi trường rất lạnh thậm chí sẽ rơi vào giấc ngủ sâu như ngủ đông. "Không sao đâu, mùa xuân sẽ lại mọc ra thôi~", bản thân cô ấy bổ sung thêm như vậy.

### `lang_multi_text.db||MultiText||ItemInfo_83200006_AttributesDescription`
- HV cũ: Kha Lai Tháp. Mô đun thức tỉnh\nKiến thức nhỏ: Kha Lai Tháp thích màu đỏ, và có sự nắm bắt chính xác về việc sử dụng màu đỏ nào trong hoàn cảnh nào. Nếu phải nói cái khó nắm bắt nhất, e rằng là màu ửng đỏ trên má chăng?
- HV V4: Carlotta. Mô đun thức tỉnh\nKiến thức nhỏ: Carlotta thích màu đỏ, và có sự nắm bắt chính xác về việc sử dụng màu đỏ nào trong hoàn cảnh nào. Nếu phải nói cái khó nắm bắt nhất, e rằng là màu ửng đỏ trên má chăng?

### `lang_multi_text.db||MultiText||ItemInfo_83200006_BgDescription`
- HV cũ: Khi Kha Lai Tháp thực hiện Đánh Thường, phát bắn thứ {0} được thay thế bằng "Mỹ Học Bạo Lực", gây sát thương Ngưng Băng bằng {1}\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nCarlotta thích màu đỏ, và có sự nắm bắt chính xác về việc sử dụng màu đỏ nào trong hoàn cảnh nào. Nếu phải nói cái khó nắm bắt nhất, e rằng là màu ửng đỏ trên má chăng?
- HV V4: Khi Carlotta thực hiện Đánh Thường, phát bắn thứ {0} được thay thế bằng "Mỹ Học Bạo Lực", gây sát thương Ngưng Băng bằng {1}\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nCarlotta thích màu đỏ, và có sự nắm bắt chính xác về việc sử dụng màu đỏ nào trong hoàn cảnh nào. Nếu phải nói cái khó nắm bắt nhất, e rằng là màu ửng đỏ trên má chăng?

### `lang_multi_text.db||MultiText||ItemInfo_83200007_AttributesDescription`
- HV cũ: Lạc Khả Khả. Mô đun thức tỉnh\nKiến thức nhỏ: Lạc Khả Khả không bao giờ tham gia tiết mục ca hát, vì hát trước mặt mọi người sẽ hơi căng thẳng, căng thẳng thì sẽ hát lạc nhịp, hát lạc nhịp lại càng căng thẳng hơn.
- HV V4: Roccia. Mô đun thức tỉnh\nKiến thức nhỏ: Roccia không bao giờ tham gia tiết mục ca hát, vì hát trước mặt mọi người sẽ hơi căng thẳng, căng thẳng thì sẽ hát lạc nhịp, hát lạc nhịp lại càng căng thẳng hơn.

### `lang_multi_text.db||MultiText||ItemInfo_83200008_AttributesDescription`
- HV cũ: Bố Lan Đặc. Mô đun thức tỉnh\nKiến thức nhỏ: Bố Lan Đặc có một cái tên luôn bị chôn vùi: Tern, nghĩa là nhàn biển, đó là cái tên cha mẹ để lại cho anh ấy. Nhưng bây giờ Tern có nghĩa là Bố Lan Đặc, là một thành viên của Đoàn Kịch Kẻ Ngốc.
- HV V4: Brant. Mô đun thức tỉnh\nKiến thức nhỏ: Brant có một cái tên luôn bị chôn vùi: Tern, nghĩa là nhàn biển, đó là cái tên cha mẹ để lại cho anh ấy. Nhưng bây giờ Tern có nghĩa là Brant, là một thành viên của Đoàn Kịch Kẻ Ngốc.

### `lang_multi_text.db||MultiText||ItemInfo_83200008_BgDescription`
- HV cũ: Mỏ neo khi đập xuống sẽ tạo ra "Quýt Xanh" và "Quýt Vàng". Nhặt "Quýt Xanh" có thể hồi {0} năng lượng Hiệp Tấu, nhặt "Quýt Vàng" có thể hồi {1} Năng lượng Dango\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nBrant có một cái tên luôn bị chôn vùi: Tern, nghĩa là nhàn biển, đó là cái tên cha mẹ để lại cho anh ấy. Nhưng bây giờ Tern có nghĩa là Bố Lan Đặc, là một thành viên của Đoàn Kịch Kẻ Ngốc.
- HV V4: Mỏ neo khi đập xuống sẽ tạo ra "Quýt Xanh" và "Quýt Vàng". Nhặt "Quýt Xanh" có thể hồi {0} năng lượng Hiệp Tấu, nhặt "Quýt Vàng" có thể hồi {1} Năng lượng Dango\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nBrant có một cái tên luôn bị chôn vùi: Tern, nghĩa là nhàn biển, đó là cái tên cha mẹ để lại cho anh ấy. Nhưng bây giờ Tern có nghĩa là Brant, là một thành viên của Đoàn Kịch Kẻ Ngốc.

### `lang_multi_text.db||MultiText||ItemInfo_83200009_AttributesDescription`
- HV cũ: Khảm Đặc Lôi Lạp. Mô đun thức tỉnh\nKiến thức nhỏ: Khảm Đặc Lôi Lạp hầu như không có vị giác, nhưng thích thức ăn có kết cấu dai giòn.
- HV V4: Cantarella. Mô đun thức tỉnh\nKiến thức nhỏ: Cantarella hầu như không có vị giác, nhưng thích thức ăn có kết cấu dai giòn.

### `lang_multi_text.db||MultiText||ItemInfo_83200010_AttributesDescription`
- HV cũ: Tán Ny. Mô đun thức tỉnh\nKiến thức nhỏ: Tán Ny trong kỳ nghỉ mỗi ngày đều dành ra một tiếng để đánh bóng và bôi sáp cho sừng của mình.
- HV V4: Zani. Mô đun thức tỉnh\nKiến thức nhỏ: Zani trong kỳ nghỉ mỗi ngày đều dành ra một tiếng để đánh bóng và bôi sáp cho sừng của mình.

### `lang_multi_text.db||MultiText||ItemInfo_83200010_BgDescription`
- HV cũ: Kỹ Năng Cốt Lõi mỗi lần trúng mục tiêu, trong trận chiến này sát thương tăng thêm của Dango Tán Ny tăng vĩnh viễn {0}\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nZani trong kỳ nghỉ mỗi ngày đều dành ra một tiếng để đánh bóng và bôi sáp cho sừng của mình.
- HV V4: Kỹ Năng Cốt Lõi mỗi lần trúng mục tiêu, trong trận chiến này sát thương tăng thêm của Dango Zani tăng vĩnh viễn {0}\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nZani trong kỳ nghỉ mỗi ngày đều dành ra một tiếng để đánh bóng và bôi sáp cho sừng của mình.

### `lang_multi_text.db||MultiText||ItemInfo_83200011_AttributesDescription`
- HV cũ: Tạp Đề Hi Á. Mô đun thức tỉnh\nKiến thức nhỏ: Một phần kiếm kỹ mà Tạp Đề Hi Á thi triển hiện nay là do cô ấy tự sáng tạo ra trong một khoảnh khắc lóe sáng khi dùng múa rối ngón tay ở Avinoleum.
- HV V4: Cartethyia. Mô đun thức tỉnh\nKiến thức nhỏ: Một phần kiếm kỹ mà Cartethyia thi triển hiện nay là do cô ấy tự sáng tạo ra trong một khoảnh khắc lóe sáng khi dùng múa rối ngón tay ở Avinoleum.

### `lang_multi_text.db||MultiText||ItemInfo_83200011_BgDescription`
- HV cũ: Thời gian duy trì của "Mưa Kiếm" tăng {0} giây\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nMột phần kiếm kỹ mà Tạp Đề Hi Á thi triển hiện nay là do cô ấy tự sáng tạo ra trong một khoảnh khắc lóe sáng khi dùng múa rối ngón tay ở Avinoleum.
- HV V4: Thời gian duy trì của "Mưa Kiếm" tăng {0} giây\n\n<size=40><color=Title>Kiến thức nhỏ</color></size>\nMột phần kiếm kỹ mà Cartethyia thi triển hiện nay là do cô ấy tự sáng tạo ra trong một khoảnh khắc lóe sáng khi dùng múa rối ngón tay ở Avinoleum.

### `lang_multi_text.db||MultiText||ItemInfo_83200012_AttributesDescription`
- HV cũ: Phi Bỉ. Mô đun thức tỉnh\nKiến thức nhỏ: Phi Bỉ không thích ăn đồ chua, ăn một chút chua là sẽ mất kiểm soát biểu cảm, khuôn mặt nhăn nhúm lại.
- HV V4: Phoebe. Mô đun thức tỉnh\nKiến thức nhỏ: Phoebe không thích ăn đồ chua, ăn một chút chua là sẽ mất kiểm soát biểu cảm, khuôn mặt nhăn nhúm lại.

### `lang_multi_text.db||MultiText||ItemInfo_85303001_AttributesDescription`
- HV cũ: Miếng dán Namipon có hình Phi Bỉ, có thể tăng cường sức chiến đấu cho Cộng Hưởng Giả khi thám hiểm ở Honami.
- HV V4: Miếng dán Namipon có hình Phoebe, có thể tăng cường sức chiến đấu cho Cộng Hưởng Giả khi thám hiểm ở Honami.

### `lang_multi_text.db||MultiText||ItemInfo_85303002_AttributesDescription`
- HV cũ: Miếng dán Namipon có hình Lộ Mạt, có thể tăng cường sức chiến đấu cho Cộng Hưởng Giả khi thám hiểm ở Honami.
- HV V4: Miếng dán Namipon có hình Lupa, có thể tăng cường sức chiến đấu cho Cộng Hưởng Giả khi thám hiểm ở Honami.

### `lang_multi_text.db||MultiText||ItemInfo_85303004_AttributesDescription`
- HV cũ: Miếng dán Namipon có hình Tán Ny, có thể tăng cường sức chiến đấu cho Cộng Hưởng Giả khi thám hiểm ở Honami.
- HV V4: Miếng dán Namipon có hình Zani, có thể tăng cường sức chiến đấu cho Cộng Hưởng Giả khi thám hiểm ở Honami.

### `lang_multi_text.db||MultiText||ItemInfo_85303005_AttributesDescription`
- HV cũ: Miếng dán Namipon có hình Tạp Đề Hi Á, có thể tăng cường sức chiến đấu cho Cộng Hưởng Giả khi thám hiểm ở Honami.
- HV V4: Miếng dán Namipon có hình Cartethyia, có thể tăng cường sức chiến đấu cho Cộng Hưởng Giả khi thám hiểm ở Honami.

### `lang_multi_text.db||MultiText||ItemInfo_85303007_AttributesDescription`
- HV cũ: Miếng dán Namipon có hình Thủ Ngạn Nhân, có thể tăng cường sức chiến đấu cho Cộng Hưởng Giả khi thám hiểm ở Honami.
- HV V4: Miếng dán Namipon có hình Shorekeeper, có thể tăng cường sức chiến đấu cho Cộng Hưởng Giả khi thám hiểm ở Honami.

### `lang_multi_text.db||MultiText||ItemInfo_85303008_AttributesDescription`
- HV cũ: Miếng dán Namipon có hình Áo Cổ Tư Tháp, có thể tăng cường sức chiến đấu cho Cộng Hưởng Giả khi thám hiểm ở Honami.
- HV V4: Miếng dán Namipon có hình Augusta, có thể tăng cường sức chiến đấu cho Cộng Hưởng Giả khi thám hiểm ở Honami.

### `lang_multi_text.db||MultiText||ItemInfo_85303012_AttributesDescription`
- HV cũ: Miếng dán Namipon có hình Thiên Tiếu, có thể tăng cường sức chiến đấu cho Cộng Hưởng Giả khi thám hiểm ở Honami.
- HV V4: Miếng dán Namipon có hình Chisa, có thể tăng cường sức chiến đấu cho Cộng Hưởng Giả khi thám hiểm ở Honami.

### `lang_multi_text.db||MultiText||ItemInfo_87400101_Name`
- HV cũ: Dán Tường Phi Bỉ - Tròn I
- HV V4: Dán Tường Phoebe - Tròn I

### `lang_multi_text.db||MultiText||ItemInfo_87400111_Name`
- HV cũ: Dán Tường Phi Bỉ - Thoi I
- HV V4: Dán Tường Phoebe - Thoi I

### `lang_multi_text.db||MultiText||ItemInfo_87400121_Name`
- HV cũ: Dán Tường Phi Bỉ - Lục Giác I
- HV V4: Dán Tường Phoebe - Lục Giác I

### `lang_multi_text.db||MultiText||ItemInfo_87400131_Name`
- HV cũ: Dán Tường Phi Bỉ - Tròn II
- HV V4: Dán Tường Phoebe - Tròn II

### `lang_multi_text.db||MultiText||ItemInfo_87400141_Name`
- HV cũ: Dán Tường Phi Bỉ - Thoi II
- HV V4: Dán Tường Phoebe - Thoi II

### `lang_multi_text.db||MultiText||ItemInfo_87400151_Name`
- HV cũ: Dán Tường Phi Bỉ - Lục Giác II
- HV V4: Dán Tường Phoebe - Lục Giác II

### `lang_multi_text.db||MultiText||ItemInfo_87400161_Name`
- HV cũ: Dán Tường Phi Bỉ - Tròn III
- HV V4: Dán Tường Phoebe - Tròn III

### `lang_multi_text.db||MultiText||ItemInfo_87400171_Name`
- HV cũ: Dán Tường Phi Bỉ - Thoi III
- HV V4: Dán Tường Phoebe - Thoi III

### `lang_multi_text.db||MultiText||ItemInfo_87400181_Name`
- HV cũ: Dán Tường Phi Bỉ - Lục Giác III
- HV V4: Dán Tường Phoebe - Lục Giác III

### `lang_multi_text.db||MultiText||ItemInfo_87400201_Name`
- HV cũ: Dán Tường Lộ Mạt - Tròn I
- HV V4: Dán Tường Lupa - Tròn I

### `lang_multi_text.db||MultiText||ItemInfo_87400211_Name`
- HV cũ: Dán Tường Lộ Mạt - Thoi I
- HV V4: Dán Tường Lupa - Thoi I

### `lang_multi_text.db||MultiText||ItemInfo_87400221_Name`
- HV cũ: Dán Tường Lộ Mạt - Lục Giác I
- HV V4: Dán Tường Lupa - Lục Giác I

### `lang_multi_text.db||MultiText||ItemInfo_87400231_Name`
- HV cũ: Dán Tường Lộ Mạt - Tròn II
- HV V4: Dán Tường Lupa - Tròn II

### `lang_multi_text.db||MultiText||ItemInfo_87400241_Name`
- HV cũ: Dán Tường Lộ Mạt - Thoi II
- HV V4: Dán Tường Lupa - Thoi II

### `lang_multi_text.db||MultiText||ItemInfo_87400251_Name`
- HV cũ: Dán Tường Lộ Mạt - Lục Giác II
- HV V4: Dán Tường Lupa - Lục Giác II

### `lang_multi_text.db||MultiText||ItemInfo_87400261_Name`
- HV cũ: Dán Tường Lộ Mạt - Tròn III
- HV V4: Dán Tường Lupa - Tròn III

### `lang_multi_text.db||MultiText||ItemInfo_87400271_Name`
- HV cũ: Dán Tường Lộ Mạt - Thoi III
- HV V4: Dán Tường Lupa - Thoi III

### `lang_multi_text.db||MultiText||ItemInfo_87400281_Name`
- HV cũ: Dán Tường Lộ Mạt - Lục Giác III
- HV V4: Dán Tường Lupa - Lục Giác III

### `lang_multi_text.db||MultiText||ItemInfo_87400401_Name`
- HV cũ: Dán Tường Tán Ny - Tròn I
- HV V4: Dán Tường Zani - Tròn I

### `lang_multi_text.db||MultiText||ItemInfo_87400411_Name`
- HV cũ: Dán Tường Tán Ny - Thoi I
- HV V4: Dán Tường Zani - Thoi I

### `lang_multi_text.db||MultiText||ItemInfo_87400421_Name`
- HV cũ: Dán Tường Tán Ny - Lục Giác I
- HV V4: Dán Tường Zani - Lục Giác I

### `lang_multi_text.db||MultiText||ItemInfo_87400431_Name`
- HV cũ: Dán Tường Tán Ny - Tròn II
- HV V4: Dán Tường Zani - Tròn II

### `lang_multi_text.db||MultiText||ItemInfo_87400441_Name`
- HV cũ: Dán Tường Tán Ny - Thoi II
- HV V4: Dán Tường Zani - Thoi II

### `lang_multi_text.db||MultiText||ItemInfo_87400451_Name`
- HV cũ: Dán Tường Tán Ny - Lục Giác II
- HV V4: Dán Tường Zani - Lục Giác II

### `lang_multi_text.db||MultiText||ItemInfo_87400461_Name`
- HV cũ: Dán Tường Tán Ny - Tròn III
- HV V4: Dán Tường Zani - Tròn III

### `lang_multi_text.db||MultiText||ItemInfo_87400471_Name`
- HV cũ: Dán Tường Tán Ny - Thoi II
- HV V4: Dán Tường Zani - Thoi II

### `lang_multi_text.db||MultiText||ItemInfo_87400481_Name`
- HV cũ: Dán Tường Tán Ny - Lục Giác III
- HV V4: Dán Tường Zani - Lục Giác III

### `lang_multi_text.db||MultiText||ItemInfo_87400501_Name`
- HV cũ: Dán Tường Tạp Đề Hi Á - Tròn I
- HV V4: Dán Tường Cartethyia - Tròn I

### `lang_multi_text.db||MultiText||ItemInfo_87400511_Name`
- HV cũ: Dán Tường Tạp Đề Hi Á - Thoi I
- HV V4: Dán Tường Cartethyia - Thoi I

### `lang_multi_text.db||MultiText||ItemInfo_87400521_Name`
- HV cũ: Dán Tường Tạp Đề Hi Á - Lục Giác I
- HV V4: Dán Tường Cartethyia - Lục Giác I

### `lang_multi_text.db||MultiText||ItemInfo_87400531_Name`
- HV cũ: Dán Tường Tạp Đề Hi Á - Tròn II
- HV V4: Dán Tường Cartethyia - Tròn II

### `lang_multi_text.db||MultiText||ItemInfo_87400541_Name`
- HV cũ: Dán Tường Tạp Đề Hi Á - Thoi II
- HV V4: Dán Tường Cartethyia - Thoi II

### `lang_multi_text.db||MultiText||ItemInfo_87400551_Name`
- HV cũ: Dán Tường Tạp Đề Hi Á - Lục Giác II
- HV V4: Dán Tường Cartethyia - Lục Giác II

### `lang_multi_text.db||MultiText||ItemInfo_87400561_Name`
- HV cũ: Dán Tường Tạp Đề Hi Á - Tròn III
- HV V4: Dán Tường Cartethyia - Tròn III

### `lang_multi_text.db||MultiText||ItemInfo_87400571_Name`
- HV cũ: Dán Tường Tạp Đề Hi Á - Thoi III
- HV V4: Dán Tường Cartethyia - Thoi III

### `lang_multi_text.db||MultiText||ItemInfo_87400581_Name`
- HV cũ: Dán Tường Tạp Đề Hi Á - Lục Giác III
- HV V4: Dán Tường Cartethyia - Lục Giác III

### `lang_multi_text.db||MultiText||ItemInfo_87400701_Name`
- HV cũ: Dán Tường Thủ Ngạn Nhân - Tròn I
- HV V4: Dán Tường Shorekeeper - Tròn I

### `lang_multi_text.db||MultiText||ItemInfo_87400711_Name`
- HV cũ: Dán Tường Thủ Ngạn Nhân - Thoi I
- HV V4: Dán Tường Shorekeeper - Thoi I

### `lang_multi_text.db||MultiText||ItemInfo_87400721_Name`
- HV cũ: Dán Tường Thủ Ngạn Nhân - Lục Giác I
- HV V4: Dán Tường Shorekeeper - Lục Giác I

### `lang_multi_text.db||MultiText||ItemInfo_87400731_Name`
- HV cũ: Dán Tường Thủ Ngạn Nhân - Tròn II
- HV V4: Dán Tường Shorekeeper - Tròn II

### `lang_multi_text.db||MultiText||ItemInfo_87400741_Name`
- HV cũ: Dán Tường Thủ Ngạn Nhân - Thoi II
- HV V4: Dán Tường Shorekeeper - Thoi II

### `lang_multi_text.db||MultiText||ItemInfo_87400751_Name`
- HV cũ: Dán Tường Thủ Ngạn Nhân - Lục Giác II
- HV V4: Dán Tường Shorekeeper - Lục Giác II

### `lang_multi_text.db||MultiText||ItemInfo_87400761_Name`
- HV cũ: Dán Tường Thủ Ngạn Nhân - Tròn III
- HV V4: Dán Tường Shorekeeper - Tròn III

### `lang_multi_text.db||MultiText||ItemInfo_87400771_Name`
- HV cũ: Dán Tường Thủ Ngạn Nhân - Thoi III
- HV V4: Dán Tường Shorekeeper - Thoi III

### `lang_multi_text.db||MultiText||ItemInfo_87400781_Name`
- HV cũ: Dán Tường Thủ Ngạn Nhân - Lục Giác III
- HV V4: Dán Tường Shorekeeper - Lục Giác III

### `lang_multi_text.db||MultiText||ItemInfo_87400801_Name`
- HV cũ: Dán Tường Áo Cổ Tư Tháp - Tròn I
- HV V4: Dán Tường Augusta - Tròn I

### `lang_multi_text.db||MultiText||ItemInfo_87400811_Name`
- HV cũ: Dán Tường Áo Cổ Tư Tháp - Thoi I
- HV V4: Dán Tường Augusta - Thoi I

### `lang_multi_text.db||MultiText||ItemInfo_87400821_Name`
- HV cũ: Dán Tường Áo Cổ Tư Tháp - Lục Giác I
- HV V4: Dán Tường Augusta - Lục Giác I

### `lang_multi_text.db||MultiText||ItemInfo_87400831_Name`
- HV cũ: Dán Tường Áo Cổ Tư Tháp - Tròn II
- HV V4: Dán Tường Augusta - Tròn II

### `lang_multi_text.db||MultiText||ItemInfo_87400841_Name`
- HV cũ: Dán Tường Áo Cổ Tư Tháp - Thoi II
- HV V4: Dán Tường Augusta - Thoi II

### `lang_multi_text.db||MultiText||ItemInfo_87400851_Name`
- HV cũ: Dán Tường Áo Cổ Tư Tháp - Lục Giác II
- HV V4: Dán Tường Augusta - Lục Giác II

### `lang_multi_text.db||MultiText||ItemInfo_87400861_Name`
- HV cũ: Dán Tường Áo Cổ Tư Tháp - Tròn III
- HV V4: Dán Tường Augusta - Tròn III

### `lang_multi_text.db||MultiText||ItemInfo_87400871_Name`
- HV cũ: Dán Tường Áo Cổ Tư Tháp - Thoi III
- HV V4: Dán Tường Augusta - Thoi III

### `lang_multi_text.db||MultiText||ItemInfo_87400881_Name`
- HV cũ: Dán Tường Áo Cổ Tư Tháp - Lục Giác III
- HV V4: Dán Tường Augusta - Lục Giác III

### `lang_multi_text.db||MultiText||ItemInfo_87401201_Name`
- HV cũ: Dán Tường Thiên Tiếu - Tròn I
- HV V4: Dán Tường Chisa - Tròn I

### `lang_multi_text.db||MultiText||ItemInfo_87401211_Name`
- HV cũ: Dán Tường Thiên Tiếu - Thoi I
- HV V4: Dán Tường Chisa - Thoi I

### `lang_multi_text.db||MultiText||ItemInfo_87401221_Name`
- HV cũ: Dán Tường Thiên Tiếu - Lục Giác I
- HV V4: Dán Tường Chisa - Lục Giác I

### `lang_multi_text.db||MultiText||ItemInfo_87401231_Name`
- HV cũ: Dán Tường Thiên Tiếu - Tròn II
- HV V4: Dán Tường Chisa - Tròn II

### `lang_multi_text.db||MultiText||ItemInfo_87401241_Name`
- HV cũ: Dán Tường Thiên Tiếu - Thoi II
- HV V4: Dán Tường Chisa - Thoi II

### `lang_multi_text.db||MultiText||ItemInfo_87401251_Name`
- HV cũ: Dán Tường Thiên Tiếu - Lục Giác II
- HV V4: Dán Tường Chisa - Lục Giác II

### `lang_multi_text.db||MultiText||ItemInfo_87401261_Name`
- HV cũ: Dán Tường Thiên Tiếu - Tròn III
- HV V4: Dán Tường Chisa - Tròn III

### `lang_multi_text.db||MultiText||ItemInfo_87401271_Name`
- HV cũ: Dán Tường Thiên Tiếu - Thoi III
- HV V4: Dán Tường Chisa - Thoi III

### `lang_multi_text.db||MultiText||ItemInfo_87401281_Name`
- HV cũ: Dán Tường Thiên Tiếu - Lục Giác III
- HV V4: Dán Tường Chisa - Lục Giác III

### `lang_multi_text.db||MultiText||ItemShowType_30_Name`
- VI cũ: Dải Tần Hồi Âm
- VI V4: Dải Âm Vang
- HV cũ: Dải Tần Hồi Âm
- HV V4: Dải Âm Vang


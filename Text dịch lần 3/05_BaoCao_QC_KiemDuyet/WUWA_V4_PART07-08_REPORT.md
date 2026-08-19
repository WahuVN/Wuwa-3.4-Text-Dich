# Wuthering Waves V4 — part07–08

## Kết quả

- part07: 22,945 entry; 138 entry VI thay đổi so với V3.
- part08: 26,439 entry; 11 entry VI thay đổi so với V3.
- CN / EN / JP giữ nguyên.
- Đã kiểm đủ tag, placeholder, gender branch, `%s/%d`, `\n` trên mọi entry sửa.

## Relationship state

### Encore ↔ Rover / Verina
- Rover: `{Male=anh;Female=chị}`; ưu tiên thứ tự Việt `anh/chị {PlayerName}`.
- Verina: `chị Verina`; Encore giữ giọng trẻ con ngoan, các câu đáp trực tiếp dùng `Vâng!` khi phù hợp.

### Mornye ↔ Rover
- `Mornye_shengtai_*` / Coop hậu reveal: **em – tiền bối**.
- Rover → Mornye: có thể gọi `em`; không hard-code giới tính Rover trong lời Mornye.
- Độc thoại/giấc mơ không có addressee thì không ép tự xưng `em`.

### Sigrika ↔ Rover
- Trước nhận diện: register trung tính.
- Trigger tại `YXBLDHJ_30_24–25`: Sigrika nhận ra Rover là “vị tiền bối”.
- Sau trigger, trong quan hệ riêng tư/ngưỡng mộ: **em – tiền bối**.
- Vai học đường công khai vẫn song song: Sigrika là đàn chị, Rover là sinh viên năm nhất. `YXBLDHJ_39_33` dùng **đàn em**, không retcon thành `tiền bối`.

## Semantic fixes nổi bật

- `YXBLDHJ_111_5–6`: trả chủ thể về Lynae, không biến hành động/cảm xúc của Lynae thành của Sigrika.
- `YXBLDHJ_111_16`: Sigrika vui vì Rover đã đến.
- `Mornye_shengtai_1_3`: source là Mornye đang ngủ, không phải đang nói mớ.
- `YXBLDHJ_39_33`: sửa lỗi đảo `学弟/学妹` thành `tiền bối` của bản cũ.

## Term lock xuyên part07–08

- `<ano=Aero>` → **Khí Động**
- `<ano=Glacio>` → **Ngưng Băng**
- `<ano=Coordinated Attack>` → **Kỹ Năng Liên Kết**
- `<ano=Heavy Attack DMG>` → **Sát Thương Trọng Kích**
- `<ano=Rover>` → **Rover**
- `<ano=Tacet Field>` → **Vùng Vô Thanh**
- `<ano=Threnodian>` → **Minh Thức**
- `<ano=treatment>` → **Điều Trị**
- `Nghi Thức Nghi Lễ Đổi Nhật` → **Nghi Lễ Đổi Nhật**.

## NAME LOCK HV

- Jinhsi → **Kim Tịch**
- Jiyan → **Kỵ Viêm**
- Changli → **Trường Ly**
- Yinlin → **Ngâm Lâm**
- Xiangli Yao → **Tương Lý Yếu**
- Yangyang → **Ương Ương**
- Chixia → **Xí Hà**
- Baizhi → **Bạch Chỉ**
- Sanhua → **Tán Hoa**
- Taoqi → **Đào Kì**
- Danjin → **Đan Cẩn**
- Jianxin → **Giám Tâm**
- Yuanwu → **Uyên Vũ**
- Mortefi → **Mạc Đặc Phỉ**
- Aalto → **Thu Thủy**
- Zhezhi → **Chiết Chi**
- Suisui → **Tuệ Tuệ**

Tên không có mapping giữ EN.

## Change log so với V3

### part07

#### `lang_multi_text.db||MultiText||Character_Encore_36_38`
- Cũ: Vậy nên, {PlayerName}, {Male=anh;Female=chị}...
- Mới: Vậy nên, {Male=anh;Female=chị} {PlayerName}...

#### `lang_multi_text.db||MultiText||Character_Encore_36_40`
- Cũ: Ừ! Encore muốn viết cho xong câu chuyện này!
- Mới: Vâng! Encore muốn viết cho xong câu chuyện này!

#### `lang_multi_text.db||MultiText||Character_Encore_37_23`
- Cũ: Ừ! Chính là gửi gắm cảm xúc vào vòng hoa!
- Mới: Vâng! Chính là gửi gắm cảm xúc vào vòng hoa!

#### `lang_multi_text.db||MultiText||Character_Encore_37_32`
- Cũ: Ừ! Chính là vậy đó, {Male=anh;Female=chị}! Chúng ta đi tìm những bông hoa có thể thể hiện cảm xúc của mình nào!
- Mới: Vâng! Chính là vậy đó, {Male=anh;Female=chị}! Chúng ta đi tìm những bông hoa có thể thể hiện cảm xúc của mình nào!

#### `lang_multi_text.db||MultiText||Character_Encore_37_37`
- Cũ: Ừ! Cảm ơn chị Verina! Vậy tụi em đi tìm đây!
- Mới: Vâng! Cảm ơn chị Verina! Vậy tụi em đi tìm đây!

#### `lang_multi_text.db||MultiText||Character_Encore_40_13`
- Cũ: Ừ! À mà còn nữa, chị Verina, có thể chừa lại một chỗ trống trên vòng hoa được không ạ?
- Mới: Vâng! À mà còn nữa, chị Verina, có thể chừa lại một chỗ trống trên vòng hoa được không ạ?

#### `lang_multi_text.db||MultiText||Character_Encore_40_18`
- Cũ: {Male=Đại ca;Female=Đại tỷ}, đợi vòng hoa làm xong, chúng ta có thể đi kể chuyện cho Ying nghe rồi đó.
- Mới: {Male=Anh;Female=Chị}, đợi vòng hoa làm xong, chúng ta có thể đi kể chuyện cho Ying nghe rồi đó.

#### `lang_multi_text.db||MultiText||Character_Encore_41_1`
- Cũ: {PlayerName}, {Male=anh;Female=chị} đến rồi à!
- Mới: {Male=anh;Female=chị} {PlayerName} đến rồi à!

#### `lang_multi_text.db||MultiText||Character_Encore_49_14`
- Cũ: {Male=Đại ca;Female=Đại tỷ}, lại đến phần phản hồi từ khán giả rồi. {Male=Đại ca;Female=Đại tỷ} thấy đây có phải là một câu chuyện hay không?
- Mới: {Male=Anh;Female=Chị}, lại đến phần phản hồi từ khán giả rồi. {Male=Anh;Female=Chị} thấy đây có phải là một câu chuyện hay không?

#### `lang_multi_text.db||MultiText||Character_JiYan_27_26`
- Cũ: Jiyan phát hiện Tàn Tượng đang mô phỏng Dạ Quy tham gia lễ tưởng niệm của Quảng Trường Minh Chung, điều này khiến cho anh ấy cảm thấy nực cười, bởi vì Tàn Tượng mãi mãi không thể nào hiểu được ý nghĩa của lễ tưởng niệm. Tiếng chuông lại một lần nữa vang lên, nhìn đám Ảo Ảnh đang di chuyển về phía sương mù, bạn cùng với Jiyan, đi tiến hành một cuộc tạm biệt.
- Mới: Jiyan nhận ra những Tàn Tượng đang bắt chước cảnh Dạ Quy tham dự lễ tưởng niệm ở Quảng Trường Minh Chung. Điều đó khiến anh thấy thật nực cười, bởi Tàn Tượng vĩnh viễn không thể hiểu ý nghĩa của nghi lễ ấy. Tiếng chuông lại vang lên. Nhìn những Ảo Ảnh đang tiến về phía màn sương, bạn cùng Jiyan bước tiếp để nói lời từ biệt.

#### `lang_multi_text.db||MultiText||Character_LingYang_25_19`
- Cũ: Đã tự nhận là dã thú, chắc không thể không biết, dã thú trên đời này đều có kỹ năng săn mồi riêng...
- Mới: Đã tự nhận mình là dã thú thì hẳn phải biết, mỗi loài dã thú trên đời đều có cách săn mồi riêng...

#### `lang_multi_text.db||MultiText||Character_Rococo_72_9`
- Cũ: Nguyện ý.
- Mới: Mình muốn tham gia.

#### `lang_multi_text.db||MultiText||Character_Zani_21303_1`
- Cũ: A... Rắc rối thật, thế này thì không thể không đánh một trận rồi.
- Mới: A... phiền thật, xem ra phải đánh một trận rồi.

#### `lang_multi_text.db||MultiText||Luuk_Shengtai_2_6`
- Cũ: Thực ra tôi cũng vậy, rõ ràng lên kế hoạch đợi xử lý xong đống công việc trong tay này, sẽ dọn dẹp phòng của mình thật đàng hoàng... Kết quả luôn bị đủ thứ tình huống đột xuất làm đảo lộn.
- Mới: Thật ra tôi cũng vậy. Tôi đã định xử lý xong đống việc trong tay rồi sẽ dọn phòng cho tử tế... ai ngờ cứ hết chuyện đột xuất này đến chuyện khác chen ngang.

#### `lang_multi_text.db||MultiText||Luuk_Shengtai_2_7`
- Cũ: Haiz, quả nhiên cuộc sống là như vậy mà~ Kế hoạch luôn rất khó bắt kịp sự thay đổi. Việc chúng ta có thể làm, có lẽ cũng chỉ là trong những khe hở bận rộn, tìm được cách để bản thân có thể hít thở thoải mái thôi.
- Mới: Haiz, cuộc sống là vậy đấy~ Kế hoạch chẳng bao giờ theo kịp thay đổi. Việc chúng ta có thể làm có lẽ chỉ là tranh thủ những khoảng nghỉ giữa bộn bề để tự cho mình một chút không gian thở thôi.

#### `lang_multi_text.db||MultiText||Mornye_shengtai_1_10`
- Cũ: ...Nhưng mà, ánh sáng của em... nhất định cũng có một ngày...
- Mới: ...Nhưng ánh sáng của mình... rồi sẽ có một ngày...

#### `lang_multi_text.db||MultiText||Mornye_shengtai_1_12`
- Cũ: Buổi tối vui vẻ, Mornye.
- Mới: Chào buổi tối, Mornye.

#### `lang_multi_text.db||MultiText||Mornye_shengtai_1_16`
- Cũ: Cảm thấy ở đây có lẽ sẽ gặp được em.
- Mới: Tôi nghĩ có lẽ sẽ gặp em ở đây.

#### `lang_multi_text.db||MultiText||Mornye_shengtai_1_20`
- Cũ: ...Tiền bối cũng giống như em, sẽ hoài niệm cảm giác đứng dưới bầu trời sao này?
- Mới: ...Tiền bối cũng giống em, cũng nhớ cảm giác được ở dưới bầu trời sao này sao?

#### `lang_multi_text.db||MultiText||Mornye_shengtai_1_21`
- Cũ: Muốn... cùng ngồi một lát không? Giống như trước đây.
- Mới: Tiền bối... có muốn ngồi cùng em một lát không? Như ngày trước.

#### `lang_multi_text.db||MultiText||Mornye_shengtai_1_3`
- Cũ: (Mornye đây là... đang nói mớ sao?)
- Mới: (Mornye... ngủ rồi sao?)

#### `lang_multi_text.db||MultiText||Mornye_shengtai_2_1`
- Cũ: Hôm nay Trận Liệt Mô Phỏng Khí Quyển không có dự kiến giáng thủy, cho nên, các vì sao sẽ đặc biệt sáng.
- Mới: Hôm nay Trận Liệt Mô Phỏng Khí Quyển không có lịch tạo mưa, nên các vì sao sẽ sáng hơn hẳn.

#### `lang_multi_text.db||MultiText||Mornye_shengtai_2_10`
- Cũ: Trông em có chút cô đơn.
- Mới: Trông em có vẻ hơi buồn.

#### `lang_multi_text.db||MultiText||Mornye_shengtai_2_2`
- Cũ: Anh nhìn xem, lấy ngôi sao sáng nhất trên đỉnh làm trung tâm, rồi nối các ngôi sao xung quanh lại, hình dáng sẽ giống như một ngọn hải đăng vậy.
- Mới: Tiền bối nhìn xem, lấy ngôi sao sáng nhất trên đỉnh trời làm trung tâm rồi nối các ngôi sao xung quanh lại, trông sẽ giống một ngọn hải đăng.

#### `lang_multi_text.db||MultiText||Mornye_shengtai_2_21`
- Cũ: Tuy rằng có hơi chậm một chút, tuy rằng dù với tốc độ ánh sáng, cũng phải tiêu tốn không biết bao nhiêu năm... nhưng mà, ánh sáng của em, nhất định sẽ có một ngày hòa vào bầu trời sao của Lahai-Roi, cùng mọi người thắp sáng nơi này.
- Mới: Dù có chậm một chút, dù ánh sáng phải mất không biết bao nhiêu năm mới đến nơi... ánh sáng của em nhất định sẽ có ngày hòa vào bầu trời sao Lahai-Roi, cùng mọi người soi sáng nơi này.

#### `lang_multi_text.db||MultiText||Mornye_shengtai_2_22`
- Cũ: Cũng có thể... chạm đến trong mắt anh.
- Mới: Và rồi... cũng sẽ đến được nơi tiền bối có thể nhìn thấy.

#### `lang_multi_text.db||MultiText||Mornye_shengtai_2_3`
- Cũ: Vị trí của chúng ở ngoài bầu trời vô tận, nhưng ánh sáng phát ra lại mãnh liệt như thế, dường như vươn tay là có thể chạm tới...
- Mới: Chúng ở tận phía bên kia bầu trời xa vô tận, vậy mà ánh sáng vẫn rực rỡ đến mức tưởng như chỉ cần đưa tay là chạm tới...

#### `lang_multi_text.db||MultiText||Mornye_shengtai_2_5`
- Cũ: "Nghi Thức Nghi Lễ Đổi Nhật" thành công rồi.
- Mới: "Nghi Lễ Đổi Nhật" thành công rồi.

#### `lang_multi_text.db||MultiText||Mornye_shengtai_3_2`
- Cũ: Hôm nay đến đây... cũng là để ngắm sao sao?
- Mới: Hôm nay... tiền bối cũng đến ngắm sao ạ?

#### `lang_multi_text.db||MultiText||Mornye_shengtai_3_4`
- Cũ: Muốn đến thăm cậu.
- Mới: Muốn đến thăm em.

#### `lang_multi_text.db||MultiText||Mornye_shengtai_3_5`
- Cũ: Vậy thì, xin cậu hãy lại ngồi bên cạnh mình nhé.
- Mới: Vậy thì... tiền bối lại ngồi bên cạnh em nhé.

#### `lang_multi_text.db||MultiText||Mornye_shengtai_3_7`
- Cũ: Tuyệt quá... được nhớ đến dưới bầu trời sao này, mình rất vui.
- Mới: Tốt quá... được tiền bối nhớ đến dưới bầu trời sao này, em vui lắm.

#### `lang_multi_text.db||MultiText||Mornye_shengtai_3_8`
- Cũ: Xin cậu hãy lại ngồi bên cạnh mình nhé, tiền bối.
- Mới: Tiền bối... lại ngồi bên cạnh em nhé.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_102_2`
- Cũ: Tiền bối, xin hãy để mình suy nghĩ kỹ đã.
- Mới: Tiền bối, xin hãy để em suy nghĩ kỹ đã.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_111_13`
- Cũ: Những câu đố này... phản ánh sự bất an và sợ hãi của em. Em nên trốn tránh luôn, không suy nghĩ gì cả, hay là đi đối mặt với nó, đi đối mặt với cái em trong Mặt Tối đó?
- Mới: Những câu đố này... phản chiếu nỗi bất an và sợ hãi của em. Em nên cứ thế trốn tránh, không nghĩ gì nữa, hay đối mặt với chúng—đối mặt với chính mình trong Mặt Tối?

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_111_16`
- Cũ: Em có thể tới, em rất vui.
- Mới: Tiền bối đến được đây, em vui lắm.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_111_29`
- Cũ: Cậu đến chỗ thầy bói, cùng Sigrika giải mã câu đố cuối cùng.\nSau vài ngày suy nghĩ, Sigrika nói cho cậu biết đáp án của cô bé.\nCác cậu quyết định cùng nhau đối mặt với tâm xoáy của Mặt Tối.
- Mới: Bạn đến chỗ thầy bói và cùng Sigrika giải mã câu đố cuối cùng.\nSau vài ngày suy nghĩ, Sigrika cho bạn biết câu trả lời của mình.\nHai người quyết định cùng nhau đối mặt với Tâm Xoáy của Mặt Tối.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_111_5`
- Cũ: Tiền bối Lynae kể cho em rất nhiều chuyện quá khứ của chị ấy. Chị ấy kể, lúc mới đến Học Viện Tinh Cự, chị ấy cũng không biết điều gì đang chờ đón em.
- Mới: Tiền bối Lynae kể cho em rất nhiều chuyện về quá khứ của chị ấy. Chị ấy nói rằng khi mới đến Học Viện Tinh Cự, bản thân cũng không biết điều gì đang chờ mình phía trước.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_111_6`
- Cũ: Nhưng chị ấy rất hài lòng với cuộc sống hiện tại, rất vui vì em có thể đứng ở đây.
- Mới: Nhưng chị ấy rất hài lòng với cuộc sống hiện tại, cũng rất vui vì bản thân có thể đứng ở nơi này.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_111_7`
- Cũ: Giáo sư Lucilla nói, cho dù cuối cùng sẽ xảy ra chuyện gì, cô ấy đều mong em có thể đối mặt. Ngoài em ra, còn có anh, có cô ấy, có bác sĩ Luuk... mọi người sẽ không để Mặt Tối thực sự lây nhiễm vào học viện.
- Mới: Giáo sư Lucilla nói, dù cuối cùng có chuyện gì xảy ra, cô ấy vẫn mong em có thể đối mặt. Ngoài em ra còn có tiền bối, giáo sư Lucilla, bác sĩ Luuk... mọi người sẽ không để Mặt Tối thật sự xâm chiếm Học Viện.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_111_9`
- Cũ: Và cả, tiền bối nữa. Những lời anh nói, em đều ghi tạc trong lòng.
- Mới: Và cả tiền bối nữa. Những lời tiền bối nói, em đều ghi nhớ trong lòng.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_134_22`
- Cũ: Tiền bối, anh mau lại đây đi!
- Mới: Tiền bối, mau lại đây!

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_134_3`
- Cũ: Tiền bối, cảm ơn anh.
- Mới: Cảm ơn tiền bối.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_30_23`
- Cũ: Mình là tân sinh viên năm nhất.
- Mới: Mình là sinh viên năm nhất.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_30_24`
- Cũ: Cái gì... Cậu chính là vị tiền bối đó?! Mới năm nhất thôi sao, giỏi quá...
- Mới: Hả... cậu chính là vị tiền bối ấy sao?! Mới năm nhất thôi mà... giỏi thật...

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_30_25`
- Cũ: Mình là Sigrika, mong được giúp đỡ! Lúc trước nghe tiền bối Lynae kể chuyện của các cậu, mình thật không ngờ người đánh bại Trùng Hư Đản lại chính là cậu!
- Mới: Em là Sigrika, mong tiền bối chỉ giáo! Trước đây em đã nghe tiền bối Lynae kể về mọi người. Em thật không ngờ người đánh bại Trùng Hư Đản lại chính là tiền bối!

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_30_26`
- Cũ: Vậy, có cần mình giúp gì không?
- Mới: Vậy tiền bối cần em giúp gì không?

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_30_28`
- Cũ: Vậy mà lại cần nói chuyện riêng sao? Xem ra không phải chuyện nhỏ rồi, đàn chị Sigrika, em mau giúp đỡ nhé.
- Mới: Phải nói chuyện riêng sao? Xem ra không phải chuyện nhỏ rồi. Đàn chị Sigrika, chị mau giúp một tay đi.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_30_30`
- Cũ: Mình hiểu rồi, thế phải tìm chỗ nào ít người...
- Mới: Em hiểu rồi, vậy phải tìm chỗ nào vắng người một chút...

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_36_1`
- Cũ: Hôm qua lúc ở trong Mặt Tối, mình hoàn toàn không kết nối cậu với câu chuyện của tiền bối Lynae lại với nhau.
- Mới: Hôm qua ở Mặt Tối, em hoàn toàn không nhận ra tiền bối chính là người trong những câu chuyện tiền bối Lynae từng kể.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_36_2`
- Cũ: Tiền bối Lynae kể, cậu rất kiên định, việc gì muốn làm là nhất định sẽ làm cho bằng được.
- Mới: Tiền bối Lynae nói tiền bối rất kiên định, đã muốn làm gì thì nhất định sẽ làm đến cùng.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_36_3`
- Cũ: Thật lợi hại.
- Mới: Thật đáng nể.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_37_10`
- Cũ: Tiền bối biết lời đồn đó chứ, Mặt Tối phản chiếu những suy nghĩ chân thật nhất của mọi người.
- Mới: Tiền bối biết lời đồn đó chứ? Mặt Tối phản chiếu những suy nghĩ chân thật nhất của mọi người.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_37_11`
- Cũ: Có lần, mình thấy trong đó một con mèo đen muốn về nhà, con mèo này rất lợi hại, có thể biến ra đôi cánh đen để bay.
- Mới: Có lần, em thấy trong đó một con mèo đen muốn về nhà. Nó rất lợi hại, còn có thể mọc ra đôi cánh đen để bay.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_37_12`
- Cũ: Còn có lần, mình trò chuyện với một cô bé hồn ma rất lâu. Mình không nhìn thấy cô ấy, nhưng lại nghe được tiếng cô ấy nói.
- Mới: Còn có lần, em trò chuyện rất lâu với một cô bé hồn ma. Em không nhìn thấy cô ấy, nhưng lại nghe được giọng cô ấy.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_37_17`
- Cũ: Nhưng cô ấy lại rất kiên định, kiên định đến mức khiến mình cảm thấy ấm áp. Vì thế, mình luôn nhớ về cô ấy.
- Mới: Nhưng cô ấy rất kiên định, kiên định đến mức khiến em cảm thấy ấm áp. Vì vậy, em vẫn luôn nhớ cô ấy.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_37_18`
- Cũ: Những chuyện này tuy kỳ lạ, nhưng lại rất thú vị, khiến mình muốn ở lỳ trong đó cả ngày, chẳng phải nghĩ ngợi đến chuyện bực mình nào.
- Mới: Những chuyện ấy tuy kỳ lạ nhưng rất thú vị, đến mức em từng muốn ở lì trong đó cả ngày, chẳng phải nghĩ đến chuyện phiền lòng nào.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_37_2`
- Cũ: Cậu xem, rất thích hợp để trò chuyện đúng không.
- Mới: Tiền bối xem, nơi này rất hợp để nói chuyện đúng không?

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_37_20`
- Cũ: Những thứ mình gặp hôm qua...
- Mới: Những thứ em gặp hôm qua...

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_37_22`
- Cũ: Cậu xem, nếu mình không làm gì cả, nó chỉ là một phù văn bình thường.
- Mới: Tiền bối xem, nếu em không làm gì, nó chỉ là một phù văn bình thường.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_37_23`
- Cũ: Nhưng nếu mình kích hoạt ngữ nghĩa của nó...
- Mới: Nhưng nếu em kích hoạt ngữ nghĩa của nó...

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_37_26`
- Cũ: Mình cũng không có manh mối... Mình từng thử truy vết, nhưng những phù văn đó cứ như sinh ra từ không khí vậy.
- Mới: Em cũng chưa có manh mối... Em đã thử truy vết, nhưng những phù văn đó cứ như tự nhiên xuất hiện từ hư không vậy.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_37_3`
- Cũ: Tiền bối tìm mình, là vì chuyện xảy ra ở Mặt Tối phải không?
- Mới: Tiền bối tìm em là vì chuyện xảy ra ở Mặt Tối phải không?

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_37_6`
- Cũ: Mình nghe Denia nói, dạo này cậu vẫn luôn bận giải đố.
- Mới: Em nghe Denia nói dạo này tiền bối vẫn luôn giải đố.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_37_7`
- Cũ: Ừm, những câu đố này rất thú vị, mình muốn giải thêm nhiều câu nữa trước khi lễ hội kết thúc.
- Mới: Ừm, những câu đố này thú vị lắm. Em muốn giải thêm vài câu trước khi lễ hội kết thúc.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_39_11`
- Cũ: Cậu không thấy lạ sao?
- Mới: Tiền bối không thấy lạ sao?

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_39_17`
- Cũ: ...Mình hiểu rồi!
- Mới: ...Em hiểu rồi!

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_39_18`
- Cũ: Mình nghĩ... chúng ta phải đi tìm Mặt Trời này.
- Mới: Em nghĩ... chúng ta phải đi tìm Mặt Trời này.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_39_19`
- Cũ: Đối với <ano=người Roya>bọn mình</ano> mà nói, phù văn được học đầu tiên và quen thuộc nhất, chính là "Mặt Trời".
- Mới: Với <ano=người Roya>bọn em</ano>, phù văn đầu tiên ai cũng học, cũng là phù văn quen thuộc nhất, chính là "Mặt Trời".

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_39_20`
- Cũ: Được tắm mình trong lời chúc phúc của ánh sáng mặt trời, đối với bọn mình cũng được coi là một loại <ano=thiên phú>ân tứ</ano>.
- Mới: Được tắm mình trong ánh Mặt Trời ban phúc, với bọn em cũng được xem là một dạng <ano=thiên phú>ân tứ</ano>.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_39_22`
- Cũ: Đúng vậy. Nó rất giống một trò chơi mà mình từng chơi.
- Mới: Đúng vậy. Nó rất giống một trò chơi em từng chơi.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_39_24`
- Cũ: Bọn mình cần tìm ra tất cả những phù văn này, theo sự chỉ dẫn của chúng để thoát khỏi Rừng Phù Quang.
- Mới: Bọn em phải tìm ra tất cả những phù văn ấy, rồi lần theo chỉ dẫn của chúng để ra khỏi Rừng Phù Quang.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_39_26`
- Cũ: Và nếu muốn giải được câu đố này, tiền bối, có lẽ cậu đang thiếu một người hướng dẫn hiểu rõ về phù văn Roya đấy.
- Mới: Và nếu muốn giải được câu đố này, tiền bối có lẽ đang thiếu một người dẫn đường hiểu rõ phù văn Roya.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_39_29`
- Cũ: Tiền bối? Không yên tâm về mình sao? Mình thật sự rất giỏi đấy nhé.
- Mới: Tiền bối? Không yên tâm về em sao? Em giỏi lắm đấy nhé.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_39_33`
- Cũ: Ừm! Hãy tin mình đi, {Male=tiền bối;Female=tiền bối} {PlayerName}, chúng ta đi tìm đáp án thôi!
- Mới: Ừm! Cứ tin mình đi, {PlayerName} {Male=đàn em;Female=đàn em}! Chúng ta đi tìm đáp án thôi!

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_39_34`
- Cũ: Từ chỗ thầy bói, các cậu nhận được một câu đố.\nCậu nhạy bén phát hiện, trong câu đố có thông tin về sự thay đổi của Mặt Tối: Mặt Tối đang nuôi dưỡng quái vật trong bóng tối.\nSigrika nhận ra, câu đố này rất giống trò chơi cô bé thường chơi ngày trước.\nCô bé xung phong làm người hướng dẫn, cùng cậu giải đố.
- Mới: Từ chỗ thầy bói, hai bạn nhận được một câu đố.\nBạn nhanh chóng nhận ra câu đố chứa manh mối về những biến đổi của Mặt Tối: nơi đó đang nuôi dưỡng quái vật trong bóng tối.\nSigrika nhận ra câu đố này rất giống trò chơi cô từng chơi khi còn nhỏ.\nCô chủ động đề nghị làm người dẫn đường và cùng bạn giải đố.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_39_8`
- Cũ: Phù văn. Đây là biểu tượng của "Mặt Trời". Đối với người Roya bọn mình mà nói, Mặt Trời là một sự tồn tại rất quan trọng.
- Mới: Phù văn. Đây là biểu tượng của "Mặt Trời". Với người Roya bọn em, Mặt Trời vô cùng quan trọng.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_42_3`
- Cũ: Tiền bối, cậu có mang máy ảnh không?
- Mới: Tiền bối, có mang máy ảnh không?

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_47_6`
- Cũ: Không sao đâu, đợi khi nào tiền bối muốn nói, thì lại nói cho mình biết nhé.
- Mới: Không sao đâu. Khi nào tiền bối muốn nói, hãy kể cho em biết nhé.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_4_10`
- Cũ: Con người phải có chiếc gối êm ái thì mới ngủ ngon được. Đối với 'giấc mộng' mà nói, đó là chân lý tuyệt đối.
- Mới: Muốn ngủ ngon thì phải có một chiếc gối êm. Với "giấc mộng", đó là chân lý tuyệt đối.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_4_11`
- Cũ: Đúng vậy, đối với 'giấc mộng' mà nói, đó chính là chân lý tuyệt đối.
- Mới: Đúng vậy. Với "giấc mộng", đó chính là chân lý tuyệt đối.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_67_2`
- Cũ: Đối với người Roya mà nói, thiên phú là gì, phúc lành là gì? Hãy nói cho tôi câu trả lời của cậu.
- Mới: Với người Roya, thế nào là thiên phú, thế nào là phúc lành? Cho tôi nghe câu trả lời của cậu.

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_70_1`
- Cũ: Tiền bối, cậu đến rồi!
- Mới: Tiền bối đến rồi!

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_73_20`
- Cũ: Mình muốn chơi thử! Tiền bối thì sao?
- Mới: Em muốn thử! Còn tiền bối?

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_75_18`
- Cũ: Nhiều, nhiều âm thanh như vậy... Tiền bối, khi bên tai anh có rất nhiều âm thanh, anh sẽ làm gì?
- Mới: Nhiều, nhiều âm thanh quá... Tiền bối, khi bên tai có quá nhiều tiếng nói, tiền bối sẽ làm gì?

#### `lang_multi_text_1sthalf.db||MultiText||Main_LahaiRoi_YXBLDHJ_75_5`
- Cũ: Hửm? Tiền bối, giọng cậu trở lại bình thường rồi kìa.
- Mới: Hửm? Tiền bối, giọng của tiền bối trở lại bình thường rồi kìa.

#### `lang_multi_text_1sthalf.db||MultiText||Zuoyequnxing_193_13`
- Cũ: Chỉ là... chị không thể không lo lắng. Chị hiểu rõ tài năng của Hiyuki hơn bất cứ ai. Em thậm chí có tiềm năng thu phục cả <ano=Threnodian>Minh Thức</ano>.
- Mới: Chỉ là... chị thật sự không yên tâm. Chẳng ai hiểu rõ tài năng của Hiyuki hơn chị. Em thậm chí còn có tiềm năng thu phục cả <ano=Threnodian>Minh Thức</ano>.

#### `lang_multi_text_2ndhalf.db||MultiText||HD_JYZDFY_8_16`
- Cũ: Liên Hiệp Thâm Không không thể không biết đến sự tồn tại của cô ấy, liệu có phải Vu Nữ đại nhân đã đạt được thỏa thuận hợp tác nào đó với họ không?
- Mới: Spacetrek Collective chắc chắn biết cô ấy tồn tại. Liệu Vu Nữ đại nhân có đạt được thỏa thuận hợp tác nào đó với họ không?

#### `lang_multi_text.db||MultiText||Werouge_BuffDesc_2102`
- Cũ: Cộng Hưởng Giả hỗ trợ trong mộng kỳ này: <color=#ffd12f>Carlotta, Chiết Chi, Lingyang, Sanhua, Youhu</color>, sử dụng ít nhất 1 Cộng Hưởng Giả hỗ trợ trong mộng có thể <color=#ffd12f>nhận thêm 150% Điểm Dị Tưởng</color>!\nHiệu quả hỗ trợ trong mộng kỳ này:\n·Toàn bộ nhân vật trong đội <color=#ffd12f>tăng 30% sát thương Ngưng Băng</color>;\n·Khi Đánh Thường trúng kẻ địch sẽ nhận 20 điểm Năng Lượng Mộng Cảnh, mỗi giây có thể kích hoạt 1 lần; <color=#ffd12f>khi thi triển Giải Phóng Cộng Hưởng, nhận 100 điểm Năng Lượng Mộng Cảnh, mỗi 10 giây có thể kích hoạt 1 lần; khi gây sát thương Ngưng Băng, nhận 30 điểm Năng Lượng Mộng Cảnh, mỗi giây có thể kích hoạt 1 lần;</color>\n·Năng Lượng Mộng Cảnh đạt 500 điểm sẽ vào trạng thái Mộng Tỉnh, trong trạng thái Mộng Tỉnh, Ẩn Dụ đặc định sẽ được cường hóa, đồng thời toàn đội tăng 50% Bạo Kích, 100% Hiệu Suất Cộng Hưởng, giảm 50% thời gian chờ Kỹ Năng Cộng Hưởng và Giải Phóng Cộng Hưởng. Trạng thái Mộng Tỉnh duy trì 10 giây, sau khi kết thúc, Năng Lượng Mộng Cảnh giảm xuống 0 điểm.
- Mới: Cộng Hưởng Giả hỗ trợ trong mộng kỳ này: <color=#ffd12f>Carlotta, Zhezhi, Lingyang, Sanhua, Youhu</color>, sử dụng ít nhất 1 Cộng Hưởng Giả hỗ trợ trong mộng có thể <color=#ffd12f>nhận thêm 150% Điểm Dị Tưởng</color>!\nHiệu quả hỗ trợ trong mộng kỳ này:\n·Toàn bộ nhân vật trong đội <color=#ffd12f>tăng 30% sát thương Ngưng Băng</color>;\n·Khi Đánh Thường trúng kẻ địch sẽ nhận 20 điểm Năng Lượng Mộng Cảnh, mỗi giây có thể kích hoạt 1 lần; <color=#ffd12f>khi thi triển Giải Phóng Cộng Hưởng, nhận 100 điểm Năng Lượng Mộng Cảnh, mỗi 10 giây có thể kích hoạt 1 lần; khi gây sát thương Ngưng Băng, nhận 30 điểm Năng Lượng Mộng Cảnh, mỗi giây có thể kích hoạt 1 lần;</color>\n·Năng Lượng Mộng Cảnh đạt 500 điểm sẽ vào trạng thái Mộng Tỉnh, trong trạng thái Mộng Tỉnh, Ẩn Dụ đặc định sẽ được cường hóa, đồng thời toàn đội tăng 50% Bạo Kích, 100% Hiệu Suất Cộng Hưởng, giảm 50% thời gian chờ Kỹ Năng Cộng Hưởng và Giải Phóng Cộng Hưởng. Trạng thái Mộng Tỉnh duy trì 10 giây, sau khi kết thúc, Năng Lượng Mộng Cảnh giảm xuống 0 điểm.

#### `lang_multi_text.db||MultiText||Werouge_BuffDesc_2106`
- Cũ: Cộng Hưởng Giả hỗ trợ trong mộng kỳ này: <color=#ffd12f>Jiyan, Giám Tâm, Mortefi, Yangyang, Aalto</color>, sử dụng ít nhất 1 Cộng Hưởng Giả hỗ trợ trong mộng có thể nhận thêm 150% điểm!\nHiệu quả hỗ trợ trong mộng kỳ này:\n·Toàn bộ nhân vật trong đội <color=#ffd12f>tăng 30% sát thương Khí Động</color>;\n·Khi Đánh Thường trúng kẻ địch sẽ nhận 20 điểm Năng Lượng Mộng Cảnh, mỗi giây có thể kích hoạt 1 lần; <color=#ffd12f>khi thi triển Giải Phóng Cộng Hưởng, nhận 100 điểm Năng Lượng Mộng Cảnh, mỗi 10 giây có thể kích hoạt 1 lần; khi gây sát thương Khí Động, nhận 30 điểm Năng Lượng Mộng Cảnh, mỗi giây có thể kích hoạt 1 lần;</color>\n·Năng Lượng Mộng Cảnh đạt 500 điểm sẽ vào trạng thái Mộng Tỉnh, trong trạng thái Mộng Tỉnh, Ẩn Dụ đặc định sẽ được cường hóa, đồng thời toàn đội tăng 50% Bạo Kích, 100% Hiệu Suất Cộng Hưởng, giảm 50% thời gian chờ Kỹ Năng Cộng Hưởng và Giải Phóng Cộng Hưởng. Trạng thái Mộng Tỉnh duy trì 10 giây, sau khi kết thúc, Năng Lượng Mộng Cảnh giảm xuống 0 điểm.
- Mới: Cộng Hưởng Giả hỗ trợ trong mộng kỳ này: <color=#ffd12f>Jiyan, Jianxin, Mortefi, Yangyang, Aalto</color>, sử dụng ít nhất 1 Cộng Hưởng Giả hỗ trợ trong mộng có thể nhận thêm 150% điểm!\nHiệu quả hỗ trợ trong mộng kỳ này:\n·Toàn bộ nhân vật trong đội <color=#ffd12f>tăng 30% sát thương Khí Động</color>;\n·Khi Đánh Thường trúng kẻ địch sẽ nhận 20 điểm Năng Lượng Mộng Cảnh, mỗi giây có thể kích hoạt 1 lần; <color=#ffd12f>khi thi triển Giải Phóng Cộng Hưởng, nhận 100 điểm Năng Lượng Mộng Cảnh, mỗi 10 giây có thể kích hoạt 1 lần; khi gây sát thương Khí Động, nhận 30 điểm Năng Lượng Mộng Cảnh, mỗi giây có thể kích hoạt 1 lần;</color>\n·Năng Lượng Mộng Cảnh đạt 500 điểm sẽ vào trạng thái Mộng Tỉnh, trong trạng thái Mộng Tỉnh, Ẩn Dụ đặc định sẽ được cường hóa, đồng thời toàn đội tăng 50% Bạo Kích, 100% Hiệu Suất Cộng Hưởng, giảm 50% thời gian chờ Kỹ Năng Cộng Hưởng và Giải Phóng Cộng Hưởng. Trạng thái Mộng Tỉnh duy trì 10 giây, sau khi kết thúc, Năng Lượng Mộng Cảnh giảm xuống 0 điểm.

#### `lang_multi_text.db||MultiText||Werouge_BuffDesc_2304`
- Cũ: Cộng Hưởng Giả hỗ trợ trong mộng kỳ này: <color=#ffd12f>Cartethyia, Ciaccona, Jiyan, Giám Tâm, Yangyang, Aalto</color>, sử dụng ít nhất 1 Cộng Hưởng Giả hỗ trợ trong mộng có thể nhận thêm 150% điểm!\nHiệu quả hỗ trợ trong mộng kỳ này:\n·Toàn bộ nhân vật trong đội <color=#ffd12f>tăng 30% sát thương Khí Động</color>;\n·<color=#ffd12f>Khi gây sát thương Khí Động, nhận 30 điểm Năng Lượng Mộng Cảnh, mỗi giây có thể kích hoạt 1 lần;</color>\n·Năng Lượng Mộng Cảnh đạt 500 điểm sẽ vào trạng thái Mộng Tỉnh, trong trạng thái Mộng Tỉnh, Ẩn Dụ đặc định sẽ được cường hóa, đồng thời toàn đội tăng 50% Bạo Kích, 100% Hiệu Suất Cộng Hưởng, giảm 50% thời gian chờ Kỹ Năng Cộng Hưởng và Giải Phóng Cộng Hưởng. Trạng thái Mộng Tỉnh duy trì 10 giây, sau khi kết thúc, Năng Lượng Mộng Cảnh giảm xuống 0 điểm.
- Mới: Cộng Hưởng Giả hỗ trợ trong mộng kỳ này: <color=#ffd12f>Cartethyia, Ciaccona, Jiyan, Jianxin, Yangyang, Aalto</color>, sử dụng ít nhất 1 Cộng Hưởng Giả hỗ trợ trong mộng có thể nhận thêm 150% điểm!\nHiệu quả hỗ trợ trong mộng kỳ này:\n·Toàn bộ nhân vật trong đội <color=#ffd12f>tăng 30% sát thương Khí Động</color>;\n·<color=#ffd12f>Khi gây sát thương Khí Động, nhận 30 điểm Năng Lượng Mộng Cảnh, mỗi giây có thể kích hoạt 1 lần;</color>\n·Năng Lượng Mộng Cảnh đạt 500 điểm sẽ vào trạng thái Mộng Tỉnh, trong trạng thái Mộng Tỉnh, Ẩn Dụ đặc định sẽ được cường hóa, đồng thời toàn đội tăng 50% Bạo Kích, 100% Hiệu Suất Cộng Hưởng, giảm 50% thời gian chờ Kỹ Năng Cộng Hưởng và Giải Phóng Cộng Hưởng. Trạng thái Mộng Tỉnh duy trì 10 giây, sau khi kết thúc, Năng Lượng Mộng Cảnh giảm xuống 0 điểm.

#### `lang_multi_text.db||MultiText||Werouge_BuffDesc_2306`
- Cũ: Cộng Hưởng Giả hỗ trợ trong mộng kỳ này: <color=#ffd12f>Carlotta, Chiết Chi, Lingyang, Sanhua, Youhu</color>, sử dụng ít nhất 1 Cộng Hưởng Giả hỗ trợ trong mộng có thể <color=#ffd12f>nhận thêm 150% Điểm Dị Tưởng</color>!\nHiệu quả hỗ trợ trong mộng kỳ này:\n·Toàn bộ nhân vật trong đội <color=#ffd12f>tăng 30% sát thương Ngưng Băng</color>;\n·<color=#ffd12f>Khi gây sát thương Ngưng Băng, nhận 30 điểm Năng Lượng Mộng Cảnh, mỗi giây có thể kích hoạt 1 lần;</color>\n·Năng Lượng Mộng Cảnh đạt 500 điểm sẽ vào trạng thái Mộng Tỉnh, trong trạng thái Mộng Tỉnh, Ẩn Dụ đặc định sẽ được cường hóa, đồng thời toàn đội tăng 50% Bạo Kích, 100% Hiệu Suất Cộng Hưởng, giảm 50% thời gian chờ Kỹ Năng Cộng Hưởng và Giải Phóng Cộng Hưởng. Trạng thái Mộng Tỉnh duy trì 10 giây, sau khi kết thúc, Năng Lượng Mộng Cảnh giảm xuống 0 điểm.
- Mới: Cộng Hưởng Giả hỗ trợ trong mộng kỳ này: <color=#ffd12f>Carlotta, Zhezhi, Lingyang, Sanhua, Youhu</color>, sử dụng ít nhất 1 Cộng Hưởng Giả hỗ trợ trong mộng có thể <color=#ffd12f>nhận thêm 150% Điểm Dị Tưởng</color>!\nHiệu quả hỗ trợ trong mộng kỳ này:\n·Toàn bộ nhân vật trong đội <color=#ffd12f>tăng 30% sát thương Ngưng Băng</color>;\n·<color=#ffd12f>Khi gây sát thương Ngưng Băng, nhận 30 điểm Năng Lượng Mộng Cảnh, mỗi giây có thể kích hoạt 1 lần;</color>\n·Năng Lượng Mộng Cảnh đạt 500 điểm sẽ vào trạng thái Mộng Tỉnh, trong trạng thái Mộng Tỉnh, Ẩn Dụ đặc định sẽ được cường hóa, đồng thời toàn đội tăng 50% Bạo Kích, 100% Hiệu Suất Cộng Hưởng, giảm 50% thời gian chờ Kỹ Năng Cộng Hưởng và Giải Phóng Cộng Hưởng. Trạng thái Mộng Tỉnh duy trì 10 giây, sau khi kết thúc, Năng Lượng Mộng Cảnh giảm xuống 0 điểm.

#### `lang_multi_text.db||MultiText||Werouge_BuffDesc_2401`
- Cũ: Cộng Hưởng Giả hỗ trợ trong mộng kỳ này: <color=#ffd12f>Cartethyia, Ciaccona, Jiyan, Giám Tâm, Yangyang, Aalto</color>, sử dụng ít nhất 1 Cộng Hưởng Giả hỗ trợ trong mộng có thể nhận thêm 150% điểm!\nHiệu quả hỗ trợ trong mộng kỳ này:\n·Toàn bộ nhân vật trong đội <color=#ffd12f>tăng 30% sát thương Khí Động</color>;\n·<color=#ffd12f>Khi gây sát thương Khí Động, nhận 30 điểm Năng Lượng Mộng Cảnh, mỗi giây có thể kích hoạt 1 lần;</color>\n·Năng Lượng Mộng Cảnh đạt 500 điểm sẽ vào trạng thái Mộng Tỉnh, trong trạng thái Mộng Tỉnh, Ẩn Dụ đặc định sẽ được cường hóa, đồng thời toàn đội tăng 50% Bạo Kích, 100% Hiệu Suất Cộng Hưởng, giảm 50% thời gian chờ Kỹ Năng Cộng Hưởng và Giải Phóng Cộng Hưởng. Trạng thái Mộng Tỉnh duy trì 10 giây, sau khi kết thúc, Năng Lượng Mộng Cảnh giảm xuống 0 điểm.
- Mới: Cộng Hưởng Giả hỗ trợ trong mộng kỳ này: <color=#ffd12f>Cartethyia, Ciaccona, Jiyan, Jianxin, Yangyang, Aalto</color>, sử dụng ít nhất 1 Cộng Hưởng Giả hỗ trợ trong mộng có thể nhận thêm 150% điểm!\nHiệu quả hỗ trợ trong mộng kỳ này:\n·Toàn bộ nhân vật trong đội <color=#ffd12f>tăng 30% sát thương Khí Động</color>;\n·<color=#ffd12f>Khi gây sát thương Khí Động, nhận 30 điểm Năng Lượng Mộng Cảnh, mỗi giây có thể kích hoạt 1 lần;</color>\n·Năng Lượng Mộng Cảnh đạt 500 điểm sẽ vào trạng thái Mộng Tỉnh, trong trạng thái Mộng Tỉnh, Ẩn Dụ đặc định sẽ được cường hóa, đồng thời toàn đội tăng 50% Bạo Kích, 100% Hiệu Suất Cộng Hưởng, giảm 50% thời gian chờ Kỹ Năng Cộng Hưởng và Giải Phóng Cộng Hưởng. Trạng thái Mộng Tỉnh duy trì 10 giây, sau khi kết thúc, Năng Lượng Mộng Cảnh giảm xuống 0 điểm.

#### `lang_multi_text.db||MultiText||ResonantChain_112_AttributesDescription`
- Cũ: Khi thi triển Mạch Cộng Hưởng <color=Highlight>Đánh Mạnh - Hỗn Nguyên Khí Toàn</color>, sát thương Giải Phóng Cộng Hưởng <color=Highlight>Địch Tịnh Lực Trường</color> của Giám Tâm tăng {0}, duy trì {1} giây.
- Mới: Khi thi triển Mạch Cộng Hưởng <color=Highlight>Đánh Mạnh - Hỗn Nguyên Khí Toàn</color>, sát thương Giải Phóng Cộng Hưởng <color=Highlight>Địch Tịnh Lực Trường</color> của Jianxin tăng {0}, duy trì {1} giây.

#### `lang_multi_text.db||MultiText||ResonantChain_114_AttributesDescription`
- Cũ: Trong thời gian Mạch Cộng Hưởng <color=Highlight>Đánh Mạnh - Hỗn Nguyên Khí Toàn</color> thi triển <color=Highlight>Trùng Quyền</color>, nhận được Kỹ Năng Cộng Hưởng cường hóa <color=Highlight>Đặc Thù Hành Khí Phản Công</color>, trong {0} giây có thể thi triển {1} lần. <color=Highlight>Đặc Thù Hành Khí Phản Công</color>: Gây <color=Wind>sát thương Khí Động</color> bằng {2} Tấn Công của Giám Tâm, sát thương lần này là sát thương Đánh Mạnh, đồng thời nhận được khiên đạt giai đoạn Đại Chu Thiên - Ngoại (chịu ảnh hưởng buff của Kỹ Năng Nội Tại <color=Highlight>Phúc Ánh Ngô Thân</color>).
- Mới: Trong thời gian Mạch Cộng Hưởng <color=Highlight>Đánh Mạnh - Hỗn Nguyên Khí Toàn</color> thi triển <color=Highlight>Trùng Quyền</color>, nhận được Kỹ Năng Cộng Hưởng cường hóa <color=Highlight>Đặc Thù Hành Khí Phản Công</color>, trong {0} giây có thể thi triển {1} lần. <color=Highlight>Đặc Thù Hành Khí Phản Công</color>: Gây <color=Wind>sát thương Khí Động</color> bằng {2} Tấn Công của Jianxin, sát thương lần này là sát thương Đánh Mạnh, đồng thời nhận được khiên đạt giai đoạn Đại Chu Thiên - Ngoại (chịu ảnh hưởng buff của Kỹ Năng Nội Tại <color=Highlight>Phúc Ánh Ngô Thân</color>).

#### `lang_multi_text.db||MultiText||Skill_1001907_SkillDescribe`
- Cũ: <size=40><color=Title>Đánh Mạnh: Hỗn Nguyên Khí Toàn</color></size>\nKhi [Khí] đạt giới hạn, nhấn giữ <color=Highlight>Đánh Thường</color> sẽ thi triển <color=Highlight>Hỗn Nguyên Khí Toàn</color>, bước vào <color=Highlight>Trạng thái Vận Khí</color>.\n<size=10> </size>\n <size=40><color=Title>Trạng thái Vận Khí</color></size>\nKhả năng kháng gián đoạn của Giám Tâm tăng lên, sát thương phải chịu giảm {0};\nTiếp tục tiêu hao [Khí], và liên tục thi triển <color=Highlight>Vận Khí</color> tấn công mục tiêu gần đó, gây <color=Wind>Sát thương Khí Động</color>;\nTheo thời gian <color=Highlight>Trạng thái Vận Khí</color> kéo dài, Giám Tâm dần đạt đến các Chu Thiên khác nhau, khi đạt đến các Chu Thiên khác nhau:\n·Chưa đạt Tiểu Chu Thiên: Nhận được khiên Vận Khí tầng 1. Khi gián đoạn <color=Highlight>Trạng thái Vận Khí</color>, thi triển <color=Highlight>Xung Quyền</color> tấn công mục tiêu, gây <color=Wind>Sát thương Khí Động</color>;\n·Tiểu Chu Thiên: Nhận được khiên Vận Khí tầng 2, và <color=Highlight>Chấn Khí</color> tấn công mục tiêu, gây <color=Wind>Sát thương Khí Động</color>. Khi gián đoạn <color=Highlight>Trạng thái Vận Khí</color>, thi triển <color=Highlight>Thôi Thủ</color> tấn công mục tiêu, gây <color=Wind>Sát thương Khí Động</color>;\n·Đại Chu Thiên·Nội: Nhận được khiên Vận Khí tầng 3, và <color=Highlight>Chấn Khí</color> tấn công mục tiêu, gây <color=Wind>Sát thương Khí Động</color>. Khi gián đoạn <color=Highlight>Trạng thái Vận Khí</color>, thi triển <color=Highlight>Thôi Thủ</color> tấn công mục tiêu, gây <color=Wind>Sát thương Khí Động</color>;\n·Đại Chu Thiên·Ngoại: Nhận được khiên Vận Khí tầng 4, và <color=Highlight>Chấn Khí</color> tấn công mục tiêu, gây <color=Wind>Sát thương Khí Động</color>;\n·Khi buông <color=Highlight>Đánh Thường</color>, gián đoạn <color=Highlight>Trạng thái Vận Khí</color>, và tiêu hao tất cả [Khí];\n·Khi tiêu hao hết tất cả [Khí], kết thúc <color=Highlight>Trạng thái Vận Khí</color>;\n<size=10></size>\nKhi <color=Highlight>Trạng thái Vận Khí</color> kết thúc, nhận lại khiên của Chu Thiên tương ứng dựa trên giai đoạn Chu Thiên;\nTrong thời gian khiên nhận được từ <color=Highlight>Đánh Mạnh: Hỗn Nguyên Khí Toàn</color> duy trì, mỗi {1} giây hồi phục sinh lực cho nhân vật đang xuất chiến trong đội;\n<size=10></size>\n<size=40><color=Title>Quy tắc nhận Khí</color></size>\nGiới hạn [Khí] là {2} điểm.\nKhi Đánh Thường <color=Highlight>Phong Nghi Quyền Thuật</color> trúng mục tiêu, nhận được [Khí].\nKhi thi triển Kỹ Năng Cộng Hưởng <color=Highlight>Tĩnh Khí Tuần Hành</color>, nhận được [Khí].\nKhi Kỹ Năng Cộng Hưởng <color=Highlight>Hành Khí Phản Công</color> hoặc Kỹ Năng Cộng Hưởng <color=Highlight>Giáng Khí Phản Công</color> trúng mục tiêu, nhận được [Khí].\nKhi Kỹ Năng Biến Tấu <color=Highlight>Chưởng Tức Chi Yếu</color> trúng mục tiêu, nhận được [Khí].
- Mới: <size=40><color=Title>Đánh Mạnh: Hỗn Nguyên Khí Toàn</color></size>\nKhi [Khí] đạt giới hạn, nhấn giữ <color=Highlight>Đánh Thường</color> sẽ thi triển <color=Highlight>Hỗn Nguyên Khí Toàn</color>, bước vào <color=Highlight>Trạng thái Vận Khí</color>.\n<size=10> </size>\n <size=40><color=Title>Trạng thái Vận Khí</color></size>\nKhả năng kháng gián đoạn của Jianxin tăng lên, sát thương phải chịu giảm {0};\nTiếp tục tiêu hao [Khí], và liên tục thi triển <color=Highlight>Vận Khí</color> tấn công mục tiêu gần đó, gây <color=Wind>Sát thương Khí Động</color>;\nTheo thời gian <color=Highlight>Trạng thái Vận Khí</color> kéo dài, Jianxin dần đạt đến các Chu Thiên khác nhau, khi đạt đến các Chu Thiên khác nhau:\n·Chưa đạt Tiểu Chu Thiên: Nhận được khiên Vận Khí tầng 1. Khi gián đoạn <color=Highlight>Trạng thái Vận Khí</color>, thi triển <color=Highlight>Xung Quyền</color> tấn công mục tiêu, gây <color=Wind>Sát thương Khí Động</color>;\n·Tiểu Chu Thiên: Nhận được khiên Vận Khí tầng 2, và <color=Highlight>Chấn Khí</color> tấn công mục tiêu, gây <color=Wind>Sát thương Khí Động</color>. Khi gián đoạn <color=Highlight>Trạng thái Vận Khí</color>, thi triển <color=Highlight>Thôi Thủ</color> tấn công mục tiêu, gây <color=Wind>Sát thương Khí Động</color>;\n·Đại Chu Thiên·Nội: Nhận được khiên Vận Khí tầng 3, và <color=Highlight>Chấn Khí</color> tấn công mục tiêu, gây <color=Wind>Sát thương Khí Động</color>. Khi gián đoạn <color=Highlight>Trạng thái Vận Khí</color>, thi triển <color=Highlight>Thôi Thủ</color> tấn công mục tiêu, gây <color=Wind>Sát thương Khí Động</color>;\n·Đại Chu Thiên·Ngoại: Nhận được khiên Vận Khí tầng 4, và <color=Highlight>Chấn Khí</color> tấn công mục tiêu, gây <color=Wind>Sát thương Khí Động</color>;\n·Khi buông <color=Highlight>Đánh Thường</color>, gián đoạn <color=Highlight>Trạng thái Vận Khí</color>, và tiêu hao tất cả [Khí];\n·Khi tiêu hao hết tất cả [Khí], kết thúc <color=Highlight>Trạng thái Vận Khí</color>;\n<size=10></size>\nKhi <color=Highlight>Trạng thái Vận Khí</color> kết thúc, nhận lại khiên của Chu Thiên tương ứng dựa trên giai đoạn Chu Thiên;\nTrong thời gian khiên nhận được từ <color=Highlight>Đánh Mạnh: Hỗn Nguyên Khí Toàn</color> duy trì, mỗi {1} giây hồi phục sinh lực cho nhân vật đang xuất chiến trong đội;\n<size=10></size>\n<size=40><color=Title>Quy tắc nhận Khí</color></size>\nGiới hạn [Khí] là {2} điểm.\nKhi Đánh Thường <color=Highlight>Phong Nghi Quyền Thuật</color> trúng mục tiêu, nhận được [Khí].\nKhi thi triển Kỹ Năng Cộng Hưởng <color=Highlight>Tĩnh Khí Tuần Hành</color>, nhận được [Khí].\nKhi Kỹ Năng Cộng Hưởng <color=Highlight>Hành Khí Phản Công</color> hoặc Kỹ Năng Cộng Hưởng <color=Highlight>Giáng Khí Phản Công</color> trúng mục tiêu, nhận được [Khí].\nKhi Kỹ Năng Biến Tấu <color=Highlight>Chưởng Tức Chi Yếu</color> trúng mục tiêu, nhận được [Khí].

#### `lang_multi_text.db||MultiText||Skill_1001907_SkillResume`
- Cũ: <size=40><color=Title>Đánh Mạnh: Hỗn Nguyên Khí Toàn</color></size>\nKhi [Khí] đạt giới hạn, nhấn giữ <color=Highlight>Đánh Thường</color>, bước vào <color=Highlight>Trạng thái Vận Khí</color>.\n<size=10></size>\n<size=40><color=Title>Trạng thái Vận Khí</color></size>\nTiếp tục tiêu hao [Khí], và liên tục tấn công mục tiêu gần đó, gây <color=Wind>Sát thương Khí Động</color>;\nTheo thời gian <color=Highlight>Trạng thái Vận Khí</color> kéo dài, Giám Tâm có thể gây sát thương cao hơn, và nhận được khiên mạnh hơn.\nKhi <color=Highlight>Trạng thái Vận Khí</color> kết thúc, dựa trên thời gian duy trì trạng thái, nhận lại khiên của Chu Thiên tương ứng;\nTrong thời gian khiên nhận được từ <color=Highlight>Đánh Mạnh: Hỗn Nguyên Khí Toàn</color> duy trì, mỗi {1} giây hồi phục sinh lực cho nhân vật đang xuất chiến trong đội;\n<size=10></size>\n<size=40><color=Title>Quy tắc nhận Khí</color></size>\nGiới hạn [Khí] là {2} điểm.\nĐường lối nhận Khí: <color=Highlight>Đánh Thường</color>, <color=Highlight>Kỹ Năng Cộng Hưởng</color>, <color=Highlight>Kỹ Năng Biến Tấu</color>.
- Mới: <size=40><color=Title>Đánh Mạnh: Hỗn Nguyên Khí Toàn</color></size>\nKhi [Khí] đạt giới hạn, nhấn giữ <color=Highlight>Đánh Thường</color>, bước vào <color=Highlight>Trạng thái Vận Khí</color>.\n<size=10></size>\n<size=40><color=Title>Trạng thái Vận Khí</color></size>\nTiếp tục tiêu hao [Khí], và liên tục tấn công mục tiêu gần đó, gây <color=Wind>Sát thương Khí Động</color>;\nTheo thời gian <color=Highlight>Trạng thái Vận Khí</color> kéo dài, Jianxin có thể gây sát thương cao hơn, và nhận được khiên mạnh hơn.\nKhi <color=Highlight>Trạng thái Vận Khí</color> kết thúc, dựa trên thời gian duy trì trạng thái, nhận lại khiên của Chu Thiên tương ứng;\nTrong thời gian khiên nhận được từ <color=Highlight>Đánh Mạnh: Hỗn Nguyên Khí Toàn</color> duy trì, mỗi {1} giây hồi phục sinh lực cho nhân vật đang xuất chiến trong đội;\n<size=10></size>\n<size=40><color=Title>Quy tắc nhận Khí</color></size>\nGiới hạn [Khí] là {2} điểm.\nĐường lối nhận Khí: <color=Highlight>Đánh Thường</color>, <color=Highlight>Kỹ Năng Cộng Hưởng</color>, <color=Highlight>Kỹ Năng Biến Tấu</color>.

#### `lang_multi_text.db||MultiText||Skill_1001909_MultiSkillDescribe_1.1`
- Cũ: Nhân vật trong đội gần đó kích hoạt Kỹ Năng Hiệp Tấu của Giám Tâm sẽ được tăng {0} Sát thương Giải Phóng Cộng Hưởng, hiệu quả kéo dài {1} giây, nếu chuyển sang nhân vật khác thì hiệu quả này sẽ kết thúc sớm.
- Mới: Nhân vật trong đội gần đó kích hoạt Kỹ Năng Hiệp Tấu của Jianxin sẽ được tăng {0} Sát thương Giải Phóng Cộng Hưởng, hiệu quả kéo dài {1} giây, nếu chuyển sang nhân vật khác thì hiệu quả này sẽ kết thúc sớm.

#### `lang_multi_text.db||MultiText||Skill_1002202_SkillDescribe`
- Cũ: Gây <color=Ice>Sát thương Ngưng Băng</color>. Nếu Chiết Chi có ít nhất 60 điểm [<te href=850028>Linh Vận</te>], sẽ tiêu hao 60 điểm [<te href=850028>Linh Vận</te>], triệu hồi <color=Highlight><te href=850026>Hạc Ảnh</te>.Trái</color> và <color=Highlight><te href=850026>Hạc Ảnh</te>.Phải</color>.\n·Khi nhấn ngắn trên mặt đất, <te href=850026>Hạc Ảnh</te> sẽ được triệu hồi trên mặt đất.\n·Khi nhấn giữ trên mặt đất hoặc nhấn ngắn trên không, <te href=850026>Hạc Ảnh</te> sẽ được triệu hồi trên không.
- Mới: Gây <color=Ice>Sát thương Ngưng Băng</color>. Nếu Zhezhi có ít nhất 60 điểm [<te href=850028>Linh Vận</te>], sẽ tiêu hao 60 điểm [<te href=850028>Linh Vận</te>], triệu hồi <color=Highlight><te href=850026>Hạc Ảnh</te>.Trái</color> và <color=Highlight><te href=850026>Hạc Ảnh</te>.Phải</color>.\n·Khi nhấn ngắn trên mặt đất, <te href=850026>Hạc Ảnh</te> sẽ được triệu hồi trên mặt đất.\n·Khi nhấn giữ trên mặt đất hoặc nhấn ngắn trên không, <te href=850026>Hạc Ảnh</te> sẽ được triệu hồi trên không.

#### `lang_multi_text.db||MultiText||Skill_1002202_SkillResume`
- Cũ: Gây <color=Ice>Sát thương Ngưng Băng</color>. Nếu Chiết Chi có ít nhất 60 điểm [Linh Vận], sẽ tiêu hao 60 điểm [Linh Vận], triệu hồi 2 <color=Highlight>Hạc Ảnh</color>
- Mới: Gây <color=Ice>Sát thương Ngưng Băng</color>. Nếu Zhezhi có ít nhất 60 điểm [Linh Vận], sẽ tiêu hao 60 điểm [Linh Vận], triệu hồi 2 <color=Highlight>Hạc Ảnh</color>

#### `lang_multi_text.db||MultiText||Skill_1002203_SkillDescribe`
- Cũ: Chiết Chi triệu hồi <color=Highlight>Mặc Hạc</color> hỗ trợ chiến đấu.\nCó thể thi triển trên không.\n<size=10> </size>\n<size=40><color=Title>Mặc Hạc</color></size>\nKhi nhân vật đang xuất chiến trong đội gây sát thương, sẽ triệu hồi <color=Highlight>Mặc Hạc</color> tiến hành tấn công phối hợp vào mục tiêu, gây <color=Ice>Sát thương Ngưng Băng</color>, sát thương lần này là sát thương Đánh Thường.\n·Trong {0} giây tiếp theo sau khi gây sát thương, mỗi giây có thể triệu hồi 1 con <color=Highlight>Mặc Hạc</color>, hiệu quả này mỗi giây có thể kích hoạt 1 lần. Sát thương do Mặc Hạc gây ra sẽ không kích hoạt hiệu quả này.\n·<color=Highlight>Mặc Hạc</color> mỗi giây có thể triệu hồi tối đa {1} con, có thể triệu hồi tổng cộng {2} con.\n·Hiệu quả duy trì {3} giây, hoặc duy trì đến khi <color=Highlight>Mặc Hạc</color> đạt số lượng triệu hồi tối đa.
- Mới: Zhezhi triệu hồi <color=Highlight>Mặc Hạc</color> hỗ trợ chiến đấu.\nCó thể thi triển trên không.\n<size=10> </size>\n<size=40><color=Title>Mặc Hạc</color></size>\nKhi nhân vật đang xuất chiến trong đội gây sát thương, sẽ triệu hồi <color=Highlight>Mặc Hạc</color> tiến hành tấn công phối hợp vào mục tiêu, gây <color=Ice>Sát thương Ngưng Băng</color>, sát thương lần này là sát thương Đánh Thường.\n·Trong {0} giây tiếp theo sau khi gây sát thương, mỗi giây có thể triệu hồi 1 con <color=Highlight>Mặc Hạc</color>, hiệu quả này mỗi giây có thể kích hoạt 1 lần. Sát thương do Mặc Hạc gây ra sẽ không kích hoạt hiệu quả này.\n·<color=Highlight>Mặc Hạc</color> mỗi giây có thể triệu hồi tối đa {1} con, có thể triệu hồi tổng cộng {2} con.\n·Hiệu quả duy trì {3} giây, hoặc duy trì đến khi <color=Highlight>Mặc Hạc</color> đạt số lượng triệu hồi tối đa.

#### `lang_multi_text.db||MultiText||Skill_1002203_SkillResume`
- Cũ: Chiết Chi triệu hồi <color=Highlight>Mặc Hạc</color> hỗ trợ chiến đấu.\n<size=10></size>\n<size=40><color=Title>Mặc Hạc</color></size>\nKhi nhân vật đang xuất chiến trong đội gây sát thương, sẽ triệu hồi <color=Highlight>Mặc Hạc</color> tiến hành tấn công phối hợp vào mục tiêu, gây <color=Ice>Sát thương Ngưng Băng</color>.
- Mới: Zhezhi triệu hồi <color=Highlight>Mặc Hạc</color> hỗ trợ chiến đấu.\n<size=10></size>\n<size=40><color=Title>Mặc Hạc</color></size>\nKhi nhân vật đang xuất chiến trong đội gây sát thương, sẽ triệu hồi <color=Highlight>Mặc Hạc</color> tiến hành tấn công phối hợp vào mục tiêu, gây <color=Ice>Sát thương Ngưng Băng</color>.

#### `lang_multi_text.db||MultiText||Skill_1002205_MultiSkillDescribe_1.1`
- Cũ: Nhân vật trong đội gần đó kích hoạt Kỹ Năng Hiệp Tấu của Chiết Chi sẽ được hồi {0} điểm năng lượng Cộng Hưởng.
- Mới: Nhân vật trong đội gần đó kích hoạt Kỹ Năng Hiệp Tấu của Zhezhi sẽ được hồi {0} điểm năng lượng Cộng Hưởng.

#### `lang_multi_text.db||MultiText||Skill_1002207_SkillDescribe`
- Cũ: <size=40><color=Title>Hạc Ảnh</color></size>\nKhi Chiết Chi thi triển Kỹ Năng Cộng Hưởng <color=Highlight>Dĩ Hình Tả Thần</color> hoặc Đánh Mạnh <color=Highlight>Cấu Hình</color>, tiêu hao [Linh Vận] có thể triệu hồi <color=Highlight>Hạc Ảnh</color>.\n<color=Highlight>Hạc Ảnh</color> chia thành 3 loại <color=Highlight>Hạc Ảnh·Trái</color>, <color=Highlight>Hạc Ảnh·Giữa</color>, <color=Highlight>Hạc Ảnh·Phải</color>, mỗi loại tồn tại tối đa 1 bức, duy trì {0} giây.\n<size=10> </size>\n<size=40><color=Title>Đánh Mạnh·Cấu Hình</color></size>\nKhi tiến hành 5 thao tác dưới đây, có thể tiêu hao thể lực thi triển kỹ năng này tấn công mục tiêu, gây <color=Ice>Sát thương Ngưng Băng</color>.\n·Nhấn giữ <color=Highlight>Đánh Thường</color> trong một khoảng thời gian nhất định sau <color=Highlight>Đánh Thường đoạn thứ 3</color>\n·Nhấn ngắn <color=Highlight>Đánh Thường</color> trong một khoảng thời gian nhất định sau khi thi triển Kỹ Năng Cộng Hưởng <color=Highlight>Dĩ Hình Tả Thần</color>\n·Nhấn giữ <color=Highlight>Đánh Thường</color> trong một khoảng thời gian nhất định sau khi thi triển Kỹ Năng Cộng Hưởng <color=Highlight>Thần Lai Chi Bút</color>, Kỹ Năng Cộng Hưởng <color=Highlight>Cực Ý.Thần Lai Chi Bút</color>\n·Nhấn giữ <color=Highlight>Đánh Thường</color> khi đang ở trạng thái trên không\n·Nhấn giữ <color=Highlight>Đánh Thường</color> sau khi <color=Highlight>Né Tránh</color> thành công\nNếu khi thi triển Chiết Chi có ít nhất 30 điểm [Linh Vận], sẽ tiêu hao 30 điểm [Linh Vận] để triệu hồi <color=Highlight>Hạc Ảnh·Giữa</color> trên sân.\n<size=10> </size>\n<size=40><color=Title>Kỹ Năng Cộng Hưởng·Thần Lai Chi Bút</color></size>\nKhi gần Chiết Chi có <color=Highlight>Hạc Ảnh</color>, Kỹ Năng Cộng Hưởng thay thế bằng <color=Highlight>Thần Lai Chi Bút</color>. Khi thi triển:\n·Di chuyển đến vị trí của <color=Highlight>Hạc Ảnh</color> và xóa nó, sau đó triệu hồi bạch hạc tấn công mục tiêu, gây <color=Ice>Sát thương Ngưng Băng</color>, sát thương lần này là sát thương Đánh Thường. Nếu di chuyển đến <color=Highlight>Hạc Ảnh</color> đang ở trên không, có thể đặt lại số lần Né Tránh trên không.\n·Nhận 1 tầng [Cực Ý], duy trì {1} giây, có thể cộng dồn 2 tầng.\n·Có thể thi triển trên không.\n<size=10> </size>\n<size=40><color=Title>Kỹ Năng Cộng Hưởng·Cực Ý.Thần Lai Chi Bút</color></size>\nKhi gần Chiết Chi có <color=Highlight>Hạc Ảnh</color>, và số tầng [Cực Ý] là 2, <color=Highlight>Thần Lai Chi Bút</color> thay thế bằng <color=Highlight>Cực Ý.Thần Lai Chi Bút</color>. Khi thi triển:\n·Xóa tất cả [Cực Ý].\n·Di chuyển đến vị trí của <color=Highlight>Hạc Ảnh</color> và xóa nó, sau đó triệu hồi bạch hạc tấn công mục tiêu, gây <color=Ice>Sát thương Ngưng Băng</color> cao hơn, sát thương lần này là sát thương Đánh Thường, đồng thời làm tăng {2} sát thương Đánh Thường của Chiết Chi, duy trì {3} giây. Nếu di chuyển đến <color=Highlight>Hạc Ảnh</color> đang ở trên không, có thể đặt lại số lần Né Tránh trên không.\n·Có thể thi triển trên không.\n<size=10> </size>\n<size=40><color=Title>Quy tắc nhận [Linh Vận]</color></size>\nGiới hạn [Linh Vận] là 90 điểm.\nĐánh Thường gây sát thương có thể hồi phục [Linh Vận].\nThi triển Kỹ Năng Biến Tấu có thể hồi phục [Linh Vận].
- Mới: <size=40><color=Title>Hạc Ảnh</color></size>\nKhi Zhezhi thi triển Kỹ Năng Cộng Hưởng <color=Highlight>Dĩ Hình Tả Thần</color> hoặc Đánh Mạnh <color=Highlight>Cấu Hình</color>, tiêu hao [Linh Vận] có thể triệu hồi <color=Highlight>Hạc Ảnh</color>.\n<color=Highlight>Hạc Ảnh</color> chia thành 3 loại <color=Highlight>Hạc Ảnh·Trái</color>, <color=Highlight>Hạc Ảnh·Giữa</color>, <color=Highlight>Hạc Ảnh·Phải</color>, mỗi loại tồn tại tối đa 1 bức, duy trì {0} giây.\n<size=10> </size>\n<size=40><color=Title>Đánh Mạnh·Cấu Hình</color></size>\nKhi tiến hành 5 thao tác dưới đây, có thể tiêu hao thể lực thi triển kỹ năng này tấn công mục tiêu, gây <color=Ice>Sát thương Ngưng Băng</color>.\n·Nhấn giữ <color=Highlight>Đánh Thường</color> trong một khoảng thời gian nhất định sau <color=Highlight>Đánh Thường đoạn thứ 3</color>\n·Nhấn ngắn <color=Highlight>Đánh Thường</color> trong một khoảng thời gian nhất định sau khi thi triển Kỹ Năng Cộng Hưởng <color=Highlight>Dĩ Hình Tả Thần</color>\n·Nhấn giữ <color=Highlight>Đánh Thường</color> trong một khoảng thời gian nhất định sau khi thi triển Kỹ Năng Cộng Hưởng <color=Highlight>Thần Lai Chi Bút</color>, Kỹ Năng Cộng Hưởng <color=Highlight>Cực Ý.Thần Lai Chi Bút</color>\n·Nhấn giữ <color=Highlight>Đánh Thường</color> khi đang ở trạng thái trên không\n·Nhấn giữ <color=Highlight>Đánh Thường</color> sau khi <color=Highlight>Né Tránh</color> thành công\nNếu khi thi triển Zhezhi có ít nhất 30 điểm [Linh Vận], sẽ tiêu hao 30 điểm [Linh Vận] để triệu hồi <color=Highlight>Hạc Ảnh·Giữa</color> trên sân.\n<size=10> </size>\n<size=40><color=Title>Kỹ Năng Cộng Hưởng·Thần Lai Chi Bút</color></size>\nKhi gần Zhezhi có <color=Highlight>Hạc Ảnh</color>, Kỹ Năng Cộng Hưởng thay thế bằng <color=Highlight>Thần Lai Chi Bút</color>. Khi thi triển:\n·Di chuyển đến vị trí của <color=Highlight>Hạc Ảnh</color> và xóa nó, sau đó triệu hồi bạch hạc tấn công mục tiêu, gây <color=Ice>Sát thương Ngưng Băng</color>, sát thương lần này là sát thương Đánh Thường. Nếu di chuyển đến <color=Highlight>Hạc Ảnh</color> đang ở trên không, có thể đặt lại số lần Né Tránh trên không.\n·Nhận 1 tầng [Cực Ý], duy trì {1} giây, có thể cộng dồn 2 tầng.\n·Có thể thi triển trên không.\n<size=10> </size>\n<size=40><color=Title>Kỹ Năng Cộng Hưởng·Cực Ý.Thần Lai Chi Bút</color></size>\nKhi gần Zhezhi có <color=Highlight>Hạc Ảnh</color>, và số tầng [Cực Ý] là 2, <color=Highlight>Thần Lai Chi Bút</color> thay thế bằng <color=Highlight>Cực Ý.Thần Lai Chi Bút</color>. Khi thi triển:\n·Xóa tất cả [Cực Ý].\n·Di chuyển đến vị trí của <color=Highlight>Hạc Ảnh</color> và xóa nó, sau đó triệu hồi bạch hạc tấn công mục tiêu, gây <color=Ice>Sát thương Ngưng Băng</color> cao hơn, sát thương lần này là sát thương Đánh Thường, đồng thời làm tăng {2} sát thương Đánh Thường của Zhezhi, duy trì {3} giây. Nếu di chuyển đến <color=Highlight>Hạc Ảnh</color> đang ở trên không, có thể đặt lại số lần Né Tránh trên không.\n·Có thể thi triển trên không.\n<size=10> </size>\n<size=40><color=Title>Quy tắc nhận [Linh Vận]</color></size>\nGiới hạn [Linh Vận] là 90 điểm.\nĐánh Thường gây sát thương có thể hồi phục [Linh Vận].\nThi triển Kỹ Năng Biến Tấu có thể hồi phục [Linh Vận].

#### `lang_multi_text.db||MultiText||Skill_1002207_SkillResume`
- Cũ: <size=40><color=Title>Hạc Ảnh</color></size>\nKhi Chiết Chi thi triển Kỹ Năng Cộng Hưởng <color=Highlight>Dĩ Hình Tả Thần</color> hoặc Đánh Mạnh <color=Highlight>Cấu Hình</color>, tiêu hao [Linh Vận] có thể triệu hồi <color=Highlight>Hạc Ảnh</color>.\n\n<size=40><color=Title>Đánh Mạnh·Cấu Hình</color></size>\nKhi tiến hành 5 thao tác dưới đây, có thể tiêu hao thể lực, gây <color=Ice>Sát thương Ngưng Băng</color>.\n·Nhấn giữ <color=Highlight>Đánh Thường</color> trong một khoảng thời gian nhất định sau <color=Highlight>Đánh Thường đoạn thứ 3</color>\n·Nhấn ngắn <color=Highlight>Đánh Thường</color> trong một khoảng thời gian nhất định sau khi thi triển Kỹ Năng Cộng Hưởng <color=Highlight>Dĩ Hình Tả Thần</color>\n·Nhấn giữ <color=Highlight>Đánh Thường</color> trong một khoảng thời gian nhất định sau khi thi triển Kỹ Năng Cộng Hưởng <color=Highlight>Thần Lai Chi Bút</color>, Kỹ Năng Cộng Hưởng <color=Highlight>Cực Ý.Thần Lai Chi Bút</color>\n·Nhấn giữ <color=Highlight>Đánh Thường</color> khi đang ở trạng thái trên không\n·Nhấn giữ <color=Highlight>Đánh Thường</color> sau khi <color=Highlight>Né Tránh</color> thành công\nNếu khi thi triển Chiết Chi có ít nhất 30 điểm [Linh Vận], sẽ tiêu hao 30 điểm [Linh Vận] để triệu hồi <color=Highlight>Hạc Ảnh·Giữa</color> trên sân.\n\n<size=40><color=Title>Kỹ Năng Cộng Hưởng·Thần Lai Chi Bút</color></size>\nKhi có <color=Highlight>Hạc Ảnh</color>, Kỹ Năng Cộng Hưởng thay thế bằng <color=Highlight>Thần Lai Chi Bút</color>. Khi thi triển:\n·Gây <color=Ice>Sát thương Ngưng Băng</color>.\n·Nhận 1 tầng [Cực Ý].\n\n<size=40><color=Title>Kỹ Năng Cộng Hưởng·Cực Ý.Thần Lai Chi Bút</color></size>\nKhi có <color=Highlight>Hạc Ảnh</color>, và số tầng [Cực Ý] là 2, <color=Highlight>Thần Lai Chi Bút</color> thay thế bằng <color=Highlight>Cực Ý.Thần Lai Chi Bút</color>. Khi thi triển:\n·Gây <color=Ice>Sát thương Ngưng Băng</color> cao hơn, và làm tăng sát thương Đánh Thường của Chiết Chi.\n\n<size=10></size>\n<size=40><color=Title>Quy tắc nhận [Linh Vận]</color></size>\nGiới hạn [Linh Vận] là 90 điểm.\nĐường lối nhận [Linh Vận]: <color=Highlight>Đánh Thường</color>, <color=Highlight>Kỹ Năng Biến Tấu</color>.
- Mới: <size=40><color=Title>Hạc Ảnh</color></size>\nKhi Zhezhi thi triển Kỹ Năng Cộng Hưởng <color=Highlight>Dĩ Hình Tả Thần</color> hoặc Đánh Mạnh <color=Highlight>Cấu Hình</color>, tiêu hao [Linh Vận] có thể triệu hồi <color=Highlight>Hạc Ảnh</color>.\n\n<size=40><color=Title>Đánh Mạnh·Cấu Hình</color></size>\nKhi tiến hành 5 thao tác dưới đây, có thể tiêu hao thể lực, gây <color=Ice>Sát thương Ngưng Băng</color>.\n·Nhấn giữ <color=Highlight>Đánh Thường</color> trong một khoảng thời gian nhất định sau <color=Highlight>Đánh Thường đoạn thứ 3</color>\n·Nhấn ngắn <color=Highlight>Đánh Thường</color> trong một khoảng thời gian nhất định sau khi thi triển Kỹ Năng Cộng Hưởng <color=Highlight>Dĩ Hình Tả Thần</color>\n·Nhấn giữ <color=Highlight>Đánh Thường</color> trong một khoảng thời gian nhất định sau khi thi triển Kỹ Năng Cộng Hưởng <color=Highlight>Thần Lai Chi Bút</color>, Kỹ Năng Cộng Hưởng <color=Highlight>Cực Ý.Thần Lai Chi Bút</color>\n·Nhấn giữ <color=Highlight>Đánh Thường</color> khi đang ở trạng thái trên không\n·Nhấn giữ <color=Highlight>Đánh Thường</color> sau khi <color=Highlight>Né Tránh</color> thành công\nNếu khi thi triển Zhezhi có ít nhất 30 điểm [Linh Vận], sẽ tiêu hao 30 điểm [Linh Vận] để triệu hồi <color=Highlight>Hạc Ảnh·Giữa</color> trên sân.\n\n<size=40><color=Title>Kỹ Năng Cộng Hưởng·Thần Lai Chi Bút</color></size>\nKhi có <color=Highlight>Hạc Ảnh</color>, Kỹ Năng Cộng Hưởng thay thế bằng <color=Highlight>Thần Lai Chi Bút</color>. Khi thi triển:\n·Gây <color=Ice>Sát thương Ngưng Băng</color>.\n·Nhận 1 tầng [Cực Ý].\n\n<size=40><color=Title>Kỹ Năng Cộng Hưởng·Cực Ý.Thần Lai Chi Bút</color></size>\nKhi có <color=Highlight>Hạc Ảnh</color>, và số tầng [Cực Ý] là 2, <color=Highlight>Thần Lai Chi Bút</color> thay thế bằng <color=Highlight>Cực Ý.Thần Lai Chi Bút</color>. Khi thi triển:\n·Gây <color=Ice>Sát thương Ngưng Băng</color> cao hơn, và làm tăng sát thương Đánh Thường của Zhezhi.\n\n<size=10></size>\n<size=40><color=Title>Quy tắc nhận [Linh Vận]</color></size>\nGiới hạn [Linh Vận] là 90 điểm.\nĐường lối nhận [Linh Vận]: <color=Highlight>Đánh Thường</color>, <color=Highlight>Kỹ Năng Biến Tấu</color>.

#### `lang_multi_text.db||MultiText||Skill_1002209_MultiSkillDescribe_1.1`
- Cũ: Nhân vật trong đội gần đó kích hoạt Kỹ Năng Hiệp Tấu của Chiết Chi sẽ được tăng {0} Sát thương Ngưng Băng, tăng {1} Sát thương Kỹ Năng Cộng Hưởng, hiệu quả kéo dài {2} giây, nếu chuyển sang nhân vật khác thì hiệu quả này sẽ kết thúc sớm.
- Mới: Nhân vật trong đội gần đó kích hoạt Kỹ Năng Hiệp Tấu của Zhezhi sẽ được tăng {0} Sát thương Ngưng Băng, tăng {1} Sát thương Kỹ Năng Cộng Hưởng, hiệu quả kéo dài {2} giây, nếu chuyển sang nhân vật khác thì hiệu quả này sẽ kết thúc sớm.

#### `lang_resonate_chain.db||ResonantChain||1092`
- Cũ: <color=#ffffff>Khi Tấn Công Phối Hợp của <color=#f4d582><ano=Resonance Skill>Kỹ Năng Cộng Hưởng</ano>·Khô Dạ Chi Khiết</color> đánh trúng mục tiêu, dựa trên 15% Phòng Thủ của Uyên Vũ, tăng thêm sát thương.</color>
- Mới: <color=#ffffff>Khi Tấn Công Phối Hợp của <color=#f4d582><ano=Resonance Skill>Kỹ Năng Cộng Hưởng</ano>·Khô Dạ Chi Khiết</color> đánh trúng mục tiêu, dựa trên 15% Phòng Thủ của Yuanwu, tăng thêm sát thương.</color>

#### `lang_resonate_chain.db||ResonantChain||1116`
- Cũ: <color=#ffffff>Khi <color=#f4d582>Giải Phóng Cộng Hưởng·Tịch Thổ Trùng Minh</color> đánh trúng mục tiêu, nếu Sinh Mệnh của Uyên Vũ trên 50%, nhận khiên dựa trên 150% Phòng Ngự của Uyên Vũ, kéo dài 12 giây.</color>
- Mới: <color=#ffffff>Khi <color=#f4d582>Giải Phóng Cộng Hưởng·Tịch Thổ Trùng Minh</color> đánh trúng mục tiêu, nếu Sinh Mệnh của Yuanwu trên 50%, nhận khiên dựa trên 150% Phòng Ngự của Yuanwu, kéo dài 12 giây.</color>

#### `lang_resonate_chain.db||ResonantChain||21`
- Cũ: <color=#ffffff>Cộng <ano=Aero>Sát Thương Khí Động</ano> tăng 3%.</color>
- Mới: <color=#ffffff>Cộng <ano=Aero>Khí Động</ano> tăng 3%.</color>

#### `lang_resonate_chain.db||ResonantChain||225`
- Cũ: <color=#ffffff>Cộng <ano=Glacio>Sát Thương Ngưng Băng</ano> tăng 3%.</color>
- Mới: <color=#ffffff>Cộng <ano=Glacio>Ngưng Băng</ano> tăng 3%.</color>

#### `lang_resonate_chain.db||ResonantChain||237`
- Cũ: <color=#ffffff>Cộng <ano=Glacio>Sát Thương Ngưng Băng</ano> tăng 3%.</color>
- Mới: <color=#ffffff>Cộng <ano=Glacio>Ngưng Băng</ano> tăng 3%.</color>

#### `lang_resonate_chain.db||ResonantChain||273`
- Cũ: <color=#ffffff>Cộng <ano=Glacio>Sát Thương Ngưng Băng</ano> tăng 3%.</color>
- Mới: <color=#ffffff>Cộng <ano=Glacio>Ngưng Băng</ano> tăng 3%.</color>

#### `lang_resonate_chain.db||ResonantChain||285`
- Cũ: <color=#ffffff>Cộng <ano=Glacio>Sát Thương Ngưng Băng</ano> tăng 3%.</color>
- Mới: <color=#ffffff>Cộng <ano=Glacio>Ngưng Băng</ano> tăng 3%.</color>

#### `lang_resonate_chain.db||ResonantChain||33`
- Cũ: <color=#ffffff>Cộng <ano=Aero>Sát Thương Khí Động</ano> tăng 3%.</color>
- Mới: <color=#ffffff>Cộng <ano=Aero>Khí Động</ano> tăng 3%.</color>

#### `lang_resonate_chain.db||ResonantChain||45`
- Cũ: <color=#ffffff>Cộng <ano=Aero>Sát Thương Khí Động</ano> tăng 3%.</color>
- Mới: <color=#ffffff>Cộng <ano=Aero>Khí Động</ano> tăng 3%.</color>

#### `lang_resonate_chain.db||ResonantChain||57`
- Cũ: <color=#ffffff>Cộng <ano=Aero>Sát Thương Khí Động</ano> tăng 3%.</color>
- Mới: <color=#ffffff>Cộng <ano=Aero>Khí Động</ano> tăng 3%.</color>

#### `lang_resonate_chain.db||ResonantChain||69`
- Cũ: <color=#ffffff>Cộng <ano=Aero>Sát Thương Khí Động</ano> tăng 3%.</color>
- Mới: <color=#ffffff>Cộng <ano=Aero>Khí Động</ano> tăng 3%.</color>

#### `lang_resonate_chain.db||ResonantChain||9`
- Cũ: <color=#ffffff>Cộng <ano=Aero>Sát Thương Khí Động</ano> tăng 3%.</color>
- Mới: <color=#ffffff>Cộng <ano=Aero>Khí Động</ano> tăng 3%.</color>

#### `lang_skill.db||Skill||10`
- Cũ: <color=#ffffff>Sau khi sử dụng <color=#f4d582><ano=Coordinated Attack>Kỹ Năng Liên Kết</ano> · Tán Lam Lễ Tán</color>, Tăng Sát Thương <ano=Aero>Khí Động</ano> của Ương Ương tăng 15%, hiệu quả kéo dài 8 giây.</color>
- Mới: <color=#ffffff>Sau khi sử dụng <color=#f4d582><ano=Coordinated Attack>Kỹ Năng Liên Kết</ano> · Tán Lam Lễ Tán</color>, Tăng Sát Thương <ano=Aero>Khí Động</ano> của Yangyang tăng 15%, hiệu quả kéo dài 8 giây.</color>

#### `lang_skill.db||Skill||130`
- Cũ: <color=#ffffff><color=#d4bf5f><ano=Normal Attack>Đánh Thường</ano></color>\nVung kiếm khổng lồ, nhẹ nhàng tựa lông hồng, tiến hành tối đa 4 đoạn tấn công liên tiếp.\n\n<color=#d4bf5f><ano=Heavy Attack>Đánh Mạnh</ano></color>\nTiêu hao một lượng <ano=Stamina>Thể Lực</ano>, vào trạng thái <color=#f4d582>Huyền Vũ Thủ Thế</color>.\n\n<color=#d4bf5f>Huyền Vũ Thủ Thế</color>\nTrong trạng thái này, Đào Kỳ sẽ tập trung hơn vào phòng thủ, liên tục tiêu hao <ano=Stamina>Thể Lực</ano>, đổi lại sát thương phải nhận giảm.\nTrong thời gian Huyền Vũ Thủ Thế kéo dài, nếu Đào Kỳ bị tấn công, sẽ kích hoạt <color=#f4d582>Hậu Phát Chế Nhân</color>, phản kích mục tiêu.\nKhi tiêu hao hết Thể Lực, kết thúc trạng thái Huyền Vũ Thủ Thế, đồng thời lập tức phát động 1 đòn tấn công, gây <color=#e649a6>sát thương <ano=Havoc>Hủy Diệt</ano></color>.\n\n<color=#d4bf5f>Hậu Phát Chế Nhân</color>\nKhi kích hoạt thành công Hậu Phát Chế Nhân, Đào Kỳ có thể tiến hành tối đa 3 đoạn truy kích, gây <color=#e649a6>sát thương <ano=Havoc>Hủy Diệt</ano></color>.\nKhi thi triển Hậu Phát Chế Nhân, nếu sở hữu [Cương Nhu Hóa Thế], thì mỗi đoạn truy kích tiêu hao 1 điểm [Cương Nhu Hóa Thế], và kích hoạt <color=#f4d582>Mạch Cộng Hưởng · Thần Quy Phân Thọ</color>.\nSau khi thi triển <color=#f4d582><ano=Coordinated Attack>Kỹ Năng Liên Kết</ano> · Huề Công Thủ Trận</color>, sử dụng <color=#f4d582><ano=Normal Attack>Đánh Thường</ano></color>, có thể trực tiếp thi triển Hậu Phát Chế Nhân.\n\n<color=#d4bf5f>Tấn Công Trên Không</color>\nTiêu hao một lượng <ano=Stamina>Thể Lực</ano>, bật lên trên không lao xuống tấn công, gây <color=#e649a6>sát thương <ano=Havoc>Hủy Diệt</ano></color>.\n\n<color=#d4bf5f>Phản Kích Né Tránh</color>\nTrong một khoảng thời gian sau khi <color=#f4d582><ano=Dodge>Né Tránh</ano></color> thành công, sử dụng <color=#f4d582><ano=Normal Attack>Đánh Thường</ano></color>, sẽ tấn công mục tiêu, gây <color=#e649a6>sát thương <ano=Havoc>Hủy Diệt</ano></color>.</color>
- Mới: <color=#ffffff><color=#d4bf5f><ano=Normal Attack>Đánh Thường</ano></color>\nVung kiếm khổng lồ, nhẹ nhàng tựa lông hồng, tiến hành tối đa 4 đoạn tấn công liên tiếp.\n\n<color=#d4bf5f><ano=Heavy Attack>Đánh Mạnh</ano></color>\nTiêu hao một lượng <ano=Stamina>Thể Lực</ano>, vào trạng thái <color=#f4d582>Huyền Vũ Thủ Thế</color>.\n\n<color=#d4bf5f>Huyền Vũ Thủ Thế</color>\nTrong trạng thái này, Taoqi sẽ tập trung hơn vào phòng thủ, liên tục tiêu hao <ano=Stamina>Thể Lực</ano>, đổi lại sát thương phải nhận giảm.\nTrong thời gian Huyền Vũ Thủ Thế kéo dài, nếu Taoqi bị tấn công, sẽ kích hoạt <color=#f4d582>Hậu Phát Chế Nhân</color>, phản kích mục tiêu.\nKhi tiêu hao hết Thể Lực, kết thúc trạng thái Huyền Vũ Thủ Thế, đồng thời lập tức phát động 1 đòn tấn công, gây <color=#e649a6>sát thương <ano=Havoc>Hủy Diệt</ano></color>.\n\n<color=#d4bf5f>Hậu Phát Chế Nhân</color>\nKhi kích hoạt thành công Hậu Phát Chế Nhân, Taoqi có thể tiến hành tối đa 3 đoạn truy kích, gây <color=#e649a6>sát thương <ano=Havoc>Hủy Diệt</ano></color>.\nKhi thi triển Hậu Phát Chế Nhân, nếu sở hữu [Cương Nhu Hóa Thế], thì mỗi đoạn truy kích tiêu hao 1 điểm [Cương Nhu Hóa Thế], và kích hoạt <color=#f4d582>Mạch Cộng Hưởng · Thần Quy Phân Thọ</color>.\nSau khi thi triển <color=#f4d582><ano=Coordinated Attack>Kỹ Năng Liên Kết</ano> · Huề Công Thủ Trận</color>, sử dụng <color=#f4d582><ano=Normal Attack>Đánh Thường</ano></color>, có thể trực tiếp thi triển Hậu Phát Chế Nhân.\n\n<color=#d4bf5f>Tấn Công Trên Không</color>\nTiêu hao một lượng <ano=Stamina>Thể Lực</ano>, bật lên trên không lao xuống tấn công, gây <color=#e649a6>sát thương <ano=Havoc>Hủy Diệt</ano></color>.\n\n<color=#d4bf5f>Phản Kích Né Tránh</color>\nTrong một khoảng thời gian sau khi <color=#f4d582><ano=Dodge>Né Tránh</ano></color> thành công, sử dụng <color=#f4d582><ano=Normal Attack>Đánh Thường</ano></color>, sẽ tấn công mục tiêu, gây <color=#e649a6>sát thương <ano=Havoc>Hủy Diệt</ano></color>.</color>

#### `lang_skill.db||Skill||134`
- Cũ: <color=#ffffff>Sử dụng Bộ Khuếch Đại Dị Năng phát động Chân Vũ Phù Hộ, phát động 1 đòn tấn công dựa trên phòng thủ của Đào Kỳ đối với mục tiêu, gây <color=#e649a6>sát thương <ano=Havoc>Hủy Diệt</ano></color>, và hình thành trường lực đặc biệt xung quanh, kẻ địch nằm trong trường lực đặc biệt sẽ bị giảm tốc, hiệu quả kéo dài 2 giây.</color>
- Mới: <color=#ffffff>Sử dụng Bộ Khuếch Đại Dị Năng phát động Chân Vũ Phù Hộ, phát động 1 đòn tấn công dựa trên phòng thủ của Taoqi đối với mục tiêu, gây <color=#e649a6>sát thương <ano=Havoc>Hủy Diệt</ano></color>, và hình thành trường lực đặc biệt xung quanh, kẻ địch nằm trong trường lực đặc biệt sẽ bị giảm tốc, hiệu quả kéo dài 2 giây.</color>

#### `lang_skill.db||Skill||14`
- Cũ: <color=#ffffff><color=#d4bf5f>Trọng Kích · Phong Tập</color>\nKhi Ương Ương sở hữu 3 tiếng [Lưu Hưởng], sử dụng <ano=Heavy Attack>Đánh Mạnh</ano> có thể kích hoạt Phong Tập, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color> và đánh văng mục tiêu, sát thương lần này tính là <ano=Heavy Attack DMG>Sát Thương Trọng Kích</ano>.\n\n<color=#d4bf5f>Tấn Công Trên Không · Thích Vũ</color>\nKhi Ương Ương sở hữu 3 tiếng [Lưu Hưởng], sử dụng <color=#f4d582>Tấn Công Trên Không</color> trên không, sẽ tiêu hao toàn bộ [Lưu Hưởng], phát động tấn công liên tiếp, và bổ nhào từ trên không gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>. Sau khi tiếp đất, Ương Ương sẽ thu đao tấn công, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>, sát thương lần này tính là sát thương <ano=Normal Attack>Đánh Thường</ano>.\n\n<color=#d4bf5f>Quy Tắc Nhận Lưu Hưởng</color>\nKhi sử dụng <color=#f4d582><ano=Normal Attack>Đánh Thường</ano> đoạn 4</color> đánh trúng mục tiêu có thể nhận 1 tiếng [Lưu Hưởng].\nKhi sử dụng <color=#f4d582>Trọng Kích · Phong Ngâm</color> đánh trúng mục tiêu có thể nhận 1 tiếng [Lưu Hưởng].\nKhi sử dụng <color=#f4d582><ano=Resonance Skill>Kỹ Năng Cộng Hưởng</ano> · Lưu Phong Tại Vực</color> đánh trúng mục tiêu có thể nhận 1 tiếng [Lưu Hưởng].\nKhi sử dụng <color=#f4d582><ano=Coordinated Attack>Kỹ Năng Liên Kết</ano> · Tán Lam Lễ Tán</color> đánh trúng mục tiêu có thể nhận 1 tiếng [Lưu Hưởng].</color>
- Mới: <color=#ffffff><color=#d4bf5f>Trọng Kích · Phong Tập</color>\nKhi Yangyang sở hữu 3 tiếng [Lưu Hưởng], sử dụng <ano=Heavy Attack>Đánh Mạnh</ano> có thể kích hoạt Phong Tập, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color> và đánh văng mục tiêu, sát thương lần này tính là <ano=Heavy Attack DMG>Sát Thương Trọng Kích</ano>.\n\n<color=#d4bf5f>Tấn Công Trên Không · Thích Vũ</color>\nKhi Yangyang sở hữu 3 tiếng [Lưu Hưởng], sử dụng <color=#f4d582>Tấn Công Trên Không</color> trên không, sẽ tiêu hao toàn bộ [Lưu Hưởng], phát động tấn công liên tiếp, và bổ nhào từ trên không gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>. Sau khi tiếp đất, Yangyang sẽ thu đao tấn công, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>, sát thương lần này tính là sát thương <ano=Normal Attack>Đánh Thường</ano>.\n\n<color=#d4bf5f>Quy Tắc Nhận Lưu Hưởng</color>\nKhi sử dụng <color=#f4d582><ano=Normal Attack>Đánh Thường</ano> đoạn 4</color> đánh trúng mục tiêu có thể nhận 1 tiếng [Lưu Hưởng].\nKhi sử dụng <color=#f4d582>Trọng Kích · Phong Ngâm</color> đánh trúng mục tiêu có thể nhận 1 tiếng [Lưu Hưởng].\nKhi sử dụng <color=#f4d582><ano=Resonance Skill>Kỹ Năng Cộng Hưởng</ano> · Lưu Phong Tại Vực</color> đánh trúng mục tiêu có thể nhận 1 tiếng [Lưu Hưởng].\nKhi sử dụng <color=#f4d582><ano=Coordinated Attack>Kỹ Năng Liên Kết</ano> · Tán Lam Lễ Tán</color> đánh trúng mục tiêu có thể nhận 1 tiếng [Lưu Hưởng].</color>

#### `lang_skill.db||Skill||148`
- Cũ: <color=#ffffff><color=#d4bf5f>Vụ Hóa Ảo Ảnh</color>\nThi triển [Mê Vụ Toàn Oa] và 1 Vụ Hóa Ảo Ảnh để khiêu khích mục tiêu xung quanh, ảo ảnh sẽ kế thừa một phần sinh mệnh của Thu Thủy, và tạo ra 6 viên <color=#f4d582>Đạn Vụ Hóa</color> xung quanh ảo ảnh, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>.\n\n<color=#d4bf5f>Đạn Vụ Hóa</color>\nGây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>.</color>
- Mới: <color=#ffffff><color=#d4bf5f>Vụ Hóa Ảo Ảnh</color>\nThi triển [Mê Vụ Toàn Oa] và 1 Vụ Hóa Ảo Ảnh để khiêu khích mục tiêu xung quanh, ảo ảnh sẽ kế thừa một phần sinh mệnh của Aalto, và tạo ra 6 viên <color=#f4d582>Đạn Vụ Hóa</color> xung quanh ảo ảnh, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>.\n\n<color=#d4bf5f>Đạn Vụ Hóa</color>\nGây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>.</color>

#### `lang_skill.db||Skill||152`
- Cũ: <color=#ffffff><color=#f4d582>Đánh Mạnh</color> của Thu Thủy chắc chắn Bạo Kích, mỗi 30 giây có thể kích hoạt 1 lần.</color>
- Mới: <color=#ffffff><color=#f4d582>Đánh Mạnh</color> của Aalto chắc chắn Bạo Kích, mỗi 30 giây có thể kích hoạt 1 lần.</color>

#### `lang_skill.db||Skill||154`
- Cũ: <color=#ffffff>Khi Thu Thủy tiến vào <color=#f4d582>Cộng Hưởng Hồi Lộ · Trạng Thái Vụ Hóa</color> sẽ liên tục hồi phục Thể Lực.</color>
- Mới: <color=#ffffff>Khi Aalto tiến vào <color=#f4d582>Cộng Hưởng Hồi Lộ · Trạng Thái Vụ Hóa</color> sẽ liên tục hồi phục Thể Lực.</color>

#### `lang_skill.db||Skill||156`
- Cũ: <color=#ffffff>Thu Thủy thoắt ẩn thoắt hiện, tiến hành bắn liên tục tốc độ cao.</color>
- Mới: <color=#ffffff>Aalto thoắt ẩn thoắt hiện, tiến hành bắn liên tục tốc độ cao.</color>

#### `lang_skill.db||Skill||158`
- Cũ: <color=#ffffff><color=#d4bf5f>Bắn Vụ Hóa</color>\nKhi đạn của <color=#f4d582>Đánh Thường</color> và <color=#f4d582>Tấn Công Trên Không</color> xuyên qua [Xoáy Sương Mù], gây <color=#46c3d4ff>sát thương Khí Động</color>.\n\n<color=#d4bf5f>Trạng Thái Vụ Hóa</color>\nKhi Thu Thủy xuyên qua [Xoáy Sương Mù], sẽ tiến vào Trạng Thái Vụ Hóa, tốc độ di chuyển tăng.\nTrong thời gian này có thể liên tục tiêu hao [Giọt Sương], mỗi tiêu hao 1 điểm [Giọt Sương], sinh ra 1 viên <color=#f4d582>Kỹ Năng Cộng Hưởng · Đạn Vụ Hóa</color>, gây <color=#46c3d4ff>sát thương Khí Động</color>, sát thương lần này tính là sát thương Kỹ Năng Cộng Hưởng.\n\n<color=#d4bf5f>Quy Tắc Nhận Giọt Sương</color>\nKhi <color=#f4d582>Đánh Thường</color> và <color=#f4d582>Tấn Công Trên Không</color> xuyên qua [Xoáy Sương Mù] đánh trúng mục tiêu, hồi phục 1 điểm [Giọt Sương].</color>
- Mới: <color=#ffffff><color=#d4bf5f>Bắn Vụ Hóa</color>\nKhi đạn của <color=#f4d582>Đánh Thường</color> và <color=#f4d582>Tấn Công Trên Không</color> xuyên qua [Xoáy Sương Mù], gây <color=#46c3d4ff>sát thương Khí Động</color>.\n\n<color=#d4bf5f>Trạng Thái Vụ Hóa</color>\nKhi Aalto xuyên qua [Xoáy Sương Mù], sẽ tiến vào Trạng Thái Vụ Hóa, tốc độ di chuyển tăng.\nTrong thời gian này có thể liên tục tiêu hao [Giọt Sương], mỗi tiêu hao 1 điểm [Giọt Sương], sinh ra 1 viên <color=#f4d582>Kỹ Năng Cộng Hưởng · Đạn Vụ Hóa</color>, gây <color=#46c3d4ff>sát thương Khí Động</color>, sát thương lần này tính là sát thương Kỹ Năng Cộng Hưởng.\n\n<color=#d4bf5f>Quy Tắc Nhận Giọt Sương</color>\nKhi <color=#f4d582>Đánh Thường</color> và <color=#f4d582>Tấn Công Trên Không</color> xuyên qua [Xoáy Sương Mù] đánh trúng mục tiêu, hồi phục 1 điểm [Giọt Sương].</color>

#### `lang_skill.db||Skill||166`
- Cũ: <color=#ffffff>Sau khi thi triển Thương Cừ Bát Hoang · Mưu Định, Kỵ Viêm tiến vào <color=#f4d582>Trạng Thái Phá Trận</color>.\n\n<color=#d4bf5f>Trạng Thái Phá Trận</color>\nTrong Trạng Thái Phá Trận, sử dụng <color=#f4d582>Đánh Thường</color> hoặc <color=#f4d582>Đánh Mạnh</color>, sẽ thi triển <color=#f4d582>Phá Trận Thương</color>.\n\n<color=#d4bf5f>Đánh Mạnh · Phá Trận Thương</color>\nTiến hành tối đa 3 đoạn tấn công liên tiếp, gây <color=#46c3d4ff>sát thương Khí Động</color>, sát thương lần này tính là Sát Thương Đánh Mạnh.</color>
- Mới: <color=#ffffff>Sau khi thi triển Thương Cừ Bát Hoang · Mưu Định, Jiyan tiến vào <color=#f4d582>Trạng Thái Phá Trận</color>.\n\n<color=#d4bf5f>Trạng Thái Phá Trận</color>\nTrong Trạng Thái Phá Trận, sử dụng <color=#f4d582>Đánh Thường</color> hoặc <color=#f4d582>Đánh Mạnh</color>, sẽ thi triển <color=#f4d582>Phá Trận Thương</color>.\n\n<color=#d4bf5f>Đánh Mạnh · Phá Trận Thương</color>\nTiến hành tối đa 3 đoạn tấn công liên tiếp, gây <color=#46c3d4ff>sát thương Khí Động</color>, sát thương lần này tính là Sát Thương Đánh Mạnh.</color>

#### `lang_skill.db||Skill||170`
- Cũ: <color=#ffffff>Khi đòn tấn công đánh trúng mục tiêu, Bạo Kích của Kỵ Viêm tăng 1%, hiệu ứng kéo dài 8 giây, có thể cộng dồn 15 tầng.</color>
- Mới: <color=#ffffff>Khi đòn tấn công đánh trúng mục tiêu, Bạo Kích của Jiyan tăng 1%, hiệu ứng kéo dài 8 giây, có thể cộng dồn 15 tầng.</color>

#### `lang_skill.db||Skill||174`
- Cũ: <color=#ffffff>Khi thi triển <color=#f4d582>Kỹ Năng Cộng Hưởng · Thương Tảo Phong Định</color>, nếu [Giá Trị Phá Trận] cao hơn 30 điểm, sẽ tiêu hao 30 điểm [Giá Trị Phá Trận], sát thương lần này của <color=#f4d582>Kỹ Năng Cộng Hưởng · Thương Tảo Phong Định</color> tăng 20%.\n\n<color=#d4bf5f>Giải Phóng Cộng Hưởng · Thương Cừ Bát Hoang · Hậu Động</color>\nKhi thi triển <color=#f4d582>Giải Phóng Cộng Hưởng · Thương Cừ Bát Hoang · Mưu Định</color>, nếu [Giá Trị Phá Trận] cao hơn 30 điểm, sẽ tiêu hao 30 điểm [Giá Trị Phá Trận], thi triển Thương Cừ Bát Hoang · Hậu Động, gây <color=#46c3d4ff>sát thương Khí Động</color>, sát thương lần này tính là sát thương Giải Phóng Cộng Hưởng.\nCó thể thi triển Thương Cừ Bát Hoang · Hậu Động trên không.\n\nKhi ở <color=#f4d582>Trạng Thái Phá Trận</color>, sát thương <color=#f4d582>Kỹ Năng Cộng Hưởng · Thương Tảo Phong Định</color> tăng 20%, và không còn tiêu hao [Giá Trị Phá Trận].\n\n<color=#d4bf5f>Quy Tắc Nhận Giá Trị Phá Trận</color>\nKhi <color=#f4d582>Đánh Thường</color> đánh trúng mục tiêu sẽ tích lũy [Giá Trị Phá Trận].\nKhi <color=#f4d582>Kỹ Năng Liên Kết · Công Kỳ Bất Bị</color> đánh trúng mục tiêu sẽ tích lũy [Giá Trị Phá Trận].\n\nTrong vòng 10 giây, nếu Kỵ Viêm không đánh trúng mục tiêu, [Giá Trị Phá Trận] sẽ giảm dần.</color>
- Mới: <color=#ffffff>Khi thi triển <color=#f4d582>Kỹ Năng Cộng Hưởng · Thương Tảo Phong Định</color>, nếu [Giá Trị Phá Trận] cao hơn 30 điểm, sẽ tiêu hao 30 điểm [Giá Trị Phá Trận], sát thương lần này của <color=#f4d582>Kỹ Năng Cộng Hưởng · Thương Tảo Phong Định</color> tăng 20%.\n\n<color=#d4bf5f>Giải Phóng Cộng Hưởng · Thương Cừ Bát Hoang · Hậu Động</color>\nKhi thi triển <color=#f4d582>Giải Phóng Cộng Hưởng · Thương Cừ Bát Hoang · Mưu Định</color>, nếu [Giá Trị Phá Trận] cao hơn 30 điểm, sẽ tiêu hao 30 điểm [Giá Trị Phá Trận], thi triển Thương Cừ Bát Hoang · Hậu Động, gây <color=#46c3d4ff>sát thương Khí Động</color>, sát thương lần này tính là sát thương Giải Phóng Cộng Hưởng.\nCó thể thi triển Thương Cừ Bát Hoang · Hậu Động trên không.\n\nKhi ở <color=#f4d582>Trạng Thái Phá Trận</color>, sát thương <color=#f4d582>Kỹ Năng Cộng Hưởng · Thương Tảo Phong Định</color> tăng 20%, và không còn tiêu hao [Giá Trị Phá Trận].\n\n<color=#d4bf5f>Quy Tắc Nhận Giá Trị Phá Trận</color>\nKhi <color=#f4d582>Đánh Thường</color> đánh trúng mục tiêu sẽ tích lũy [Giá Trị Phá Trận].\nKhi <color=#f4d582>Kỹ Năng Liên Kết · Công Kỳ Bất Bị</color> đánh trúng mục tiêu sẽ tích lũy [Giá Trị Phá Trận].\n\nTrong vòng 10 giây, nếu Jiyan không đánh trúng mục tiêu, [Giá Trị Phá Trận] sẽ giảm dần.</color>

#### `lang_skill.db||Skill||2`
- Cũ: <color=#ffffff><color=#d4bf5f><ano=Normal Attack>Đánh Thường</ano></color>\nTiến hành tối đa 4 đoạn tấn công liên tiếp, khi đoạn 4 đánh trúng mục tiêu, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>, nhận được 1 tiếng [Lưu Hưởng].\n\n<color=#d4bf5f><ano=Heavy Attack>Đánh Mạnh</ano></color>\nTiêu hao một lượng <ano=Stamina>Thể Lực</ano>, đâm về phía trước, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>.\n\n<color=#d4bf5f>Trọng Kích · Phong Ngâm</color>\nSử dụng <ano=Normal Attack>Đánh Thường</ano> trong một khoảng thời gian sau Đánh Mạnh, Ương Ương sẽ vung ra 1 luồng phong nhận, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>, nhận được 1 tiếng [Lưu Hưởng].\n\n<color=#d4bf5f>Tấn Công Trên Không</color>\nTiêu hao một lượng <ano=Stamina>Thể Lực</ano>, bật lên trên không lao xuống tấn công, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>.\n\n<color=#d4bf5f>Phản Kích Né Tránh</color>\nTrong một khoảng thời gian sau khi <color=#f4d582><ano=Dodge>Né Tránh</ano></color> thành công, sử dụng <color=#f4d582><ano=Normal Attack>Đánh Thường</ano></color>, sẽ đâm về phía trước, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>.</color>
- Mới: <color=#ffffff><color=#d4bf5f><ano=Normal Attack>Đánh Thường</ano></color>\nTiến hành tối đa 4 đoạn tấn công liên tiếp, khi đoạn 4 đánh trúng mục tiêu, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>, nhận được 1 tiếng [Lưu Hưởng].\n\n<color=#d4bf5f><ano=Heavy Attack>Đánh Mạnh</ano></color>\nTiêu hao một lượng <ano=Stamina>Thể Lực</ano>, đâm về phía trước, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>.\n\n<color=#d4bf5f>Trọng Kích · Phong Ngâm</color>\nSử dụng <ano=Normal Attack>Đánh Thường</ano> trong một khoảng thời gian sau Đánh Mạnh, Yangyang sẽ vung ra 1 luồng phong nhận, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>, nhận được 1 tiếng [Lưu Hưởng].\n\n<color=#d4bf5f>Tấn Công Trên Không</color>\nTiêu hao một lượng <ano=Stamina>Thể Lực</ano>, bật lên trên không lao xuống tấn công, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>.\n\n<color=#d4bf5f>Phản Kích Né Tránh</color>\nTrong một khoảng thời gian sau khi <color=#f4d582><ano=Dodge>Né Tránh</ano></color> thành công, sử dụng <color=#f4d582><ano=Normal Attack>Đánh Thường</ano></color>, sẽ đâm về phía trước, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>.</color>

#### `lang_skill.db||Skill||244`
- Cũ: <color=#ffffff><color=#d4bf5f>Khô Dạ Chi Tiết</color>\nNhấn Quyền Chấn Lăng Vũ, Yuanwu triệu hồi Khô Dạ Chi Tiết, gây <color=#9656d8ff>sát thương <ano=Electro>Điện Từ</ano></color>, và lấy Khô Dạ Chi Tiết làm trung tâm, hình thành <color=#f4d582>Vùng Sấm Vô Quang</color>.\nKhô Dạ Chi Tiết kéo dài 10 giây.\n\n<color=#d4bf5f>Vùng Sấm Vô Quang</color>\nKhi nhân vật xuất trận trong đội tấn công trong Vùng Sấm Vô Quang, <color=#f4d582>Khô Dạ Chi Tiết</color> sẽ tiến hành <ano=Coordinated Attack>Tấn Công Phối Hợp</ano>, gây <color=#9656d8ff>sát thương <ano=Electro>Điện Từ</ano></color>, mỗi 2.5 giây có thể kích hoạt 1 lần.\n\n<color=#d4bf5f>Vạn Hác Lôi</color>\nKhi [Lôi Mang] đầy, nhấn giữ Quyền Chấn Lăng Vũ có thể tiêu hao toàn bộ [Lôi Mang], thi triển Vạn Hác Lôi, gây <color=#9656d8ff>sát thương <ano=Electro>Điện Từ</ano></color>, và thêm cho mục tiêu 1 tầng <color=#f4d582>Mạch Cộng Hưởng · Vết Sấm</color>.\nVạn Hác Lôi sẽ kích nổ <color=#f4d582>Khô Dạ Chi Tiết</color> trong phạm vi 5 mét quanh bản thân Yuanwu, gây <color=#9656d8ff>sát thương <ano=Electro>Điện Từ</ano></color>, và thêm 1 tầng <color=#f4d582>Mạch Cộng Hưởng · Vết Sấm</color>.\n\n<color=#d4bf5f>Xả Thân Vô Ngã</color>\nSau khi thi triển <color=#f4d582>Vạn Hác Lôi</color>, Yuanwu sẽ tiến vào trạng thái Xả Thân Vô Ngã kéo dài 6 giây, trong trạng thái này, khả năng tấn công của Yuanwu sẽ tăng mạnh:\nPhạm vi tấn công của <color=#f4d582><ano=Normal Attack>Đánh Thường</ano></color> mở rộng, sát thương tấn công tăng, và gây <color=#9656d8ff>sát thương <ano=Electro>Điện Từ</ano></color>, sát thương lần này tính là sát thương <ano=Normal Attack>Đánh Thường</ano>, khả năng giảm độ cộng chấn của quái vật tăng;\n<color=#f4d582><ano=Heavy Attack>Đánh Mạnh</ano></color> sẽ liên tục lao về phía trước tấn công với khí thế bàng bạc, gây <color=#9656d8ff>sát thương <ano=Electro>Điện Từ</ano></color>, sát thương lần này tính là sát thương <ano=Heavy Attack>Đánh Mạnh</ano>, khả năng giảm độ cộng chấn của quái vật tăng.</color>
- Mới: <color=#ffffff><color=#d4bf5f>Khô Dạ Chi Tiết</color>\nNhấn Quyền Chấn Lăng Vũ, Yuanwu triệu hồi Khô Dạ Chi Tiết, gây <color=#9656d8ff>sát thương <ano=Electro>Điện Từ</ano></color>, và lấy Khô Dạ Chi Tiết làm trung tâm, hình thành <color=#f4d582>Vùng Sấm Vô Quang</color>.\nKhô Dạ Chi Tiết kéo dài 10 giây.\n\n<color=#d4bf5f>Vùng Sấm Vô Quang</color>\nKhi nhân vật xuất trận trong đội tấn công trong Vùng Sấm Vô Quang, <color=#f4d582>Khô Dạ Chi Tiết</color> sẽ tiến hành <ano=Coordinated Attack>Kỹ Năng Liên Kết</ano>, gây <color=#9656d8ff>sát thương <ano=Electro>Điện Từ</ano></color>, mỗi 2.5 giây có thể kích hoạt 1 lần.\n\n<color=#d4bf5f>Vạn Hác Lôi</color>\nKhi [Lôi Mang] đầy, nhấn giữ Quyền Chấn Lăng Vũ có thể tiêu hao toàn bộ [Lôi Mang], thi triển Vạn Hác Lôi, gây <color=#9656d8ff>sát thương <ano=Electro>Điện Từ</ano></color>, và thêm cho mục tiêu 1 tầng <color=#f4d582>Mạch Cộng Hưởng · Vết Sấm</color>.\nVạn Hác Lôi sẽ kích nổ <color=#f4d582>Khô Dạ Chi Tiết</color> trong phạm vi 5 mét quanh bản thân Yuanwu, gây <color=#9656d8ff>sát thương <ano=Electro>Điện Từ</ano></color>, và thêm 1 tầng <color=#f4d582>Mạch Cộng Hưởng · Vết Sấm</color>.\n\n<color=#d4bf5f>Xả Thân Vô Ngã</color>\nSau khi thi triển <color=#f4d582>Vạn Hác Lôi</color>, Yuanwu sẽ tiến vào trạng thái Xả Thân Vô Ngã kéo dài 6 giây, trong trạng thái này, khả năng tấn công của Yuanwu sẽ tăng mạnh:\nPhạm vi tấn công của <color=#f4d582><ano=Normal Attack>Đánh Thường</ano></color> mở rộng, sát thương tấn công tăng, và gây <color=#9656d8ff>sát thương <ano=Electro>Điện Từ</ano></color>, sát thương lần này tính là sát thương <ano=Normal Attack>Đánh Thường</ano>, khả năng giảm độ cộng chấn của quái vật tăng;\n<color=#f4d582><ano=Heavy Attack>Đánh Mạnh</ano></color> sẽ liên tục lao về phía trước tấn công với khí thế bàng bạc, gây <color=#9656d8ff>sát thương <ano=Electro>Điện Từ</ano></color>, sát thương lần này tính là sát thương <ano=Heavy Attack>Đánh Mạnh</ano>, khả năng giảm độ cộng chấn của quái vật tăng.</color>

#### `lang_skill.db||Skill||254`
- Cũ: <color=#ffffff><color=#d4bf5f>Vết Sấm</color>\nMục tiêu mang Vết Sấm chịu sát thương tăng.\nSố tầng Vết Sấm càng cao, sát thương phải chịu càng cao, hiệu quả kéo dài 12 giây, tối đa 3 tầng.\n\n<color=#d4bf5f>Vết Hám Lôi</color>\nVết Hám Lôi nâng cao toàn diện hiệu quả của Vết Sấm, uy lực bằng 2 lần Vết Sấm.\nMục tiêu mang Vết Hám Lôi chịu sát thương tăng.\nSố tầng Vết Hám Lôi càng cao, sát thương phải chịu càng cao, hiệu quả kéo dài 12 giây, tối đa 3 tầng.\n\n<color=#d4bf5f>Quy Tắc Nhận Lôi Mang</color>\nKhi trên sân tồn tại <color=#f4d582><ano=Resonance Skill>Kỹ Năng Cộng Hưởng</ano> · Khô Dạ Chi Tiết</color>, bản thân sẽ chậm rãi hồi phục [Lôi Mang], hiệu quả này vẫn có tác dụng khi Yuanwu ở hậu trường.\nKhi <ano=Coordinated Attack>Tấn Công Phối Hợp</ano> của <color=#f4d582><ano=Resonance Skill>Kỹ Năng Cộng Hưởng</ano> · Khô Dạ Chi Tiết</color> đánh trúng mục tiêu, hồi 5 điểm [Lôi Mang].\nKhi <color=#f4d582><ano=Coordinated Attack>Kỹ Năng Liên Kết</ano> · Nan Thệ Chi Ức</color> đánh trúng mục tiêu, hồi 20 điểm [Lôi Mang].\n\nKhi [Lôi Mang] đầy, nếu tấn công của bản thân Yuanwu đánh bật mục tiêu lên trên <color=#f4d582><ano=Resonance Skill>Kỹ Năng Cộng Hưởng</ano> · Khô Dạ Chi Tiết</color>, sẽ kích nổ <color=#f4d582><ano=Resonance Skill>Kỹ Năng Cộng Hưởng</ano> · Khô Dạ Chi Tiết</color>, gây sát thương <ano=Electro>Điện Từ</ano>, và thêm 1 tầng <color=#f4d582>Vết Sấm</color> cho mục tiêu.</color>
- Mới: <color=#ffffff><color=#d4bf5f>Vết Sấm</color>\nMục tiêu mang Vết Sấm chịu sát thương tăng.\nSố tầng Vết Sấm càng cao, sát thương phải chịu càng cao, hiệu quả kéo dài 12 giây, tối đa 3 tầng.\n\n<color=#d4bf5f>Vết Hám Lôi</color>\nVết Hám Lôi nâng cao toàn diện hiệu quả của Vết Sấm, uy lực bằng 2 lần Vết Sấm.\nMục tiêu mang Vết Hám Lôi chịu sát thương tăng.\nSố tầng Vết Hám Lôi càng cao, sát thương phải chịu càng cao, hiệu quả kéo dài 12 giây, tối đa 3 tầng.\n\n<color=#d4bf5f>Quy Tắc Nhận Lôi Mang</color>\nKhi trên sân tồn tại <color=#f4d582><ano=Resonance Skill>Kỹ Năng Cộng Hưởng</ano> · Khô Dạ Chi Tiết</color>, bản thân sẽ chậm rãi hồi phục [Lôi Mang], hiệu quả này vẫn có tác dụng khi Yuanwu ở hậu trường.\nKhi <ano=Coordinated Attack>Kỹ Năng Liên Kết</ano> của <color=#f4d582><ano=Resonance Skill>Kỹ Năng Cộng Hưởng</ano> · Khô Dạ Chi Tiết</color> đánh trúng mục tiêu, hồi 5 điểm [Lôi Mang].\nKhi <color=#f4d582><ano=Coordinated Attack>Kỹ Năng Liên Kết</ano> · Nan Thệ Chi Ức</color> đánh trúng mục tiêu, hồi 20 điểm [Lôi Mang].\n\nKhi [Lôi Mang] đầy, nếu tấn công của bản thân Yuanwu đánh bật mục tiêu lên trên <color=#f4d582><ano=Resonance Skill>Kỹ Năng Cộng Hưởng</ano> · Khô Dạ Chi Tiết</color>, sẽ kích nổ <color=#f4d582><ano=Resonance Skill>Kỹ Năng Cộng Hưởng</ano> · Khô Dạ Chi Tiết</color>, gây sát thương <ano=Electro>Điện Từ</ano>, và thêm 1 tầng <color=#f4d582>Vết Sấm</color> cho mục tiêu.</color>

#### `lang_skill.db||Skill||258`
- Cũ: <color=#ffffff><color=#d4bf5f><ano=Normal Attack>Đánh Thường</ano></color>\nTiến hành tối đa 4 đoạn tấn công liên tiếp, khi đoạn 4 đánh trúng mục tiêu, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>, nhận được 1 tiếng [Lưu Hưởng].\n\n<color=#d4bf5f><ano=Heavy Attack>Đánh Mạnh</ano></color>\nTiêu hao một lượng <ano=Stamina>Thể Lực</ano>, đâm về phía trước, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>.\n\n<color=#d4bf5f>Trọng Kích · Phong Ngâm</color>\nSử dụng <ano=Normal Attack>Đánh Thường</ano> trong một khoảng thời gian sau Đánh Mạnh, Ương Ương sẽ vung ra 1 luồng phong nhận, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>, nhận được 1 tiếng [Lưu Hưởng].\n\n<color=#d4bf5f>Tấn Công Trên Không</color>\nTiêu hao một lượng <ano=Stamina>Thể Lực</ano>, bật lên trên không lao xuống tấn công, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>.\n\n<color=#d4bf5f>Phản Kích Né Tránh</color>\nTrong một khoảng thời gian sau khi <color=#f4d582><ano=Dodge>Né Tránh</ano></color> thành công, sử dụng <color=#f4d582><ano=Normal Attack>Đánh Thường</ano></color>, sẽ đâm về phía trước, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>.</color>
- Mới: <color=#ffffff><color=#d4bf5f><ano=Normal Attack>Đánh Thường</ano></color>\nTiến hành tối đa 4 đoạn tấn công liên tiếp, khi đoạn 4 đánh trúng mục tiêu, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>, nhận được 1 tiếng [Lưu Hưởng].\n\n<color=#d4bf5f><ano=Heavy Attack>Đánh Mạnh</ano></color>\nTiêu hao một lượng <ano=Stamina>Thể Lực</ano>, đâm về phía trước, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>.\n\n<color=#d4bf5f>Trọng Kích · Phong Ngâm</color>\nSử dụng <ano=Normal Attack>Đánh Thường</ano> trong một khoảng thời gian sau Đánh Mạnh, Yangyang sẽ vung ra 1 luồng phong nhận, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>, nhận được 1 tiếng [Lưu Hưởng].\n\n<color=#d4bf5f>Tấn Công Trên Không</color>\nTiêu hao một lượng <ano=Stamina>Thể Lực</ano>, bật lên trên không lao xuống tấn công, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>.\n\n<color=#d4bf5f>Phản Kích Né Tránh</color>\nTrong một khoảng thời gian sau khi <color=#f4d582><ano=Dodge>Né Tránh</ano></color> thành công, sử dụng <color=#f4d582><ano=Normal Attack>Đánh Thường</ano></color>, sẽ đâm về phía trước, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>.</color>

#### `lang_skill.db||Skill||266`
- Cũ: <color=#ffffff>Sau khi sử dụng <color=#f4d582><ano=Coordinated Attack>Kỹ Năng Liên Kết</ano> · Tán Lam Lễ Tán</color>, Tăng Sát Thương <ano=Aero>Khí Động</ano> của Ương Ương tăng 15%, hiệu quả kéo dài 8 giây.</color>
- Mới: <color=#ffffff>Sau khi sử dụng <color=#f4d582><ano=Coordinated Attack>Kỹ Năng Liên Kết</ano> · Tán Lam Lễ Tán</color>, Tăng Sát Thương <ano=Aero>Khí Động</ano> của Yangyang tăng 15%, hiệu quả kéo dài 8 giây.</color>

#### `lang_skill.db||Skill||270`
- Cũ: <color=#ffffff><color=#d4bf5f>Trọng Kích · Phong Tập</color>\nKhi Ương Ương sở hữu 3 tiếng [Lưu Hưởng], sử dụng <ano=Heavy Attack>Đánh Mạnh</ano> có thể kích hoạt Phong Tập, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color> và đánh văng mục tiêu, sát thương lần này tính là <ano=Heavy Attack DMG>Sát Thương Trọng Kích</ano>.\n\n<color=#d4bf5f>Tấn Công Trên Không · Thích Vũ</color>\nKhi Ương Ương sở hữu 3 tiếng [Lưu Hưởng], sử dụng <color=#f4d582>Tấn Công Trên Không</color> trên không, sẽ tiêu hao toàn bộ [Lưu Hưởng], phát động tấn công liên tiếp, và bổ nhào từ trên không gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>. Sau khi tiếp đất, Ương Ương sẽ thu đao tấn công, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>, sát thương lần này tính là sát thương <ano=Normal Attack>Đánh Thường</ano>.\n\n<color=#d4bf5f>Quy Tắc Nhận Lưu Hưởng</color>\nKhi sử dụng <color=#f4d582><ano=Normal Attack>Đánh Thường</ano> đoạn 4</color> đánh trúng mục tiêu có thể nhận 1 tiếng [Lưu Hưởng].\nKhi sử dụng <color=#f4d582>Trọng Kích · Phong Ngâm</color> đánh trúng mục tiêu có thể nhận 1 tiếng [Lưu Hưởng].\nKhi sử dụng <color=#f4d582><ano=Resonance Skill>Kỹ Năng Cộng Hưởng</ano> · Tải Lưu Phong Vực</color> đánh trúng mục tiêu có thể nhận 1 tiếng [Lưu Hưởng].\nKhi sử dụng <color=#f4d582><ano=Coordinated Attack>Kỹ Năng Liên Kết</ano> · Tán Lam Lễ Tán</color> đánh trúng mục tiêu có thể nhận 1 tiếng [Lưu Hưởng].</color>
- Mới: <color=#ffffff><color=#d4bf5f>Trọng Kích · Phong Tập</color>\nKhi Yangyang sở hữu 3 tiếng [Lưu Hưởng], sử dụng <ano=Heavy Attack>Đánh Mạnh</ano> có thể kích hoạt Phong Tập, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color> và đánh văng mục tiêu, sát thương lần này tính là <ano=Heavy Attack DMG>Sát Thương Trọng Kích</ano>.\n\n<color=#d4bf5f>Tấn Công Trên Không · Thích Vũ</color>\nKhi Yangyang sở hữu 3 tiếng [Lưu Hưởng], sử dụng <color=#f4d582>Tấn Công Trên Không</color> trên không, sẽ tiêu hao toàn bộ [Lưu Hưởng], phát động tấn công liên tiếp, và bổ nhào từ trên không gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>. Sau khi tiếp đất, Yangyang sẽ thu đao tấn công, gây <color=#46c3d4ff>sát thương <ano=Aero>Khí Động</ano></color>, sát thương lần này tính là sát thương <ano=Normal Attack>Đánh Thường</ano>.\n\n<color=#d4bf5f>Quy Tắc Nhận Lưu Hưởng</color>\nKhi sử dụng <color=#f4d582><ano=Normal Attack>Đánh Thường</ano> đoạn 4</color> đánh trúng mục tiêu có thể nhận 1 tiếng [Lưu Hưởng].\nKhi sử dụng <color=#f4d582>Trọng Kích · Phong Ngâm</color> đánh trúng mục tiêu có thể nhận 1 tiếng [Lưu Hưởng].\nKhi sử dụng <color=#f4d582><ano=Resonance Skill>Kỹ Năng Cộng Hưởng</ano> · Tải Lưu Phong Vực</color> đánh trúng mục tiêu có thể nhận 1 tiếng [Lưu Hưởng].\nKhi sử dụng <color=#f4d582><ano=Coordinated Attack>Kỹ Năng Liên Kết</ano> · Tán Lam Lễ Tán</color> đánh trúng mục tiêu có thể nhận 1 tiếng [Lưu Hưởng].</color>

#### `lang_skill.db||Skill||38`
- Cũ: <color=#ffffff>Thúc đẩy cây cỏ xung quanh sinh trưởng nhanh chóng, gây <color=#f9ff4a>sát thương <ano=Spectro>Quang Phổ</ano></color>, hồi phục sinh mệnh cho tất cả nhân vật trong đội, khi đánh trúng mục tiêu sẽ thêm <color=#f4d582>Dấu Quang Hợp</color> cho mục tiêu.\n\n<color=#d4bf5f>Dấu Quang Hợp</color>\nKhi tất cả nhân vật trong đội đánh trúng mục tiêu mang Dấu Quang Hợp, Quyết Viên đều sẽ tiến hành <ano=Coordinated Attack>Tấn Công Phối Hợp</ano>, gây <color=#f9ff4a>sát thương <ano=Spectro>Quang Phổ</ano></color>, và hồi phục sinh mệnh cho nhân vật đã gây sát thương.</color>
- Mới: <color=#ffffff>Thúc đẩy cây cỏ xung quanh sinh trưởng nhanh chóng, gây <color=#f9ff4a>sát thương <ano=Spectro>Quang Phổ</ano></color>, hồi phục sinh mệnh cho tất cả nhân vật trong đội, khi đánh trúng mục tiêu sẽ thêm <color=#f4d582>Dấu Quang Hợp</color> cho mục tiêu.\n\n<color=#d4bf5f>Dấu Quang Hợp</color>\nKhi tất cả nhân vật trong đội đánh trúng mục tiêu mang Dấu Quang Hợp, Quyết Viên đều sẽ tiến hành <ano=Coordinated Attack>Kỹ Năng Liên Kết</ano>, gây <color=#f9ff4a>sát thương <ano=Spectro>Quang Phổ</ano></color>, và hồi phục sinh mệnh cho nhân vật đã gây sát thương.</color>

#### `lang_skill.db||Skill||48`
- Cũ: <color=#ffffff>Khi <ano=Cooking>Nấu ăn</ano> <ano=Dish>Món ăn</ano> loại khám phá <ano=Tacet Field>Minh Vực</ano>, có 20% xác suất nhận được gấp đôi món ăn giống nhau.</color>
- Mới: <color=#ffffff>Khi <ano=Cooking>Nấu ăn</ano> <ano=Dish>Món ăn</ano> loại khám phá <ano=Tacet Field>Vùng Vô Thanh</ano>, có 20% xác suất nhận được gấp đôi món ăn giống nhau.</color>

### part08

#### `lang_skill.db||Skill||78`
- Cũ: <color=#ffffff><color=#d4bf5f><ano=Heavy Attack: Burst>Đánh Mạnh · Bạo Liệt</ano></color>\nKhi Sanhua nhấn giữ <color=#f4d582><ano=Heavy Attack>Đánh Mạnh</ano></color>, nếu thả Đánh Mạnh khi con trỏ nằm trong khu vực [Băng Ngân], Sanhua sẽ sử dụng Đánh Mạnh · Bạo Liệt, lao tới mục tiêu, gây <color=#1891e7ff>sát thương <ano=Glacio>Ngưng Băng</ano></color>, sát thương lần này tính là <ano=Heavy Attack DMG>Sát Thương Đánh Mạnh</ano>.\n\n<color=#d4bf5f>Băng Bạo</color>\n<color=#f4d582><ano=Heavy Attack: Burst>Đánh Mạnh · Bạo Liệt</ano></color> sẽ kích nổ [Băng Cức], [Băng Lăng] và [Băng Xuyên] trong đường tấn công, gây <color=#1891e7ff>sát thương <ano=Glacio>Ngưng Băng</ano></color>, sát thương của [Băng Cức] tính là sát thương <ano=Coordinated Attack>Kỹ Năng Liên Kết</ano>, sát thương vụ nổ của [Băng Lăng] tính là sát thương <ano=Resonance Skill>Kỹ Năng Cộng Hưởng</ano>, sát thương vụ nổ của [Băng Xuyên] tính là sát thương <ano=Resonance Liberation>Giải Phóng Cộng Hưởng</ano>.\n\n<color=#d4bf5f>Quy Tắc Mở Rộng Khu Vực Băng Ngân</color>\nMỗi khi sở hữu 1 tầng [Thấu Thị] sẽ giúp khu vực [Băng Ngân] mở rộng, tối đa sở hữu hai tầng [Thấu Thị].\nKhi sử dụng <color=#f4d582><ano=Normal Attack>Đánh Thường</ano> đoạn 5</color>, nhận được 1 tầng [Thấu Thị].\nKhi sử dụng <color=#f4d582><ano=Coordinated Attack>Kỹ Năng Liên Kết</ano> · Lẫm Thích</color>, nhận được 1 tầng [Thấu Thị].\nKhi sử dụng <color=#f4d582><ano=Resonance Skill>Kỹ Năng Cộng Hưởng</ano> · Sóc Tuyết Vĩnh Đông</color>, nhận được 1 tầng [Thấu Thị].\nKhi sử dụng <color=#f4d582><ano=Resonance Liberation>Giải Phóng Cộng Hưởng</ano> · Tiêu Minh Đông Thổ</color>, nhận được 2 tầng [Thấu Thị].\n[Băng Ngân] sau khi mở rộng tồn tại 5 giây sẽ khôi phục về kích thước khu vực ban đầu.\nSử dụng thành công <color=#f4d582><ano=Heavy Attack: Burst>Đánh Mạnh · Bạo Liệt</ano></color> cũng sẽ khiến [Băng Ngân] sau khi mở rộng khôi phục về kích thước ban đầu.</color>
- Mới: <color=#ffffff><color=#d4bf5f><ano=Heavy Attack: Burst>Đánh Mạnh · Bạo Liệt</ano></color>\nKhi Sanhua nhấn giữ <color=#f4d582><ano=Heavy Attack>Đánh Mạnh</ano></color>, nếu thả Đánh Mạnh khi con trỏ nằm trong khu vực [Băng Ngân], Sanhua sẽ sử dụng Đánh Mạnh · Bạo Liệt, lao tới mục tiêu, gây <color=#1891e7ff>sát thương <ano=Glacio>Ngưng Băng</ano></color>, sát thương lần này tính là <ano=Heavy Attack DMG>Sát Thương Trọng Kích</ano>.\n\n<color=#d4bf5f>Băng Bạo</color>\n<color=#f4d582><ano=Heavy Attack: Burst>Đánh Mạnh · Bạo Liệt</ano></color> sẽ kích nổ [Băng Cức], [Băng Lăng] và [Băng Xuyên] trong đường tấn công, gây <color=#1891e7ff>sát thương <ano=Glacio>Ngưng Băng</ano></color>, sát thương của [Băng Cức] tính là sát thương <ano=Coordinated Attack>Kỹ Năng Liên Kết</ano>, sát thương vụ nổ của [Băng Lăng] tính là sát thương <ano=Resonance Skill>Kỹ Năng Cộng Hưởng</ano>, sát thương vụ nổ của [Băng Xuyên] tính là sát thương <ano=Resonance Liberation>Giải Phóng Cộng Hưởng</ano>.\n\n<color=#d4bf5f>Quy Tắc Mở Rộng Khu Vực Băng Ngân</color>\nMỗi khi sở hữu 1 tầng [Thấu Thị] sẽ giúp khu vực [Băng Ngân] mở rộng, tối đa sở hữu hai tầng [Thấu Thị].\nKhi sử dụng <color=#f4d582><ano=Normal Attack>Đánh Thường</ano> đoạn 5</color>, nhận được 1 tầng [Thấu Thị].\nKhi sử dụng <color=#f4d582><ano=Coordinated Attack>Kỹ Năng Liên Kết</ano> · Lẫm Thích</color>, nhận được 1 tầng [Thấu Thị].\nKhi sử dụng <color=#f4d582><ano=Resonance Skill>Kỹ Năng Cộng Hưởng</ano> · Sóc Tuyết Vĩnh Đông</color>, nhận được 1 tầng [Thấu Thị].\nKhi sử dụng <color=#f4d582><ano=Resonance Liberation>Giải Phóng Cộng Hưởng</ano> · Tiêu Minh Đông Thổ</color>, nhận được 2 tầng [Thấu Thị].\n[Băng Ngân] sau khi mở rộng tồn tại 5 giây sẽ khôi phục về kích thước khu vực ban đầu.\nSử dụng thành công <color=#f4d582><ano=Heavy Attack: Burst>Đánh Mạnh · Bạo Liệt</ano></color> cũng sẽ khiến [Băng Ngân] sau khi mở rộng khôi phục về kích thước ban đầu.</color>

#### `lang_skill.db||Skill||88`
- Cũ: <color=#ffffff>Sau khi sử dụng <color=#f4d582><ano=Heavy Attack: Resonant Chord>Đánh Mạnh · Minh Tấu</ano></color>, Tấn Công của <ano=Rover>Lữ Khách</ano> tăng 15%, kéo dài 5 giây.</color>
- Mới: <color=#ffffff>Sau khi sử dụng <color=#f4d582><ano=Heavy Attack: Resonant Chord>Đánh Mạnh · Minh Tấu</ano></color>, Tấn Công của <ano=Rover>Rover</ano> tăng 15%, kéo dài 5 giây.</color>

#### `lang_skill.db||Skill||90`
- Cũ: <color=#ffffff>Sau khi <color=#f4d582><ano=Resonance Skill>Kỹ Năng Cộng Hưởng</ano> · Phù Thanh Minh Trần · Hồi Thanh</color> đánh trúng mục tiêu, sẽ hồi phục 20 điểm Năng Lượng <ano=Concerto>Hiệp Tấu</ano> cho <ano=Rover>Lữ Khách</ano>.</color>
- Mới: <color=#ffffff>Sau khi <color=#f4d582><ano=Resonance Skill>Kỹ Năng Cộng Hưởng</ano> · Phù Thanh Minh Trần · Hồi Thanh</color> đánh trúng mục tiêu, sẽ hồi phục 20 điểm Năng Lượng <ano=Concerto>Hiệp Tấu</ano> cho <ano=Rover>Rover</ano>.</color>

#### `lang_multi_text.db||MultiText||Flow_11000001_813`
- Cũ: Thì không thể không nhắc tới cái duyên từ khi mới lọt lòng giữa anh đây và Phi Diêm!
- Mới: Thì phải nhắc đến cái duyên giữa anh đây và Phi Diêm từ lúc mới lọt lòng!

#### `lang_multi_text.db||MultiText||Flow_136000001_147`
- Cũ: Xin cậu đấy Lăng Địch, tớ không thể không gia nhập Dạ Quy được, tương lai của Dạ Quy không thể thiếu tớ mà!
- Mới: Xin cậu đấy, Lăng Địch! Tớ nhất định phải gia nhập Dạ Quy. Tương lai của Dạ Quy không thể thiếu tớ mà!

#### `lang_multi_text.db||MultiText||CoopActivity_Upgrade_505`
- Cũ: Em sẽ trân trọng bức ảnh chụp chung với tiền bối! Vâng, cùng với những bức ảnh quý giá khác.
- Mới: Em sẽ giữ gìn bức ảnh chụp chung với tiền bối thật cẩn thận! Ừm, em sẽ để nó cùng những bức ảnh quý giá khác.

#### `lang_loadingtips.db||LoadingTipsText||30`
- Cũ: Nghe nói, căn phòng tối nhỏ của Ngâm Lâm rất đáng sợ, thỉnh thoảng vẫn vọng ra tiếng kêu thảm thiết...
- Mới: Nghe nói, căn phòng tối nhỏ của Yinlin rất đáng sợ, thỉnh thoảng vẫn vọng ra tiếng kêu thảm thiết...

#### `lang_multi_text.db||MultiText||GNNPC_HJYDSTBC_8_12`
- Cũ: Nhưng đối với đội chúng ta mà nói, nó giống như ngọn hải đăng vậy.
- Mới: Nhưng với đội chúng ta, nó giống như một ngọn hải đăng vậy.

#### `lang_multi_text.db||MultiText||GNNPC_ZDGXZ_1_2`
- Cũ: Tôi đã xem trận chung kết của ngài và Lupa, không thể không nói, ngài thắng rất đẹp.
- Mới: Tôi đã xem trận chung kết của ngài và Lupa. Phải công nhận, ngài thắng rất đẹp.

#### `lang_multi_text.db||MultiText||NPC_YJYFB_30_4`
- Cũ: Nhưng chúng em không thể không có chị! Thuật toán hiệu chỉnh sai số của thiết bị quan sát vật chất ảo là do chị viết, bây giờ cả nhóm đều đang dùng...
- Mới: Nhưng chúng em cần chị! Thuật toán hiệu chỉnh sai số của thiết bị quan sát vật chất ảo là do chị viết, bây giờ cả nhóm đều đang dùng—

#### `lang_multi_text.db||MultiText||NPC_YJY_49_3`
- Cũ: Nhưng mà, cũng không thể không đuổi theo. Theo tôi thấy, nếu ngay cả dũng khí đuổi theo cũng không có, thì cần gì đến đây làm học thuật chứ?
- Mới: Nhưng vẫn phải đuổi theo. Theo tôi, nếu ngay cả dũng khí để đuổi theo cũng không có, vậy còn đến đây làm học thuật để làm gì?


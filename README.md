# Enter The Dungeon (clone from Enter The Gungeon)
### Các Folder được cung cấp:
- [x] Sprites
- [x] Sounds

### Map được xử lí bởi:
* Ai làm scene nào thì vào edit file README.md trong branch "master". Thay "..." bằng ***tên của mình***. Khi hoàn thành thì xóa dấu cách trong ngoặc vuông [] và thay bằng chữ **x**.

> VD: [ ] Start: \*\*\*...*** --> [x] Start: \*\*\*Quân***
 
- [ ] Start: ***Quân***
- [ ] The Breach: ***Quân***
- [ ] Tutorial room: ***...***
- [ ] Shopping room: ***Phát***
- [ ] Chamber 1: ***...***
- [ ] Chamber 2: ***Phát***
- [ ] Chamber 3: ***Quân***
- [ ] Hidden Chamber 1: ***...***
- [ ] Hidden Chamber 2: ***Phát***
- [ ] FinalBoss_Lich: ***...***
- [ ] Aimless Void: ***Quân***
- [ ] Boss Chamber for Hunter: ***...***
- [ ] Boss Chamber for Marine: ***...***

***Lưu ý:**
- Trong Sprites - Main Characters, **Guide** chính là **Hunter**.
- Sprite của Shotgun Kin không có folder ảnh lẻ.
- Folder Bosses và Enemies trong folder Sounds không được phân đúng loại nên nếu kiếm sound của các Enemy và Boss thì nên kiểm ở cả 2 folder này.
- Một số Sprite ko có đúng tên so vs trong các link tham khảo nên cần xem hình để phân biệt.
- Các Sprite lẻ cắt ra từ Sprite - sheet của Shotgun Kin chưa được đặt tên xong ( chỉ vừa đặt được vài cái ).
- Pixels Per Unit: 24
- Làm xong thì push lên branch của bản thân rồi vô github tạo ***pull request*** để mn cùng duyệt xong. ***TUYỆT ĐỐI KHÔNG ĐC PHÉP TỰ Ý MERGE VÔ BRANCH "MASTER".***

# Hệ thống màn chơi và các scene:

![Imgur](https://imgur.com/c7uIzWJ.png)

# Lưu ý trước khi bắt tay vô làm
1. ***Tạo nhánh mới có name là MSSV_HoTen.***

2. Khi ghép Sprite để làm Animation, có thể dùng Sprite Editor để cắt Sprite - Sheet được cung cấp thành cái Sprite nhỏ hơn ( Khuyến khích xài Sprite lẻ được cung cấp trong folder cùng tên để tạo Animation vì có thể sẽ có vài Sprite - Sheet cắt bị lỗi ).

3. Tab **Hierarchy** Các object phải được phân rõ loại để tiện tìm kiếm và chỉnh sửa:

![Imgur](https://imgur.com/YLScKYR.png)

4. Các website để tham khảo các Chamber:
- [The Breach](https://enterthegungeon.fandom.com/wiki/The_Breach?so=search)
- Tutorial Chamber: [Halls of Knowledge](https://enterthegungeon.fandom.com/wiki/Halls_of_Knowledge)
- Chambers:
  - Chamber 1: [Keep of the Lead Lord](https://enterthegungeon.fandom.com/wiki/Keep_of_the_Lead_Lord)
  - Chamber 2: [Gungeon Proper](https://enterthegungeon.fandom.com/wiki/Gungeon_Proper)
  - Chamber 3: [Forge](https://enterthegungeon.fandom.com/wiki/Forge)
- Hidden Chambers:
  - Hidden Chamber 1: [Oubliette](https://enterthegungeon.fandom.com/wiki/Oubliette)
  - Hidden Chamber 2: [Abbey of the True Gun](https://enterthegungeon.fandom.com/wiki/Abbey_of_the_True_Gun)
- Final Boss: [Bullet Hell](https://enterthegungeon.fandom.com/wiki/Bullet_Hell)

Ngoài ra cũng cần tham khảo thêm trên Youtube để tạo hình các room cho mỗi chamber và các scene khác như:

- Start Scene
- The Breach
- Aimless Void
- 2 boss chamber trong cốt chuyện của Hunter và Marine

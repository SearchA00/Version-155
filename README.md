# Version-155
Tool by MoK !
Danh sách HotKey và tính năng tương ứng( không phân biệt chữ hoa và thường) :


>>>Ấn Double phím tương ứng :
	+ Click vào Tool rồi ấn  Double "ESC" để tắt hoàn toàn Tool.Nút Close trên Tool sẽ ẩn nó và chạy ngầm chứ không tắt nhé !  

	+ Ấn Double "f" để chạy Auto follow.

	+ Ấn Double "b" để Rebuff (không phân biệt hoa thường).

	+ Ấn Double "g" sẽ get ID của vật phẩm ở ô thứ nhất trong túi đồ và lưu vào file ItemsInfo.ini(ID ở dưới [ItemInfo],dùng để get ID của phù máu và mana,sau đó cut paste vào dòng phù tương ứng .
Do mỗi phiên bản add nhiều Item lạ  không thống nhất nên làm như vậy cho tiện)


	


					    >>>>>>>>>>>>•<<<<<<<<<<<	
			
1.Loggin vào game.

2.Chạy Tool,Chọn nhân vật  tương ứng trong ô comboBox của cửa sổ game cần auto.

3. Sync : Đồng bộ tấn công theo nhân vật chỉ định.Thực hiện như sau :
	- B1 : Target vào nhân vật muốn đánh theo.
	- B2 : Tích vào Sync xong.
	Muốn tạm thòi không tấn công theo thì bỏ tích,muốn đánh theo lại thì chỉ cần tích vào mà ko cần target lại nữa,muốn đổi sang đánh theo nhân vật khác thì làm lại từ B1>B2.

4. AutoFollow : Tự động đi theo Key.Trong chế độ này thì nhân vật sẽ tự động theo Key nếu khoảng cách tới Key lớn hơn ô ghi bên cạnh. Ngoài ra sẽ tự động chuyển trạng thái cưỡi ngựa ,ko cưỡi hay Fly theo Key đồng thời sẽ tự động tăng độ cao.

5. Tool tự động dừng auto khi mất kết nối hay nhân vật thoát ra màn hình chọn nhân vật.

6.Nút "Show/Hide" ẩn của sổ game cho nó sáng cái màn hình.

7.Tool có 3 chế độ đánh là: - Đánh mod theo tên thì ("trước khi run phải target Mod cần đánh trước") 
			      - Đánh tất cả thì ko cần target,đánh toàn bộ mod xung quanh ! 
			      -Chế độ "ẩn" đánh Boss ae xem video !

8.CountDie :Giới hạn số lần sống lại(mặc định 1000 lần) sau đó tool Pause.Manne : Số lượng hình nhân trong túi(bản 136 chưa có hàng mẫu để lấy ID nên ko khả dụng)

9. Về làng : nếu sau khi die muốn về làng

10. Dùng bùa : nếu sau khi die muốn dùng bùa hồi sinh

11. Kỹ Năng : Chờ Vũ linh hồi sinh.

12. Manne : Số lượng hình nhân hiện tại.

13. Die : Số lần chết.

14. OnlyName : Chế độ chỉ đánh theo tên mà bỏ qua hết các cài đặt như lvl,height,Distance...Nên kết hợp với MovBack để trở lại vị trí ban đầu !

15. Distance,Height,MobsLVL là các giới hạn chọn mob theo bán kính train, độ cao,level mob.

16. MovBack : Trở lại khu vực train nếu vì lý do nào đó mà chạy ra ngoài !

17. Change Hp-Mp : Tự động thay phù HP,Mp khi dung lượng phù nhỏ hơn giá trị ghi bên cạnh.Hiện tại chỉ hỗ trợ thay phù xanh Free và phù 350k,ae muốn thêm thì tự add thêm vào(cách add xem thông tin về Hotkey Double "g")

18. Pot Hp-Mp : Do bản này chưa có Long ngâm nên mình đã thêm chức năng cắn máu và mana bình.Với số máu và mana còn lại tương ứng ô ghi bên cạnh.

19. Min Relia : Độ bền tối thiểu để thay vũ khí.

20. Change Weapon : Tích vào để tự động thay,tối đa 3 lần,vú khí phải để ở ô 1-2-3 trong túi đồ.

21.PickUp All: Nhawtk tất.Thời gian giữa các lần nhặt ghi trong ô bên cạnh.

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>TAB 2---SKILL<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<



22. Norman Attack : tấn công thường.
 
23. Load Skill : ấn để load skill vào các ô.Tool tự get thông tin Delay của skill ko cần Set.chọn skill rồi tick vào là được.

	Hỗ trợ 4 Skill tấn công và 1 Skill dùng chân nguyên(chọn số lượng chân nguyên tương ứng).

24. CHú ý phần Skill ReBuff có phần nhập lần lượt là thời gian(chuẩn bị + thi triển) của skill đó ô tiếp theo là thời gian Rebuff lại.

	Nếu muốn sử dụng chức năng rebuff phản damage cho Pt thì skill buff Phản chấn [hải để đầu tiên.

25. Skill Tran: Thiết lập skill biến hình cho TT(sau này sẽ thêm TíT).Chọn skill biến hình,tích vào Transfiguration để kích hoạt tính năng này sẽ.

	Tự động hóa người thay Phù,Vũ khí,Rebuff rồi trở về dạng thú nếu train dạng thú.

26. Pet: Chỉ dành cho Tít, tích vào để bật tính năng.
	
	- PercentHp : Phần trăm máu còn lại của Pet,thấp hơn hoặc bằng sẽ tự động Heal.

	- TimeRev(s) : Thời gian hồi sinh Pet(tùy theo lvl của skill) tính bằng  giấy !

	- Pets Loc : Vị trí của Pet trong túi thú - 1.Ngoài ra vị trí số 1 trong túi thú mặc định là thú cưỡi dùng cho tính năng Auto Follow.
	
	- Feeding : Tích vào để tự động cho ăn khi độ trung thành nhỏ hơn giá trị bên cạnh.(Thúc ăn mặc định ô 8 trong túi đồ).

27.Chú ý: một số trường hợp pause auto lại rồi run bị lỗi ae chạy lại tool hộ nhá ,lười chả fix !










 Hiên thông báo nập tên cho các thao tác như comboskill tấn công hay rebop (repeat=0 : chạy liên tục) ....
   Coldown : Tổng thời gian thi triển của các skill trong combo tính = giây.
   Delay   : Thời gian lặp lại của comboskill tính = giây.
   Repeat  : Số lần thực hiện lặp(0: lặp vô hạn)
   Rồi chuột phải vào ô đặt comboskill là ok !
 Có thể nhập thêm chú thích hoặc không(nhận dạng rebuff với Note là "Rbop").Nếu thấy sai có thể chuột phải vào dòng tương ứng trong Listview rồi Del.

9.Tmes Died: hiện số lần sống lại  khi Run auto.

10.Chuột phải vào ListBox để xóa 1 thiết lập hoặc toàn bộ,save cài đăt
  sau đó run thôi !



*** Cập nhật ngày 11/05/2023:

+ Dùng nút "Get P" để Get tọa độ trong phần Click nhé !
+ Thay việc set cứng HotKey bằng các HotKey mềm (có thể thay đổi) nhưng sẽ bị khóa phím ko như HotKey cứng ko bị !<Thử nghiệm>

*** Cập nhật ngày 15/05/2023:

+ Bỏ Hotkey của Run và Pause,hoàn thiện Hotkey mềm ko bị khóa phím.

+ Fix lại AutoFollow bị lỗi đi theo liên tục 

+ Thêm hàm Fly thay cho việc get điểm click.

+ Thêm hàm PickUp nhặt tất cả vật phảm ở gần.

+ Thêm Click get Skill biến hình của TT  hỗ trợ train dạng cọp(khi rebuff sẽ hóa người Rebuff rồi biến trở lại cọp)

+ Thêm hàm gọi Pet sẽ không phải dùng click nữa(chỉ cần gọi pet ra trước là được)

*** Cập nhật ngày 20/05/2023:
 + Thêm GetTrans cho TT(hỗ trợ train khi hóa cọp) vẫn đổi vũ khí và phù khi train dạng Cọp.Lưu ý khi kích hoạt tính năng này phải ở dạng người để Tool nhận dạng trạng thái người (Vì ở các Sv khác nhau giá trị này ko gióng nhau nên phải làm vậy).
 
+ Mở rộng tính năng tự động  đi theo từ phải cùng Pt và dùng Click "Đi theo" sang ko cần cùng Pt.Ban đầu khi kích hoạt tính năng chỉ cần Target nhân vật cần đi theo rồi bật tính năng,chuột phải vào "mặt" mục tiêu chọn đi theo là xong.Ngoài ra còn thêm tự động cưỡi thú khi đối tượng đi theo cưỡi thú !(cái này khá hay kéo chạy Q đỡ mệt.Lưu ý là sẽ tự động gọi thú đầu tiên trong túi đồ nhé !).

+ Vẫn dể giới hạn số lần thay Vũ khí là 3 lần nhưng mở rộng phạm vi vị trí để phù thành toàn bộ túi đồ,ko giới hạn ở dòng thứ 4 như trước!Chú ý là nếu trong túi có đồ mà bị báo không tìm thấy thì có thể mở túi ra và di chuột qua vị trí của đồ đó rồi tích lại là dc.Cái này là do cơ chế của game load chậm các item,tool đọc thông tin mà game nó chưa load cũng bó tay !

*** Cập nhật ngày 25/05/2023:
+ Thêm chức năng sử dụng skill Tinh linh.Chọn vị trí skill cần sử dụng(Số thứ tự 1 là hàng trên bên trái),rồi chọn thời gian tái sử dụng ! Ae làm Pt rồi cứ chọn 2 skill Diệt phách với Nê nính mà phệt Boss thì phút mốt xong !

*** Cập nhật ngày 28/05/2023:
+ Do mới tìm đựơc hàm nhận Keys của game nên fix lại toàn bộ các thao tác dùng  click thay thế cho key.Dùng Keys cho các phím  số từ 1-9 và F1 - F8. Cụ thể có thể tùy chọn.

 + Chuyển  việc Heal và hồi sinh Pet thành F1,F2( tùy chọn),F4 đặt Pet(khi auto ko cần phải gọi Pet ra trước như các phiên bản trc).Kiểm tra lvl Pet theo thời gian tránh việc pet up lvl tăng máu gây lỗi heal liên tục.Hỗ trợ cho pet tấn công trước và sử dụng toàn bộ các skill theo thời gian(tự dùng sau khi hết time cooldown đã cài).

 + Chuyển việc thay vũ khí để trong túi đồ ở dòng thứ nhất thành đặt ở các ô F6 F7 F8(tùy chọn).


 + Phím số 1,2 dùng đặt 2 comboskill đánh,phím 3 và 4 để skill Rebuff(các phím có thể thay đổi và thời gian ở đây tính là mili giây).

 + Hủy bỏ tính năng thay toàn bộ trang bị(dùng trong Pk) và thay phù trong mục Using Items,nhưng lạ bổ xung thêm các lựa chọn mở rộng cho việc sử dụng các phím số từ 5-9 ( dùng cắn các loại bí kíp tăng exp,lak QC khi đó để thời gian CoolDown = 0 ,Delay bằng thời gian muốn sử dụng lại thao tác ,...cách sử dụng tùy khả năng của bạn !



PS: MỘt số chức năng có hết trong video mà lười gõ ae thông cảm nhá !
Chúc các bạn chơi game vui vẻ Mộc !

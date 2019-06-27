# Ubuntu server 16.04

## Mục lục

[I. Tìm hiểu chung](#tìmhieuchung)
- [Linux](#linux)
- [Các phiên bản Ubuntu](#cacphienbanubuntu)
- [Ubuntu Server](#ubuntuserver)

[II. Cài đặt Ubuntu server 16.04 trên vmware](#caidatubuntuserver16.04trenvmware)
- [Requirements](#requirements)
- [Cài đặt](#caidat)

========================================================

<a name="timhieuchung"></a>

### I. Tìm hiểu chung

<a name="linux"></a>

#### Linux

`Ubuntu` là một hệ điều hành máy tính dựa trên Debian GNU/Linux.

`Linux` là một hệ điều hành máy tính dựa trên Unix được phát triển và phân phối theo hướng từ do mã nguồn mở dựa trên Linux kernel. Linux thường được đóng gói trong bản phân phối Linux (viết tắt là distro). Vì Linux là một hề điều hành mã nguồn mở nên ai cũng có thể tạo nên một distro cho riêng mình. Mỗi bản phân phối hướng đến một đối tượng, phục vụ một nhu cầu khác nhau. Các bản phân phối nổi tiếng hiện nay như: Ubuntu, Fedora, Arch Linux, ... Về cơ bản có ba nhánh chính:

- Debian , một bản phân phối phi thương mại và là một trong những sớm nhất, được duy trì bởi một cộng đồng gồm các nhà phát triển tình nguyện. Ví dụ: Ubuntu, Linux Mint Knoppix, ...

- Fedora , một bản phân phối được phát triển từ Red Hat Enterprise Linux (RHEL). RHEL là một bản phân phối Linux được phát triển bởi Red Hat và mục tiêu hướng tới thị trường thương mại, còn phiên bản chính thức của nó hướng tới người dùng cá nhân là Fedora.

- Slackware , được tạo ra vào năm 1993, là một trong những bản phân phối Linux đầu tiên. Một số distro tiêu biểu: Arch, Gentoo, ...

<a name="cacphienbanubuntu"></a>

#### Các phiên bản Ubuntu

Bản phát hành đầu tiên của Ubuntu là vào 20 tháng 10 năm 2004, bắt đầu bằng việc tạo ra một nhánh tạm thời của dự án Debian Linux. Phiên bản mới nhất hiên nay là Ubuntu 19.04 (Disco Dingo) được phát hành vào tháng 4 năm 2019.

Các phiên bản Ubuntu được đặt tên theo dạng YY.MM (tên mã), trong đó YY tương ứng với năm phát hành, và MM tương ứng với tháng phát hành. Tên trong ngoặc là tên mã được đặt cho phiên bản trước khi phát hành chính thức. Tên mã được đặt theo các chữ cái bắt đầu theo thứ tự từ A -> Z cho các phiên bản, bản đầu tiên là Warty Warthog.

Gồm có các bản thông thường và các bản hỗ trợ lâu dài.

Những phiên bản hỗ trợ dài hạn "Long Term Support" sẽ được hỗ trợ trong vòng 3 năm đối với máy tính để bàn và 5 năm đối với máy chủ. Các phiên bản Long Term Support sẽ được ra mắt mỗi 2 năm một lần.

<a name="ubuntuserver"></a>

#### Ubuntu Server

Ubuntu Server là một biến thể của Ubuntu tiêu chuẩn được điều chỉnh cho các mạng và dịch vụ. Không giống như cài đặt Ubuntu Desktop, Ubuntu Server không bao gồm chương trình cài đặt giao diện đồ họa (GUI).

<a name="caidatubuntuserver16.04trenvmware"></a>

### II. Cài đặt Ubuntu server 16.04 trên vmware

<a name="requirements"></a>

#### Requirements

- Đối với phiên bản Ubuntu Desktop:
 - 2 GHz dual core processor
 - 2 GiB RAM (system memory)
 - 25 GB of hard-drive space
 - Ổ đĩa CD/DVD hoặc USB

- Đối với phiên bản Ubuntu Server:
 - 300 MHz x86 processor
 - 256 MiB of system memory (RAM)
 - 1.5 GB of disk space
 - Ổ đĩa CD/DVD hoặc USB

<a name="caidat"></a>

#### Cài đặt

- Khởi động vmware và bấm tạo máy ảo

![Ảnh](https://i.imgur.com/aAlh9FD.png)

- Bấm `Next` để tiếp tục

![Ảnh](https://i.imgur.com/gNgglLt.png)

- Chọn `I will install the operating system later`

![Ảnh](https://i.imgur.com/8jYNpft.png)

- Chọn `Linux` và Version `Ubuntu 64-bit`

![Ảnh](https://i.imgur.com/lylaL9D.png)

- Đặt tên và chọn nơi lưu trữ máy ảo

![Ảnh](https://i.imgur.com/35887LO.png)

- Chọn `Customize Hardware...`

![Ảnh](https://i.imgur.com/KJGFJkc.png)

- Tại mục `New CD/DVD` ta chọn file ISO để cài đặt

![Ảnh](https://i.imgur.com/AaY57Y4.png)

- Sau đó ta tiến hành bật máy ảo và chọn ngôn ngữ, mặc định là English

![Ảnh](https://i.imgur.com/xTo0tn2.png)

- Chọn `Install Ubuntu Server`

![Ảnh](https://i.imgur.com/kVmcYw5.png)

- Chọn ngôn ngữ cài đặt, mặc định là English

![Ảnh](https://i.imgur.com/u8L1lBL.png)

- Chọn khu vực, mặc định là United States

![Ảnh](https://i.imgur.com/bUsAGpf.png)

- Cấu hình layout bàn phím, chọn `Yes` để cấu hình tự động, chọn `No` để cấu hình thủ công

![Ảnh](https://i.imgur.com/YURlV3M.png)

- Điền tên hostname

![Ảnh](https://i.imgur.com/tEKLweh.png)

- Tiến hành đặt tên và mật khẩu người dùng

![Ảnh](https://i.imgur.com/FvSuHaq.png)

![Ảnh](https://i.imgur.com/Qk9SXSn.png)

![Ảnh](https://i.imgur.com/eR123H7.png)

- Chọn `Yes` nếu muốn mã hóa thư mục home để tăng tính bảo mật, chon `No` để từ chối

![Ảnh](https://i.imgur.com/JcJEyTl.png)

- Chọn timezone, chọn `Yes` để chọn timezone mà máy ảo nhận diện được theo máy thật, chọn `No` để chọn timezone khác

![Ảnh](https://i.imgur.com/8k4EKsX.png)

- Chọn phân vùng ổ cứng cho Ubuntu, có 4 sự lựa chọn:

 - `Guided - use entire disk` : máy tính sẽ tự động phân vùng cho ổ cứng

 - `Guided - use entire disk and with set up LVM` : tự động phân vùng bằng LVM (Logical Volume Management)

 - `Guided - use entire disk and with set encrypted up LVM` : giống lựa chọn thứ hai nhưng ổ cứng sẽ được mã hóa để tăng tính bảo mật

 - `Manual` : phân vùng thủ công

![Ảnh](https://i.imgur.com/oxElhdM.png)

![Ảnh](https://i.imgur.com/xJUXEd0.png)

![Ảnh](https://i.imgur.com/6Fj9LIy.png)

![Ảnh](https://i.imgur.com/5AlHwPb.png)

![Ảnh](https://i.imgur.com/ILEwwSx.png)

![Ảnh](https://i.imgur.com/GVjAxUY.png)

- Sau đó Ubuntu sẽ được cài đặt

![Ảnh](https://i.imgur.com/kkRzXWG.png)

- Mục cấu hình proxy có thể bỏ trống

![Ảnh](https://i.imgur.com/hX2eRoL.png)

- Mục cấu hình update có 3 lựa chọn:

 - `No automatic update` : không tự động cập nhật

 - `Install security updates automatically` : tự động cập nhật

 - `Mange system with Landscape` : quản lý cập nhật từ xa

![Ảnh](https://i.imgur.com/IPSgIhZ.png)

- Cài đặt các phần mềm hỗ trợ: bấm `space` để chọn những mục cần cài đặt. Mặc định mục `standard system utilities` gồm các phần mềm cơ bản của ubuntu sẽ được chọn. Ta có thể cài thêm `OpenSSH server` để remote từ xa.

![Ảnh](https://i.imgur.com/SOGgAIt.png)

- Cài đặt GRUB boot loader trên hard disk để khởi động

![Ảnh](https://i.imgur.com/Dhl59fI.png)

- Hoàn tất việc cài đặt và khởi động lại hệ thống

![Ảnh](https://i.imgur.com/YMsdDDY.png)

- Nhập username và password đã lập để đăng nhập

![Ảnh](https://i.imgur.com/3L9bXGR.png)
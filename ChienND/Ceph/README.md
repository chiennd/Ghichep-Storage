<img src=http://i.imgur.com/lKpJRm8.png>

<ul>
<li>**Mon Server**: Cài đặt ceph-mon daemon, số lượng node tối thiểu là 3 node để đảm bảo HA.</li>
<li> `Volumes Pool` : Cài đặt ceph-osd daemon, sử dụng các HDD hiệu năng cao, nhân bản tối thiểu 3 lần để bảo vệ dữ liệu người dùng.</li>
<li> `Images Pool` : Cài đặt ceph-osd daemon, đặt các image máy ảo, khuyến nghị sử dụng SSD và nhân bản 3 lần.</li>
<li> `Backups Pool` : Cài đặt ceph-osd daemon, đặt các bản backup cho máy ảo, sử dụng HDD hiệu năng thấp và erasure code, nhân bản 1.5 lần để tiết kiệm dung lượng sử dụng.</li>
</ul>

Mô hình mạng

<img src=http://i.imgur.com/8peefH6.png>

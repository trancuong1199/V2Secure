<template>
  <div class="v2Nips">
    <h1>HỆ THỐNG PHÒNG - CHỐNG TẤN CÔNG MẠNG THẾ HỆ MỚI V2 - NIPS</h1>
    <div class="v2Nips-1">
      <h2>1. Phát hiện tấn công mạng</h2>
      <h3>
        1.1. Phát hiện tấn công mạng dựa theo tập các dấu hiệu phát hiện tấn
        công (Signature)
      </h3>
      <span>
        Hệ thống có khả năng phân tích kết nối mạng để phát hiện tấn công mạng
        mà không làm ảnh hưởng tới hoạt động của hệ thống được bảo vệ. <br />
        Phát hiện các hoạt động không bình thường trên hệ thống dựa vào tập dấu
        hiệu của hệ thống. <br />
        Dạng tấn công mạng đối tượng là người dùng bên trong hệ thống. <br />
        Dạng tấn công từ chối dịch vụ (Dos/DDoS). <br />
        Dạng tấn công vi phạm chính sách hệ thống. Phát hiện kết nối mạng dị
        bình thường phát hiện trên hệ thống. <br />
        Dạng tấn công sử dụng Shellcode. <br />
        Phát hiện các hoạt động của phần mềm độc hại qua môi trường mạng. <br />
        Dạng tấn công dò quét hệ thống Network-scan. <br />
        Dạng tấn công vào các hệ điều hành (Linux, Windows,..). <br />
        Dạng tấn công vào máy chủ Web (IIS, Apache, Oracle,...) <br />
        Dạng tấn công vào máy chủ Cơ sở dữ liệu (Mssql, Mysql, Oracle,...)
        <br />
        Dạng tấn công vào máy chủ Thư điện tử (POP3, IMAP, SMTP,...) <br />
        Dạng tấn công vào ứng dụng Web (SQL/XSS/Command Line Injection, HTTP
        detour attack, Inclusion Vulnerabili-ties, Brute Force,...)
      </span>
      <div class="v2Nips-1-img">
        <img src="../assets/images/V2Siem/v2-nips-1.png" />
      </div>
      <h3>
        1.2. Phát hiện tấn công mạng dựa vào hoạt động dị thường trên hệ thống
      </h3>
      <span>
        Chức năng Behavior Detection cho phép phát hiện các hành vi dị thường để
        phát hiện chính xác đối tượng tấn công và bị tấn công dựa vào khả năng
        tự động phân tích các cảnh báo nhận được từ hệ thống.<br />
        Chức năng Behavior Detection cho phép người quản trị thiết lập tập luật
        để phát hiện các hành vi dị thường của người dùng, kết nối mạng không
        bình thường trên hệ thống.<br />
        Chức năng Behavior Detection được thiết lập các tập luật sẵn có để phát
        hiện những hành vi sau:<br />
        - Hành vi dò quét mạng của tin tặc.<br />
        - Hành vi tấn công từ một địa chỉ nguồn khi thực hiện các dạng tấn công
        mạng khác nhau tới hệ thống được bảo vệ.<br />
        - Hành vi tấn công ứng dụng Web.<br />
        - Hành vi tấn công mã độc, phần mềm độc hại.</span
      >
      <h3>
        1.3. Phát hiện các hành vi mã độc dựa vào kết nối mạng dị thường hệ
        thống
      </h3>
      <div class="v2Nips-1-img">
        <img src="../assets/images/V2Siem/v2-nips-1-3.png" />
      </div>
    </div>
    <div class="v2Nips-2">
      <h2>2. Xử lý tấn công mạng</h2>
      <p
        >Hệ thống cung cấp khả năng tương tác với thiết bị mạng (Router,
        Switch), thiết bị bảo mật (Firewall) và hệ điều hành (Windows,
        Linux,...) để thực hiện ngăn chặn tấn công mạng.<br> Khả năng này cho phép
        hệ thống có thể ngăn chặn tấn công mạng mà không làm ảnh hưởng tới hoạt
        động và hiệu năng của hệ thống, không yêu cầu cài đặt Agent trên các
        thiết bị máy chủ.
      </p>
      <div class="v2Nips-2-img">
        <img src="../assets/images/V2Siem/download2.png">
      </div>
    </div>
    <div class="v2Nips-3">
        <h2>3. CHỨC NĂNG QUẢN TRỊ HỆ THỐNG</h2>
        <div class="v2Nips-3-content">
            <div class="v2Nips-3-content-children">
                <p>CHỨC NĂNG DASHBOARD CHO PHÉP NGƯỜI QUẢN TRỊ CÓ THÔNG TIN TỔNG QUAN VỀ HỆ THỐNG.</p>
                <p>CHỨC NĂNG BEHAVIOR BLOCKING QUẢN LÝ CÁC CẢNH BÁO VỀ PHÁT HIỆN VÀ NGĂN CHẶN TẤN CÔNG THEO HÀNH VI.</p>
                <p>CHỨC NĂNG TẠO BÁO CÁO CHO PHÉP NGƯỜI QUẢN TRỊ TẠO RA CÁC BÁO CÁO TÙY BIẾN THEO TỪNG ĐIỀU KIỆN CỤ THỂ THEO CÁC ĐỊNH DẠNG KHÁC NHAU.</p>
                <p>QUẢN LÝ CẤU HÌNH HỆ THỐNG</p>
            </div>
            <h3>THỐNG KÊ VÀ BÁO CÁO</h3>
            <div class="v2Nips-3-content-children">
                <p>QUẢN LÝ CÁC TÀI KHOẢN QUẢN TRỊ HỆ THỐNG</p>
                <p>QUẢN LÝ CẬP NHẬT PHẦN MỀM HỆ THỐNG TỪ CLOUD</p>
                <p>QUẢN LÝ CÁC TÀI KHOẢN QUẢN TRỊ HỆ THỐNG</p>
                <p>THÔNG TIN TRẠNG THÁI HỆ THỐNG</p>
                <p>QUẢN LÝ LOGS HOẠT ĐỘNG TRÊN HỆ THỐNG</p>
                <p>QUẢN TRỊ HỆ THỐNG THÔNG QUA GIAO DIỆN CONSOLE VÀ SSH</p>
            </div>
        </div>

    </div>
  </div>
</template>

<style scoped>
@import "../assets/v2Nips.css";
</style>

<template>
  <div class="V2Waf">
    <h1>HỆ THỐNG TƯỜNG LỬA ỨNG DỤNG WEB V2 - WAF</h1>
    <div class="V2Waf-1">
      <div class="V2Waf-1-left">
        <h2 class="V2Waf-title">BẢO MẬT ỨNG DỤNG WEB</h2>
        <p>
          <img
            src="../assets/images/V2Siem/start.png"
            v-bind:style="{ width: 15 + 'px', height: 16 + 'px' }"
            class="V2Waf-1-left-img"
          />
          LỌC GÓI TIN THEO BLACKLIST.
        </p>
        <p>
          <img
            src="../assets/images/V2Siem/start.png"
            v-bind:style="{ width: 15 + 'px', height: 16 + 'px' }"
            class="V2Waf-1-left-img"
          />
          LỌC ĐỊA CHỈ IP.
        </p>
        <p>
          <img
            src="../assets/images/V2Siem/start.png"
            v-bind:style="{ width: 15 + 'px', height: 16 + 'px' }"
            class="V2Waf-1-left-img"
          />
          PHÂN GIẢI ĐỊA CHỈ IP THÀNH TỌA ĐỘ ĐỊA LÝ.
        </p>
        <p>
          <img
            src="../assets/images/V2Siem/start.png"
            v-bind:style="{ width: 15 + 'px', height: 16 + 'px' }"
            class="V2Waf-1-left-img"
          />
          ÁP DỤNG TOP 10 CỦA OWASP.
        </p>
        <p>
          <img
            src="../assets/images/V2Siem/start.png"
            v-bind:style="{ width: 15 + 'px', height: 16 + 'px' }"
            class="V2Waf-1-left-img"
          />
          PHÒNG CHỐNG TẤN CÔNG CSS.
        </p>
        <p>
          <img
            src="../assets/images/V2Siem/start.png"
            v-bind:style="{ width: 15 + 'px', height: 16 + 'px' }"
            class="V2Waf-1-left-img"
          />
          PHÒNG CHỐNG TẤN CÔNG CSRF.
        </p>
        <p>
          <img
            src="../assets/images/V2Siem/start.png"
            v-bind:style="{ width: 15 + 'px', height: 16 + 'px' }"
            class="V2Waf-1-left-img"
          />
          PHÒNG CHỐNG TẤN CÔNG SESSION HIJACKING.
        </p>
        <p>
          <img
            src="../assets/images/V2Siem/start.png"
            v-bind:style="{ width: 15 + 'px', height: 16 + 'px' }"
            class="V2Waf-1-left-img"
          />
          LỌC ĐỊA CHỈ IP.
        </p>
        <p>
          <img
            src="../assets/images/V2Siem/start.png"
            v-bind:style="{ width: 15 + 'px', height: 16 + 'px' }"
            class="V2Waf-1-left-img"
          />
          TÍCH HỢP TÍNH NĂNG QUÉT LỖ HỔNG SẴN CÓ.
        </p>
        <p>
          <img
            src="../assets/images/V2Siem/start.png"
            v-bind:style="{ width: 15 + 'px', height: 16 + 'px' }"
            class="V2Waf-1-left-img"
          />
          PHÁT HIỆN MALWARE.
        </p>
        <p>
          <img
            src="../assets/images/V2Siem/start.png"
            v-bind:style="{ width: 15 + 'px', height: 16 + 'px' }"
            class="V2Waf-1-left-img"
          />
          VIRTUAL PATCHING.
        </p>
        <p>
          <img
            src="../assets/images/V2Siem/start.png"
            v-bind:style="{ width: 15 + 'px', height: 16 + 'px' }"
            class="V2Waf-1-left-img"
          />
          PHÒNG CHỐNG TẤN CÔNG BRUTEFORCE.
        </p>
        <p>
          <img
            src="../assets/images/V2Siem/start.png"
            v-bind:style="{ width: 15 + 'px', height: 16 + 'px' }"
            class="V2Waf-1-left-img"
          />
          PHÁT HIỆN TẤN CÔNG SQLI.
        </p>
        <p>
          <img
            src="../assets/images/V2Siem/start.png"
            v-bind:style="{ width: 15 + 'px', height: 16 + 'px' }"
            class="V2Waf-1-left-img"
          />
          TÍCH HỢP TƯỜNG LỬA STATEFUL Ở TẦNG 4.
        </p>
        <p>
          <img
            src="../assets/images/V2Siem/start.png"
            v-bind:style="{ width: 15 + 'px', height: 16 + 'px' }"
            class="V2Waf-1-left-img"
          />
          PHÒNG CHỐNG TẤN CÔNG DOS.
        </p>
        <p>
          <img
            src="../assets/images/V2Siem/start.png"
            v-bind:style="{ width: 15 + 'px', height: 16 + 'px' }"
            class="V2Waf-1-left-img"
          />
          PHÒNG CHỐNG TẤN CÔNG DEFACE.
        </p>
      </div>
      <div class="V2Waf-1-right">
        <h2 class="V2Waf-title">1. MÔ TẢ CHỨC NĂNG</h2>
        <span
          >Tường lửa ứng dụng web là một giải pháp bảo vệ ứng dụng trước các
          cuộc tấn công mạng. WAF là một thiết bị phần cứng hoặc phần mềm được
          cài lên máy chủ có chức năng theo dõi các thông tin sử dụng giao thức
          http/https giữa các trình duyệt của người dùng và máy chủ web. WAF có
          chức năng thực thi các chính sách bảo mật dựa trên các dấu hiệu tấn
          công, các giao thức tiêu chuẩn và các lưu lượng truy cập ứng dụng web
          bất thường.
        </span>
        <div class="V2Waf-1-right--imgFirst">
          <img src="../assets/images/V2Siem/v2-waf-1png.png" />
        </div>
        <h2>2. PHƯƠNG ÁN TRIỂN KHAI</h2>
        <div class="V2Waf-1-right--text">
          <div></div>
          <p>Triển khai giống như một proxy ngược (reverse proxy).</p>
        </div>
        <div class="V2Waf-1-right--text">
          <div></div>
          <p>Triển khai giống như một proxy trong suốt (transparent proxy).</p>
        </div>
        <div class="V2Waf-1-right--text">
          <div></div>
          <p>Triển khai giống như một proxy trong suốt (transparent proxy).</p>
        </div>
        <div class="V2Waf-1-right--text">
          <div></div>
          <p>
            Triển khai với giao thức Web Cache Communication Protocal (WCCP).
          </p>
        </div>
        <div class="V2Waf-1-right--imgSecond">
          <img src="../assets/images/V2Siem/v2-waf-2.png" />
        </div>
        <h2>3. BẢO VỆ HƯỚNG ĐỐI TƯỢNG</h2>
        <div class="V2Waf-1-right--text">
          <div></div>
          <p>
            Cho phép thiết lập chính sách hệ thống theo từng Webserver cần bảo
            vệ.
          </p>
        </div>
        <div class="V2Waf-1-right--text">
          <div></div>
          <p>
            Cho phép thiết lập tập luật bảo vệ theo từng Website cần bảo vệ.
          </p>
        </div>
        <h2>4. XỬ LÝ, PHÂN TÍCH TƯƠNG QUAN</h2>
        <span>
          Cho phép thiết lập các luật để tự động phân tích tương quan nhiều
          nguồn log khác nhau để phát hiện tấn công mạng.<br />
          Cho phép phát hiện các hành vi dị thường để phát hiện chính xác đối
          tương tấn công và bị tấn công dựa vào khả năng tự động phân tích các
          cảnh báo nhận được từ hệ thống. <br />
          Cho phép người quản trị thiết lập tập luật để phát hiện các hành vi dị
          thường của người dùng, kết nối mạng không bình thường trên hệ thống.
        </span>
        <div class="V2Waf-1-right--imgSecond">
          <img src="../assets/images/V2Siem/v2-waf-4.png" />
        </div>
      </div>
    </div>
    <div class="V2Waf-2">
      <div class="V2Waf-2-left">
        <h2 class="V2Waf-title">5. CẢNH BÁO VÀ TỰ ĐỘNG NGĂN CHẶN TẤN CÔNG</h2>
        <span>
          Tự động cảnh báo tấn công qua SMS, Email,... Hệ thống cung cấp khả
          năng tương tác với thiết bị mạng (Router Cisco - Juniper, Firewall
          Cisco PIX - ASA, Firewall Check-Point, Firewall Fortigate,..), Thiết
          bị bảo mật (Firewall, NAC, IDS, IPS) và hệ điều hành (Windows Server,
          Linux Centos, Fedora, Ubuntu, Debian, Linux Transparent Firewall,...)
          để thực hiện ngăn chặn tấn công mạng.. Ngăn chặn tấn công mạng mà
          không làm ảnh hưởng tới hoạt đông và hiệu năng của hệ thống, không yêu
          cầu cài đặt Agent trên các thiết bị hay máy chủ.
        </span>
        <h2>6. ĐIỀU TRA VÀ PHÂN TÍCH SỰ CỐ</h2>
        <div class="V2Waf-1-right--text">
          <div></div>
          <p>Cho phép phân tính log mức sâu theo từng trường thông tin</p>
        </div>
        <div class="V2Waf-1-right--text">
          <div></div>
          <p>
            Cho phép viết luật tương quan cho phép phát hiện và điều tra tấn
            công, sự cố.
          </p>
        </div>
        <div class="V2Waf-1-right--text">
          <div></div>
          <p>
            Cho phép phân tích và điều tra sự cố thông qua giao diện trực quan.
          </p>
        </div>
      </div>
      <div class="V2Waf-2-right">
        <img src="../assets/images/V2Siem/v2-waf-5.png" />
      </div>
    </div>
    <div class="V2Waf-3">
      <h2>1. MÔ TẢ CHỨC NĂNG</h2>
    </div>
    <div class="V2Waf-4">
      <h2>7. CHỨC NĂNG QUẢN TRỊ HỆ THỐNG</h2>
      <div class="V2Waf-4-content">
        <div class="V2Waf-4-content--children">
          <p>
            CHỨC NĂNG DASHBOARD CHO PHÉP NGƯỜI QUẢN TRỊ CÓ THÔNG TIN TỔNG QUAN
            VỀ HỆ THỐNG.
          </p>
          <p>
            CHỨC NĂNG BEHAVIOR BLOCKING QUẢN LÝ CÁC CẢNH BÁO VỀ PHÁT HIỆN VÀ NGĂN TẤN CÔNG THEO HÀNH VI..
          </p>
          <p>
            CHỨC NĂNG TẠO BÁO CÁO CHO PHÉP NGƯỜI QUẢN TRỊ TẠO RA CÁC BÁO CÁO TÙY BIẾN THEO TỪNG ĐIỀU KIỆN CỤ THỂ THEO CÁC ĐỊNH DẠNG KHÁC NHAU.
          </p>
        </div>
        <div class="V2Waf-4-content--children">
          <p>QUẢN LÝ CÁC TÀI KHOẢN QUẢN TRỊ HỆ THỐNG.</p>
          <p>QUẢN LÝ CẬP NHẬT PHẦN MỀM HỆ THỐNG TỪ CLOUD.</p>
          <p>THÔNG TIN TRẠNG THÁI HỆ THỐNG.</p>
          <p>QUẢN LÝ LOGS HOẠT ĐỘNG TRÊN HỆ THỐNG.</p>
          <p>QUẢN TRỊ HỆ THỐNG THÔNG QUA GIAO DIỆN CONSOLE VÀ SSH.</p>
        </div>
      </div>
    </div>
    <div class="V2Waf-5">
      <h2>8. NĂNG LỰC XỬ LÝ TỐI THIỂU</h2>
      <div class="V2Waf-5-content">
        <div class="V2Waf-5-content--children">
          <div class="V2Waf-5-content--children_left">
            <div></div>
            <p>Băng thông: 200 Mbps</p>
          </div>
          <div class="V2Waf-5-content--children_left">
            <div></div>
            <p>Số lượng máy chủ: 10-25</p>
          </div>
          <div class="V2Waf-5-content--children_left">
            <div></div>
            <p>Số lượng giao tiếp HTTP: 30,000 / giây</p>
          </div>
          <div class="V2Waf-5-content--children_left">
            <div></div>
            <p>Số lượng kết nối HTTP: 10,000 / giây</p>
          </div>
          <div class="V2Waf-5-content--children_left">
            <div></div>
            <p>Số lượng giao tiếp HTTPS: 12,000 / giây</p>
          </div>
          <div class="V2Waf-5-content--children_left">
            <div></div>
            <p>Giới hạn kết nối đồng thời: 500,000</p>
          </div>
        </div>
        <img src="../assets/images/V2Siem/download1.png">
      </div>
    </div>
  </div>
</template>

<style scoped>
@import "../assets/v2Waf.css";
</style>

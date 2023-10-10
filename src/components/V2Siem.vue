<template>
  <div class="V2Siem">
    <h1 class="V2Siem-title">
      HỆ THỐNG QUẢN LÝ GIÁM SÁT AN TOÀN THÔNG TIN TẬP TRUNG V2 - SIEM
    </h1>
    <div class="V2Siem-1">
      <h2 class="V2Siem-1-title">
        1. THU THẬP VÀ QUẢN LÝ LOG THEO THỜI GIAN THỰC
      </h2>
      <div class="V2Siem-1-content">
        <div class="V2Siem-1-content-children">
          <h3>1.1. Hệ thống cho phép thu thập log từ người khác nhau:</h3>
          <span>
            (1) Các thiết bị mạng, thiết bị bảo mật: Router, Switch,
            Firewall/IPS/IDS, Sandbox WAF, Network APT.<br />
            (2) Các máy chủ hệ thống trên các nền tảng khác nhau: Windows,
            Linux, Unix.<br />
            (3) Các ứng dụng: Ứng dụng phục vụ hoạt động của hệ thống: DHCP,
            DNS, NTP, VPN, Proxy Server,...; Ứng dụng cung cấp dịch vụ: Web,
            Mail, FPT, TFTP và các hệ quản trị cơ sở dữ liệu Oracle, SQL, IP
            Camera.<br />
            (4) Các thiết bị đầu cuối: Máy tính người sử dụng, máy in, máy fax,
            IP Phone, IP Camera.<br />
            (5) Điểm giám sát trên đường truyền: Điểm giám sát biên tại giao
            diện kết nối của thiết bị định tuyến biên với các mạng bên ngoài;
            điểm giám sát tạo mỗi vùng mạng của hệ thống.
          </span>
          <h3>1.2. Tự động chuẩn hóa log:</h3>
          <p>
            (1) Tự động chuẩn hóa các dạng log nhận được từ các thiết bị, ứng
            dụng.<br />
            (2) Tự động cập nhật các định dạng log mới từ Cloud
          </p>
        </div>
        <img src="../assets/images/V2Siem/v2-siem-1.34657cc7dee593f2419b.png" />
      </div>
    </div>
    <div class="V2Siem-2">
      <h3>2. PHÁT HIỆN TẤN CÔNG MẠNG</h3>
      <div class="V2Siem-2-children">
        <img src="../assets/images/V2Siem/v2-siem-2.jpg" />
        <div class="V2Siem-2-children--left">
          <p>
            <img
              src="../assets/images/V2Siem/siemIcon.png"
              v-bind:style="{ width: 18 + 'px', height: 20 + 'px' }"
              class="V2Siem-2-children-left_img"
            />
            Phát hiện tấn công mạng dự vào phân tích log truy cập ứng dụng Web.
          </p>
          <p>
            <img
              src="../assets/images/V2Siem/siemIcon.png"
              v-bind:style="{ width: 18 + 'px', height: 20 + 'px' }"
              class="V2Siem-2-children-left_img"
            />
            Phát hiện truy vấn tên miền độc hại dựa vào phân tích log truy vấn
            DNS.
          </p>
          <p>
            <img
              src="../assets/images/V2Siem/siemIcon.png"
              v-bind:style="{ width: 18 + 'px', height: 20 + 'px' }"
              class="V2Siem-2-children-left_img"
            />
            Phát hiện kết nối tới các địa chỉ IP độc hại dựa vào phân tích log
            kết nối của các thiết bị và hệ điều hành.
          </p>
          <p>
            <img
              src="../assets/images/V2Siem/siemIcon.png"
              v-bind:style="{ width: 18 + 'px', height: 20 + 'px' }"
              class="V2Siem-2-children-left_img"
            />
            Cập nhật tự động từ Cloud dấu hiệu phát hiện tấn công ứng dụng web,
            danh sách tên miền và địa chỉ độc hại.
          </p>
        </div>
      </div>
    </div>
    <div class="V2Siem-3">
      <div class="V2Siem-3-feft">
        <h3>3. XỬ LÝ PHÂN TÍCH TƯƠNG QUAN</h3>
        <p>
          <img
            src="../assets/images/V2Siem/siemIcon2.png"
            v-bind:style="{ width: 18 + 'px', height: 20 + 'px' }"
            class="V2Siem-3-feft-img"
          />
          Cho phép thiết lập các luật để tự động phân tích tương quan nhiều
          nguồn log khác nhau để phát hiện tấn công mạng.
        </p>
        <p>
          <img
            src="../assets/images/V2Siem/siemIcon2.png"
            v-bind:style="{ width: 18 + 'px', height: 20 + 'px' }"
            class="V2Siem-3-feft-img"
          />
          Phát hiện các hành vi dị thường để phát hiện chính xác đối tượng tấn
          công và bị tấn công dựa vào khả năng tự động phân tích các cảnh báo
          nhận được từ hệ thống.
        </p>
        <p>
          <img
            src="../assets/images/V2Siem/siemIcon2.png"
            v-bind:style="{ width: 18 + 'px', height: 20 + 'px' }"
            class="V2Siem-3-feft-img"
          />
          Cho phép người quản trị thiết lập tập luật để phát hiện các hành vi dị
          thường của người dùng, kết nối mạng không bình thường trên hệ thống.
        </p>
        <p>
          <img
            src="../assets/images/V2Siem/siemIcon2.png"
            v-bind:style="{ width: 18 + 'px', height: 20 + 'px' }"
            class="V2Siem-3-feft-img"
          />
          Thiết lập các tập luật sẵn có để phát hiện những hành vi sau:
        </p>
        <div class="V2Siem-3-feft--children">
          <p>- Hành vi dò quét mạng của tin tặc.</p>
          <p>
            - Hành vi tấn công từ một địa chỉ nguồn khi thực hiện các dạng tấn
            công mạng khác nhau tới hệ thống được bảo vệ.
          </p>
          <p>- Hành vi tấn công ứng dụng Web.</p>
          <p>- Hành vi tấn công mã độc, phần mềm độc hại.</p>
        </div>
      </div>
      <div class="V2Siem-3-right">
        <h3>4. TÍCH HỢP THREAT INTELLIGENCE</h3>
        <p>
          <img
            src="../assets/images/V2Siem/siemIcon3.png"
            v-bind:style="{ width: 18 + 'px', height: 20 + 'px' }"
            class="V2Siem-3-right-img"
          />
          Tích hợp chức năng threat intelligence.
        </p>
        <p>
          <img
            src="../assets/images/V2Siem/siemIcon3.png"
            v-bind:style="{ width: 18 + 'px', height: 20 + 'px' }"
            class="V2Siem-3-right-img"
          />
          Cập nhật dữ liệu threat intelligence từ cloud.
        </p>
        <p>
          <img
            src="../assets/images/V2Siem/siemIcon3.png"
            v-bind:style="{ width: 18 + 'px', height: 20 + 'px' }"
            class="V2Siem-3-right-img"
          />
          Tự động cập nhật blacklist (IP, DOMAIN, HASH) cho SIEM từ dữ liệu
          threat intelligence.
        </p>
        <p>
          <img
            src="../assets/images/V2Siem/siemIcon3.png"
            v-bind:style="{ width: 18 + 'px', height: 20 + 'px' }"
            class="V2Siem-3-right-img"
          />
          Cho phép chia sẻ thông tin với các hệ thống threat intelligence.
        </p>

        <div class="V2Siem-3-right--children">
          <h3>5. TÍCH HỢP VUILNERABILITY MANAGEMENT</h3>
          <div class="V2Siem-3-right--children_content">
            <img src="../assets/images/V2Siem/v2-siem-5png.png" />
            <div>
              <p>
                <img
                  src="../assets/images/V2Siem/siemIcon4png.png"
                  v-bind:style="{ width: 15 + 'px', height: 18 + 'px' }"
                  class="V2Siem-3-right--children_content-img"
                />
                Tích hợp chức năng quản lý điểm yếu an toàn thông tin.
              </p>
              <p>
                <img
                  src="../assets/images/V2Siem/siemIcon4png.png"
                  v-bind:style="{ width: 15 + 'px', height: 18 + 'px' }"
                  class="V2Siem-3-right--children_content-img"
                />
                Tự động cảnh báo khi phát hiện điểm yếu an toàn thông tin trong hệ thống.
              </p>
              <p>
                <img
                  src="../assets/images/V2Siem/siemIcon4png.png"
                  v-bind:style="{ width: 15 + 'px', height: 18 + 'px' }"
                  class="V2Siem-3-right--children_content-img"
                />
                Cho phép thiết lập chính sách bản vá ảo để bảo vệ hệ thống.
              </p>
              <p>
                <img
                  src="../assets/images/V2Siem/siemIcon4png.png"
                  v-bind:style="{ width: 15 + 'px', height: 18 + 'px' }"
                  class="V2Siem-3-right--children_content-img"
                />
                Tích hợp chức năng tra cứu thông tin lỗ hổng, điểm yếu.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="V2Siem-4">
        <div class="V2Siem-4-content">
            <h3>6. CẢNH BÁO VÀ TỰ ĐỘNG NGĂN CHẶN TẤN CÔNG</h3>
            <p>
                <p>
                <img
                    src="../assets/images/V2Siem/icon5.png"
                    v-bind:style="{ width: 15 + 'px', height: 15 + 'px' }"
                    class="V2Siem-4-content-img"
                />
                Tự đông cảnh báo tấn công qua SMS, Email, ...
                </p>
            </p>
            <p>
                <p>
                <img
                    src="../assets/images/V2Siem/icon5.png"
                    v-bind:style="{ width: 15 + 'px', height: 15 + 'px' }"
                    class="V2Siem-4-content-img"
                />
                Hệ thống cung cấp khả năng tương tác với thiết bị mạng (Router Cisco - Juniper, Fireall Cisco PIX - ASA, Firewall, Check-Point, Firewall Forgtinet,...), Thiết bị bảo mật(Firewall, NAC, IDS, IPS) và hệ điều hành (Windows Server, Linux, Centos, Fedora, Ubuntu, Debian, Linux, Transparent Firewall,...) để thực hiện ngăn chặn tấn công mạng.
                </p>
            </p>
            <p>
                <p>
                <img
                    src="../assets/images/V2Siem/icon5.png"
                    v-bind:style="{ width: 15 + 'px', height: 15 + 'px' }"
                    class="V2Siem-4-content-img"
                />
                Khả năng này cho phép hệ thống có thể ngăn chặn tấn công mạng mà không làm ảnh hưởng tới hoạt động và hiệu năng của hệ thống, không yêu cầu cài đặt Agent trên các thiết bị hay máy chủ.
                </p>
            </p>
            <h3>7. ĐIỀU TRA VÀ PHÂN TÍCH SỰ CỐ</h3>
            <p class="V2Siem-4-content--textBold">
                <img
                    src="../assets/images/V2Siem/icon5.png"
                    v-bind:style="{ width: 15 + 'px', height: 15 + 'px' }"
                    class="V2Siem-4-content-img"
                />
                Cho phép viết luật tương quan.
            </p>
            <p class="V2Siem-4-content--textBold">
                <img
                    src="../assets/images/V2Siem/icon5.png"
                    v-bind:style="{ width: 15 + 'px', height: 15 + 'px' }"
                    class="V2Siem-4-content-img"
                />
                Cho phép phát hiện và điều tra tấn công, sự cố.
            </p>
            <p class="V2Siem-4-content--textBold">
                <img
                    src="../assets/images/V2Siem/icon5.png"
                    v-bind:style="{ width: 15 + 'px', height: 15 + 'px' }"
                    class="V2Siem-4-content-img"
                />
                Cho phép phân tích log mức sâu theo từng trường thông tin.
            </p>
            <p class="V2Siem-4-content--textBold">
                <img
                    src="../assets/images/V2Siem/icon5.png"
                    v-bind:style="{ width: 15 + 'px', height: 15 + 'px' }"
                    class="V2Siem-4-content-img"
                />
                Cho phép phân tích và điều tra sự cố thông qua giao diện trực quan.
            </p>
            <h3>8. TỰ ĐỘNG XÁC MINH TẤN CÔNG MẠNG SỬ DỤNG CÔNG NGHỆ AI</h3>
            <p class="V2Siem-4-content--textBold">
                <img
                    src="../assets/images/V2Siem/icon5.png"
                    v-bind:style="{ width: 15 + 'px', height: 15 + 'px' }"
                    class="V2Siem-4-content-img"
                />
                Tự động xác minh nguồn tấn công mạng sử dụng công nghệ AI.
            </p>
            <p class="V2Siem-4-content--textBold">
                <img
                    src="../assets/images/V2Siem/icon5.png"
                    v-bind:style="{ width: 15 + 'px', height: 15 + 'px' }"
                    class="V2Siem-4-content-img"
                />
                Tự động phát hiện và xác minh tấn công mã độc nâng cao sử dụng công nghệ Malware Graph, Abnormal Detection, DGA Detection.
            </p>
        </div>
        <img src="../assets/images/V2Siem/v2-6.png"> 
    </div>
    <div class="V2Siem-5">
        <h3>9. CHỨC NĂNG QUẢN TRỊ HỆ THỐNG</h3>
        <div class="V2Siem-5-content">
            <div class="V2Siem-5-content--text">
                <p>Chức năng Dashboard cho phép người quản trị có thông tin tổng quát về hệ thống.</p>
                <p>Chức năng Event Map cho phép hiện thị trực quan theo thời gian thực tấn công mạng.</p>
                <p>Chức năng tạo báo cáo cho phép người quản trị tạo ra các báo cáo tùy biến theo từng điều kiện cụ thể theo các định dạng khác nhau.</p>
                <p>Quản lý cấu hình hệ thống.</p>
                <p>Quản lý các tài khoản quản trị hệ thống.</p>
                <p>Quản lý cập nhật phần mềm hệ thống từ Cloud.</p>
                <p>Thông tin trạng thái hệ thống.</p>
                <p>Quản lý logs hoạt động trên hệ thống.</p>
                <p>Quản trị hệ thống qua giao diện Console và SSH</p>
            </div>
            <img src="../assets/images/V2Siem/v2-7.png">
        </div>
    </div>
  </div>
</template>

<style scoped>
@import "../assets/V2Siem.css";
</style>

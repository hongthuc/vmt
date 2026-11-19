<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0" />
  <title>CÔNG TY TNHH TM DV XÂY DỰNG CƠ KHÍ VMT | Thiết Kế & Thi Công Trọn Gói Đà Nẵng - vmt.com</title>
  <meta name="description" content="CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ XÂY DỰNG CƠ KHÍ VMT - Chuyên thiết kế kiến trúc, thi công xây dựng nhà phố, biệt thự, khách sạn, căn hộ và gia công cơ khí kết cấu thép tại Đà Nẵng. Hotline: 0337.222.775." />

  <!-- Meta Open Graph & Thumbnail Chia Sẻ Link (Sử dụng ảnh Logo VMT khi chia sẻ link vmt.com) -->
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="XÂY DỰNG CƠ KHÍ VMT - vmt.com" />
  <meta property="og:url" content="https://vmt.com/" />
  <meta property="og:title" content="CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ XÂY DỰNG CƠ KHÍ VMT" />
  <meta property="og:description" content="Thiết kế kiến trúc - Thi công xây dựng trọn gói - Gia công cơ khí kết cấu thép uy tín tại Đà Nẵng. Hotline: 0337.222.775." />
  <meta property="og:image" content="https://vmt.com/wp-content/uploads/logo-vmt-thumbnail.png" />
  <meta property="og:image:width" content="1200" />
  <meta property="og:image:height" content="630" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="CÔNG TY TNHH TM DV XÂY DỰNG CƠ KHÍ VMT" />
  <meta name="twitter:description" content="Thiết kế & Thi công xây dựng cơ khí uy tín tại Đà Nẵng - vmt.com" />
  <meta name="twitter:image" content="https://vmt.com/wp-content/uploads/logo-vmt-thumbnail.png" />

  <!-- Favicon Logo VMT -->
  <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230F2C59'/%3E%3Cpath d='M12 20L24 46L36 20H29.5L24 33L18.5 20H12Z' fill='%23E59217'/%3E%3Cpath d='M36 46V20H52V25.5H42.5V30.5H50.5V35.5H42.5V46H36Z' fill='%23FFFFFF'/%3E%3C/svg%3E" />

  <!-- Font chữ Inter chuẩn hiện đại & dễ đọc -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" />

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            vmt: {
              navy: '#0F2C59',
              navyDark: '#091E3E',
              navyLight: '#1B427E',
              gold: '#D97706',
              goldLight: '#F59E0B',
              surface: '#F8FAFC',
              border: '#E2E8F0',
            }
          }
        }
      }
    }
  </script>

  <style>
    /* ==========================================================================
       CẤU HÌNH LAYOUT CHUẨN FLATSOME - CHỐNG TRÀN VIỀN & CHIỀU NGANG 95% DESKTOP
       ========================================================================== */
    *, *::before, *::after {
      box-sizing: border-box;
    }

    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      color: #1E293B;
      background-color: #FFFFFF;
      scroll-behavior: smooth;
      -webkit-font-smoothing: antialiased;
    }

    /* Container chính: 100% có đệm an toàn trên mobile, đúng 95% màn hình trên máy tính */
    .vmt-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 640px) {
      .vmt-container {
        padding-left: 20px;
        padding-right: 20px;
      }
    }

    @media (min-width: 1024px) {
      .vmt-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* ==========================================================================
       BANNER SLIDER - 2 BANNER KÍCH THƯỚC BẰNG NHAU TUYỆT ĐỐI & KHÔNG CẮT CHỮ
       ========================================================================== */
    .vmt-banner-grid {
      display: grid;
      grid-template-columns: 1fr;
      width: 100%;
      position: relative;
      overflow: hidden;
    }

    .vmt-banner-slide {
      grid-area: 1 / 1;
      opacity: 0;
      visibility: hidden;
      transition: opacity 0.7s ease, visibility 0.7s ease;
      position: relative;
      display: flex;
      align-items: center;
      width: 100%;
      min-height: 300px;
    }

    @media (min-width: 768px) {
      .vmt-banner-slide {
        min-height: 410px;
      }
    }

    @media (min-width: 1024px) {
      .vmt-banner-slide {
        min-height: 470px;
      }
    }

    .vmt-banner-slide.active {
      opacity: 1;
      visibility: visible;
      z-index: 2;
    }

    /* Menu Dropdown chuẩn Flatsome */
    .nav-dropdown-wrap {
      position: relative;
    }
    .nav-dropdown-menu {
      position: absolute;
      top: 100%;
      left: 0;
      min-width: 225px;
      background: #FFFFFF;
      border: 1px solid #E2E8F0;
      border-top: 2px solid #D97706;
      border-radius: 0 0 8px 8px;
      box-shadow: 0 12px 28px rgba(15, 44, 89, 0.12);
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.22s ease;
      z-index: 60;
      padding: 6px 0;
    }
    .nav-dropdown-wrap:hover .nav-dropdown-menu {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    /* Thanh cuộn ẩn cho thanh danh mục trên mobile */
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }

    /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
    @keyframes phonePulse {
      0%, 100% { transform: scale(1); box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.55); }
      50% { transform: scale(1.06); box-shadow: 0 0 0 10px rgba(220, 38, 38, 0); }
    }
    .btn-hotline-pulse {
      animation: phonePulse 2s infinite;
    }

    /* Đường gạch chân tiêu đề mục chuẩn Flatsome */
    .section-divider {
      width: 56px;
      height: 3px;
      background: linear-gradient(90deg, #0F2C59 0%, #D97706 100%);
      border-radius: 999px;
      margin: 10px auto 0;
    }

    /* Đảm bảo ảnh card đồng nhất tỉ lệ, không méo */
    .card-img-box {
      position: relative;
      width: 100%;
      aspect-ratio: 4 / 3;
      overflow: hidden;
      background-color: #E2E8F0;
    }
    .card-img-box img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
      transition: transform 0.45s ease;
    }
    .vmt-card:hover .card-img-box img {
      transform: scale(1.05);
    }
  </style>
</head>

<body class="bg-white text-slate-800">

  <!-- ========================================================================
       UXBUILDER SECTION 1: TOP BAR & HEADER CHÍNH (KHÔNG CÓ NÚT GỌI NGAY)
       ======================================================================== -->
  <div class="bg-vmt-navy text-white text-[11px] sm:text-xs py-1.5 border-b border-white/10">
    <div class="vmt-container flex flex-wrap items-center justify-between gap-y-1">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <a href="tel:0337222775" class="inline-flex items-center gap-1.5 hover:text-amber-400 transition">
          <i class="fa-solid fa-phone text-amber-400 text-[10px]"></i>
          <span class="font-medium">0337.222.775</span>
        </a>
        <span class="hidden sm:inline text-white/30">|</span>
        <span class="hidden md:inline-flex items-center gap-1.5 text-slate-200">
          <i class="fa-solid fa-location-dot text-amber-400 text-[10px]"></i>
          <span>69 Bàu Cầu 15, Phường Hòa Xuân, TP Đà Nẵng</span>
        </span>
      </div>
      <div class="flex items-center gap-3">
        <span class="hidden sm:inline text-slate-300">Website: <strong class="text-white">vmt.com</strong></span>
        <div class="flex items-center gap-2.5">
          <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" aria-label="Facebook VMT" class="hover:text-amber-400 transition">
            <i class="fa-brands fa-facebook-f"></i>
          </a>
          <a href="https://zalo.me/0337222775" target="_blank" rel="noopener noreferrer" aria-label="Zalo VMT" class="hover:text-amber-400 transition font-bold text-[10px]">
            Zalo
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- Header Sticky -->
  <header id="main-header" class="sticky top-0 z-50 bg-white/95 backdrop-blur-md border-b border-slate-200 shadow-sm">
    <div class="vmt-container">
      <div class="flex items-center justify-between h-14 md:h-16 gap-3">

        <!-- LOGO VMT CHUYÊN NGHIỆP - CHỈNH GỌN NHỎ LẠI -->
        <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group" aria-label="CÔNG TY TNHH TM DV XÂY DỰNG CƠ KHÍ VMT">
          <svg class="w-9 h-9 md:w-10 md:h-10 shrink-0 transition-transform duration-300 group-hover:scale-105" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Logo VMT">
            <!-- Khung khiên hình lục giác/bo góc kết cấu cơ khí xây dựng -->
            <rect x="2" y="2" width="60" height="60" rx="12" fill="#0F2C59"/>
            <rect x="5" y="5" width="54" height="54" rx="9" stroke="#D97706" stroke-width="1.5" stroke-opacity="0.7"/>
            <!-- Biểu tượng mái kiến trúc & kết cấu thép trên đỉnh -->
            <path d="M14 22L32 10L50 22" stroke="#F59E0B" stroke-width="3.2" stroke-linecap="round" stroke-linejoin="round"/>
            <!-- Chữ VMT cách điệu mạnh mẽ -->
            <path d="M12.5 27H17.8L21.5 39.2L25.2 27H30.3L24.1 45H18.9L12.5 27Z" fill="#FFFFFF"/>
            <path d="M31.8 27H37.2L40.5 37.8L43.8 27H49.2V45H45.2V33.6L41.8 45H39.1L35.7 33.6V45H31.8V27Z" fill="#F59E0B"/>
            <!-- Thanh nền kỹ thuật bên dưới -->
            <rect x="13" y="49" width="38" height="3" rx="1.5" fill="#FFFFFF" fill-opacity="0.9"/>
            <rect x="35" y="49" width="16" height="3" rx="1.5" fill="#F59E0B"/>
          </svg>
          <div class="leading-tight">
            <div class="text-sm md:text-[15px] font-extrabold tracking-tight text-vmt-navy">
              VMT <span class="text-vmt-gold">CONSTRUCTION</span>
            </div>
            <div class="text-[9px] md:text-[10px] font-semibold text-slate-500 uppercase tracking-wider">
              Xây Dựng &amp; Cơ Khí
            </div>
          </div>
        </a>

        <!-- MENU CHÍNH TRÊN MÁY TÍNH: VIẾT LIỀN TRÊN 1 HÀNG, CHỮ NHỎ GỌN, KHÔNG XUỐNG DÒNG -->
        <nav class="hidden lg:flex items-center justify-end flex-nowrap gap-3 xl:gap-5" aria-label="Menu chính">
          <a href="#trang-chu" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold text-vmt-navy hover:text-vmt-gold transition py-2">
            Trang chủ
          </a>
          <a href="#gioi-thieu" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-vmt-gold transition py-2">
            Giới thiệu
          </a>

          <!-- Dropdown Công trình thực tế (theo web mẫu tintruongthinh.com) -->
          <div class="nav-dropdown-wrap">
            <a href="#cong-trinh-thuc-te" class="whitespace-nowrap inline-flex items-center gap-1 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-vmt-gold transition py-2">
              <span>Công trình thực tế</span>
              <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
            </a>
            <div class="nav-dropdown-menu">
              <a href="#cong-trinh-thuc-te" onclick="filterProducts('khach-san-can-ho')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-vmt-gold">Khách sạn – Căn hộ – Phòng trọ</a>
              <a href="#cong-trinh-thuc-te" onclick="filterProducts('biet-thu')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-vmt-gold">Biệt thự</a>
              <a href="#cong-trinh-thuc-te" onclick="filterProducts('nha-pho')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-vmt-gold">Nhà phố</a>
              <a href="#cong-trinh-thuc-te" onclick="filterProducts('van-phong-co-khi')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-vmt-gold">Văn phòng – Cơ khí kết cấu</a>
            </div>
          </div>

          <a href="#du-an-da-nang" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-vmt-gold transition py-2">
            Dự án Đà Nẵng
          </a>

          <!-- Dropdown Lĩnh vực hoạt động -->
          <div class="nav-dropdown-wrap">
            <a href="#linh-vuc" class="whitespace-nowrap inline-flex items-center gap-1 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-vmt-gold transition py-2">
              <span>Lĩnh vực hoạt động</span>
              <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
            </a>
            <div class="nav-dropdown-menu">
              <a href="#linh-vuc" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-vmt-gold">Thiết kế Kiến trúc – Nội thất</a>
              <a href="#linh-vuc" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-vmt-gold">Thi công phần thô</a>
              <a href="#linh-vuc" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-vmt-gold">Thi công hoàn thiện</a>
              <a href="#linh-vuc" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-vmt-gold">Gia công cơ khí – Kết cấu thép</a>
            </div>
          </div>

          <!-- Dropdown Báo giá -->
          <div class="nav-dropdown-wrap">
            <a href="#bao-gia" class="whitespace-nowrap inline-flex items-center gap-1 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-vmt-gold transition py-2">
              <span>Báo giá</span>
              <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
            </a>
            <div class="nav-dropdown-menu">
              <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-vmt-gold">Báo giá thiết kế kiến trúc</a>
              <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-vmt-gold">Báo giá thi công phần thô</a>
              <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-vmt-gold">Báo giá thi công hoàn thiện</a>
              <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-vmt-gold">Báo giá thi công trọn gói</a>
            </div>
          </div>

          <a href="#tin-tuc" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-vmt-gold transition py-2">
            Tin tức
          </a>
          <a href="#doi-tac" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-vmt-gold transition py-2">
            Đối tác
          </a>
          <a href="#lien-he" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-vmt-gold transition py-2">
            Liên hệ
          </a>
        </nav>

        <!-- Nút Mở Menu Mobile (Không đặt nút Gọi ngay trên header để tránh tràn viền) -->
        <button id="mobileMenuBtn" type="button" aria-label="Mở menu điều hướng" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-vmt-navy hover:bg-slate-100 transition">
          <i class="fa-solid fa-bars text-lg"></i>
        </button>

      </div>
    </div>

    <!-- Menu Mobile Drawer -->
    <div id="mobileMenu" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
      <div class="vmt-container py-3 flex flex-col divide-y divide-slate-100 text-sm font-semibold">
        <a href="#trang-chu" class="mobile-nav-link py-2.5 text-vmt-navy hover:text-vmt-gold">Trang chủ</a>
        <a href="#gioi-thieu" class="mobile-nav-link py-2.5 text-slate-700 hover:text-vmt-gold">Giới thiệu</a>
        <a href="#linh-vuc" class="mobile-nav-link py-2.5 text-slate-700 hover:text-vmt-gold">Lĩnh vực hoạt động</a>
        <a href="#cong-trinh-thuc-te" class="mobile-nav-link py-2.5 text-slate-700 hover:text-vmt-gold">Công trình thực tế</a>
        <a href="#du-an-da-nang" class="mobile-nav-link py-2.5 text-slate-700 hover:text-vmt-gold">Dự án Đà Nẵng</a>
        <a href="#bao-gia" class="mobile-nav-link py-2.5 text-slate-700 hover:text-vmt-gold">Yêu cầu &amp; Báo giá</a>
        <a href="#tin-tuc" class="mobile-nav-link py-2.5 text-slate-700 hover:text-vmt-gold">Tin tức</a>
        <a href="#doi-tac" class="mobile-nav-link py-2.5 text-slate-700 hover:text-vmt-gold">Đối tác</a>
        <a href="#lien-he" class="mobile-nav-link py-2.5 text-slate-700 hover:text-vmt-gold">Bản đồ &amp; Liên hệ</a>
      </div>
    </div>
  </header>

  <main id="trang-chu" class="w-full overflow-x-hidden">

    <!-- ========================================================================
         UXBUILDER SECTION 2: 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (KÍCH THƯỚC BẰNG NHAU)
         Chữ nằm gọn hoàn toàn bên trong, cách xa viền ảnh, không bị thiếu chữ trên Mobile & PC
         ======================================================================== -->
    <section class="w-full bg-vmt-navyDark relative" aria-label="Banner giới thiệu VMT">
      <div id="heroBannerSlider" class="vmt-banner-grid">

        <!-- BANNER 1 -->
        <div class="vmt-banner-slide active">
          <!-- Ảnh nền thi công thực tế Drive 1 -->
          <img
            src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1600"
            data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
            data-fallback-label="Xay Dung Co Khi VMT Da Nang"
            onerror="handleDriveImageError(this)"
            alt="Thi công xây dựng trọn gói VMT Đà Nẵng"
            class="absolute inset-0 w-full h-full object-cover object-center"
          />
          <!-- Lớp phủ gradient giúp chữ tương phản sắc nét -->
          <div class="absolute inset-0 bg-gradient-to-r from-[#091E3E]/92 via-[#0F2C59]/80 to-[#091E3E]/55"></div>

          <!-- Nội dung nằm trong khung an toàn, cách xa viền ảnh banner -->
          <div class="relative z-10 w-full py-10 sm:py-14 md:py-16 px-12 sm:px-16 md:px-24 lg:px-28">
            <div class="max-w-2xl mx-auto md:mx-0 text-center md:text-left">
              <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-[0.16em] text-amber-400 mb-2 sm:mb-3">
                CÔNG TY TNHH TM DV XÂY DỰNG CƠ KHÍ VMT
              </p>
              <h1 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold text-white leading-snug mb-3 sm:mb-4">
                THIẾT KẾ &amp; THI CÔNG XÂY DỰNG TRỌN GÓI TẠI ĐÀ NẴNG
              </h1>
              <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-5 sm:mb-6">
                Chuyên Nhà phố, Biệt thự, Khách sạn, Căn hộ và Văn phòng với tiêu chuẩn kỹ thuật vững chắc, tiến độ minh bạch và bảo hành dài lâu.
              </p>
              <div class="flex flex-wrap items-center justify-center md:justify-start gap-2.5 sm:gap-3">
                <a href="#bao-gia" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-vmt-gold hover:bg-amber-600 text-white text-xs sm:text-sm font-bold shadow-md transition">
                  Nhận Báo Giá Miễn Phí
                </a>
                <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold backdrop-blur-sm transition">
                  Xem Dự Án Đà Nẵng
                </a>
              </div>
            </div>
          </div>
        </div>

        <!-- BANNER 2 -->
        <div class="vmt-banner-slide">
          <!-- Ảnh nền dự án thực tế Đà Nẵng Drive -->
          <img
            src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1600"
            data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
            data-fallback-label="Co Khi Ket Cau Thep VMT"
            onerror="handleDriveImageError(this)"
            alt="Gia công cơ khí và kết cấu thép VMT"
            class="absolute inset-0 w-full h-full object-cover object-center"
          />
          <div class="absolute inset-0 bg-gradient-to-r from-[#091E3E]/92 via-[#0F2C59]/80 to-[#091E3E]/55"></div>

          <!-- Nội dung nằm trong khung an toàn, cách xa viền ảnh banner -->
          <div class="relative z-10 w-full py-10 sm:py-14 md:py-16 px-12 sm:px-16 md:px-24 lg:px-28">
            <div class="max-w-2xl mx-auto md:mx-0 text-center md:text-left">
              <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-[0.16em] text-amber-400 mb-2 sm:mb-3">
                UY TÍN – AN TOÀN – CHẤT LƯỢNG – ĐÚNG TIẾN ĐỘ
              </p>
              <h2 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold text-white leading-snug mb-3 sm:mb-4">
                GIA CÔNG CƠ KHÍ, KẾT CẤU THÉP &amp; HOÀN THIỆN CÔNG TRÌNH
              </h2>
              <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-5 sm:mb-6">
                Giải pháp tối ưu chi phí từ phần thô, cơ khí nhà xưởng đến hoàn thiện nội ngoại thất cho chủ đầu tư khu vực Đà Nẵng và miền Trung.
              </p>
              <div class="flex flex-wrap items-center justify-center md:justify-start gap-2.5 sm:gap-3">
                <a href="#cong-trinh-thuc-te" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-vmt-gold hover:bg-amber-600 text-white text-xs sm:text-sm font-bold shadow-md transition">
                  Công Trình Thực Tế
                </a>
                <a href="tel:0337222775" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold backdrop-blur-sm transition">
                  Hotline: 0337.222.775
                </a>
              </div>
            </div>
          </div>
        </div>

        <!-- Nút điều hướng Trái / Phải đặt gọn sát mép, không đè chữ -->
        <button id="bannerPrev" type="button" aria-label="Banner trước" class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-vmt-gold text-white flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
        </button>
        <button id="bannerNext" type="button" aria-label="Banner kế tiếp" class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-vmt-gold text-white flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
        </button>

        <!-- Chấm chỉ thị slide -->
        <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button type="button" data-slide="0" aria-label="Xem banner 1" class="banner-dot w-6 h-2 rounded-full bg-vmt-gold transition-all"></button>
          <button type="button" data-slide="1" aria-label="Xem banner 2" class="banner-dot w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all"></button>
        </div>
      </div>
    </section>

    <!-- ========================================================================
         UXBUILDER SECTION 3: DỊCH VỤ TIÊU BIỂU (LĨNH VỰC HOẠT ĐỘNG - THEO WEB MẪU)
         ======================================================================== -->
    <section id="linh-vuc" class="py-10 md:py-14 bg-white">
      <div class="vmt-container">
        <div class="text-center mb-7 md:mb-9">
          <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-vmt-navy uppercase tracking-wide">
            DỊCH VỤ TIÊU BIỂU
          </h2>
          <div class="section-divider"></div>
        </div>

        <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
          <!-- Dịch vụ 1 -->
          <a href="#bao-gia" class="group bg-vmt-surface border border-slate-200 rounded-xl p-4 sm:p-6 text-center hover:border-vmt-gold hover:shadow-md transition">
            <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 rounded-xl bg-vmt-navy text-amber-400 flex items-center justify-center text-lg sm:text-xl group-hover:bg-vmt-gold group-hover:text-white transition">
              <i class="fa-solid fa-compass-drafting"></i>
            </div>
            <h3 class="text-xs sm:text-sm md:text-base font-bold text-vmt-navy uppercase mb-1.5 break-words">
              Thiết Kế Kiến Trúc
            </h3>
            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
              Tư vấn thiết kế kiến trúc nhà phố, biệt thự, khách sạn, căn hộ tối ưu công năng &amp; thẩm mỹ.
            </p>
          </a>

          <!-- Dịch vụ 2 -->
          <a href="#bao-gia" class="group bg-vmt-surface border border-slate-200 rounded-xl p-4 sm:p-6 text-center hover:border-vmt-gold hover:shadow-md transition">
            <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 rounded-xl bg-vmt-navy text-amber-400 flex items-center justify-center text-lg sm:text-xl group-hover:bg-vmt-gold group-hover:text-white transition">
              <i class="fa-solid fa-trowel-bricks"></i>
            </div>
            <h3 class="text-xs sm:text-sm md:text-base font-bold text-vmt-navy uppercase mb-1.5 break-words">
              Thi Công Xây Dựng
            </h3>
            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
              Thi công phần thô, hoàn thiện và xây nhà trọn gói cam kết đúng bản vẽ, đúng tiến độ.
            </p>
          </a>

          <!-- Dịch vụ 3 -->
          <a href="#bao-gia" class="group bg-vmt-surface border border-slate-200 rounded-xl p-4 sm:p-6 text-center hover:border-vmt-gold hover:shadow-md transition">
            <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 rounded-xl bg-vmt-navy text-amber-400 flex items-center justify-center text-lg sm:text-xl group-hover:bg-vmt-gold group-hover:text-white transition">
              <i class="fa-solid fa-gears"></i>
            </div>
            <h3 class="text-xs sm:text-sm md:text-base font-bold text-vmt-navy uppercase mb-1.5 break-words">
              Gia Công Cơ Khí
            </h3>
            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
              Thi công nhà thép tiền chế, kết cấu thép, mái che, cổng sắt, lan can và hệ thống M&amp;E.
            </p>
          </a>

          <!-- Dịch vụ 4 -->
          <a href="#bao-gia" class="group bg-vmt-surface border border-slate-200 rounded-xl p-4 sm:p-6 text-center hover:border-vmt-gold hover:shadow-md transition">
            <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 rounded-xl bg-vmt-navy text-amber-400 flex items-center justify-center text-lg sm:text-xl group-hover:bg-vmt-gold group-hover:text-white transition">
              <i class="fa-solid fa-couch"></i>
            </div>
            <h3 class="text-xs sm:text-sm md:text-base font-bold text-vmt-navy uppercase mb-1.5 break-words">
              Thi Công Nội Thất
            </h3>
            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
              Thiết kế và thi công hoàn thiện nội thất căn hộ, văn phòng, biệt thự hiện đại bền đẹp.
            </p>
          </a>
        </div>
      </div>
    </section>

    <!-- ========================================================================
         UXBUILDER SECTION 4: GIỚI THIỆU CÔNG TY VMT & THẾ MẠNH CỦA CHÚNG TÔI
         ======================================================================== -->
    <section id="gioi-thieu" class="py-10 md:py-14 bg-vmt-surface border-y border-slate-200">
      <div class="vmt-container">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center mb-10">
          <!-- Cột giới thiệu công ty -->
          <div class="lg:col-span-7">
            <p class="text-xs font-bold uppercase tracking-wider text-vmt-gold mb-1.5">VỀ CHÚNG TÔI</p>
            <h2 class="text-lg sm:text-2xl font-extrabold text-vmt-navy leading-snug mb-3">
              CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ XÂY DỰNG CƠ KHÍ VMT
            </h2>
            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed mb-3">
              <strong>VMT</strong> chuyên Thiết kế Kiến trúc – Thi công Xây dựng trọn gói – Gia công Cơ khí kết cấu thép và Hoàn thiện Nội thất cho các công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ, Văn phòng tại khu vực <strong>Đà Nẵng – Quảng Nam</strong>.
            </p>
            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed mb-4">
              Với phương châm <strong>“Nhà ở Gia đình – Tiêu chuẩn Công trình”</strong>, chúng tôi đặt chữ <strong>TÂM</strong> và chất lượng kỹ thuật lên hàng đầu để mỗi công trình bàn giao đều đạt chuẩn <strong>AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – THẨM MỸ</strong>.
            </p>
            <div class="grid grid-cols-3 gap-3 pt-2">
              <div class="bg-white rounded-lg border border-slate-200 p-3 text-center">
                <div class="text-lg sm:text-2xl font-extrabold text-vmt-gold">100%</div>
                <div class="text-[11px] sm:text-xs font-medium text-slate-600">Đúng Tiến Độ</div>
              </div>
              <div class="bg-white rounded-lg border border-slate-200 p-3 text-center">
                <div class="text-lg sm:text-2xl font-extrabold text-vmt-navy">5+ Năm</div>
                <div class="text-[11px] sm:text-xs font-medium text-slate-600">Bảo Hành Kết Cấu</div>
              </div>
              <div class="bg-white rounded-lg border border-slate-200 p-3 text-center">
                <div class="text-lg sm:text-2xl font-extrabold text-vmt-gold">24/7</div>
                <div class="text-[11px] sm:text-xs font-medium text-slate-600">Tư Vấn Miễn Phí</div>
              </div>
            </div>
          </div>

          <!-- Cột hình ảnh thực tế giới thiệu -->
          <div class="lg:col-span-5">
            <div class="rounded-xl overflow-hidden shadow-md border border-slate-200 bg-white">
              <div class="card-img-box">
                <img
                  src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w1000"
                  data-drive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
                  data-fallback-label="Thi Cong Thuc Te VMT"
                  onerror="handleDriveImageError(this)"
                  alt="Hình ảnh thi công thực tế Công ty Xây dựng Cơ khí VMT"
                />
              </div>
            </div>
          </div>
        </div>

        <!-- 6 Thế mạnh của chúng tôi (chuẩn web mẫu tintruongthinh.com) -->
        <div class="text-center mb-6">
          <h3 class="text-base sm:text-xl font-extrabold text-vmt-navy uppercase">THẾ MẠNH CỦA CHÚNG TÔI</h3>
          <div class="section-divider"></div>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
          <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 flex items-start gap-3.5">
            <div class="w-10 h-10 rounded-lg bg-vmt-navy/10 text-vmt-navy flex items-center justify-center shrink-0">
              <i class="fa-solid fa-helmet-safety"></i>
            </div>
            <div>
              <h4 class="text-sm font-bold text-vmt-navy mb-1">Đội ngũ kỹ sư, thợ lành nghề</h4>
              <p class="text-xs text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư xây dựng, cơ khí giàu kinh nghiệm trực tiếp giám sát.</p>
            </div>
          </div>

          <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 flex items-start gap-3.5">
            <div class="w-10 h-10 rounded-lg bg-vmt-navy/10 text-vmt-navy flex items-center justify-center shrink-0">
              <i class="fa-solid fa-layer-group"></i>
            </div>
            <div>
              <h4 class="text-sm font-bold text-vmt-navy mb-1">Cập nhật xu hướng hiện đại</h4>
              <p class="text-xs text-slate-600 leading-relaxed">Áp dụng vật liệu mới, giải pháp kết cấu tối ưu và phong cách kiến trúc bền vững theo thời gian.</p>
            </div>
          </div>

          <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 flex items-start gap-3.5">
            <div class="w-10 h-10 rounded-lg bg-vmt-navy/10 text-vmt-navy flex items-center justify-center shrink-0">
              <i class="fa-solid fa-clipboard-check"></i>
            </div>
            <div>
              <h4 class="text-sm font-bold text-vmt-navy mb-1">Giám sát tiến độ chuẩn xác</h4>
              <p class="text-xs text-slate-600 leading-relaxed">Báo cáo tiến độ từng hạng mục thường xuyên giúp chủ đầu tư dễ dàng theo dõi từ xa.</p>
            </div>
          </div>

          <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 flex items-start gap-3.5">
            <div class="w-10 h-10 rounded-lg bg-vmt-navy/10 text-vmt-navy flex items-center justify-center shrink-0">
              <i class="fa-solid fa-shield-halved"></i>
            </div>
            <div>
              <h4 class="text-sm font-bold text-vmt-navy mb-1">Bảo hành công trình lâu dài</h4>
              <p class="text-xs text-slate-600 leading-relaxed">Chính sách hậu mãi minh bạch, hỗ trợ nhanh chóng khi khách hàng có nhu cầu bảo trì.</p>
            </div>
          </div>

          <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 flex items-start gap-3.5">
            <div class="w-10 h-10 rounded-lg bg-vmt-navy/10 text-vmt-navy flex items-center justify-center shrink-0">
              <i class="fa-solid fa-hand-holding-dollar"></i>
            </div>
            <div>
              <h4 class="text-sm font-bold text-vmt-navy mb-1">Chi phí minh bạch, hợp lý</h4>
              <p class="text-xs text-slate-600 leading-relaxed">Dự toán chi tiết từng hạng mục, hạn chế phát sinh và cân đối ngân sách hiệu quả nhất.</p>
            </div>
          </div>

          <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 flex items-start gap-3.5">
            <div class="w-10 h-10 rounded-lg bg-vmt-navy/10 text-vmt-navy flex items-center justify-center shrink-0">
              <i class="fa-solid fa-headset"></i>
            </div>
            <div>
              <h4 class="text-sm font-bold text-vmt-navy mb-1">Hỗ trợ tư vấn miễn phí 24/7</h4>
              <p class="text-xs text-slate-600 leading-relaxed">Khảo sát thực tế tận nơi tại Đà Nẵng, tư vấn phương án thi công và báo giá hoàn toàn miễn phí.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ========================================================================
         UXBUILDER SECTION 5: SẢN PHẨM & CÔNG TRÌNH THI CÔNG THỰC TẾ (9 ẢNH DRIVE)
         - Danh mục gọn đẹp 1 hàng trên PC, không ngắt dòng trong tên danh mục
         - Chia 2 cột trên điện thoại, KHÔNG nhãn dán đè lên ảnh, tên sản phẩm đầy đủ
         ======================================================================== -->
    <section id="cong-trinh-thuc-te" class="py-10 md:py-14 bg-white">
      <div class="vmt-container">
        <div class="text-center mb-5 md:mb-7">
          <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-vmt-navy uppercase tracking-wide">
            SẢN PHẨM &amp; CÔNG TRÌNH THI CÔNG THỰC TẾ
          </h2>
          <div class="section-divider"></div>
        </div>

        <!-- Thanh Danh Mục Sản Phẩm (Gọn đẹp 1 hàng trên máy tính, tên từng danh mục không bao giờ xuống dòng) -->
        <div class="flex flex-wrap items-center justify-center gap-2 mb-6 md:mb-8" id="productCategoryTabs" role="tablist">
          <button type="button" data-cat="all" class="cat-tab active whitespace-nowrap px-3 py-1.5 md:px-4 md:py-2 rounded-lg text-[11.5px] sm:text-xs font-semibold border transition bg-vmt-navy text-white border-vmt-navy">
            Tất cả
          </button>
          <button type="button" data-cat="nha-pho" class="cat-tab whitespace-nowrap px-3 py-1.5 md:px-4 md:py-2 rounded-lg text-[11.5px] sm:text-xs font-semibold border transition bg-white text-slate-700 border-slate-200 hover:border-vmt-gold hover:text-vmt-navy">
            Nhà phố
          </button>
          <button type="button" data-cat="biet-thu" class="cat-tab whitespace-nowrap px-3 py-1.5 md:px-4 md:py-2 rounded-lg text-[11.5px] sm:text-xs font-semibold border transition bg-white text-slate-700 border-slate-200 hover:border-vmt-gold hover:text-vmt-navy">
            Biệt thự
          </button>
          <button type="button" data-cat="khach-san-can-ho" class="cat-tab whitespace-nowrap px-3 py-1.5 md:px-4 md:py-2 rounded-lg text-[11.5px] sm:text-xs font-semibold border transition bg-white text-slate-700 border-slate-200 hover:border-vmt-gold hover:text-vmt-navy">
            Khách sạn – Căn hộ
          </button>
          <button type="button" data-cat="van-phong-co-khi" class="cat-tab whitespace-nowrap px-3 py-1.5 md:px-4 md:py-2 rounded-lg text-[11.5px] sm:text-xs font-semibold border transition bg-white text-slate-700 border-slate-200 hover:border-vmt-gold hover:text-vmt-navy">
            Văn phòng – Cơ khí
          </button>
          <button type="button" data-cat="thi-cong-phan-tho" class="cat-tab whitespace-nowrap px-3 py-1.5 md:px-4 md:py-2 rounded-lg text-[11.5px] sm:text-xs font-semibold border transition bg-white text-slate-700 border-slate-200 hover:border-vmt-gold hover:text-vmt-navy">
            Thi công phần thô
          </button>
        </div>

        <!-- Lưới sản phẩm thi công thực tế: 2 cột trên điện thoại, 3 cột tablet/laptop, 4 cột desktop -->
        <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
          <!-- Render động bằng JavaScript từ 9 ảnh thực tế Google Drive -->
        </div>
      </div>
    </section>

    <!-- ========================================================================
         UXBUILDER SECTION 6: CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (10 ẢNH DRIVE)
         - 2 cột trên điện thoại, không nhãn dán đè ảnh, hiển thị đầy đủ tên dự án
         ======================================================================== -->
    <section id="du-an-da-nang" class="py-10 md:py-14 bg-vmt-surface border-t border-slate-200">
      <div class="vmt-container">
        <div class="text-center mb-6 md:mb-8">
          <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-vmt-navy uppercase tracking-wide">
            CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
          </h2>
          <p class="text-xs sm:text-sm text-slate-600 mt-1.5 max-w-2xl mx-auto">
            Hình ảnh thực tế các công trình xây dựng, hoàn thiện và cơ khí do VMT triển khai tại Hòa Xuân, Cẩm Lệ, Hải Châu, Sơn Trà, Ngũ Hành Sơn và Liên Chiểu.
          </p>
          <div class="section-divider"></div>
        </div>

        <!-- Lưới 10 dự án Đà Nẵng: 2 cột trên mobile, 4-5 cột trên PC -->
        <div id="danangProjectsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
          <!-- Render động bằng JavaScript từ 10 ảnh dự án Đà Nẵng Google Drive -->
        </div>
      </div>
    </section>

    <!-- ========================================================================
         UXBUILDER SECTION 7: FORM YÊU CẦU & BÁO GIÁ MIỄN PHÍ TRANG CHỦ
         ======================================================================== -->
    <section id="bao-gia" class="py-10 md:py-14 bg-vmt-navy text-white">
      <div class="vmt-container">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">

          <!-- Thông tin báo giá tham khảo -->
          <div class="lg:col-span-5">
            <p class="text-xs font-bold uppercase tracking-wider text-amber-400 mb-1.5">MIỄN PHÍ TƯ VẤN &amp; KHẢO SÁT</p>
            <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold leading-snug mb-3">
              YÊU CẦU BÁO GIÁ THIẾT KẾ &amp; THI CÔNG XÂY DỰNG
            </h2>
            <p class="text-xs sm:text-sm text-slate-200 leading-relaxed mb-5">
              Quý khách vui lòng để lại thông tin công trình, đội ngũ kỹ sư VMT sẽ liên hệ tư vấn phương án tối ưu và gửi bảng dự toán chi tiết hoàn toàn miễn phí.
            </p>

            <div class="space-y-2.5 text-xs sm:text-sm">
              <div class="flex items-center justify-between bg-white/10 rounded-lg px-4 py-2.5 border border-white/10">
                <span class="font-medium text-slate-100">Thiết kế Kiến trúc – Nội thất</span>
                <span class="font-bold text-amber-400">Tư vấn &amp; Báo giá</span>
              </div>
              <div class="flex items-center justify-between bg-white/10 rounded-lg px-4 py-2.5 border border-white/10">
                <span class="font-medium text-slate-100">Thi công Phần thô &amp; Nhân công</span>
                <span class="font-bold text-amber-400">Báo giá theo m²</span>
              </div>
              <div class="flex items-center justify-between bg-white/10 rounded-lg px-4 py-2.5 border border-white/10">
                <span class="font-medium text-slate-100">Thi công Trọn gói Chìa khóa trao tay</span>
                <span class="font-bold text-amber-400">Ưu đãi thiết kế</span>
              </div>
              <div class="flex items-center justify-between bg-white/10 rounded-lg px-4 py-2.5 border border-white/10">
                <span class="font-medium text-slate-100">Gia công Cơ khí &amp; Kết cấu thép</span>
                <span class="font-bold text-amber-400">Khảo sát tận nơi</span>
              </div>
            </div>
          </div>

          <!-- Form đăng ký yêu cầu báo giá -->
          <div class="lg:col-span-7">
            <form id="quoteForm" class="bg-white text-slate-800 rounded-xl p-5 sm:p-7 shadow-xl">
              <h3 class="text-base sm:text-lg font-extrabold text-vmt-navy mb-4">
                GỬI YÊU CẦU BÁO GIÁ NHANH
              </h3>
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5 mb-3.5">
                <div>
                  <label for="qName" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên <span class="text-red-500">*</span></label>
                  <input id="qName" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-vmt-gold focus:ring-1 focus:ring-vmt-gold" />
                </div>
                <div>
                  <label for="qPhone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại <span class="text-red-500">*</span></label>
                  <input id="qPhone" type="tel" required placeholder="VD: 0337.222.775" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-vmt-gold focus:ring-1 focus:ring-vmt-gold" />
                </div>
                <div>
                  <label for="qType" class="block text-xs font-semibold text-slate-700 mb-1">Loại công trình</label>
                  <select id="qType" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:outline-none focus:border-vmt-gold focus:ring-1 focus:ring-vmt-gold">
                    <option value="Nhà phố">Nhà phố</option>
                    <option value="Biệt thự">Biệt thự</option>
                    <option value="Khách sạn - Căn hộ - Phòng trọ">Khách sạn – Căn hộ – Phòng trọ</option>
                    <option value="Văn phòng">Văn phòng</option>
                    <option value="Gia công cơ khí - Kết cấu thép">Gia công cơ khí – Kết cấu thép</option>
                    <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                  </select>
                </div>
                <div>
                  <label for="qBudget" class="block text-xs font-semibold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                  <select id="qBudget" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:outline-none focus:border-vmt-gold focus:ring-1 focus:ring-vmt-gold">
                    <option value="Chưa xác định">Chưa xác định</option>
                    <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                    <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                    <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                    <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                  </select>
                </div>
              </div>

              <div class="mb-3.5">
                <label for="qEmail" class="block text-xs font-semibold text-slate-700 mb-1">Email (không bắt buộc)</label>
                <input id="qEmail" type="email" placeholder="Nhập địa chỉ email nhận bảng báo giá" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-vmt-gold focus:ring-1 focus:ring-vmt-gold" />
              </div>

              <div class="mb-4">
                <label for="qNote" class="block text-xs font-semibold text-slate-700 mb-1">Nội dung yêu cầu (diện tích, số tầng, địa điểm...)</label>
                <textarea id="qNote" rows="3" placeholder="VD: Xây nhà phố 3 tầng diện tích 5x20m tại Hòa Xuân, Đà Nẵng..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-vmt-gold focus:ring-1 focus:ring-vmt-gold"></textarea>
              </div>

              <button type="submit" class="w-full py-3 rounded-lg bg-vmt-gold hover:bg-amber-600 text-white font-bold text-sm uppercase tracking-wide shadow transition">
                GỬI YÊU CẦU BÁO GIÁ NGAY
              </button>
            </form>
          </div>
        </div>
      </div>
    </section>

    <!-- ========================================================================
         UXBUILDER SECTION 8: DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ
         ======================================================================== -->
    <section id="tin-tuc" class="py-10 md:py-14 bg-white">
      <div class="vmt-container">
        <div class="text-center mb-6 md:mb-8">
          <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-vmt-navy uppercase tracking-wide">
            TIN TỨC &amp; KINH NGHIỆM XÂY DỰNG
          </h2>
          <div class="section-divider"></div>
        </div>

        <div id="newsGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
          <!-- Render động bài viết -->
        </div>
      </div>
    </section>

    <!-- ========================================================================
         UXBUILDER SECTION 9: DANH MỤC CÁC ĐỐI TÁC
         ======================================================================== -->
    <section id="doi-tac" class="py-10 md:py-12 bg-vmt-surface border-y border-slate-200">
      <div class="vmt-container">
        <div class="text-center mb-6 md:mb-8">
          <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-vmt-navy uppercase tracking-wide">
            ĐỐI TÁC ĐỒNG HÀNH
          </h2>
          <div class="section-divider"></div>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-3">
          <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-16 hover:border-vmt-gold transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-blue-900">HÒA PHÁT</span>
          </div>
          <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-16 hover:border-vmt-gold transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-red-700">HOA SEN</span>
          </div>
          <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-16 hover:border-vmt-gold transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-sky-700">DULUX</span>
          </div>
          <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-16 hover:border-vmt-gold transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-slate-800">XINGFA</span>
          </div>
          <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-16 hover:border-vmt-gold transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-emerald-700">XUÂN THÀNH</span>
          </div>
          <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-16 hover:border-vmt-gold transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-amber-700">CADIVI</span>
          </div>
          <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-16 hover:border-vmt-gold transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-indigo-800">INAX</span>
          </div>
          <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-16 hover:border-vmt-gold transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-blue-800">VIỆT NHẬT</span>
          </div>
        </div>
      </div>
    </section>

    <!-- ========================================================================
         UXBUILDER SECTION 10: GOOGLE MAP & FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ
         ======================================================================== -->
    <section id="lien-he" class="py-10 md:py-14 bg-white">
      <div class="vmt-container">
        <div class="text-center mb-6 md:mb-8">
          <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-vmt-navy uppercase tracking-wide">
            BẢN ĐỒ ĐỊA CHỈ &amp; FANPAGE CHÍNH THỨC
          </h2>
          <div class="section-divider"></div>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 md:gap-6 items-stretch">

          <!-- Cột Trái: Google Map Trực Tiếp Địa Chỉ 69 Bàu Cầu 15, Hòa Xuân, Đà Nẵng -->
          <div class="lg:col-span-7 flex flex-col bg-vmt-surface border border-slate-200 rounded-xl overflow-hidden shadow-sm">
            <div class="px-4 py-3 bg-vmt-navy text-white flex flex-wrap items-center justify-between gap-2">
              <div class="flex items-center gap-2 text-xs sm:text-sm font-bold">
                <i class="fa-solid fa-map-location-dot text-amber-400"></i>
                <span>69 Bàu Cầu 15, Phường Hòa Xuân, TP Đà Nẵng</span>
              </div>
              <a href="https://www.google.com/maps/search/?api=1&query=69+B%C3%A0u+C%E1%BA%A7u+15,+H%C3%B2a+Xu%C3%A2n,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-[11px] sm:text-xs font-semibold text-amber-300 hover:text-white underline">
                Mở Google Maps
              </a>
            </div>
            <div class="w-full flex-1 min-h-[280px] sm:min-h-[340px]">
              <iframe
                title="Bản đồ Công ty TNHH TM DV Xây Dựng Cơ Khí VMT - 69 Bàu Cầu 15, Hòa Xuân, Đà Nẵng"
                src="https://www.google.com/maps?q=69+B%C3%A0u+C%E1%BA%A7u+15,+H%C3%B2a+Xu%C3%A2n,+%C4%90%C3%A0+N%E1%BA%B5ng&output=embed"
                class="w-full h-full min-h-[280px] sm:min-h-[340px] border-0 block"
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"
              ></iframe>
            </div>
          </div>

          <!-- Cột Phải: Khung Fanpage Facebook Ngoài Trang Chủ -->
          <div class="lg:col-span-5 flex flex-col bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm">
            <div class="px-4 py-3 bg-[#1877F2] text-white flex items-center justify-between">
              <div class="flex items-center gap-2 text-xs sm:text-sm font-bold">
                <i class="fa-brands fa-facebook text-base"></i>
                <span>FANPAGE FACEBOOK VMT</span>
              </div>
              <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" class="text-[11px] bg-white text-[#1877F2] font-bold px-2.5 py-1 rounded-md hover:bg-slate-100 transition">
                Theo dõi
              </a>
            </div>

            <!-- Giao diện Facebook Page Card -->
            <div class="relative h-36 sm:h-40 bg-vmt-navy overflow-hidden">
              <img
                src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w1000"
                data-drive-id="1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff"
                data-fallback-label="Fanpage VMT Da Nang"
                onerror="handleDriveImageError(this)"
                alt="Ảnh bìa Fanpage Xây Dựng Cơ Khí VMT"
                class="w-full h-full object-cover opacity-80"
              />
              <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
              <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                <div class="w-12 h-12 rounded-lg bg-vmt-navy border-2 border-white flex items-center justify-center shrink-0 shadow">
                  <span class="text-sm font-extrabold text-amber-400">VMT</span>
                </div>
                <div class="min-w-0 text-white">
                  <div class="text-sm font-bold leading-tight truncate">Xây Dựng Cơ Khí VMT - Đà Nẵng</div>
                  <div class="text-[11px] text-slate-200">Công ty Xây dựng &amp; Cơ khí • vmt.com</div>
                </div>
              </div>
            </div>

            <div class="p-4 flex-1 flex flex-col justify-between gap-4">
              <div class="space-y-2.5 text-xs sm:text-sm text-slate-700">
                <p class="leading-relaxed">
                  Theo dõi Fanpage chính thức của <strong>CÔNG TY TNHH TM DV XÂY DỰNG CƠ KHÍ VMT</strong> để cập nhật hình ảnh thi công thực tế hàng ngày, mẫu thiết kế mới và ưu đãi xây nhà trọn gói tại Đà Nẵng.
                </p>
                <div class="bg-slate-50 border border-slate-200 rounded-lg p-3 text-xs space-y-1.5">
                  <div class="flex items-center gap-2 text-slate-700">
                    <i class="fa-solid fa-phone text-[#1877F2] w-4"></i>
                    <span>Hotline tư vấn: <strong>0337.222.775</strong></span>
                  </div>
                  <div class="flex items-center gap-2 text-slate-700">
                    <i class="fa-solid fa-globe text-[#1877F2] w-4"></i>
                    <span>Website: <strong>vmt.com</strong></span>
                  </div>
                  <div class="flex items-center gap-2 text-slate-700">
                    <i class="fa-solid fa-location-dot text-[#1877F2] w-4"></i>
                    <span>69 Bàu Cầu 15, P. Hòa Xuân, TP Đà Nẵng</span>
                  </div>
                </div>
              </div>

              <div class="grid grid-cols-2 gap-2.5">
                <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-1.5 py-2.5 px-3 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold transition">
                  <i class="fa-solid fa-thumbs-up"></i>
                  <span>Thích Fanpage</span>
                </a>
                <a href="https://zalo.me/0337222775" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-1.5 py-2.5 px-3 rounded-lg bg-slate-100 hover:bg-slate-200 text-vmt-navy text-xs font-bold transition">
                  <i class="fa-solid fa-comment-dots"></i>
                  <span>Nhắn Tin Ngay</span>
                </a>
              </div>
            </div>
          </div>

        </div>
      </div>
    </section>

  </main>

  <!-- ========================================================================
       UXBUILDER SECTION 11: FOOTER CHUẨN FLATSOME
       ======================================================================== -->
  <footer class="bg-vmt-navyDark text-slate-300 pt-10 pb-6 border-t-4 border-vmt-gold">
    <div class="vmt-container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-7 pb-8 border-b border-white/10">

        <!-- Cột 1: Thông tin doanh nghiệp -->
        <div class="lg:col-span-5">
          <div class="flex items-center gap-2.5 mb-3">
            <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
              <rect x="2" y="2" width="60" height="60" rx="12" fill="#0F2C59" stroke="#F59E0B" stroke-width="2"/>
              <path d="M14 22L32 10L50 22" stroke="#F59E0B" stroke-width="3.2" stroke-linecap="round" stroke-linejoin="round"/>
              <path d="M12.5 27H17.8L21.5 39.2L25.2 27H30.3L24.1 45H18.9L12.5 27Z" fill="#FFFFFF"/>
              <path d="M31.8 27H37.2L40.5 37.8L43.8 27H49.2V45H45.2V33.6L41.8 45H39.1L35.7 33.6V45H31.8V27Z" fill="#F59E0B"/>
              <rect x="13" y="49" width="38" height="3" rx="1.5" fill="#FFFFFF"/>
            </svg>
            <div>
              <div class="text-sm font-extrabold text-white leading-snug">
                CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ XÂY DỰNG CƠ KHÍ VMT
              </div>
              <div class="text-[11px] text-amber-400 font-semibold">vmt.com</div>
            </div>
          </div>
          <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-location-dot text-amber-400 mt-1 shrink-0"></i>
              <span>Trụ sở: 69 Bàu Cầu 15, Phường Hòa Xuân, TP Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-phone text-amber-400 shrink-0"></i>
              <span>Hotline: <a href="tel:0337222775" class="text-white font-bold hover:text-amber-400">0337.222.775</a></span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-file-invoice text-amber-400 shrink-0"></i>
              <span>Mã số thuế: 0402294173</span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-globe text-amber-400 shrink-0"></i>
              <span>Website: <strong class="text-white">vmt.com</strong></span>
            </li>
          </ul>
        </div>

        <!-- Cột 2: Lĩnh vực hoạt động -->
        <div class="lg:col-span-3">
          <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3">Lĩnh Vực Hoạt Động</h4>
          <ul class="space-y-2 text-xs sm:text-sm">
            <li><a href="#linh-vuc" class="hover:text-amber-400 transition">Thiết kế Kiến trúc – Nội thất</a></li>
            <li><a href="#linh-vuc" class="hover:text-amber-400 transition">Thi công Xây dựng Phần thô</a></li>
            <li><a href="#linh-vuc" class="hover:text-amber-400 transition">Thi công Hoàn thiện &amp; Trọn gói</a></li>
            <li><a href="#linh-vuc" class="hover:text-amber-400 transition">Gia công Cơ khí – Kết cấu thép</a></li>
            <li><a href="#linh-vuc" class="hover:text-amber-400 transition">Thi công Hệ thống Điện Nước M&amp;E</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục công trình -->
        <div class="lg:col-span-4">
          <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3">Danh Mục Công Trình</h4>
          <ul class="space-y-2 text-xs sm:text-sm">
            <li><a href="#cong-trinh-thuc-te" onclick="filterProducts('nha-pho')" class="hover:text-amber-400 transition">Thi công Nhà phố hiện đại</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="filterProducts('biet-thu')" class="hover:text-amber-400 transition">Thiết kế &amp; Thi công Biệt thự</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="filterProducts('khach-san-can-ho')" class="hover:text-amber-400 transition">Khách sạn – Căn hộ – Phòng trọ</a></li>
            <li><a href="#du-an-da-nang" class="hover:text-amber-400 transition">Dự án tiêu biểu tại Đà Nẵng</a></li>
            <li><a href="#bao-gia" class="hover:text-amber-400 transition">Nhận bảng báo giá thi công mới nhất</a></li>
          </ul>
        </div>

      </div>

      <div class="pt-5 text-center text-xs text-slate-400">
        Copyright 2026 © <strong class="text-white">CÔNG TY TNHH THƯƠNG MẠI DỊCH VỤ XÂY DỰNG CƠ KHÍ VMT</strong> — Website: vmt.com
      </div>
    </div>
  </footer>

  <!-- ========================================================================
       CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (TƯƠNG THÍCH MOBILE & PC)
       ======================================================================== -->
  <div class="fixed right-3 bottom-4 sm:right-5 sm:bottom-6 z-40 flex flex-col items-end gap-2.5">
    <!-- Nút Facebook -->
    <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" aria-label="Facebook VMT" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white rounded-full p-2.5 sm:px-3.5 sm:py-2.5 shadow-lg transition">
      <i class="fa-brands fa-facebook-f w-5 h-5 flex items-center justify-center text-sm sm:text-base"></i>
      <span class="hidden md:inline text-xs font-bold pr-1">Facebook</span>
    </a>

    <!-- Nút Zalo -->
    <a href="https://zalo.me/0337222775" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0337.222.775" class="group flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white rounded-full p-2.5 sm:px-3.5 sm:py-2.5 shadow-lg transition">
      <span class="w-5 h-5 flex items-center justify-center text-[11px] font-extrabold leading-none">Zalo</span>
      <span class="hidden md:inline text-xs font-bold pr-1">Chat Zalo</span>
    </a>

    <!-- Nút Hotline nổi bật -->
    <a href="tel:0337222775" aria-label="Gọi Hotline 0337.222.775" class="btn-hotline-pulse flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white rounded-full p-2.5 sm:px-4 sm:py-2.5 shadow-xl transition">
      <i class="fa-solid fa-phone-volume w-5 h-5 flex items-center justify-center text-sm sm:text-base"></i>
      <span class="hidden sm:inline text-xs font-extrabold tracking-wide">0337.222.775</span>
    </a>
  </div>

  <!-- ========================================================================
       MODAL XEM CHI TIẾT ẢNH DỰ ÁN / SẢN PHẨM & HỘP THÔNG BÁO (KHÔNG DÙNG ALERT)
       ======================================================================== -->
  <div id="detailModal" class="fixed inset-0 z-50 hidden items-center justify-center bg-black/75 p-3 sm:p-5 backdrop-blur-sm">
    <div class="bg-white rounded-xl max-w-2xl w-full overflow-hidden shadow-2xl relative animate-fadeIn">
      <button id="closeDetailModal" type="button" aria-label="Đóng cửa sổ" class="absolute top-3 right-3 z-10 w-9 h-9 rounded-full bg-black/60 hover:bg-vmt-gold text-white flex items-center justify-center transition">
        <i class="fa-solid fa-xmark"></i>
      </button>
      <div class="w-full bg-slate-100 max-h-[60vh] overflow-hidden flex items-center justify-center">
        <img id="modalImg" src="" alt="" class="w-full h-full max-h-[60vh] object-contain bg-slate-900" />
      </div>
      <div class="p-4 sm:p-5">
        <h3 id="modalTitle" class="text-base sm:text-lg font-extrabold text-vmt-navy mb-1.5"></h3>
        <p id="modalDesc" class="text-xs sm:text-sm text-slate-600 leading-relaxed mb-4"></p>
        <div class="flex flex-wrap items-center gap-2.5">
          <a href="#bao-gia" onclick="closeModal()" class="inline-flex items-center gap-2 px-4 py-2 rounded-lg bg-vmt-gold hover:bg-amber-600 text-white text-xs sm:text-sm font-bold transition">
            <i class="fa-solid fa-file-signature"></i>
            <span>Yêu Cầu Báo Giá Công Trình Này</span>
          </a>
          <a href="tel:0337222775" class="inline-flex items-center gap-2 px-4 py-2 rounded-lg bg-vmt-navy hover:bg-vmt-navyLight text-white text-xs sm:text-sm font-bold transition">
            <i class="fa-solid fa-phone"></i>
            <span>0337.222.775</span>
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- Hộp Thông Báo Toast Chuyên Nghiệp -->
  <div id="toastBox" class="fixed top-20 right-3 left-3 sm:left-auto sm:right-5 sm:max-w-sm z-50 hidden bg-vmt-navy text-white border-l-4 border-vmt-gold rounded-lg shadow-2xl p-4">
    <div class="flex items-start gap-3">
      <i class="fa-solid fa-circle-check text-amber-400 text-lg mt-0.5"></i>
      <div class="flex-1 text-xs sm:text-sm leading-relaxed" id="toastMessage"></div>
      <button type="button" onclick="hideToast()" class="text-slate-300 hover:text-white">
        <i class="fa-solid fa-xmark"></i>
      </button>
    </div>
  </div>

  <!-- ========================================================================
       JAVASCRIPT: DỮ LIỆU ẢNH GOOGLE DRIVE, SLIDER, LỌC DANH MỤC, MODAL & FORM
       ======================================================================== -->
  <script>
    /**
     * Hàm tạo đường dẫn trực tiếp từ Google Drive File ID
     * Ưu tiên lh3.googleusercontent.com, tự động chuyển sang drive thumbnail và placeholder nếu lỗi
     */
    function getDriveUrl(fileId) {
      return `https://lh3.googleusercontent.com/d/${fileId}=w1000`;
    }

    function handleDriveImageError(imgEl) {
      const fileId = imgEl.getAttribute('data-drive-id');
      const fallbackLabel = imgEl.getAttribute('data-fallback-label') || 'Xay Dung Co Khi VMT';
      const step = parseInt(imgEl.getAttribute('data-err-step') || '0', 10);

      if (step === 0 && fileId) {
        imgEl.setAttribute('data-err-step', '1');
        imgEl.src = `https://drive.google.com/thumbnail?id=${fileId}&sz=w1000`;
      } else {
        imgEl.onerror = null;
        imgEl.src = `https://placehold.co/800x600/0F2C59/FFFFFF?text=${encodeURIComponent(fallbackLabel)}`;
      }
    }

    /**
     * DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (Bộ link Google Drive 1)
     */
    const realConstructionProducts = [
      {
        id: 'sp-1',
        driveId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        category: 'nha-pho',
        title: 'Thi Công Xây Dựng Nhà Phố Trọn Gói Hiện Đại',
        desc: 'Hạng mục thiết kế và thi công trọn gói nhà phố từ phần móng, kết cấu khung bê tông cốt thép đến hoàn thiện chìa khóa trao tay bởi đội ngũ kỹ sư VMT.'
      },
      {
        id: 'sp-2',
        driveId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        category: 'thi-cong-phan-tho',
        title: 'Thi Công Phần Thô & Kết Cấu Cốt Thép Sàn',
        desc: 'Công tác lắp dựng cốt thép, cốp pha và đổ bê tông đúng chuẩn kỹ thuật xây dựng, đảm bảo độ bền vững lâu dài cho công trình.'
      },
      {
        id: 'sp-3',
        driveId: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        category: 'nha-pho',
        title: 'Thi Công Hoàn Thiện Mặt Tiền Nhà Phố',
        desc: 'Hoàn thiện kiến trúc mặt tiền sắc nét, ốp lát vật liệu cao cấp, hệ cửa nhôm kính và lan can cơ khí đồng bộ.'
      },
      {
        id: 'sp-4',
        driveId: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        category: 'van-phong-co-khi',
        title: 'Gia Công Cơ Khí Kết Cấu Thép & Nhà Tiền Chế',
        desc: 'Gia công, lắp dựng khung kèo thép tiền chế, mái che cơ khí chịu lực cao, xử lý sơn chống gỉ tiêu chuẩn công nghiệp.'
      },
      {
        id: 'sp-5',
        driveId: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        category: 'khach-san-can-ho',
        title: 'Thi Công Khách Sạn & Căn Hộ Cho Thuê',
        desc: 'Giải pháp thiết kế và thi công căn hộ dịch vụ, khách sạn mini tối ưu số phòng, hệ thống M&E và phòng cháy an toàn.'
      },
      {
        id: 'sp-6',
        driveId: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
        category: 'biet-thu',
        title: 'Thi Công Biệt Thự Hiện Đại & Sân Vườn',
        desc: 'Thi công trọn gói biệt thự cao cấp với không gian mở, kết cấu chắc chắn và đường nét hoàn thiện tinh tế.'
      },
      {
        id: 'sp-7',
        driveId: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
        category: 'van-phong-co-khi',
        title: 'Thiết Kế & Thi Công Văn Phòng Làm Việc',
        desc: 'Thi công cải tạo và hoàn thiện văn phòng hiện đại, tối ưu ánh sáng, vách ngăn cơ khí kính và hệ thống điện mạng.'
      },
      {
        id: 'sp-8',
        driveId: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        category: 'van-phong-co-khi',
        title: 'Thi Công Cơ Khí Cổng Sắt, Cầu Thang & Lan Can',
        desc: 'Gia công tỉ mỉ các hạng mục cơ khí dân dụng: cổng sắt nghệ thuật, cầu thang xương cá, mái kính cường lực.'
      },
      {
        id: 'sp-9',
        driveId: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
        category: 'thi-cong-phan-tho',
        title: 'Thi Công Hoàn Thiện Nội Thất & Hệ Thống M&E',
        desc: 'Lắp đặt hệ thống điện nước âm tường, trần thạch cao, sơn bả và hoàn thiện nội thất trọn gói theo bản vẽ.'
      }
    ];

    /**
     * DỮ LIỆU 10 ẢNH DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (Bộ link Google Drive 2)
     */
    const danangProjects = [
      {
        driveId: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        title: 'Dự Án Nhà Phố 3 Tầng – Hòa Xuân, Đà Nẵng',
        desc: 'Công trình thi công trọn gói tại Khu đô thị sinh thái Hòa Xuân, TP Đà Nẵng do VMT trực tiếp thực hiện.'
      },
      {
        driveId: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
        title: 'Dự Án Căn Hộ Dịch Vụ – Quận Sơn Trà, Đà Nẵng',
        desc: 'Thi công xây dựng và hoàn thiện tòa nhà căn hộ dịch vụ cao cấp khu vực ven biển Sơn Trà, Đà Nẵng.'
      },
      {
        driveId: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
        title: 'Dự Án Biệt Thự 2 Mặt Tiền – Nam Việt Á, Đà Nẵng',
        desc: 'Thi công phần thô, hoàn thiện kiến trúc và hạng mục cơ khí ngoại thất biệt thự 2 mặt tiền tại Nam Việt Á.'
      },
      {
        driveId: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
        title: 'Dự Án Khách Sạn Mini – Ngũ Hành Sơn, Đà Nẵng',
        desc: 'Thiết kế và thi công khách sạn mini đạt chuẩn thẩm mỹ, tối ưu công năng khai thác du lịch tại Ngũ Hành Sơn.'
      },
      {
        driveId: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
        title: 'Dự Án Nhà Phố Hiện Đại – Bàu Cầu, Hòa Xuân',
        desc: 'Thi công nhà phố gia đình khu vực Bàu Cầu, Phường Hòa Xuân, TP Đà Nẵng với tiến độ bàn giao vượt cam kết.'
      },
      {
        driveId: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
        title: 'Dự Án Cơ Khí Kết Cấu Thép – Hòa Khánh, Đà Nẵng',
        desc: 'Gia công và lắp dựng kết cấu thép, mái tôn cách nhiệt cho công trình nhà xưởng tại Liên Chiểu, Đà Nẵng.'
      },
      {
        driveId: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
        title: 'Dự Án Văn Phòng Công Ty – Hải Châu, Đà Nẵng',
        desc: 'Thi công xây dựng và hoàn thiện không gian văn phòng làm việc chuyên nghiệp tại trung tâm Quận Hải Châu.'
      },
      {
        driveId: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
        title: 'Dự Án Hoàn Thiện Nhà Phố – Cẩm Lệ, Đà Nẵng',
        desc: 'Hạng mục hoàn thiện mặt tiền, ốp lát, sơn nước và nội thất cơ bản nhà phố 2 tầng tại Quận Cẩm Lệ.'
      },
      {
        driveId: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
        title: 'Dự Án Biệt Thự Phố – Khu Phước Lý, Đà Nẵng',
        desc: 'Thiết kế và thi công trọn gói biệt thự phố hiện đại tại khu đô thị Phước Lý, TP Đà Nẵng.'
      },
      {
        driveId: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
        title: 'Dự Án Căn Hộ Cho Thuê – Liên Chiểu, Đà Nẵng',
        desc: 'Thi công xây dựng tòa nhà căn hộ cho thuê hiện đại, tối ưu chi phí đầu tư tại Quận Liên Chiểu, Đà Nẵng.'
      }
    ];

    /**
     * DỮ LIỆU BÀI VIẾT / TIN TỨC TRANG CHỦ (Tương tự web mẫu & lĩnh vực VMT)
     */
    const newsArticles = [
      {
        driveId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        title: 'Hướng dẫn bảo dưỡng bê tông móng đúng kỹ thuật xây dựng',
        excerpt: 'Bảo dưỡng bê tông móng đúng quy trình giúp kết cấu đạt cường độ tối đa, chống nứt và tăng tuổi thọ công trình.',
        date: '15/11/2026'
      },
      {
        driveId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        title: '03 Nỗi lo lớn nhất khi xây nhà trọn gói tại Đà Nẵng và giải pháp',
        excerpt: 'Làm sao để kiểm soát chi phí phát sinh, đảm bảo vật tư chuẩn và đúng tiến độ khi khởi công xây dựng nhà mới?',
        date: '10/11/2026'
      },
      {
        driveId: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        title: 'Ưu điểm của kết cấu thép và cơ khí xây dựng trong công trình hiện đại',
        excerpt: 'Giải pháp nhà thép tiền chế và hạng mục cơ khí giúp rút ngắn thời gian thi công, vượt nhịp lớn và linh hoạt mở rộng.',
        date: '04/11/2026'
      },
      {
        driveId: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        title: 'Kinh nghiệm lập dự toán thi công phần thô và hoàn thiện tiết kiệm',
        excerpt: 'Cách bóc tách khối lượng, lựa chọn vật liệu hoàn thiện phù hợp ngân sách nhưng vẫn đảm bảo thẩm mỹ bền đẹp.',
        date: '28/10/2026'
      }
    ];

    /**
     * Render danh sách sản phẩm / công trình thực tế (KHÔNG có nhãn dán đè lên ảnh)
     */
    function renderProducts(category = 'all') {
      const grid = document.getElementById('productGrid');
      if (!grid) return;

      const filtered = category === 'all'
        ? realConstructionProducts
        : realConstructionProducts.filter(item => item.category === category);

      grid.innerHTML = filtered.map(item => `
        <article
          onclick="openDetailModal('${item.driveId}', '${escapeQuotes(item.title)}', '${escapeQuotes(item.desc)}')"
          class="vmt-card cursor-pointer bg-white border border-slate-200 rounded-xl overflow-hidden hover:border-vmt-gold hover:shadow-md transition flex flex-col"
        >
          <div class="card-img-box">
            <img
              src="${getDriveUrl(item.driveId)}"
              data-drive-id="${item.driveId}"
              data-fallback-label="${item.title}"
              onerror="handleDriveImageError(this)"
              alt="${item.title}"
              loading="lazy"
            />
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <h3 class="text-[12px] sm:text-sm font-bold text-vmt-navy leading-snug break-words group-hover:text-vmt-gold">
              ${item.title}
            </h3>
            <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] font-semibold text-vmt-gold">
              <span>Xem chi tiết</span>
              <i class="fa-solid fa-arrow-right text-[10px]"></i>
            </div>
          </div>
        </article>
      `).join('');
    }

    /**
     * Render 10 dự án tại Đà Nẵng (KHÔNG có nhãn dán đè lên ảnh)
     */
    function renderDanangProjects() {
      const grid = document.getElementById('danangProjectsGrid');
      if (!grid) return;

      grid.innerHTML = danangProjects.map(item => `
        <article
          onclick="openDetailModal('${item.driveId}', '${escapeQuotes(item.title)}', '${escapeQuotes(item.desc)}')"
          class="vmt-card cursor-pointer bg-white border border-slate-200 rounded-xl overflow-hidden hover:border-vmt-gold hover:shadow-md transition flex flex-col"
        >
          <div class="card-img-box">
            <img
              src="${getDriveUrl(item.driveId)}"
              data-drive-id="${item.driveId}"
              data-fallback-label="${item.title}"
              onerror="handleDriveImageError(this)"
              alt="${item.title}"
              loading="lazy"
            />
          </div>
          <div class="p-2.5 sm:p-3 flex-1 flex items-center">
            <h3 class="text-[12px] sm:text-[13px] font-bold text-vmt-navy leading-snug break-words">
              ${item.title}
            </h3>
          </div>
        </article>
      `).join('');
    }

    /**
     * Render danh mục bài viết trang chủ (KHÔNG có nhãn dán đè ảnh)
     */
    function renderNews() {
      const grid = document.getElementById('newsGrid');
      if (!grid) return;

      grid.innerHTML = newsArticles.map(post => `
        <article
          onclick="openDetailModal('${post.driveId}', '${escapeQuotes(post.title)}', '${escapeQuotes(post.excerpt)}')"
          class="vmt-card cursor-pointer bg-white border border-slate-200 rounded-xl overflow-hidden hover:border-vmt-gold hover:shadow-md transition flex flex-col"
        >
          <div class="card-img-box">
            <img
              src="${getDriveUrl(post.driveId)}"
              data-drive-id="${post.driveId}"
              data-fallback-label="Tin Tuc Xay Dung VMT"
              onerror="handleDriveImageError(this)"
              alt="${post.title}"
              loading="lazy"
            />
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[11px] text-slate-400 font-medium mb-1">
                <i class="fa-regular fa-calendar mr-1"></i>${post.date}
              </div>
              <h3 class="text-[12.5px] sm:text-sm font-bold text-vmt-navy leading-snug mb-1.5 break-words">
                ${post.title}
              </h3>
              <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed">
                ${post.excerpt}
              </p>
            </div>
          </div>
        </article>
      `).join('');
    }

    function escapeQuotes(str) {
      return String(str).replace(/'/g, "\\'").replace(/"/g, '&quot;');
    }

    /**
     * Chuyển đổi danh mục lọc sản phẩm
     */
    function filterProducts(category) {
      const tabs = document.querySelectorAll('#productCategoryTabs .cat-tab');
      tabs.forEach(tab => {
        const isTarget = tab.getAttribute('data-cat') === category;
        if (isTarget) {
          tab.classList.add('bg-vmt-navy', 'text-white', 'border-vmt-navy');
          tab.classList.remove('bg-white', 'text-slate-700', 'border-slate-200');
        } else {
          tab.classList.remove('bg-vmt-navy', 'text-white', 'border-vmt-navy');
          tab.classList.add('bg-white', 'text-slate-700', 'border-slate-200');
        }
      });
      renderProducts(category);
    }

    /**
     * Điều khiển 2 Banner Tự Trượt Chuyên Nghiệp (Hỗ trợ Auto-Slide + Touch Swipe)
     */
    let currentSlide = 0;
    let slideInterval = null;

    function showBannerSlide(index) {
      const slides = document.querySelectorAll('#heroBannerSlider .vmt-banner-slide');
      const dots = document.querySelectorAll('#heroBannerSlider .banner-dot');
      if (!slides.length) return;

      currentSlide = (index + slides.length) % slides.length;
      slides.forEach((s, i) => {
        s.classList.toggle('active', i === currentSlide);
      });
      dots.forEach((d, i) => {
        if (i === currentSlide) {
          d.classList.remove('w-2.5', 'bg-white/50');
          d.classList.add('w-6', 'bg-vmt-gold');
        } else {
          d.classList.remove('w-6', 'bg-vmt-gold');
          d.classList.add('w-2.5', 'bg-white/50');
        }
      });
    }

    function startBannerAutoPlay() {
      stopBannerAutoPlay();
      slideInterval = setInterval(() => {
        showBannerSlide(currentSlide + 1);
      }, 5000);
    }

    function stopBannerAutoPlay() {
      if (slideInterval) clearInterval(slideInterval);
    }

    /**
     * Modal Xem Chi Tiết Ảnh Công Trình
     */
    function openDetailModal(driveId, title, desc) {
      const modal = document.getElementById('detailModal');
      const modalImg = document.getElementById('modalImg');
      const modalTitle = document.getElementById('modalTitle');
      const modalDesc = document.getElementById('modalDesc');

      modalImg.setAttribute('data-drive-id', driveId);
      modalImg.setAttribute('data-fallback-label', title);
      modalImg.setAttribute('data-err-step', '0');
      modalImg.onerror = function() { handleDriveImageError(this); };
      modalImg.src = getDriveUrl(driveId);
      modalImg.alt = title;

      modalTitle.textContent = title;
      modalDesc.textContent = desc;

      modal.classList.remove('hidden');
      modal.classList.add('flex');
      document.body.style.overflow = 'hidden';
    }

    function closeModal() {
      const modal = document.getElementById('detailModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
      document.body.style.overflow = '';
    }

    /**
     * Thông báo Toast thay thế alert()
     */
    let toastTimer = null;
    function showToast(message) {
      const box = document.getElementById('toastBox');
      const msgEl = document.getElementById('toastMessage');
      msgEl.textContent = message;
      box.classList.remove('hidden');
      if (toastTimer) clearTimeout(toastTimer);
      toastTimer = setTimeout(hideToast, 5500);
    }

    function hideToast() {
      document.getElementById('toastBox').classList.add('hidden');
    }

    /**
     * Khởi tạo toàn bộ sự kiện khi tải trang
     */
    document.addEventListener('DOMContentLoaded', () => {
      try {
        // Render nội dung các khu vực chính
        renderProducts('all');
        renderDanangProjects();
        renderNews();

        // Sự kiện lọc danh mục sản phẩm
        document.querySelectorAll('#productCategoryTabs .cat-tab').forEach(btn => {
          btn.addEventListener('click', () => {
            filterProducts(btn.getAttribute('data-cat'));
          });
        });

        // Điều khiển Banner Slider
        const prevBtn = document.getElementById('bannerPrev');
        const nextBtn = document.getElementById('bannerNext');
        const sliderEl = document.getElementById('heroBannerSlider');

        prevBtn.addEventListener('click', () => {
          showBannerSlide(currentSlide - 1);
          startBannerAutoPlay();
        });
        nextBtn.addEventListener('click', () => {
          showBannerSlide(currentSlide + 1);
          startBannerAutoPlay();
        });

        document.querySelectorAll('#heroBannerSlider .banner-dot').forEach(dot => {
          dot.addEventListener('click', () => {
            showBannerSlide(parseInt(dot.getAttribute('data-slide'), 10));
            startBannerAutoPlay();
          });
        });

        // Hỗ trợ vuốt cảm ứng trên điện thoại cho 2 Banner
        let touchStartX = 0;
        sliderEl.addEventListener('touchstart', (e) => {
          touchStartX = e.changedTouches[0].screenX;
        }, { passive: true });
        sliderEl.addEventListener('touchend', (e) => {
          const touchEndX = e.changedTouches[0].screenX;
          if (touchStartX - touchEndX > 45) {
            showBannerSlide(currentSlide + 1);
            startBannerAutoPlay();
          } else if (touchEndX - touchStartX > 45) {
            showBannerSlide(currentSlide - 1);
            startBannerAutoPlay();
          }
        }, { passive: true });

        startBannerAutoPlay();

        // Menu Mobile
        const mobileMenuBtn = document.getElementById('mobileMenuBtn');
        const mobileMenu = document.getElementById('mobileMenu');
        mobileMenuBtn.addEventListener('click', () => {
          mobileMenu.classList.toggle('hidden');
        });
        document.querySelectorAll('.mobile-nav-link').forEach(link => {
          link.addEventListener('click', () => {
            mobileMenu.classList.add('hidden');
          });
        });

        // Đóng Modal chi tiết
        document.getElementById('closeDetailModal').addEventListener('click', closeModal);
        document.getElementById('detailModal').addEventListener('click', (e) => {
          if (e.target.id === 'detailModal') closeModal();
        });

        // Xử lý Form Yêu Cầu & Báo Giá
        const quoteForm = document.getElementById('quoteForm');
        quoteForm.addEventListener('submit', (e) => {
          e.preventDefault();
          const name = document.getElementById('qName').value.trim();
          const phone = document.getElementById('qPhone').value.trim();
          const type = document.getElementById('qType').value;

          if (!name || !phone) {
            showToast('Vui lòng nhập đầy đủ Họ tên và Số điện thoại để VMT liên hệ báo giá.');
            return;
          }

          showToast(`Cảm ơn ${name}! VMT đã nhận yêu cầu báo giá "${type}" và sẽ liên hệ qua số ${phone} trong thời gian sớm nhất.`);
          quoteForm.reset();
        });
      } catch (error) {
        console.error('Lỗi khởi tạo giao diện VMT:', error);
      }
    });
  </script>
</body>
</html>

<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>levo.com - CÔNG TY TNHH L.E.V.O ARCHITECTURE & CONSTRUCTION</title>
    <meta name="description" content="CÔNG TY TNHH L.E.V.O ARCHITECTURE & CONSTRUCTION - Chuyên thi công nội thất, khu vui chơi, cơ khí, quảng cáo, vật tư nhôm, phụ kiện nội thất tủ bếp tại Đà Nẵng và toàn quốc. Hotline: 0905.952.233">
    
    <!-- Open Graph / Thumbnail là ảnh Logo khi gửi link trang web -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://levo.com/">
    <meta property="og:site_name" content="levo.com">
    <meta property="og:title" content="levo.com - CÔNG TY TNHH L.E.V.O ARCHITECTURE & CONSTRUCTION">
    <meta property="og:description" content="Chuyên thi công nội thất, khu vui chơi trẻ em, cơ khí, quảng cáo, vật tư nhôm, phụ kiện nội thất tủ bếp. Địa chỉ: 612B Nguyễn Lương Bằng, P. Hải Vân, TP Đà Nẵng.">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1TdJQi_jTp3zFtTTmiFq0ncLbENU86AK4&sz=w1200">
    <meta property="og:image:alt" content="Logo L.E.V.O Architecture & Construction">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1TdJQi_jTp3zFtTTmiFq0ncLbENU86AK4&sz=w1200">
    <link rel="icon" href="https://drive.google.com/thumbnail?id=1TdJQi_jTp3zFtTTmiFq0ncLbENU86AK4&sz=w256">

    <!-- Tailwind CSS & Font Awesome & Google Fonts (Inter / Montserrat chuẩn Flatsome) -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        levo: {
                            dark: '#0c2340',     /* Xanh đậm kiến trúc theo tông logo */
                            primary: '#164e87',  /* Xanh chủ đạo chuẩn thương hiệu */
                            light: '#eaf2fa',    /* Nền xanh nhạt Flatsome section */
                            accent: '#f59e0b',   /* Vàng cam điểm nhấn nội thất & khu vui chơi */
                            accentHover: '#d97706'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Khóa tràn viền tuyệt đối trên cả máy tính và điện thoại */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden !important;
            margin: 0;
            padding: 0;
            scroll-behavior: smooth;
            background-color: #f8fafc;
            color: #1e293b;
        }

        /* Khung Container chuẩn Flatsome: 95% trên máy tính, căn giữa tuyệt đối */
        .flatsome-container {
            width: 96%;
            max-width: 96%;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
            }
        }

        /* Tiêu đề Section chuẩn UX Builder Flatsome (Style Normal / Center) */
        .section-title-container {
            margin-bottom: 1.25rem;
        }
        .section-title-main {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e2e8f0;
            padding-bottom: 0.5rem;
            gap: 0.75rem;
            flex-wrap: wrap;
        }
        .section-title-main h2 {
            position: relative;
            font-weight: 800;
            text-transform: uppercase;
            color: #0c2340;
            margin: 0;
            padding-bottom: 0.5rem;
            margin-bottom: -0.6rem;
            border-bottom: 3px solid #164e87;
        }

        /* Tối ưu tên danh mục trên máy tính: viết liền trên 1 hàng, không bị ngắt chữ giữa chừng */
        .nav-cat-item {
            white-space: nowrap;
            display: inline-flex;
            align-items: center;
            transition: all 0.2s ease;
        }

        /* Hiệu ứng nút liên hệ nổi rung nhẹ */
        @keyframes pulse-ring {
            0% { transform: scale(0.92); box-shadow: 0 0 0 0 rgba(22, 78, 135, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(22, 78, 135, 0); }
            100% { transform: scale(0.92); box-shadow: 0 0 0 0 rgba(22, 78, 135, 0); }
        }
        .floating-btn-pulse {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="font-sans antialiased">

    <!-- =====================================================================
         FLATSOME HEADER (#header) - KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN
         ===================================================================== -->
    <header id="header" class="bg-white shadow-sm sticky top-0 z-40 w-full">
        
        <!-- Top Bar đơn giản chuẩn Flatsome -->
        <div class="bg-levo-dark text-white text-xs py-1.5 border-b border-slate-700">
            <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-2 truncate">
                    <span class="font-semibold tracking-wide text-amber-400">levo.com</span>
                    <span class="hidden sm:inline text-slate-400">|</span>
                    <span class="truncate">CÔNG TY TNHH L.E.V.O ARCHITECTURE & CONSTRUCTION</span>
                </div>
                <div class="hidden md:flex items-center gap-4 text-slate-200 shrink-0">
                    <span><i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>612B Nguyễn Lương Bằng, P. Hải Vân, TP Đà Nẵng</span>
                    <span><i class="fa-solid fa-phone text-amber-400 mr-1"></i>0905.952.233</span>
                </div>
            </div>
        </div>

        <!-- Header Main: Logo gọn nhỏ + Thanh tìm kiếm + Địa chỉ (Không có nút gọi ngay) -->
        <div class="py-2.5 bg-white border-b border-slate-100">
            <div class="flatsome-container flex items-center justify-between gap-3">
                
                <!-- Nút mở Menu trên Điện thoại -->
                <button id="mobileMenuBtn" onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-lg text-levo-dark hover:bg-slate-100 focus:outline-none shrink-0">
                    <i class="fa-solid fa-bars text-xl"></i>
                </button>

                <!-- Logo chỉnh gọn nhỏ lại + Tên thương hiệu -->
                <a href="#top" class="flex items-center gap-2.5 min-w-0 shrink">
                    <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-lg border border-slate-200 bg-white p-0.5 flex items-center justify-center overflow-hidden shrink-0 shadow-xs">
                        <img src="https://drive.google.com/thumbnail?id=1TdJQi_jTp3zFtTTmiFq0ncLbENU86AK4&sz=w400" 
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1TdJQi_jTp3zFtTTmiFq0ncLbENU86AK4';" 
                             alt="Logo L.E.V.O" 
                             class="w-full h-full object-contain">
                    </div>
                    <div class="min-w-0">
                        <div class="text-sm sm:text-base font-extrabold text-levo-dark leading-tight truncate">
                            L.E.V.O ARCHITECTURE
                        </div>
                        <div class="text-[10px] sm:text-xs font-medium text-levo-primary truncate">
                            Nội Thất • Khu Vui Chơi • Cơ Khí • Quảng Cáo • Nhôm
                        </div>
                    </div>
                </a>

                <!-- Ô tìm kiếm sản phẩm/dịch vụ (Máy tính) -->
                <div class="hidden md:flex flex-1 max-w-md mx-4">
                    <div class="relative w-full">
                        <input id="searchInputDesktop" type="text" oninput="filterProductsBySearch(this.value)" placeholder="Tìm nội thất, khu vui chơi, cơ khí, nhôm, phụ kiện bếp..." 
                               class="w-full pl-3.5 pr-9 py-1.5 text-xs rounded-full border border-slate-300 focus:border-levo-primary focus:outline-none bg-slate-50">
                        <span class="absolute right-3 top-1/2 -translate-y-1/2 text-slate-400 text-xs">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </span>
                    </div>
                </div>

                <!-- Thông tin văn phòng gọn gàng (Không để nút gọi ngay tránh tràn viền) -->
                <div class="hidden xl:flex items-center gap-4 text-xs text-slate-600 shrink-0">
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-building-shield text-levo-primary text-base"></i>
                        <div>
                            <div class="font-bold text-levo-dark">Uy Tín - Trọn Gói</div>
                            <div class="text-[11px] text-slate-500">Xưởng sản xuất trực tiếp</div>
                        </div>
                    </div>
                </div>

            </div>
        </div>

        <!-- Header Bottom: Thanh Danh Mục Trên Máy Tính (Chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng từng chữ) -->
        <nav class="hidden lg:block bg-levo-primary text-white">
            <div class="flatsome-container">
                <ul class="flex flex-wrap items-center justify-center xl:justify-between gap-x-1 gap-y-1 py-1.5 text-[12px] xl:text-[13px] font-semibold">
                    <li>
                        <a href="#top" onclick="selectCategory('all')" class="nav-cat-item px-2.5 py-1.5 rounded bg-amber-500 text-slate-950 font-bold hover:bg-amber-400">
                            <i class="fa-solid fa-house mr-1.5 text-[11px]"></i>TRANG CHỦ
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-dich-vu" onclick="selectCategory('noi-that')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-white/15">
                            <i class="fa-solid fa-couch mr-1.5 text-amber-300 text-[11px]"></i>THI CÔNG NỘI THẤT
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-dich-vu" onclick="selectCategory('khu-vui-choi')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-white/15">
                            <i class="fa-solid fa-shapes mr-1.5 text-amber-300 text-[11px]"></i>KHU VUI CHƠI
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-dich-vu" onclick="selectCategory('co-khi')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-white/15">
                            <i class="fa-solid fa-gears mr-1.5 text-amber-300 text-[11px]"></i>CƠ KHÍ
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-dich-vu" onclick="selectCategory('quang-cao')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-white/15">
                            <i class="fa-solid fa-bullhorn mr-1.5 text-amber-300 text-[11px]"></i>QUẢNG CÁO
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-dich-vu" onclick="selectCategory('vat-tu-nhom')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-white/15">
                            <i class="fa-solid fa-layer-group mr-1.5 text-amber-300 text-[11px]"></i>VẬT TƯ NHÔM
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-dich-vu" onclick="selectCategory('phu-kien-bep')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-white/15">
                            <i class="fa-solid fa-kitchen-set mr-1.5 text-amber-300 text-[11px]"></i>PHỤ KIỆN NỘI THẤT TỦ BẾP
                        </a>
                    </li>
                    <li>
                        <a href="#doi-tac" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-white/15">
                            ĐỐI TÁC
                        </a>
                    </li>
                    <li>
                        <a href="#bai-viet" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-white/15">
                            BÀI VIẾT
                        </a>
                    </li>
                    <li>
                        <a href="#bao-gia" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-white/15">
                            BÁO GIÁ & LIÊN HỆ
                        </a>
                    </li>
                </ul>
            </div>
        </nav>

        <!-- Menu Danh Mục Thu Gọn Mở Rộng Trên Điện Thoại -->
        <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-b border-slate-200 shadow-lg">
            <div class="flatsome-container py-3 space-y-2">
                <div class="relative">
                    <input type="text" oninput="filterProductsBySearch(this.value)" placeholder="Tìm kiếm hạng mục..." 
                           class="w-full pl-3 pr-8 py-2 text-xs rounded-lg border border-slate-300 bg-slate-50">
                    <i class="fa-solid fa-magnifying-glass absolute right-3 top-1/2 -translate-y-1/2 text-slate-400 text-xs"></i>
                </div>
                <div class="grid grid-cols-2 gap-1.5 text-xs font-semibold text-levo-dark pt-1">
                    <a href="#san-pham-dich-vu" onclick="selectCategory('noi-that'); toggleMobileMenu();" class="p-2 rounded bg-slate-100 hover:bg-levo-light flex items-center gap-1.5">
                        <i class="fa-solid fa-couch text-levo-primary"></i><span>Thi Công Nội Thất</span>
                    </a>
                    <a href="#san-pham-dich-vu" onclick="selectCategory('khu-vui-choi'); toggleMobileMenu();" class="p-2 rounded bg-slate-100 hover:bg-levo-light flex items-center gap-1.5">
                        <i class="fa-solid fa-shapes text-levo-primary"></i><span>Khu Vui Chơi</span>
                    </a>
                    <a href="#san-pham-dich-vu" onclick="selectCategory('co-khi'); toggleMobileMenu();" class="p-2 rounded bg-slate-100 hover:bg-levo-light flex items-center gap-1.5">
                        <i class="fa-solid fa-gears text-levo-primary"></i><span>Cơ Khí</span>
                    </a>
                    <a href="#san-pham-dich-vu" onclick="selectCategory('quang-cao'); toggleMobileMenu();" class="p-2 rounded bg-slate-100 hover:bg-levo-light flex items-center gap-1.5">
                        <i class="fa-solid fa-bullhorn text-levo-primary"></i><span>Quảng Cáo</span>
                    </a>
                    <a href="#san-pham-dich-vu" onclick="selectCategory('vat-tu-nhom'); toggleMobileMenu();" class="p-2 rounded bg-slate-100 hover:bg-levo-light flex items-center gap-1.5">
                        <i class="fa-solid fa-layer-group text-levo-primary"></i><span>Vật Tư Nhôm</span>
                    </a>
                    <a href="#san-pham-dich-vu" onclick="selectCategory('phu-kien-bep'); toggleMobileMenu();" class="p-2 rounded bg-slate-100 hover:bg-levo-light flex items-center gap-1.5">
                        <i class="fa-solid fa-kitchen-set text-levo-primary"></i><span>Phụ Kiện Tủ Bếp</span>
                    </a>
                    <a href="#bao-gia" onclick="toggleMobileMenu();" class="p-2 rounded bg-amber-50 text-amber-900 flex items-center gap-1.5">
                        <i class="fa-solid fa-file-signature text-amber-600"></i><span>Nhận Báo Giá</span>
                    </a>
                    <a href="#ket-noi-bando" onclick="toggleMobileMenu();" class="p-2 rounded bg-amber-50 text-amber-900 flex items-center gap-1.5">
                        <i class="fa-solid fa-map-location-dot text-amber-600"></i><span>Bản Đồ & Fanpage</span>
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!-- =====================================================================
         MAIN CONTENT (#main) - THIẾT KẾ CHUẨN UX BUILDER FLATSOME
         ===================================================================== -->
    <main id="top" class="w-full">

        <!-- 1. SECTION: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
             Hình ảnh & chữ nằm trọn trong banner, chữ cách xa viền, không mất chữ trên ĐT & Máy tính -->
        <section class="py-3 sm:py-4">
            <div class="flatsome-container">
                <div class="relative w-full h-[270px] sm:h-[340px] md:h-[400px] rounded-xl overflow-hidden shadow-md bg-levo-dark">
                    
                    <!-- SLIDE 1 -->
                    <div id="bannerSlide0" class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
                        <!-- Nền & Khung cách xa viền an toàn (px-7 sm:px-14 md:px-20 py-6 sm:py-10) -->
                        <div class="w-full h-full bg-gradient-to-r from-[#091c34] via-[#133b68] to-[#1a528b] flex items-center justify-between px-7 sm:px-14 md:px-20 py-6 sm:py-10 gap-4 sm:gap-8">
                            <!-- Khối chữ bên trái: cách xa viền, tự co giãn vừa vặn 100% -->
                            <div class="w-3/5 sm:w-7/12 text-white space-y-1.5 sm:space-y-3">
                                <div class="text-[10px] sm:text-xs md:text-sm font-bold text-amber-400 tracking-wider uppercase">
                                    CÔNG TY TNHH L.E.V.O ARCHITECTURE & CONSTRUCTION
                                </div>
                                <h1 class="text-sm sm:text-xl md:text-2xl lg:text-3xl font-extrabold leading-snug">
                                    THIẾT KẾ & THI CÔNG NỘI THẤT, KHU VUI CHƠI, CƠ KHÍ, QUẢNG CÁO
                                </h1>
                                <p class="text-[11px] sm:text-xs md:text-sm text-slate-200 leading-relaxed">
                                    Giải pháp thi công đồng bộ tại Đà Nẵng & Miền Trung. Cung cấp vật tư nhôm và phụ kiện nội thất tủ bếp chính hãng, tối ưu chi phí.
                                </p>
                                <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2">
                                    <a href="#bao-gia" class="inline-block bg-amber-500 hover:bg-amber-400 text-slate-950 font-bold text-[11px] sm:text-xs md:text-sm px-3.5 py-1.5 sm:px-5 sm:py-2.5 rounded-lg transition">
                                        Yêu Cầu Báo Giá
                                    </a>
                                    <span class="text-[11px] sm:text-xs font-semibold text-amber-300">
                                        <i class="fa-solid fa-phone-volume mr-1"></i>0905.952.233
                                    </span>
                                </div>
                            </div>

                            <!-- Khối hình thực tế nằm gọn bên trong banner -->
                            <div class="w-2/5 sm:w-5/12 h-full flex items-center justify-center">
                                <div class="w-full h-[180px] sm:h-[240px] md:h-[300px] rounded-xl overflow-hidden border-2 border-white/30 shadow-lg bg-slate-900">
                                    <img src="https://drive.google.com/thumbnail?id=1WROwMPkWQroMnuniDEkrgjBmxRYxabuj&sz=w1200" 
                                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1WROwMPkWQroMnuniDEkrgjBmxRYxabuj';"
                                         alt="Công trình thực tế L.E.V.O 1" 
                                         class="w-full h-full object-cover">
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- SLIDE 2 (Kích thước bằng nhau 100% với Slide 1) -->
                    <div id="bannerSlide1" class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0 pointer-events-none">
                        <!-- Nền & Khung cách xa viền an toàn (px-7 sm:px-14 md:px-20 py-6 sm:py-10) -->
                        <div class="w-full h-full bg-gradient-to-r from-[#0f2942] via-[#164e87] to-[#0c2340] flex items-center justify-between px-7 sm:px-14 md:px-20 py-6 sm:py-10 gap-4 sm:gap-8">
                            <!-- Khối chữ bên trái: cách xa viền, không tràn hay mất chữ -->
                            <div class="w-3/5 sm:w-7/12 text-white space-y-1.5 sm:space-y-3">
                                <div class="text-[10px] sm:text-xs md:text-sm font-bold text-amber-400 tracking-wider uppercase">
                                    XƯỞNG SẢN XUẤT & PHÂN PHỐI VẬT TƯ UY TÍN - LEVO.COM
                                </div>
                                <h2 class="text-sm sm:text-xl md:text-2xl lg:text-3xl font-extrabold leading-snug">
                                    CHUYÊN VẬT TƯ NHÔM, PHỤ KIỆN TỦ BẾP & KHU VUI CHƠI TRẺ EM
                                </h2>
                                <p class="text-[11px] sm:text-xs md:text-sm text-slate-200 leading-relaxed">
                                    Địa chỉ: 612B Nguyễn Lương Bằng, Phường Hải Vân, TP Đà Nẵng. Khảo sát tận nơi, thiết kế 3D sát thực tế và bảo hành dài hạn.
                                </p>
                                <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2">
                                    <a href="#san-pham-dich-vu" class="inline-block bg-amber-500 hover:bg-amber-400 text-slate-950 font-bold text-[11px] sm:text-xs md:text-sm px-3.5 py-1.5 sm:px-5 sm:py-2.5 rounded-lg transition">
                                        Xem Dự Án Thực Tế
                                    </a>
                                    <span class="text-[11px] sm:text-xs font-semibold text-amber-300">
                                        <i class="fa-solid fa-location-dot mr-1"></i>TP Đà Nẵng
                                    </span>
                                </div>
                            </div>

                            <!-- Khối hình thực tế nằm gọn bên trong banner -->
                            <div class="w-2/5 sm:w-5/12 h-full flex items-center justify-center">
                                <div class="w-full h-[180px] sm:h-[240px] md:h-[300px] rounded-xl overflow-hidden border-2 border-white/30 shadow-lg bg-slate-900">
                                    <img src="https://drive.google.com/thumbnail?id=1LogWj9XB1Dg6667Hr41WF8ZcCajc8YNd&sz=w1200" 
                                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1LogWj9XB1Dg6667Hr41WF8ZcCajc8YNd';"
                                         alt="Công trình thực tế L.E.V.O 2" 
                                         class="w-full h-full object-cover">
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Nút điều hướng qua lại nằm sát mép ngoài phần chữ -->
                    <button onclick="prevBanner()" aria-label="Banner trước" class="absolute left-1.5 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
                        <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                    </button>
                    <button onclick="nextBanner()" aria-label="Banner tiếp" class="absolute right-1.5 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
                        <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                    </button>

                    <!-- Chấm tròn báo vị trí Banner -->
                    <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                        <button id="bannerDot0" onclick="goToBanner(0)" aria-label="Slide 1" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
                        <button id="bannerDot1" onclick="goToBanner(1)" aria-label="Slide 2" class="w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- 2. SECTION: DANH MỤC LĨNH VỰC HOẠT ĐỘNG Ở TRANG CHỦ
             Chữ danh mục nhỏ gọn, trên máy tính nằm gọn trên 1 hàng, trên điện thoại chia lưới đều đẹp -->
        <section class="py-4 bg-white border-y border-slate-200">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title-main">
                        <h2 class="text-sm sm:text-base md:text-lg">DANH MỤC LĨNH VỰC CHUYÊN MÔN</h2>
                        <span class="text-xs text-slate-500">Chọn danh mục để lọc nhanh hạng mục bên dưới</span>
                    </div>
                </div>

                <!-- Lưới 6 danh mục: 2 cột trên ĐT, 3 cột trên Tablet, 6 cột trên 1 hàng ở Máy tính -->
                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5">
                    
                    <button onclick="selectCategory('noi-that')" class="cat-box group p-2.5 rounded-xl border border-slate-200 hover:border-levo-primary bg-slate-50 hover:bg-levo-light transition text-center flex flex-col items-center justify-center">
                        <div class="w-9 h-9 rounded-full bg-levo-primary text-white flex items-center justify-center mb-1.5 group-hover:scale-105 transition">
                            <i class="fa-solid fa-couch text-sm"></i>
                        </div>
                        <span class="text-[11px] sm:text-xs font-bold text-levo-dark whitespace-nowrap">Thi Công Nội Thất</span>
                    </button>

                    <button onclick="selectCategory('khu-vui-choi')" class="cat-box group p-2.5 rounded-xl border border-slate-200 hover:border-levo-primary bg-slate-50 hover:bg-levo-light transition text-center flex flex-col items-center justify-center">
                        <div class="w-9 h-9 rounded-full bg-levo-primary text-white flex items-center justify-center mb-1.5 group-hover:scale-105 transition">
                            <i class="fa-solid fa-shapes text-sm"></i>
                        </div>
                        <span class="text-[11px] sm:text-xs font-bold text-levo-dark whitespace-nowrap">Khu Vui Chơi</span>
                    </button>

                    <button onclick="selectCategory('co-khi')" class="cat-box group p-2.5 rounded-xl border border-slate-200 hover:border-levo-primary bg-slate-50 hover:bg-levo-light transition text-center flex flex-col items-center justify-center">
                        <div class="w-9 h-9 rounded-full bg-levo-primary text-white flex items-center justify-center mb-1.5 group-hover:scale-105 transition">
                            <i class="fa-solid fa-gears text-sm"></i>
                        </div>
                        <span class="text-[11px] sm:text-xs font-bold text-levo-dark whitespace-nowrap">Gia Công Cơ Khí</span>
                    </button>

                    <button onclick="selectCategory('quang-cao')" class="cat-box group p-2.5 rounded-xl border border-slate-200 hover:border-levo-primary bg-slate-50 hover:bg-levo-light transition text-center flex flex-col items-center justify-center">
                        <div class="w-9 h-9 rounded-full bg-levo-primary text-white flex items-center justify-center mb-1.5 group-hover:scale-105 transition">
                            <i class="fa-solid fa-bullhorn text-sm"></i>
                        </div>
                        <span class="text-[11px] sm:text-xs font-bold text-levo-dark whitespace-nowrap">Thi Công Quảng Cáo</span>
                    </button>

                    <button onclick="selectCategory('vat-tu-nhom')" class="cat-box group p-2.5 rounded-xl border border-slate-200 hover:border-levo-primary bg-slate-50 hover:bg-levo-light transition text-center flex flex-col items-center justify-center">
                        <div class="w-9 h-9 rounded-full bg-levo-primary text-white flex items-center justify-center mb-1.5 group-hover:scale-105 transition">
                            <i class="fa-solid fa-layer-group text-sm"></i>
                        </div>
                        <span class="text-[11px] sm:text-xs font-bold text-levo-dark whitespace-nowrap">Vật Tư Nhôm</span>
                    </button>

                    <button onclick="selectCategory('phu-kien-bep')" class="cat-box group p-2.5 rounded-xl border border-slate-200 hover:border-levo-primary bg-slate-50 hover:bg-levo-light transition text-center flex flex-col items-center justify-center">
                        <div class="w-9 h-9 rounded-full bg-levo-primary text-white flex items-center justify-center mb-1.5 group-hover:scale-105 transition">
                            <i class="fa-solid fa-kitchen-set text-sm"></i>
                        </div>
                        <span class="text-[11px] sm:text-xs font-bold text-levo-dark whitespace-nowrap">Phụ Kiện Tủ Bếp</span>
                    </button>

                </div>
            </div>
        </section>

        <!-- 3. SECTION: SẢN PHẨM & CÔNG TRÌNH THỰC TẾ (LẤY 6 ẢNH THỰC TẾ TRONG GOOGLE DRIVE)
             - Không để các nhãn dán ở trang chủ
             - Sản phẩm chia thành 2 cột trên điện thoại (grid-cols-2)
             - Tên sản phẩm hiển thị đầy đủ, không bị tràn hay thiếu chữ -->
        <section id="san-pham-dich-vu" class="py-6 sm:py-8">
            <div class="flatsome-container">
                
                <!-- Tiêu đề & Thanh lọc danh mục nhỏ gọn -->
                <div class="section-title-container">
                    <div class="section-title-main">
                        <h2 class="text-sm sm:text-base md:text-lg">SẢN PHẨM & HÌNH ẢNH THI CÔNG THỰC TẾ</h2>
                        <div class="flex flex-wrap items-center gap-1.5 pt-2 sm:pt-0">
                            <button onclick="selectCategory('all')" data-cat="all" class="cat-tab-btn px-2.5 py-1 rounded text-[11px] font-semibold bg-levo-primary text-white whitespace-nowrap">
                                Tất cả
                            </button>
                            <button onclick="selectCategory('noi-that')" data-cat="noi-that" class="cat-tab-btn px-2.5 py-1 rounded text-[11px] font-semibold bg-white border border-slate-200 text-slate-700 hover:bg-slate-100 whitespace-nowrap">
                                Thi công nội thất
                            </button>
                            <button onclick="selectCategory('khu-vui-choi')" data-cat="khu-vui-choi" class="cat-tab-btn px-2.5 py-1 rounded text-[11px] font-semibold bg-white border border-slate-200 text-slate-700 hover:bg-slate-100 whitespace-nowrap">
                                Khu vui chơi
                            </button>
                            <button onclick="selectCategory('co-khi')" data-cat="co-khi" class="cat-tab-btn px-2.5 py-1 rounded text-[11px] font-semibold bg-white border border-slate-200 text-slate-700 hover:bg-slate-100 whitespace-nowrap">
                                Cơ khí
                            </button>
                            <button onclick="selectCategory('quang-cao')" data-cat="quang-cao" class="cat-tab-btn px-2.5 py-1 rounded text-[11px] font-semibold bg-white border border-slate-200 text-slate-700 hover:bg-slate-100 whitespace-nowrap">
                                Quảng cáo
                            </button>
                            <button onclick="selectCategory('vat-tu-nhom')" data-cat="vat-tu-nhom" class="cat-tab-btn px-2.5 py-1 rounded text-[11px] font-semibold bg-white border border-slate-200 text-slate-700 hover:bg-slate-100 whitespace-nowrap">
                                Vật tư nhôm
                            </button>
                            <button onclick="selectCategory('phu-kien-bep')" data-cat="phu-kien-bep" class="cat-tab-btn px-2.5 py-1 rounded text-[11px] font-semibold bg-white border border-slate-200 text-slate-700 hover:bg-slate-100 whitespace-nowrap">
                                Phụ kiện nội thất tủ bếp
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Lưới Sản Phẩm: Điện thoại 2 cột (grid-cols-2), Máy tính 3-4 cột. Hoàn toàn KHÔNG có nhãn dán (sticker/badge) -->
                <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                    <!-- Nội dung các sản phẩm được render từ danh sách 6 ảnh thực tế Google Drive bên dưới -->
                </div>

            </div>
        </section>

        <!-- 4. SECTION: HÌNH ẢNH THỰC TẾ TỪ XƯỞNG & CÔNG TRÌNH (TRƯNG BÀY ĐẦY ĐỦ 6 FILE GOOGLE DRIVE) -->
        <section class="py-6 bg-white border-y border-slate-200">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title-main">
                        <h2 class="text-sm sm:text-base md:text-lg">THƯ VIỆN ẢNH THỰC TẾ CÔNG TRÌNH L.E.V.O</h2>
                        <span class="text-xs text-slate-500">Hình ảnh thực tế thi công trực tiếp bởi đội ngũ L.E.V.O</span>
                    </div>
                </div>

                <!-- Chia 2 cột trên điện thoại, 3 cột trên máy tính -->
                <div class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-4">
                    <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-50 flex flex-col">
                        <div class="aspect-4/3 w-full overflow-hidden bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1WROwMPkWQroMnuniDEkrgjBmxRYxabuj&sz=w1000" 
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1WROwMPkWQroMnuniDEkrgjBmxRYxabuj';"
                                 alt="Thi công nội thất & tủ bếp L.E.V.O" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <h3 class="text-xs sm:text-sm font-bold text-levo-dark break-words">Thi Công Nội Thất Trọn Gói & Hệ Tủ Bếp Cao Cấp</h3>
                        </div>
                    </div>

                    <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-50 flex flex-col">
                        <div class="aspect-4/3 w-full overflow-hidden bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1LogWj9XB1Dg6667Hr41WF8ZcCajc8YNd&sz=w1000" 
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1LogWj9XB1Dg6667Hr41WF8ZcCajc8YNd';"
                                 alt="Thiết kế thi công khu vui chơi trẻ em" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <h3 class="text-xs sm:text-sm font-bold text-levo-dark break-words">Thiết Kế & Lắp Đặt Khu Vui Chơi Trẻ Em Trong Nhà</h3>
                        </div>
                    </div>

                    <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-50 flex flex-col">
                        <div class="aspect-4/3 w-full overflow-hidden bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1QOB0v0yom2cKy9maR-VTADTZd9O3SzuQ&sz=w1000" 
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1QOB0v0yom2cKy9maR-VTADTZd9O3SzuQ';"
                                 alt="Gia công cơ khí kết cấu" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <h3 class="text-xs sm:text-sm font-bold text-levo-dark break-words">Gia Công Cơ Khí, Khung Kết Cấu & Hạng Mục Sắt Thép</h3>
                        </div>
                    </div>

                    <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-50 flex flex-col">
                        <div class="aspect-4/3 w-full overflow-hidden bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1W8a5zLbMCml6qtzsSmehq1naBKQcpWtr&sz=w1000" 
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1W8a5zLbMCml6qtzsSmehq1naBKQcpWtr';"
                                 alt="Thi công bảng hiệu quảng cáo" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <h3 class="text-xs sm:text-sm font-bold text-levo-dark break-words">Thi Công Quảng Cáo, Mặt Dựng Alu & Chữ Nổi Đèn LED</h3>
                        </div>
                    </div>

                    <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-50 flex flex-col">
                        <div class="aspect-4/3 w-full overflow-hidden bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1LwtwFo2kftanBGRAxMR9HsU-rM1W-yua&sz=w1000" 
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1LwtwFo2kftanBGRAxMR9HsU-rM1W-yua';"
                                 alt="Cung cấp vật tư nhôm kính" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <h3 class="text-xs sm:text-sm font-bold text-levo-dark break-words">Phân Phối Vật Tư Nhôm Thanh Định Hình & Nhôm Nội Thất</h3>
                        </div>
                    </div>

                    <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-50 flex flex-col">
                        <div class="aspect-4/3 w-full overflow-hidden bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1S4f5dWmfG8tR5o03lPCUPkOL1pq_OrLK&sz=w1000" 
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1S4f5dWmfG8tR5o03lPCUPkOL1pq_OrLK';"
                                 alt="Phụ kiện nội thất tủ bếp" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <h3 class="text-xs sm:text-sm font-bold text-levo-dark break-words">Lắp Đặt Phụ Kiện Nội Thất Tủ Bếp Thông Minh Đồng Bộ</h3>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- 5. SECTION: FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ -->
        <section id="bao-gia" class="py-6 sm:py-8 bg-levo-light">
            <div class="flatsome-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-start">
                    
                    <!-- Cột thông tin quy trình làm việc (5/12) -->
                    <div class="lg:col-span-5 bg-levo-dark text-white rounded-xl p-5 sm:p-6 space-y-4">
                        <h2 class="text-base sm:text-lg font-extrabold text-amber-400 uppercase">
                            CÔNG TY TNHH L.E.V.O ARCHITECTURE & CONSTRUCTION
                        </h2>
                        <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
                            Chúng tôi nhận khảo sát tận nơi, lên phương án thiết kế và gửi bảng báo giá chi tiết từng hạng mục theo đúng ngân sách của quý khách hàng.
                        </p>
                        <ul class="space-y-2.5 text-xs sm:text-sm text-slate-100">
                            <li class="flex items-start gap-2.5">
                                <i class="fa-solid fa-circle-check text-amber-400 mt-1"></i>
                                <span><strong>Thi công nội thất & Khu vui chơi:</strong> Thiết kế 3D sáng tạo, an toàn, tối ưu công năng.</span>
                            </li>
                            <li class="flex items-start gap-2.5">
                                <i class="fa-solid fa-circle-check text-amber-400 mt-1"></i>
                                <span><strong>Cơ khí & Quảng cáo:</strong> Gia công trực tiếp tại xưởng, bền đẹp theo thời gian.</span>
                            </li>
                            <li class="flex items-start gap-2.5">
                                <i class="fa-solid fa-circle-check text-amber-400 mt-1"></i>
                                <span><strong>Vật tư nhôm & Phụ kiện tủ bếp:</strong> Giá sỉ tại kho, đầy đủ mẫu mã mới nhất.</span>
                            </li>
                        </ul>
                        <div class="pt-2 border-t border-white/15 text-xs sm:text-sm space-y-1.5">
                            <div><i class="fa-solid fa-location-dot text-amber-400 mr-2"></i><strong>Địa chỉ:</strong> 612B Nguyễn Lương Bằng, Phường Hải Vân, TP Đà Nẵng</div>
                            <div><i class="fa-solid fa-phone text-amber-400 mr-2"></i><strong>Hotline/Zalo:</strong> <a href="tel:0905952233" class="text-amber-300 font-bold">0905.952.233</a></div>
                            <div><i class="fa-solid fa-globe text-amber-400 mr-2"></i><strong>Website:</strong> levo.com</div>
                        </div>
                    </div>

                    <!-- Cột Form Yêu Cầu & Báo Giá (7/12) -->
                    <div class="lg:col-span-7 bg-white rounded-xl p-5 sm:p-6 border border-slate-200 shadow-xs">
                        <h3 class="text-base sm:text-lg font-extrabold text-levo-dark uppercase mb-1">
                            ĐĂNG KÝ YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ
                        </h3>
                        <p class="text-xs text-slate-500 mb-4">
                            Điền thông tin bên dưới, bộ phận kỹ thuật L.E.V.O sẽ liên hệ báo giá nhanh qua SĐT/Zalo.
                        </p>

                        <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="space-y-3.5">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên quý khách *</label>
                                    <input type="text" id="custName" required placeholder="Nhập họ và tên..." 
                                           class="w-full px-3.5 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:border-levo-primary focus:outline-none">
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                    <input type="tel" id="custPhone" required placeholder="Ví dụ: 0905952233" 
                                           class="w-full px-3.5 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:border-levo-primary focus:outline-none">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Hạng mục cần báo giá *</label>
                                    <select id="custCategory" class="w-full px-3.5 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:border-levo-primary focus:outline-none bg-white">
                                        <option value="Thi công nội thất">Thi công nội thất</option>
                                        <option value="Thiết kế & Thi công khu vui chơi">Thiết kế & Thi công khu vui chơi</option>
                                        <option value="Gia công cơ khí">Gia công cơ khí</option>
                                        <option value="Thi công quảng cáo">Thi công quảng cáo</option>
                                        <option value="Mua vật tư nhôm">Mua vật tư nhôm</option>
                                        <option value="Phụ kiện nội thất tủ bếp">Phụ kiện nội thất tủ bếp</option>
                                        <option value="Trọn gói nhiều hạng mục">Trọn gói nhiều hạng mục</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Khu vực / Địa điểm công trình</label>
                                    <input type="text" id="custAddress" placeholder="Ví dụ: Liên Chiểu, Đà Nẵng..." 
                                           class="w-full px-3.5 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:border-levo-primary focus:outline-none">
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Nội dung yêu cầu chi tiết (Kích thước, nhu cầu vật tư...)</label>
                                <textarea id="custNote" rows="3" placeholder="Mô tả sơ bộ nhu cầu thi công hoặc mã sản phẩm cần báo giá..." 
                                          class="w-full px-3.5 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:border-levo-primary focus:outline-none"></textarea>
                            </div>

                            <div class="flex flex-wrap items-center justify-between gap-3 pt-1">
                                <button type="submit" class="bg-levo-primary hover:bg-levo-dark text-white font-bold text-xs sm:text-sm px-6 py-2.5 rounded-lg transition cursor-pointer">
                                    <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU BÁO GIÁ
                                </button>
                                <a href="https://zalo.me/0905952233" target="_blank" rel="noopener" class="text-xs font-bold text-levo-primary hover:underline">
                                    <i class="fa-solid fa-comments mr-1"></i>Hoặc nhắn trực tiếp qua Zalo: 0905.952.233
                                </a>
                            </div>

                            <!-- Thông báo gửi thành công -->
                            <div id="quoteSuccessBox" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs font-medium"></div>
                        </form>
                    </div>

                </div>
            </div>
        </section>

        <!-- 6. SECTION: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ -->
        <section id="bai-viet" class="py-6 sm:py-8 bg-white">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title-main">
                        <h2 class="text-sm sm:text-base md:text-lg">DANH MỤC BÀI VIẾT & KINH NGHIỆM THI CÔNG</h2>
                        <span class="text-xs text-slate-500">Cập nhật xu hướng thiết kế & vật tư mới nhất</span>
                    </div>
                </div>

                <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    
                    <!-- Bài viết 1 -->
                    <article class="rounded-xl border border-slate-200 bg-white overflow-hidden flex flex-col hover:shadow-md transition">
                        <div class="aspect-16/10 w-full bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1LogWj9XB1Dg6667Hr41WF8ZcCajc8YNd&sz=w800" 
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1LogWj9XB1Dg6667Hr41WF8ZcCajc8YNd';"
                                 alt="Bài viết khu vui chơi" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3 flex-1 flex flex-col justify-between space-y-2">
                            <div>
                                <div class="text-[10px] font-bold text-levo-primary uppercase mb-1">Khu Vui Chơi Trẻ Em</div>
                                <h3 class="text-xs sm:text-sm font-bold text-levo-dark leading-snug break-words">
                                    Kinh Nghiệm Thiết Kế Thi Công Khu Vui Chơi Trẻ Em Thu Hút Khách & Nhanh Thu Hồi Vốn
                                </h3>
                                <p class="text-[11px] text-slate-600 mt-1.5 hidden sm:block">
                                    Cách bố trí nhà liên hoàn, hồ bóng, sàn xốp an toàn và phối màu sắc sinh động cho mặt bằng kinh doanh.
                                </p>
                            </div>
                            <button onclick="openArticleModal(0)" class="text-left text-[11px] font-bold text-levo-primary hover:underline pt-1">
                                Xem chi tiết <i class="fa-solid fa-arrow-right ml-0.5 text-[10px]"></i>
                            </button>
                        </div>
                    </article>

                    <!-- Bài viết 2 -->
                    <article class="rounded-xl border border-slate-200 bg-white overflow-hidden flex flex-col hover:shadow-md transition">
                        <div class="aspect-16/10 w-full bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1WROwMPkWQroMnuniDEkrgjBmxRYxabuj&sz=w800" 
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1WROwMPkWQroMnuniDEkrgjBmxRYxabuj';"
                                 alt="Bài viết thi công nội thất" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3 flex-1 flex flex-col justify-between space-y-2">
                            <div>
                                <div class="text-[10px] font-bold text-levo-primary uppercase mb-1">Thi Công Nội Thất</div>
                                <h3 class="text-xs sm:text-sm font-bold text-levo-dark leading-snug break-words">
                                    Báo Giá Thi Công Nội Thất Phòng Khách & Tủ Bếp Cánh Kính Khung Nhôm Tại Đà Nẵng
                                </h3>
                                <p class="text-[11px] text-slate-600 mt-1.5 hidden sm:block">
                                    So sánh độ bền giữa gỗ công nghiệp MDF lõi xanh chống ẩm và hệ tủ bếp hợp kim nhôm cao cấp.
                                </p>
                            </div>
                            <button onclick="openArticleModal(1)" class="text-left text-[11px] font-bold text-levo-primary hover:underline pt-1">
                                Xem chi tiết <i class="fa-solid fa-arrow-right ml-0.5 text-[10px]"></i>
                            </button>
                        </div>
                    </article>

                    <!-- Bài viết 3 -->
                    <article class="rounded-xl border border-slate-200 bg-white overflow-hidden flex flex-col hover:shadow-md transition">
                        <div class="aspect-16/10 w-full bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1LwtwFo2kftanBGRAxMR9HsU-rM1W-yua&sz=w800" 
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1LwtwFo2kftanBGRAxMR9HsU-rM1W-yua';"
                                 alt="Bài viết vật tư nhôm và phụ kiện tủ bếp" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3 flex-1 flex flex-col justify-between space-y-2">
                            <div>
                                <div class="text-[10px] font-bold text-levo-primary uppercase mb-1">Nhôm & Phụ Kiện Bếp</div>
                                <h3 class="text-xs sm:text-sm font-bold text-levo-dark leading-snug break-words">
                                    Danh Mục Phụ Kiện Nội Thất Tủ Bếp Thông Minh & Vật Tư Nhôm Không Thể Thiếu
                                </h3>
                                <p class="text-[11px] text-slate-600 mt-1.5 hidden sm:block">
                                    Giá bát nâng hạ, kệ xoong nồi Inox 304, bản lề giảm chấn và hệ nhôm nội thất thế hệ mới.
                                </p>
                            </div>
                            <button onclick="openArticleModal(2)" class="text-left text-[11px] font-bold text-levo-primary hover:underline pt-1">
                                Xem chi tiết <i class="fa-solid fa-arrow-right ml-0.5 text-[10px]"></i>
                            </button>
                        </div>
                    </article>

                    <!-- Bài viết 4 -->
                    <article class="rounded-xl border border-slate-200 bg-white overflow-hidden flex flex-col hover:shadow-md transition">
                        <div class="aspect-16/10 w-full bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1W8a5zLbMCml6qtzsSmehq1naBKQcpWtr&sz=w800" 
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1W8a5zLbMCml6qtzsSmehq1naBKQcpWtr';"
                                 alt="Bài viết cơ khí quảng cáo" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3 flex-1 flex flex-col justify-between space-y-2">
                            <div>
                                <div class="text-[10px] font-bold text-levo-primary uppercase mb-1">Cơ Khí & Quảng Cáo</div>
                                <h3 class="text-xs sm:text-sm font-bold text-levo-dark leading-snug break-words">
                                    Quy Trình Gia Công Cơ Khí Khung Thép Tiền Chế & Bảng Hiệu Quảng Cáo Bền Đẹp
                                </h3>
                                <p class="text-[11px] text-slate-600 mt-1.5 hidden sm:block">
                                    Tiêu chuẩn kỹ thuật chống gỉ sét cho công trình ven biển Đà Nẵng và bảo hành dài hạn.
                                </p>
                            </div>
                            <button onclick="openArticleModal(3)" class="text-left text-[11px] font-bold text-levo-primary hover:underline pt-1">
                                Xem chi tiết <i class="fa-solid fa-arrow-right ml-0.5 text-[10px]"></i>
                            </button>
                        </div>
                    </article>

                </div>
            </div>
        </section>

        <!-- 7. SECTION: DANH MỤC CÁC ĐỐI TÁC -->
        <section id="doi-tac" class="py-6 bg-slate-50 border-y border-slate-200">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title-main">
                        <h2 class="text-sm sm:text-base md:text-lg">ĐỐI TÁC & THƯƠNG HIỆU VẬT TƯ ĐỒNG HÀNH</h2>
                        <span class="text-xs text-slate-500">Hợp tác cung ứng vật tư chính hãng chất lượng cao</span>
                    </div>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
                    <div class="bg-white p-3 rounded-xl border border-slate-200 flex flex-col items-center justify-center text-center h-20">
                        <span class="font-extrabold text-sm text-levo-dark tracking-wider">AN CƯỜNG</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Gỗ Công Nghiệp Nội Thất</span>
                    </div>
                    <div class="bg-white p-3 rounded-xl border border-slate-200 flex flex-col items-center justify-center text-center h-20">
                        <span class="font-extrabold text-sm text-levo-primary tracking-wider">XINGFA GROUP</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Hệ Nhôm Định Hình</span>
                    </div>
                    <div class="bg-white p-3 rounded-xl border border-slate-200 flex flex-col items-center justify-center text-center h-20">
                        <span class="font-extrabold text-sm text-red-700 tracking-wider">HÄFELE</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Phụ Kiện Nội Thất Bếp</span>
                    </div>
                    <div class="bg-white p-3 rounded-xl border border-slate-200 flex flex-col items-center justify-center text-center h-20">
                        <span class="font-extrabold text-sm text-amber-600 tracking-wider">BLUM</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Phụ Kiện Bản Lề & Ray</span>
                    </div>
                    <div class="bg-white p-3 rounded-xl border border-slate-200 flex flex-col items-center justify-center text-center h-20">
                        <span class="font-extrabold text-sm text-emerald-700 tracking-wider">EUROGOLD</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Phụ Kiện Tủ Bếp Inox 304</span>
                    </div>
                    <div class="bg-white p-3 rounded-xl border border-slate-200 flex flex-col items-center justify-center text-center h-20">
                        <span class="font-extrabold text-sm text-blue-800 tracking-wider">HÒA PHÁT</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Thép & Cơ Khí Xây Dựng</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- 8. SECTION: ĐƯA FANPAGE & GOOGLE MAP RA NGOÀI TRANG CHỦ -->
        <section id="ket-noi-bando" class="py-6 sm:py-8 bg-white">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title-main">
                        <h2 class="text-sm sm:text-base md:text-lg">KẾT NỐI FANPAGE & BẢN ĐỒ CHỈ ĐƯỜNG</h2>
                        <span class="text-xs text-slate-500">612B Nguyễn Lương Bằng, Phường Hải Vân, TP Đà Nẵng</span>
                    </div>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-2 gap-5">
                    
                    <!-- Khối Fanpage Facebook ngoài trang chủ -->
                    <div class="rounded-xl border border-slate-200 bg-slate-50 p-4 flex flex-col justify-between space-y-3">
                        <div class="flex items-center gap-3 pb-3 border-b border-slate-200">
                            <img src="https://drive.google.com/thumbnail?id=1TdJQi_jTp3zFtTTmiFq0ncLbENU86AK4&sz=w200" 
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1TdJQi_jTp3zFtTTmiFq0ncLbENU86AK4';"
                                 alt="Logo Fanpage L.E.V.O" class="w-12 h-12 rounded-lg object-contain bg-white border border-slate-200 p-1 shrink-0">
                            <div class="min-w-0">
                                <h3 class="text-xs sm:text-sm font-extrabold text-levo-dark break-words">
                                    CÔNG TY TNHH L.E.V.O ARCHITECTURE & CONSTRUCTION
                                </h3>
                                <p class="text-[11px] text-slate-600">
                                    Fanpage chính thức • Cập nhật hình ảnh công trình mỗi ngày
                                </p>
                            </div>
                        </div>

                        <!-- Nhúng Facebook Page Plugin + Khung kết nối trực tiếp -->
                        <div class="w-full overflow-hidden rounded-lg bg-white border border-slate-200">
                            <iframe 
                                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D61575512366433&tabs=timeline&width=500&height=220&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                                width="100%" height="220" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowfullscreen="true" 
                                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                            </iframe>
                        </div>

                        <div class="flex flex-wrap items-center justify-between gap-2 pt-1">
                            <span class="text-xs text-slate-600">
                                <i class="fa-brands fa-facebook text-blue-600 mr-1"></i>Theo dõi chúng tôi trên Facebook
                            </span>
                            <a href="https://www.facebook.com/profile.php?id=61575512366433" target="_blank" rel="noopener" 
                               class="inline-flex items-center gap-1.5 bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold px-4 py-2 rounded-lg transition">
                                <i class="fa-brands fa-facebook-f"></i> Truy Cập Fanpage L.E.V.O
                            </a>
                        </div>
                    </div>

                    <!-- Khối Bản Đồ Google Map ngoài trang chủ -->
                    <div class="rounded-xl border border-slate-200 bg-slate-50 p-4 flex flex-col justify-between space-y-3">
                        <div class="flex items-start justify-between gap-2 pb-2 border-b border-slate-200">
                            <div>
                                <h3 class="text-xs sm:text-sm font-extrabold text-levo-dark">
                                    <i class="fa-solid fa-map-location-dot text-red-600 mr-1.5"></i>VỊ TRÍ TRÊN GOOGLE MAPS
                                </h3>
                                <p class="text-[11px] sm:text-xs text-slate-600 mt-0.5">
                                    Địa chỉ: <strong>612B Nguyễn Lương Bằng, Phường Hải Vân, TP Đà Nẵng</strong>
                                </p>
                            </div>
                        </div>

                        <div class="w-full h-[220px] rounded-lg overflow-hidden border border-slate-200 bg-slate-200">
                            <iframe 
                                src="https://maps.google.com/maps?q=612B%20Nguy%E1%BB%85n%20L%C6%B0%C6%A1ng%20B%E1%BA%B1ng%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed" 
                                width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"
                                title="Bản đồ 612B Nguyễn Lương Bằng, Phường Hải Vân, TP Đà Nẵng">
                            </iframe>
                        </div>

                        <div class="flex flex-wrap items-center justify-between gap-2 pt-1">
                            <span class="text-xs text-slate-600">
                                <i class="fa-solid fa-phone text-levo-primary mr-1"></i>Hotline chỉ đường: <strong>0905.952.233</strong>
                            </span>
                            <a href="https://www.google.com/maps/search/?api=1&query=612B+Nguyễn+Lương+Bằng,+Đà+Nẵng" target="_blank" rel="noopener" 
                               class="inline-flex items-center gap-1.5 bg-levo-primary hover:bg-levo-dark text-white text-xs font-bold px-4 py-2 rounded-lg transition">
                                <i class="fa-solid fa-diamond-turn-right"></i> Mở Google Maps Lớn
                            </a>
                        </div>
                    </div>

                </div>
            </div>
        </section>

    </main>

    <!-- =====================================================================
         FLATSOME FOOTER (#footer)
         ===================================================================== -->
    <footer id="footer" class="bg-levo-dark text-slate-200 pt-8 pb-6 border-t-4 border-amber-500">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6 pb-6 border-b border-white/15">
                
                <!-- Cột 1: Thông tin công ty -->
                <div class="space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <img src="https://drive.google.com/thumbnail?id=1TdJQi_jTp3zFtTTmiFq0ncLbENU86AK4&sz=w200" 
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1TdJQi_jTp3zFtTTmiFq0ncLbENU86AK4';"
                             alt="Logo L.E.V.O" class="w-10 h-10 rounded bg-white p-0.5 object-contain shrink-0">
                        <div>
                            <div class="text-sm font-extrabold text-white">levo.com</div>
                            <div class="text-[11px] text-amber-400 font-semibold">L.E.V.O ARCHITECTURE & CONSTRUCTION</div>
                        </div>
                    </div>
                    <p class="text-xs text-slate-300 leading-relaxed">
                        CÔNG TY TNHH L.E.V.O ARCHITECTURE & CONSTRUCTION chuyên thiết kế, thi công nội thất, khu vui chơi trẻ em, cơ khí, quảng cáo, cung cấp vật tư nhôm và phụ kiện nội thất tủ bếp.
                    </p>
                </div>

                <!-- Cột 2: Danh mục dịch vụ -->
                <div class="space-y-2">
                    <h4 class="text-xs sm:text-sm font-extrabold text-amber-400 uppercase">LĨNH VỰC HOẠT ĐỘNG</h4>
                    <ul class="grid grid-cols-2 gap-1.5 text-xs text-slate-300">
                        <li><a href="#san-pham-dich-vu" onclick="selectCategory('noi-that')" class="hover:text-white">• Thi công nội thất</a></li>
                        <li><a href="#san-pham-dich-vu" onclick="selectCategory('khu-vui-choi')" class="hover:text-white">• Khu vui chơi</a></li>
                        <li><a href="#san-pham-dich-vu" onclick="selectCategory('co-khi')" class="hover:text-white">• Gia công cơ khí</a></li>
                        <li><a href="#san-pham-dich-vu" onclick="selectCategory('quang-cao')" class="hover:text-white">• Thi công quảng cáo</a></li>
                        <li><a href="#san-pham-dich-vu" onclick="selectCategory('vat-tu-nhom')" class="hover:text-white">• Vật tư nhôm</a></li>
                        <li><a href="#san-pham-dich-vu" onclick="selectCategory('phu-kien-bep')" class="hover:text-white">• Phụ kiện tủ bếp</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Liên hệ trực tiếp -->
                <div class="space-y-2 text-xs">
                    <h4 class="text-xs sm:text-sm font-extrabold text-amber-400 uppercase">THÔNG TIN LIÊN HỆ</h4>
                    <p><i class="fa-solid fa-location-dot text-amber-400 mr-2"></i><strong>Địa chỉ:</strong> 612B Nguyễn Lương Bằng, Phường Hải Vân, TP Đà Nẵng</p>
                    <p><i class="fa-solid fa-phone text-amber-400 mr-2"></i><strong>Điện thoại / Zalo:</strong> <a href="tel:0905952233" class="text-amber-300 font-bold">0905.952.233</a></p>
                    <p><i class="fa-solid fa-globe text-amber-400 mr-2"></i><strong>Website:</strong> levo.com</p>
                    <p><i class="fa-brands fa-facebook text-amber-400 mr-2"></i><strong>Fanpage:</strong> <a href="https://www.facebook.com/profile.php?id=61575512366433" target="_blank" rel="noopener" class="underline hover:text-white">L.E.V.O Architecture & Construction</a></p>
                </div>

            </div>

            <div class="pt-4 text-center text-[11px] text-slate-400">
                © Bản quyền thuộc về <strong>CÔNG TY TNHH L.E.V.O ARCHITECTURE & CONSTRUCTION</strong> (levo.com). Giao diện chuẩn UX Builder Flatsome.
            </div>
        </div>
    </footer>

    <!-- =====================================================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         Tương thích hoàn hảo trên máy tính & điện thoại, không gây tràn viền
         ===================================================================== -->
    <div class="fixed bottom-4 right-3 sm:right-4 z-50 flex flex-col items-end gap-2.5">
        
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/profile.php?id=61575512366433" target="_blank" rel="noopener"
           aria-label="Chat Facebook Fanpage"
           class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition">
            <i class="fa-brands fa-facebook-f text-sm w-4 text-center"></i>
            <span class="text-xs font-bold">Facebook</span>
        </a>

        <!-- Nút Zalo 0905.952.233 -->
        <a href="https://zalo.me/0905952233" target="_blank" rel="noopener"
           aria-label="Nhắn Zalo 0905.952.233"
           class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-600 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="font-extrabold text-xs bg-white text-[#0068ff] rounded-full w-4 h-4 flex items-center justify-center">Z</span>
            <span class="text-xs font-bold">Zalo: 0905.952.233</span>
        </a>

        <!-- Nút Hotline Gọi Ngay -->
        <a href="tel:0905952233"
           aria-label="Gọi Hotline 0905.952.233"
           class="floating-btn-pulse flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white px-3.5 py-2.5 rounded-full shadow-xl transition">
            <i class="fa-solid fa-phone-volume text-sm"></i>
            <span class="text-xs sm:text-sm font-extrabold">0905.952.233</span>
        </a>

    </div>

    <!-- =====================================================================
         MODAL XEM CHI TIẾT BÀI VIẾT / BÁO GIÁ NHANH (KHÔNG DÙNG ALERT)
         ===================================================================== -->
    <div id="infoModal" class="fixed inset-0 bg-black/60 z-50 hidden items-center justify-center p-4">
        <div class="bg-white rounded-xl max-w-lg w-full p-5 space-y-3 shadow-2xl border border-slate-200 max-h-[85vh] overflow-y-auto">
            <div class="flex items-start justify-between gap-3 border-b border-slate-200 pb-2.5">
                <h3 id="modalTitle" class="text-sm sm:text-base font-extrabold text-levo-dark">Thông tin chi tiết</h3>
                <button onclick="closeInfoModal()" class="text-slate-400 hover:text-slate-700 text-lg leading-none">&times;</button>
            </div>
            <div id="modalBody" class="text-xs sm:text-sm text-slate-600 space-y-2 leading-relaxed"></div>
            <div class="pt-3 border-t border-slate-200 flex items-center justify-end gap-2">
                <a href="tel:0905952233" class="bg-levo-primary text-white text-xs font-bold px-4 py-2 rounded-lg">
                    <i class="fa-solid fa-phone mr-1"></i>Gọi 0905.952.233
                </a>
                <button onclick="closeInfoModal()" class="bg-slate-200 text-slate-700 text-xs font-bold px-4 py-2 rounded-lg">
                    Đóng
                </button>
            </div>
        </div>
    </div>

    <!-- =====================================================================
         JAVASCRIPT XỬ LÝ BANNER TỰ TRƯỢT, LỌC DANH MỤC & FORM BÁO GIÁ
         ===================================================================== -->
    <script>
        // Danh sách 6 ảnh thực tế Google Drive của công ty
        const drivePhotos = [
            "https://drive.google.com/thumbnail?id=1WROwMPkWQroMnuniDEkrgjBmxRYxabuj&sz=w1000",
            "https://drive.google.com/thumbnail?id=1LogWj9XB1Dg6667Hr41WF8ZcCajc8YNd&sz=w1000",
            "https://drive.google.com/thumbnail?id=1QOB0v0yom2cKy9maR-VTADTZd9O3SzuQ&sz=w1000",
            "https://drive.google.com/thumbnail?id=1W8a5zLbMCml6qtzsSmehq1naBKQcpWtr&sz=w1000",
            "https://drive.google.com/thumbnail?id=1LwtwFo2kftanBGRAxMR9HsU-rM1W-yua&sz=w1000",
            "https://drive.google.com/thumbnail?id=1S4f5dWmfG8tR5o03lPCUPkOL1pq_OrLK&sz=w1000"
        ];

        // Dữ liệu 12 sản phẩm/hạng mục chia đều vào 6 danh mục, sử dụng 6 ảnh thực tế Google Drive
        const productsData = [
            {
                id: 1,
                category: "noi-that",
                categoryName: "Thi công nội thất",
                title: "Thi Công Nội Thất Phòng Khách & Căn Hộ Trọn Gói",
                img: drivePhotos[0],
                fallbackId: "1WROwMPkWQroMnuniDEkrgjBmxRYxabuj",
                desc: "Thiết kế 3D và thi công hoàn thiện nội thất gỗ công nghiệp chống ẩm, tủ kệ tivi, vách ốp trang trí hiện đại."
            },
            {
                id: 2,
                category: "noi-that",
                categoryName: "Thi công nội thất",
                title: "Thiết Kế Thi Công Tủ Bếp Cánh Kính & Nội Thất Phòng Ngủ",
                img: drivePhotos[5],
                fallbackId: "1S4f5dWmfG8tR5o03lPCUPkOL1pq_OrLK",
                desc: "Gia công lắp đặt hệ tủ bếp chữ L, chữ I, tủ quần áo kịch trần chuẩn kích thước thực tế tại Đà Nẵng."
            },
            {
                id: 3,
                category: "khu-vui-choi",
                categoryName: "Khu vui chơi",
                title: "Thiết Kế & Thi Công Khu Vui Chơi Trẻ Em Liên Hoàn Trong Nhà",
                img: drivePhotos[1],
                fallbackId: "1LogWj9XB1Dg6667Hr41WF8ZcCajc8YNd",
                desc: "Lắp đặt trọn gói nhà banh, cầu trượt liên hoàn, khu vận động mềm an toàn cho trung tâm thương mại, trường mầm non."
            },
            {
                id: 4,
                category: "khu-vui-choi",
                categoryName: "Khu vui chơi",
                title: "Thi Công Khu Vui Chơi Kids Cafe & Khu Vận Động Sáng Tạo",
                img: drivePhotos[0],
                fallbackId: "1WROwMPkWQroMnuniDEkrgjBmxRYxabuj",
                desc: "Tư vấn mô hình Kids Cafe kết hợp khu vui chơi trẻ em hiện đại, tối ưu diện tích và chi phí đầu tư."
            },
            {
                id: 5,
                category: "co-khi",
                categoryName: "Cơ khí",
                title: "Gia Công Cơ Khí Kết Cấu Khung Thép, Mái Che & Cầu Thang",
                img: drivePhotos[2],
                fallbackId: "1QOB0v0yom2cKy9maR-VTADTZd9O3SzuQ",
                desc: "Đội ngũ thợ cơ khí lành nghề chuyên thi công khung nhà tiền chế, mái kính sắt nghệ thuật, lan can cầu thang."
            },
            {
                id: 6,
                category: "co-khi",
                categoryName: "Cơ khí",
                title: "Thi Công Khung Sắt Bảo Vệ, Cổng Cửa Sắt Sơn Tĩnh Điện",
                img: drivePhotos[3],
                fallbackId: "1W8a5zLbMCml6qtzsSmehq1naBKQcpWtr",
                desc: "Gia công cơ khí chính xác theo bản vẽ kỹ thuật, mối hàn thẩm mỹ, chống ăn mòn cao."
            },
            {
                id: 7,
                category: "quang-cao",
                categoryName: "Quảng cáo",
                title: "Thi Công Bảng Hiệu Quảng Cáo Alu, Chữ Nổi Mica Đèn LED",
                img: drivePhotos[3],
                fallbackId: "1W8a5zLbMCml6qtzsSmehq1naBKQcpWtr",
                desc: "Thiết kế và lắp đặt bảng hiệu showroom, cửa hàng, mặt dựng Alu chữ nổi Inox sáng chân nổi bật ban đêm."
            },
            {
                id: 8,
                category: "quang-cao",
                categoryName: "Quảng cáo",
                title: "Trang Trí Nội Ngoại Thất Showroom, Hộp Đèn & Vách Logo",
                img: drivePhotos[1],
                fallbackId: "1LogWj9XB1Dg6667Hr41WF8ZcCajc8YNd",
                desc: "Thi công bộ nhận diện thương hiệu quầy lễ tân, hộp đèn quảng cáo siêu mỏng sắc nét."
            },
            {
                id: 9,
                category: "vat-tu-nhom",
                categoryName: "Vật tư nhôm",
                title: "Cung Cấp Vật Tư Nhôm Nội Thất, Nhôm Cánh Kính & Nhôm Định Hình",
                img: drivePhotos[4],
                fallbackId: "1LwtwFo2kftanBGRAxMR9HsU-rM1W-yua",
                desc: "Phân phối sỉ & lẻ thanh nhôm nội thất, nhôm tủ bếp, nhôm vách ngăn chất lượng cao tại Đà Nẵng."
            },
            {
                id: 10,
                category: "vat-tu-nhom",
                categoryName: "Vật tư nhôm",
                title: "Phân Phối Vật Tư Nhôm Kính & Phụ Kiện Lắp Đặt Đồng Bộ",
                img: drivePhotos[2],
                fallbackId: "1QOB0v0yom2cKy9maR-VTADTZd9O3SzuQ",
                desc: "Đầy đủ mã màu nhôm anode, nhôm vân gỗ, phụ kiện ke góc, gioăng cao su phục vụ xưởng sản xuất."
            },
            {
                id: 11,
                category: "phu-kien-bep",
                categoryName: "Phụ kiện nội thất tủ bếp",
                title: "Trọn Bộ Phụ Kiện Nội Thất Tủ Bếp Inox 304 Thông Minh",
                img: drivePhotos[5],
                fallbackId: "1S4f5dWmfG8tR5o03lPCUPkOL1pq_OrLK",
                desc: "Giá bát nâng hạ, giá xoong nồi, kệ gia vị dao thớt, thùng gạo âm tủ, bản lề giảm chấn chính hãng."
            },
            {
                id: 12,
                category: "phu-kien-bep",
                categoryName: "Phụ kiện nội thất tủ bếp",
                title: "Phụ Kiện Tủ Áo, Ray Trượt Giảm Chấn & Tay Nắm Nội Thất",
                img: drivePhotos[4],
                fallbackId: "1LwtwFo2kftanBGRAxMR9HsU-rM1W-yua",
                desc: "Cung cấp phụ kiện tủ bếp và phụ kiện tủ quần áo cao cấp, hỗ trợ giao hàng và lắp đặt tận nơi."
            }
        ];

        let currentCategory = "all";
        let currentSearch = "";

        // Hàm hiển thị danh sách sản phẩm (Chia 2 cột trên ĐT, không nhãn dán, tên đầy đủ không bị cắt)
        function renderProducts() {
            const grid = document.getElementById("productGrid");
            const filtered = productsData.filter(item => {
                const matchCat = (currentCategory === "all") || (item.category === currentCategory);
                const matchSearch = item.title.toLowerCase().includes(currentSearch.toLowerCase()) ||
                                    item.categoryName.toLowerCase().includes(currentSearch.toLowerCase());
                return matchCat && matchSearch;
            });

            if (filtered.length === 0) {
                grid.innerHTML = `
                    <div class="col-span-full py-8 text-center text-xs sm:text-sm text-slate-500 bg-white rounded-xl border border-slate-200">
                        Không tìm thấy sản phẩm phù hợp. Quý khách vui lòng chọn danh mục khác hoặc liên hệ <strong>0905.952.233</strong>.
                    </div>
                `;
                return;
            }

            grid.innerHTML = filtered.map(item => `
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
                            <img src="${item.img}" 
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/${item.fallbackId}';"
                                 alt="${item.title}" 
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5 space-y-1.5">
                            <div class="text-[10px] font-semibold text-levo-primary uppercase">
                                ${item.categoryName}
                            </div>
                            <!-- Tên sản phẩm tự động xuống hàng đầy đủ, không bao giờ bị tràn ra ngoài hay thiếu chữ -->
                            <h3 class="text-xs sm:text-sm font-bold text-levo-dark leading-snug break-words whitespace-normal">
                                ${item.title}
                            </h3>
                            <p class="text-[11px] text-slate-600 leading-relaxed break-words">
                                ${item.desc}
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 flex items-center justify-between gap-2 border-t border-slate-100 mt-1">
                        <span class="text-[11px] font-extrabold text-amber-600">Liên hệ: 0905.952.233</span>
                        <button onclick="quickQuote('${item.title.replace(/'/g, "\\'")}')" class="bg-levo-primary hover:bg-levo-dark text-white text-[11px] font-bold px-2.5 py-1.5 rounded-lg transition cursor-pointer shrink-0">
                            Báo giá
                        </button>
                    </div>
                </div>
            `).join("");
        }

        // Lọc theo danh mục
        function selectCategory(cat) {
            currentCategory = cat;
            document.querySelectorAll(".cat-tab-btn").forEach(btn => {
                if (btn.getAttribute("data-cat") === cat) {
                    btn.className = "cat-tab-btn px-2.5 py-1 rounded text-[11px] font-semibold bg-levo-primary text-white whitespace-nowrap";
                } else {
                    btn.className = "cat-tab-btn px-2.5 py-1 rounded text-[11px] font-semibold bg-white border border-slate-200 text-slate-700 hover:bg-slate-100 whitespace-nowrap";
                }
            });
            renderProducts();
        }

        // Tìm kiếm sản phẩm
        function filterProductsBySearch(keyword) {
            currentSearch = keyword || "";
            renderProducts();
        }

        // Chọn sản phẩm điền nhanh vào form báo giá
        function quickQuote(productName) {
            const noteEl = document.getElementById("custNote");
            if (noteEl) {
                noteEl.value = "Tôi cần tư vấn và báo giá hạng mục: " + productName;
            }
            const formSection = document.getElementById("bao-gia");
            if (formSection) {
                formSection.scrollIntoView({ behavior: "smooth" });
            }
        }

        // Điều khiển 2 Banner tự trượt
        let activeBanner = 0;
        let bannerInterval = null;

        function showBanner(index) {
            activeBanner = index;
            const slide0 = document.getElementById("bannerSlide0");
            const slide1 = document.getElementById("bannerSlide1");
            const dot0 = document.getElementById("bannerDot0");
            const dot1 = document.getElementById("bannerDot1");

            if (activeBanner === 0) {
                slide0.classList.remove("opacity-0", "z-0", "pointer-events-none");
                slide0.classList.add("opacity-100", "z-10");
                slide1.classList.remove("opacity-100", "z-10");
                slide1.classList.add("opacity-0", "z-0", "pointer-events-none");
                dot0.className = "w-6 h-2 rounded-full bg-amber-400 transition-all";
                dot1.className = "w-2.5 h-2 rounded-full bg-white/60 transition-all";
            } else {
                slide1.classList.remove("opacity-0", "z-0", "pointer-events-none");
                slide1.classList.add("opacity-100", "z-10");
                slide0.classList.remove("opacity-100", "z-10");
                slide0.classList.add("opacity-0", "z-0", "pointer-events-none");
                dot1.className = "w-6 h-2 rounded-full bg-amber-400 transition-all";
                dot0.className = "w-2.5 h-2 rounded-full bg-white/60 transition-all";
            }
        }

        function nextBanner() {
            showBanner(activeBanner === 0 ? 1 : 0);
            resetBannerTimer();
        }

        function prevBanner() {
            showBanner(activeBanner === 0 ? 1 : 0);
            resetBannerTimer();
        }

        function goToBanner(idx) {
            showBanner(idx);
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                showBanner(activeBanner === 0 ? 1 : 0);
            }, 5000);
        }

        // Bật/Tắt Menu trên điện thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById("mobileMenuDrawer");
            drawer.classList.toggle("hidden");
        }

        // Xử lý gửi Form Báo Giá
        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById("custName").value.trim();
            const phone = document.getElementById("custPhone").value.trim();
            const category = document.getElementById("custCategory").value;
            const box = document.getElementById("quoteSuccessBox");

            box.innerHTML = `<i class="fa-solid fa-circle-check mr-1.5"></i>Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu báo giá hạng mục <strong>${category}</strong> đã được ghi nhận. Bộ phận kỹ thuật L.E.V.O sẽ liên hệ ngay hoặc quý khách có thể gọi trực tiếp <strong>0905.952.233</strong>.`;
            box.classList.remove("hidden");
            document.getElementById("quoteRequestForm").reset();
        }

        // Nội dung chi tiết 4 bài viết trang chủ
        const articlesContent = [
            {
                title: "Kinh Nghiệm Thiết Kế Thi Công Khu Vui Chơi Trẻ Em Thu Hút Khách",
                body: `
                    <p><strong>CÔNG TY TNHH L.E.V.O ARCHITECTURE & CONSTRUCTION</strong> chuyên tư vấn, thiết kế 3D và thi công trọn gói khu vui chơi trẻ em trong nhà, Kids Cafe, trường mầm non tại Đà Nẵng và khu vực miền Trung.</p>
                    <p>• Phân khu chức năng thông minh: Nhà banh liên hoàn, cầu trượt, hồ hạt gỗ, khu hướng nghiệp, sàn nhún Trampoline.</p>
                    <p>• Vật tư an toàn, khung thép bọc xốp tiêu chuẩn, màu sắc tươi sáng và bảo hành bảo trì nhanh chóng.</p>
                `
            },
            {
                title: "Báo Giá Thi Công Nội Thất Phòng Khách & Tủ Bếp Cánh Kính Khung Nhôm",
                body: `
                    <p>L.E.V.O trực tiếp khảo sát, sản xuất và lắp đặt nội thất gia đình, căn hộ, showroom với độ hoàn thiện sắc nét:</p>
                    <p>• Tủ bếp MDF lõi xanh chống ẩm phủ Melamine/Acrylic và tủ bếp hợp kim nhôm cánh kính cường lực.</p>
                    <p>• Thiết kế tối ưu diện tích, kết hợp đồng bộ phụ kiện tủ bếp thông minh giúp căn bếp luôn gọn gàng, sang trọng.</p>
                `
            },
            {
                title: "Danh Mục Phụ Kiện Nội Thất Tủ Bếp Thông Minh & Vật Tư Nhôm",
                body: `
                    <p>Chúng tôi cung cấp sỉ & lẻ vật tư nhôm thanh định hình, nhôm nội thất và phụ kiện tủ bếp chính hãng:</p>
                    <p>• Phụ kiện bếp Inox 304: Giá bát nâng hạ, kệ xoong nồi, kệ dao thớt gia vị, thùng gạo mặt gương, mâm xoay góc.</p>
                    <p>• Phụ kiện bản lề giảm chấn, ray trượt âm, nhôm cánh kính tủ áo và nhôm nội thất đa dạng màu sắc.</p>
                `
            },
            {
                title: "Quy Trình Gia Công Cơ Khí Khung Thép & Bảng Hiệu Quảng Cáo",
                body: `
                    <p>Đội ngũ cơ khí & quảng cáo của L.E.V.O đáp ứng trọn gói nhu cầu xây dựng và nhận diện cửa hàng:</p>
                    <p>• Gia công khung kèo thép, mái kính, cầu thang, lan can, cửa cổng sắt mỹ thuật bền bỉ.</p>
                    <p>• Thi công bảng hiệu Alu, chữ nổi Mica, chữ Inox gắn đèn LED nổi bật, chống chịu thời tiết khắc nghiệt.</p>
                `
            }
        ];

        function openArticleModal(idx) {
            const item = articlesContent[idx];
            if (!item) return;
            document.getElementById("modalTitle").textContent = item.title;
            document.getElementById("modalBody").innerHTML = item.body;
            const modal = document.getElementById("infoModal");
            modal.classList.remove("hidden");
            modal.classList.add("flex");
        }

        function closeInfoModal() {
            const modal = document.getElementById("infoModal");
            modal.classList.add("hidden");
            modal.classList.remove("flex");
        }

        // Khởi chạy khi tải trang
        window.onload = function() {
            renderProducts();
            resetBannerTimer();
        };
    </script>
</body>
</html>

<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PHÚC KHANG THỊNH PHÁT - Giải Pháp Quà Tặng Doanh Nghiệp | phuckhangthinhphat.com</title>
    <meta name="description" content="CÔNG TY TNHH THƯƠNG MẠI & DỊCH VỤ PHÚC KHANG THỊNH PHÁT - Chuyên sản xuất và tư vấn giải pháp quà tặng cho các đối tác doanh nghiệp trong và ngoài nước. Hotline: 0938.613.943">
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Inter & Montserrat chuẩn giao diện Flatsome hiện đại -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Montserrat:wght@600;700;800&display=swap" rel="stylesheet">
    <!-- Font Awesome 6 -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        heading: ['Montserrat', 'sans-serif'],
                    },
                    colors: {
                        pk: {
                            gold: '#C69320',
                            goldLight: '#E5B84B',
                            goldDark: '#9A6F0B',
                            navy: '#1E2433',
                            navyDark: '#141824',
                            cream: '#FDFBF7',
                            sand: '#F5EFE6'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Cấu trúc CSS chuẩn Flatsome (Section -> Row -> Col -> Col-inner -> Box) để dễ dàng dựng lại trên UX Builder */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #F8F9FA;
            color: #222222;
            overflow-x: hidden;
        }

        .flatsome-container {
            max-width: 1230px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 15px;
            padding-right: 15px;
        }

        /* Section Title chuẩn Flatsome (section-title-normal / section-title-center) */
        .section-title-container {
            margin-bottom: 1.25rem;
        }
        .section-title {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #E5E7EB;
            padding-bottom: 10px;
            position: relative;
        }
        .section-title-main {
            font-family: 'Montserrat', sans-serif;
            font-weight: 800;
            text-transform: uppercase;
            color: #1E2433;
            position: relative;
            display: inline-flex;
            align-items: center;
            gap: 10px;
        }
        .section-title-main::after {
            content: '';
            position: absolute;
            bottom: -12px;
            left: 0;
            width: 100%;
            height: 3px;
            background: linear-gradient(90deg, #C69320, #E5B84B);
        }

        /* Box Category & Box Product chuẩn Flatsome */
        .box-category, .product-small.box {
            transition: all 0.25s ease;
        }
        .box-category:hover {
            transform: translateY(-4px);
            box-shadow: 0 10px 20px -5px rgba(198, 147, 32, 0.2);
            border-color: #C69320;
        }
        .product-small.box:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.08);
            border-color: #D1D5DB;
        }

        /* Nút liên hệ nổi (Zalo, Facebook, Gọi điện, Bản đồ) */
        @keyframes pulse-ring {
            0% { transform: scale(0.9); opacity: 0.8; }
            70% { transform: scale(1.35); opacity: 0; }
            100% { transform: scale(1.35); opacity: 0; }
        }
        .contact-pulse::before {
            content: '';
            position: absolute;
            inset: 0;
            border-radius: 9999px;
            background: inherit;
            animation: pulse-ring 2s infinite;
            z-index: -1;
        }

        /* Ẩn thanh cuộn ngang cho danh mục nhanh trên điện thoại */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="antialiased selection:bg-pk-gold selection:text-white">

    <!-- ==========================================
         HEADER WRAPPER (CHUẨN FLATSOME HEADER)
         Không hiển thị thanh công cụ UX Builder ở dòng trên
         ========================================== -->
    <header id="header" class="sticky top-0 z-40 bg-white shadow-sm">
        
        <!-- 1. TOP BAR (Chỉ hiển thị thông tin công ty, địa chỉ, SĐT khách hàng) -->
        <div id="top-bar" class="bg-pk-navy text-white text-xs py-2 border-b border-white/10">
            <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-2 font-medium truncate">
                    <span class="text-pk-goldLight"><i class="fa-solid fa-award"></i></span>
                    <span class="truncate">PHÚC KHANG THỊNH PHÁT – Sản Xuất & Tư Vấn Giải Pháp Quà Tặng Doanh Nghiệp Trong Và Ngoài Nước</span>
                </div>
                <div class="hidden md:flex items-center gap-5 text-gray-200">
                    <a href="https://maps.app.goo.gl/JNZ3N1iF34Te4HBW7" target="_blank" rel="noopener noreferrer" class="hover:text-pk-goldLight transition flex items-center gap-1.5">
                        <i class="fa-solid fa-location-dot text-pk-goldLight"></i>
                        <span>252 Tô Hiệu, P. Hòa Khánh, TP. Đà Nẵng</span>
                    </a>
                    <span class="text-white/20">|</span>
                    <a href="https://www.facebook.com/nguyen.thu.trang.854486/" target="_blank" rel="noopener noreferrer" class="hover:text-pk-goldLight transition flex items-center gap-1.5">
                        <i class="fa-brands fa-facebook text-blue-400"></i>
                        <span>Facebook Chính Thức</span>
                    </a>
                    <span class="text-white/20">|</span>
                    <a href="tel:0938613943" class="hover:text-pk-goldLight transition font-semibold text-pk-goldLight flex items-center gap-1.5">
                        <i class="fa-solid fa-phone-volume"></i>
                        <span>0938.613.943</span>
                    </a>
                </div>
            </div>
        </div>

        <!-- 2. HEADER MAIN (Logo PK trong ảnh + Tìm kiếm + Hotline + Zalo) -->
        <div id="masthead" class="py-2.5 md:py-4 bg-white">
            <div class="flatsome-container flex items-center justify-between gap-2 md:gap-6">
                
                <!-- Nút mở Menu trên Điện thoại -->
                <button onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-lg border border-gray-200 text-pk-navy hover:bg-gray-50 shrink-0">
                    <i class="fa-solid fa-bars text-lg"></i>
                </button>

                <!-- LOGO PHÚC KHANG THỊNH PHÁT (Vẽ chuẩn từng đường nét theo ảnh logo cận cảnh) -->
                <a href="#" onclick="filterCategory('all'); return false;" class="flex items-center gap-2 sm:gap-3 group min-w-0">
                    <div class="w-10 h-10 sm:w-12 sm:h-12 md:w-14 md:h-14 flex items-center justify-center shrink-0">
                        <!-- SVG Logo PK chuẩn theo ảnh chụp cận cảnh -->
                        <svg viewBox="0 0 130 110" class="w-full h-full drop-shadow-sm" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <defs>
                                <linearGradient id="pkGoldTop" x1="0%" y1="0%" x2="100%" y2="100%">
                                    <stop offset="0%" stop-color="#F2D15B"/>
                                    <stop offset="50%" stop-color="#D4A017"/>
                                    <stop offset="100%" stop-color="#9E7208"/>
                                </linearGradient>
                                <linearGradient id="pkGoldInner" x1="0%" y1="0%" x2="100%" y2="100%">
                                    <stop offset="0%" stop-color="#E8C247"/>
                                    <stop offset="60%" stop-color="#C59112"/>
                                    <stop offset="100%" stop-color="#926806"/>
                                </linearGradient>
                                <linearGradient id="pkDarkBase" x1="0%" y1="0%" x2="100%" y2="100%">
                                    <stop offset="0%" stop-color="#3E4454"/>
                                    <stop offset="55%" stop-color="#282D3A"/>
                                    <stop offset="100%" stop-color="#171A24"/>
                                </linearGradient>
                            </defs>
                            <!-- 1. Thanh chữ Γ vàng bên trái (vát chéo ở đỉnh phải và vát nhọn ở chân trái) -->
                            <path d="M18 33 H68 L79 48 H34 V78 L18 95 V33 Z" fill="url(#pkGoldInner)"/>
                            <!-- 2. Vòng cung chữ P vàng lớn bên ngoài ôm vòng sang phải và uốn xuống -->
                            <path d="M35 10 H80 C103 10 116 23 116 41 C116 59 103 72 80 72 H59 L40 83 V66 L55 56 H78 C91 56 99 50 99 41 C99 32 91 26 78 26 H47 L35 10 Z" fill="url(#pkGoldTop)"/>
                            <!-- 3. Khối đế màu xanh đen đậm bên dưới tạo chân chữ K -->
                            <path d="M44 82 L60 66 V84 H92 L82 68 L98 63 L116 96 H44 V82 Z" fill="url(#pkDarkBase)"/>
                        </svg>
                    </div>
                    <div class="flex flex-col min-w-0">
                        <span class="font-heading font-extrabold text-xs sm:text-base md:text-lg lg:text-xl tracking-tight text-pk-navy leading-tight truncate">
                            PHÚC KHANG THỊNH PHÁT
                        </span>
                        <span class="text-[9px] sm:text-xs font-semibold tracking-wider sm:tracking-widest uppercase text-pk-gold truncate">
                            GIẢI PHÁP QUÀ TẶNG DOANH NGHIỆP
                        </span>
                    </div>
                </a>

                <!-- Ô tìm kiếm sản phẩm (Desktop) -->
                <div class="hidden lg:flex flex-1 max-w-md mx-4">
                    <div class="relative w-full flex">
                        <input 
                            id="desktopSearchInput"
                            type="text" 
                            oninput="handleSearch(this.value)"
                            placeholder="Tìm kiếm: Bình giữ nhiệt, ly sứ, áo mưa, quà Tết..." 
                            class="w-full pl-4 pr-10 py-2.5 text-sm bg-gray-50 border border-gray-300 rounded-l-lg focus:outline-none focus:border-pk-gold focus:bg-white transition"
                        >
                        <button onclick="handleSearch(document.getElementById('desktopSearchInput').value)" class="px-5 bg-pk-gold hover:bg-pk-goldDark text-white rounded-r-lg transition flex items-center justify-center">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </button>
                    </div>
                </div>

                <!-- Cụm nút Liên hệ nhanh trên Header -->
                <div class="flex items-center gap-2 sm:gap-3">
                    <a href="tel:0938613943" class="hidden sm:flex items-center gap-2.5 px-3.5 py-2 rounded-lg bg-amber-50 border border-amber-200 hover:bg-amber-100 transition">
                        <div class="w-8 h-8 rounded-full bg-pk-gold text-white flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-phone text-xs"></i>
                        </div>
                        <div class="leading-tight">
                            <div class="text-[10px] uppercase text-gray-500 font-semibold">Hotline / Zalo 24/7</div>
                            <div class="text-sm font-extrabold text-pk-navy">0938.613.943</div>
                        </div>
                    </a>

                    <a href="https://zalo.me/0938613943" target="_blank" rel="noopener noreferrer" class="px-2.5 sm:px-3.5 py-2 sm:py-2.5 rounded-lg bg-blue-600 hover:bg-blue-700 text-white font-semibold text-xs sm:text-sm flex items-center gap-1.5 shadow-sm transition shrink-0">
                        <i class="fa-solid fa-comment-dots"></i>
                        <span>Chat Zalo</span>
                    </a>
                </div>
            </div>

            <!-- Ô tìm kiếm trên Điện thoại -->
            <div class="flatsome-container mt-2.5 lg:hidden">
                <div class="relative flex w-full">
                    <input 
                        id="mobileSearchInput"
                        type="text" 
                        oninput="handleSearch(this.value)"
                        placeholder="Tìm sản phẩm quà tặng in logo..." 
                        class="w-full pl-3.5 pr-10 py-2 text-sm bg-gray-50 border border-gray-300 rounded-l-lg focus:outline-none focus:border-pk-gold"
                    >
                    <button onclick="handleSearch(document.getElementById('mobileSearchInput').value)" class="px-4 bg-pk-gold text-white rounded-r-lg">
                        <i class="fa-solid fa-magnifying-glass text-sm"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- 3. HEADER BOTTOM / NAVIGATION BAR (Menu Danh mục chuẩn Quà Tặng Quang Vũ + Flatsome) -->
        <div id="wide-nav" class="hidden lg:block bg-pk-navy text-white border-t border-white/10">
            <div class="flatsome-container flex items-center justify-between">
                
                <!-- Nút Mega Dropdown Danh Mục Sản Phẩm -->
                <div class="relative group">
                    <button class="bg-pk-gold hover:bg-pk-goldDark text-white font-heading font-bold text-sm uppercase px-5 py-3.5 flex items-center gap-3 tracking-wide transition">
                        <i class="fa-solid fa-bars-staggered"></i>
                        <span>DANH MỤC SẢN PHẨM</span>
                        <i class="fa-solid fa-chevron-down text-xs ml-2"></i>
                    </button>

                    <!-- Menu xổ xuống khi di chuột trên máy tính -->
                    <div class="absolute left-0 top-full w-72 bg-white text-gray-800 shadow-xl rounded-b-xl border border-gray-200 py-2 hidden group-hover:block z-50">
                        <a href="#danh-muc-san-pham" onclick="filterCategory('binh-giu-nhiet')" class="flex items-center justify-between px-4 py-2.5 hover:bg-amber-50 hover:text-pk-goldDark text-sm font-medium border-b border-gray-100">
                            <span class="flex items-center gap-2.5"><i class="fa-solid fa-bottle-water text-pk-gold w-4 text-center"></i> Bình Giữ Nhiệt & Bình Thủy Tinh</span>
                            <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
                        </a>
                        <a href="#danh-muc-san-pham" onclick="filterCategory('gom-su')" class="flex items-center justify-between px-4 py-2.5 hover:bg-amber-50 hover:text-pk-goldDark text-sm font-medium border-b border-gray-100">
                            <span class="flex items-center gap-2.5"><i class="fa-solid fa-mug-hot text-pk-gold w-4 text-center"></i> Ly Sứ & Ấm Chén In Logo</span>
                            <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
                        </a>
                        <a href="#danh-muc-san-pham" onclick="filterCategory('quang-cao')" class="flex items-center justify-between px-4 py-2.5 hover:bg-amber-50 hover:text-pk-goldDark text-sm font-medium border-b border-gray-100">
                            <span class="flex items-center gap-2.5"><i class="fa-solid fa-umbrella text-pk-gold w-4 text-center"></i> Ô Dù, Áo Mưa & Mũ Bảo Hiểm</span>
                            <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
                        </a>
                        <a href="#danh-muc-san-pham" onclick="filterCategory('van-phong')" class="flex items-center justify-between px-4 py-2.5 hover:bg-amber-50 hover:text-pk-goldDark text-sm font-medium border-b border-gray-100">
                            <span class="flex items-center gap-2.5"><i class="fa-solid fa-book-open text-pk-gold w-4 text-center"></i> Sổ Tay Da, Bút Ký & Balo</span>
                            <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
                        </a>
                        <a href="#danh-muc-san-pham" onclick="filterCategory('cong-nghe')" class="flex items-center justify-between px-4 py-2.5 hover:bg-amber-50 hover:text-pk-goldDark text-sm font-medium border-b border-gray-100">
                            <span class="flex items-center gap-2.5"><i class="fa-solid fa-battery-full text-pk-gold w-4 text-center"></i> Sạc Dự Phòng, Đồng Hồ, Quạt</span>
                            <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
                        </a>
                        <a href="#danh-muc-san-pham" onclick="filterCategory('mua-vu')" class="flex items-center justify-between px-4 py-2.5 hover:bg-amber-50 hover:text-pk-goldDark text-sm font-medium">
                            <span class="flex items-center gap-2.5"><i class="fa-solid fa-gift text-pk-gold w-4 text-center"></i> Quà Tết & Bánh Trung Thu</span>
                            <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
                        </a>
                    </div>
                </div>

                <!-- Các liên kết Menu ngang -->
                <nav class="flex items-center space-x-1 xl:space-x-2 text-xs xl:text-sm font-semibold uppercase tracking-wide">
                    <a href="#" onclick="filterCategory('all'); return false;" class="px-3 py-3.5 text-pk-goldLight hover:text-white transition">Trang chủ</a>
                    <a href="#danh-muc-visual" class="px-3 py-3.5 hover:text-pk-goldLight transition">Danh mục quà tặng</a>
                    <a href="#sec-binh-giu-nhiet" class="px-3 py-3.5 hover:text-pk-goldLight transition">Bình giữ nhiệt</a>
                    <a href="#sec-gom-su" class="px-3 py-3.5 hover:text-pk-goldLight transition">Quà tặng gốm sứ</a>
                    <a href="#sec-quang-cao" class="px-3 py-3.5 hover:text-pk-goldLight transition">Quà tặng quảng cáo</a>
                    <a href="#sec-van-phong" class="px-3 py-3.5 hover:text-pk-goldLight transition">Văn phòng & Công nghệ</a>
                    <a href="#sec-mua-vu" class="px-3 py-3.5 hover:text-pk-goldLight transition">Quà Tết & Trung Thu</a>
                    <a href="#lien-he-footer" class="px-3 py-3.5 hover:text-pk-goldLight transition">Liên hệ</a>
                </nav>
            </div>
        </div>
    </header>

    <!-- ==========================================
         MENU TRƯỢT TRÊN ĐIỆN THOẠI (MOBILE DRAWER)
         ========================================== -->
    <div id="mobileMenuBackdrop" onclick="toggleMobileMenu()" class="fixed inset-0 bg-black/60 z-50 hidden"></div>
    <aside id="mobileMenuDrawer" class="fixed top-0 left-0 bottom-0 w-80 max-w-[85vw] bg-white z-50 transform -translate-x-full transition-transform duration-300 flex flex-col shadow-2xl">
        <div class="p-4 bg-pk-navy text-white flex items-center justify-between">
            <div class="font-heading font-bold text-sm text-pk-goldLight">PHÚC KHANG THỊNH PHÁT</div>
            <button onclick="toggleMobileMenu()" class="w-8 h-8 rounded-lg bg-white/10 flex items-center justify-center text-white">
                <i class="fa-solid fa-xmark"></i>
            </button>
        </div>
        <div class="p-4 overflow-y-auto flex-1 space-y-4">
            <div class="text-xs font-bold uppercase text-gray-400 tracking-wider">Danh mục sản phẩm</div>
            <div class="grid grid-cols-2 gap-2 text-xs font-semibold text-pk-navy">
                <button onclick="filterCategory('all'); toggleMobileMenu();" class="p-2.5 rounded-lg bg-amber-50 border border-amber-200 text-left flex items-center gap-2 col-span-2">
                    <i class="fa-solid fa-border-all text-pk-gold"></i> Tất cả sản phẩm
                </button>
                <button onclick="filterCategory('binh-giu-nhiet'); toggleMobileMenu();" class="p-2.5 rounded-lg bg-gray-50 border border-gray-200 text-left">Bình giữ nhiệt</button>
                <button onclick="filterCategory('gom-su'); toggleMobileMenu();" class="p-2.5 rounded-lg bg-gray-50 border border-gray-200 text-left">Ly sứ & Ấm chén</button>
                <button onclick="filterCategory('quang-cao'); toggleMobileMenu();" class="p-2.5 rounded-lg bg-gray-50 border border-gray-200 text-left">Ô dù & Áo mưa</button>
                <button onclick="filterCategory('van-phong'); toggleMobileMenu();" class="p-2.5 rounded-lg bg-gray-50 border border-gray-200 text-left">Sổ da & Bút ký</button>
                <button onclick="filterCategory('cong-nghe'); toggleMobileMenu();" class="p-2.5 rounded-lg bg-gray-50 border border-gray-200 text-left">Balo & Công nghệ</button>
                <button onclick="filterCategory('mua-vu'); toggleMobileMenu();" class="p-2.5 rounded-lg bg-gray-50 border border-gray-200 text-left">Quà Tết & Trung Thu</button>
            </div>

            <div class="border-t border-gray-100 pt-4 space-y-2.5 text-sm">
                <div class="text-xs font-bold uppercase text-gray-400 tracking-wider">Thông tin liên hệ</div>
                <a href="tel:0938613943" class="flex items-center gap-2.5 text-pk-navy font-semibold">
                    <i class="fa-solid fa-phone text-pk-gold w-5"></i> 0938.613.943
                </a>
                <a href="https://zalo.me/0938613943" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2.5 text-blue-600 font-semibold">
                    <i class="fa-solid fa-comment-dots w-5"></i> Chat Zalo: 0938.613.943
                </a>
                <a href="https://www.facebook.com/nguyen.thu.trang.854486/" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2.5 text-blue-700 font-semibold">
                    <i class="fa-brands fa-facebook w-5"></i> Facebook Thu Trang
                </a>
                <a href="https://maps.app.goo.gl/JNZ3N1iF34Te4HBW7" target="_blank" rel="noopener noreferrer" class="flex items-start gap-2.5 text-gray-600 text-xs leading-relaxed">
                    <i class="fa-solid fa-location-dot text-red-500 w-5 mt-0.5"></i> 252 Tô Hiệu, Phường Hòa Khánh, Tp. Đà Nẵng
                </a>
            </div>
        </div>
    </aside>

    <!-- ==========================================
         MAIN CONTENT (CẤU TRÚC SECTION FLATSOME)
         ========================================== -->
    <main id="main">

        <!-- SECTION 1: BANNER CHÍNH TÁI HIỆN CHÍNH XÁC BỐ CỤC ẢNH GỐC -->
        <section class="section py-4 md:py-6 bg-gradient-to-b from-pk-sand/70 to-white">
            <div class="flatsome-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 items-stretch">
                    
                    <!-- Khối Trái (5 cột): Thương hiệu Phúc Khang Thịnh Phát + 4 Giá trị cốt lõi + SĐT/Địa chỉ đúng như ảnh -->
                    <div class="lg:col-span-5 bg-gradient-to-br from-[#FBF8F1] via-[#F5EFE2] to-[#EFE5D2] rounded-2xl p-5 sm:p-6 border border-amber-200/70 shadow-sm flex flex-col justify-between relative overflow-hidden">
                        <!-- Họa tiết sóng vàng góc trái trên giống trong ảnh -->
                        <div class="absolute -top-10 -left-10 w-40 h-40 rounded-full border-[14px] border-pk-gold/15 pointer-events-none"></div>

                        <div class="text-center relative z-10">
                            <!-- Logo PK Lớn chính giữa chuẩn theo ảnh logo cận cảnh -->
                            <div class="w-28 h-24 mx-auto mb-1.5 flex items-center justify-center">
                                <svg viewBox="0 0 130 110" class="w-full h-full drop-shadow-sm" fill="none" xmlns="http://www.w3.org/2000/svg">
                                    <path d="M18 33 H68 L79 48 H34 V78 L18 95 V33 Z" fill="url(#pkGoldInner)"/>
                                    <path d="M35 10 H80 C103 10 116 23 116 41 C116 59 103 72 80 72 H59 L40 83 V66 L55 56 H78 C91 56 99 50 99 41 C99 32 91 26 78 26 H47 L35 10 Z" fill="url(#pkGoldTop)"/>
                                    <path d="M44 82 L60 66 V84 H92 L82 68 L98 63 L116 96 H44 V82 Z" fill="url(#pkDarkBase)"/>
                                </svg>
                            </div>
                            <h1 class="font-heading font-extrabold text-xl sm:text-2xl text-pk-navy tracking-tight">
                                PHÚC KHANG THỊNH PHÁT
                            </h1>
                            <div class="flex items-center justify-center gap-2 my-1.5">
                                <span class="h-[1px] w-8 bg-pk-gold"></span>
                                <p class="text-xs sm:text-sm font-bold uppercase tracking-widest text-pk-goldDark">
                                    GIẢI PHÁP QUÀ TẶNG DOANH NGHIỆP
                                </p>
                                <span class="h-[1px] w-8 bg-pk-gold"></span>
                            </div>
                            <p class="text-xs text-gray-700 font-medium max-w-md mx-auto mt-1 leading-relaxed">
                                Chuyên sản xuất – tư vấn giải pháp quà tặng cho các đối tác doanh nghiệp trong và ngoài nước
                            </p>
                        </div>

                        <!-- 4 Icon cam kết vàng kim y hệt trong ảnh -->
                        <div class="grid grid-cols-4 gap-2 my-5 pt-3 border-t border-amber-300/50 text-center">
                            <div class="px-1 border-r border-amber-300/60">
                                <div class="text-pk-gold text-xl sm:text-2xl mb-1.5"><i class="fa-solid fa-gift"></i></div>
                                <div class="text-[10px] sm:text-[11px] font-bold uppercase text-pk-navy leading-tight">Quà tặng<br>doanh nghiệp</div>
                            </div>
                            <div class="px-1 border-r border-amber-300/60">
                                <div class="text-pk-gold text-xl sm:text-2xl mb-1.5"><i class="fa-solid fa-shield-halved"></i></div>
                                <div class="text-[10px] sm:text-[11px] font-bold uppercase text-pk-navy leading-tight">Chất lượng<br>uy tín</div>
                            </div>
                            <div class="px-1 border-r border-amber-300/60">
                                <div class="text-pk-gold text-xl sm:text-2xl mb-1.5"><i class="fa-regular fa-lightbulb"></i></div>
                                <div class="text-[10px] sm:text-[11px] font-bold uppercase text-pk-navy leading-tight">Thiết kế<br>theo yêu cầu</div>
                            </div>
                            <div class="px-1">
                                <div class="text-pk-gold text-xl sm:text-2xl mb-1.5"><i class="fa-regular fa-handshake"></i></div>
                                <div class="text-[10px] sm:text-[11px] font-bold uppercase text-pk-navy leading-tight">Gắn kết<br>thương hiệu</div>
                            </div>
                        </div>

                        <!-- Thanh viên thuốc SĐT + Địa chỉ giống hệt ảnh -->
                        <div class="bg-white/90 rounded-xl p-3 border border-amber-200 flex flex-col sm:flex-row items-center justify-between gap-2 shadow-sm">
                            <a href="tel:0938613943" class="flex items-center gap-2 font-heading font-extrabold text-base sm:text-lg text-pk-navy hover:text-pk-gold transition shrink-0">
                                <span class="w-7 h-7 rounded-full bg-pk-gold text-white flex items-center justify-center text-xs">
                                    <i class="fa-solid fa-phone"></i>
                                </span>
                                <span>0938 613 943</span>
                            </a>
                            <span class="hidden sm:inline text-gray-300">|</span>
                            <a href="https://maps.app.goo.gl/JNZ3N1iF34Te4HBW7" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2 text-xs text-gray-700 hover:text-pk-goldDark font-medium text-center sm:text-left">
                                <span class="w-6 h-6 rounded-full bg-pk-gold/20 text-pk-goldDark flex items-center justify-center shrink-0">
                                    <i class="fa-solid fa-location-dot"></i>
                                </span>
                                <span>252 Tô Hiệu, Phường Hòa Khánh, Thành phố Đà Nẵng</span>
                            </a>
                        </div>
                    </div>

                    <!-- Khối Phải (7 cột): 2 Banner lớn BÁNH TRUNG THU & QUÀ TẾT DOANH NGHIỆP giống ảnh -->
                    <div class="lg:col-span-7 grid grid-cols-1 sm:grid-cols-2 gap-4">
                        
                        <!-- Card 1: BÁNH TRUNG THU (Ảnh thực tế) -->
                        <div onclick="filterCategory('mua-vu')" class="cursor-pointer group rounded-2xl bg-gradient-to-b from-[#F9F3E3] to-[#EAD9B5] p-5 border border-amber-200/80 shadow-sm flex flex-col justify-between relative overflow-hidden">
                            <div>
                                <h2 class="font-heading font-extrabold text-lg sm:text-xl text-amber-900 uppercase">BÁNH TRUNG THU</h2>
                                <p class="text-xs text-amber-800/90 mt-0.5 leading-relaxed">
                                    Hương vị truyền thống<br>Chất lượng tinh tuyển
                                </p>
                            </div>

                            <!-- Ảnh thực tế Hộp Bánh Trung Thu Doanh Nghiệp -->
                            <div class="my-3 h-44 sm:h-48 rounded-xl overflow-hidden bg-white shadow-inner border border-amber-200/60">
                                <img 
                                    src="https://commons.wikimedia.org/wiki/Special:FilePath/Mooncake.jpg?width=700" 
                                    alt="Hộp Bánh Trung Thu Quà Tặng Doanh Nghiệp" 
                                    onerror="this.onerror=null;this.src='https://placehold.co/600x450/0F4C81/F3E5AB?text=Banh+Trung+Thu+PK';"
                                    class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                                >
                            </div>

                            <div class="text-xs font-bold text-amber-900 flex items-center justify-between pt-2 border-t border-amber-800/15">
                                <span>In logo hộp quà theo yêu cầu</span>
                                <span class="group-hover:translate-x-1 transition"><i class="fa-solid fa-arrow-right"></i></span>
                            </div>
                        </div>

                        <!-- Card 2: QUÀ TẾT DOANH NGHIỆP (Ảnh thực tế) -->
                        <div onclick="filterCategory('mua-vu')" class="cursor-pointer group rounded-2xl bg-gradient-to-b from-[#FDF4EC] to-[#F7DEC8] p-5 border border-red-200/80 shadow-sm flex flex-col justify-between relative overflow-hidden">
                            <div>
                                <h2 class="font-heading font-extrabold text-lg sm:text-xl text-red-800 uppercase">QUÀ TẾT DOANH NGHIỆP</h2>
                                <p class="text-xs text-red-900/80 mt-0.5 leading-relaxed">
                                    Tinh tế trong từng món quà<br>Gắn kết tri ân, đón xuân an khang
                                </p>
                            </div>

                            <!-- Ảnh thực tế Set Quà Tết Doanh Nghiệp -->
                            <div class="my-3 h-44 sm:h-48 rounded-xl overflow-hidden bg-white shadow-inner border border-red-200/60">
                                <img 
                                    src="https://commons.wikimedia.org/wiki/Special:FilePath/Hamper.jpg?width=700" 
                                    alt="Set Quà Tết Doanh Nghiệp Cao Cấp" 
                                    onerror="this.onerror=null;this.src='https://placehold.co/600x450/991B1B/FDE047?text=Qua+Tet+Doanh+Nghiep';"
                                    class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                                >
                            </div>

                            <div class="text-xs font-bold text-red-800 flex items-center justify-between pt-2 border-t border-red-800/15">
                                <span>Set quà Tết thiết kế riêng</span>
                                <span class="group-hover:translate-x-1 transition"><i class="fa-solid fa-arrow-right"></i></span>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
        </section>

        <!-- ==========================================
             SECTION 2: DANH MỤC SẢN PHẨM (TỐI ƯU ĐẸP TRÊN CẢ MÁY TÍNH & ĐIỆN THOẠI)
             Đầy đủ 13 danh mục trong ảnh + danh mục từ Quà Tặng Quang Vũ
             Không có nhãn dán (badge/sticker)
             ========================================== -->
        <section id="danh-muc-visual" class="section py-6 md:py-8 bg-white border-y border-gray-100">
            <div class="flatsome-container">
                
                <div class="section-title-container">
                    <div class="section-title">
                        <h2 class="section-title-main text-base sm:text-lg md:text-xl">
                            <i class="fa-solid fa-layer-group text-pk-gold"></i>
                            <span>DANH MỤC QUÀ TẶNG DOANH NGHIỆP</span>
                        </h2>
                        <button onclick="filterCategory('all')" class="text-xs sm:text-sm font-semibold text-pk-goldDark hover:underline flex items-center gap-1">
                            <span>Xem tất cả</span>
                            <i class="fa-solid fa-angle-right text-xs"></i>
                        </button>
                    </div>
                </div>

                <!-- Grid danh mục: Điện thoại 3 cột gọn đẹp, Tablet 4 cột, Máy tính 7 cột giống đúng bố cục 2 hàng trên ảnh -->
                <div id="categoryGridContainer" class="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-5 lg:grid-cols-7 gap-2 sm:gap-3">
                    <!-- Được render tự động bằng JS từ mảng 14 danh mục chuẩn trong ảnh & web mẫu -->
                </div>

            </div>
        </section>

        <!-- Thanh thông báo khi đang lọc tìm kiếm / danh mục -->
        <div id="filterStatusBar" class="hidden bg-amber-50 border-b border-amber-200 py-3">
            <div class="flatsome-container flex items-center justify-between">
                <div class="text-sm font-medium text-pk-navy">
                    Đang hiển thị: <span id="filterStatusText" class="font-bold text-pk-goldDark">Tất cả sản phẩm</span>
                </div>
                <button onclick="filterCategory('all')" class="px-3 py-1 rounded-lg bg-white border border-amber-300 text-xs font-semibold text-pk-navy hover:bg-amber-100">
                    <i class="fa-solid fa-rotate-left mr-1"></i> Bỏ lọc
                </button>
            </div>
        </div>

        <!-- ==========================================
             CÁC SECTION SẢN PHẨM THEO NHÓM DANH MỤC (CHUẨN FLATSOME)
             - Trên điện thoại: Chia thành 2 cột (grid-cols-2)
             - Trên máy tính: Chia thành 4 cột (lg:grid-cols-4)
             - Hoàn toàn KHÔNG để nhãn dán (Sale/Hot/New) ở trang chủ
             ========================================== -->
        <div id="danh-muc-san-pham" class="space-y-8 py-6 md:py-10">
            <!-- Các Section sản phẩm được render tự động từ dữ liệu bên dưới để code gọn, dễ copy sang UX Builder -->
        </div>

        <!-- ==========================================
             SECTION QUY TRÌNH ĐẶT QUÀ TẶNG (CHUẨN QUÀ TẶNG QUANG VŨ)
             ========================================== -->
        <section class="section py-8 md:py-12 bg-white border-t border-gray-200">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title">
                        <h2 class="section-title-main text-base sm:text-lg md:text-xl">
                            <i class="fa-solid fa-clipboard-check text-pk-gold"></i>
                            <span>QUY TRÌNH ĐẶT QUÀ TẶNG IN LOGO TẠI PHÚC KHANG THỊNH PHÁT</span>
                        </h2>
                    </div>
                </div>

                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <div class="p-4 sm:p-5 rounded-xl bg-pk-cream border border-amber-200/80">
                        <div class="w-10 h-10 rounded-lg bg-pk-gold text-white font-heading font-bold flex items-center justify-center mb-3">01</div>
                        <h3 class="font-heading font-bold text-sm sm:text-base text-pk-navy mb-1">Tư Vấn & Chọn Mẫu</h3>
                        <p class="text-xs text-gray-600 leading-relaxed">Tiếp nhận nhu cầu, ngân sách và gợi ý mẫu quà tặng doanh nghiệp tối ưu nhất.</p>
                    </div>
                    <div class="p-4 sm:p-5 rounded-xl bg-pk-cream border border-amber-200/80">
                        <div class="w-10 h-10 rounded-lg bg-pk-gold text-white font-heading font-bold flex items-center justify-center mb-3">02</div>
                        <h3 class="font-heading font-bold text-sm sm:text-base text-pk-navy mb-1">Thiết Kế Demo Miễn Phí</h3>
                        <p class="text-xs text-gray-600 leading-relaxed">Lên maket in/khắc logo thương hiệu lên sản phẩm để khách hàng duyệt trước.</p>
                    </div>
                    <div class="p-4 sm:p-5 rounded-xl bg-pk-cream border border-amber-200/80">
                        <div class="w-10 h-10 rounded-lg bg-pk-gold text-white font-heading font-bold flex items-center justify-center mb-3">03</div>
                        <h3 class="font-heading font-bold text-sm sm:text-base text-pk-navy mb-1">Sản Xuất & In Ấn</h3>
                        <p class="text-xs text-gray-600 leading-relaxed">Gia công in ấn sắc nét, kiểm tra chất lượng nghiêm ngặt từng sản phẩm.</p>
                    </div>
                    <div class="p-4 sm:p-5 rounded-xl bg-pk-cream border border-amber-200/80">
                        <div class="w-10 h-10 rounded-lg bg-pk-gold text-white font-heading font-bold flex items-center justify-center mb-3">04</div>
                        <h3 class="font-heading font-bold text-sm sm:text-base text-pk-navy mb-1">Giao Hàng Đúng Hẹn</h3>
                        <p class="text-xs text-gray-600 leading-relaxed">Bàn giao tận nơi tại Đà Nẵng và vận chuyển toàn quốc, đầy đủ hóa đơn VAT.</p>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- ==========================================
         FOOTER (ĐẦY ĐỦ THÔNG TIN CÔNG TY, BẢN ĐỒ, FACEBOOK, SĐT)
         ========================================== -->
    <footer id="lien-he-footer" class="bg-pk-navy text-gray-300 pt-10 pb-20 md:pb-10 border-t-4 border-pk-gold">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-white/10">
                
                <!-- Cột 1: Thông tin công ty (5 cột) -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center gap-3">
                        <div class="w-12 h-12 bg-white rounded-lg p-1.5 flex items-center justify-center shrink-0">
                            <svg viewBox="0 0 130 110" class="w-full h-full" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path d="M18 33 H68 L79 48 H34 V78 L18 95 V33 Z" fill="url(#pkGoldInner)"/>
                                <path d="M35 10 H80 C103 10 116 23 116 41 C116 59 103 72 80 72 H59 L40 83 V66 L55 56 H78 C91 56 99 50 99 41 C99 32 91 26 78 26 H47 L35 10 Z" fill="url(#pkGoldTop)"/>
                                <path d="M44 82 L60 66 V84 H92 L82 68 L98 63 L116 96 H44 V82 Z" fill="url(#pkDarkBase)"/>
                            </svg>
                        </div>
                        <div>
                            <div class="text-xs text-pk-goldLight font-semibold uppercase">Giải Pháp Quà Tặng Doanh Nghiệp</div>
                            <h3 class="font-heading font-extrabold text-white text-sm sm:text-base leading-snug">
                                CÔNG TY TNHH THƯƠNG MẠI & DỊCH VỤ PHÚC KHANG THỊNH PHÁT
                            </h3>
                        </div>
                    </div>

                    <p class="text-xs sm:text-sm text-gray-300 leading-relaxed pt-1">
                        Đơn vị uy tín chuyên <strong>sản xuất và tư vấn giải pháp quà tặng</strong> thương hiệu cho các đối tác doanh nghiệp trong và ngoài nước.
                    </p>

                    <ul class="space-y-2.5 text-sm pt-1">
                        <li class="flex items-start gap-2.5">
                            <i class="fa-solid fa-location-dot text-pk-goldLight mt-1 w-4 text-center"></i>
                            <span><strong>Địa chỉ:</strong> 252 Tô Hiệu, Phường Hòa Khánh, Tp. Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone text-pk-goldLight w-4 text-center"></i>
                            <span><strong>Hotline / Zalo:</strong> <a href="tel:0938613943" class="text-pk-goldLight font-bold hover:underline">0938.613.943</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-globe text-pk-goldLight w-4 text-center"></i>
                            <span><strong>Website:</strong> <a href="https://phuckhangthinhphat.com" class="hover:text-white">phuckhangthinhphat.com</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-brands fa-facebook text-pk-goldLight w-4 text-center"></i>
                            <span><strong>Facebook:</strong> <a href="https://www.facebook.com/nguyen.thu.trang.854486/" target="_blank" rel="noopener noreferrer" class="hover:text-white underline">facebook.com/nguyen.thu.trang.854486</a></span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm chính (3 cột) -->
                <div class="lg:col-span-3 space-y-3">
                    <h4 class="font-heading font-bold text-white uppercase text-sm tracking-wider border-l-4 border-pk-gold pl-2.5">
                        Danh Mục Quà Tặng
                    </h4>
                    <ul class="grid grid-cols-2 lg:grid-cols-1 gap-2 text-sm">
                        <li><a href="#sec-binh-giu-nhiet" class="hover:text-pk-goldLight transition"><i class="fa-solid fa-angle-right text-xs mr-1.5 text-pk-gold"></i>Bình giữ nhiệt in logo</a></li>
                        <li><a href="#sec-gom-su" class="hover:text-pk-goldLight transition"><i class="fa-solid fa-angle-right text-xs mr-1.5 text-pk-gold"></i>Ly sứ & Ấm chén Bát Tràng</a></li>
                        <li><a href="#sec-quang-cao" class="hover:text-pk-goldLight transition"><i class="fa-solid fa-angle-right text-xs mr-1.5 text-pk-gold"></i>Ô dù, Áo mưa, Mũ bảo hiểm</a></li>
                        <li><a href="#sec-van-phong" class="hover:text-pk-goldLight transition"><i class="fa-solid fa-angle-right text-xs mr-1.5 text-pk-gold"></i>Sổ tay bìa da & Bút kim loại</a></li>
                        <li><a href="#sec-van-phong" class="hover:text-pk-goldLight transition"><i class="fa-solid fa-angle-right text-xs mr-1.5 text-pk-gold"></i>Balo, Sạc dự phòng, Đồng hồ</a></li>
                        <li><a href="#sec-mua-vu" class="hover:text-pk-goldLight transition"><i class="fa-solid fa-angle-right text-xs mr-1.5 text-pk-gold"></i>Bánh Trung Thu & Quà Tết</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Kết nối Google Maps & Mạng xã hội (4 cột) -->
                <div class="lg:col-span-4 space-y-3">
                    <h4 class="font-heading font-bold text-white uppercase text-sm tracking-wider border-l-4 border-pk-gold pl-2.5">
                        Bản Đồ & Kết Nối Nhanh
                    </h4>
                    <div class="bg-white/5 rounded-xl p-4 border border-white/10 space-y-3">
                        <div class="flex items-start gap-3">
                            <div class="w-10 h-10 rounded-lg bg-red-500/20 text-red-400 flex items-center justify-center shrink-0 text-lg">
                                <i class="fa-solid fa-map-location-dot"></i>
                            </div>
                            <div class="text-xs leading-relaxed">
                                <div class="font-bold text-white text-sm">Văn phòng Đà Nẵng</div>
                                <div>252 Tô Hiệu, Phường Hòa Khánh, Tp. Đà Nẵng</div>
                            </div>
                        </div>
                        <div class="grid grid-cols-2 gap-2 pt-1">
                            <a href="https://maps.app.goo.gl/JNZ3N1iF34Te4HBW7" target="_blank" rel="noopener noreferrer" class="py-2 px-3 rounded-lg bg-pk-gold hover:bg-pk-goldDark text-white font-semibold text-xs text-center flex items-center justify-center gap-1.5 transition">
                                <i class="fa-solid fa-diamond-turn-right"></i> Chỉ đường Map
                            </a>
                            <a href="https://www.facebook.com/nguyen.thu.trang.854486/" target="_blank" rel="noopener noreferrer" class="py-2 px-3 rounded-lg bg-blue-600 hover:bg-blue-700 text-white font-semibold text-xs text-center flex items-center justify-center gap-1.5 transition">
                                <i class="fa-brands fa-facebook-f"></i> Trang Facebook
                            </a>
                        </div>
                    </div>
                </div>

            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between text-xs text-gray-400 gap-2">
                <div>© Bản quyền thuộc về <strong class="text-white">phuckhangthinhphat.com</strong> – Công ty TNHH TM & DV Phúc Khang Thịnh Phát.</div>
                <div>Giao diện chuẩn Flatsome UX Builder</div>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CỤM NÚT LIÊN HỆ NỔI (ZALO, FACEBOOK, BẢN ĐỒ, GỌI ĐIỆN)
         ========================================== -->
    <div class="fixed right-3 sm:right-5 bottom-4 sm:bottom-6 z-40 flex flex-col items-end gap-3">
        
        <!-- Nút Google Maps -->
        <a href="https://maps.app.goo.gl/JNZ3N1iF34Te4HBW7" target="_blank" rel="noopener noreferrer" title="Xem bản đồ 252 Tô Hiệu" class="group flex items-center gap-2 bg-white hover:bg-red-50 text-gray-800 p-1.5 pr-3 rounded-full shadow-lg border border-gray-200 transition">
            <span class="w-9 h-9 rounded-full bg-red-500 text-white flex items-center justify-center text-base">
                <i class="fa-solid fa-location-dot"></i>
            </span>
            <span class="text-xs font-bold hidden sm:inline">Chỉ đường</span>
        </a>

        <!-- Nút Facebook -->
        <a href="https://www.facebook.com/nguyen.thu.trang.854486/" target="_blank" rel="noopener noreferrer" title="Chat Facebook" class="group flex items-center gap-2 bg-white hover:bg-blue-50 text-gray-800 p-1.5 pr-3 rounded-full shadow-lg border border-gray-200 transition">
            <span class="w-9 h-9 rounded-full bg-[#1877F2] text-white flex items-center justify-center text-base contact-pulse relative">
                <i class="fa-brands fa-facebook-f"></i>
            </span>
            <span class="text-xs font-bold text-[#1877F2] hidden sm:inline">Facebook</span>
        </a>

        <!-- Nút Zalo -->
        <a href="https://zalo.me/0938613943" target="_blank" rel="noopener noreferrer" title="Chat Zalo 0938.613.943" class="group flex items-center gap-2 bg-white hover:bg-blue-50 text-gray-800 p-1.5 pr-3 rounded-full shadow-lg border border-gray-200 transition">
            <span class="w-9 h-9 rounded-full bg-[#0068FF] text-white flex items-center justify-center font-heading font-extrabold text-xs contact-pulse relative">
                Zalo
            </span>
            <span class="text-xs font-bold text-[#0068FF] hidden sm:inline">0938.613.943</span>
        </a>

        <!-- Nút Gọi Hotline -->
        <a href="tel:0938613943" title="Gọi ngay 0938.613.943" class="flex items-center gap-2 bg-pk-gold hover:bg-pk-goldDark text-white p-1.5 pr-4 rounded-full shadow-xl transition">
            <span class="w-9 h-9 rounded-full bg-white text-pk-goldDark flex items-center justify-center text-base contact-pulse relative">
                <i class="fa-solid fa-phone-volume"></i>
            </span>
            <div class="leading-tight">
                <div class="text-[10px] uppercase opacity-90">Gọi báo giá</div>
                <div class="text-xs sm:text-sm font-extrabold">0938.613.943</div>
            </div>
        </a>
    </div>

    <!-- ==========================================
         MODAL TƯ VẤN / BÁO GIÁ NHANH SẢN PHẨM
         ========================================== -->
    <div id="productModal" class="fixed inset-0 bg-black/60 z-50 hidden items-center justify-center p-4">
        <div class="bg-white rounded-2xl max-w-md w-full p-5 sm:p-6 shadow-2xl relative">
            <button onclick="closeProductModal()" class="absolute top-4 right-4 w-8 h-8 rounded-full bg-gray-100 hover:bg-gray-200 flex items-center justify-center text-gray-600">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div class="text-xs font-bold uppercase text-pk-gold tracking-wider">Yêu cầu báo giá & Thiết kế logo</div>
            <h3 id="modalProductName" class="font-heading font-extrabold text-lg text-pk-navy mt-1 pr-6">Bình Giữ Nhiệt In Logo PK</h3>
            <p class="text-xs text-gray-600 mt-1">Liên hệ trực tiếp với <strong>Phúc Khang Thịnh Phát</strong> để nhận báo giá sỉ tận xưởng và bản thiết kế in logo miễn phí:</p>
            
            <div class="mt-4 space-y-2.5">
                <a href="https://zalo.me/0938613943" target="_blank" rel="noopener noreferrer" class="w-full py-3 px-4 rounded-xl bg-[#0068FF] hover:bg-blue-700 text-white font-bold text-sm flex items-center justify-center gap-2 transition">
                    <i class="fa-solid fa-comment-dots"></i> Nhắn Zalo Nhận Báo Giá (0938.613.943)
                </a>
                <a href="https://www.facebook.com/nguyen.thu.trang.854486/" target="_blank" rel="noopener noreferrer" class="w-full py-3 px-4 rounded-xl bg-[#1877F2] hover:bg-blue-800 text-white font-bold text-sm flex items-center justify-center gap-2 transition">
                    <i class="fa-brands fa-facebook"></i> Nhắn Tin Qua Facebook
                </a>
                <a href="tel:0938613943" class="w-full py-3 px-4 rounded-xl bg-amber-50 hover:bg-amber-100 text-pk-navy border border-amber-300 font-bold text-sm flex items-center justify-center gap-2 transition">
                    <i class="fa-solid fa-phone text-pk-gold"></i> Gọi Trực Tiếp: 0938.613.943
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         JAVASCRIPT: DỮ LIỆU DANH MỤC & SẢN PHẨM VỚI ẢNH THỰC TẾ TRÊN MẠNG
         ========================================== -->
    <script>
        // 14 Danh mục kết hợp chính xác từ ảnh chụp catalogue + Quà Tặng Quang Vũ với ảnh chụp sản phẩm thực tế chuẩn xác 100%
        const categoriesData = [
            {
                id: 'binh-giu-nhiet',
                name: 'BÌNH GIỮ NHIỆT',
                group: 'binh-giu-nhiet',
                image: 'https://images.unsplash.com/photo-1602143407151-7111542de6e8?auto=format&fit=crop&w=500&q=80'
            },
            {
                id: 'ly-su',
                name: 'LY SỨ',
                group: 'gom-su',
                image: 'https://images.unsplash.com/photo-1514228742587-6b1558fcca3d?auto=format&fit=crop&w=500&q=80'
            },
            {
                id: 'binh-thuy-tinh',
                name: 'BÌNH THỦY TINH',
                group: 'binh-giu-nhiet',
                image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Glass_water_bottle_positive_water_bottle_cheryl_myers_mypositivewater.com_my_positive_water_(44).jpg?width=500'
            },
            {
                id: 'so-tay',
                name: 'SỔ TAY BÌA DA',
                group: 'van-phong',
                image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Notebook.jpg?width=500'
            },
            {
                id: 'but-kim-loai',
                name: 'BÚT KIM LOẠI',
                group: 'van-phong',
                image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Ballpoint_Pen.jpg?width=500'
            },
            {
                id: 'dong-ho',
                name: 'ĐỒNG HỒ',
                group: 'cong-nghe',
                image: 'https://images.unsplash.com/photo-1524805444758-089113d48a6d?auto=format&fit=crop&w=500&q=80'
            },
            {
                id: 'mu-bao-hiem',
                name: 'MŨ BẢO HIỂM',
                group: 'quang-cao',
                image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Arai_Vector_motorcycle_helmet.jpg?width=500'
            },
            {
                id: 'o-du',
                name: 'Ô DÙ',
                group: 'quang-cao',
                image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Umbrella-65485.jpg?width=500'
            },
            {
                id: 'gau-bong',
                name: 'GẤU BÔNG',
                group: 'quang-cao',
                image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Teddy_bear_(9843921373).jpg?width=500'
            },
            {
                id: 'ao-mua',
                name: 'ÁO MƯA',
                group: 'quang-cao',
                image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Raincoat.jpg?width=500'
            },
            {
                id: 'balo',
                name: 'BALO',
                group: 'van-phong',
                image: 'https://images.unsplash.com/photo-1553062407-98eeb64c6a62?auto=format&fit=crop&w=500&q=80'
            },
            {
                id: 'the-hanh-ly',
                name: 'THẺ HÀNH LÝ',
                group: 'cong-nghe',
                image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Dca-baggage-tag.jpg?width=500'
            },
            {
                id: 'sac-du-phong',
                name: 'SẠC DỰ PHÒNG',
                group: 'cong-nghe',
                image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Portable_power_bank.jpg?width=500'
            },
            {
                id: 'quat-cam-tay',
                name: 'QUẠT CẦM TAY',
                group: 'cong-nghe',
                image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Kipas_portable.jpg?width=500'
            }
        ];

        // Dữ liệu các Section sản phẩm với ảnh chụp quà tặng doanh nghiệp thực tế chuẩn xác 100%
        const productSections = [
            {
                id: 'sec-binh-giu-nhiet',
                group: 'binh-giu-nhiet',
                title: 'BÌNH GIỮ NHIỆT & BÌNH THỦY TINH IN LOGO',
                products: [
                    {
                        code: 'PK-BGN01',
                        name: 'Bình Giữ Nhiệt Inox 304 Hiển Thị Nhiệt Độ In Logo Doanh Nghiệp',
                        image: 'https://images.unsplash.com/photo-1602143407151-7111542de6e8?auto=format&fit=crop&w=600&q=80'
                    },
                    {
                        code: 'PK-BGN02',
                        name: 'Bình Giữ Nhiệt Inox Cao Cấp Khắc Laser Thương Hiệu',
                        image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Thermos.JPG?width=600'
                    },
                    {
                        code: 'PK-BGN03',
                        name: 'Bình Giữ Nhiệt Nắp Bật Quà Tặng Đối Tác Trong & Ngoài Nước',
                        image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Japanese_vacuum_flask.jpg?width=600'
                    },
                    {
                        code: 'PK-BTT04',
                        name: 'Bình Thủy Tinh Chịu Nhiệt Có Dây Xách In Logo Theo Yêu Cầu',
                        image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Glass_water_bottle_positive_water_bottle_cheryl_myers_mypositivewater.com_my_positive_water_(44).jpg?width=600'
                    }
                ]
            },
            {
                id: 'sec-gom-su',
                group: 'gom-su',
                title: 'QUÀ TẶNG GỐM SỨ: LY SỨ & ẤM CHÉN BÁT TRÀNG',
                products: [
                    {
                        code: 'PK-LS01',
                        name: 'Ly Sứ Trắng Quai C In Logo Công Ty Sắc Nét',
                        image: 'https://images.unsplash.com/photo-1514228742587-6b1558fcca3d?auto=format&fit=crop&w=600&q=80'
                    },
                    {
                        code: 'PK-LS02',
                        name: 'Bộ Cốc Sứ Màu Cao Cấp Kèm Hộp Quà Sang Trọng',
                        image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Coffee_mugs.jpg?width=600'
                    },
                    {
                        code: 'PK-AC01',
                        name: 'Bộ Ấm Chén Sứ Trắng In Logo Đại Hội & Sự Kiện',
                        image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Teapot.jpg?width=600'
                    },
                    {
                        code: 'PK-AC02',
                        name: 'Bộ Ấm Trà Sứ Cao Cấp Quà Tặng Tri Ân Đối Tác Trong & Ngoài Nước',
                        image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Teapot_with_glass_%27piala%27.jpg?width=600'
                    }
                ]
            },
            {
                id: 'sec-quang-cao',
                group: 'quang-cao',
                title: 'QUÀ TẶNG QUẢNG CÁO: Ô DÙ, ÁO MƯA, MŨ BẢO HIỂM, GẤU BÔNG',
                products: [
                    {
                        code: 'PK-OD01',
                        name: 'Ô Dù Cầm Tay Gấp Gọn Tự Động In Logo Doanh Nghiệp',
                        image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Umbrella-65485.jpg?width=600'
                    },
                    {
                        code: 'PK-AM01',
                        name: 'Áo Mưa Cánh Dơi Vải Dù Siêu Nhẹ In Logo Quảng Bá Thương Hiệu',
                        image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Raincoat.jpg?width=600'
                    },
                    {
                        code: 'PK-MBH01',
                        name: 'Mũ Bảo Hiểm Đạt Chuẩn In Logo Quà Tặng Khách Hàng',
                        image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Arai_Vector_motorcycle_helmet.jpg?width=600'
                    },
                    {
                        code: 'PK-GB01',
                        name: 'Gấu Bông Thêu Logo Doanh Nghiệp Quà Tặng Sự Kiện',
                        image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Teddy_bear_(9843921373).jpg?width=600'
                    }
                ]
            },
            {
                id: 'sec-van-phong',
                group: 'van-phong',
                title: 'QUÀ TẶNG VĂN PHÒNG: SỔ TAY BÌA DA, BÚT KIM LOẠI, BALO',
                products: [
                    {
                        code: 'PK-ST01',
                        name: 'Sổ Tay Bìa Da PU Cao Cấp Dập Chìm / Ép Nhũ Vàng Logo',
                        image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Notebook.jpg?width=600'
                    },
                    {
                        code: 'PK-BKL01',
                        name: 'Bút Ký Kim Loại Khắc Laser Tên & Logo Kèm Hộp Quà',
                        image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Ballpoint_Pen.jpg?width=600'
                    },
                    {
                        code: 'PK-BL01',
                        name: 'Balo Laptop Công Sở Chống Thấm Nước Thêu Logo Công Ty',
                        image: 'https://images.unsplash.com/photo-1553062407-98eeb64c6a62?auto=format&fit=crop&w=600&q=80'
                    },
                    {
                        code: 'PK-GS01',
                        name: 'Bút Kim Loại Cao Cấp Khắc Logo Đối Tác Doanh Nghiệp',
                        image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Ballpoint_Pen_DS.jpg?width=600'
                    }
                ]
            },
            {
                id: 'sec-cong-nghe',
                group: 'cong-nghe',
                title: 'PHỤ KIỆN & CÔNG NGHỆ: SẠC DỰ PHÒNG, ĐỒNG HỒ, QUẠT, THẺ HÀNH LÝ',
                products: [
                    {
                        code: 'PK-SDP01',
                        name: 'Pin Sạc Dự Phòng 10.000mAh Sạc Nhanh In Logo Theo Yêu Cầu',
                        image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Portable_power_bank.jpg?width=600'
                    },
                    {
                        code: 'PK-DH01',
                        name: 'Đồng Hồ Đeo Tay & Đồng Hồ Để Bàn In Logo Đối Tác Doanh Nghiệp',
                        image: 'https://images.unsplash.com/photo-1524805444758-089113d48a6d?auto=format&fit=crop&w=600&q=80'
                    },
                    {
                        code: 'PK-THL01',
                        name: 'Thẻ Đeo Hành Lý In Logo Quà Tặng Du Lịch & Hàng Không',
                        image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Dca-baggage-tag.jpg?width=600'
                    },
                    {
                        code: 'PK-QCT01',
                        name: 'Quạt Cầm Tay Mini Tích Điện In Logo Quà Tặng Sự Kiện Mùa Hè',
                        image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Kipas_portable.jpg?width=600'
                    }
                ]
            },
            {
                id: 'sec-mua-vu',
                group: 'mua-vu',
                title: 'QUÀ TẾT DOANH NGHIỆP & HỘP BÁNH TRUNG THU CAO CẤP',
                products: [
                    {
                        code: 'PK-TT01',
                        name: 'Hộp Bánh Trung Thu Phú Quý In Nhũ Kim Logo Doanh Nghiệp',
                        image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Mooncake.jpg?width=600'
                    },
                    {
                        code: 'PK-TT02',
                        name: 'Set Bánh Trung Thu Truyền Thống Kết Hợp Trà Thượng Hạng Tặng Đối Tác',
                        image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Mooncake_3-4,_lotus_seed_paste_(cropped).jpg?width=600'
                    },
                    {
                        code: 'PK-QT01',
                        name: 'Giỏ Quà Tết Doanh Nghiệp An Khang Thiết Kế Theo Ngân Sách',
                        image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Hamper.jpg?width=600'
                    },
                    {
                        code: 'PK-QT02',
                        name: 'Hộp Quà Tết Thịnh Vượng In Logo Tặng Đối Tác Trong & Ngoài Nước',
                        image: 'https://commons.wikimedia.org/wiki/Special:FilePath/Gift_box.jpg?width=600'
                    }
                ]
            }
        ];

        // Render Danh mục (Category Grid): Chữ nhỏ gọn, hiển thị đầy đủ không bị cắt "...", tối ưu trên cả Điện thoại & Máy tính
        function renderCategories() {
            const container = document.getElementById('categoryGridContainer');
            container.innerHTML = categoriesData.map(cat => `
                <div onclick="filterCategory('${cat.group}')" class="box-category cursor-pointer rounded-xl bg-white border border-gray-200/90 p-1.5 sm:p-2 flex flex-col items-center justify-start text-center shadow-sm">
                    <div class="w-full aspect-square rounded-lg overflow-hidden bg-gray-50 flex items-center justify-center border border-gray-100">
                        <img 
                            src="${cat.image}" 
                            alt="${cat.name}" 
                            loading="lazy"
                            onerror="this.onerror=null;this.src='https://placehold.co/300x300/FAF7F2/1E2433?text=${encodeURIComponent(cat.name)}';"
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="mt-1.5 pt-1 border-t border-gray-100 w-full flex items-center justify-center min-h-[26px] sm:min-h-[30px]">
                        <h3 class="font-heading font-bold text-[10px] sm:text-[11px] text-pk-navy uppercase tracking-tight leading-tight text-center">
                            ${cat.name}
                        </h3>
                    </div>
                </div>
            `).join('');
        }

        // Render các Section sản phẩm (Điện thoại 2 cột: grid-cols-2, Máy tính 4 cột: lg:grid-cols-4, KHÔNG nhãn dán)
        function renderProducts(activeGroup = 'all', searchKeyword = '') {
            const wrapper = document.getElementById('danh-muc-san-pham');
            const kw = searchKeyword.trim().toLowerCase();

            const filteredSections = productSections.map(sec => {
                if (activeGroup !== 'all' && sec.group !== activeGroup) return null;
                const matchedProducts = sec.products.filter(p => 
                    !kw || p.name.toLowerCase().includes(kw) || p.code.toLowerCase().includes(kw)
                );
                if (matchedProducts.length === 0) return null;
                return { ...sec, products: matchedProducts };
            }).filter(Boolean);

            if (filteredSections.length === 0) {
                wrapper.innerHTML = `
                    <div class="flatsome-container text-center py-12 bg-white rounded-xl border border-gray-200">
                        <p class="text-base font-semibold text-gray-700">Không tìm thấy sản phẩm phù hợp với từ khóa "${searchKeyword}".</p>
                        <button onclick="filterCategory('all')" class="mt-3 px-4 py-2 bg-pk-gold text-white rounded-lg text-sm font-semibold">Xem tất cả sản phẩm</button>
                    </div>
                `;
                return;
            }

            wrapper.innerHTML = filteredSections.map(sec => `
                <section id="${sec.id}" class="section">
                    <div class="flatsome-container">
                        <!-- Tiêu đề danh mục chuẩn Flatsome -->
                        <div class="section-title-container">
                            <div class="section-title">
                                <h2 class="section-title-main text-sm sm:text-base md:text-lg">
                                    <span>${sec.title}</span>
                                </h2>
                                <a href="https://zalo.me/0938613943" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-pk-goldDark hover:underline shrink-0">
                                    Nhận catalogue <i class="fa-solid fa-angle-right"></i>
                                </a>
                            </div>
                        </div>

                        <!-- Lưới sản phẩm: 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4), KHÔNG có nhãn dán -->
                        <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                            ${sec.products.map(prod => `
                                <div class="col">
                                    <div class="col-inner h-full">
                                        <div class="product-small box bg-white rounded-xl border border-gray-200 overflow-hidden h-full flex flex-col justify-between">
                                            <!-- Box Image (Ảnh chụp thực tế, không có bất kỳ nhãn dán/sticker nào) -->
                                            <div onclick="openProductModal('${prod.name}')" class="box-image cursor-pointer bg-gray-50 h-40 sm:h-52 overflow-hidden flex items-center justify-center border-b border-gray-100">
                                                <img 
                                                    src="${prod.image}" 
                                                    alt="${prod.name}" 
                                                    loading="lazy"
                                                    onerror="this.onerror=null;this.src='https://placehold.co/400x400/FAF7F2/1E2433?text=${encodeURIComponent(prod.code)}';"
                                                    class="w-full h-full object-cover hover:scale-105 transition duration-500"
                                                >
                                            </div>
                                            <!-- Box Text -->
                                            <div class="box-text p-3 sm:p-4 flex-1 flex flex-col justify-between">
                                                <div>
                                                    <div class="text-[11px] text-gray-400 font-medium mb-1">Mã SP: ${prod.code}</div>
                                                    <h3 onclick="openProductModal('${prod.name}')" class="cursor-pointer font-semibold text-xs sm:text-sm text-pk-navy hover:text-pk-goldDark line-clamp-2 leading-snug">
                                                        ${prod.name}
                                                    </h3>
                                                </div>
                                                <div class="mt-3 pt-2.5 border-t border-gray-100 flex items-center justify-between gap-2">
                                                    <span class="text-xs sm:text-sm font-bold text-pk-goldDark">Giá: Liên hệ</span>
                                                    <button onclick="openProductModal('${prod.name}')" class="px-2.5 py-1.5 rounded-lg bg-pk-navy hover:bg-pk-gold text-white text-[11px] sm:text-xs font-semibold transition">
                                                        Báo giá
                                                    </button>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            `).join('')}
                        </div>
                    </div>
                </section>
            `).join('');
        }

        // Lọc theo danh mục
        function filterCategory(group) {
            const statusBar = document.getElementById('filterStatusBar');
            const statusText = document.getElementById('filterStatusText');
            const desktopInput = document.getElementById('desktopSearchInput');
            const mobileInput = document.getElementById('mobileSearchInput');
            if (desktopInput) desktopInput.value = '';
            if (mobileInput) mobileInput.value = '';

            if (group === 'all') {
                statusBar.classList.add('hidden');
            } else {
                const sec = productSections.find(s => s.group === group);
                statusText.textContent = sec ? sec.title : 'Danh mục đã chọn';
                statusBar.classList.remove('hidden');
            }
            renderProducts(group, '');
        }

        // Tìm kiếm trực tiếp
        function handleSearch(value) {
            const statusBar = document.getElementById('filterStatusBar');
            const statusText = document.getElementById('filterStatusText');
            if (value.trim() === '') {
                statusBar.classList.add('hidden');
                renderProducts('all', '');
            } else {
                statusText.textContent = `Từ khóa "${value}"`;
                statusBar.classList.remove('hidden');
                renderProducts('all', value);
            }
        }

        // Bật/tắt Menu trên điện thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            const backdrop = document.getElementById('mobileMenuBackdrop');
            const isHidden = drawer.classList.contains('-translate-x-full');
            if (isHidden) {
                drawer.classList.remove('-translate-x-full');
                backdrop.classList.remove('hidden');
            } else {
                drawer.classList.add('-translate-x-full');
                backdrop.classList.add('hidden');
            }
        }

        // Mở/Đóng Modal Báo giá sản phẩm
        function openProductModal(productName) {
            document.getElementById('modalProductName').textContent = productName;
            const modal = document.getElementById('productModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeProductModal() {
            const modal = document.getElementById('productModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        // Khởi chạy khi tải trang
        window.onload = function() {
            renderCategories();
            renderProducts('all', '');
        };
    </script>
</body>
</html>

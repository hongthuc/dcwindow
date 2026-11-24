<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY TNHH CỬA KÍNH DCWINDOW | Cửa Nhôm Xingfa & Kính Cường Lực Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH CỬA KÍNH DCWINDOW (dcwindow.com) chuyên thiết kế, thi công cửa nhôm Xingfa nhập khẩu, cửa kính cường lực, kính ốp bếp, phòng tắm kính, cầu thang kính uy tín giá tốt tại Đà Nẵng. Hotline: 0901 121 007.">

    <!-- Open Graph / Thumbnail chia sẻ link là ảnh Logo DCWINDOW -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="CÔNG TY TNHH CỬA KÍNH DCWINDOW">
    <meta property="og:title" content="CÔNG TY TNHH CỬA KÍNH DCWINDOW | Cửa Nhôm Xingfa & Kính Cường Lực Đà Nẵng">
    <meta property="og:description" content="Thi công cửa nhôm Xingfa chính hãng, kính ốp bếp, phòng tắm kính, cầu thang kính, cửa tự động uy tín tại Đà Nẵng. Địa chỉ: 201-203 Phan Thúc Trực, Hòa Xuân, Đà Nẵng.">
    <meta property="og:url" content="https://dcwindow.com">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1Ob8boFWkYf5k9RTxUCpmXshEWcrjIm6x&sz=w1000">
    <meta property="og:image:alt" content="Logo CÔNG TY TNHH CỬA KÍNH DCWINDOW">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH CỬA KÍNH DCWINDOW - dcwindow.com">
    <meta name="twitter:description" content="Cửa nhôm Xingfa, cửa kính cường lực, kính ốp bếp, phòng tắm kính uy tín tại Đà Nẵng.">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1Ob8boFWkYf5k9RTxUCpmXshEWcrjIm6x&sz=w1000">
    <link rel="icon" href="https://drive.google.com/thumbnail?id=1Ob8boFWkYf5k9RTxUCpmXshEWcrjIm6x&sz=w256" type="image/png">

    <!-- Fonts & Icons -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
                    },
                    colors: {
                        dc: {
                            primary: '#004b93',   // Xanh dương đậm chủ đạo theo nhận diện DCWINDOW
                            dark: '#003468',      // Xanh navy đậm
                            light: '#0070c9',     // Xanh dương sáng điểm nhấn
                            soft: '#eef5fc',      // Nền xanh nhạt
                            accent: '#d62828',    // Đỏ điểm nhấn cho % giảm giá & giá ưu đãi
                            surface: '#f5f7fa',   // Nền section nhẹ chuẩn Flatsome
                        }
                    }
                }
            }
        }
    </script>

    <!-- Custom CSS tối ưu chuẩn Flatsome & chống tràn viền 100% -->
    <style>
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html {
            scroll-behavior: smooth;
            max-width: 100%;
            overflow-x: hidden;
        }
        body {
            margin: 0;
            padding: 0;
            font-family: 'Inter', system-ui, -apple-system, sans-serif;
            color: #1e293b;
            background-color: #ffffff;
            max-width: 100%;
            overflow-x: hidden;
            -webkit-font-smoothing: antialiased;
        }

        /* Chiều ngang chuẩn 95% trên máy tính, căn giữa tuyệt đối, không lệch phải */
        .dc-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 640px) {
            .dc-container {
                padding-left: 18px;
                padding-right: 18px;
            }
        }
        @media (min-width: 1024px) {
            .dc-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Flatsome Section Title chuẩn UXBuilder */
        .flatsome-title-wrap {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 14px;
            margin-bottom: 1.5rem;
        }
        .flatsome-title-line {
            flex: 1;
            height: 2px;
            background: #e2e8f0;
            max-width: 120px;
        }
        .flatsome-title-text {
            font-weight: 800;
            text-transform: uppercase;
            color: #004b93;
            letter-spacing: 0.02em;
            text-align: center;
        }

        /* Menu máy tính 1 hàng gọn đẹp, không bao giờ xuống dòng trong từng mục */
        .nav-item-link {
            white-space: nowrap;
            display: inline-flex;
            align-items: center;
            gap: 4px;
            transition: color 0.2s ease, background-color 0.2s ease;
        }
        .nav-dropdown {
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
        }
        .nav-group:hover .nav-dropdown,
        .nav-group:focus-within .nav-dropdown {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        /* Hệ thống 2 Banner tự trượt cùng kích thước tuyệt đối bằng CSS Grid Stack */
        .banner-stack {
            display: grid;
            grid-template-columns: 1fr;
            width: 100%;
            position: relative;
        }
        .banner-slide {
            grid-area: 1 / 1;
            width: 100%;
            opacity: 0;
            visibility: hidden;
            pointer-events: none;
            transition: opacity 0.65s ease, transform 0.65s ease;
            transform: scale(1.01);
        }
        .banner-slide.is-active {
            opacity: 1;
            visibility: visible;
            pointer-events: auto;
            transform: scale(1);
            z-index: 2;
        }

        /* Hiệu ứng nhịp tim nhẹ cho nút Hotline nổi */
        @keyframes dcPulse {
            0% { box-shadow: 0 0 0 0 rgba(214, 40, 40, 0.55); }
            70% { box-shadow: 0 0 0 12px rgba(214, 40, 40, 0); }
            100% { box-shadow: 0 0 0 0 rgba(214, 40, 40, 0); }
        }
        .hotline-pulse {
            animation: dcPulse 2s infinite;
        }

        /* Hiệu ứng ẩn/hiện modal mượt mà */
        .dc-modal {
            transition: opacity 0.25s ease, visibility 0.25s ease;
        }
        .dc-modal.hidden-modal {
            opacity: 0;
            visibility: hidden;
            pointer-events: none;
        }

        /* Thanh cuộn tinh tế cho bảng báo giá trên điện thoại */
        .table-scroll::-webkit-scrollbar {
            height: 6px;
        }
        .table-scroll::-webkit-scrollbar-thumb {
            background: #cbd5e1;
            border-radius: 999px;
        }
    </style>

    <!-- Hàm hỗ trợ tải ảnh Google Drive có 3 lớp dự phòng chống lỗi -->
    <script>
        function dcImgFallback(img, fileId, label) {
            const step = parseInt(img.getAttribute('data-err') || '0', 10);
            if (step === 0 && fileId) {
                img.setAttribute('data-err', '1');
                img.src = 'https://lh3.googleusercontent.com/d/' + fileId + '=w1000';
            } else if (step === 1 && fileId) {
                img.setAttribute('data-err', '2');
                img.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
            } else {
                img.onerror = null;
                img.src = 'https://placehold.co/600x450/004b93/ffffff?text=' + encodeURIComponent(label || 'DCWINDOW');
            }
        }
    </script>
</head>
<body class="bg-white text-slate-800">

    <!-- =========================================================
         TOP BAR: Thông tin địa chỉ & giờ làm việc (Gọn gàng, chuẩn Flatsome)
         ========================================================= -->
    <div class="bg-dc-primary text-white text-xs py-1.5 border-b border-white/10">
        <div class="dc-container flex flex-wrap items-center justify-between gap-y-1 gap-x-4">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-location-dot text-sky-300"></i>
                    <span>201-203 Phan Thúc Trực, Hòa Xuân, Đà Nẵng</span>
                </span>
                <span class="hidden sm:inline-flex items-center gap-1.5">
                    <i class="fa-regular fa-clock text-sky-300"></i>
                    <span>Làm việc: 07:30 - 21:00 (T2 - CN)</span>
                </span>
            </div>
            <div class="flex items-center gap-x-4">
                <span class="hidden md:inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-globe text-sky-300"></i>
                    <span>dcwindow.com</span>
                </span>
                <a href="tel:0901121007" class="inline-flex items-center gap-1.5 font-semibold text-white hover:text-sky-200 transition">
                    <i class="fa-solid fa-phone-volume text-sky-300"></i>
                    <span>0901 121 007</span>
                </a>
            </div>
        </div>
    </div>

    <!-- =========================================================
         HEADER & NAVIGATION: Logo gọn nhỏ, Menu 1 hàng không xuống dòng, KHÔNG nút gọi ngay
         ========================================================= -->
    <header id="site-header" class="sticky top-0 z-40 bg-white/95 backdrop-blur border-b border-slate-200 shadow-sm">
        <div class="dc-container py-2 lg:py-2.5 flex items-center justify-between gap-2 lg:gap-4">
            <!-- Logo DCWINDOW chỉnh gọn nhỏ -->
            <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group" aria-label="Trang chủ CÔNG TY TNHH CỬA KÍNH DCWINDOW">
                <img
                    src="https://drive.google.com/thumbnail?id=1Ob8boFWkYf5k9RTxUCpmXshEWcrjIm6x&sz=w500"
                    alt="Logo CÔNG TY TNHH CỬA KÍNH DCWINDOW"
                    onerror="dcImgFallback(this, '1Ob8boFWkYf5k9RTxUCpmXshEWcrjIm6x', 'DCWINDOW')"
                    class="h-9 sm:h-10 lg:h-11 w-auto max-w-[135px] sm:max-w-[155px] object-contain"
                >
            </a>

            <!-- Danh mục trên máy tính: Chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng tên danh mục -->
            <nav aria-label="Danh mục chính" class="hidden lg:flex items-center justify-end flex-1 min-w-0">
                <ul class="flex flex-wrap items-center justify-end gap-x-0.5 xl:gap-x-1.5 gap-y-1 text-[12px] xl:text-[13px] font-semibold text-slate-700">
                    <li>
                        <a href="#trang-chu" class="nav-item-link px-2 xl:px-2.5 py-2 rounded-md text-dc-primary bg-dc-soft">Trang chủ</a>
                    </li>
                    <li>
                        <a href="#gioi-thieu" class="nav-item-link px-2 xl:px-2.5 py-2 rounded-md hover:text-dc-primary hover:bg-dc-soft">Giới thiệu</a>
                    </li>

                    <!-- Dropdown: Cửa nhôm xingfa -->
                    <li class="relative nav-group">
                        <a href="#san-pham-xingfa" class="nav-item-link px-2 xl:px-2.5 py-2 rounded-md hover:text-dc-primary hover:bg-dc-soft">
                            <span>Cửa nhôm xingfa</span>
                            <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                        </a>
                        <div class="nav-dropdown absolute left-0 top-full pt-1.5 z-50 w-56">
                            <ul class="bg-white rounded-lg shadow-xl border border-slate-200 py-1.5 text-[13px] font-medium text-slate-700">
                                <li><a href="#san-pham-xingfa" onclick="filterXingfa('1-canh')" class="block px-4 py-2 hover:bg-dc-soft hover:text-dc-primary whitespace-nowrap">Cửa nhôm xingfa 1 cánh</a></li>
                                <li><a href="#san-pham-xingfa" onclick="filterXingfa('2-canh')" class="block px-4 py-2 hover:bg-dc-soft hover:text-dc-primary whitespace-nowrap">Cửa nhôm xingfa 2 cánh</a></li>
                                <li><a href="#san-pham-xingfa" onclick="filterXingfa('3-canh')" class="block px-4 py-2 hover:bg-dc-soft hover:text-dc-primary whitespace-nowrap">Cửa nhôm xingfa 3 cánh</a></li>
                                <li><a href="#san-pham-xingfa" onclick="filterXingfa('4-canh')" class="block px-4 py-2 hover:bg-dc-soft hover:text-dc-primary whitespace-nowrap">Cửa nhôm xingfa 4 cánh</a></li>
                                <li><a href="#san-pham-xingfa" onclick="filterXingfa('xep-truot')" class="block px-4 py-2 hover:bg-dc-soft hover:text-dc-primary whitespace-nowrap">Cửa nhôm xingfa 5 cánh</a></li>
                            </ul>
                        </div>
                    </li>

                    <li>
                        <a href="#danh-muc-san-pham" onclick="highlightCategory('Cửa kính cường lực')" class="nav-item-link px-2 xl:px-2.5 py-2 rounded-md hover:text-dc-primary hover:bg-dc-soft">Cửa kính cường lực</a>
                    </li>

                    <!-- Dropdown: Sản phẩm -->
                    <li class="relative nav-group">
                        <a href="#danh-muc-san-pham" class="nav-item-link px-2 xl:px-2.5 py-2 rounded-md hover:text-dc-primary hover:bg-dc-soft">
                            <span>Sản phẩm</span>
                            <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                        </a>
                        <div class="nav-dropdown absolute left-0 top-full pt-1.5 z-50 w-52">
                            <ul class="bg-white rounded-lg shadow-xl border border-slate-200 py-1.5 text-[13px] font-medium text-slate-700">
                                <li><a href="#san-pham-xingfa" class="block px-4 py-2 hover:bg-dc-soft hover:text-dc-primary whitespace-nowrap">Cửa nhôm xingfa</a></li>
                                <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('cua-nhua-loi-thep')" class="block px-4 py-2 hover:bg-dc-soft hover:text-dc-primary whitespace-nowrap">Cửa nhựa lõi thép</a></li>
                                <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('cua-tu-dong')" class="block px-4 py-2 hover:bg-dc-soft hover:text-dc-primary whitespace-nowrap">Cửa kính tự động</a></li>
                                <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('cau-thang-kinh')" class="block px-4 py-2 hover:bg-dc-soft hover:text-dc-primary whitespace-nowrap">Cầu thang kính</a></li>
                                <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('kinh-op-bep')" class="block px-4 py-2 hover:bg-dc-soft hover:text-dc-primary whitespace-nowrap">Kính ốp bếp</a></li>
                                <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('phong-tam-kinh')" class="block px-4 py-2 hover:bg-dc-soft hover:text-dc-primary whitespace-nowrap">Phòng tắm kính</a></li>
                            </ul>
                        </div>
                    </li>

                    <li>
                        <a href="#cong-trinh" class="nav-item-link px-2 xl:px-2.5 py-2 rounded-md hover:text-dc-primary hover:bg-dc-soft">Công trình</a>
                    </li>
                    <li>
                        <a href="#bao-gia" class="nav-item-link px-2 xl:px-2.5 py-2 rounded-md hover:text-dc-primary hover:bg-dc-soft">Báo giá</a>
                    </li>
                    <li>
                        <a href="#tin-tuc" class="nav-item-link px-2 xl:px-2.5 py-2 rounded-md hover:text-dc-primary hover:bg-dc-soft">Tin tức</a>
                    </li>
                    <li>
                        <a href="#lien-he" class="nav-item-link px-2 xl:px-2.5 py-2 rounded-md hover:text-dc-primary hover:bg-dc-soft">Liên hệ</a>
                    </li>
                </ul>
            </nav>

            <!-- Nút mở Menu trên điện thoại & máy tính bảng -->
            <button
                id="mobile-menu-btn"
                type="button"
                aria-label="Mở danh mục"
                class="lg:hidden inline-flex items-center justify-center gap-2 px-3 py-2 rounded-lg border border-slate-200 text-dc-primary font-semibold text-sm hover:bg-dc-soft active:scale-95 transition"
            >
                <i class="fa-solid fa-bars text-base"></i>
                <span>Danh mục</span>
            </button>
        </div>
    </header>

    <!-- =========================================================
         MOBILE DRAWER MENU (Giao diện danh mục điện thoại đẹp, mượt)
         ========================================================= -->
    <div id="mobile-drawer-overlay" class="fixed inset-0 bg-slate-900/50 z-50 hidden opacity-0 transition-opacity duration-300"></div>
    <aside id="mobile-drawer" class="fixed top-0 left-0 bottom-0 w-[84%] max-w-[320px] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
        <div class="flex items-center justify-between px-4 py-3 border-b border-slate-200 bg-dc-soft/60">
            <img
                src="https://drive.google.com/thumbnail?id=1Ob8boFWkYf5k9RTxUCpmXshEWcrjIm6x&sz=w400"
                alt="DCWINDOW Logo"
                onerror="dcImgFallback(this, '1Ob8boFWkYf5k9RTxUCpmXshEWcrjIm6x', 'DCWINDOW')"
                class="h-8 w-auto object-contain"
            >
            <button id="mobile-close-btn" type="button" aria-label="Đóng danh mục" class="w-9 h-9 rounded-lg flex items-center justify-center text-slate-600 hover:bg-slate-200">
                <i class="fa-solid fa-xmark text-lg"></i>
            </button>
        </div>

        <nav class="flex-1 overflow-y-auto p-3 space-y-1 text-sm font-semibold text-slate-700">
            <a href="#trang-chu" class="mobile-nav-link block px-3 py-2.5 rounded-lg bg-dc-soft text-dc-primary">Trang chủ</a>
            <a href="#gioi-thieu" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-slate-100">Giới thiệu</a>

            <!-- Accordion Cửa nhôm Xingfa -->
            <div class="border border-slate-100 rounded-lg overflow-hidden">
                <button type="button" onclick="toggleMobileSub('sub-xingfa', this)" class="w-full flex items-center justify-between px-3 py-2.5 hover:bg-slate-100 text-left">
                    <span>Cửa nhôm xingfa</span>
                    <i class="fa-solid fa-chevron-down text-xs transition-transform duration-200"></i>
                </button>
                <div id="sub-xingfa" class="hidden bg-slate-50 px-2 pb-2 space-y-0.5 text-[13px] font-medium text-slate-600">
                    <a href="#san-pham-xingfa" onclick="filterXingfa('1-canh')" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-white hover:text-dc-primary">+ Cửa nhôm xingfa 1 cánh</a>
                    <a href="#san-pham-xingfa" onclick="filterXingfa('2-canh')" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-white hover:text-dc-primary">+ Cửa nhôm xingfa 2 cánh</a>
                    <a href="#san-pham-xingfa" onclick="filterXingfa('3-canh')" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-white hover:text-dc-primary">+ Cửa nhôm xingfa 3 cánh</a>
                    <a href="#san-pham-xingfa" onclick="filterXingfa('4-canh')" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-white hover:text-dc-primary">+ Cửa nhôm xingfa 4 cánh</a>
                    <a href="#san-pham-xingfa" onclick="filterXingfa('xep-truot')" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-white hover:text-dc-primary">+ Cửa nhôm xingfa 5 cánh</a>
                </div>
            </div>

            <a href="#danh-muc-san-pham" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-slate-100">Cửa kính cường lực</a>

            <!-- Accordion Sản phẩm -->
            <div class="border border-slate-100 rounded-lg overflow-hidden">
                <button type="button" onclick="toggleMobileSub('sub-sanpham', this)" class="w-full flex items-center justify-between px-3 py-2.5 hover:bg-slate-100 text-left">
                    <span>Sản phẩm</span>
                    <i class="fa-solid fa-chevron-down text-xs transition-transform duration-200"></i>
                </button>
                <div id="sub-sanpham" class="hidden bg-slate-50 px-2 pb-2 space-y-0.5 text-[13px] font-medium text-slate-600">
                    <a href="#san-pham-xingfa" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-white hover:text-dc-primary">+ Cửa nhôm xingfa</a>
                    <a href="#danh-muc-san-pham" onclick="openCategoryModal('cua-nhua-loi-thep')" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-white hover:text-dc-primary">+ Cửa nhựa lõi thép</a>
                    <a href="#danh-muc-san-pham" onclick="openCategoryModal('cua-tu-dong')" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-white hover:text-dc-primary">+ Cửa kính tự động</a>
                    <a href="#danh-muc-san-pham" onclick="openCategoryModal('cau-thang-kinh')" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-white hover:text-dc-primary">+ Cầu thang kính</a>
                    <a href="#danh-muc-san-pham" onclick="openCategoryModal('kinh-op-bep')" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-white hover:text-dc-primary">+ Kính ốp bếp</a>
                    <a href="#danh-muc-san-pham" onclick="openCategoryModal('phong-tam-kinh')" class="mobile-nav-link block px-3 py-2 rounded-md hover:bg-white hover:text-dc-primary">+ Phòng tắm kính</a>
                </div>
            </div>

            <a href="#cong-trinh" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-slate-100">Công trình</a>
            <a href="#bao-gia" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-slate-100">Báo giá</a>
            <a href="#tin-tuc" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-slate-100">Tin tức</a>
            <a href="#lien-he" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-slate-100">Liên hệ</a>
        </nav>

        <div class="p-4 border-t border-slate-200 bg-slate-50 text-xs text-slate-600 space-y-1.5">
            <p class="font-bold text-dc-primary">CÔNG TY TNHH CỬA KÍNH DCWINDOW</p>
            <p><i class="fa-solid fa-location-dot text-dc-primary mr-1"></i> 201-203 Phan Thúc Trực, Hòa Xuân, Đà Nẵng</p>
            <p><i class="fa-solid fa-phone text-dc-primary mr-1"></i> Hotline: 0901 121 007</p>
        </div>
    </aside>

    <!-- =========================================================
         HERO BANNER SLIDER: 2 Banner tự trượt kích thước bằng nhau tuyệt đối,
         hình ảnh & chữ nằm trọn bên trong, cách xa viền, không mất chữ trên mọi thiết bị
         ========================================================= -->
    <section id="trang-chu" class="py-3 sm:py-4 bg-white">
        <div class="dc-container">
            <div id="hero-slider" class="relative rounded-xl overflow-hidden shadow-lg bg-dc-dark select-none">
                <div class="banner-stack">

                    <!-- BANNER 1 -->
                    <div class="banner-slide is-active relative flex items-center bg-gradient-to-r from-[#002855] via-[#004b93] to-[#0064b7]">
                        <!-- Ảnh nền tinh tế có lớp phủ đảm bảo độ tương phản chữ -->
                        <div class="absolute inset-0 opacity-20 pointer-events-none">
                            <img
                                src="https://drive.google.com/thumbnail?id=1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ&sz=w1400"
                                alt="Dự án cửa nhôm kính DCWINDOW"
                                onerror="dcImgFallback(this, '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ', 'DCWINDOW')"
                                class="w-full h-full object-cover"
                            >
                        </div>
                        <!-- Vùng an toàn cách xa viền banner trên cả điện thoại và máy tính -->
                        <div class="relative z-10 w-full px-10 sm:px-14 md:px-20 lg:px-24 py-8 sm:py-12 md:py-14 lg:py-16">
                            <div class="grid grid-cols-1 md:grid-cols-12 gap-6 lg:gap-10 items-center">
                                <div class="md:col-span-7 text-white space-y-3 sm:space-y-4">
                                    <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-sky-200">
                                        CÔNG TY TNHH CỬA KÍNH DCWINDOW • ĐÀ NẴNG
                                    </p>
                                    <h1 class="text-xl sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-tight tracking-tight">
                                        Cửa Nhôm Xingfa Chính Hãng &amp; Cửa Kính Cường Lực Cao Cấp
                                    </h1>
                                    <p class="text-xs sm:text-sm md:text-base text-slate-100 leading-relaxed max-w-xl">
                                        Thi công trực tiếp từ xưởng sản xuất tại Hòa Xuân, Đà Nẵng. Cam kết nhôm Xingfa tem đỏ Quảng Đông, phụ kiện Kinlong đồng bộ, bảo hành dài hạn.
                                    </p>
                                    <div class="pt-1 flex flex-wrap items-center gap-2.5 sm:gap-3">
                                        <a href="#form-bao-gia" class="inline-flex items-center gap-2 px-4 sm:px-6 py-2.5 rounded-lg bg-dc-accent hover:bg-red-700 text-white font-bold text-xs sm:text-sm shadow-md transition">
                                            <span>Nhận Báo Giá Ngay</span>
                                            <i class="fa-solid fa-arrow-right text-xs"></i>
                                        </a>
                                        <a href="#san-pham-xingfa" class="inline-flex items-center gap-2 px-4 sm:px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-xs sm:text-sm transition">
                                            <span>Xem Sản Phẩm</span>
                                        </a>
                                    </div>
                                </div>
                                <div class="md:col-span-5">
                                    <div class="rounded-xl overflow-hidden border-2 border-white/25 shadow-2xl bg-white/10 aspect-[16/10] w-full">
                                        <img
                                            src="https://drive.google.com/thumbnail?id=1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX&sz=w1000"
                                            alt="Cửa nhôm Xingfa Đà Nẵng DCWINDOW"
                                            onerror="dcImgFallback(this, '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX', 'Cua Nhom Xingfa')"
                                            class="w-full h-full object-cover"
                                        >
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- BANNER 2 -->
                    <div class="banner-slide relative flex items-center bg-gradient-to-r from-[#0b2948] via-[#004b93] to-[#0277bd]">
                        <div class="absolute inset-0 opacity-20 pointer-events-none">
                            <img
                                src="https://drive.google.com/thumbnail?id=1za_IJpAm850uulT6IuhBsk1THb3LuPuc&sz=w1400"
                                alt="Công trình kính cường lực DCWINDOW Đà Nẵng"
                                onerror="dcImgFallback(this, '1za_IJpAm850uulT6IuhBsk1THb3LuPuc', 'DCWINDOW')"
                                class="w-full h-full object-cover"
                            >
                        </div>
                        <!-- Vùng an toàn cách xa viền banner đồng bộ 100% với Banner 1 -->
                        <div class="relative z-10 w-full px-10 sm:px-14 md:px-20 lg:px-24 py-8 sm:py-12 md:py-14 lg:py-16">
                            <div class="grid grid-cols-1 md:grid-cols-12 gap-6 lg:gap-10 items-center">
                                <div class="md:col-span-7 text-white space-y-3 sm:space-y-4">
                                    <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-sky-200">
                                        GIẢI PHÁP NỘI THẤT KÍNH ĐẸP • GIÁ TỐT TẠI ĐÀ NẴNG
                                    </p>
                                    <h2 class="text-xl sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-tight tracking-tight">
                                        Kính Màu Ốp Bếp, Phòng Tắm Kính &amp; Cầu Thang Kính Hiện Đại
                                    </h2>
                                    <p class="text-xs sm:text-sm md:text-base text-slate-100 leading-relaxed max-w-xl">
                                        Khảo sát đo đạc tận nơi hoàn toàn miễn phí tại Đà Nẵng &amp; miền Trung. Đội ngũ kỹ thuật giàu kinh nghiệm, thi công chuẩn xác, thẩm mỹ vượt trội.
                                    </p>
                                    <div class="pt-1 flex flex-wrap items-center gap-2.5 sm:gap-3">
                                        <a href="#cong-trinh" class="inline-flex items-center gap-2 px-4 sm:px-6 py-2.5 rounded-lg bg-white text-dc-primary hover:bg-sky-50 font-bold text-xs sm:text-sm shadow-md transition">
                                            <span>Xem Công Trình Thực Tế</span>
                                            <i class="fa-solid fa-building text-xs"></i>
                                        </a>
                                        <a href="tel:0901121007" class="inline-flex items-center gap-2 px-4 sm:px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-xs sm:text-sm transition">
                                            <i class="fa-solid fa-phone text-xs"></i>
                                            <span>Hotline: 0901 121 007</span>
                                        </a>
                                    </div>
                                </div>
                                <div class="md:col-span-5">
                                    <div class="rounded-xl overflow-hidden border-2 border-white/25 shadow-2xl bg-white/10 aspect-[16/10] w-full">
                                        <img
                                            src="https://drive.google.com/thumbnail?id=1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb&sz=w1000"
                                            alt="Kính màu ốp bếp đẹp uy tín Đà Nẵng"
                                            onerror="dcImgFallback(this, '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb', 'Kinh Op Bep')"
                                            class="w-full h-full object-cover"
                                        >
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>

                <!-- Nút điều hướng Trái/Phải đặt gọn sát mép ngoài vùng chữ -->
                <button id="banner-prev" type="button" aria-label="Banner trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/30 hover:bg-black/55 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                </button>
                <button id="banner-next" type="button" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/30 hover:bg-black/55 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                </button>

                <!-- Dấu chấm chỉ báo slide -->
                <div class="absolute bottom-2.5 sm:bottom-3.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" onclick="goToSlide(0)" aria-label="Chuyển tới Banner 1" class="banner-dot w-6 h-2 rounded-full bg-white transition-all"></button>
                    <button type="button" onclick="goToSlide(1)" aria-label="Chuyển tới Banner 2" class="banner-dot w-2.5 h-2 rounded-full bg-white/45 hover:bg-white/75 transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         GIỚI THIỆU CÔNG TY & THÔNG SỐ NỔI BẬT (Chuẩn bố cục Flatsome)
         ========================================================= -->
    <section id="gioi-thieu" class="py-10 sm:py-12 bg-dc-surface border-y border-slate-200/70">
        <div class="dc-container">
            <div class="flatsome-title-wrap">
                <span class="flatsome-title-line"></span>
                <h2 class="flatsome-title-text text-lg sm:text-xl md:text-2xl">CÔNG TY TNHH CỬA KÍNH DCWINDOW – ĐÀ NẴNG</h2>
                <span class="flatsome-title-line"></span>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-8 items-center">
                <div class="lg:col-span-7 space-y-3.5 text-sm sm:text-[15px] text-slate-600 leading-relaxed">
                    <p>
                        <strong class="text-dc-primary">CÔNG TY TNHH CỬA KÍNH DCWINDOW</strong> là đơn vị hàng đầu chuyên tư vấn thiết kế, sản xuất và thi công lắp đặt các hạng mục nhôm kính cao cấp tại Đà Nẵng và khu vực Miền Trung. Các dòng sản phẩm chủ lực bao gồm: <strong>Cửa nhôm Xingfa nhập khẩu, Cửa kính cường lực, Cửa nhựa lõi thép, Kính màu ốp bếp, Phòng tắm kính, Cầu thang kính và Cửa kính tự động</strong>.
                    </p>
                    <p>
                        Với phương châm <em>“Chất lượng tạo niềm tin – Cửa đẹp cho mọi công trình”</em>, DCWINDOW trực tiếp gia công trên dây chuyền máy móc hiện đại tại địa chỉ <strong>201-203 Phan Thúc Trực, Hòa Xuân, Đà Nẵng</strong>. Chúng tôi cam kết sản phẩm chính hãng, tiến độ chuẩn xác, thẩm mỹ tinh tế cùng chế độ bảo hành chu đáo cho mọi nhà phố, biệt thự, khách sạn và resort.
                    </p>
                    <!-- Cam kết dịch vụ ngắn gọn -->
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 pt-2">
                        <div class="flex items-center gap-2.5 bg-white p-3 rounded-lg border border-slate-200/80">
                            <i class="fa-solid fa-circle-check text-dc-primary text-base shrink-0"></i>
                            <span class="text-xs sm:text-sm font-medium text-slate-700">Khảo sát, đo đạc &amp; tư vấn miễn phí tận nơi</span>
                        </div>
                        <div class="flex items-center gap-2.5 bg-white p-3 rounded-lg border border-slate-200/80">
                            <i class="fa-solid fa-shield-halved text-dc-primary text-base shrink-0"></i>
                            <span class="text-xs sm:text-sm font-medium text-slate-700">Sản phẩm chính hãng, bảo hành 12 – 60 tháng</span>
                        </div>
                        <div class="flex items-center gap-2.5 bg-white p-3 rounded-lg border border-slate-200/80">
                            <i class="fa-solid fa-tags text-dc-primary text-base shrink-0"></i>
                            <span class="text-xs sm:text-sm font-medium text-slate-700">Giá gốc tại xưởng, ưu đãi công trình lớn</span>
                        </div>
                        <div class="flex items-center gap-2.5 bg-white p-3 rounded-lg border border-slate-200/80">
                            <i class="fa-solid fa-screwdriver-wrench text-dc-primary text-base shrink-0"></i>
                            <span class="text-xs sm:text-sm font-medium text-slate-700">Đội ngũ thợ tay nghề cao, thi công nhanh gọn</span>
                        </div>
                    </div>
                </div>

                <!-- 4 ô số liệu nổi bật -->
                <div class="lg:col-span-5 grid grid-cols-2 gap-3 sm:gap-4">
                    <div class="bg-white rounded-xl p-5 text-center border border-slate-200 shadow-sm">
                        <div class="text-2xl sm:text-3xl font-extrabold text-dc-primary">150+</div>
                        <div class="text-xs sm:text-sm text-slate-600 mt-1 font-medium">Dự án đã hoàn thành</div>
                    </div>
                    <div class="bg-white rounded-xl p-5 text-center border border-slate-200 shadow-sm">
                        <div class="text-2xl sm:text-3xl font-extrabold text-dc-primary">50+</div>
                        <div class="text-xs sm:text-sm text-slate-600 mt-1 font-medium">Kỹ thuật viên kinh nghiệm</div>
                    </div>
                    <div class="bg-white rounded-xl p-5 text-center border border-slate-200 shadow-sm">
                        <div class="text-2xl sm:text-3xl font-extrabold text-dc-primary">100+</div>
                        <div class="text-xs sm:text-sm text-slate-600 mt-1 font-medium">Mẫu cửa kính chất lượng</div>
                    </div>
                    <div class="bg-white rounded-xl p-5 text-center border border-slate-200 shadow-sm">
                        <div class="text-2xl sm:text-3xl font-extrabold text-dc-primary">100%</div>
                        <div class="text-xs sm:text-sm text-slate-600 mt-1 font-medium">Khách hàng hài lòng</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         SẢN PHẨM CỬA NHÔM XINGFA ĐÀ NẴNG
         - 2 cột trên điện thoại, 3 cột trên máy tính
         - Giá & Giảm giá % góc trên bên trái sản phẩm
         - Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hay tràn khung
         ========================================================= -->
    <section id="san-pham-xingfa" class="py-10 sm:py-14 bg-white">
        <div class="dc-container">
            <div class="flatsome-title-wrap">
                <span class="flatsome-title-line"></span>
                <h2 class="flatsome-title-text text-lg sm:text-xl md:text-2xl">BÁO GIÁ CỬA NHÔM XINGFA ĐÀ NẴNG</h2>
                <span class="flatsome-title-line"></span>
            </div>

            <!-- Thanh lọc nhanh theo loại cửa Xingfa -->
            <div class="flex flex-wrap items-center justify-center gap-2 mb-6 sm:mb-8">
                <button type="button" onclick="filterXingfa('all')" data-filter="all" class="xingfa-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-dc-primary text-white transition">Tất cả</button>
                <button type="button" onclick="filterXingfa('1-canh')" data-filter="1-canh" class="xingfa-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-dc-soft hover:text-dc-primary transition">1 cánh</button>
                <button type="button" onclick="filterXingfa('2-canh')" data-filter="2-canh" class="xingfa-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-dc-soft hover:text-dc-primary transition">2 cánh</button>
                <button type="button" onclick="filterXingfa('3-canh')" data-filter="3-canh" class="xingfa-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-dc-soft hover:text-dc-primary transition">3 cánh</button>
                <button type="button" onclick="filterXingfa('4-canh')" data-filter="4-canh" class="xingfa-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-dc-soft hover:text-dc-primary transition">4 cánh</button>
                <button type="button" onclick="filterXingfa('xep-truot')" data-filter="xep-truot" class="xingfa-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-dc-soft hover:text-dc-primary transition">Xếp trượt &amp; Cửa sổ</button>
            </div>

            <!-- Lưới sản phẩm: 2 cột trên điện thoại (grid-cols-2), 3 cột trên máy tính (md:grid-cols-3) -->
            <div id="xingfa-product-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5 lg:gap-6">
                <!-- Các sản phẩm được render tự động từ dữ liệu bên dưới -->
            </div>
        </div>
    </section>

    <!-- =========================================================
         DANH MỤC SẢN PHẨM NỔI BẬT (6 Danh mục giống web mẫu + ảnh thực tế Drive)
         ========================================================= -->
    <section id="danh-muc-san-pham" class="py-10 sm:py-14 bg-dc-surface border-t border-slate-200/70">
        <div class="dc-container">
            <div class="flatsome-title-wrap">
                <span class="flatsome-title-line"></span>
                <h2 class="flatsome-title-text text-lg sm:text-xl md:text-2xl">DANH MỤC SẢN PHẨM NỔI BẬT</h2>
                <span class="flatsome-title-line"></span>
            </div>

            <div id="category-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5 lg:gap-6">
                <!-- Render tự động 6 danh mục -->
            </div>
        </div>
    </section>

    <!-- =========================================================
         BẢNG BÁO GIÁ THAM KHẢO NHANH (Flatsome Tabs)
         ========================================================= -->
    <section id="bao-gia" class="py-10 sm:py-14 bg-white border-t border-slate-200/70">
        <div class="dc-container">
            <div class="flatsome-title-wrap">
                <span class="flatsome-title-line"></span>
                <h2 class="flatsome-title-text text-lg sm:text-xl md:text-2xl">BẢNG BÁO GIÁ THI CÔNG TẠI ĐÀ NẴNG</h2>
                <span class="flatsome-title-line"></span>
            </div>

            <!-- Tabs chuyển đổi bảng giá -->
            <div class="flex flex-wrap justify-center gap-2 mb-6">
                <button type="button" onclick="switchPriceTab('xingfa', this)" class="price-tab-btn px-4 py-2 rounded-lg text-xs sm:text-sm font-bold bg-dc-primary text-white shadow-sm transition">Cửa Nhôm Xingfa</button>
                <button type="button" onclick="switchPriceTab('cuakinh', this)" class="price-tab-btn px-4 py-2 rounded-lg text-xs sm:text-sm font-bold bg-slate-100 text-slate-700 hover:bg-dc-soft hover:text-dc-primary transition">Cửa Kính Cường Lực</button>
                <button type="button" onclick="switchPriceTab('kinhbep', this)" class="price-tab-btn px-4 py-2 rounded-lg text-xs sm:text-sm font-bold bg-slate-100 text-slate-700 hover:bg-dc-soft hover:text-dc-primary transition">Kính Ốp Bếp &amp; Phòng Tắm Kính</button>
            </div>

            <!-- Nội dung bảng giá -->
            <div class="bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden">
                <div class="overflow-x-auto table-scroll">
                    <table class="w-full text-left border-collapse min-w-[540px]">
                        <thead>
                            <tr class="bg-dc-primary text-white text-xs sm:text-sm">
                                <th class="py-3 px-4 font-bold w-14 text-center">STT</th>
                                <th class="py-3 px-4 font-bold">Hạng Mục Sản Phẩm</th>
                                <th class="py-3 px-4 font-bold">Quy Cách / Độ Dày</th>
                                <th class="py-3 px-4 font-bold text-right">Đơn Giá Tham Khảo</th>
                            </tr>
                        </thead>
                        <tbody id="price-table-body" class="divide-y divide-slate-200 text-xs sm:text-sm text-slate-700">
                            <!-- Render qua JS -->
                        </tbody>
                    </table>
                </div>
                <div class="bg-dc-soft/60 px-4 py-3 flex flex-wrap items-center justify-between gap-2 text-xs text-slate-600">
                    <span>* Đơn giá đã bao gồm chi phí vận chuyển và lắp đặt hoàn thiện tại nội thành Đà Nẵng.</span>
                    <a href="#form-bao-gia" class="font-bold text-dc-primary hover:underline">Nhận báo giá chi tiết theo bản vẽ →</a>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         CÁC DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG (6 Dự án thực tế)
         ========================================================= -->
    <section id="cong-trinh" class="py-10 sm:py-14 bg-dc-surface border-t border-slate-200/70">
        <div class="dc-container">
            <div class="flatsome-title-wrap">
                <span class="flatsome-title-line"></span>
                <h2 class="flatsome-title-text text-lg sm:text-xl md:text-2xl">CÁC DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG</h2>
                <span class="flatsome-title-line"></span>
            </div>

            <div class="flex flex-wrap items-center justify-center gap-2 mb-6 sm:mb-8">
                <button type="button" onclick="filterProjects('all')" data-proj="all" class="proj-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-dc-primary text-white transition">Tất cả dự án</button>
                <button type="button" onclick="filterProjects('khach-san')" data-proj="khach-san" class="proj-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-white border border-slate-200 text-slate-700 hover:border-dc-primary hover:text-dc-primary transition">Dự án Khách sạn</button>
                <button type="button" onclick="filterProjects('resort')" data-proj="resort" class="proj-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-white border border-slate-200 text-slate-700 hover:border-dc-primary hover:text-dc-primary transition">Dự án Resort</button>
            </div>

            <div id="project-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5 lg:gap-6">
                <!-- Render 6 dự án Đà Nẵng -->
            </div>
        </div>
    </section>

    <!-- =========================================================
         FORM YÊU CẦU & NHẬN BÁO GIÁ TRANG CHỦ
         ========================================================= -->
    <section id="form-bao-gia" class="py-10 sm:py-14 bg-gradient-to-br from-[#003468] via-[#004b93] to-[#005fb8] text-white">
        <div class="dc-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-6 space-y-4">
                    <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold uppercase tracking-tight">
                        Đăng Ký Yêu Cầu Tư Vấn &amp; Nhận Báo Giá Miễn Phí
                    </h2>
                    <p class="text-sm sm:text-base text-sky-100 leading-relaxed">
                        Để lại thông tin hạng mục cần thi công, kỹ thuật viên của <strong>CÔNG TY TNHH CỬA KÍNH DCWINDOW</strong> sẽ liên hệ tư vấn mẫu mã, khảo sát đo đạc tận công trình và gửi bảng dự toán chi tiết trong vòng 15 phút.
                    </p>
                    <ul class="space-y-2.5 text-sm text-white/95 pt-1">
                        <li class="flex items-start gap-2.5">
                            <i class="fa-solid fa-check-circle text-sky-300 mt-1"></i>
                            <span>Báo giá minh bạch, cạnh tranh nhất thị trường Đà Nẵng.</span>
                        </li>
                        <li class="flex items-start gap-2.5">
                            <i class="fa-solid fa-check-circle text-sky-300 mt-1"></i>
                            <span>Đem mẫu nhôm Xingfa, bảng màu kính ốp bếp tận nhà cho khách hàng xem thực tế.</span>
                        </li>
                        <li class="flex items-start gap-2.5">
                            <i class="fa-solid fa-check-circle text-sky-300 mt-1"></i>
                            <span>Hỗ trợ trực tiếp qua Hotline / Zalo: <strong class="text-amber-300">0901 121 007</strong>.</span>
                        </li>
                    </ul>
                </div>

                <div class="lg:col-span-6">
                    <form id="quote-form" class="bg-white text-slate-800 rounded-xl p-5 sm:p-7 shadow-2xl space-y-4">
                        <h3 class="text-base sm:text-lg font-extrabold text-dc-primary uppercase text-center">
                            Form Gửi Yêu Cầu Báo Giá
                        </h3>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                            <div>
                                <label for="q-name" class="block text-xs font-semibold text-slate-600 mb-1">Họ và tên *</label>
                                <input id="q-name" name="name" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:ring-2 focus:ring-dc-primary/30 focus:border-dc-primary">
                            </div>
                            <div>
                                <label for="q-phone" class="block text-xs font-semibold text-slate-600 mb-1">Số điện thoại / Zalo *</label>
                                <input id="q-phone" name="phone" type="tel" required placeholder="Ví dụ: 0901 121 007" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:ring-2 focus:ring-dc-primary/30 focus:border-dc-primary">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                            <div>
                                <label for="q-service" class="block text-xs font-semibold text-slate-600 mb-1">Hạng mục quan tâm</label>
                                <select id="q-service" name="service" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:ring-2 focus:ring-dc-primary/30 focus:border-dc-primary">
                                    <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa</option>
                                    <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                                    <option value="Kính màu ốp bếp">Kính màu ốp bếp</option>
                                    <option value="Phòng tắm kính">Phòng tắm kính</option>
                                    <option value="Cầu thang kính">Cầu thang kính</option>
                                    <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                                    <option value="Cửa kính tự động">Cửa kính tự động</option>
                                </select>
                            </div>
                            <div>
                                <label for="q-address" class="block text-xs font-semibold text-slate-600 mb-1">Địa chỉ công trình</label>
                                <input id="q-address" name="address" type="text" placeholder="Quận/Huyện tại Đà Nẵng..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:ring-2 focus:ring-dc-primary/30 focus:border-dc-primary">
                            </div>
                        </div>

                        <div>
                            <label for="q-note" class="block text-xs font-semibold text-slate-600 mb-1">Ghi chú kích thước / yêu cầu cụ thể</label>
                            <textarea id="q-note" name="note" rows="3" placeholder="Ví dụ: Cần làm cửa đi Xingfa 4 cánh và 6m kính ốp bếp màu xanh ngọc..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:ring-2 focus:ring-dc-primary/30 focus:border-dc-primary"></textarea>
                        </div>

                        <!-- Hộp thông báo trạng thái ngay trong form (không dùng alert) -->
                        <div id="quote-feedback" class="hidden rounded-lg px-4 py-3 text-xs sm:text-sm font-medium"></div>

                        <button type="submit" class="w-full py-3 rounded-lg bg-dc-accent hover:bg-red-700 text-white font-bold text-sm uppercase tracking-wide shadow-md transition active:scale-[0.99]">
                            <i class="fa-solid fa-paper-plane mr-1.5"></i> Gửi Yêu Cầu Nhận Báo Giá
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         DANH MỤC CÁC BÀI VIẾT / TIN TỨC NỔI BẬT TRANG CHỦ
         ========================================================= -->
    <section id="tin-tuc" class="py-10 sm:py-14 bg-white">
        <div class="dc-container">
            <div class="flatsome-title-wrap">
                <span class="flatsome-title-line"></span>
                <h2 class="flatsome-title-text text-lg sm:text-xl md:text-2xl">DANH MỤC BÀI VIẾT &amp; TIN TỨC NỔI BẬT</h2>
                <span class="flatsome-title-line"></span>
            </div>

            <!-- Danh mục bài viết gọn đẹp -->
            <div class="flex flex-wrap items-center justify-center gap-2 mb-6 sm:mb-8">
                <button type="button" onclick="filterArticles('all')" data-art="all" class="art-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-dc-primary text-white transition">Tất cả bài viết</button>
                <button type="button" onclick="filterArticles('xingfa')" data-art="xingfa" class="art-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-dc-soft hover:text-dc-primary transition">Tư vấn Nhôm Xingfa</button>
                <button type="button" onclick="filterArticles('kinh')" data-art="kinh" class="art-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-dc-soft hover:text-dc-primary transition">Kính Ốp Bếp &amp; Nội Thất</button>
                <button type="button" onclick="filterArticles('kinh-nghiem')" data-art="kinh-nghiem" class="art-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-dc-soft hover:text-dc-primary transition">Kinh Nghiệm Chọn Cửa</button>
            </div>

            <div id="article-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-6">
                <!-- Render 6 bài viết nổi bật -->
            </div>
        </div>
    </section>

    <!-- =========================================================
         BẢN ĐỒ GOOGLE MAP & FANPAGE FACEBOOK NGOÀI TRANG CHỦ
         ========================================================= -->
    <section id="lien-he" class="py-10 sm:py-14 bg-dc-surface border-t border-slate-200/70">
        <div class="dc-container">
            <div class="flatsome-title-wrap">
                <span class="flatsome-title-line"></span>
                <h2 class="flatsome-title-text text-lg sm:text-xl md:text-2xl">BẢN ĐỒ SHOWROOM &amp; FANPAGE DCWINDOW</h2>
                <span class="flatsome-title-line"></span>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                <!-- Cột Trái: Google Map trực tiếp địa chỉ 201-203 Phan Thúc Trực, Hòa Xuân, Đà Nẵng -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
                    <div class="px-4 py-3 bg-dc-primary text-white flex flex-wrap items-center justify-between gap-2">
                        <div class="flex items-center gap-2 text-xs sm:text-sm font-bold">
                            <i class="fa-solid fa-map-location-dot text-sky-300"></i>
                            <span>Bản đồ chỉ đường: 201-203 Phan Thúc Trực, Hòa Xuân, Đà Nẵng</span>
                        </div>
                        <a
                            href="https://www.google.com/maps/search/?api=1&query=201-203+Phan+Th%C3%BAc+Tr%E1%BB%B1c,+H%C3%B2a+Xu%C3%A2n,+%C4%90%C3%A0+N%E1%BA%B5ng"
                            target="_blank"
                            rel="noopener noreferrer"
                            class="text-xs font-semibold text-sky-200 hover:text-white underline"
                        >
                            Mở Google Maps
                        </a>
                    </div>
                    <div class="flex-1 min-h-[320px] sm:min-h-[380px] w-full bg-slate-100">
                        <iframe
                            title="Bản đồ CÔNG TY TNHH CỬA KÍNH DCWINDOW - 201-203 Phan Thúc Trực, Hòa Xuân, Đà Nẵng"
                            src="https://maps.google.com/maps?q=201-203+Phan+Th%C3%BAc+Tr%E1%BB%B1c,+H%C3%B2a+Xu%C3%A2n,+C%E1%BA%A9m+L%E1%BB%87,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full min-h-[320px] sm:min-h-[380px] border-0 block"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade"
                        ></iframe>
                    </div>
                </div>

                <!-- Cột Phải: Nhúng Fanpage Facebook chính thức ngoài trang chủ -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
                    <div class="px-4 py-3 bg-[#1877f2] text-white flex items-center justify-between gap-2">
                        <div class="flex items-center gap-2 text-xs sm:text-sm font-bold">
                            <i class="fa-brands fa-facebook text-base"></i>
                            <span>Fanpage Facebook Chính Thức</span>
                        </div>
                        <a
                            href="https://www.facebook.com/Kinhmauopbepgiareuytindanang/"
                            target="_blank"
                            rel="noopener noreferrer"
                            class="text-xs font-semibold bg-white/20 hover:bg-white/30 px-2.5 py-1 rounded-md transition"
                        >
                            Theo dõi ngay
                        </a>
                    </div>

                    <div class="p-4 flex-1 flex flex-col justify-between gap-4">
                        <!-- Khung nhúng Facebook Page Plugin -->
                        <div class="w-full rounded-lg overflow-hidden border border-slate-200 bg-slate-50 min-h-[260px] flex items-center justify-center">
                            <iframe
                                title="Fanpage Facebook CÔNG TY TNHH CỬA KÍNH DCWINDOW"
                                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FKinhmauopbepgiareuytindanang%2F&tabs=timeline&width=440&height=280&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                class="w-full h-[280px] border-0 overflow-hidden block"
                                scrolling="no"
                                frameborder="0"
                                allowfullscreen="true"
                                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                            ></iframe>
                        </div>

                        <!-- Thẻ kết nối nhanh Fanpage đảm bảo luôn hiển thị đẹp ngay cả khi trình duyệt chặn iframe Facebook -->
                        <div class="flex items-center justify-between gap-3 p-3 rounded-lg bg-dc-soft border border-dc-primary/15">
                            <div class="flex items-center gap-3 min-w-0">
                                <img
                                    src="https://drive.google.com/thumbnail?id=1Ob8boFWkYf5k9RTxUCpmXshEWcrjIm6x&sz=w200"
                                    alt="DCWINDOW Fanpage"
                                    onerror="dcImgFallback(this, '1Ob8boFWkYf5k9RTxUCpmXshEWcrjIm6x', 'DC')"
                                    class="w-11 h-11 rounded-lg object-contain bg-white p-1 border border-slate-200 shrink-0"
                                >
                                <div class="min-w-0">
                                    <p class="text-xs sm:text-sm font-bold text-dc-primary truncate">Cửa Kính &amp; Kính Màu Ốp Bếp DCWINDOW</p>
                                    <p class="text-[11px] text-slate-600 truncate">fb.com/Kinhmauopbepgiareuytindanang</p>
                                </div>
                            </div>
                            <a
                                href="https://www.facebook.com/Kinhmauopbepgiareuytindanang/"
                                target="_blank"
                                rel="noopener noreferrer"
                                class="shrink-0 px-3 py-2 rounded-lg bg-[#1877f2] hover:bg-blue-700 text-white text-xs font-bold transition"
                            >
                                Xem Fanpage
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         ĐỐI TÁC CỦA CHÚNG TÔI (6 Logo Đối Tác từ Google Drive)
         ========================================================= -->
    <section class="py-10 sm:py-12 bg-white border-t border-slate-200/70">
        <div class="dc-container">
            <div class="flatsome-title-wrap">
                <span class="flatsome-title-line"></span>
                <h2 class="flatsome-title-text text-lg sm:text-xl md:text-2xl">ĐỐI TÁC CỦA CHÚNG TÔI</h2>
                <span class="flatsome-title-line"></span>
            </div>

            <div class="grid grid-cols-3 sm:grid-cols-3 md:grid-cols-6 gap-3 sm:gap-4">
                <div class="bg-white rounded-lg border border-slate-200 p-3 sm:p-4 flex items-center justify-center h-20 sm:h-24 hover:shadow-md transition">
                    <img src="https://drive.google.com/thumbnail?id=13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk&sz=w500" alt="Đối tác DCWINDOW 1" onerror="dcImgFallback(this, '13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk', 'Partner 1')" class="max-h-full max-w-full object-contain">
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 sm:p-4 flex items-center justify-center h-20 sm:h-24 hover:shadow-md transition">
                    <img src="https://drive.google.com/thumbnail?id=1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq&sz=w500" alt="Đối tác DCWINDOW 2" onerror="dcImgFallback(this, '1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq', 'Partner 2')" class="max-h-full max-w-full object-contain">
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 sm:p-4 flex items-center justify-center h-20 sm:h-24 hover:shadow-md transition">
                    <img src="https://drive.google.com/thumbnail?id=1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn&sz=w500" alt="Đối tác DCWINDOW 3" onerror="dcImgFallback(this, '1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn', 'Partner 3')" class="max-h-full max-w-full object-contain">
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 sm:p-4 flex items-center justify-center h-20 sm:h-24 hover:shadow-md transition">
                    <img src="https://drive.google.com/thumbnail?id=1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT&sz=w500" alt="Đối tác DCWINDOW 4" onerror="dcImgFallback(this, '1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT', 'Partner 4')" class="max-h-full max-w-full object-contain">
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 sm:p-4 flex items-center justify-center h-20 sm:h-24 hover:shadow-md transition">
                    <img src="https://drive.google.com/thumbnail?id=1SDcarhnX0yypmqdbawICjYBRtFnKngn-&sz=w500" alt="Đối tác DCWINDOW 5" onerror="dcImgFallback(this, '1SDcarhnX0yypmqdbawICjYBRtFnKngn-', 'Partner 5')" class="max-h-full max-w-full object-contain">
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 sm:p-4 flex items-center justify-center h-20 sm:h-24 hover:shadow-md transition">
                    <img src="https://drive.google.com/thumbnail?id=1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg&sz=w500" alt="Đối tác DCWINDOW 6" onerror="dcImgFallback(this, '1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg', 'Partner 6')" class="max-h-full max-w-full object-contain">
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         FOOTER CHUẨN FLATSOME (4 Cột sạch sẽ, dễ dựng lại trên UXBuilder)
         ========================================================= -->
    <footer class="bg-[#0b2340] text-slate-200 pt-10 pb-20 sm:pb-8">
        <div class="dc-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-white/10">
                <!-- Cột 1: Thông tin công ty -->
                <div class="space-y-3">
                    <div class="inline-block bg-white rounded-lg px-3 py-1.5">
                        <img
                            src="https://drive.google.com/thumbnail?id=1Ob8boFWkYf5k9RTxUCpmXshEWcrjIm6x&sz=w400"
                            alt="Logo CÔNG TY TNHH CỬA KÍNH DCWINDOW"
                            onerror="dcImgFallback(this, '1Ob8boFWkYf5k9RTxUCpmXshEWcrjIm6x', 'DCWINDOW')"
                            class="h-9 w-auto object-contain"
                        >
                    </div>
                    <h3 class="text-sm font-bold text-white uppercase">CÔNG TY TNHH CỬA KÍNH DCWINDOW</h3>
                    <ul class="space-y-2 text-xs sm:text-[13px] text-slate-300">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-sky-400 mt-1 shrink-0"></i>
                            <span>201-203 Phan Thúc Trực, Hòa Xuân, Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone text-sky-400 shrink-0"></i>
                            <a href="tel:0901121007" class="hover:text-white font-semibold">Hotline: 0901 121 007</a>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-globe text-sky-400 shrink-0"></i>
                            <span>Website: dcwindow.com</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-file-invoice text-sky-400 shrink-0"></i>
                            <span>MST: 0401955127</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Cửa nhôm Xingfa -->
                <div>
                    <h4 class="text-sm font-bold text-white uppercase pb-2 mb-3 border-b border-white/15">Cửa Nhôm Xingfa</h4>
                    <ul class="space-y-2 text-xs sm:text-[13px] text-slate-300">
                        <li><a href="#san-pham-xingfa" onclick="filterXingfa('1-canh')" class="hover:text-sky-300 transition">› Cửa nhôm xingfa 1 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterXingfa('2-canh')" class="hover:text-sky-300 transition">› Cửa nhôm xingfa 2 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterXingfa('3-canh')" class="hover:text-sky-300 transition">› Cửa nhôm xingfa 3 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterXingfa('4-canh')" class="hover:text-sky-300 transition">› Cửa nhôm xingfa 4 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterXingfa('xep-truot')" class="hover:text-sky-300 transition">› Cửa nhôm xingfa 5 cánh &amp; xếp trượt</a></li>
                        <li><a href="#bao-gia" class="hover:text-sky-300 transition">› Báo giá cửa nhôm Xingfa Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục sản phẩm -->
                <div>
                    <h4 class="text-sm font-bold text-white uppercase pb-2 mb-3 border-b border-white/15">Danh Mục Sản Phẩm</h4>
                    <ul class="space-y-2 text-xs sm:text-[13px] text-slate-300">
                        <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('cua-nhom-xingfa')" class="hover:text-sky-300 transition">› Cửa nhôm xingfa Đà Nẵng</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('cua-nhua-loi-thep')" class="hover:text-sky-300 transition">› Cửa nhựa lõi thép Đà Nẵng</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('cua-tu-dong')" class="hover:text-sky-300 transition">› Cửa kính tự động Đà Nẵng</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('cau-thang-kinh')" class="hover:text-sky-300 transition">› Cầu thang kính cường lực</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('kinh-op-bep')" class="hover:text-sky-300 transition">› Kính màu ốp bếp Đà Nẵng</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('phong-tam-kinh')" class="hover:text-sky-300 transition">› Phòng tắm kính cường lực</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Kết nối & Hỗ trợ -->
                <div>
                    <h4 class="text-sm font-bold text-white uppercase pb-2 mb-3 border-b border-white/15">Kết Nối Nhanh</h4>
                    <p class="text-xs sm:text-[13px] text-slate-300 leading-relaxed mb-3">
                        Cập nhật các mẫu cửa nhôm kính, kính màu ốp bếp và công trình thi công thực tế mới nhất tại Đà Nẵng.
                    </p>
                    <div class="flex items-center gap-2.5">
                        <a href="https://www.facebook.com/Kinhmauopbepgiareuytindanang/" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 px-3 py-2 rounded-lg bg-[#1877f2] hover:bg-blue-600 text-white text-xs font-bold transition">
                            <i class="fa-brands fa-facebook-f"></i>
                            <span>Facebook</span>
                        </a>
                        <a href="https://zalo.me/0901121007" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 px-3 py-2 rounded-lg bg-[#0068ff] hover:bg-sky-600 text-white text-xs font-bold transition">
                            <span>Zalo</span>
                        </a>
                        <a href="tel:0901121007" class="inline-flex items-center gap-1.5 px-3 py-2 rounded-lg bg-dc-accent hover:bg-red-700 text-white text-xs font-bold transition">
                            <i class="fa-solid fa-phone"></i>
                            <span>Gọi</span>
                        </a>
                    </div>
                </div>
            </div>

            <!-- Thanh bản quyền dưới cùng -->
            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
                <p>Copyright 2026 © Bản quyền thuộc về <strong class="text-white">CÔNG TY TNHH CỬA KÍNH DCWINDOW</strong> (dcwindow.com)</p>
                <p>Thiết kế chuẩn bố cục Flatsome • Tối ưu máy tính &amp; điện thoại</p>
            </div>
        </div>
    </footer>

    <!-- =========================================================
         CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE
         Tương thích mượt mà trên cả máy tính và điện thoại, không che nội dung
         ========================================================= -->
    <!-- Cụm nút nổi trên Máy tính & Tablet (Bên phải dưới) -->
    <div class="hidden sm:flex fixed right-4 bottom-5 z-40 flex-col items-end gap-2.5">
        <!-- Nút Zalo nổi -->
        <a
            href="https://zalo.me/0901121007"
            target="_blank"
            rel="noopener noreferrer"
            class="group flex items-center gap-2.5 pl-4 pr-2.5 py-2 rounded-full bg-[#0068ff] hover:bg-blue-700 text-white shadow-lg transition-all hover:scale-105"
            aria-label="Chat Zalo DCWINDOW 0901 121 007"
        >
            <span class="text-xs font-bold tracking-wide">Chat Zalo</span>
            <span class="w-8 h-8 rounded-full bg-white text-[#0068ff] font-extrabold text-[11px] flex items-center justify-center shadow-inner">Zalo</span>
        </a>

        <!-- Nút Facebook nổi -->
        <a
            href="https://www.facebook.com/Kinhmauopbepgiareuytindanang/"
            target="_blank"
            rel="noopener noreferrer"
            class="group flex items-center gap-2.5 pl-4 pr-2.5 py-2 rounded-full bg-[#1877f2] hover:bg-blue-700 text-white shadow-lg transition-all hover:scale-105"
            aria-label="Fanpage Facebook DCWINDOW"
        >
            <span class="text-xs font-bold tracking-wide">Facebook</span>
            <span class="w-8 h-8 rounded-full bg-white text-[#1877f2] flex items-center justify-center shadow-inner">
                <i class="fa-brands fa-facebook-f text-sm"></i>
            </span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a
            href="tel:0901121007"
            class="hotline-pulse flex items-center gap-2.5 pl-4 pr-2.5 py-2 rounded-full bg-dc-accent hover:bg-red-700 text-white shadow-xl transition-all hover:scale-105"
            aria-label="Gọi Hotline 0901 121 007"
        >
            <span class="text-xs font-extrabold tracking-wide">0901 121 007</span>
            <span class="w-8 h-8 rounded-full bg-white text-dc-accent flex items-center justify-center shadow-inner">
                <i class="fa-solid fa-phone-volume text-sm"></i>
            </span>
        </a>
    </div>

    <!-- Thanh liên hệ nổi bật cố định đáy màn hình trên Điện thoại (3 nút đều nhau, dễ bấm bằng ngón tay) -->
    <div class="sm:hidden fixed bottom-0 left-0 right-0 z-40 bg-white/95 backdrop-blur border-t border-slate-200 shadow-[0_-4px_15px_rgba(0,0,0,0.08)] px-2 py-2">
        <div class="grid grid-cols-3 gap-2">
            <a
                href="tel:0901121007"
                class="flex items-center justify-center gap-1.5 py-2.5 rounded-lg bg-dc-accent text-white font-bold text-xs shadow-sm active:scale-95 transition"
            >
                <i class="fa-solid fa-phone-volume"></i>
                <span>Hotline</span>
            </a>
            <a
                href="https://zalo.me/0901121007"
                target="_blank"
                rel="noopener noreferrer"
                class="flex items-center justify-center gap-1.5 py-2.5 rounded-lg bg-[#0068ff] text-white font-bold text-xs shadow-sm active:scale-95 transition"
            >
                <span class="px-1 py-0.5 rounded bg-white text-[#0068ff] text-[10px] font-extrabold leading-none">Z</span>
                <span>Zalo</span>
            </a>
            <a
                href="https://www.facebook.com/Kinhmauopbepgiareuytindanang/"
                target="_blank"
                rel="noopener noreferrer"
                class="flex items-center justify-center gap-1.5 py-2.5 rounded-lg bg-[#1877f2] text-white font-bold text-xs shadow-sm active:scale-95 transition"
            >
                <i class="fa-brands fa-facebook-f"></i>
                <span>Facebook</span>
            </a>
        </div>
    </div>

    <!-- =========================================================
         MODAL XEM NHANH SẢN PHẨM / DỰ ÁN / BÀI VIẾT
         ========================================================= -->
    <div id="detail-modal" class="dc-modal hidden-modal fixed inset-0 z-50 flex items-center justify-center p-3 sm:p-5 bg-slate-900/65 backdrop-blur-xs">
        <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200 relative">
            <button type="button" onclick="closeDetailModal()" aria-label="Đóng cửa sổ" class="sticky top-3 float-right mr-3 mt-3 z-10 w-9 h-9 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-700 flex items-center justify-center transition">
                <i class="fa-solid fa-xmark text-base"></i>
            </button>
            <div id="detail-modal-body" class="p-4 sm:p-6 clear-both">
                <!-- Nội dung động render bởi JS -->
            </div>
        </div>
    </div>

    <!-- =========================================================
         JAVASCRIPT ĐIỀU KHIỂN DỮ LIỆU & TƯƠNG TÁC WEBSITE
         ========================================================= -->
    <script>
        // =====================================================
        // 1. DỮ LIỆU SẢN PHẨM CỬA NHÔM XINGFA (Ảnh Google Drive thực tế)
        // =====================================================
        const xingfaProducts = [
            {
                id: 'xf-1',
                name: 'Cửa đi quay mở 1 cánh nhôm xingfa',
                filter: '1-canh',
                fileId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
                originalPrice: '2.450.000 ₫',
                salePrice: '2.100.000 ₫',
                discount: '-14%',
                specs: 'Nhôm Xingfa hệ 55 dày 2.0mm, kính cường lực 8mm – 10mm, phụ kiện Kinlong nhập khẩu chính hãng, gioăng kép EPDM kín khít.',
                usage: 'Phù hợp cửa thông phòng, cửa ban công, cửa nhà vệ sinh, cửa lối đi phụ nhà phố & căn hộ.'
            },
            {
                id: 'xf-2',
                name: 'Cửa đi quay mở 2 cánh nhôm xingfa',
                filter: '2-canh',
                fileId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
                originalPrice: '2.400.000 ₫',
                salePrice: '2.100.000 ₫',
                discount: '-13%',
                specs: 'Nhôm Xingfa tem đỏ Quảng Đông hệ 55 dày 2.0mm, ép góc toàn khối, bản lề 3D Kinlong chịu lực cao.',
                usage: 'Lý tưởng cho cửa mặt tiền nhà phố, cửa ra sân vườn, cửa văn phòng và khách sạn tại Đà Nẵng.'
            },
            {
                id: 'xf-3',
                name: 'Cửa đi quay mở 3 cánh nhôm xingfa',
                filter: '3-canh',
                fileId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
                originalPrice: '2.500.000 ₫',
                salePrice: '2.100.000 ₫',
                discount: '-16%',
                specs: 'Nhôm Xingfa nhập khẩu dày 2.0mm, sơn tĩnh điện ngoài trời chống ăn mòn muối biển miền Trung.',
                usage: 'Tối ưu độ rộng lối đi, lấy sáng tự nhiên, cách âm cách nhiệt vượt trội.'
            },
            {
                id: 'xf-4',
                name: 'Cửa đi quay mở 4 cánh nhôm xingfa',
                filter: '4-canh',
                fileId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
                originalPrice: '2.450.000 ₫',
                salePrice: '2.100.000 ₫',
                discount: '-14%',
                specs: 'Nhôm Xingfa hệ 55 dày 2.0mm, khóa đa điểm chống trộm an toàn tuyệt đối, keo silicone chịu thời tiết.',
                usage: 'Lựa chọn hàng đầu cho cửa chính mặt tiền nhà phố, biệt thự và showroom sang trọng.'
            },
            {
                id: 'xf-5',
                name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
                filter: 'xep-truot',
                fileId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
                originalPrice: '2.600.000 ₫',
                salePrice: '2.100.000 ₫',
                discount: '-19%',
                specs: 'Nhôm Xingfa hệ 63 chuyên dụng xếp trượt (3, 4, 5, 6 cánh), hệ ray trượt & bánh xe chịu tải vận hành êm ái.',
                usage: 'Mở rộng tối đa không gian kết nối phòng khách với sân vườn, hồ bơi, ban công khách sạn & resort.'
            },
            {
                id: 'xf-6',
                name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
                filter: 'xep-truot',
                fileId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
                originalPrice: '2.350.000 ₫',
                salePrice: '1.950.000 ₫',
                discount: '-17%',
                specs: 'Nhôm Xingfa hệ 55 dày 1.4mm, thanh định vị góc mở 45 độ chống gió đập mạnh mùa mưa bão Đà Nẵng.',
                usage: 'Chống hắt mưa hiệu quả ngay cả khi mở lấy gió, phù hợp nhà cao tầng, căn hộ và khách sạn.'
            }
        ];

        // =====================================================
        // 2. DỮ LIỆU 6 DANH MỤC SẢN PHẨM NỔI BẬT
        // =====================================================
        const categoriesData = [
            {
                slug: 'cua-nhom-xingfa',
                name: 'CỬA NHÔM XINGFA',
                fileId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
                summary: 'Cửa nhôm Xingfa nhập khẩu tem đỏ Quảng Đông chính hãng hệ 55, 63, 93 kết hợp phụ kiện Kinlong đồng bộ, chống bão và cách âm vượt trội.'
            },
            {
                slug: 'cua-nhua-loi-thep',
                name: 'CỬA NHỰA LÕI THÉP',
                fileId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
                summary: 'Cửa nhựa uPVC lõi thép gia cường chống cong vênh, cách âm cách nhiệt hiệu quả, chi phí tiết kiệm cho nhà ở và căn hộ cho thuê.'
            },
            {
                slug: 'cua-tu-dong',
                name: 'CỬA TỰ ĐỘNG',
                fileId: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ',
                summary: 'Hệ thống cửa kính trượt tự động cảm biến mắt thần Hàn Quốc, Nhật Bản vận hành êm ái, sang trọng cho khách sạn, ngân hàng, showroom.'
            },
            {
                slug: 'cau-thang-kinh',
                name: 'CẦU THANG KÍNH',
                fileId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
                summary: 'Lan can cầu thang kính cường lực 10mm – 12mm tay vịn gỗ hoặc inox 304 chống gỉ, mang lại không gian thông thoáng và hiện đại.'
            },
            {
                slug: 'kinh-op-bep',
                name: 'KÍNH ỐP BẾP',
                fileId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
                summary: 'Kính màu cường lực ốp bếp sơn nhiệt cao cấp chống bám dầu mỡ, dễ lau chùi, đa dạng hơn 30 màu sắc hợp phong thủy gia chủ tại Đà Nẵng.'
            },
            {
                slug: 'phong-tam-kinh',
                name: 'PHÒNG TẮM KÍNH',
                fileId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
                summary: 'Cabin vách tắm kính cường lực 10mm cửa mở quay hoặc cửa lùa, phụ kiện inox 304 chuẩn chống nước tràn, giữ nhà tắm luôn khô ráo sạch sẽ.'
            }
        ];

        // =====================================================
        // 3. DỮ LIỆU 6 DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG
        // =====================================================
        const projectsData = [
            {
                id: 'pj-1',
                name: 'DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT & SPA”',
                type: 'resort',
                fileId: '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ',
                location: 'Quảng Nam – Đà Nẵng',
                scope: 'Thi công toàn bộ hệ cửa nhôm Xingfa cao cấp, vách kính lớn view thiên nhiên và phòng tắm kính cường lực tiêu chuẩn 4 sao.'
            },
            {
                id: 'pj-2',
                name: 'THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE',
                type: 'khach-san',
                fileId: '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy',
                location: 'TP. Đà Nẵng',
                scope: 'Lắp đặt hệ mặt dựng nhôm kính, cửa đi ban công nhôm Xingfa chống gió biển và cabin tắm kính toàn bộ các phòng nghỉ.'
            },
            {
                id: 'pj-3',
                name: 'DỰ ÁN KHÁCH SẠN RUBY LIGHT',
                type: 'khach-san',
                fileId: '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ',
                location: 'TP. Đà Nẵng',
                scope: 'Cung cấp và lắp đặt cửa kính cường lực sảnh chính, hệ cửa sổ mở hất Xingfa cách âm và lan can kính cường lực.'
            },
            {
                id: 'pj-4',
                name: 'THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL',
                type: 'khach-san',
                fileId: '1za_IJpAm850uulT6IuhBsk1THb3LuPuc',
                location: 'Ven biển Mỹ Khê, Đà Nẵng',
                scope: 'Thi công cửa nhôm Xingfa sơn tĩnh điện chống ăn mòn muối biển, cửa kính tự động sảnh lễ tân và vách kính phòng tắm.'
            },
            {
                id: 'pj-5',
                name: 'THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA',
                type: 'khach-san',
                fileId: '1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64',
                location: 'TP. Đà Nẵng',
                scope: 'Hoàn thiện trọn gói hạng mục nhôm kính Xingfa nhập khẩu, vách kính mặt tiền và kính cường lực nội thất khách sạn.'
            },
            {
                id: 'pj-6',
                name: 'THI CÔNG DỰ ÁN KHÁCH SẠN SOHO',
                type: 'khach-san',
                fileId: '1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt',
                location: 'TP. Đà Nẵng',
                scope: 'Thi công hệ thống cửa nhôm Xingfa màu xám ghi sang trọng, kính cường lực mặt dựng và phòng tắm kính cao cấp.'
            }
        ];

        // =====================================================
        // 4. DỮ LIỆU BẢNG BÁO GIÁ THEO TAB
        // =====================================================
        const priceTables = {
            xingfa: [
                { item: 'Cửa đi mở quay 1 cánh, 2 cánh nhôm Xingfa', spec: 'Hệ 55 dày 2.0mm, kính cường lực 8mm', price: '2.100.000 ₫ / m²' },
                { item: 'Cửa đi mở quay 3 cánh, 4 cánh nhôm Xingfa', spec: 'Hệ 55 dày 2.0mm, kính cường lực 8mm', price: '2.100.000 ₫ / m²' },
                { item: 'Cửa đi mở xếp trượt nhôm Xingfa (3 – 6 cánh)', spec: 'Hệ 63 chuyên dụng, phụ kiện đồng bộ', price: '2.100.000 ₫ / m²' },
                { item: 'Cửa sổ mở quay / mở hất 2 cánh nhôm Xingfa', spec: 'Hệ 55 dày 1.4mm, thanh chống gió bão', price: '1.950.000 ₫ / m²' },
                { item: 'Vách kính cố định khung nhôm Xingfa', spec: 'Hệ 55 dày 1.4mm, kính 8mm cường lực', price: '1.450.000 ₫ / m²' }
            ],
            cuakinh: [
                { item: 'Cửa kính cường lực mở quay bản lề sàn 10mm', spec: 'Kính cường lực 10ly phôi Việt Nhật', price: '750.000 ₫ / m²' },
                { item: 'Cửa kính cường lực mở quay bản lề sàn 12mm', spec: 'Kính cường lực 12ly an toàn cao', price: '850.000 ₫ / m²' },
                { item: 'Cửa kính cường lực lùa treo ray inox', spec: 'Kính 10mm + bộ bánh xe inox 304', price: '820.000 ₫ / m²' },
                { item: 'Vách kính cường lực văn phòng & mặt tiền', spec: 'Kính 10mm, nẹp nhôm / U inox 304', price: '680.000 ₫ / m²' }
            ],
            kinhbep: [
                { item: 'Kính màu ốp bếp cường lực 8mm sơn nhiệt', spec: 'Hơn 30 màu trơn & ánh kim chống ố', price: '750.000 ₫ / m dài' },
                { item: 'Kính ốp bếp 3D in tranh UV cao cấp', spec: 'Kính cường lực 8mm sắc nét bền màu', price: '1.150.000 ₫ / m dài' },
                { item: 'Phòng tắm kính mở quay 90° / 135° / 180°', spec: 'Kính 10mm cường lực, phụ kiện inox 304', price: '780.000 ₫ / m²' },
                { item: 'Cầu thang kính cường lực tay vịn gỗ / inox', spec: 'Kính 10mm – 12mm, trụ inox 304 chuẩn', price: '1.250.000 ₫ / m dài' }
            ]
        };

        // =====================================================
        // 5. DỮ LIỆU DANH MỤC BÀI VIẾT / TIN TỨC TRANG CHỦ
        // =====================================================
        const articlesData = [
            {
                id: 'art-1',
                category: 'xingfa',
                catLabel: 'Tư vấn Nhôm Xingfa',
                title: 'Cửa nhôm Xingfa có phù hợp với khí hậu biển Đà Nẵng không?',
                date: '18/11/2026',
                fileId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
                excerpt: 'Với công nghệ sơn tĩnh điện ngoài trời và kết cấu khoang rỗng chịu lực, cửa nhôm Xingfa chống ăn mòn hơi muối biển và chịu gió bão cực tốt tại Đà Nẵng.',
                content: 'Khí hậu ven biển Đà Nẵng có độ ẩm cao, hơi muối và thường xuyên chịu ảnh hưởng của gió bão lớn. Cửa nhôm Xingfa nhập khẩu chính hãng tại DCWINDOW sử dụng hợp kim nhôm 6063-T5 phủ sơn tĩnh điện cao cấp giúp bền màu trên 15 năm, không hoen gỉ, kết hợp hệ gioăng kép EPDM và keo chuyên dụng chống thấm nước mưa tuyệt đối.'
            },
            {
                id: 'art-2',
                category: 'kinh',
                catLabel: 'Kính Ốp Bếp & Nội Thất',
                title: 'Kinh nghiệm chọn màu kính ốp bếp cường lực bền đẹp, dễ lau chùi',
                date: '14/11/2026',
                fileId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
                excerpt: 'Hướng dẫn phối màu kính ốp bếp hài hòa với tủ bếp, ánh sáng và phong thủy giúp gian bếp luôn sáng bóng, hiện đại và sạch dầu mỡ.',
                content: 'Kính màu ốp bếp cường lực 8mm là giải pháp thay thế gạch men hiệu quả nhờ bề mặt phẳng liền mạch không có đường ron bám bẩn. Các tông màu được ưa chuộng nhất tại Đà Nẵng gồm xanh ngọc, vàng chanh, trắng sữa, xanh dương và đen kim sa. DCWINDOW hỗ trợ mang bảng màu kính thực tế đến tận nhà để khách hàng dễ dàng đối chiếu với màu tủ bếp.'
            },
            {
                id: 'art-3',
                category: 'kinh-nghiem',
                catLabel: 'Kinh Nghiệm Chọn Cửa',
                title: 'Cách phân biệt cửa nhôm Xingfa nhập khẩu tem đỏ chính hãng',
                date: '09/11/2026',
                fileId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
                excerpt: '4 dấu hiệu quan trọng giúp gia chủ kiểm tra đúng nhôm Xingfa Quảng Đông dày chuẩn 2.0mm và phụ kiện Kinlong đồng bộ, tránh hàng nhái.',
                content: 'Để chọn đúng cửa nhôm Xingfa chính hãng: (1) Kiểm tra tem đỏ in rõ nét có mã QR truy xuất nguồn gốc, (2) Mặt cắt bên trong thanh nhôm có ánh kim màu đồng do mạ crom chống oxy hóa, (3) Độ dày đạt chuẩn 2.0mm cho cửa đi và 1.4mm cho cửa sổ, (4) Góc cửa được bấm ép góc toàn khối sắc nét thay vì bắt vít thủ công.'
            },
            {
                id: 'art-4',
                category: 'kinh',
                catLabel: 'Kính Ốp Bếp & Nội Thất',
                title: 'Nên chọn phòng tắm kính mở quay hay cửa lùa cho nhà phố?',
                date: '05/11/2026',
                fileId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
                excerpt: 'So sánh ưu điểm từng kiểu cabin tắm kính cường lực 10mm giúp tối ưu diện tích và chống tràn nước hiệu quả cho phòng tắm gia đình.',
                content: 'Với phòng tắm có diện tích vừa và nhỏ, cabin vách tắm kính cửa lùa treo giúp tiết kiệm tối đa khoảng mở cánh. Trong khi đó, phòng tắm rộng rãi sẽ rất phù hợp với vách kính mở quay góc 90 độ hoặc 135 độ tạo vẻ đẹp sang trọng như khách sạn. Toàn bộ phụ kiện bản lề, kẹp kính tại DCWINDOW đều sử dụng inox 304 chống gỉ.'
            },
            {
                id: 'art-5',
                category: 'xingfa',
                catLabel: 'Tư vấn Nhôm Xingfa',
                title: 'Cửa nhôm Xingfa có cách âm, cách nhiệt và chống trộm tốt không?',
                date: '01/11/2026',
                fileId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
                excerpt: 'Tìm hiểu cấu tạo đa khoang, kính hộp/kính cường lực và khóa đa điểm giúp cửa nhôm Xingfa bảo vệ không gian yên tĩnh, an toàn.',
                content: 'Nhờ cấu trúc thanh profile nhiều khoang trống có gân gia cường kết hợp gioăng EPDM kín khít và hệ khóa đa điểm Kinlong, cửa nhôm Xingfa giảm thiểu tiếng ồn đường phố đáng kể, giữ nhiệt điều hòa tiết kiệm điện năng và tăng cường khả năng chống cạy phá an toàn cho ngôi nhà.'
            },
            {
                id: 'art-6',
                category: 'kinh-nghiem',
                catLabel: 'Kinh Nghiệm Chọn Cửa',
                title: 'Báo giá lắp đặt cầu thang kính cường lực trọn gói tại Đà Nẵng 2026',
                date: '27/10/2026',
                fileId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
                excerpt: 'Cập nhật mẫu cầu thang kính tay vịn gỗ sồi, gỗ lim và inox 304 sang trọng, bền vững cùng quy trình thi công chuẩn kỹ thuật tại DCWINDOW.',
                content: 'Cầu thang kính cường lực không chỉ giúp mở rộng tầm nhìn, đón sáng tự nhiên cho nhà ống mà còn đảm bảo độ chắc chắn an toàn tuyệt đối khi sử dụng kính 10mm – 12mm đạt tiêu chuẩn. Liên hệ ngay DCWINDOW qua số 0901 121 007 để được khảo sát cầu thang và nhận báo giá trọn gói tốt nhất.'
            }
        ];

        // =====================================================
        // 6. RENDER GIAO DIỆN SẢN PHẨM, DANH MỤC, DỰ ÁN, BÀI VIẾT
        // =====================================================
        function renderXingfaProducts(filterKey = 'all') {
            const container = document.getElementById('xingfa-product-grid');
            const list = filterKey === 'all' ? xingfaProducts : xingfaProducts.filter(p => p.filter === filterKey);

            container.innerHTML = list.map(p => `
                <article class="group bg-white rounded-xl border border-slate-200 shadow-sm hover:shadow-lg transition-all duration-300 flex flex-col overflow-hidden">
                    <!-- Ảnh sản phẩm + Nhãn giảm giá % góc trên bên trái -->
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden cursor-pointer" onclick="openProductModal('${p.id}')">
                        <span class="absolute top-2 left-2 z-10 inline-flex items-center justify-center px-2 py-1 rounded-md bg-dc-accent text-white font-extrabold text-[11px] sm:text-xs shadow-md">
                            ${p.discount}
                        </span>
                        <img
                            src="https://drive.google.com/thumbnail?id=${p.fileId}&sz=w800"
                            alt="${p.name}"
                            onerror="dcImgFallback(this, '${p.fileId}', '${p.name}')"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                            loading="lazy"
                        >
                    </div>

                    <!-- Nội dung thẻ sản phẩm: Tên hiển thị đầy đủ, không cắt chữ, không tràn khung -->
                    <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between gap-2.5">
                        <div>
                            <h3
                                onclick="openProductModal('${p.id}')"
                                class="text-[13px] sm:text-[15px] font-bold text-slate-800 group-hover:text-dc-primary leading-snug break-words cursor-pointer transition"
                            >
                                ${p.name}
                            </h3>
                        </div>

                        <div class="space-y-2.5 pt-1 border-t border-slate-100">
                            <!-- Giá gốc gạch ngang & Giá khuyến mãi nổi bật -->
                            <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                                <span class="text-sm sm:text-base font-extrabold text-dc-accent">${p.salePrice}</span>
                                <span class="text-[11px] sm:text-xs text-slate-400 line-through">${p.originalPrice}</span>
                            </div>

                            <div class="grid grid-cols-2 gap-1.5 sm:gap-2">
                                <button
                                    type="button"
                                    onclick="openProductModal('${p.id}')"
                                    class="py-2 px-2 rounded-lg bg-dc-soft hover:bg-dc-primary text-dc-primary hover:text-white font-semibold text-[11px] sm:text-xs transition text-center"
                                >
                                    Xem nhanh
                                </button>
                                <button
                                    type="button"
                                    onclick="requestQuoteFor('${p.name.replace(/'/g, "\\'")}')"
                                    class="py-2 px-2 rounded-lg bg-dc-primary hover:bg-dc-dark text-white font-semibold text-[11px] sm:text-xs transition text-center"
                                >
                                    Báo giá
                                </button>
                            </div>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        function filterXingfa(key) {
            renderXingfaProducts(key);
            document.querySelectorAll('.xingfa-filter-btn').forEach(btn => {
                const active = btn.getAttribute('data-filter') === key;
                btn.className = active
                    ? 'xingfa-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-dc-primary text-white transition'
                    : 'xingfa-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-dc-soft hover:text-dc-primary transition';
            });
        }

        function renderCategories() {
            const container = document.getElementById('category-grid');
            container.innerHTML = categoriesData.map(c => `
                <div
                    onclick="openCategoryModal('${c.slug}')"
                    class="group cursor-pointer bg-white rounded-xl border border-slate-200 shadow-sm hover:shadow-lg overflow-hidden transition-all duration-300 flex flex-col"
                >
                    <div class="aspect-[4/3] overflow-hidden bg-slate-100 relative">
                        <img
                            src="https://drive.google.com/thumbnail?id=${c.fileId}&sz=w800"
                            alt="${c.name}"
                            onerror="dcImgFallback(this, '${c.fileId}', '${c.name}')"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-3 sm:p-4 text-center bg-white flex-1 flex flex-col justify-center">
                        <h3 class="text-xs sm:text-sm md:text-[15px] font-extrabold text-dc-primary uppercase tracking-wide break-words">
                            ${c.name}
                        </h3>
                        <p class="hidden sm:block text-xs text-slate-500 mt-1 line-clamp-2">${c.summary}</p>
                    </div>
                </div>
            `).join('');
        }

        function renderProjects(typeKey = 'all') {
            const container = document.getElementById('project-grid');
            const list = typeKey === 'all' ? projectsData : projectsData.filter(p => p.type === typeKey);

            container.innerHTML = list.map(p => `
                <article
                    onclick="openProjectModal('${p.id}')"
                    class="group cursor-pointer bg-white rounded-xl border border-slate-200 shadow-sm hover:shadow-lg overflow-hidden transition-all duration-300 flex flex-col"
                >
                    <div class="aspect-[4/3] overflow-hidden bg-slate-100">
                        <img
                            src="https://drive.google.com/thumbnail?id=${p.fileId}&sz=w800"
                            alt="${p.name}"
                            onerror="dcImgFallback(this, '${p.fileId}', '${p.name}')"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between gap-2">
                        <h3 class="text-[12.5px] sm:text-sm font-bold text-slate-800 group-hover:text-dc-primary leading-snug break-words transition">
                            ${p.name}
                        </h3>
                        <div class="flex items-center justify-between text-[11px] sm:text-xs text-slate-500 pt-1.5 border-t border-slate-100">
                            <span><i class="fa-solid fa-location-dot text-dc-primary mr-1"></i>${p.location}</span>
                            <span class="font-semibold text-dc-primary">Chi tiết →</span>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        function filterProjects(key) {
            renderProjects(key);
            document.querySelectorAll('.proj-filter-btn').forEach(btn => {
                const active = btn.getAttribute('data-proj') === key;
                btn.className = active
                    ? 'proj-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-dc-primary text-white transition'
                    : 'proj-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-white border border-slate-200 text-slate-700 hover:border-dc-primary hover:text-dc-primary transition';
            });
        }

        function switchPriceTab(tabKey, btnEl) {
            const rows = priceTables[tabKey] || [];
            const tbody = document.getElementById('price-table-body');
            tbody.innerHTML = rows.map((r, idx) => `
                <tr class="hover:bg-dc-soft/40 transition">
                    <td class="py-3 px-4 text-center font-semibold text-slate-500">${idx + 1}</td>
                    <td class="py-3 px-4 font-bold text-slate-800">${r.item}</td>
                    <td class="py-3 px-4 text-slate-600">${r.spec}</td>
                    <td class="py-3 px-4 text-right font-extrabold text-dc-accent whitespace-nowrap">${r.price}</td>
                </tr>
            `).join('');

            if (btnEl) {
                document.querySelectorAll('.price-tab-btn').forEach(b => {
                    b.className = 'price-tab-btn px-4 py-2 rounded-lg text-xs sm:text-sm font-bold bg-slate-100 text-slate-700 hover:bg-dc-soft hover:text-dc-primary transition';
                });
                btnEl.className = 'price-tab-btn px-4 py-2 rounded-lg text-xs sm:text-sm font-bold bg-dc-primary text-white shadow-sm transition';
            }
        }

        function renderArticles(catKey = 'all') {
            const container = document.getElementById('article-grid');
            const list = catKey === 'all' ? articlesData : articlesData.filter(a => a.category === catKey);

            container.innerHTML = list.map(a => `
                <article
                    onclick="openArticleModal('${a.id}')"
                    class="group cursor-pointer bg-white rounded-xl border border-slate-200 shadow-sm hover:shadow-lg overflow-hidden transition-all duration-300 flex flex-col"
                >
                    <div class="aspect-[16/10] overflow-hidden bg-slate-100">
                        <img
                            src="https://drive.google.com/thumbnail?id=${a.fileId}&sz=w800"
                            alt="${a.title}"
                            onerror="dcImgFallback(this, '${a.fileId}', 'Tin tuc DCWINDOW')"
                            class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-4 flex-1 flex flex-col justify-between gap-2.5">
                        <div class="space-y-1.5">
                            <div class="flex items-center justify-between text-[11px] font-semibold text-dc-light">
                                <span>${a.catLabel}</span>
                                <span class="text-slate-400 font-normal">${a.date}</span>
                            </div>
                            <h3 class="text-sm sm:text-[15px] font-bold text-slate-800 group-hover:text-dc-primary leading-snug break-words transition">
                                ${a.title}
                            </h3>
                            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">
                                ${a.excerpt}
                            </p>
                        </div>
                        <div class="pt-2 border-t border-slate-100">
                            <span class="text-xs font-bold text-dc-primary group-hover:underline">Xem chi tiết bài viết →</span>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        function filterArticles(key) {
            renderArticles(key);
            document.querySelectorAll('.art-filter-btn').forEach(btn => {
                const active = btn.getAttribute('data-art') === key;
                btn.className = active
                    ? 'art-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-dc-primary text-white transition'
                    : 'art-filter-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-dc-soft hover:text-dc-primary transition';
            });
        }

        // =====================================================
        // 7. MODAL CHI TIẾT (SẢN PHẨM, DANH MỤC, DỰ ÁN, BÀI VIẾT)
        // =====================================================
        const detailModal = document.getElementById('detail-modal');
        const detailModalBody = document.getElementById('detail-modal-body');

        function openDetailModal(html) {
            detailModalBody.innerHTML = html;
            detailModal.classList.remove('hidden-modal');
            document.body.style.overflow = 'hidden';
        }

        function closeDetailModal() {
            detailModal.classList.add('hidden-modal');
            document.body.style.overflow = '';
        }

        detailModal.addEventListener('click', (e) => {
            if (e.target === detailModal) closeDetailModal();
        });

        function openProductModal(id) {
            const p = xingfaProducts.find(item => item.id === id);
            if (!p) return;
            openDetailModal(`
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-5 items-start">
                    <div class="relative rounded-xl overflow-hidden border border-slate-200 bg-slate-100 aspect-[4/3]">
                        <span class="absolute top-2.5 left-2.5 px-2.5 py-1 rounded-md bg-dc-accent text-white font-extrabold text-xs shadow">${p.discount}</span>
                        <img src="https://drive.google.com/thumbnail?id=${p.fileId}&sz=w900" alt="${p.name}" onerror="dcImgFallback(this, '${p.fileId}', '${p.name}')" class="w-full h-full object-cover">
                    </div>
                    <div class="space-y-3">
                        <h3 class="text-lg font-extrabold text-dc-primary leading-snug">${p.name}</h3>
                        <div class="flex items-baseline gap-2.5">
                            <span class="text-xl font-extrabold text-dc-accent">${p.salePrice}/m²</span>
                            <span class="text-sm text-slate-400 line-through">${p.originalPrice}</span>
                        </div>
                        <div class="text-xs sm:text-sm text-slate-600 space-y-2 leading-relaxed">
                            <p><strong class="text-slate-800">Thông số kỹ thuật:</strong> ${p.specs}</p>
                            <p><strong class="text-slate-800">Ứng dụng:</strong> ${p.usage}</p>
                        </div>
                        <div class="pt-2 flex flex-wrap gap-2">
                            <button type="button" onclick="closeDetailModal(); requestQuoteFor('${p.name.replace(/'/g, "\\'")}')" class="flex-1 py-2.5 px-4 rounded-lg bg-dc-accent hover:bg-red-700 text-white font-bold text-xs sm:text-sm transition">
                                Nhận báo giá mẫu này
                            </button>
                            <a href="tel:0901121007" class="py-2.5 px-4 rounded-lg bg-dc-primary hover:bg-dc-dark text-white font-bold text-xs sm:text-sm transition">
                                <i class="fa-solid fa-phone mr-1"></i>0901 121 007
                            </a>
                        </div>
                    </div>
                </div>
            `);
        }

        function openCategoryModal(slug) {
            const c = categoriesData.find(item => item.slug === slug);
            if (!c) return;
            openDetailModal(`
                <div class="space-y-4">
                    <div class="rounded-xl overflow-hidden border border-slate-200 aspect-[16/9] bg-slate-100">
                        <img src="https://drive.google.com/thumbnail?id=${c.fileId}&sz=w1000" alt="${c.name}" onerror="dcImgFallback(this, '${c.fileId}', '${c.name}')" class="w-full h-full object-cover">
                    </div>
                    <h3 class="text-lg sm:text-xl font-extrabold text-dc-primary">${c.name} – DCWINDOW ĐÀ NẴNG</h3>
                    <p class="text-sm text-slate-600 leading-relaxed">${c.summary}</p>
                    <div class="flex flex-wrap gap-2.5 pt-2">
                        <button type="button" onclick="closeDetailModal(); requestQuoteFor('${c.name}')" class="px-5 py-2.5 rounded-lg bg-dc-accent hover:bg-red-700 text-white font-bold text-sm transition">
                            Yêu cầu báo giá hạng mục này
                        </button>
                        <a href="https://zalo.me/0901121007" target="_blank" rel="noopener noreferrer" class="px-5 py-2.5 rounded-lg bg-[#0068ff] hover:bg-blue-700 text-white font-bold text-sm transition">
                            Tư vấn qua Zalo
                        </a>
                    </div>
                </div>
            `);
        }

        function openProjectModal(id) {
            const p = projectsData.find(item => item.id === id);
            if (!p) return;
            openDetailModal(`
                <div class="space-y-4">
                    <div class="rounded-xl overflow-hidden border border-slate-200 aspect-[16/10] bg-slate-100">
                        <img src="https://drive.google.com/thumbnail?id=${p.fileId}&sz=w1000" alt="${p.name}" onerror="dcImgFallback(this, '${p.fileId}', '${p.name}')" class="w-full h-full object-cover">
                    </div>
                    <div>
                        <p class="text-xs font-bold text-dc-light uppercase mb-1"><i class="fa-solid fa-location-dot mr-1"></i>${p.location}</p>
                        <h3 class="text-lg font-extrabold text-dc-primary leading-snug">${p.name}</h3>
                    </div>
                    <p class="text-sm text-slate-600 leading-relaxed"><strong class="text-slate-800">Hạng mục DCWINDOW thi công:</strong> ${p.scope}</p>
                    <div class="pt-1 flex flex-wrap gap-2.5">
                        <button type="button" onclick="closeDetailModal(); requestQuoteFor('Tư vấn thi công công trình tương tự: ${p.name.replace(/'/g, "\\'")}')" class="px-5 py-2.5 rounded-lg bg-dc-primary hover:bg-dc-dark text-white font-bold text-sm transition">
                            Liên hệ tư vấn dự án
                        </button>
                    </div>
                </div>
            `);
        }

        function openArticleModal(id) {
            const a = articlesData.find(item => item.id === id);
            if (!a) return;
            openDetailModal(`
                <div class="space-y-4">
                    <div class="rounded-xl overflow-hidden border border-slate-200 aspect-[16/9] bg-slate-100">
                        <img src="https://drive.google.com/thumbnail?id=${a.fileId}&sz=w1000" alt="${a.title}" onerror="dcImgFallback(this, '${a.fileId}', 'Tin tuc')" class="w-full h-full object-cover">
                    </div>
                    <div class="flex items-center gap-3 text-xs text-slate-500">
                        <span class="font-bold text-dc-primary">${a.catLabel}</span>
                        <span>•</span>
                        <span>Ngày đăng: ${a.date}</span>
                    </div>
                    <h3 class="text-lg sm:text-xl font-extrabold text-slate-900 leading-snug">${a.title}</h3>
                    <p class="text-sm text-slate-700 leading-relaxed">${a.content}</p>
                    <div class="p-4 rounded-lg bg-dc-soft border border-dc-primary/15 text-xs sm:text-sm text-slate-700">
                        <strong>CÔNG TY TNHH CỬA KÍNH DCWINDOW</strong> – 201-203 Phan Thúc Trực, Hòa Xuân, Đà Nẵng. Hotline hỗ trợ miễn phí: <a href="tel:0901121007" class="font-bold text-dc-accent">0901 121 007</a>.
                    </div>
                </div>
            `);
        }

        function highlightCategory(label) {
            const sel = document.getElementById('q-service');
            if (sel) sel.value = label;
        }

        function requestQuoteFor(productName) {
            const noteInput = document.getElementById('q-note');
            if (noteInput) {
                noteInput.value = 'Tôi cần tư vấn và nhận báo giá chi tiết cho: ' + productName;
            }
            const formSection = document.getElementById('form-bao-gia');
            if (formSection) {
                formSection.scrollIntoView({ behavior: 'smooth', block: 'start' });
            }
            setTimeout(() => {
                const nameInput = document.getElementById('q-name');
                if (nameInput) nameInput.focus();
            }, 500);
        }

        // =====================================================
        // 8. ĐIỀU KHIỂN SLIDER 2 BANNER TỰ TRƯỢT + VUỐT CẢM ỨNG
        // =====================================================
        let currentSlide = 0;
        const slides = document.querySelectorAll('.banner-slide');
        const dots = document.querySelectorAll('.banner-dot');
        let bannerTimer = null;

        function goToSlide(index) {
            currentSlide = (index + slides.length) % slides.length;
            slides.forEach((s, i) => {
                s.classList.toggle('is-active', i === currentSlide);
            });
            dots.forEach((d, i) => {
                if (i === currentSlide) {
                    d.classList.add('w-6', 'bg-white');
                    d.classList.remove('w-2.5', 'bg-white/45');
                } else {
                    d.classList.remove('w-6', 'bg-white');
                    d.classList.add('w-2.5', 'bg-white/45');
                }
            });
        }

        function startBannerAuto() {
            stopBannerAuto();
            bannerTimer = setInterval(() => {
                goToSlide(currentSlide + 1);
            }, 5000);
        }

        function stopBannerAuto() {
            if (bannerTimer) clearInterval(bannerTimer);
        }

        document.getElementById('banner-prev').addEventListener('click', () => {
            goToSlide(currentSlide - 1);
            startBannerAuto();
        });
        document.getElementById('banner-next').addEventListener('click', () => {
            goToSlide(currentSlide + 1);
            startBannerAuto();
        });

        const heroSlider = document.getElementById('hero-slider');
        heroSlider.addEventListener('mouseenter', stopBannerAuto);
        heroSlider.addEventListener('mouseleave', startBannerAuto);

        // Hỗ trợ vuốt cảm ứng trái/phải cho banner trên điện thoại
        let touchStartX = 0;
        heroSlider.addEventListener('touchstart', (e) => {
            touchStartX = e.changedTouches[0].screenX;
        }, { passive: true });
        heroSlider.addEventListener('touchend', (e) => {
            const diff = e.changedTouches[0].screenX - touchStartX;
            if (Math.abs(diff) > 40) {
                goToSlide(diff > 0 ? currentSlide - 1 : currentSlide + 1);
                startBannerAuto();
            }
        }, { passive: true });

        // =====================================================
        // 9. ĐIỀU KHIỂN MENU ĐIỆN THOẠI (DRAWER & ACCORDION)
        // =====================================================
        const mobileDrawer = document.getElementById('mobile-drawer');
        const mobileOverlay = document.getElementById('mobile-drawer-overlay');

        function openMobileMenu() {
            mobileOverlay.classList.remove('hidden');
            requestAnimationFrame(() => {
                mobileOverlay.classList.remove('opacity-0');
                mobileDrawer.classList.remove('-translate-x-full');
            });
            document.body.style.overflow = 'hidden';
        }

        function closeMobileMenu() {
            mobileOverlay.classList.add('opacity-0');
            mobileDrawer.classList.add('-translate-x-full');
            setTimeout(() => {
                mobileOverlay.classList.add('hidden');
                document.body.style.overflow = '';
            }, 300);
        }

        document.getElementById('mobile-menu-btn').addEventListener('click', openMobileMenu);
        document.getElementById('mobile-close-btn').addEventListener('click', closeMobileMenu);
        mobileOverlay.addEventListener('click', closeMobileMenu);

        document.querySelectorAll('.mobile-nav-link').forEach(link => {
            link.addEventListener('click', closeMobileMenu);
        });

        function toggleMobileSub(id, btn) {
            const el = document.getElementById(id);
            const icon = btn.querySelector('i');
            if (!el) return;
            el.classList.toggle('hidden');
            if (icon) icon.classList.toggle('rotate-180');
        }

        // =====================================================
        // 10. XỬ LÝ FORM GỬI YÊU CẦU BÁO GIÁ (KHÔNG DÙNG ALERT)
        // =====================================================
        document.getElementById('quote-form').addEventListener('submit', function(e) {
            e.preventDefault();
            const name = document.getElementById('q-name').value.trim();
            const phone = document.getElementById('q-phone').value.trim();
            const service = document.getElementById('q-service').value;
            const feedback = document.getElementById('quote-feedback');

            if (!name || !phone) {
                feedback.className = 'rounded-lg px-4 py-3 text-xs sm:text-sm font-medium bg-red-50 text-red-700 border border-red-200';
                feedback.textContent = 'Vui lòng nhập đầy đủ Họ tên và Số điện thoại để DCWINDOW liên hệ tư vấn.';
                return;
            }

            feedback.className = 'rounded-lg px-4 py-3 text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200';
            feedback.innerHTML = `<i class="fa-solid fa-circle-check mr-1.5 text-emerald-600"></i>Cảm ơn <strong>${name}</strong>! DCWINDOW đã tiếp nhận yêu cầu báo giá hạng mục <strong>${service}</strong> cho số <strong>${phone}</strong> và sẽ liên hệ tư vấn ngay.`;
            this.reset();
        });

        // Khởi chạy toàn bộ nội dung khi tải trang
        window.addEventListener('DOMContentLoaded', () => {
            renderXingfaProducts('all');
            renderCategories();
            renderProjects('all');
            switchPriceTab('xingfa');
            renderArticles('all');
            startBannerAuto();
        });
    </script>
</body>
</html>

# Resume_Krittrin-J.
<!DOCTYPE html>
<html lang="th" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KRITTRIN JIRINWONG | Cost Accountant · Senior Cost Accountant · Cost Controller</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Inter & Noto Sans Thai -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Noto+Sans+Thai:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['"Inter"', '"Noto Sans Thai"', 'sans-serif'],
                    },
                    colors: {
                        navyDark: '#0F172A',
                        navyMid: '#1E293B',
                        alabaster: '#F8FAFC',
                        slateText: '#334155',
                        slateMuted: '#64748B',
                        slateBorder: '#E2E8F0',
                        execGold: '#B45309',
                        execGoldBright: '#D97706',
                        execGoldSoft: '#FEF3C7',
                        corpBlue: '#1D4ED8'
                    },
                    boxShadow: {
                        'exec': '0 4px 20px -2px rgba(15, 23, 42, 0.05), 0 1px 3px 0 rgba(15, 23, 42, 0.04)',
                        'exec-hover': '0 10px 25px -5px rgba(15, 23, 42, 0.08), 0 4px 10px -2px rgba(15, 23, 42, 0.04)',
                        'nav': '0 4px 24px -4px rgba(15, 23, 42, 0.12)'
                    }
                }
            }
        }
    </script>

    <style>
        body {
            background-color: #F8FAFC;
            color: #0F172A;
            overflow-x: hidden;
            -webkit-tap-highlight-color: transparent;
        }

        /* Subtle Formal Top Grid Pattern */
        .corporate-header-bg {
            background: linear-gradient(180deg, #0F172A 0%, #1E293B 100%);
        }

        /* Language Switcher Pill Animation */
        .lang-slider {
            transition: transform 0.25s cubic-bezier(0.34, 1.56, 0.64, 1);
        }

        /* Smooth Accordion Expand */
        .accordion-content {
            display: grid;
            grid-template-rows: 1fr;
            transition: grid-template-rows 0.28s cubic-bezier(0.16, 1, 0.3, 1);
        }
        .accordion-content.collapsed {
            grid-template-rows: 0fr;
        }
        .accordion-inner {
            overflow: hidden;
        }

        /* Clean Custom Scrollbar */
        ::-webkit-scrollbar {
            width: 6px;
            height: 6px;
        }
        ::-webkit-scrollbar-track {
            background: #F1F5F9;
        }
        ::-webkit-scrollbar-thumb {
            background: #CBD5E1;
            border-radius: 9999px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #94A3B8;
        }

        /* Print Media Optimization for Executive Two-Column A4 Resume */
        @media print {
            @page {
                size: A4;
                margin: 10mm 12mm;
            }
            body * {
                visibility: hidden;
            }
            #resume-modal, #resume-printable, #resume-printable * {
                visibility: visible;
            }
            #resume-modal {
                position: static !important;
                display: block !important;
                padding: 0 !important;
                margin: 0 !important;
                background: white !important;
                overflow: visible !important;
            }
            #resume-printable {
                position: static !important;
                width: 100% !important;
                max-width: 100% !important;
                box-shadow: none !important;
                border: none !important;
                padding: 0 !important;
                margin: 0 !important;
                overflow: visible !important;
                font-size: 9.5pt !important;
                line-height: 1.38 !important;
            }
            .no-print {
                display: none !important;
            }
        }
    </style>
</head>
<body class="antialiased selection:bg-amber-100 selection:text-navyDark">

    <!-- Toast Notification (No alert() used) -->
    <div id="toast" class="fixed bottom-6 left-1/2 -translate-x-1/2 z-[100] pointer-events-none opacity-0 transition-all duration-300 translate-y-3 no-print">
        <div class="bg-navyDark text-white border border-slate-700 text-xs sm:text-sm font-medium px-4 py-2.5 rounded-xl shadow-xl flex items-center gap-2.5">
            <svg class="w-4 h-4 text-amber-400 shrink-0" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"></path>
            </svg>
            <span id="toast-message">คัดลอกข้อมูลเรียบร้อยแล้ว</span>
        </div>
    </div>

    <!-- ==========================================
         1. STICKY EXECUTIVE TOP NAVIGATION BAR
    =========================================== -->
    <header class="sticky top-0 z-40 bg-navyDark/95 backdrop-blur-md border-b border-slate-800 shadow-nav no-print">
        <div class="max-w-5xl mx-auto px-4 sm:px-6 h-16 flex items-center justify-between gap-2">
            <!-- Left: Monogram Badge 'KJ' in Deep Navy with Gold Border -->
            <a href="#top" class="flex items-center gap-3 group shrink-0">
                <div class="w-10 h-10 rounded-xl bg-navyMid border-2 border-amber-500/80 flex items-center justify-center font-extrabold text-sm tracking-wider text-amber-400 shadow-xs group-hover:border-amber-400 transition-colors">
                    KJ
                </div>
                <div class="hidden sm:block">
                    <p class="text-xs font-bold tracking-wider text-white">KRITTRIN JIRINWONG</p>
                    <p class="text-[10px] font-medium text-slate-400">Cost &amp; Inventory Accounting</p>
                </div>
            </a>

            <!-- Center: Quick Section Anchor Links -->
            <nav class="hidden lg:flex items-center gap-5 text-xs font-semibold text-slate-300">
                <a href="#summary" class="hover:text-amber-400 transition-colors" data-i18n="nav_summary">Summary</a>
                <a href="#achievements" class="hover:text-amber-400 transition-colors" data-i18n="nav_achievements">Achievements</a>
                <a href="#experience" class="hover:text-amber-400 transition-colors" data-i18n="nav_experience">Experience</a>
                <a href="#skills" class="hover:text-amber-400 transition-colors" data-i18n="nav_skills">Skills</a>
                <a href="#qualifications" class="hover:text-amber-400 transition-colors" data-i18n="nav_qualifications">Qualifications</a>
            </nav>

            <!-- Right: Language Toggle + Resume PDF & Contact Quick Buttons -->
            <div class="flex items-center gap-2 sm:gap-2.5">
                <!-- TH / EN Switcher Pill -->
                <div class="relative bg-slate-800/90 p-1 rounded-lg flex items-center border border-slate-700">
                    <div id="lang-indicator" class="lang-slider absolute left-1 top-1 w-9 h-7 bg-amber-600 rounded-md shadow-xs"></div>
                    <button type="button" onclick="setLanguage('th')" id="btn-th" class="relative z-10 w-9 h-7 text-[11px] font-bold tracking-wide text-white transition-colors">
                        TH
                    </button>
                    <button type="button" onclick="setLanguage('en')" id="btn-en" class="relative z-10 w-9 h-7 text-[11px] font-bold tracking-wide text-slate-400 transition-colors">
                        EN
                    </button>
                </div>

                <!-- Compact Resume PDF Button -->
                <button type="button" onclick="openResumeModal()" class="px-3 py-2 rounded-lg bg-amber-600 hover:bg-amber-500 text-white text-xs font-bold transition-colors flex items-center gap-1.5 shadow-xs">
                    <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M12 10v6m0 0l-3-3m3 3l3-3m2 8H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path>
                    </svg>
                    <span data-i18n="nav_btn_pdf">Resume PDF</span>
                </button>

                <!-- Compact Contact Button -->
                <button type="button" onclick="openContactModal()" class="px-3 py-2 rounded-lg bg-slate-800 hover:bg-slate-700 border border-slate-600 text-slate-100 text-xs font-semibold transition-colors hidden sm:inline-flex items-center gap-1.5">
                    <span data-i18n="nav_btn_contact">Contact</span>
                </button>

                <!-- Mobile Drawer Toggle -->
                <button type="button" onclick="toggleMobileMenu(true)" class="lg:hidden p-2 rounded-lg bg-slate-800 border border-slate-700 text-slate-200 hover:bg-slate-700" aria-label="Menu">
                    <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16"></path>
                    </svg>
                </button>
            </div>
        </div>
    </header>

    <!-- Mobile Navigation Slide-over Drawer -->
    <div id="mobile-drawer-backdrop" onclick="toggleMobileMenu(false)" class="fixed inset-0 bg-navyDark/50 backdrop-blur-xs z-50 hidden opacity-0 transition-opacity duration-300 no-print"></div>
    <aside id="mobile-drawer" class="fixed top-0 right-0 h-full w-72 bg-navyDark text-white z-50 shadow-2xl border-l border-slate-800 transform translate-x-full transition-transform duration-300 ease-out flex flex-col justify-between p-6 no-print">
        <div>
            <div class="flex items-center justify-between pb-5 border-b border-slate-800">
                <div class="flex items-center gap-2.5">
                    <span class="w-9 h-9 rounded-lg bg-navyMid border border-amber-500 flex items-center justify-center font-bold text-xs text-amber-400">KJ</span>
                    <div>
                        <p class="text-xs font-bold text-white">KRITTRIN JIRINWONG</p>
                        <p class="text-[11px] text-slate-400">Navigation</p>
                    </div>
                </div>
                <button type="button" onclick="toggleMobileMenu(false)" class="p-2 rounded-lg bg-slate-800 text-slate-300 hover:text-white">
                    <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"></path>
                    </svg>
                </button>
            </div>

            <nav class="mt-5 flex flex-col gap-1.5 text-sm font-medium">
                <a href="#summary" onclick="toggleMobileMenu(false)" class="px-3.5 py-2.5 rounded-lg hover:bg-slate-800 text-slate-200 flex justify-between items-center">
                    <span data-i18n="nav_summary">Summary</span>
                    <span class="text-xs text-slate-500">01</span>
                </a>
                <a href="#achievements" onclick="toggleMobileMenu(false)" class="px-3.5 py-2.5 rounded-lg hover:bg-slate-800 text-slate-200 flex justify-between items-center">
                    <span data-i18n="nav_achievements">Achievements</span>
                    <span class="text-xs text-slate-500">02</span>
                </a>
                <a href="#experience" onclick="toggleMobileMenu(false)" class="px-3.5 py-2.5 rounded-lg hover:bg-slate-800 text-slate-200 flex justify-between items-center">
                    <span data-i18n="nav_experience">Experience</span>
                    <span class="text-xs text-slate-500">03</span>
                </a>
                <a href="#skills" onclick="toggleMobileMenu(false)" class="px-3.5 py-2.5 rounded-lg hover:bg-slate-800 text-slate-200 flex justify-between items-center">
                    <span data-i18n="nav_skills">Skills</span>
                    <span class="text-xs text-slate-500">04</span>
                </a>
                <a href="#qualifications" onclick="toggleMobileMenu(false)" class="px-3.5 py-2.5 rounded-lg hover:bg-slate-800 text-slate-200 flex justify-between items-center">
                    <span data-i18n="nav_qualifications">Qualifications</span>
                    <span class="text-xs text-slate-500">05</span>
                </a>
            </nav>
        </div>

        <div class="space-y-2.5 pt-4 border-t border-slate-800">
            <button type="button" onclick="toggleMobileMenu(false); openResumeModal();" class="w-full py-2.5 px-4 rounded-lg bg-amber-600 hover:bg-amber-500 text-white text-xs font-bold flex items-center justify-center gap-2">
                <span data-i18n="cta_resume_full">ดูเรซูเม่ฉบับเต็ม / บันทึก PDF</span>
            </button>
            <button type="button" onclick="toggleMobileMenu(false); openContactModal();" class="w-full py-2.5 px-4 rounded-lg bg-slate-800 border border-slate-700 text-slate-200 text-xs font-semibold flex items-center justify-center gap-2">
                <span data-i18n="cta_contact">ติดต่อฉัน</span>
            </button>
        </div>
    </aside>

    <!-- ==========================================
         2. EXECUTIVE HERO SECTION
    =========================================== -->
    <section id="top" class="corporate-header-bg text-white border-b border-slate-800 no-print">
        <div class="max-w-5xl mx-auto px-4 sm:px-6 py-10 sm:py-14">
            <!-- Status Badge -->
            <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-slate-800/90 border border-amber-500/40 text-amber-300 text-xs font-semibold mb-5">
                <span class="w-2 h-2 rounded-full bg-emerald-400"></span>
                <span data-i18n="hero_status">ผู้ทำบัญชีขึ้นทะเบียน | สถานะ CPD ปัจจุบัน (Registered Accountant | Active CPD Status)</span>
            </div>

            <!-- Main Display Name -->
            <h1 class="text-2xl sm:text-4xl lg:text-[40px] font-extrabold tracking-tight text-white leading-tight mb-2.5" data-i18n="hero_name">
                กฤษตฤณ จิรินวงค์ — KRITTRIN JIRINWONG
            </h1>

            <!-- Target Titles -->
            <p class="text-base sm:text-xl font-semibold text-amber-400 tracking-wide mb-6">
                Cost Accountant <span class="text-slate-500 mx-1">|</span> Senior Cost Accountant <span class="text-slate-500 mx-1">|</span> Cost Controller
            </p>

            <!-- Contact Strip with One-Click Copy -->
            <div class="flex flex-wrap items-center gap-2.5 sm:gap-3 mb-8">
                <button type="button" onclick="copyText('Bangkok | Open to Relocation')" class="inline-flex items-center gap-2 px-3.5 py-2 rounded-lg bg-slate-800/80 hover:bg-slate-800 border border-slate-700 text-xs sm:text-sm text-slate-200 transition-colors group">
                    <svg class="w-4 h-4 text-amber-400 shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path>
                        <path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path>
                    </svg>
                    <span>Bangkok | Open to Relocation</span>
                </button>

                <button type="button" onclick="copyText('Krittrin.j@gmail.com')" class="inline-flex items-center gap-2 px-3.5 py-2 rounded-lg bg-slate-800/80 hover:bg-slate-800 border border-slate-700 text-xs sm:text-sm text-slate-200 transition-colors group">
                    <svg class="w-4 h-4 text-amber-400 shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
                    </svg>
                    <span>Krittrin.j@gmail.com</span>
                    <span class="text-[10px] px-1.5 py-0.5 rounded bg-slate-700 text-slate-300 group-hover:bg-amber-600 group-hover:text-white transition-colors" data-i18n="copy_badge">Copy</span>
                </button>

                <button type="button" onclick="copyText('064-656-3456')" class="inline-flex items-center gap-2 px-3.5 py-2 rounded-lg bg-slate-800/80 hover:bg-slate-800 border border-slate-700 text-xs sm:text-sm text-slate-200 transition-colors group">
                    <svg class="w-4 h-4 text-amber-400 shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path>
                    </svg>
                    <span>064-656-3456</span>
                    <span class="text-[10px] px-1.5 py-0.5 rounded bg-slate-700 text-slate-300 group-hover:bg-amber-600 group-hover:text-white transition-colors" data-i18n="copy_badge">Copy</span>
                </button>
            </div>

            <!-- Primary CTA Buttons -->
            <div class="flex flex-col sm:flex-row items-stretch sm:items-center gap-3">
                <button type="button" onclick="openResumeModal()" class="px-6 py-3.5 rounded-xl bg-amber-600 hover:bg-amber-500 text-white font-bold text-sm shadow-lg shadow-amber-950/30 flex items-center justify-center gap-2.5 transition-all active:scale-[0.99]">
                    <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path>
                    </svg>
                    <span data-i18n="cta_resume_full">ดูเรซูเม่ฉบับเต็ม / บันทึก PDF</span>
                </button>

                <button type="button" onclick="openContactModal()" class="px-6 py-3.5 rounded-xl bg-white hover:bg-slate-100 text-navyDark font-bold text-sm shadow-sm flex items-center justify-center gap-2.5 transition-all active:scale-[0.99]">
                    <svg class="w-4 h-4 text-execGold" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z"></path>
                    </svg>
                    <span data-i18n="cta_contact">ติดต่อฉัน</span>
                </button>
            </div>
        </div>
    </section>

    <!-- ==========================================
         MAIN PORTFOLIO CONTENT
    =========================================== -->
    <main class="max-w-5xl mx-auto px-4 sm:px-6 py-10 sm:py-12 space-y-12 no-print">

        <!-- ==========================================
             3. KEY ACHIEVEMENTS HIGHLIGHT STRIP
        =========================================== -->
        <section id="achievements" class="scroll-mt-24">
            <div class="flex items-center gap-2.5 mb-4">
                <span class="w-1.5 h-5 rounded-full bg-execGold"></span>
                <h2 class="text-sm sm:text-base font-extrabold uppercase tracking-wider text-navyDark" data-i18n="sec_achievements">
                    Key Achievements · ผลงานสำคัญที่โดดเด่น
                </h2>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                <!-- Card 1: 99.98% -->
                <div class="bg-white rounded-2xl border border-slateBorder border-t-4 border-t-amber-600 p-5 sm:p-6 shadow-exec hover:shadow-exec-hover transition-shadow">
                    <div class="flex items-baseline justify-between mb-2">
                        <span class="text-2xl sm:text-3xl font-extrabold text-navyDark tracking-tight">99.98%</span>
                        <span class="text-[11px] font-bold uppercase tracking-wider px-2.5 py-0.5 rounded bg-amber-50 text-execGold border border-amber-200/70">2025 Audit</span>
                    </div>
                    <p class="text-xs sm:text-[13.5px] text-slateText leading-relaxed" data-i18n="ach_1">
                        สร้างความแม่นยำของสินค้าคงเหลือได้ถึง 99.98% ในการตรวจนับประจำปี 2025 โดยเป็นผู้นำกระบวนการทั้งหมดตั้งแต่การระงับรายการเคลื่อนไหว (Transaction Freezing) การควบคุมการตรวจนับ ไปจนถึงการตรวจสอบหาสาเหตุผลต่างและการปรับปรุงยอดสต็อกขั้นสุดท้าย
                    </p>
                </div>

                <!-- Card 2: ~1,400 / mo -->
                <div class="bg-white rounded-2xl border border-slateBorder border-t-4 border-t-navyDark p-5 sm:p-6 shadow-exec hover:shadow-exec-hover transition-shadow">
                    <div class="flex items-baseline justify-between mb-2">
                        <span class="text-2xl sm:text-3xl font-extrabold text-navyDark tracking-tight">~1,400 <span class="text-base font-bold text-slateMuted">/ mo</span></span>
                        <span class="text-[11px] font-bold uppercase tracking-wider px-2.5 py-0.5 rounded bg-slate-100 text-navyMid border border-slate-200">Oracle EBS R12</span>
                    </div>
                    <p class="text-xs sm:text-[13.5px] text-slateText leading-relaxed" data-i18n="ach_2">
                        ตรวจสอบและปิดใบสั่งผลิต (Manufacturing Work Orders) ประมาณ 1,400 ใบต่อเดือน ทำให้มั่นใจได้ถึงการกระทบยอดงานระหว่างทำ (WIP Reconciliation) ที่ตรงเวลาและการบันทึกต้นทุนในระบบ Oracle EBS R12 อย่างถูกต้องแม่นยำ
                    </p>
                </div>

                <!-- Card 3: THB 200M+ -->
                <div class="bg-white rounded-2xl border border-slateBorder border-t-4 border-t-corpBlue p-5 sm:p-6 shadow-exec hover:shadow-exec-hover transition-shadow">
                    <div class="flex items-baseline justify-between mb-2">
                        <span class="text-2xl sm:text-3xl font-extrabold text-navyDark tracking-tight">THB 200M+</span>
                        <span class="text-[11px] font-bold uppercase tracking-wider px-2.5 py-0.5 rounded bg-blue-50 text-corpBlue border border-blue-200/70">GL Reconciliation</span>
                    </div>
                    <p class="text-xs sm:text-[13.5px] text-slateText leading-relaxed" data-i18n="ach_3">
                        บริหารจัดการและกระทบยอดบัญชีแยกประเภททั่วไปที่เกี่ยวข้องกับสินค้าคงเหลือมูลค่ามากกว่า 200 ล้านบาท เพื่อให้ยอดคงเหลือระหว่างบัญชีย่อยสินค้าคงเหลือ (Inventory Subledger) และงบทดลอง (Trial Balance) ตรงกันอย่างครบถ้วน
                    </p>
                </div>
            </div>
        </section>

        <!-- ==========================================
             4. PROFESSIONAL SUMMARY SECTION
        =========================================== -->
        <section id="summary" class="scroll-mt-24">
            <div class="bg-white rounded-2xl border border-slateBorder p-6 sm:p-8 shadow-exec">
                <div class="flex items-center gap-2.5 mb-3.5">
                    <span class="w-1.5 h-5 rounded-full bg-navyDark"></span>
                    <h2 class="text-sm sm:text-base font-extrabold uppercase tracking-wider text-navyDark" data-i18n="sec_summary">
                        Professional Summary · บทสรุปผู้บริหารและประสบการณ์วิชาชีพ
                    </h2>
                </div>
                <p class="text-sm sm:text-[15px] text-slateText leading-relaxed" data-i18n="summary_text">
                    นักบัญชีต้นทุนที่มุ่งเน้นผลลัพธ์ (Results-driven Cost Accountant) มีประสบการณ์ด้านบัญชีต้นทุนการผลิต การกระทบยอดงานระหว่างทำ (WIP) และสินค้าคงเหลือ การควบคุมใบสั่งผลิต (Work Order Control) ระบบต้นทุนมาตรฐาน (Standard Costing) และการวิเคราะห์ผลต่าง (Variance Analysis) ในระบบ Oracle EBS รับผิดชอบการตรวจสอบและปิดใบสั่งผลิตประมาณ 1,400 ใบต่อเดือน กระทบยอดสินค้าคงเหลือมูลค่ามากกว่า 200 ล้านบาท และจัดทำรายงานวิเคราะห์ผลต่าง MUV และ IPV เพื่อระบุสาเหตุที่แท้จริง ขับเคลื่อนการทำงานร่วมกันข้ามสายงาน (Cross-functional Collaboration) อย่างมีประสิทธิภาพกับฝ่ายผลิต ฝ่ายจัดซื้อ และฝ่ายจัดหา เพื่อประสานการแก้ไขและปรับปรุงกระบวนการทำงานให้คล่องตัว เป็นผู้นำกระบวนการตรวจนับสินค้าคงเหลือประจำปี 2025 จนบรรลุความแม่นยำ 99.98% เชี่ยวชาญการใช้ Microsoft Excel, Power Query และ PivotTables พร้อมประสบการณ์เพิ่มเติมด้านการปิดบัญชีสิ้นงวด การสนับสนุนการตรวจสอบบัญชี เจ้าหนี้การค้า (AP) และภาษีหัก ณ ที่จ่าย เป็นผู้ทำบัญชีขึ้นทะเบียนที่มีสถานะ CPD ปัจจุบัน
                </p>
            </div>
        </section>

        <!-- ==========================================
             5. PROFESSIONAL EXPERIENCE SECTION (ALL 21 BULLETS)
        =========================================== -->
        <section id="experience" class="scroll-mt-24">
            <div class="flex flex-wrap items-center justify-between gap-2 mb-5">
                <div class="flex items-center gap-2.5">
                    <span class="w-1.5 h-5 rounded-full bg-execGold"></span>
                    <h2 class="text-sm sm:text-base font-extrabold uppercase tracking-wider text-navyDark" data-i18n="sec_experience">
                        Professional Experience · ประสบการณ์การทำงานฉบับสมบูรณ์
                    </h2>
                </div>
                <button type="button" onclick="toggleAllSubsections()" id="toggle-all-btn" class="text-xs font-semibold text-corpBlue hover:text-navyDark px-3 py-1.5 rounded-lg bg-white border border-slateBorder shadow-2xs transition-colors" data-i18n="btn_collapse_all">
                    ย่อ/ขยายหมวดงานทั้งหมด
                </button>
            </div>

            <div class="space-y-8">
                <!-- ==========================================
                     ROLE 1: HACH (THAILAND) LIMITED
                =========================================== -->
                <article class="bg-white rounded-2xl border border-slateBorder shadow-exec overflow-hidden">
                    <!-- Role 1 Header -->
                    <div class="bg-slate-50/90 border-b border-slateBorder p-5 sm:p-7 flex flex-col sm:flex-row sm:items-center justify-between gap-3">
                        <div>
                            <div class="flex flex-wrap items-center gap-2 mb-1">
                                <h3 class="text-lg sm:text-xl font-extrabold text-navyDark">Hach (Thailand) Limited</h3>
                                <span class="px-2.5 py-0.5 rounded-md bg-navyDark text-amber-400 text-[11px] font-bold">2024 – Present</span>
                            </div>
                            <p class="text-sm sm:text-base font-bold text-execGold">Cost Accountant</p>
                        </div>
                        <div class="inline-flex items-center gap-2 px-3.5 py-2 rounded-xl bg-white border border-slateBorder text-xs font-semibold text-navyMid self-start sm:self-center">
                            <span class="text-slateMuted">System:</span>
                            <span>Oracle E-Business Suite (Oracle EBS)</span>
                        </div>
                    </div>

                    <!-- Role 1 Sub-categories (4 Sub-categories, 16 Bullets) -->
                    <div class="p-5 sm:p-7 space-y-5">
                        <!-- Sub-category 1.1: Cost Accounting & Variance Analysis (4 bullets) -->
                        <div class="rounded-xl border border-slateBorder overflow-hidden">
                            <button type="button" onclick="toggleExpGroup(this)" class="w-full px-4 py-3.5 bg-slate-50 hover:bg-slate-100/80 flex items-center justify-between gap-2 text-left transition-colors">
                                <div class="flex items-center gap-2.5">
                                    <span class="w-2 h-2 rounded-full bg-amber-600 shrink-0"></span>
                                    <h4 class="text-xs sm:text-sm font-bold text-navyDark" data-i18n="hach_sub1_title">
                                        Cost Accounting &amp; Variance Analysis (การบัญชีต้นทุนและการวิเคราะห์ผลต่าง)
                                    </h4>
                                </div>
                                <span class="text-xs font-semibold text-slateMuted shrink-0">4 items ▾</span>
                            </button>
                            <div class="accordion-content">
                                <div class="accordion-inner">
                                    <ul class="p-4 sm:p-5 space-y-2.5 text-xs sm:text-[13.5px] text-slateText leading-relaxed list-disc pl-8 bg-white">
                                        <li data-i18n="hach_1_1">ติดตามรายการเคลื่อนไหวของงานระหว่างทำ (WIP transactions) และดำเนินการกระทบยอดรายสัปดาห์และสิ้นเดือนระหว่างรายงาน WIP กับงบทดลอง (Trial Balance)</li>
                                        <li data-i18n="hach_1_2">ตรวจสอบและปิดใบสั่งผลิต (Manufacturing Work Orders) ประมาณ 1,400 ใบต่อเดือน รวมถึงการตรวจสอบความถูกต้องของปริมาณวัตถุดิบที่ต้องใช้และที่เบิกจ่ายจริงก่อนปิดงาน</li>
                                        <li data-i18n="hach_1_3">จัดทำรายงานผลต่าง MUV และ IPV รายสัปดาห์และรายเดือน วิเคราะห์หาสาเหตุที่แท้จริง (Root Causes) และประสานงานแนวทางแก้ไขร่วมกับฝ่ายผลิต ฝ่ายจัดซื้อ และฝ่ายจัดหา</li>
                                        <li data-i18n="hach_1_4">อัปเดตต้นทุนมาตรฐาน (Standard Costs) สำหรับวัตถุดิบและสินค้าสำเร็จรูป พร้อมตรวจสอบโครงสร้างสูตรการผลิต (BOM components) เพื่อระบุปัญหาด้านต้นทุนหรือข้อมูลหลัก (Master Data)</li>
                                    </ul>
                                </div>
                            </div>
                        </div>

                        <!-- Sub-category 1.2: Inventory Control, Physical Count & GL Reconciliation (6 bullets) -->
                        <div class="rounded-xl border border-slateBorder overflow-hidden">
                            <button type="button" onclick="toggleExpGroup(this)" class="w-full px-4 py-3.5 bg-slate-50 hover:bg-slate-100/80 flex items-center justify-between gap-2 text-left transition-colors">
                                <div class="flex items-center gap-2.5">
                                    <span class="w-2 h-2 rounded-full bg-navyDark shrink-0"></span>
                                    <h4 class="text-xs sm:text-sm font-bold text-navyDark" data-i18n="hach_sub2_title">
                                        Inventory Control, Physical Count &amp; GL Reconciliation (การควบคุมสินค้าคงเหลือ การตรวจนับ และการกระทบยอด GL)
                                    </h4>
                                </div>
                                <span class="text-xs font-semibold text-slateMuted shrink-0">6 items ▾</span>
                            </button>
                            <div class="accordion-content">
                                <div class="accordion-inner">
                                    <ul class="p-4 sm:p-5 space-y-2.5 text-xs sm:text-[13.5px] text-slateText leading-relaxed list-disc pl-8 bg-white">
                                        <li data-i18n="hach_2_1">บริหารจัดการบัญชีแยกประเภททั่วไปที่เกี่ยวข้องกับสินค้าคงเหลือมูลค่ามากกว่า 200 ล้านบาท และกระทบยอดบัญชีย่อยสินค้าคงเหลือ (Inventory Subledger) กับงบทดลองเป็นประจำทุกเดือน</li>
                                        <li data-i18n="hach_2_2">เป็นผู้นำกระบวนการตรวจนับสินค้าคงเหลือทั้งหมด ตั้งแต่การระงับรายการเคลื่อนไหว (Transaction Freezing) การดำเนินการตรวจนับ การตรวจสอบหาสาเหตุผลต่าง ไปจนถึงการปรับปรุงสต็อกขั้นสุดท้าย โดยสร้างความแม่นยำได้ถึง 99.98% ในปี 2025</li>
                                        <li data-i18n="hach_2_3">ตรวจสอบรายงานสินค้าคงเหลือประจำวัน (Daily Inventory On-hand Reports) เพื่อระบุรายการยอดติดลบ รายการที่ขาดต้นทุนต่อหน่วย และรายการเคลื่อนไหวที่ผิดปกติ พร้อมประสานงานแก้ไขอย่างทันท่วงที</li>
                                        <li data-i18n="hach_2_4">จัดทำรายงานอายุสินค้าคงเหลือ (Inventory Aging) และรายงานของเสียรายเดือน (Monthly Scrap Reports) วิเคราะห์หาสาเหตุที่แท้จริง และประสานแผนการปรับปรุงร่วมกับหน่วยงานที่รับผิดชอบ</li>
                                        <li data-i18n="hach_2_5">ประสานงานการตรวจนับและการทำลายของเสีย (Scrap Counting and Destruction) ร่วมกับผู้สอบบัญชีภายนอก (External Auditors) และเจ้าหน้าที่กรมสรรพากรในพื้นที่ให้เป็นไปตามระบบการควบคุมภายใน</li>
                                        <li data-i18n="hach_2_6">จัดทำทะเบียนคุมการปรับปรุงสินค้าคงเหลือ (Inventory Adjustment Logs) กำหนดเลขที่อ้างอิงการปรับปรุง และกำหนดรหัสบัญชี (COA Classifications) ที่เหมาะสม</li>
                                    </ul>
                                </div>
                            </div>
                        </div>

                        <!-- Sub-category 1.3: Accounts Payable & Tax Compliance (3 bullets) -->
                        <div class="rounded-xl border border-slateBorder overflow-hidden">
                            <button type="button" onclick="toggleExpGroup(this)" class="w-full px-4 py-3.5 bg-slate-50 hover:bg-slate-100/80 flex items-center justify-between gap-2 text-left transition-colors">
                                <div class="flex items-center gap-2.5">
                                    <span class="w-2 h-2 rounded-full bg-corpBlue shrink-0"></span>
                                    <h4 class="text-xs sm:text-sm font-bold text-navyDark" data-i18n="hach_sub3_title">
                                        Accounts Payable &amp; Tax Compliance (เจ้าหนี้การค้าและการปฏิบัติตามกฎหมายภาษี)
                                    </h4>
                                </div>
                                <span class="text-xs font-semibold text-slateMuted shrink-0">3 items ▾</span>
                            </button>
                            <div class="accordion-content">
                                <div class="accordion-inner">
                                    <ul class="p-4 sm:p-5 space-y-2.5 text-xs sm:text-[13.5px] text-slateText leading-relaxed list-disc pl-8 bg-white">
                                        <li data-i18n="hach_3_1">ตรวจสอบและบันทึกบัญชีใบแจ้งหนี้ในประเทศ ต่างประเทศ บริษัทในเครือ (Intercompany) และค่าขนส่ง (Freight) ในสกุลเงิน THB, USD และ EUR โดยใช้ระบบตรวจสอบ 3 ทาง (Three-way matching: PO, GR และ Invoice) เพื่อความถูกต้องและสอดคล้องตามระเบียบ</li>
                                        <li data-i18n="hach_3_2">ตรวจสอบรายงานการรับสินค้า (Goods Receipt - GR) เทียบกับใบสั่งซื้อ (PO) และใบแจ้งหนี้ที่บันทึกไว้ เพื่อยืนยันความถูกต้องของการรับของและสนับสนุนกระบวนการ Three-way matching</li>
                                        <li data-i18n="hach_3_3">กระทบยอดภาษีซื้อและภาษีขายประจำเดือน (ภ.พ.30) กับบัญชีแยกประเภททั่วไป และจัดทำแบบแสดงรายการภาษีหัก ณ ที่จ่าย (ภ.ง.ด.3, ภ.ง.ด.53) รวมถึงออกหนังสือรับรองการหักภาษี ณ ที่จ่าย (50 ทวิ) เพื่อให้ถูกต้องตามกฎหมายภาษีและยื่นแบบตรงเวลา</li>
                                    </ul>
                                </div>
                            </div>
                        </div>

                        <!-- Sub-category 1.4: Month-End Closing, Process Improvement & Audit Readiness (3 bullets) -->
                        <div class="rounded-xl border border-slateBorder overflow-hidden">
                            <button type="button" onclick="toggleExpGroup(this)" class="w-full px-4 py-3.5 bg-slate-50 hover:bg-slate-100/80 flex items-center justify-between gap-2 text-left transition-colors">
                                <div class="flex items-center gap-2.5">
                                    <span class="w-2 h-2 rounded-full bg-emerald-600 shrink-0"></span>
                                    <h4 class="text-xs sm:text-sm font-bold text-navyDark" data-i18n="hach_sub4_title">
                                        Month-End Closing, Process Improvement &amp; Audit Readiness (การปิดบัญชีสิ้นงวด การพัฒนากระบวนการ และความพร้อมรับการตรวจสอบ)
                                    </h4>
                                </div>
                                <span class="text-xs font-semibold text-slateMuted shrink-0">3 items ▾</span>
                            </button>
                            <div class="accordion-content">
                                <div class="accordion-inner">
                                    <ul class="p-4 sm:p-5 space-y-2.5 text-xs sm:text-[13.5px] text-slateText leading-relaxed list-disc pl-8 bg-white">
                                        <li data-i18n="hach_4_1">สนับสนุนการปิดบัญชีรายเดือน รายไตรมาส และประจำปี พร้อมจัดเตรียมข้อมูลด้านต้นทุนและสินค้าคงเหลือสำหรับการตรวจสอบภายในและภายนอก (Internal and External Audits)</li>
                                        <li data-i18n="hach_4_2">ปรับปรุงขั้นตอนการปฏิบัติงานและจัดทำมาตรฐานคู่มือการปฏิบัติงานบัญชี (Accounting Work Instructions) เพิ่มประสิทธิภาพการเตรียมข้อมูลและการกระทบยอดเพื่อลดระยะเวลาปิดบัญชีและเพิ่มประสิทธิภาพของทีม</li>
                                        <li data-i18n="hach_4_3">จัดระเบียบและแยกหมวดหมู่แฟ้มเอกสารตัวจริงและไฟล์ข้อมูลดิจิทัลบน Shared Drive และ OneDrive ให้เป็นระบบการจัดเก็บที่มีโครงสร้างชัดเจน เพื่อรักษาร่องรอยการตรวจสอบ (Audit Trails) และสืบค้นข้อมูลย้อนหลังได้อย่างรวดเร็ว</li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                </article>

                <!-- ==========================================
                     ROLE 2: VP REAL ESTATE PROPERTY DEVELOPMENT CO., LTD.
                =========================================== -->
                <article class="bg-white rounded-2xl border border-slateBorder shadow-exec overflow-hidden">
                    <!-- Role 2 Header -->
                    <div class="bg-slate-50/90 border-b border-slateBorder p-5 sm:p-7 flex flex-col sm:flex-row sm:items-center justify-between gap-3">
                        <div>
                            <div class="flex flex-wrap items-center gap-2 mb-1">
                                <h3 class="text-lg sm:text-xl font-extrabold text-navyDark">VP Real Estate Property Development Co., Ltd.</h3>
                                <span class="px-2.5 py-0.5 rounded-md bg-slate-200 text-navyDark text-[11px] font-bold">2021 – 2024</span>
                            </div>
                            <p class="text-sm sm:text-base font-bold text-slateText">Accounts Payable Accountant</p>
                        </div>
                        <div class="inline-flex items-center gap-2 px-3.5 py-2 rounded-xl bg-white border border-slateBorder text-xs font-semibold text-navyMid self-start sm:self-center">
                            <span class="text-slateMuted">System:</span>
                            <span>Express Accounting Software</span>
                        </div>
                    </div>

                    <!-- Role 2 Sub-categories (3 Sub-categories, 7 Bullets) -->
                    <div class="p-5 sm:p-7 space-y-5">
                        <!-- Sub-category 2.1: Accounts Payable, Project Coordination & Cash Management (3 bullets) -->
                        <div class="rounded-xl border border-slateBorder overflow-hidden">
                            <button type="button" onclick="toggleExpGroup(this)" class="w-full px-4 py-3.5 bg-slate-50 hover:bg-slate-100/80 flex items-center justify-between gap-2 text-left transition-colors">
                                <div class="flex items-center gap-2.5">
                                    <span class="w-2 h-2 rounded-full bg-amber-600 shrink-0"></span>
                                    <h4 class="text-xs sm:text-sm font-bold text-navyDark" data-i18n="vp_sub1_title">
                                        Accounts Payable, Project Coordination &amp; Cash Management (เจ้าหนี้การค้า การประสานงานโครงการ และการบริหารเงินสด)
                                    </h4>
                                </div>
                                <span class="text-xs font-semibold text-slateMuted shrink-0">3 items ▾</span>
                            </button>
                            <div class="accordion-content">
                                <div class="accordion-inner">
                                    <ul class="p-4 sm:p-5 space-y-2.5 text-xs sm:text-[13.5px] text-slateText leading-relaxed list-disc pl-8 bg-white">
                                        <li data-i18n="vp_1_1">ตรวจสอบและบันทึกบัญชีใบแจ้งหนี้ซัพพลายเออร์ในประเทศประมาณ 100 รายการต่อเดือน โดยตรวจสอบความครบถ้วนของเอกสารประกอบ การจัดหมวดหมู่บัญชีที่ถูกต้อง และการอนุมัติตามระเบียบ</li>
                                        <li data-i18n="vp_1_2">ประสานงานกับโฟร์แมนประจำโครงการ (Project Foremen) เพื่อติดตามความคืบหน้างานก่อสร้างและงวดการจ่ายเงินตามสัญญาโครงการ</li>
                                        <li data-i18n="vp_1_3">บริหารจัดการการเบิกจ่ายเงินสดย่อย (Petty Cash Disbursements) และดำเนินการกระทบยอดบัญชีเงินฝากธนาคาร (Bank Reconciliations)</li>
                                    </ul>
                                </div>
                            </div>
                        </div>

                        <!-- Sub-category 2.2: Tax Compliance & Filing (2 bullets) -->
                        <div class="rounded-xl border border-slateBorder overflow-hidden">
                            <button type="button" onclick="toggleExpGroup(this)" class="w-full px-4 py-3.5 bg-slate-50 hover:bg-slate-100/80 flex items-center justify-between gap-2 text-left transition-colors">
                                <div class="flex items-center gap-2.5">
                                    <span class="w-2 h-2 rounded-full bg-corpBlue shrink-0"></span>
                                    <h4 class="text-xs sm:text-sm font-bold text-navyDark" data-i18n="vp_sub2_title">
                                        Tax Compliance &amp; Filing (การปฏิบัติตามกฎหมายภาษีและการยื่นแบบ)
                                    </h4>
                                </div>
                                <span class="text-xs font-semibold text-slateMuted shrink-0">2 items ▾</span>
                            </button>
                            <div class="accordion-content">
                                <div class="accordion-inner">
                                    <ul class="p-4 sm:p-5 space-y-2.5 text-xs sm:text-[13.5px] text-slateText leading-relaxed list-disc pl-8 bg-white">
                                        <li data-i18n="vp_2_1">จัดทำแบบแสดงรายการภาษีหัก ณ ที่จ่ายประจำเดือน (ภ.ง.ด.1, ภ.ง.ด.3 และ ภ.ง.ด.53) เพื่อให้มั่นใจในความถูกต้องตามกฎหมายภาษีและการยื่นแบบตรงเวลา</li>
                                        <li data-i18n="vp_2_2">จัดทำหนังสือรับรองการหักภาษี ณ ที่จ่าย และประสานงานด้านภาษีกับเจ้าหน้าที่กรมสรรพากรและหน่วยงานภายนอก</li>
                                    </ul>
                                </div>
                            </div>
                        </div>

                        <!-- Sub-category 2.3: Inventory Control & Month-End Closing (2 bullets) -->
                        <div class="rounded-xl border border-slateBorder overflow-hidden">
                            <button type="button" onclick="toggleExpGroup(this)" class="w-full px-4 py-3.5 bg-slate-50 hover:bg-slate-100/80 flex items-center justify-between gap-2 text-left transition-colors">
                                <div class="flex items-center gap-2.5">
                                    <span class="w-2 h-2 rounded-full bg-emerald-600 shrink-0"></span>
                                    <h4 class="text-xs sm:text-sm font-bold text-navyDark" data-i18n="vp_sub3_title">
                                        Inventory Control &amp; Month-End Closing (การควบคุมสินค้าคงเหลือและการปิดบัญชีสิ้นงวด)
                                    </h4>
                                </div>
                                <span class="text-xs font-semibold text-slateMuted shrink-0">2 items ▾</span>
                            </button>
                            <div class="accordion-content">
                                <div class="accordion-inner">
                                    <ul class="p-4 sm:p-5 space-y-2.5 text-xs sm:text-[13.5px] text-slateText leading-relaxed list-disc pl-8 bg-white">
                                        <li data-i18n="vp_3_1">ดำเนินการตรวจนับสินค้าคงเหลือจริง (Physical Inventory Counts) กระทบยอดการใช้วัสดุเทียบกับข้อมูลในระบบ และจัดทำรายการปรับปรุงสต็อกที่จำเป็น</li>
                                        <li data-i18n="vp_3_2">สนับสนุนการปิดบัญชีสิ้นเดือน และจัดเตรียมตารางรายละเอียดประกอบงบการเงิน (Accounting Schedules) รวมถึงเอกสารประกอบสำหรับสำนักงานบัญชีภายนอก</li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                </article>
            </div>
        </section>

        <!-- ==========================================
             6. TECHNICAL SKILLS MATRIX (ALL 22 ITEMS)
        =========================================== -->
        <section id="skills" class="scroll-mt-24">
            <div class="flex items-center gap-2.5 mb-5">
                <span class="w-1.5 h-5 rounded-full bg-navyDark"></span>
                <h2 class="text-sm sm:text-base font-extrabold uppercase tracking-wider text-navyDark" data-i18n="sec_skills">
                    Technical Skills Matrix · ทักษะทางวิชาชีพและระบบงาน (ครบทั้ง 22 รายการ)
                </h2>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-3 gap-5">
                <!-- Category 1: ERP and Accounting Systems (5 items) -->
                <div class="bg-white rounded-2xl border border-slateBorder p-5 sm:p-6 shadow-exec flex flex-col">
                    <div class="flex items-center gap-2.5 pb-3.5 mb-4 border-b border-slateBorder">
                        <div class="w-8 h-8 rounded-lg bg-navyDark text-amber-400 flex items-center justify-center font-bold text-xs shrink-0">ERP</div>
                        <h3 class="text-sm font-extrabold text-navyDark">ERP and Accounting Systems</h3>
                    </div>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">Oracle ERP</span>
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">Work Order and Inventory Transaction Review</span>
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">General Ledger Reconciliation</span>
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">Accounts Payable Processing</span>
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">Three-Way Matching</span>
                    </div>
                </div>

                <!-- Category 2: Microsoft Excel and Data Analysis (7 items) -->
                <div class="bg-white rounded-2xl border border-slateBorder p-5 sm:p-6 shadow-exec flex flex-col">
                    <div class="flex items-center gap-2.5 pb-3.5 mb-4 border-b border-slateBorder">
                        <div class="w-8 h-8 rounded-lg bg-emerald-900 text-emerald-200 flex items-center justify-center font-bold text-xs shrink-0">XLS</div>
                        <h3 class="text-sm font-extrabold text-navyDark">Microsoft Excel and Data Analysis</h3>
                    </div>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">Microsoft Excel</span>
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">Power Query</span>
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">PivotTables and PivotCharts</span>
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">XLOOKUP and VLOOKUP</span>
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">Data Reconciliation and Validation</span>
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">Cost and Variance Analysis</span>
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">Inventory and WIP Analysis</span>
                    </div>
                </div>

                <!-- Category 3: Accounting and Costing (10 items) -->
                <div class="bg-white rounded-2xl border border-slateBorder p-5 sm:p-6 shadow-exec flex flex-col">
                    <div class="flex items-center gap-2.5 pb-3.5 mb-4 border-b border-slateBorder">
                        <div class="w-8 h-8 rounded-lg bg-amber-700 text-amber-100 flex items-center justify-center font-bold text-xs shrink-0">ACC</div>
                        <h3 class="text-sm font-extrabold text-navyDark">Accounting and Costing</h3>
                    </div>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">Manufacturing Cost Accounting</span>
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">Standard Costing</span>
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">MUV and IPV Analysis</span>
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">WIP Reconciliation</span>
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">Inventory Reconciliation</span>
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">Physical Inventory</span>
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">Inventory Aging</span>
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">Scrap Analysis</span>
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">Month-End Closing</span>
                        <span class="px-3 py-1.5 rounded-lg bg-slate-50 border border-slate-200 text-xs font-semibold text-navyMid">Withholding Tax</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==========================================
             7. EDUCATION, QUALIFICATION, TRAINING & LANGUAGES GRID
        =========================================== -->
        <section id="qualifications" class="scroll-mt-24">
            <div class="flex items-center gap-2.5 mb-5">
                <span class="w-1.5 h-5 rounded-full bg-execGold"></span>
                <h2 class="text-sm sm:text-base font-extrabold uppercase tracking-wider text-navyDark" data-i18n="sec_qual">
                    Education, Qualification, Training &amp; Languages · การศึกษา คุณวุฒิ การอบรม และภาษา
                </h2>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-5">
                <!-- Education -->
                <div class="bg-white rounded-2xl border border-slateBorder p-5 sm:p-6 shadow-exec">
                    <p class="text-[11px] font-extrabold uppercase tracking-wider text-execGold mb-2">Education · การศึกษา</p>
                    <h3 class="text-sm sm:text-base font-extrabold text-navyDark">
                        Bachelor of Business Administration (B.B.A.), Accounting
                    </h3>
                    <p class="text-xs sm:text-sm font-semibold text-slateText mt-1">
                        King Mongkut's University of Technology North Bangkok
                    </p>
                    <span class="inline-block mt-2.5 px-2.5 py-0.5 rounded bg-slate-100 text-navyMid text-xs font-bold">
                        2017 – 2021
                    </span>
                </div>

                <!-- Professional Qualification -->
                <div class="bg-white rounded-2xl border border-slateBorder p-5 sm:p-6 shadow-exec">
                    <p class="text-[11px] font-extrabold uppercase tracking-wider text-execGold mb-2">Professional Qualification · คุณวุฒิวิชาชีพ</p>
                    <div class="flex items-start gap-3">
                        <div class="w-10 h-10 rounded-xl bg-navyDark text-amber-400 flex items-center justify-center font-extrabold text-xs shrink-0">
                            CPD
                        </div>
                        <div>
                            <h3 class="text-sm sm:text-base font-extrabold text-navyDark">
                                Registered Accountant | Active CPD Status
                            </h3>
                            <p class="text-xs sm:text-sm text-slateText mt-1" data-i18n="qual_desc">
                                ผู้ทำบัญชีขึ้นทะเบียนถูกต้องตามกฎหมาย พร้อมสถานะการพัฒนาความรู้ต่อเนื่องทางวิชาชีพ (CPD) ปัจจุบัน
                            </p>
                        </div>
                    </div>
                </div>

                <!-- Professional Training -->
                <div class="bg-white rounded-2xl border border-slateBorder p-5 sm:p-6 shadow-exec">
                    <p class="text-[11px] font-extrabold uppercase tracking-wider text-execGold mb-2.5">Professional Training · การอบรมวิชาชีพ</p>
                    <ul class="space-y-2.5 text-xs sm:text-sm text-slateText">
                        <li class="flex items-start justify-between gap-2 p-2.5 rounded-xl bg-slate-50 border border-slate-200/80">
                            <span class="font-bold text-navyDark">Essential Cost Accounting Theory, DBD Academy</span>
                            <span class="px-2 py-0.5 rounded bg-amber-100 text-execGold font-bold text-xs shrink-0">2026</span>
                        </li>
                        <li class="flex items-start justify-between gap-2 p-2.5 rounded-xl bg-slate-50 border border-slate-200/80">
                            <span class="font-bold text-navyDark">Ethics for Accounting Professionals, DBD Academy</span>
                            <span class="px-2 py-0.5 rounded bg-amber-100 text-execGold font-bold text-xs shrink-0">2026</span>
                        </li>
                    </ul>
                </div>

                <!-- Languages -->
                <div class="bg-white rounded-2xl border border-slateBorder p-5 sm:p-6 shadow-exec">
                    <p class="text-[11px] font-extrabold uppercase tracking-wider text-execGold mb-2.5">Languages · ทักษะทางภาษา</p>
                    <div class="space-y-2.5 text-xs sm:text-sm">
                        <div class="p-2.5 rounded-xl bg-slate-50 border border-slate-200/80">
                            <span class="font-extrabold text-navyDark">Thai:</span>
                            <span class="text-slateText font-medium"> Native</span>
                        </div>
                        <div class="p-2.5 rounded-xl bg-slate-50 border border-slate-200/80">
                            <span class="font-extrabold text-navyDark">English:</span>
                            <span class="text-slateText font-medium"> Intermediate (Proficient in Business Email &amp; Documentation; Actively enhancing speaking fluency)</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Bottom Action Strip -->
        <section class="bg-navyDark text-white rounded-2xl p-6 sm:p-8 flex flex-col sm:flex-row items-center justify-between gap-4 shadow-exec">
            <div>
                <h3 class="text-base sm:text-lg font-extrabold text-white" data-i18n="footer_cta_title">
                    พร้อมร่วมงานและสร้างความแม่นยำให้กับระบบบัญชีต้นทุนและสินค้าคงเหลือขององค์กร
                </h3>
                <p class="text-xs sm:text-sm text-slate-300 mt-1">
                    Bangkok | Open to Relocation · Krittrin.j@gmail.com · 064-656-3456
                </p>
            </div>
            <div class="flex items-center gap-3 w-full sm:w-auto shrink-0">
                <button type="button" onclick="openResumeModal()" class="flex-1 sm:flex-initial px-5 py-3 rounded-xl bg-amber-600 hover:bg-amber-500 text-white text-xs sm:text-sm font-bold transition-colors">
                    <span data-i18n="nav_btn_pdf">Resume PDF</span>
                </button>
                <button type="button" onclick="openContactModal()" class="flex-1 sm:flex-initial px-5 py-3 rounded-xl bg-white hover:bg-slate-100 text-navyDark text-xs sm:text-sm font-bold transition-colors">
                    <span data-i18n="cta_contact">ติดต่อฉัน</span>
                </button>
            </div>
        </section>

        <footer class="text-center text-xs text-slateMuted pb-4">
            <p>© 2026 KRITTRIN JIRINWONG (กฤษตฤณ จิรินวงค์) · Cost Accountant | Senior Cost Accountant | Cost Controller</p>
        </footer>
    </main>

    <!-- ==========================================
         MODAL 1: CONTACT MODAL
    =========================================== -->
    <div id="contact-modal" class="fixed inset-0 z-50 hidden items-end sm:items-center justify-center p-0 sm:p-4 no-print">
        <div onclick="closeContactModal()" class="fixed inset-0 bg-navyDark/60 backdrop-blur-xs transition-opacity"></div>

        <div class="relative z-10 w-full max-w-md bg-white rounded-t-2xl sm:rounded-2xl p-6 shadow-2xl border border-slateBorder">
            <div class="w-10 h-1 bg-slate-300 rounded-full mx-auto mb-4 sm:hidden"></div>

            <div class="flex items-center justify-between pb-4 mb-4 border-b border-slateBorder">
                <div>
                    <h3 class="text-base sm:text-lg font-extrabold text-navyDark" data-i18n="contact_modal_title">ติดต่อ กฤษตฤณ จิรินวงค์</h3>
                    <p class="text-xs text-slateMuted" data-i18n="contact_modal_sub">คลิกปุ่มคัดลอกเพื่อนำข้อมูลไปติดต่อได้ทันที</p>
                </div>
                <button type="button" onclick="closeContactModal()" class="w-8 h-8 rounded-lg bg-slate-100 hover:bg-slate-200 flex items-center justify-center text-navyDark">
                    <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"></path>
                    </svg>
                </button>
            </div>

            <div class="space-y-3">
                <!-- Email -->
                <div class="p-3.5 rounded-xl bg-slate-50 border border-slateBorder flex items-center justify-between gap-2">
                    <div class="min-w-0">
                        <p class="text-[11px] font-bold uppercase tracking-wider text-slateMuted">Email</p>
                        <p class="text-sm font-bold text-navyDark truncate">Krittrin.j@gmail.com</p>
                    </div>
                    <button type="button" onclick="copyText('Krittrin.j@gmail.com')" class="px-3 py-1.5 rounded-lg bg-navyDark hover:bg-navyMid text-white text-xs font-bold shrink-0">
                        <span data-i18n="copy_badge">Copy</span>
                    </button>
                </div>

                <!-- Phone -->
                <div class="p-3.5 rounded-xl bg-slate-50 border border-slateBorder flex items-center justify-between gap-2">
                    <div>
                        <p class="text-[11px] font-bold uppercase tracking-wider text-slateMuted">Phone</p>
                        <a href="tel:0646563456" class="text-sm font-bold text-navyDark hover:underline">064-656-3456</a>
                    </div>
                    <button type="button" onclick="copyText('064-656-3456')" class="px-3 py-1.5 rounded-lg bg-navyDark hover:bg-navyMid text-white text-xs font-bold shrink-0">
                        <span data-i18n="copy_badge">Copy</span>
                    </button>
                </div>

                <!-- Location -->
                <div class="p-3.5 rounded-xl bg-slate-50 border border-slateBorder flex items-center justify-between gap-2">
                    <div>
                        <p class="text-[11px] font-bold uppercase tracking-wider text-slateMuted">Location</p>
                        <p class="text-sm font-bold text-navyDark">Bangkok | Open to Relocation</p>
                    </div>
                    <button type="button" onclick="copyText('Bangkok | Open to Relocation')" class="px-3 py-1.5 rounded-lg bg-navyDark hover:bg-navyMid text-white text-xs font-bold shrink-0">
                        <span data-i18n="copy_badge">Copy</span>
                    </button>
                </div>
            </div>

            <div class="mt-5 grid grid-cols-2 gap-2.5">
                <a href="mailto:Krittrin.j@gmail.com" class="py-2.5 px-4 rounded-xl bg-slate-100 hover:bg-slate-200 text-navyDark text-xs font-bold text-center">
                    Send Email
                </a>
                <a href="tel:0646563456" class="py-2.5 px-4 rounded-xl bg-amber-600 hover:bg-amber-500 text-white text-xs font-bold text-center">
                    Call 064-656-3456
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         MODAL 2: PRINTABLE A4 EXECUTIVE RESUME MODAL
         (100% Complete Two-Column Formal Resume)
    =========================================== -->
    <div id="resume-modal" class="fixed inset-0 z-50 hidden items-center justify-center p-2 sm:p-5 overflow-y-auto">
        <div onclick="closeResumeModal()" class="fixed inset-0 bg-navyDark/70 backdrop-blur-xs no-print"></div>

        <div class="relative z-10 w-full max-w-4xl bg-white rounded-2xl shadow-2xl overflow-hidden my-auto max-h-[94vh] flex flex-col border border-slateBorder">
            <!-- Modal Control Bar (Hidden on Print) -->
            <div class="no-print px-4 sm:px-6 py-3.5 bg-navyDark text-white flex items-center justify-between gap-2 shrink-0">
                <div class="flex items-center gap-2.5">
                    <span class="w-7 h-7 rounded-md bg-navyMid border border-amber-500 flex items-center justify-center text-xs font-bold text-amber-400">KJ</span>
                    <span class="text-xs sm:text-sm font-bold" data-i18n="resume_modal_header">Executive Resume Preview (A4 Print Ready)</span>
                </div>
                <div class="flex items-center gap-2">
                    <button type="button" onclick="window.print()" class="px-4 py-2 rounded-lg bg-amber-600 hover:bg-amber-500 text-white text-xs font-bold flex items-center gap-1.5 shadow-sm">
                        <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M17 17h2a2 2 0 002-2v-4a2 2 0 00-2-2H5a2 2 0 00-2 2v4a2 2 0 002 2h2m2 4h6a2 2 0 002-2v-4a2 2 0 00-2-2H9a2 2 0 00-2 2v4a2 2 0 002 2zm8-12V5a2 2 0 00-2-2H9a2 2 0 00-2 2v4h10z"></path>
                        </svg>
                        <span data-i18n="btn_print_pdf">Print / Save as PDF</span>
                    </button>
                    <button type="button" onclick="closeResumeModal()" class="w-8 h-8 rounded-lg bg-slate-800 hover:bg-slate-700 text-slate-200 flex items-center justify-center">
                        <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"></path>
                        </svg>
                    </button>
                </div>
            </div>

            <!-- Printable A4 Two-Column Formal Document -->
            <div id="resume-printable" class="p-6 sm:p-10 overflow-y-auto bg-white text-navyDark text-left">
                <!-- Top Executive Banner -->
                <div class="border-b-2 border-navyDark pb-4 mb-5 flex flex-col sm:flex-row sm:items-end justify-between gap-3">
                    <div>
                        <h1 class="text-2xl sm:text-3xl font-extrabold tracking-tight text-navyDark">KRITTRIN JIRINWONG</h1>
                        <p class="text-xs sm:text-sm font-bold text-execGold mt-0.5">Cost Accountant | Senior Cost Accountant | Cost Controller</p>
                    </div>
                    <div class="text-xs text-slateText sm:text-right space-y-0.5 font-medium">
                        <p>Bangkok | Open to Relocation</p>
                        <p>Krittrin.j@gmail.com | 064-656-3456</p>
                    </div>
                </div>

                <!-- Two-Column Layout -->
                <div class="grid grid-cols-1 md:grid-cols-12 gap-6">
                    <!-- LEFT SIDEBAR COLUMN (4 cols) -->
                    <div class="md:col-span-4 space-y-5 md:border-r md:border-slateBorder md:pr-5">
                        <!-- Contact -->
                        <div>
                            <h2 class="text-[11px] font-extrabold uppercase tracking-wider text-navyDark border-b border-slateBorder pb-1 mb-2">CONTACT</h2>
                            <ul class="text-xs text-slateText space-y-1">
                                <li>Bangkok | Open to Relocation</li>
                                <li>Krittrin.j@gmail.com</li>
                                <li>064-656-3456</li>
                            </ul>
                        </div>

                        <!-- Technical Skills (All 22 exact items) -->
                        <div>
                            <h2 class="text-[11px] font-extrabold uppercase tracking-wider text-navyDark border-b border-slateBorder pb-1 mb-2">TECHNICAL SKILLS</h2>
                            
                            <p class="text-[11px] font-bold text-execGold mt-2 mb-1">ERP and Accounting Systems</p>
                            <ul class="text-[11.5px] text-slateText space-y-0.5 list-disc pl-4">
                                <li>Oracle ERP</li>
                                <li>Work Order and Inventory Transaction Review</li>
                                <li>General Ledger Reconciliation</li>
                                <li>Accounts Payable Processing</li>
                                <li>Three-Way Matching</li>
                            </ul>

                            <p class="text-[11px] font-bold text-execGold mt-2.5 mb-1">Microsoft Excel and Data Analysis</p>
                            <ul class="text-[11.5px] text-slateText space-y-0.5 list-disc pl-4">
                                <li>Microsoft Excel</li>
                                <li>Power Query</li>
                                <li>PivotTables and PivotCharts</li>
                                <li>XLOOKUP and VLOOKUP</li>
                                <li>Data Reconciliation and Validation</li>
                                <li>Cost and Variance Analysis</li>
                                <li>Inventory and WIP Analysis</li>
                            </ul>

                            <p class="text-[11px] font-bold text-execGold mt-2.5 mb-1">Accounting and Costing</p>
                            <ul class="text-[11.5px] text-slateText space-y-0.5 list-disc pl-4">
                                <li>Manufacturing Cost Accounting</li>
                                <li>Standard Costing</li>
                                <li>MUV and IPV Analysis</li>
                                <li>WIP Reconciliation</li>
                                <li>Inventory Reconciliation</li>
                                <li>Physical Inventory</li>
                                <li>Inventory Aging</li>
                                <li>Scrap Analysis</li>
                                <li>Month-End Closing</li>
                                <li>Withholding Tax</li>
                            </ul>
                        </div>

                        <!-- Languages -->
                        <div>
                            <h2 class="text-[11px] font-extrabold uppercase tracking-wider text-navyDark border-b border-slateBorder pb-1 mb-2">LANGUAGES</h2>
                            <ul class="text-[11.5px] text-slateText space-y-1">
                                <li><strong>Thai:</strong> Native</li>
                                <li><strong>English:</strong> Intermediate (Proficient in Business Email &amp; Documentation; Actively enhancing speaking fluency)</li>
                            </ul>
                        </div>

                        <!-- Education -->
                        <div>
                            <h2 class="text-[11px] font-extrabold uppercase tracking-wider text-navyDark border-b border-slateBorder pb-1 mb-2">EDUCATION</h2>
                            <p class="text-[11.5px] font-bold text-navyDark">Bachelor of Business Administration (B.B.A.), Accounting</p>
                            <p class="text-[11.5px] text-slateText">2017–2021 | King Mongkut's University of Technology North Bangkok</p>
                        </div>

                        <!-- Professional Qualification -->
                        <div>
                            <h2 class="text-[11px] font-extrabold uppercase tracking-wider text-navyDark border-b border-slateBorder pb-1 mb-2">PROFESSIONAL QUALIFICATION</h2>
                            <p class="text-[11.5px] font-bold text-navyDark">Registered Accountant | Active CPD Status</p>
                        </div>

                        <!-- Professional Training -->
                        <div>
                            <h2 class="text-[11px] font-extrabold uppercase tracking-wider text-navyDark border-b border-slateBorder pb-1 mb-2">PROFESSIONAL TRAINING</h2>
                            <ul class="text-[11.5px] text-slateText space-y-1 list-disc pl-4">
                                <li>Essential Cost Accounting Theory, DBD Academy | 2026</li>
                                <li>Ethics for Accounting Professionals, DBD Academy | 2026</li>
                            </ul>
                        </div>
                    </div>

                    <!-- RIGHT MAIN COLUMN (8 cols) -->
                    <div class="md:col-span-8 space-y-5">
                        <!-- Professional Summary -->
                        <div>
                            <h2 class="text-[11px] font-extrabold uppercase tracking-wider text-navyDark border-b border-slateBorder pb-1 mb-2">PROFESSIONAL SUMMARY</h2>
                            <p class="text-[11.5px] text-slateText leading-relaxed">
                                Results-driven Cost Accountant with experience in manufacturing cost accounting, WIP and inventory reconciliation, work order control, standard costing, and variance analysis in Oracle EBS. Responsible for reviewing and closing approximately 1,400 manufacturing work orders per month, reconciling inventory balances exceeding THB 200 million, and performing MUV and IPV analyses to identify root causes. Drives effective Cross-functional Collaboration with Production, Purchasing, and Sourcing teams to coordinate corrective actions and streamline operations. Led the 2025 physical inventory process, achieving 99.98% inventory accuracy. Proficient in Microsoft Excel, Power Query, and PivotTables, with additional experience in month-end closing, audit support, AP, and withholding tax. Registered accountant with active CPD status.
                            </p>
                        </div>

                        <!-- Key Achievements -->
                        <div>
                            <h2 class="text-[11px] font-extrabold uppercase tracking-wider text-navyDark border-b border-slateBorder pb-1 mb-2">KEY ACHIEVEMENTS</h2>
                            <ul class="text-[11.5px] text-slateText space-y-1.5 list-disc pl-4 leading-relaxed">
                                <li>Achieved 99.98% inventory accuracy in the 2025 year-end physical inventory by leading the full process from transaction freezing and count execution to discrepancy resolution and final stock adjustments.</li>
                                <li>Reviewed and closed approximately 1,400 manufacturing work orders per month, ensuring timely WIP reconciliation and accurate cost posting in Oracle EBS R12.</li>
                                <li>Managed and reconciled inventory-related general ledger accounts exceeding THB 200 million, ensuring alignment between inventory subledger balances and the trial balance.</li>
                            </ul>
                        </div>

                        <!-- Professional Experience -->
                        <div>
                            <h2 class="text-[11px] font-extrabold uppercase tracking-wider text-navyDark border-b border-slateBorder pb-1 mb-2.5">PROFESSIONAL EXPERIENCE</h2>

                            <!-- Role 1 -->
                            <div class="mb-4">
                                <div class="flex flex-wrap justify-between items-baseline">
                                    <h3 class="text-xs font-extrabold text-navyDark">Hach (Thailand) Limited — Cost Accountant</h3>
                                    <span class="text-[11px] font-bold text-execGold">2024 – Present</span>
                                </div>
                                <p class="text-[11px] font-semibold text-slateMuted mb-1.5">System: Oracle E-Business Suite (Oracle EBS)</p>

                                <p class="text-[11px] font-bold text-navyMid mt-1.5">Cost Accounting &amp; Variance Analysis</p>
                                <ul class="text-[11px] text-slateText space-y-1 list-disc pl-4 leading-snug">
                                    <li>Monitor WIP transactions and perform weekly and month-end reconciliations between WIP reports and the trial balance.</li>
                                    <li>Review and close approximately 1,400 manufacturing work orders per month, including verification of required and issued material quantities before closure.</li>
                                    <li>Prepare weekly and monthly MUV and IPV reports, investigate root causes, and coordinate corrective actions with Production, Purchasing, and Sourcing teams.</li>
                                    <li>Update standard costs for raw materials and finished goods and review BOM components to identify costing or master-data issues.</li>
                                </ul>

                                <p class="text-[11px] font-bold text-navyMid mt-2">Inventory Control, Physical Count &amp; GL Reconciliation</p>
                                <ul class="text-[11px] text-slateText space-y-1 list-disc pl-4 leading-snug">
                                    <li>Manage inventory-related general ledger accounts exceeding THB 200 million and reconcile inventory subledger balances with the trial balance each month.</li>
                                    <li>Lead the full physical inventory process, from transaction freezing and count execution to discrepancy investigation and final stock adjustment, achieving 99.98% inventory accuracy in 2025.</li>
                                    <li>Review daily inventory on-hand reports to identify negative quantities, missing unit costs, and unusual transactions and coordinate timely corrections.</li>
                                    <li>Prepare inventory aging and monthly scrap reports, analyze root causes, and coordinate improvement actions with responsible departments.</li>
                                    <li>Coordinate scrap counting and destruction with external auditors and local Revenue Department officers in accordance with internal controls.</li>
                                    <li>Maintain inventory adjustment logs, assign adjustment reference numbers, and determine appropriate COA classifications.</li>
                                </ul>

                                <p class="text-[11px] font-bold text-navyMid mt-2">Accounts Payable &amp; Tax Compliance</p>
                                <ul class="text-[11px] text-slateText space-y-1 list-disc pl-4 leading-snug">
                                    <li>Review and record domestic, overseas, intercompany, and freight invoices in THB, USD, and EUR using three-way matching (PO, GR, and Invoice) to ensure accuracy and compliance.</li>
                                    <li>Review Goods Receipt (GR) reports against purchase orders (PO) and recorded invoices to verify receipt accuracy and support three-way matching.</li>
                                    <li>Reconcile monthly Input/Output VAT (P.P.30) with GL accounts and prepare Withholding Tax returns (P.N.D.3, P.N.D.53), including issuing 50 Tawi certificates, ensuring full tax compliance and timely filing.</li>
                                </ul>

                                <p class="text-[11px] font-bold text-navyMid mt-2">Month-End Closing, Process Improvement &amp; Audit Readiness</p>
                                <ul class="text-[11px] text-slateText space-y-1 list-disc pl-4 leading-snug">
                                    <li>Support monthly, quarterly, and annual closings and provide costing and inventory information for internal and external audits.</li>
                                    <li>Improve operational workflows and standardize Accounting Work Instructions, optimizing data preparation and reconciliation procedures to shorten closing timelines and enhance team efficiency.</li>
                                    <li>Organize and categorize physical files and digital records on Shared Drive and OneDrive into structured filing systems to maintain clear audit trails and enable fast historical retrieval.</li>
                                </ul>
                            </div>

                            <!-- Role 2 -->
                            <div>
                                <div class="flex flex-wrap justify-between items-baseline">
                                    <h3 class="text-xs font-extrabold text-navyDark">VP Real Estate Property Development Co., Ltd. — Accounts Payable Accountant</h3>
                                    <span class="text-[11px] font-bold text-slateMuted">2021 – 2024</span>
                                </div>
                                <p class="text-[11px] font-semibold text-slateMuted mb-1.5">System: Express Accounting Software</p>

                                <p class="text-[11px] font-bold text-navyMid mt-1.5">Accounts Payable, Project Coordination &amp; Cash Management</p>
                                <ul class="text-[11px] text-slateText space-y-1 list-disc pl-4 leading-snug">
                                    <li>Reviewed and recorded approximately 100 domestic supplier invoices per month, ensuring complete supporting documents, accurate account classification, and proper approvals.</li>
                                    <li>Coordinated with project foremen to monitor construction progress and payment milestones under project contracts.</li>
                                    <li>Managed petty cash disbursements and performed bank reconciliations.</li>
                                </ul>

                                <p class="text-[11px] font-bold text-navyMid mt-2">Tax Compliance &amp; Filing</p>
                                <ul class="text-[11px] text-slateText space-y-1 list-disc pl-4 leading-snug">
                                    <li>Prepared monthly Withholding Tax returns (P.N.D.1, P.N.D.3, and P.N.D.53), ensuring accurate tax compliance and timely submission.</li>
                                    <li>Prepared withholding tax certificates and coordinated tax-related matters with Revenue Department officers and external parties.</li>
                                </ul>

                                <p class="text-[11px] font-bold text-navyMid mt-2">Inventory Control &amp; Month-End Closing</p>
                                <ul class="text-[11px] text-slateText space-y-1 list-disc pl-4 leading-snug">
                                    <li>Conducted physical inventory counts, reconciled material usage against system records, and prepared necessary stock adjustments.</li>
                                    <li>Supported month-end closing and prepared accounting schedules and supporting documents for the external accounting firm.</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- ==========================================
         JAVASCRIPT: BILINGUAL ENGINE & INTERACTIONS
    =========================================== -->
    <script>
        const translations = {
            th: {
                nav_summary: "บทสรุปวิชาชีพ",
                nav_achievements: "ผลงานเด่น",
                nav_experience: "ประสบการณ์",
                nav_skills: "ทักษะเฉพาะทาง",
                nav_qualifications: "คุณวุฒิและการศึกษา",
                nav_btn_pdf: "Resume PDF",
                nav_btn_contact: "ติดต่อ",
                hero_status: "ผู้ทำบัญชีขึ้นทะเบียน | สถานะ CPD ปัจจุบัน (Registered Accountant | Active CPD Status)",
                hero_name: "กฤษตฤณ จิรินวงค์ — KRITTRIN JIRINWONG",
                copy_badge: "คัดลอก",
                cta_resume_full: "ดูเรซูเม่ฉบับเต็ม / บันทึก PDF",
                cta_contact: "ติดต่อฉัน",
                sec_achievements: "Key Achievements · ผลงานสำคัญที่โดดเด่น",
                ach_1: "สร้างความแม่นยำของสินค้าคงเหลือได้ถึง 99.98% ในการตรวจนับประจำปี 2025 โดยเป็นผู้นำกระบวนการทั้งหมดตั้งแต่การระงับรายการเคลื่อนไหว (Transaction Freezing) การควบคุมการตรวจนับ ไปจนถึงการตรวจสอบหาสาเหตุผลต่างและการปรับปรุงยอดสต็อกขั้นสุดท้าย",
                ach_2: "ตรวจสอบและปิดใบสั่งผลิต (Manufacturing Work Orders) ประมาณ 1,400 ใบต่อเดือน ทำให้มั่นใจได้ถึงการกระทบยอดงานระหว่างทำ (WIP Reconciliation) ที่ตรงเวลาและการบันทึกต้นทุนในระบบ Oracle EBS R12 อย่างถูกต้องแม่นยำ",
                ach_3: "บริหารจัดการและกระทบยอดบัญชีแยกประเภททั่วไปที่เกี่ยวข้องกับสินค้าคงเหลือมูลค่ามากกว่า 200 ล้านบาท เพื่อให้ยอดคงเหลือระหว่างบัญชีย่อยสินค้าคงเหลือ (Inventory Subledger) และงบทดลอง (Trial Balance) ตรงกันอย่างครบถ้วน",
                sec_summary: "Professional Summary · บทสรุปผู้บริหารและประสบการณ์วิชาชีพ",
                summary_text: "นักบัญชีต้นทุนที่มุ่งเน้นผลลัพธ์ (Results-driven Cost Accountant) มีประสบการณ์ด้านบัญชีต้นทุนการผลิต การกระทบยอดงานระหว่างทำ (WIP) และสินค้าคงเหลือ การควบคุมใบสั่งผลิต (Work Order Control) ระบบต้นทุนมาตรฐาน (Standard Costing) และการวิเคราะห์ผลต่าง (Variance Analysis) ในระบบ Oracle EBS รับผิดชอบการตรวจสอบและปิดใบสั่งผลิตประมาณ 1,400 ใบต่อเดือน กระทบยอดสินค้าคงเหลือมูลค่ามากกว่า 200 ล้านบาท และจัดทำรายงานวิเคราะห์ผลต่าง MUV และ IPV เพื่อระบุสาเหตุที่แท้จริง ขับเคลื่อนการทำงานร่วมกันข้ามสายงาน (Cross-functional Collaboration) อย่างมีประสิทธิภาพกับฝ่ายผลิต ฝ่ายจัดซื้อ และฝ่ายจัดหา เพื่อประสานการแก้ไขและปรับปรุงกระบวนการทำงานให้คล่องตัว เป็นผู้นำกระบวนการตรวจนับสินค้าคงเหลือประจำปี 2025 จนบรรลุความแม่นยำ 99.98% เชี่ยวชาญการใช้ Microsoft Excel, Power Query และ PivotTables พร้อมประสบการณ์เพิ่มเติมด้านการปิดบัญชีสิ้นงวด การสนับสนุนการตรวจสอบบัญชี เจ้าหนี้การค้า (AP) และภาษีหัก ณ ที่จ่าย เป็นผู้ทำบัญชีขึ้นทะเบียนที่มีสถานะ CPD ปัจจุบัน",
                sec_experience: "Professional Experience · ประสบการณ์การทำงานฉบับสมบูรณ์",
                btn_collapse_all: "ย่อ/ขยายหมวดงานทั้งหมด",
                hach_sub1_title: "Cost Accounting & Variance Analysis (การบัญชีต้นทุนและการวิเคราะห์ผลต่าง)",
                hach_1_1: "ติดตามรายการเคลื่อนไหวของงานระหว่างทำ (WIP transactions) และดำเนินการกระทบยอดรายสัปดาห์และสิ้นเดือนระหว่างรายงาน WIP กับงบทดลอง (Trial Balance)",
                hach_1_2: "ตรวจสอบและปิดใบสั่งผลิต (Manufacturing Work Orders) ประมาณ 1,400 ใบต่อเดือน รวมถึงการตรวจสอบความถูกต้องของปริมาณวัตถุดิบที่ต้องใช้และที่เบิกจ่ายจริงก่อนปิดงาน",
                hach_1_3: "จัดทำรายงานผลต่าง MUV และ IPV รายสัปดาห์และรายเดือน วิเคราะห์หาสาเหตุที่แท้จริง (Root Causes) และประสานงานแนวทางแก้ไขร่วมกับฝ่ายผลิต ฝ่ายจัดซื้อ และฝ่ายจัดหา",
                hach_1_4: "อัปเดตต้นทุนมาตรฐาน (Standard Costs) สำหรับวัตถุดิบและสินค้าสำเร็จรูป พร้อมตรวจสอบโครงสร้างสูตรการผลิต (BOM components) เพื่อระบุปัญหาด้านต้นทุนหรือข้อมูลหลัก (Master Data)",
                hach_sub2_title: "Inventory Control, Physical Count & GL Reconciliation (การควบคุมสินค้าคงเหลือ การตรวจนับ และการกระทบยอด GL)",
                hach_2_1: "บริหารจัดการบัญชีแยกประเภททั่วไปที่เกี่ยวข้องกับสินค้าคงเหลือมูลค่ามากกว่า 200 ล้านบาท และกระทบยอดบัญชีย่อยสินค้าคงเหลือ (Inventory Subledger) กับงบทดลองเป็นประจำทุกเดือน",
                hach_2_2: "เป็นผู้นำกระบวนการตรวจนับสินค้าคงเหลือทั้งหมด ตั้งแต่การระงับรายการเคลื่อนไหว (Transaction Freezing) การดำเนินการตรวจนับ การตรวจสอบหาสาเหตุผลต่าง ไปจนถึงการปรับปรุงสต็อกขั้นสุดท้าย โดยสร้างความแม่นยำได้ถึง 99.98% ในปี 2025",
                hach_2_3: "ตรวจสอบรายงานสินค้าคงเหลือประจำวัน (Daily Inventory On-hand Reports) เพื่อระบุรายการยอดติดลบ รายการที่ขาดต้นทุนต่อหน่วย และรายการเคลื่อนไหวที่ผิดปกติ พร้อมประสานงานแก้ไขอย่างทันท่วงที",
                hach_2_4: "จัดทำรายงานอายุสินค้าคงเหลือ (Inventory Aging) และรายงานของเสียรายเดือน (Monthly Scrap Reports) วิเคราะห์หาสาเหตุที่แท้จริง และประสานแผนการปรับปรุงร่วมกับหน่วยงานที่รับผิดชอบ",
                hach_2_5: "ประสานงานการตรวจนับและการทำลายของเสีย (Scrap Counting and Destruction) ร่วมกับผู้สอบบัญชีภายนอก (External Auditors) และเจ้าหน้าที่กรมสรรพากรในพื้นที่ให้เป็นไปตามระบบการควบคุมภายใน",
                hach_2_6: "จัดทำทะเบียนคุมการปรับปรุงสินค้าคงเหลือ (Inventory Adjustment Logs) กำหนดเลขที่อ้างอิงการปรับปรุง และกำหนดรหัสบัญชี (COA Classifications) ที่เหมาะสม",
                hach_sub3_title: "Accounts Payable & Tax Compliance (เจ้าหนี้การค้าและการปฏิบัติตามกฎหมายภาษี)",
                hach_3_1: "ตรวจสอบและบันทึกบัญชีใบแจ้งหนี้ในประเทศ ต่างประเทศ บริษัทในเครือ (Intercompany) และค่าขนส่ง (Freight) ในสกุลเงิน THB, USD และ EUR โดยใช้ระบบตรวจสอบ 3 ทาง (Three-way matching: PO, GR และ Invoice) เพื่อความถูกต้องและสอดคล้องตามระเบียบ",
                hach_3_2: "ตรวจสอบรายงานการรับสินค้า (Goods Receipt - GR) เทียบกับใบสั่งซื้อ (PO) และใบแจ้งหนี้ที่บันทึกไว้ เพื่อยืนยันความถูกต้องของการรับของและสนับสนุนกระบวนการ Three-way matching",
                hach_3_3: "กระทบยอดภาษีซื้อและภาษีขายประจำเดือน (ภ.พ.30) กับบัญชีแยกประเภททั่วไป และจัดทำแบบแสดงรายการภาษีหัก ณ ที่จ่าย (ภ.ง.ด.3, ภ.ง.ด.53) รวมถึงออกหนังสือรับรองการหักภาษี ณ ที่จ่าย (50 ทวิ) เพื่อให้ถูกต้องตามกฎหมายภาษีและยื่นแบบตรงเวลา",
                hach_sub4_title: "Month-End Closing, Process Improvement & Audit Readiness (การปิดบัญชีสิ้นงวด การพัฒนากระบวนการ และความพร้อมรับการตรวจสอบ)",
                hach_4_1: "สนับสนุนการปิดบัญชีรายเดือน รายไตรมาส และประจำปี พร้อมจัดเตรียมข้อมูลด้านต้นทุนและสินค้าคงเหลือสำหรับการตรวจสอบภายในและภายนอก (Internal and External Audits)",
                hach_4_2: "ปรับปรุงขั้นตอนการปฏิบัติงานและจัดทำมาตรฐานคู่มือการปฏิบัติงานบัญชี (Accounting Work Instructions) เพิ่มประสิทธิภาพการเตรียมข้อมูลและการกระทบยอดเพื่อลดระยะเวลาปิดบัญชีและเพิ่มประสิทธิภาพของทีม",
                hach_4_3: "จัดระเบียบและแยกหมวดหมู่แฟ้มเอกสารตัวจริงและไฟล์ข้อมูลดิจิทัลบน Shared Drive และ OneDrive ให้เป็นระบบการจัดเก็บที่มีโครงสร้างชัดเจน เพื่อรักษาร่องรอยการตรวจสอบ (Audit Trails) และสืบค้นข้อมูลย้อนหลังได้อย่างรวดเร็ว",
                vp_sub1_title: "Accounts Payable, Project Coordination & Cash Management (เจ้าหนี้การค้า การประสานงานโครงการ และการบริหารเงินสด)",
                vp_1_1: "ตรวจสอบและบันทึกบัญชีใบแจ้งหนี้ซัพพลายเออร์ในประเทศประมาณ 100 รายการต่อเดือน โดยตรวจสอบความครบถ้วนของเอกสารประกอบ การจัดหมวดหมู่บัญชีที่ถูกต้อง และการอนุมัติตามระเบียบ",
                vp_1_2: "ประสานงานกับโฟร์แมนประจำโครงการ (Project Foremen) เพื่อติดตามความคืบหน้างานก่อสร้างและงวดการจ่ายเงินตามสัญญาโครงการ",
                vp_1_3: "บริหารจัดการการเบิกจ่ายเงินสดย่อย (Petty Cash Disbursements) และดำเนินการกระทบยอดบัญชีเงินฝากธนาคาร (Bank Reconciliations)",
                vp_sub2_title: "Tax Compliance & Filing (การปฏิบัติตามกฎหมายภาษีและการยื่นแบบ)",
                vp_2_1: "จัดทำแบบแสดงรายการภาษีหัก ณ ที่จ่ายประจำเดือน (ภ.ง.ด.1, ภ.ง.ด.3 และ ภ.ง.ด.53) เพื่อให้มั่นใจในความถูกต้องตามกฎหมายภาษีและการยื่นแบบตรงเวลา",
                vp_2_2: "จัดทำหนังสือรับรองการหักภาษี ณ ที่จ่าย และประสานงานด้านภาษีกับเจ้าหน้าที่กรมสรรพากรและหน่วยงานภายนอก",
                vp_sub3_title: "Inventory Control & Month-End Closing (การควบคุมสินค้าคงเหลือและการปิดบัญชีสิ้นงวด)",
                vp_3_1: "ดำเนินการตรวจนับสินค้าคงเหลือจริง (Physical Inventory Counts) กระทบยอดการใช้วัสดุเทียบกับข้อมูลในระบบ และจัดทำรายการปรับปรุงสต็อกที่จำเป็น",
                vp_3_2: "สนับสนุนการปิดบัญชีสิ้นเดือน และจัดเตรียมตารางรายละเอียดประกอบงบการเงิน (Accounting Schedules) รวมถึงเอกสารประกอบสำหรับสำนักงานบัญชีภายนอก",
                sec_skills: "Technical Skills Matrix · ทักษะทางวิชาชีพและระบบงาน (ครบทั้ง 22 รายการ)",
                sec_qual: "Education, Qualification, Training & Languages · การศึกษา คุณวุฒิ การอบรม และภาษา",
                qual_desc: "ผู้ทำบัญชีขึ้นทะเบียนถูกต้องตามกฎหมาย พร้อมสถานะการพัฒนาความรู้ต่อเนื่องทางวิชาชีพ (CPD) ปัจจุบัน",
                footer_cta_title: "พร้อมร่วมงานและสร้างความแม่นยำให้กับระบบบัญชีต้นทุนและสินค้าคงเหลือขององค์กร",
                contact_modal_title: "ติดต่อ กฤษตฤณ จิรินวงค์",
                contact_modal_sub: "คลิกปุ่มคัดลอกเพื่อนำข้อมูลไปติดต่อได้ทันที",
                resume_modal_header: "ตัวอย่างเรซูเม่ฉบับสมบูรณ์ (A4 Print Ready)",
                btn_print_pdf: "พิมพ์ / บันทึกเป็น PDF",
                toast_copied: "คัดลอกข้อมูลแล้ว"
            },
            en: {
                nav_summary: "Summary",
                nav_achievements: "Achievements",
                nav_experience: "Experience",
                nav_skills: "Skills",
                nav_qualifications: "Qualifications",
                nav_btn_pdf: "Resume PDF",
                nav_btn_contact: "Contact",
                hero_status: "Registered Accountant | Active CPD Status",
                hero_name: "KRITTRIN JIRINWONG",
                copy_badge: "Copy",
                cta_resume_full: "View Full Resume / Save PDF",
                cta_contact: "Contact Me",
                sec_achievements: "Key Achievements",
                ach_1: "Achieved 99.98% inventory accuracy in the 2025 year-end physical inventory by leading the full process from transaction freezing and count execution to discrepancy resolution and final stock adjustments.",
                ach_2: "Reviewed and closed approximately 1,400 manufacturing work orders per month, ensuring timely WIP reconciliation and accurate cost posting in Oracle EBS R12.",
                ach_3: "Managed and reconciled inventory-related general ledger accounts exceeding THB 200 million, ensuring alignment between inventory subledger balances and the trial balance.",
                sec_summary: "Professional Summary",
                summary_text: "Results-driven Cost Accountant with experience in manufacturing cost accounting, WIP and inventory reconciliation, work order control, standard costing, and variance analysis in Oracle EBS. Responsible for reviewing and closing approximately 1,400 manufacturing work orders per month, reconciling inventory balances exceeding THB 200 million, and performing MUV and IPV analyses to identify root causes. Drives effective Cross-functional Collaboration with Production, Purchasing, and Sourcing teams to coordinate corrective actions and streamline operations. Led the 2025 physical inventory process, achieving 99.98% inventory accuracy. Proficient in Microsoft Excel, Power Query, and PivotTables, with additional experience in month-end closing, audit support, AP, and withholding tax. Registered accountant with active CPD status.",
                sec_experience: "Professional Experience",
                btn_collapse_all: "Expand / Collapse All",
                hach_sub1_title: "Cost Accounting & Variance Analysis",
                hach_1_1: "Monitor WIP transactions and perform weekly and month-end reconciliations between WIP reports and the trial balance.",
                hach_1_2: "Review and close approximately 1,400 manufacturing work orders per month, including verification of required and issued material quantities before closure.",
                hach_1_3: "Prepare weekly and monthly MUV and IPV reports, investigate root causes, and coordinate corrective actions with Production, Purchasing, and Sourcing teams.",
                hach_1_4: "Update standard costs for raw materials and finished goods and review BOM components to identify costing or master-data issues.",
                hach_sub2_title: "Inventory Control, Physical Count & GL Reconciliation",
                hach_2_1: "Manage inventory-related general ledger accounts exceeding THB 200 million and reconcile inventory subledger balances with the trial balance each month.",
                hach_2_2: "Lead the full physical inventory process, from transaction freezing and count execution to discrepancy investigation and final stock adjustment, achieving 99.98% inventory accuracy in 2025.",
                hach_2_3: "Review daily inventory on-hand reports to identify negative quantities, missing unit costs, and unusual transactions and coordinate timely corrections.",
                hach_2_4: "Prepare inventory aging and monthly scrap reports, analyze root causes, and coordinate improvement actions with responsible departments.",
                hach_2_5: "Coordinate scrap counting and destruction with external auditors and local Revenue Department officers in accordance with internal controls.",
                hach_2_6: "Maintain inventory adjustment logs, assign adjustment reference numbers, and determine appropriate COA classifications.",
                hach_sub3_title: "Accounts Payable & Tax Compliance",
                hach_3_1: "Review and record domestic, overseas, intercompany, and freight invoices in THB, USD, and EUR using three-way matching (PO, GR, and Invoice) to ensure accuracy and compliance.",
                hach_3_2: "Review Goods Receipt (GR) reports against purchase orders (PO) and recorded invoices to verify receipt accuracy and support three-way matching.",
                hach_3_3: "Reconcile monthly Input/Output VAT (P.P.30) with GL accounts and prepare Withholding Tax returns (P.N.D.3, P.N.D.53), including issuing 50 Tawi certificates, ensuring full tax compliance and timely filing.",
                hach_sub4_title: "Month-End Closing, Process Improvement & Audit Readiness",
                hach_4_1: "Support monthly, quarterly, and annual closings and provide costing and inventory information for internal and external audits.",
                hach_4_2: "Improve operational workflows and standardize Accounting Work Instructions, optimizing data preparation and reconciliation procedures to shorten closing timelines and enhance team efficiency.",
                hach_4_3: "Organize and categorize physical files and digital records on Shared Drive and OneDrive into structured filing systems to maintain clear audit trails and enable fast historical retrieval.",
                vp_sub1_title: "Accounts Payable, Project Coordination & Cash Management",
                vp_1_1: "Reviewed and recorded approximately 100 domestic supplier invoices per month, ensuring complete supporting documents, accurate account classification, and proper approvals.",
                vp_1_2: "Coordinated with project foremen to monitor construction progress and payment milestones under project contracts.",
                vp_1_3: "Managed petty cash disbursements and performed bank reconciliations.",
                vp_sub2_title: "Tax Compliance & Filing",
                vp_2_1: "Prepared monthly Withholding Tax returns (P.N.D.1, P.N.D.3, and P.N.D.53), ensuring accurate tax compliance and timely submission.",
                vp_2_2: "Prepared withholding tax certificates and coordinated tax-related matters with Revenue Department officers and external parties.",
                vp_sub3_title: "Inventory Control & Month-End Closing",
                vp_3_1: "Conducted physical inventory counts, reconciled material usage against system records, and prepared necessary stock adjustments.",
                vp_3_2: "Supported month-end closing and prepared accounting schedules and supporting documents for the external accounting firm.",
                sec_skills: "Technical Skills Matrix (All 22 Skills)",
                sec_qual: "Education, Qualification, Training & Languages",
                qual_desc: "Licensed bookkeeper with active Continuing Professional Development (CPD) status.",
                footer_cta_title: "Ready to deliver accuracy and strong internal control to your Cost & Inventory Accounting operations.",
                contact_modal_title: "Contact Krittrin Jirinwong",
                contact_modal_sub: "Click Copy to save contact information directly",
                resume_modal_header: "Executive Resume Preview (A4 Print Ready)",
                btn_print_pdf: "Print / Save as PDF",
                toast_copied: "Copied to clipboard"
            }
        };

        let currentLang = 'th';
        let allExpanded = true;

        function setLanguage(lang) {
            currentLang = lang;
            document.documentElement.lang = lang;

            const indicator = document.getElementById('lang-indicator');
            const btnTh = document.getElementById('btn-th');
            const btnEn = document.getElementById('btn-en');

            if (lang === 'en') {
                indicator.style.transform = 'translateX(36px)';
                btnEn.classList.replace('text-slate-400', 'text-white');
                btnTh.classList.replace('text-white', 'text-slate-400');
            } else {
                indicator.style.transform = 'translateX(0px)';
                btnTh.classList.replace('text-slate-400', 'text-white');
                btnEn.classList.replace('text-white', 'text-slate-400');
            }

            document.querySelectorAll('[data-i18n]').forEach(el => {
                const key = el.getAttribute('data-i18n');
                if (translations[lang] && translations[lang][key]) {
                    el.textContent = translations[lang][key];
                }
            });
        }

        function toggleExpGroup(btnEl) {
            const content = btnEl.nextElementSibling;
            content.classList.toggle('collapsed');
        }

        function toggleAllSubsections() {
            allExpanded = !allExpanded;
            document.querySelectorAll('#experience .accordion-content').forEach(el => {
                if (allExpanded) {
                    el.classList.remove('collapsed');
                } else {
                    el.classList.add('collapsed');
                }
            });
        }

        function toggleMobileMenu(show) {
            const drawer = document.getElementById('mobile-drawer');
            const backdrop = document.getElementById('mobile-drawer-backdrop');
            if (show) {
                backdrop.classList.remove('hidden');
                requestAnimationFrame(() => {
                    backdrop.classList.remove('opacity-0');
                    drawer.classList.remove('translate-x-full');
                });
            } else {
                backdrop.classList.add('opacity-0');
                drawer.classList.add('translate-x-full');
                setTimeout(() => backdrop.classList.add('hidden'), 300);
            }
        }

        function openContactModal() {
            const modal = document.getElementById('contact-modal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeContactModal() {
            const modal = document.getElementById('contact-modal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function openResumeModal() {
            const modal = document.getElementById('resume-modal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeResumeModal() {
            const modal = document.getElementById('resume-modal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function copyText(text) {
            const tempInput = document.createElement('textarea');
            tempInput.value = text;
            tempInput.style.position = 'fixed';
            tempInput.style.opacity = '0';
            document.body.appendChild(tempInput);
            tempInput.select();
            try {
                document.execCommand('copy');
                showToast(`${translations[currentLang].toast_copied}: ${text}`);
            } catch (err) {
                showToast(text);
            }
            document.body.removeChild(tempInput);
        }

        let toastTimer;
        function showToast(msg) {
            const toast = document.getElementById('toast');
            const toastMsg = document.getElementById('toast-message');
            toastMsg.textContent = msg;
            toast.classList.remove('opacity-0', 'translate-y-3');
            clearTimeout(toastTimer);
            toastTimer = setTimeout(() => {
                toast.classList.add('opacity-0', 'translate-y-3');
            }, 2400);
        }

        document.addEventListener('keydown', (e) => {
            if (e.key === 'Escape') {
                toggleMobileMenu(false);
                closeContactModal();
                closeResumeModal();
            }
        });
    </script>
</body>
</html>

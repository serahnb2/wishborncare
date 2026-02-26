# Wishborn Care

**당신의 여정, 가볍게 함께** - 난임부터 임신까지, 모든 여정을 함께하는 전문 스킨케어 브랜드

## 🌸 프로젝트 개요

Wishborn Care는 난임 치료부터 임신, 산후 회복까지 모든 단계를 함께하는 전문 스킨케어 브랜드입니다. 안전하고 효과적인 성분으로 예비맘과 임산부의 다양한 피부 고민을 해결합니다.

## ✅ 최근 업데이트 (2026-02-26)

### 🎨 디자인 & UI 개선
- ✅ **KR 언어 스위치**: "KR"에서 "< KR" 형태로 변경 (honest.co.kr 스타일)
  - 폰트 크기 21px → 10.5px (50% 감소)
  - Desktop: 10.5px, Tablet: 9px, Mobile: 8px
  - 모든 페이지 (index.html, brand-story.html, products.html) 적용

### 🌟 Brand Story 페이지 (brand-story.html)
- ✅ **히어로 섹션**: 감성적인 이미지 배경 추가 (hero-brand-story.jpg)
  - 전체 화면 이미지 with overlay
  - 텍스트 그라데이션 배경 효과
- ✅ **Our Story 섹션 제거**: 창업자 스토리 및 타임라인 전체 삭제
- ✅ **Brand Philosophy 섹션 개편**:
  - 3단 레이아웃 (이미지 | 텍스트 | 이미지)
  - 좌우에 감성 이미지 배치 (philosophy-left.jpg, philosophy-right.jpg)
  - 텍스트 최소화: 핵심 메시지만 강조
- ✅ **유지된 섹션**: Etymology, Journey, Core Values, Closing Message

### 🏠 메인 페이지 (index.html)
- ✅ **Product Lineup 섹션 제거**: 기존 6개 제품 그리드 삭제
- ✅ **Brand Story 섹션 추가**: 브랜드 핵심 가치 축약 버전
  - 소망이 태어나다 하이라이트 타이틀
  - 브랜드 소개 텍스트 (3줄)
  - 2개 값 카드 (진짜 공감 | 안전한 성분)
  - "브랜드 스토리 더보기" CTA 버튼
- ✅ **View All Products CTA**: Best Seller 하단에 "전체 제품 보기" 버튼 추가
  - products.html로 링크
  - 중앙 정렬, 여백 최적화

### 📱 모바일 최적화
- ✅ Hero 텍스트 오버랩 해결: 네비게이션 폭 축소, 로고 크기 조정
- ✅ Hero 라인 간격 조정: line-height 1.2 → 1.15 (Desktop), 1.2 (Mobile)
- ✅ 섹션 여백 축소: padding 100px → 60px (Desktop), 40px (Mobile)
- ✅ Hero 높이 최적화: min-height 100vh → 85vh (Desktop), auto (Mobile)
- ✅ Best Seller 모바일 레이아웃: 2×2 그리드
- ✅ Product Lineup (products.html): 모바일 2×2 그리드
- ✅ Brand Story Values: 모바일 1열 스택 레이아웃
- ✅ 모든 텍스트 잘림 현상 해결, 반응형 폰트 크기 적용

## 📁 주요 페이지

### 1. 메인 페이지 (index.html)
- Hero 섹션: 좌측 텍스트 + 우측 이미지 레이아웃
- Best Seller: 4개 제품 그리드 (모바일 2×2)
- View All Products CTA
- Brand Story: 축약 버전 with 2개 값 카드
- Footer: 심플한 2열 레이아웃

### 2. Brand Story (brand-story.html)
- Hero Video: 감성 이미지 배경
- Etymology: 브랜드 이름 어원 (Wish + Born)
- Journey: 난임의 여정 3단계 + 공감 인용
- Philosophy: 3단 레이아웃 (이미지 | 핵심 메시지 | 이미지)
- Core Values: 4개 값 (Safety, Science, Empathy, Sustainable)
- Closing Message: 마무리 메시지

### 3. Products (products.html)
- Essential Care: 2개 제품 (Relaxing Leg Cream, All-in-One Cream)
- Advanced Care: 2개 제품 (Nipple Care Cream, Soothing Belly Balm)
- Baby Care: 2개 제품 (Diaper Rash Cream Pink/Mint)
- 각 라인별 토글 그리드 (2×2 모바일 레이아웃)

## 🎨 디자인 시스템

### 색상 팔레트
```css
--warm-terracotta: #D4836F    /* 메인 강조 색상 */
--soft-peach: #F5D4C8          /* 부드러운 배경 */
--warm-beige: #E8DDD0          /* 테두리 색상 */
--deep-brown: #6B5446          /* 텍스트 주색 */
--cream: #FFF8F3               /* 섹션 배경 */
--warm-gold: #C9A26D           /* 카테고리 배지 */
--light-warm: #FDF6F0          /* 밝은 배경 */
```

### 타이포그래피
- **헤딩**: Noto Serif KR (serif)
- **본문**: Noto Sans KR (sans-serif)
- **아이콘**: Font Awesome 6.4.0

### 반응형 Breakpoints
- Desktop: > 768px
- Tablet: 768px
- Mobile: 480px
- Small Mobile: < 480px

## 🖼️ 이미지 에셋

### 히어로 & 브랜드 이미지
- `hero-mom-baby.jpg` - 메인 히어로 이미지 (2.03 MB)
- `hero-brand-story.jpg` - Brand Story 히어로 이미지 (1.44 MB, NEW)
- `philosophy-left.jpg` - Philosophy 좌측 이미지 (146 KB, NEW)
- `philosophy-right.jpg` - Philosophy 우측 이미지 (488 KB, NEW)

### 베스트 셀러 제품
- `product-diaper-cream.jpg` - 기저귀 발진 크림
- `product-allinone-cream.jpg` - 올인원 크림
- `product-relaxing-leg.jpg` - 릴랙싱 레그 크림
- `product-nipple-care.jpg` - 니플 케어 크림

### Product Line 제품 (6개)
- `product-relaxing-leg-new.jpg` - Essential Care (1.07 MB)
- `product-allinone-new.jpg` - Essential Care (1.14 MB)
- `product-nipple-new.jpg` - Advanced Care (989 KB)
- `product-belly-balm.jpg` - Advanced Care (1.06 MB)
- `product-diaper-pink.jpg` - Baby Care (1.33 MB)
- `product-diaper-mint.jpg` - Baby Care (1.29 MB)

### 기타 에셋
- `kr-flag.png` - 한국 국기 아이콘 (1 KB, REMOVED - 텍스트 변경으로 대체)

## 🚀 향후 개발 계획

### 우선순위 높음
- [ ] Contact Us 페이지 구현
- [ ] 제품 상세 페이지 (개별 제품 페이지)
- [ ] 장바구니 & 결제 시스템 연동
- [ ] 다국어 지원 (영문 버전)

### 우선순위 중간
- [ ] 제품 리뷰 & 평점 시스템
- [ ] FAQ 섹션 추가
- [ ] 블로그/스토리 섹션
- [ ] 회원가입/로그인 기능

### 우선순위 낮음
- [ ] 소셜 미디어 통합
- [ ] 뉴스레터 구독 기능
- [ ] 실시간 채팅 상담
- [ ] 모바일 앱 개발

## 🔧 기술 스택

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Fonts**: Google Fonts (Noto Serif KR, Noto Sans KR)
- **Icons**: Font Awesome 6.4.0
- **Responsive**: CSS Media Queries
- **Deployment**: Static Hosting (ready for deployment)

## 📊 파일 구조

```
wishborn-care/
├── index.html                   (20.8 KB) ← 최근 수정
├── brand-story.html             (23.1 KB) ← 최근 수정
├── products.html                (21.9 KB) ← 최근 수정
├── index-backup.html            (55.8 KB, 백업 파일)
├── index-broken.html            (26.7 KB, 삭제 예정)
├── README.md                    (이 파일)
└── images/
    ├── hero-mom-baby.jpg                (2.03 MB)
    ├── hero-brand-story.jpg             (1.44 MB) ← NEW
    ├── philosophy-left.jpg              (146 KB)  ← NEW
    ├── philosophy-right.jpg             (488 KB)  ← NEW
    ├── product-diaper-cream.jpg         (1.26 MB)
    ├── product-allinone-cream.jpg       (1.15 MB)
    ├── product-relaxing-leg.jpg         (1.09 MB)
    ├── product-nipple-care.jpg          (989 KB)
    ├── product-relaxing-leg-new.jpg     (1.07 MB)
    ├── product-allinone-new.jpg         (1.14 MB)
    ├── product-nipple-new.jpg           (989 KB)
    ├── product-belly-balm.jpg           (1.06 MB)
    ├── product-diaper-pink.jpg          (1.33 MB)
    ├── product-diaper-mint.jpg          (1.29 MB)
    ├── relief-leg-cream.jpg             (19 KB)
    ├── stretch-mark-cream.jpg           (48 KB)
    ├── comfort-belly-butter.jpg         (48 KB)
    ├── recovery-care-set.jpg            (60 KB)
    ├── soothing-breast-cream.jpg        (58 KB)
    ├── refresh-face-mist.jpg            (14 KB)
    ├── inner-glow-supplement.jpg        (85 KB)
    ├── calm-aromatherapy.jpg            (90 KB)
    ├── best-products.jpg                (403 KB)
    └── hero-beauty.jpg                  (424 KB)
```

**총 프로젝트 크기**: ~14 MB (이미지 포함)

## 🎯 완료된 작업 로그

### 2026-02-26 (Latest)
- [x] KR 언어 스위치 스타일 변경 (< KR, 50% 폰트 축소)
- [x] Brand Story 히어로 섹션 이미지 추가
- [x] Brand Story "Our Story" 섹션 제거
- [x] Brand Philosophy 이미지 추가 및 텍스트 최소화
- [x] Index.html Product Lineup 제거 & Brand Story 축약 버전 추가
- [x] Best Seller 하단에 "View All Products" CTA 추가
- [x] index.html HTML 구조 정리 (orphaned elements 제거)
- [x] 모바일 최적화 재검토 및 QA 완료

### 2026-02-25
- [x] KR 언어 토글 150% 확대 및 드롭다운 메뉴 추가
- [x] Product lineup 제품 판매중/출시예정 태그 제거
- [x] 모바일 헤더·히어오 텍스트 오버랩 해결
- [x] 히어오 텍스트 line-height 축소 및 섹션 여백 최적화
- [x] products.html 페이지 생성 (Essential, Advanced, Baby Care)
- [x] brand-story.html 페이지 생성 (어원, 철학, 스토리, 핵심 가치)

### 2026-02-24
- [x] 히어로 섹션 heading 70% 축소
- [x] Product lineup 제품 재구성 (PDF 6-8페이지 기반)
- [x] "Your Journey with Wishborn" 섹션 제거
- [x] 네비게이션 메뉴 텍스트 우측 이동
- [x] 모바일 최적화 및 데스크톱 QA 완료

## 📝 라이센스

© 2026 Wishborn Care. All rights reserved.

---

**프로젝트 상태**: ✅ Production Ready  
**최종 업데이트**: 2026-02-26  
**버전**: 2.1.0

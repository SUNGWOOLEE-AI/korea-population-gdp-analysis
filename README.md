# 📊 한국 인구변화와 GDP 성장률의 수학적 분석

## 🎯 프로젝트 개요

함수의 변화율을 활용하여 한국의 인구 구조 변화와 경제성장률 간의 상관관계를 분석하는 인터랙티브 시각화 도구입니다.

## 🚀 즉시 배포하기

### GitHub Pages
**라이브 데모**: [https://sungwoolee-ai.github.io/korea-population-gdp-analysis/](https://sungwoolee-ai.github.io/korea-population-gdp-analysis/)

### Netlify 원클릭 배포
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/SUNGWOOLEE-AI/korea-population-gdp-analysis)

### Vercel 원클릭 배포
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/SUNGWOOLEE-AI/korea-population-gdp-analysis)

## 📈 주요 분석 내용

### 1. 수학적 분석 도구
- **변화율 공식**: Δy/Δx = (y₂ - y₁)/(x₂ - x₁)
- **상관관계 분석**: 피어슨 상관계수 계산
- **함수 모델링**: 이차함수를 이용한 인구 예측 모델
- **미분의 응용**: 변화율의 변화(가속도) 분석

### 2. 데이터 범위
- **기간**: 2000년 ~ 2025년 (실제 데이터)
- **예측**: 2026년 ~ 2040년 (수학적 모델 기반)
- **지표**: 인구수, GDP 성장률, 1인당 GDP

### 3. 핵심 발견사항
- **상관계수**: 인구증가율 ↔ GDP성장률 r = 0.78 (강한 양의 상관관계)
- **변곡점**: 2018년경 인구 증가율이 0이 되어 감소세로 전환
- **함수 특성**: 이차함수 형태, f'(x) > 0 → f'(x) = 0 → f'(x) < 0 변화

## 🛠️ 기술 스택

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **차트 라이브러리**: Chart.js 3.9.1
- **디자인**: CSS Grid, Flexbox, 그라디언트
- **반응형**: 모바일 최적화 포함

## 📊 인터랙티브 기능

### 1. 실시간 차트 전환
- GDP 성장률 분석
- 1인당 GDP 변화율
- 인구증가율과 경제지표 비교

### 2. 시각적 요소
- 이중 Y축 차트로 다중 데이터 표시
- 실선(실제 데이터) vs 점선(예측 데이터) 구분
- 호버 효과와 툴팁
- 애니메이션 효과

### 3. 데이터 테이블
- 연도별 상세 수치
- 수학적 해석 포함
- 상관관계 지표 시각화

## 🎓 교육적 활용

### 수학 수행평가 활용 가능 주제
1. **함수와 그래프**: 실제 데이터의 함수 모델링
2. **미분과 적분**: 변화율과 누적 변화량 분석
3. **통계**: 상관관계와 회귀분석
4. **수학적 모델링**: 예측 모델 구축

### 학습 목표
- 수학적 개념의 실생활 적용
- 데이터 분석과 시각화 능력
- 비판적 사고와 예측 능력
- 수학적 의사소통 능력

## 🚀 사용 방법

### 1. 온라인 접속 (추천)
- **GitHub Pages**: https://sungwoolee-ai.github.io/korea-population-gdp-analysis/
- **Netlify**: 위의 배포 버튼 클릭

### 2. 로컬 실행
```bash
# 저장소 클론
git clone https://github.com/SUNGWOOLEE-AI/korea-population-gdp-analysis.git

# 디렉토리 이동
cd korea-population-gdp-analysis

# 브라우저에서 index.html 열기
open index.html
```

## 📁 프로젝트 구조

```
korea-population-gdp-analysis/
├── index.html              # 메인 HTML 파일
├── README.md               # 프로젝트 문서
├── PRESENTATION_GUIDE.md   # 발표 가이드
├── data.json              # 구조화된 데이터
├── netlify.toml           # Netlify 배포 설정
├── LICENSE                # MIT 라이선스
└── .github/
    └── workflows/
        └── pages.yml      # GitHub Pages 자동 배포
```

## 📊 주요 수학적 모델

### 1. 인구 예측 함수
```
P(t) = -0.002t² + 0.35t + 47.2
```

### 2. 변화율 함수 (1차 도함수)
```
P'(t) = -0.004t + 0.35
```

### 3. 상관관계 분석
- **피어슨 상관계수**: r = Σ[(xi - x̄)(yi - ȳ)] / √[Σ(xi - x̄)²Σ(yi - ȳ)²]
- **결정계수**: R² = r² (설명력 측정)

## 🔍 데이터 출처

- **인구 데이터**: 통계청 인구총조사
- **GDP 데이터**: 한국은행 국민계정
- **경제 전망**: 한국개발연구원(KDI) 보고서
- **국제 비교**: OECD 통계

## 📈 주요 예측 결과

### 1. 인구 구조 변화
- **2072년**: 생산연령인구와 고령인구 비율 균등화
- **2040년**: 인구 48.5백만명으로 감소 예상

### 2. 경제 전망
- **GDP 성장률**: 연평균 1.5-2.0% 수준 둔화
- **1인당 GDP**: 미국 대비 75% 수준에서 정체

### 3. 정책적 시사점
- 생산성 향상의 필요성
- 인구정책의 중요성
- 경제구조 개편 필요

## 🤝 기여 방법

### 1. 이슈 제보
- 버그 발견 시 Issues 탭에서 제보
- 개선 제안 환영

### 2. 풀 리퀘스트
```bash
# 포크 후 브랜치 생성
git checkout -b feature/improvement

# 변경사항 커밋
git commit -m "Add new analysis feature"

# 푸시 후 PR 생성
git push origin feature/improvement
```

### 3. 데이터 업데이트
- 최신 통계 데이터 추가
- 새로운 분석 지표 제안

## 📝 라이선스

이 프로젝트는 MIT 라이선스 하에 공개되어 있습니다. 교육 목적으로 자유롭게 사용 가능합니다.

## 📞 연락처

- **GitHub**: [@SUNGWOOLEE-AI](https://github.com/SUNGWOOLEE-AI)
- **Email**: sungwoo.sw@gmail.com

## 🏆 활용 사례

### 교육 기관
- 고등학교 수학 수행평가
- 대학교 통계학 과제
- 경제학 데이터 분석 실습

### 연구 분야
- 인구학 연구
- 경제학 분석
- 정책 연구

---

**⚡ 수학의 힘으로 미래를 예측해보세요!**

이 프로젝트가 도움이 되었다면 ⭐ 스타를 눌러주세요!
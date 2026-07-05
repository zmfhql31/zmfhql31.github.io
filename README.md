# yeonubot 랜딩 페이지 (GitHub Pages)

yeonubot 제품 소개 페이지 — Riot 프로덕션 앱 신청의 Product URL용.

## 구성

- `index.html` — 제품 소개(기능·티어 인증 흐름·데이터 정책·Riot 법적 고지)
- `terms.html` — 이용약관
- `privacy.html` — 개인정보 보호 정책
- `riot.txt` — (나중에) 라이엇 도메인 검증 파일 — 포털이 값을 주면 이 저장소 루트에 추가

## 올리는 방법 (한 번만)

1. GitHub에서 새 저장소 생성 — 이름을 **정확히 `zmfhql31.github.io`** 로 (public)
2. 이 폴더의 파일들(index.html, terms.html, privacy.html, README.md)을 저장소에 업로드
   - 웹에서: 저장소 → Add file → Upload files → 드래그&드롭 → Commit
3. 몇 분 뒤 **https://zmfhql31.github.io/** 에서 페이지 확인
   (사용자 사이트 저장소는 Pages가 자동 활성화됨 — 설정 불필요)

## 라이엇 도메인 검증 (신청 후)

포털이 riot.txt 내용(고유 코드)을 주면:
1. 저장소에 `riot.txt` 파일 생성 → 코드 붙여넣기 → Commit
2. https://zmfhql31.github.io/riot.txt 로 접근되는지 확인 → 포털에서 검증 진행

## 수정할 때

파일을 수정해 커밋하면 1~2분 내 반영. **이 저장소는 public 유지**
(무료 플랜은 private 저장소로 Pages 서빙 불가 + Product URL은 심사 후에도 살아 있어야 함).
봇 소스코드는 이 저장소에 올리지 않는다.


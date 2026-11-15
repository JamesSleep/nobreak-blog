# no break; 블로그 스펙

## 기술 구성
- Astro 공식 블로그 템플릿으로 시작 (`npm create astro@latest -- --template blog`)
- 글: 마크다운 (src/content)
- 호스팅: Cloudflare Pages (GitHub 연동)
- 댓글: Giscus (나중에 추가)
- 폰 글쓰기 CMS: 보류 (필요하면 나중에)

## 디자인
- 블로그 이름: `no break;`
- 다크 테마만 (전환 버튼 없음)
- 가운데 한 줄 배치, 폭 약 700px, 사이드바 없음
- 배경: GitHub 다크 느낌의 짙은 남색/회색
- 글자: 밝은 회색
- 포인트 색: 주황 (링크, hover에만)
- 폰트: 본문 Pretendard, 코드 D2Coding 또는 JetBrains Mono
- 코드 블록: 모바일에서 가로 스크롤
- 모바일 반응형 필수

## 페이지
- 메인: 글 목록 (제목, 날짜, 한 줄 요약)
- 글 상세: 제목, 날짜, 본문, 댓글
- About: 없음 (템플릿에서 삭제). 푸터에 GitHub 링크만
- 태그/검색/카테고리: 글 쌓이면 추가

## Claude 사용량 절약 규칙
- 서브에이전트/플러그인 쓰지 않기
- 작업 하나 끝나면 /clear
- 수정할 파일 경로를 직접 지정해서 요청
- 글 작성, 자잘한 CSS는 직접

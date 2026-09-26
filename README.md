# Hwajun Lee (이화준) — Academic Homepage

GitHub Pages로 배포되는 정적 홈페이지입니다. 빌드 도구 없이 `index.html` 한 파일로 구성됩니다.

## 수정 방법
- 모든 내용은 `index.html`에 있습니다.
- 영문은 `class="en"`, 국문은 `class="ko"` 요소에 들어 있습니다. 두 언어를 함께 고쳐 주세요.
- 논문은 `<section id="publications">` 안에 연도별로 있습니다. 새 논문은 해당 연도 `<ol class="pub-list">`에 `<li class="pub" data-theme-tags="cmr" data-type="article" lang="en">` 형식으로 추가합니다.
  - 주제 태그: `cmr`(민군관계), `nk`(북한·핵), `tj`(전환기 정의·기억), `sec`(안보·정체성) — 여러 개는 공백으로 구분
  - `data-type="book"`이면 '저서' 필터에 포함됩니다.
- 하단의 최종 수정일도 함께 바꿔 주세요.

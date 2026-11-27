# privacy-policy

Annuums 서비스별 개인정보처리방침을 관리하는 리포지터리입니다. GitHub Pages(Jekyll)로 배포됩니다.

- 사이트: https://annuums.github.io/privacy-policy/

## 새 방침 추가하기

1. `TEMPLATE.md`를 `_policies/<slug>.md`로 복사합니다. (예: `_policies/my-app.md`)
2. 앞부분(front matter)의 `title`, `effective_date`, `last_updated`와 본문의 `{ }` 항목을 채웁니다.
3. `main`에 푸시하면 1~2분 후 `https://annuums.github.io/privacy-policy/<slug>/`로 게시되고, 목록 페이지에도 자동으로 추가됩니다.

앱스토어/플레이스토어에는 각 방침의 개별 URL을 등록하세요. 방침을 수정할 때는 `last_updated`를 갱신하고, 중요한 변경은 git 이력으로 추적됩니다.

## 로컬 미리보기 (선택)

```sh
gem install bundler jekyll github-pages
jekyll serve --baseurl /privacy-policy
```

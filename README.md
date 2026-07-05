# .github

`robotics-study` 조직의 메타 저장소입니다. 조직 프로필과 공용 설정을 담습니다.

## 구성

| 경로 | 용도 |
|------|------|
| [`profile/README.md`](profile/README.md) | 조직 프로필 페이지 — [github.com/robotics-study](https://github.com/robotics-study) 상단에 노출 |
| `profile/assets/` | 프로필 배너 · 아바타 SVG (라이트/다크 테마) |

> 조직 홈사이트(랜딩 페이지)는 별도 저장소 [`robotics-study.github.io`](https://github.com/robotics-study/robotics-study.github.io) 에서 관리합니다 → https://robotics-study.github.io/

## 배너 수정

`profile/assets/banner-{light,dark}.svg` 를 편집합니다. `navigation` 저장소의 [docs 사이트](https://robotics-study.github.io/navigation/) 디자인(indigo→cyan 그라디언트 · Inter · path-planning 모티프)을 따릅니다.

프리뷰 렌더링:

```bash
# 브라우저에서 SVG 직접 열거나
open profile/assets/banner-dark.svg
```

새 주제를 추가하면 `profile/README.md` 의 **공부할 수 있는 주제** 표와 홈사이트([`robotics-study.github.io`](https://github.com/robotics-study/robotics-study.github.io)) 카드를 함께 갱신합니다.

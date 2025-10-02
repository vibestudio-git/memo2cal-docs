## 링크 연동 가이드 (내부 참고)

비공개 개발 저장소(main)와 공개 문서 저장소를 함께 운영할 때 참고할 연결 지침입니다.

1. **Chrome Web Store 설명란**

    - "도움말" 또는 "Support" 섹션에 `https://github.com/master-Kwon/memo2cal-docs` GitHub Pages URL 추가
    - 버전 업데이트 시 `docs/release-notes.md`의 하이라이트를 요약해 게시

2. **확장 팝업 푸터**

    - "도움말" 링크 → GitHub Pages의 `getting-started` 문서 URL
    - "버전 정보" 텍스트는 release-notes 상단 버전과 동기화

3. **비공개 main repo**

    - README 최상단에 "사용자 문서" 배지/링크 추가 (`memo2cal-docs`)
    - 배포 파이프라인 또는 체크리스트에 "공개 문서 업데이트 여부" 항목 포함

4. **지원 채널**

    - GitHub Issues 템플릿에 공개 repo URL 삽입
    - Notion/이메일 문의 주소는 `support.md`와 동일하게 유지

5. **버전 동기화 절차**
    - main repo에서 새 릴리즈 태그 생성 시, 같은 릴리즈 노트를 `release-notes.md`에 추가
    - Chrome Web Store 제출 전에 공개 문서 PR 검토 완료

6. **GitHub Pages 게시 절차**
    - 새 공개 repo(`memo2cal-docs`)를 생성한 뒤 루트에 문서를 업로드하고 `main` 브랜치로 푸시
    - repo Settings > Pages에서 Branch = `main`, Folder = `/ (root)`로 지정 후 저장
    - 발급된 Pages URL(예: `https://<계정>.github.io/memo2cal-docs/`)을 Chrome Web Store, 확장 푸터, 비공개 main repo README에 반영

> 위 지침은 운영 중 변경될 수 있으며, 문서 repo README 하단에 최신 링크 정보를 명시합니다.

# 파일럿001 미리보기 배포 안내

## 검증된 로컬 미디어

- 30초 미리보기: `preview.mp4` (395,564 bytes)
- 미리보기 SHA-256: `c989e79f8b07e25bb570a7b00f3d5781c56edb93ceb92ac373655ed62cb3ae01`
- 전체 가편집본: 29분 51.795초, 80,260,419 bytes
- 전체 영상 SHA-256: `36b4a72ba4ff1618e51cbad0dc8491070a11985cb8575a04354c549e716b0896`

## 배포 절차

1. ChatGPT에서 `visual_radio_30초_배포준비_패키지.zip` 다운로드 및 압축 해제.
2. ZIP의 `preview.mp4`와 `index.html`을 GitHub 저장소에 함께 업로드. 기존 `index.html`을 덮어쓸 경우 현재 프로젝트 소개 페이지가 미리보기 페이지로 바뀌므로, **기존 페이지를 보존하려면 `preview/index.html`과 `preview/preview.mp4`로 업로드**.
3. Settings → Pages → Build and deployment → Source = GitHub Actions.
4. Actions 배포 성공과 실제 MP4 재생 확인.

> 현재 영상 바이너리는 GitHub에 업로드되지 않았으며, 이 문서는 배포 방법과 로컬 검증 상태를 기록합니다. 최종 완성 영상이 아닙니다.

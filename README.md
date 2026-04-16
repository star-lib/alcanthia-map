# 알켄시아 배치테스트

알켄시아용 밭 배치 테스트 사이트입니다.

## 주요 기능

- 기본 밭 배치 표시
- 외곽 클릭으로 밭 확장
- 작물 배치 및 제거
- 물, 중독, 버프 범위 시각화
- 시간당 생산량 집계
- 드래그 이동, 확대/축소
- 배치도 이미지 복사
- GitHub Pages 자동 배포

## 로컬 실행

```powershell
npm install
npm run serve
```

브라우저에서 `http://127.0.0.1:4173` 를 열면 됩니다.

## 검증

```powershell
npm run verify
```

## 배포

`main` 브랜치에 푸시하면 GitHub Actions를 통해 GitHub Pages로 배포됩니다.

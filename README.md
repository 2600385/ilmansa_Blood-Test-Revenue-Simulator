# ilmansa_Blood-Test-Revenue-Simulator

일만사 × 혈액검사 수익 시뮬레이터 (원장님 전용) — 정적 단일 HTML 페이지.

## 배포 (Vercel)

빌드 과정이 필요 없는 순수 정적 HTML입니다. Vercel에서 이 저장소를 Import 하면 자동으로 배포됩니다.

1. https://vercel.com/new 에서 이 GitHub 저장소(`2600385/ilmansa_blood-test-revenue-simulator`)를 Import
2. Framework Preset: **Other** (자동 감지됨)
3. Build Command / Output Directory: 비워둠 (루트의 `index.html`이 그대로 서빙됨)
4. Deploy

로컬에서 확인하려면 `index.html`을 브라우저로 열거나 `npx serve .` 실행.
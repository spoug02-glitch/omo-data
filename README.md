# omo-data

「자격증 지원 조회」(exam-fee-support) 앱인토스 미니앱의 원격 데이터 CDN.

`dataset.json` 하나만 담는다 — 88개 시군구의 자격증 응시료 지원 조건·금액·공고 링크를
정리한 것으로, 각 지자체가 공개한 공고 내용을 구조화한 것뿐이다.

생성: `OMO/data/build-dataset.mjs` (OMO 앱 저장소). 갱신 절차·검증 규칙은 그 저장소의
`CLAUDE.md` Deploy 절 참고.

release ordering marker — 2026-07-10 01:00 KST
Why: 전 release가 같은 커밋을 target하면 created_at 동일 → GitHub 목록 정렬 무작위 → 구 updater(부분창)가 최신 release를 못 봄.
각 release 발행 직전 이 파일을 갱신해 target 커밋의 created_at을 유일화한다.

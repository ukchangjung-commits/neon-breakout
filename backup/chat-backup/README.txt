neon-breakout 대화 백업 폴더
- 대화 데이터: data/part####.js (일반 텍스트/JSON, 메모장으로도 읽힘, 완전본·요약 없음)
- 열람: viewer.html 더블클릭 (검색·접기·MD/JSON 내보내기)
- 뷰어/manifest 손상 시: 다른 프로젝트 폴더의 viewer.html 복사 또는 {마감} 재실행 → data/ 그대로면 복구
- 한 청크 손상돼도 나머지는 열람 가능(그 구간만 누락, 뷰어가 표시)
- 매 {마감}마다 새 메시지만 새 청크로 추가(중복 없음). 상태: .backup-state.json
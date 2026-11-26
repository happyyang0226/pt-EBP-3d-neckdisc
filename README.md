# 근거기반 목 디스크(C5-C6) 병태생리 3D 시뮬레이터

청암대학교 물리치료과 강의용 웹앱. 목뼈 척추사이원반 탈출(C5-C6)의 발생원인부터 중재까지 11단계를 단계별 3D 장면으로 보여 준다.

## 주요 기능
- 11단계 병태생리 설명과 단계별 3D 장면(Three.js r128). 라벨을 누르면 용어를 찾아 준다.
- 내레이션에 맞춰 카메라가 움직이는 안내 투어와 정상/압박 비교 보기
- 단계별 확인 문제 10문항(총 110문항, [QUIZ.md](QUIZ.md))과 해설, 학생 결과 내보내기, 교수용 결과 화면·CSV
- 근거 검색: PubMed(NCBI E-utilities 직접 호출), PEDro·Consensus·SciSpace 바로가기. PMID·PMCID·DOI를 표시하고 초록을 한국어로 번역한다(MyMemory).
- 학생 필기, 용어 찾기, 교수용 내용 수정(Ctrl/⌘+Shift+E)

## 실행
정적 파일 하나(`index.html`)로 되어 있다. 브라우저로 열거나 Vercel 등 정적 호스팅에 올리면 된다.
claude.ai artifact에서 열면 PubMed·Consensus·SciSpace 커넥터 검색과 Claude 번역을 쓴다.

## 참고
- 의학용어는 의학용어 6판 기준이다.
- 문항·해설·용어 뜻은 AI가 초안을 쓴 것이므로 교수 검토 후 사용한다.
- 필기·퀴즈 기록은 각 브라우저의 localStorage에만 저장된다.

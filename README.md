# jggm-electronic-document

이 레포지토리는 국립중앙박물관 소장 조선총독부박물관 문서를 XML 전자문서 편찬 연구 과정에서 생성한 jjgm.dtd 파일과 A_071.xml 파일을 제공합니다. 

## 특징

조선총독부박물관 문서를 전자문서로 설계, 편찬하는 연구에서 국사편찬위원회 한국사데이터베이스 dtd 파일과 일본외무성기록 자료, 주한일본공사관 기록, 조선왕조실록 xml 파일을 참고하였습니다.   

## 데이터

- 연구자의 작업 데이터: jjgm.dtd (작업완료일자: 2025.01.04)
- 연구자의 작업 데이터: A_071.xml (작업완료일자: 2025.01.04)
- Reference 폴더에는 설계 시, 참조한 선행 데이터(4건)들이 있다. 해당 데이터들은 다음과 같다.
<br> : histroy.dtd (국사편찬위원회 한국사데이터베이스 DTD, 작업완료일자: 2020.07.30 ver 1.4)
<br> : haf_000.xml (일본외무성기록 자료, 작업완료일자: 20220602)
<br> : jh_001.xml (주한일본공사관 기록, 작업완료일자: 20221103)
<br> : 2nd_waa_000.xml (조선왕조실록, 작업완료일자: 20221103)
- 조선총독부박물관 문서 수집 및 데이터 분석: 본 연구의 주 대상이 되는 국립중앙박물관 조선총독부박물관 문서에 대한 기초 탐색 과정에 해당하는 스크래핑 작업이다. 현재 국립중앙박물관 조선총독부박물관 문서에서 텍스트 형태로 수집할 수 있는 데이터는 권 목록, 문건 목록, 문서 목록에 해당되는 제목 텍스트이다. 해당 텍스트 데이터를 기반으로 확인할 수 있는 정보 범위를 파악하고자, 클라우드 기반의 무료 Jupyter 노트북 환경인 구글 코랩(Google Colab)에서 웹 스크래핑과 텍스트 추출 코드를 구성하고 실행하였다.

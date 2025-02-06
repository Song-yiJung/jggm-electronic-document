# 조선총독부박물관 문서 XML 기반 디지털 아카이브

## 개요 

이 레포지토리는 국립중앙박물관 소장 조선총독부박물관 문서를 XML 기반의 기계가독형 디지털 아카이브로 전환한 디지털 인문학 연구 결과물을 포함하고 있습니다. 조선총독부박물관 문서는 일제강점기 고적조사사업과 문화유산 관리 정책을 이해하는 데 중요한 사료이지만, 현재 아날로그 형태 또는 비기계가독형 디지털 자료로 제공되어 활용이 제한적입니다. <br>
본 연구는 특정 문서를 샘플 데이터로 선정하여 DTD와 XML 전자문서를 편찬함으로써 문서의 계층적 구조와 메타데이터를 체계화하였습니다. 이를 통해 검색성과 분석 가능성을 높이고, 연구자와 기관 모두가 활용할 수 있는 방안을 제시합니다. 또한, 다중 분류 체계 설계를 통해 연구자는 자신만의 분류 체계를 적용하여 심화된 분석과 학문적 통찰을 도출할 수 있으며, 대중은 검증된 문화유산 정보를 활용한 콘텐츠 제작이 가능합니다.<br>
- 연계 논문: 2월 28일 이후 제공

## 레포지토리 구성

조선총독부박물관 문서를 전자문서로 설계, 편찬하는 연구에서 국사편찬위원회 한국사데이터베이스 dtd 파일과 일본외무성기록 자료, 주한일본공사관 기록, 조선왕조실록 xml 파일을 참고하였습니다.   

### 산출 데이터 

#### 조선총독부박물관 문서 수집 및 데이터 분석
- 설명: 국립중앙박물관 조선총독부박물관 문서에서 수집한 텍스트 데이터(권 목록, 문건 목록, 문서 제목 등).<br>
- 활용 도구: Google Colab을 사용한 웹 스크래핑 및 텍스트 추출.<br>
- 목적: 현재 국립중앙박물관 조선총독부박물관 문서 웹 서비스에서 제공하는 데이터 파악을 위한 기초 연구 단계.<br>

#### 연구자가 설계한 DTD 및 XML 데이터
- 연구자의 작업 데이터: jjgm.dtd (작업완료일자: 2025.01.04)<br>
- 연구자의 작업 데이터: A_071.xml (작업완료일자: 2025.01.04)<br>

### 참조 데이터

- 설명: Reference 폴더에는 설계 시, 참조한 선행 데이터(4건)들이 포함되어 있습니다.<br>
<br> : histroy.dtd (국사편찬위원회 한국사데이터베이스 DTD, 작업완료일자: 2020.07.30 ver 1.4)
<br> : haf_000.xml (일본외무성기록 자료, 작업완료일자: 20220602)
<br> : jh_001.xml (주한일본공사관 기록, 작업완료일자: 20221103)
<br> : 2nd_waa_000.xml (조선왕조실록, 작업완료일자: 20221103)

## 사용 안내

본 레포지토리 데이터를 연구나 프로젝트에 활용할 경우 아래 형식으로 인용해주세요:<br><br>

- 영문<br>
Jung, Song-yi. "XML-Based Digital Archive for Japanese Government-General Museum of Korea Documents." GitHub Repository: jggm-electronic-document. Last updated January 4, 2025. https://github.com/Song-yiJung/jggm-electronic-document.<br>
- 국문<br>
정송이. "조선총독부박물관 문서의 XML 기반 디지털 아카이브." GitHub 저장소: jggm-electronic-document. 최종 업데이트: 2025년 1월 4일. https://github.com/Song-yiJung/jggm-electronic-document.
<br><br>
## 연락
- 문의 사항이나 협업 제안은 이메일(songi113@hanmail.net)을 통해 연락주시기 바랍니다. 감사합니다.




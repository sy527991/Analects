ERD(Entity Relationship Diagram)<br/>
![image](https://github.com/user-attachments/assets/37fe4819-b3ae-47dc-b8e2-b08d58381617)

Concept:<br/>
Script:<br/>
Commentary:<br/>
Quotation:<br/>
Person:<br/>
Book:<br/>
https://docs.google.com/spreadsheets/d/1wUHv-DqDE-1Jj41ikoeoNrq6RF9xoQoQBjv9W2FEZO8/edit?gid=0#gid=0<br/>

-TEI 준수-<br/>
루트 엘리먼트(최상위요소): text <br/>

주석자 정보: person_ID:  <br/>
- 주희(PESN_1101), 정약용(PESN_1102), 오규 소라이(PESN_1103)<br/>

경문 그룹: group <br/>
group id="SCRT_1102" script_chapter="學而_01"<br/>

본문 원문: script<br/>
script script_title="學而時習之" script_speaker="子曰"<br/>
- script_title: 구절 제목 (보통 첫 구절)
- script_speaker: 인용의 화자, 보통 "子曰"

주석 블록: div<br/>
div id="COMT_1104" person_ID="PESN_1101"<br/>
- id: 코멘트 블록 ID<br/>
- person_ID: 이 코멘트를 단 인물의 ID<br/>

단일 주석: p<br/>
p target_Concept="學" quote_ID="QUOT_1105" mentioned="PESN_1107"  <br/>
- target_Concept: 해석 대상 개념 (예: 學, 習, 君子)<br/>
- quote_ID: 인용된 문헌이나 인물 인용 고유 ID<br/>
- mentioned: 인용된 인물이나 문헌 ID 예: '尹氏' (PESN_1107)<br/>
- comt_note: 부연 설명 (愚謂, 補曰, 駁曰 등)<br/>

XML 구조의 강점 <br/>
- 계층적 주석 관리: 원문 → 장(章) → 주석자 → 주석 단위로 세분화.<br/>
- 구체적인 개념 분석: target_Concept을 통해 특정 단어에 대한 다양한 해석 추적 가능.<br/>
- 인용 및 참고 추적: quote_ID, mentioned를 통해 어떤 인용이 누구에 의해 이루어졌는지 명확히 파악 가능.<br/>
- 주해 유형 구분: comt_note를 통해 단순 해석, 보충 설명, 반박 등 유형 분리 가능.<br/>

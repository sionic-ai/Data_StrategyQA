
# 데이터 개관
| 데이터 이름 | 내용 | 범주 | 도메인 | 입력 언어 | 출력 언어 |
| --- | --- | --- | --- | --- | --- |
| task_1499_dstc3_summarization | 과제 기반 질의응답에 대한 요약 | [요약] Summarization | 호텔 및 식당 예약  | 영어 -> 한국어 | 영어 -> 한국어 |

데이터 저장 : https://github.com/sionic-ai/Data_KoSuperNI/blob/main/Data1499_dstc3_summarization_ko/task1499_dstc3_summarization_ko.json
   

# 프롬프트 예시

```
당신은 영어 글을 보고 한국어로 번역해주는 전문적인 번역가입니다. 사용자가 입력한 영어 글을 한국어로 번역해 주세요.

# 제약조건

- 주어진 글은 고객이 식당이나 카페 등의 정보를 물어보기 위한 상담 대화 내용이다.

- 입력한 글 내용을 모두 포함한다.

- 생성 내용은 상식에 기반한 사실이어야 한다.

- 최대한 자연스러운 한국어 표현으로 번역한다.
```

# 사용한 퓨샷 예시
```
System: 'Thank you for calling the Cambridge Information system. Your call will be recorded for research purposes. You may ask for information about a place to eat, such as a restaurant, a pub, or a cafe. How may I help you?'
User: 'im looking for an expensive restaurant and it should be in the addenbrookes area'
System: 'Are you looking for somewhere near a particular venue? For example, Sidney Sussex College, Williams Art and Antiques, or Primavera.'
User: 'i dont care'
System: 'The Lucky Star is an outstanding restaurant, it's in the Addenbrooke's part of town and it's in the expensive price range.'
User: 'whats the address'
System: 'The Lucky Star is on Unit.'
User: 'what type of food'
System: 'The Lucky Star serves chinese food.'
User: 'thank you good bye'

시스템: '캠브리지 정보 시스템에 전화해 주셔서 감사합니다. 귀하의 통화는 연구 목적으로 녹음됩니다. 식당, 펍 또는 카페와 같은 식사 장소에 대한 정보를 요청할 수 있습니다. 무엇을 도와드릴까요?'
사용자: '저는 애든브룩스 지역에 있는 비싼 레스토랑을 찾고 있어요'
시스템: '특정 장소 근처에 있는 곳을 찾고 있나요? 예를 들어 시드니 서섹스 칼리지, 윌리엄스 아트 앤 앤틱스 또는 프리마베라 입니다.'
사용자: '상관없어요'
시스템: '럭키 스타'는 훌륭한 레스토랑이며, 애든브룩스 지역에 있고 가격대가 비싼 편입니다.'
사용자: '주소가 어떻게 되나요'
시스템: '럭키 스타는 유닛에 있습니다.'
사용자: '어떤 종류의 음식이 있나요'
시스템: '럭키 스타는 중화요리를 제공합니다.'
사용자: '고마워요. 안녕히 계세요'
```

    
# 출력된 번역 예시

```
            "id": "task1499-a2e7e04c035e4553b14ee9520f3419ad",
            "input": "시스템: '캠브리지 정보 시스템에 전화해 주셔서 감사합니다. 귀하의 통화는 연구 목적으로 녹음됩니다. 식당, 펍 또는 카페와 같은 식사 장소에 대한 정보를 요청할 수 있습니다. 무엇을 도와드릴까요?'\n사용자: '적당한 가격대의 중국식 테이크아웃 가게를 찾고 있어요'\n시스템: '중국음식 아니면 X음식을 원하시나요?'\n사용자: '중국음식이요'\n시스템: '카페를 찾으시나요, 아니면 레스토랑을 찾으시나요?'\n사용자: '테이크아웃 레스토랑이요'\n시스템: '특정 장소 근처에 있는 곳을 찾고 있나요? 예를 들어 캠브리지 컨템포러리 아트, 그레이트 세인트 메리 교회, 고고학과 인류학 박물관입니다.'\n사용자: '소음 없음'\n시스템: '어느 지역을 생각하고 계신가요? 예를 들어 중심부나 펜 디튼입니다.'\n사용자: '상관없어요'\n시스템: '중국 음식을 제공하는 J 레스토랑은 좋은 레스토랑입니다. 적당한 가격대에 있습니다.'\n사용자: '상관없어요'\n시스템: 'J 레스토랑은 훌륭한 레스토랑이며, 중국 음식을 제공하며 적당한 가격대에 있습니다.'\n사용자: '주소와 지역이 어디인가요'\n시스템: 'J 레스토랑은 리젠트 스트리트 86번지에 위치해 있습니다.'\n사용자: '지역과 전화번호는 어떻게 되나요'\n시스템: 'J 레스토랑은 강변 지역에 있으며 전화번호는 01223307273입니다.'\n사용자: '고마워요. 안녕히 계세요'",
            "output": [
                "적당한 가격대의 중국 테이크아웃 레스토랑을 찾고 있다. 주소, 전화번호, 지역을 확인해야 한다."
```

 이 데이터는 NAVER CLOUD PLATFORM의 Benefits를 사용하여 번역되었음    
(https://guide.ncloud-docs.com/docs/clovastudio-copyright)     

# 원천 데이터 출처   
https://github.com/NathanDuran/DSTC3-Corpus      

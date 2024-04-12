- 전체 데이터 세트에 대해 설명한 블로그 글           
https://blog.sionic.ai/Super_NaturalInstructions     
    
- 한국어 번역 데이터 세트 종류 
    
| 번호 | 유형 | 데이터 이름 | 간략한 데이터 설명 | 
| --- | --- | --- | --- | 
| 1 | 질의응답 | task169_strategyQA |특정 질문이 주어졌을 때 그 질문에 답하기 위해 알아야 할 사실을 기술<br>          위키피디아 기반 질의 응답 데이터 |
| 2 | 질의응답 | task191_HotpotQA  |이전의 데이터들이 질문 하나 답변 하나로 이루어져 있었것 것에 대해 사람의 대화는 하나의 짧은 질문과 대답으로 이루어지지 않는다는 문제 의식에서 구축된 데이터   | 
| 3 | 질의응답 | task192_HotpotQA  | task 191과 크게 차이가 나는 것은 아님<br>답변에 도달하기 위해 가져온 둘 이상의 문서간의 관계에 따라 멀티홉의 세부 내용 구분     |
| 4 | 질의응답 | task226_english_language_answer_relevance_classification |주어진 질의응답 쌍에서 어느 응답이 더 수용가능한지 평가       | 
| 5 | 요약 | task1290_Extreme-Summarization |  주어진 뉴스 기사 요약     |
| 6 | 요약 | task1499_dstc3_summarization_ko  | 캠브리지에 있는 펍, 레스토랑, 커피숍을 추천해달라는 자동화 시스템과 사용자 간의 대화와 이를 요약한 데이터            |

## StrategyQA 데이터 세트에 대한 추가 설명 
 https://blog.sionic.ai/StrategyQA 

 
## 출처
https://github.com/allenai/natural-instructions

```
@inproceedings{wang-etal-2022-super,
    title = "Super-{N}atural{I}nstructions: Generalization via Declarative Instructions on 1600+ {NLP} Tasks",
    author = "Wang, Yizhong  and
      Mishra, Swaroop  and
      Alipoormolabashi, Pegah  and
      Kordi, Yeganeh  and
      Mirzaei, Amirreza  and
      Naik, Atharva  and
      Ashok, Arjun  and
      Dhanasekaran, Arut Selvan  and
      Arunkumar, Anjana  and
      Stap, David  and
      Pathak, Eshaan  and
      Karamanolakis, Giannis  and
      Lai, Haizhi  and
      Purohit, Ishan  and
      Mondal, Ishani  and
      Anderson, Jacob  and
      Kuznia, Kirby  and
      Doshi, Krima  and
      Pal, Kuntal Kumar  and
      Patel, Maitreya  and
      Moradshahi, Mehrad  and
      Parmar, Mihir  and
      Purohit, Mirali  and
      Varshney, Neeraj  and
      Kaza, Phani Rohitha  and
      Verma, Pulkit  and
      Puri, Ravsehaj Singh  and
      Karia, Rushang  and
      Doshi, Savan  and
      Sampat, Shailaja Keyur  and
      Mishra, Siddhartha  and
      Reddy A, Sujan  and
      Patro, Sumanta  and
      Dixit, Tanay  and
      Shen, Xudong",
    editor = "Goldberg, Yoav  and
      Kozareva, Zornitsa  and
      Zhang, Yue",
    booktitle = "Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing",
    month = dec,
    year = "2022",
    address = "Abu Dhabi, United Arab Emirates",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.emnlp-main.340",
    doi = "10.18653/v1/2022.emnlp-main.340",
    pages = "5085--5109",
}
```

# 2025_National_Language_Institute_AI_Speech_Review_Contest

## 국립국어원 AI 말평

## 팀 소개

- 팀명: 서당개
- 팀원: 윤찬영, 류시현, 김수진
- 수행 과제: 어문 규범

> 과제 공식 공지: [국립국어원 대회 공지 링크](https://kli.korean.go.kr/benchmark/taskBoardsOrdtm/boardsOrdtm/noticeView.do?page=0&recordId=289)

### 대회 일정

| 날짜 | 내용 |
|------|------|
| 6월 10일(화) | 과제용 말뭉치 및 기준 모델 공개 |
| 6월 11일(수) ~ 7월 31일(목) | 점수 및 답안 제출 (순위표 반영) |
| 8월 ~ 9월 | 말평 아레나 (사람 참여형 정성평가) |
| 10월 17일(금) | 수상작 선정 및 시상 (예정) |

---

## 과제 설명

- **목표**: 문장을 어문 규범에 맞게 교정하고, 그 이유를 설명하는 텍스트 생성 과제
- **활용 지식**:
  - 한글 맞춤법
  - 표준어 사정 원칙
  - 문장 부호 규정
  - 외래어 표기법 등
- **형식**:
  - 선택형: 주어진 표현 중 어문 규범에 맞는 표현 선택 + 이유 설명
  - 교정형: 문장을 수정 + 이유 설명
- **출력 형식 예시**: '표현A'가 옳다. 왜냐하면 '~'에 따른 표현이기 때문이다.
- **데이터 사용 제한**: 외부 데이터 및 증강 불가, 입력 형태 변환만 허용 (㉮ 유형)
- **데이터 형식**: JSON  
- 항목: `question`, `keyword`, `answer`, `train`, `validation`, `test` 세트 제공
- **기준 모델**: Qwen3-8B, HyperCLOVA X Text 1.5B  
- 🔗 [Baseline 코드 GitHub](https://github.com/teddysum/Korean_QA_RAG_2025)

---

## 주의사항

- 하루 최대 제출 5건
- 팀별 1개 과제만 최종 제출
- 외부 API(OpenAI 등) 사용 불가
- 모든 모델은 **단일 RTX 4090 (24GB)** 환경에서 구동 가능해야 함
- 모든 팀원은 [국립국어원 언어정보나눔터](https://kli.korean.go.kr/m/home.do#z) 회원이어야 함

---

## 참고 링크

- [공식 대회 공고](https://kli.korean.go.kr/benchmark/taskBoardsOrdtm/boardsOrdtm/noticeView.do?page=0&recordId=289)
- [국립국어원 언어정보나눔터](https://kli.korean.go.kr/m/home.do)
- [기준 모델 코드 - 어문 규범](https://github.com/teddysum/Korean_QA_RAG_2025)
- [기준 모델 코드 - 한국문화](https://github.com/teddysum/Korean_Culture_QA_2025)

# 4주차 프로젝트 연구일지

## 기본 정보

- **팀명**: Nice
- **프로젝트명**: 카페/블로그 게시글 자동 생성 시스템
- **주차**: 4주차

## 팀 구성원 활동 요약

| 이름       | 역할                              | 주요 활동                                                                                                                       | 다음 주 계획                                                                         |
| ---------- | --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| **이규범** | 팀장, NLP 모델 및 시스템 설계     | - 네이버 API와 ChatGPT API 사용법 숙지<br>- 사용자 질문에서 키워드 추출 및 검색 프로그램 개발 계획 수립<br>- 프로그램 개발 결정 | - 키워드 추출 및 검색 프로그램 개발<br>- LVLM 적용 방안 추가 연구                    |
| **김형훈** | 백엔드 개발 및 시스템 아키텍처    | - 네이버 API와 ChatGPT API 사용법 숙지<br>- 키워드 추출 및 검색 프로그램 개발 참여<br>- 프로그램 개발 결정                      | - 프로그램 개발 및 백엔드 연동<br>- 시스템 아키텍처 구체화                           |
| **홍윤재** | 데이터 처리 및 모델 구현          | - 관련 자료 조사<br>- 각종 API 사용법 학습 예정                                                                                 | - API 사용법 숙지 및 프로그램 이해도 향상<br>- 데이터 처리 과정에 API 통합 방안 연구 |
| **고승범** | 기술 연구 및 논문 분석            | 없음                                                                                                                            | - 없음                                                                               |
| **주석훈** | 시스템 통합 테스트 및 성능 최적화 | 없음                                                                                                                            | - 없음                                                                               |

## 주간 목표 달성도

| 목표                                               | 상태    | 비고                       |
| -------------------------------------------------- | ------- | -------------------------- |
| 네이버 API와 ChatGPT API 사용법 숙지               | 완료    | 이규범, 김형훈 수행        |
| 키워드 추출 및 검색 프로그램 개발 계획 수립        | 완료    | 이규범, 김형훈 수행        |
| 사용자 질문에서 키워드 추출 및 검색 기능 개발 결정 | 완료    | 예시를 통한 개발 방향 설정 |
| 관련 자료 조사 및 API 사용법 학습                  | 진행 중 | 홍윤재 수행 중             |

## 주요 성과 및 결과물

1. **네이버 API와 ChatGPT API 사용법 숙지**
2. **사용자 질문에서 키워드를 추출하고 네이버 API로 검색하는 프로그램 개발 계획 수립**
   - 예시:
     - 사용자 질문: "딥러닝에 대해서 블로그 게시글을 작성해줘"
     - 검색을 위한 키워드 추출: "딥러닝", "딥러닝의 정의", "딥러닝의 기초", "딥러닝의 예제"
3. **추출된 키워드를 전처리하여 네이버 검색 API를 사용해 정보를 수집하는 기술 개발 착수**
   - 키워드 전처리를 통해 보다 정확하고 관련성 높은 검색 결과를 얻을 수 있도록 기술 개발 중

## 기술적 도전 및 해결 방안

1. **도전 1**: 프로그램 이해도 부족 (홍윤재)
   - **해결 방안**: 각종 API를 직접 사용해보고 학습하여 이해도 향상 예정
2. **도전 2**: 키워드 전처리 및 검색 결과의 정확성 향상
   - **해결 방안**: 자연어 처리 기법을 적용하여 키워드의 의미를 파악하고, 불필요한 단어나 중복을 제거하여 검색 효율을 높이는 방안 연구 중

## 학습 내용

1. **네이버 API와 ChatGPT API 사용법 숙지**
   - **주요 내용**: 네이버 검색 API와 ChatGPT API를 활용하여 사용자 질문에서 키워드를 추출하고, 해당 키워드로 검색 결과를 가져오는 방법 학습
   - **적용 방안**: 사용자 질문 예시를 통해 키워드를 추출하고, 이를 네이버 API로 검색하여 결과를 게시글에 반영하는 프로그램 개발 예정
2. **키워드 전처리 및 정보 수집 기술 개발**
   - **주요 내용**: 추출된 키워드를 전처리하여 보다 정확한 검색 결과를 얻기 위한 기술 개발 착수
   - **적용 방안**: 불필요한 단어 제거, 동의어 처리, 키워드 확장 등을 통해 검색 효율을 높일 예정

## 다음 주 계획

1. **키워드 추출 및 검색 프로그램 개발**
   - 이규범과 김형훈이 사용자 질문에서 키워드를 추출하고, 네이버 API로 검색하는 기능을 개발할 예정
2. **API 사용법 숙지 및 프로그램 이해도 향상 (홍윤재)**
   - 각종 API를 직접 사용해보며 프로그램 이해도를 높일 예정
3. **LVLM (Large Vision Language Model) 적용 방안 추가 연구**
   - LVLM을 프로그램에 어떻게 삽입할지 연구하고 적용 방안을 구체화할 예정
4. **시스템 아키텍처 구체화 및 백엔드 연동**
   - 김형훈이 백엔드 아키텍처를 구체화하고 시스템에 연동할 예정
5. **기술 연구 및 논문 분석 (고승범)**
   - LVLM 및 관련 기술에 대한 논문을 분석하여 프로젝트에 적용할 수 있는 방안을 제시할 예정

## 기타 특이사항

- LVLM은 이번 주에 다루지 않았으며, 추후에 다시 찾아서 프로그램에 삽입할 예정
- 일부 팀원은 이번 주 활동 내용이 없음

## 팀 미팅 요약

- **일시**: 2024-09-17 15:00
- **참석자**: 이규범, 김형훈, 홍윤재
- **주요 논의 사항**:
  1. 네이버 API와 ChatGPT API 사용법 공유
  2. 키워드 추출 및 검색 프로그램 개발 계획 수립
     - 예시:
       - 사용자 질문: "딥러닝에 대해서 블로그 게시글을 작성해줘"
       - 검색을 위한 키워드 추출: "딥러닝", "딥러닝의 정의", "딥러닝의 기초", "딥러닝의 예제"
  3. 추출된 키워드를 전처리하여 네이버 검색 API로 정보를 수집하는 기술 개발 방안 논의
  4. 홍윤재의 프로그램 이해도 향상을 위한 지원 방안 논의
- **결정 사항**:
  1. 이규범과 김형훈이 사용자 질문에서 키워드를 추출하고, 추출된 키워드를 전처리하여 네이버 API로 검색하는 프로그램을 개발하기로 함
     - 예시를 통해 개발 방향을 구체화함
  2. 홍윤재는 각종 API를 사용해보며 프로그램 이해도를 높이기로 함
  3. LVLM은 추후에 다시 다루기로 결정

---

작성일: 2024-09-19
작성자: 이규범

# EMR OCR Project

병원 EMR 스캔파일(외부 차트)에서 데이터를 자동 추출하는 OCR + LLM 프로젝트

## 커리큘럼

| 주차 | 주제 | 내용 |
|------|------|------|
| 1 | 멀티모달 LLM | GPT-4o에 EMR 이미지를 넣어 텍스트 추출 |
| 2 | Structured Output | 추출 텍스트 → JSON 구조화 (환자명, 진단명, 처방 등) |
| 3 | End-to-End 파이프라인 | 이미지 → OCR → 구조화 → CSV 일괄 자동화 |
| 4 | Agent / 자동화 | Tool use로 다단계 작업 (코드 매핑, 청구 확인 등) |

## Colab에서 열기

```
https://colab.research.google.com/github/{계정}/{레포}/blob/main/week1-multimodal/week1_multimodal.ipynb
```

## 준비물

- OpenAI API 키 ([발급](https://platform.openai.com/api-keys))
- Google 계정 (Colab 실행용)

## 폴더 구조

```
emr_samples/          샘플 EMR 스캔 이미지 (병원별 1개씩)
week1-multimodal/     멀티모달 LLM으로 이미지 텍스트 추출
week2-structured-output/  추출 텍스트 구조화
week3-pipeline/       일괄 처리 파이프라인
week4-agent/          AI Agent 자동화
```

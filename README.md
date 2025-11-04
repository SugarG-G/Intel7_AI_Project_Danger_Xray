# Intel7_AI_Project_Danger_Xray

## 프로젝트 소개
- X-ray 영상에서 위험물을 자동으로 검출하여 사람이 수동으로 판독할 때 발생할 수 있는 실수를 줄이는 것을 목표로 한 프로젝트입니다.
- 본 문서는 Intel AI Class(Intel_AI_Edge_Academy_7) 발표자료를 기반으로 작성되었습니다.

## 목표
- X-ray 영상을 사람이 분석하여 발생하는 실수를 방지하고, 보다 신뢰할 수 있는 검출 결과를 제공하는 시스템 구축

## 데이터셋
- 총 1,147장의 X-ray 이미지 사용
- 세부 클래스/라벨 구성 및 수집·전처리 상세는 추후 보완 예정

## 모델 및 접근 방식
- Task: 객체 검출(Object Detection)
- 실험한 모델
  - ResNeXt101-ATSS
  - MobileNetV2-ATSS
  - YOLOX-TINY

## 결과 (발표자료 기준)
- ResNeXt101-ATSS: 97% (Score)
- MobileNetV2-ATSS: 91% (Score)
- YOLOX-TINY: 91% (Score)
- 발표 슬라이드에는 평가 지표가 "Score"로 표기되어 있습니다. 정확한 지표 명칭/산출 방식은 추후 README에 상세화할 예정입니다.

## 후기/교훈
- "Dataset Important?" — 데이터셋의 품질과 구성 중요성 재확인
- "What Should I Choose?" — 모델/전략 선택의 중요성 고찰

## 발표자료
- 발표 PDF: `발표자료/X-Ray_detect.pdf`
- 작성: 윤치영

> 사용법(환경 설정, 학습/추론 스크립트 등)은 프로젝트 코드 정리 후 추가 예정입니다.

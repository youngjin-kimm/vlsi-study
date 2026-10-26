# VLSI Study

한국어로 읽고 조작하는 VLSI 학습 사이트입니다.

https://youngjin-kimm.github.io/vlsi-study/

## 구성

- VLSI Basic, STA & SI, Extraction & DFM, Low Power, Physical Design
- 48개 챕터, 48개 시각 실험
- LIB·SDF·SPEF·DEF의 가상 예제와 그림 연결
- Time borrowing, GBA/PBA, CRPR, RC corner, CMP, Antenna, ICG, 전원 도메인 실험
- 면접 문답, 영상, 산업·직무 안내, 도서, 논문 읽기, 채용 자료 링크
- 원문 주제 대응표: 관련 장과 아직 상세히 다루지 않은 항목 구분
- 검색, 학습 기록, 다크 모드, 모바일 화면, 그림 확대

## 실행과 배포

별도 빌드나 외부 라이브러리가 없습니다. 저장소 루트에서 `python -m http.server 8000`으로 실행하거나 index.html을 직접 열 수 있습니다.

GitHub Pages는 main 브랜치의 / (root)를 배포합니다. 루트 파일을 수정해 커밋하면 Pages가 다시 배포됩니다.

## 파일

- content.js: 최초 16장과 기본 용어·출처
- expanded.js: 보충 32장, 카테고리·참고 자료
- app.js: 기본 화면·실험 로직
- expanded-labs.js: 보충 실험의 조작값·SVG·교육용 계산
- expanded-ui.js: 분야별 탐색·자료실·주제 대응표
- style.css: 반응형 스타일

## 자료와 모델

VLSI Expert의 주제를 참고하고 SoCBook의 설명·실험 구성에서 영감을 받았습니다. 공식 번역·제휴 사이트가 아닙니다. 문장과 그림·실험은 독립 작성했으며 각 장에서 주제 참고 링크를 제공합니다. 원문 개별 글의 일대일 복제본이 아닙니다.

수치는 교육용 가상 값·근사 모델입니다. 실제 PDK·라이브러리·EDA 검증을 대체하지 않습니다. 파일 실습은 고정된 작은 예시를 생성하며 임의 LIB/SDF/SPEF/DEF의 전체 parser가 아닙니다. 각 장의 실무 한계 설명을 확인하세요.

학습 기록과 테마는 해당 브라우저 localStorage에만 저장됩니다.

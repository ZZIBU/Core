# CoFiler

이미지 파일 저장 및 처리를 지원한다.

## 프로젝트의 목적과 의도
- Golang 숙련도를 높인다. 추후 argoCD와 같은 오픈소스에 기여할 수 있도록 문법, 코드 스타일 등에 익숙해지기 위함이다.
- Gin 프레임워크 사용법을 익혀 Golang 서버 개발의 특징을 파악한다. 특히 Go의 강력한 특징인 context와 고루틴, 고채널에 익숙해질 수 있도록 한다.
- MongoDB를 통해 NoSQL에 익숙해진다. MongoDB의 쿼리를 사용해보고 NoSQL의 특징 및 주의점을 학습한다. RDB 쿼리와의 차이를 알고 데이터 구조에 따른 적절한 DB 선택 방법을 알기 위함이다.
- gRPC 프로토콜을 학습한다. gRPC가 마이크로서비스간의 효율적인 통신에 어떻게 도움이 되는지 http api를 함께 작성하고 비교하며 학습한다.

## 기술 스택
언어 : Go 1.21 +
서버 : Gin 1.10.0<br>
저장소 : MongoDB <br>
운영 : Github Actions CI, ArgoCD <br>
인프라 : AWS (k3s?) <br>

## 추가 기능 및 향후 방향성 간략 정리
- [ ] PDF 등 다양한 확장자를 가진 파일을 처리할 수 있는 범용 미디어 서버로 발전시킨다.
- [ ] [Tagify](https://github.com/ZZIBU/Tagify)에서 개발 중인 LLM 기반 파일 검색 서비스와 연동한다.

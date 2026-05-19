# 영선북스

영선북스 도서의 예제 코드, 실습 자료, 보조 프로젝트를 관리하는 공식 GitHub 조직입니다.

모든 시리즈의 실행 가능한 예제 코드는 **[book-examples](https://github.com/yeongseon-books/book-examples)** 모노레포에서 관리됩니다. 각 예제는 ko/en 양 언어로 제공되며 pytest로 검증됩니다.

## 저장소 구조

| 저장소 | 설명 |
|---|---|
| [book-content](https://github.com/yeongseon-books/book-content) | 기술서·웹북·블로그 시리즈 원고 (canonical content) |
| [book-examples](https://github.com/yeongseon-books/book-examples) | 전 시리즈 예제 코드 모노레포 (92개 시리즈) |
| [mkdocs-ebook](https://github.com/yeongseon-books/mkdocs-ebook) | MkDocs → EPUB/PDF/HTML 변환 툴킷 |
| [book-public-assets](https://github.com/yeongseon-books/book-public-assets) | 외부 발행용 공개 이미지 자산 (GitHub Pages CDN) |

## 시리즈 예제 코드

모든 예제는 [`book-examples`](https://github.com/yeongseon-books/book-examples) 내 디렉토리로 구성됩니다.

### AI

| 디렉토리 | 설명 |
|---|---|
| [ai-agent-101](https://github.com/yeongseon-books/book-examples/tree/main/ai-agent-101) | AI Agent 개념부터 운영까지 |
| [ai-app-patterns-101](https://github.com/yeongseon-books/book-examples/tree/main/ai-app-patterns-101) | LLM 앱 설계 패턴 |
| [ai-data-preparation-101](https://github.com/yeongseon-books/book-examples/tree/main/ai-data-preparation-101) | AI 모델 데이터 준비 |
| [ai-evaluation-101](https://github.com/yeongseon-books/book-examples/tree/main/ai-evaluation-101) | LLM 앱 정량 평가 |
| [ai-safety-guardrails-101](https://github.com/yeongseon-books/book-examples/tree/main/ai-safety-guardrails-101) | LLM 안전 장치 |
| [ai-web-dev-101](https://github.com/yeongseon-books/book-examples/tree/main/ai-web-dev-101) | AI API부터 배포까지 |
| [document-ingestion-101](https://github.com/yeongseon-books/book-examples/tree/main/document-ingestion-101) | 문서 수집 파이프라인 |
| [harness-engineering-101](https://github.com/yeongseon-books/book-examples/tree/main/harness-engineering-101) | AI Agent harness 설계 |
| [korean-ai-stack-101](https://github.com/yeongseon-books/book-examples/tree/main/korean-ai-stack-101) | 한국어 AI 스택 |
| [langchain-101](https://github.com/yeongseon-books/book-examples/tree/main/langchain-101) | LangChain API |
| [langgraph-101](https://github.com/yeongseon-books/book-examples/tree/main/langgraph-101) | 그래프 에이전트 |
| [llm-api-production-101](https://github.com/yeongseon-books/book-examples/tree/main/llm-api-production-101) | LLM API 프로덕션 패턴 |
| [llm-app-foundations-101](https://github.com/yeongseon-books/book-examples/tree/main/llm-app-foundations-101) | LLM 앱 기초 |
| [llm-apps-ops-101](https://github.com/yeongseon-books/book-examples/tree/main/llm-apps-ops-101) | LLM 앱 운영 |
| [llm-finetuning-101](https://github.com/yeongseon-books/book-examples/tree/main/llm-finetuning-101) | LoRA 파인튜닝 |
| [llm-from-scratch-101](https://github.com/yeongseon-books/book-examples/tree/main/llm-from-scratch-101) | 밑바닥부터 GPT |
| [multimodal-ai-101](https://github.com/yeongseon-books/book-examples/tree/main/multimodal-ai-101) | 멀티모달 AI |
| [rag-benchmark-101](https://github.com/yeongseon-books/book-examples/tree/main/rag-benchmark-101) | RAG 벤치마크 |
| [rag-deep-dive](https://github.com/yeongseon-books/book-examples/tree/main/rag-deep-dive) | RAG 심층 분석 |
| [vector-search-101](https://github.com/yeongseon-books/book-examples/tree/main/vector-search-101) | 벡터 검색 |

### 프로그래밍 · CS · 소프트웨어 엔지니어링 · 데이터 · Azure

→ 전체 목록은 [book-examples README](https://github.com/yeongseon-books/book-examples#시리즈-목록)를 참조하세요.

## 예제 코드 규약

- **언어**: Python
- **테스트**: pytest 기반, `pip install -r requirements.txt && pytest -q`
- **오프라인 동작**: mock-only 기본 (실제 API는 `.env.example` 참조)
- **다국어**: `ko/`·`en/` 미러링

## 발행 채널

- **Tistory (한국어 블로그)**: <https://yeongseonchoe.tistory.com/>
- **Hashnode (영어 블로그)**: <https://hashnode.com/@yeongseon>
- **Medium**: <https://medium.com/@yeongseonchoe>

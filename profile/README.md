# 영선북스

영선북스 도서의 예제 코드, 실습 자료, 보조 프로젝트를 관리하는 공식 GitHub 조직입니다.

현재 **94개 시리즈**의 실행 가능한 예제 코드를 공개하고 있습니다. 모든 예제는 ko/en 양 언어로 제공되며 pytest로 검증됩니다.

## 인프라 저장소

| 저장소 | 설명 |
|---|---|
| [book-public-assets](https://github.com/yeongseon-books/book-public-assets) | 외부 발행용 공개 이미지 자산 (GitHub Pages CDN) |

## 시리즈별 예제 코드

### AI

| 시리즈 | 설명 |
|---|---|
| [llm-app-foundations-101](https://github.com/yeongseon-books/llm-app-foundations-101) | {'ko': 'LLM API 기초, 토큰, 프롬프트 엔지니어링 — 6부작.', 'en': 'LLM API basics, tokens, and prompt engineering in 6 parts.'} |
| [llm-api-production-101](https://github.com/yeongseon-books/llm-api-production-101) | {'ko': 'Structured Output, Tool Calling, Streaming, Caching, Retry, Rate Limit — 6부작.', 'en': 'Structured Output, Tool Calling, Streaming, Caching, Retry, and Rate Limit in 6 parts.'} |
| [vector-search-101](https://github.com/yeongseon-books/vector-search-101) | {'ko': '임베딩, FAISS, 유사도, 청크 전략 — 6부작.', 'en': 'Embeddings, FAISS, similarity search, and chunking strategies in 6 parts.'} |
| [langchain-101](https://github.com/yeongseon-books/langchain-101) | {'ko': 'LCEL, Runnable, Retriever, Tool Calling 기본, Streaming — LangChain API 사용법 6부작.', 'en': 'LCEL, Runnable, Retriever, Tool Calling, and Streaming — LangChain API in 6 parts.'} |
| [ai-app-patterns-101](https://github.com/yeongseon-books/ai-app-patterns-101) | {'ko': '챗봇, RAG Q&A, 문서비서, Agent, Workflow, Human-in-the-loop — LLM 앱 설계 패턴 6부작.', 'en': 'Chatbot, RAG Q&A, Document Assistant, Agent, Workflow, and HITL design patterns in 6 parts.'} |
| [rag-deep-dive](https://github.com/yeongseon-books/rag-deep-dive) | {'ko': 'LangChain · FAISS · RAGAS 소스로 따라가는 RAG 파이프라인 심층 분석 6부작.', 'en': 'A 6-part deep dive into RAG internals — LangChain, FAISS, and RAGAS source-pinned.'} |
| [rag-benchmark-101](https://github.com/yeongseon-books/rag-benchmark-101) | {'ko': 'RAG 품질 평가 6부작 — 평가 데이터셋, 임베딩/리트리버 비교, RAGAS, 의사결정 연결.', 'en': '6-part RAG evaluation guide — datasets, embedding/retriever comparison, RAGAS, product decisions.'} |
| [document-ingestion-101](https://github.com/yeongseon-books/document-ingestion-101) | {'ko': 'PDF 파싱, 메타데이터, 증분 인덱싱 — 6부작.', 'en': 'PDF parsing, metadata, and incremental indexing in 6 parts.'} |
| [langgraph-101](https://github.com/yeongseon-books/langgraph-101) | {'ko': '그래프 에이전트, 체크포인트, 멀티에이전트 — 6부작.', 'en': 'Graph agents, checkpoints, and multi-agent systems in 6 parts.'} |
| [ai-agent-101](https://github.com/yeongseon-books/ai-agent-101) | {'ko': 'AI Agent의 개념부터 Context Engineering, Tool Use, Workflow, Multi-Agent, Evaluation, 운영까지 배우는 실전 입문 시리즈.', 'en': 'A practical beginner guide to AI agents, from context engineering and tool use to workflows, multi-agent systems, evaluation, and production operations.'} |
| [harness-engineering-101](https://github.com/yeongseon-books/harness-engineering-101) | {'ko': 'AI Agent가 안정적으로 작업하도록 task, context, constraint, tool, test, feedback, approval, observability, production harness를 설계하는 입문 시리즈.', 'en': 'A beginner-friendly guide to designing task, context, constraint, tool, test, feedback, approval, observability, and production harnesses for reliable AI agents.'} |
| [ai-evaluation-101](https://github.com/yeongseon-books/ai-evaluation-101) | {'ko': 'LLM 애플리케이션을 정량적으로 평가하는 방법을 배우는 입문 시리즈. 평가 데이터셋 설계, 자동 채점, LLM-as-judge, 회귀 테스트, A/B 비교, 운영 평가까지 다룹니다.', 'en': 'A beginner-friendly guide to quantitatively evaluating LLM applications, covering dataset design, automated scoring, LLM-as-judge, regression testing, A/B comparison, and production evaluation.'} |
| [ai-safety-guardrails-101](https://github.com/yeongseon-books/ai-safety-guardrails-101) | {'ko': 'LLM 애플리케이션에 안전 장치를 적용하는 방법을 배우는 입문 시리즈. Prompt injection 방어, 출력 필터링, PII 감지, jailbreak 탐지, hallucination 방지, 감사 로깅까지 다룹니다.', 'en': 'A beginner-friendly guide to applying safety guardrails to LLM applications, covering prompt injection defense, output filtering, PII detection, jailbreak detection, hallucination prevention, and audit logging.'} |
| [llm-apps-ops-101](https://github.com/yeongseon-books/llm-apps-ops-101) | {'ko': '관측, 평가, 비용, 보안, 배포 — 6부작.', 'en': 'Observability, evaluation, cost, security, and deployment in 6 parts.'} |
| [ai-data-preparation-101](https://github.com/yeongseon-books/ai-data-preparation-101) | {'ko': 'AI 모델을 위한 데이터 준비 전 과정을 다루는 입문 시리즈. 수집, 정제, PII 익명화, 토큰화, 품질 필터링, 합성 데이터, 분할과 오염 통제, 프로덕션 파이프라인까지 배웁니다.', 'en': 'A beginner-friendly guide to end-to-end data preparation for AI models, covering collection, cleaning, PII anonymization, tokenization, quality filtering, synthetic data, splitting with contamination control, and production pipelines.'} |
| [llm-finetuning-101](https://github.com/yeongseon-books/llm-finetuning-101) | {'ko': 'LoRA, 데이터셋, 서빙 — 6부작 (선택).', 'en': 'LoRA, datasets, and serving in 6 parts (optional).'} |
| [llm-from-scratch-101](https://github.com/yeongseon-books/llm-from-scratch-101) | {'ko': 'PyTorch 2.x 로 토크나이저부터 챗봇까지, ~720 LOC 의 작은 GPT 9부작.', 'en': 'Build a tiny GPT from tokenizer to chatbot in ~720 LOC, in 9 parts.'} |
| [multimodal-ai-101](https://github.com/yeongseon-books/multimodal-ai-101) | {'ko': '텍스트 + 이미지 + 오디오 + 영상을 다루는 multimodal AI 입문 시리즈. CLIP, ViT, VLM, Whisper, Diffusion, multimodal RAG, video understanding을 production 관점에서 배웁니다.', 'en': 'A beginner-friendly guide to multimodal AI covering text + image + audio + video. Learn CLIP, ViT, VLMs, Whisper, Diffusion, multimodal RAG, and video understanding from a production lens.'} |
| [korean-ai-stack-101](https://github.com/yeongseon-books/korean-ai-stack-101) | {'ko': '한국어 임베딩, OCR, 국내 LLM API — 6부작.', 'en': 'Korean embeddings, OCR, and domestic LLM APIs in 6 parts.'} |
| [ai-web-dev-101](https://github.com/yeongseon-books/ai-web-dev-101) | {'ko': 'AI API 부터 배포까지, 초급 개발자를 위한 7부작.', 'en': '7-part guide for junior developers — from AI API basics to deployment.'} |
| [ax-practical-guide](https://github.com/yeongseon-books/ax-practical-guide) | {'ko': 'AX 도입 전략, 업무 자동화 사례, 조직 변화 관리.', 'en': 'Practical strategies for AI Transformation in real organizations.'} |

### 프로그래밍

| 시리즈 | 설명 |
|---|---|
| [computer-science-101](https://github.com/yeongseon-books/computer-science-101) | {'ko': '컴퓨터공학 전공에서 배우는 주요 과목들이 서로 어떻게 연결되는지 보여주는 입문 시리즈.', 'en': 'An introductory series showing how major computer science subjects connect to each other.'} |
| [python-101](https://github.com/yeongseon-books/python-101) | {'ko': 'Python을 처음 시작하는 사람을 위한 입문 시리즈. 설치와 venv부터 변수, 자료구조, 제어 흐름, 함수, 모듈, 파일 I/O와 예외, 클래스, 표준 라이브러리까지 다룹니다.', 'en': 'A beginner-friendly Python tour from install and venv through variables, data structures, control flow, functions, modules, file I/O and exceptions, classes, and the standard library.'} |
| [git-github-101](https://github.com/yeongseon-books/git-github-101) | {'ko': 'Git의 commit, branch, merge, rebase, pull request, issue, GitHub workflow를 배우는 개발 협업 입문 시리즈.', 'en': 'A beginner guide to Git and GitHub covering commit, branch, merge, rebase, pull request, issue, and GitHub workflow for collaborative development.'} |
| [linux-cli-101](https://github.com/yeongseon-books/linux-cli-101) | {'ko': '파일 탐색, 권한, 프로세스, grep, pipe, shell script, SSH 등 개발자가 반드시 알아야 할 Linux CLI 기본기를 다루는 시리즈.', 'en': 'A beginner series covering essential Linux CLI skills for developers — file navigation, permissions, processes, grep, pipes, shell scripting, and SSH.'} |
| [python-package-101](https://github.com/yeongseon-books/python-package-101) | {'ko': 'Python 프로젝트 구조, pyproject.toml, 의존성 관리, 빌드, PyPI 배포, 버전 관리, CLI 패키지, 문서화까지 배우는 패키징 입문 시리즈.', 'en': 'A beginner series covering Python packaging from project structure and pyproject.toml to dependency management, building, PyPI publishing, versioning, CLI packages, and documentation.'} |
| [pytest-101](https://github.com/yeongseon-books/pytest-101) | {'ko': 'pytest의 기본 문법, fixture, parametrization, mock, coverage, CI 연동까지 배우는 실전 테스트 입문 시리즈.', 'en': 'A beginner series on pytest covering assertions, fixtures, parametrization, mocking, coverage, and CI integration.'} |
| [oop-101](https://github.com/yeongseon-books/oop-101) | {'ko': '클래스, 캡슐화, 상속, 다형성, 추상화, SOLID 원칙까지 객체지향의 핵심을 다루는 시리즈.', 'en': 'A series covering the essentials of OOP from classes and encapsulation to inheritance, polymorphism, abstraction, and SOLID principles.'} |
| [functional-programming-101](https://github.com/yeongseon-books/functional-programming-101) | {'ko': '순수 함수, 불변 데이터, 고차 함수, 클로저, 함수 합성까지 함수형 프로그래밍의 핵심을 Python으로 배우는 시리즈.', 'en': 'A beginner series on functional programming essentials in Python covering pure functions, immutability, higher-order functions, closures, and function composition.'} |
| [type-hints-python-101](https://github.com/yeongseon-books/type-hints-python-101) | {'ko': 'Python type hint, Optional, Union, TypedDict, Protocol, Generic, mypy, Pydantic까지 타입 힌트 활용을 배우는 시리즈.', 'en': 'A beginner series on Python type hints covering basic annotations, Optional, Union, TypedDict, Protocol, Generic, mypy, and Pydantic.'} |
| [data-structures-python-101](https://github.com/yeongseon-books/data-structures-python-101) | {'ko': 'Python으로 배우는 자료구조 입문. list, dict, set, deque, 트리, 힙, 그래프를 직접 구현합니다.', 'en': 'A hands-on introduction to data structures in Python covering list, dict, set, deque, trees, heaps, and graphs.'} |
| [algorithms-python-101](https://github.com/yeongseon-books/algorithms-python-101) | {'ko': 'Python 기반으로 시간 복잡도, 탐색, 정렬, DP, BFS/DFS, 그리디 등 알고리즘 기본기를 다지는 시리즈.', 'en': 'A beginner series on algorithm fundamentals in Python covering time complexity, searching, sorting, recursion, dynamic programming, and greedy algorithms.'} |

### CS 핵심 과목

| 시리즈 | 설명 |
|---|---|
| [computer-science-major-101](https://github.com/yeongseon-books/computer-science-major-101) | {'ko': '컴퓨터학과 전공 과목 구성, 핵심 영역, 학습 순서, 졸업 전 역량까지 정리한 입문 시리즈.', 'en': 'An introductory series on computer science major curriculum, core areas, study order, and graduation skills.'} |
| [discrete-math-101](https://github.com/yeongseon-books/discrete-math-101) | {'ko': '명제, 집합, 함수, 증명, 조합, 그래프 등 컴퓨터공학에 직접 쓰이는 이산수학을 정리하는 시리즈.', 'en': 'An introductory series on discrete mathematics for computer science covering propositions, sets, functions, proofs, combinatorics, and graphs.'} |
| [math-for-cs-101](https://github.com/yeongseon-books/math-for-cs-101) | {'ko': '논리, 증명, 집합, 함수, 그래프, 조합, 확률, 선형대수, 미분, 정보이론까지 CS와 ML의 수학을 한 번에 정리하는 입문 시리즈.', 'en': 'An entry series covering the math behind CS and ML - logic, proofs, sets, functions, graphs, combinatorics, probability, linear algebra, calculus, and information theory.'} |
| [calculus-for-ml-101](https://github.com/yeongseon-books/calculus-for-ml-101) | {'ko': '함수, 기울기, 편미분, gradient, chain rule, 손실, 경사하강, backprop 직관까지 ML에 필요한 미분을 다지는 입문 시리즈.', 'en': 'An entry series covering functions, slopes, partial derivatives, gradients, chain rule, loss, gradient descent, and backprop intuition for ML.'} |
| [computer-architecture-101](https://github.com/yeongseon-books/computer-architecture-101) | {'ko': '데이터 표현, CPU와 명령어, 레지스터, 메모리 계층, 캐시, 파이프라인, 멀티코어까지 컴퓨터가 코드를 실행하는 방식을 처음 배우는 시리즈.', 'en': 'An introductory series on how computers execute code, covering data representation, CPU and instructions, registers, memory hierarchy, caches, pipelining, and multicore.'} |
| [data-structures-101](https://github.com/yeongseon-books/data-structures-101) | {'ko': '배열, 리스트, 스택, 큐, 해시, 트리, 힙, 그래프까지 자료구조의 큰 그림과 선택 기준을 다루는 시리즈.', 'en': 'An introductory series covering arrays, lists, stacks, queues, hash tables, trees, heaps, graphs, and how to choose the right data structure.'} |
| [algorithms-101](https://github.com/yeongseon-books/algorithms-101) | {'ko': '복잡도, 탐색, 정렬, 분할 정복, DP, 그리디, 그래프 알고리즘까지 알고리즘 설계 패턴을 배우는 시리즈.', 'en': 'An introductory series on algorithm design covering complexity, search, sorting, divide and conquer, dynamic programming, greedy, and graph algorithms.'} |
| [programming-languages-101](https://github.com/yeongseon-books/programming-languages-101) | {'ko': 'syntax, semantics, type system, scope, closure, memory model, interpreter/compiler 차이까지 PL 기초를 다지는 시리즈.', 'en': 'A foundational series on programming languages — syntax, semantics, type systems, scope, closures, memory model, and the interpreter vs compiler distinction.'} |
| [operating-systems-101](https://github.com/yeongseon-books/operating-systems-101) | {'ko': '프로세스, 스레드, 스케줄링, 동시성, 메모리 관리, 가상 메모리, 파일 시스템, 시스템 콜, 컨테이너까지 운영체제의 기본 개념을 다지는 시리즈.', 'en': 'A foundational series on operating systems covering processes, threads, scheduling, concurrency, memory management, virtual memory, file systems, system calls, and containers.'} |
| [computer-networks-101](https://github.com/yeongseon-books/computer-networks-101) | {'ko': 'IP, TCP, UDP, DNS, HTTP, TLS, 라우팅, 로드밸런서, WebSocket까지 인터넷 동작의 핵심을 정리하는 시리즈.', 'en': 'A foundational series on how the internet works — IP, TCP, UDP, DNS, HTTP, TLS, routing, load balancers, and WebSocket.'} |
| [database-systems-101](https://github.com/yeongseon-books/database-systems-101) | {'ko': '관계형 모델, SQL, 인덱스, 트랜잭션, isolation, 정규화, 쿼리 최적화, 복제까지 DBMS의 핵심을 다루는 시리즈.', 'en': 'A foundational series on relational databases — model, SQL, indexes, transactions, isolation, normalization, query optimization, and replication.'} |
| [distributed-systems-101](https://github.com/yeongseon-books/distributed-systems-101) | {'ko': 'failure model, consistency, replication, consensus, message queue까지 분산 시스템의 핵심 개념을 처음 배우는 시리즈.', 'en': 'A first walk through distributed systems — failure models, consistency, replication, consensus, leader election, and messaging.'} |
| [compilers-101](https://github.com/yeongseon-books/compilers-101) | {'ko': 'lexer, parser, AST, semantic analysis, IR, optimization, code generation까지 컴파일러 파이프라인을 처음 배우는 시리즈.', 'en': 'A first walk through the compiler pipeline — lexer, parser, AST, semantic analysis, IR, optimization, and code generation.'} |
| [information-security-101](https://github.com/yeongseon-books/information-security-101) | {'ko': '인증, 인가, 암호화, TLS, 웹 보안, secret 관리, 권한 최소화, 감사 로그까지 개발자 수준의 보안 기본을 다루는 시리즈.', 'en': 'Developer-level security basics - authentication, authorization, cryptography, TLS, web security, secrets, least privilege, and audit logs.'} |

### 소프트웨어 엔지니어링

| 시리즈 | 설명 |
|---|---|
| [software-engineering-101](https://github.com/yeongseon-books/software-engineering-101) | {'ko': '요구사항, 설계, 코드 리뷰, 테스트, 버전 관리, 문서화, 협업, 유지보수까지 소프트웨어 엔지니어링의 큰 그림을 다지는 시리즈.', 'en': 'The big picture of software engineering — requirements, design, code review, testing, version control, documentation, collaboration, and maintenance.'} |
| [clean-code-101](https://github.com/yeongseon-books/clean-code-101) | {'ko': '이름 짓기, 함수 분리, 조건문 단순화, 중복 제거, 오류 처리부터 리팩토링 기초까지 읽기 쉬운 코드를 쓰는 법을 다지는 시리즈.', 'en': 'Naming, small functions, simplifying conditionals, removing duplication, error handling, and refactoring fundamentals — practical Clean Code in ten essays.'} |
| [software-design-101](https://github.com/yeongseon-books/software-design-101) | {'ko': '관심사 분리, 모듈 경계, 의존성 방향, 인터페이스 설계, 계층 아키텍처를 통해 변경에 강한 코드를 설계하는 법을 다지는 시리즈.', 'en': 'Separation of concerns, module boundaries, dependency direction, interface design, and layered architecture — designing code that is easy to change.'} |
| [design-patterns-101](https://github.com/yeongseon-books/design-patterns-101) | {'ko': 'GoF 디자인 패턴을 Python 예시로 빠르게 훑고, 언제 쓰고 언제 피해야 할지 감을 잡는 시리즈.', 'en': 'A fast tour of the GoF design patterns in Python, with a clear sense of when to use them and when to avoid them.'} |
| [api-design-101](https://github.com/yeongseon-books/api-design-101) | {'ko': 'REST 기본부터 리소스 설계, HTTP method/status, schema, pagination, error, OpenAPI까지 쓰기 좋은 API를 설계하는 시리즈.', 'en': 'A practical tour of API design — REST basics, resources, HTTP methods/status, schemas, pagination, errors, and OpenAPI.'} |
| [web-development-101](https://github.com/yeongseon-books/web-development-101) | {'ko': 'HTML/CSS/JS, 브라우저, HTTP, 프론트/백엔드, 인증, DB, 배포까지 웹 개발 전체 흐름을 한 번에 보는 시리즈.', 'en': 'A whole-picture tour of web development — HTML/CSS/JS, the browser, HTTP, frontend and backend, auth, databases, and deployment.'} |
| [frontend-development-101](https://github.com/yeongseon-books/frontend-development-101) | {'ko': 'HTML/CSS, JavaScript, 컴포넌트, 라우팅, API 호출, 빌드까지 현대 프론트엔드 개발 전체 흐름을 다루는 시리즈.', 'en': 'An end-to-end tour of modern frontend development — HTML/CSS, JavaScript, components, routing, API calls, and bundling.'} |
| [backend-development-101](https://github.com/yeongseon-books/backend-development-101) | {'ko': 'HTTP 서버/라우팅/서비스/DB layer/인증/로깅/테스트/배포까지 백엔드 개발 전체 흐름을 다루는 시리즈.', 'en': 'An end-to-end tour of backend development — HTTP servers, routing, service and DB layers, auth, logging, testing, and deployment.'} |
| [testing-101](https://github.com/yeongseon-books/testing-101) | {'ko': 'Unit, Integration, E2E, Test Double, Mock, Coverage, CI 연동까지 테스트 전략 전반을 다루는 시리즈.', 'en': 'A complete tour of testing strategy — unit, integration, E2E, test doubles, mocks, coverage, and CI.'} |
| [containers-101](https://github.com/yeongseon-books/containers-101) | {'ko': 'Image, runtime, layer, Dockerfile부터 보안까지 컨테이너의 큰 그림을 입문자 관점에서 다룹니다.', 'en': 'A beginner-friendly tour of containers — images, runtimes, layers, Dockerfile, security, and how containers differ from VMs.'} |
| [docker-101](https://github.com/yeongseon-books/docker-101) | {'ko': 'Image, Container, Dockerfile, Volume, Network, Compose, 환경 설정, Python 앱 컨테이너화, 이미지 최적화, 배포 구성을 다루는 입문 시리즈.', 'en': 'Images, containers, Dockerfile, volumes, networks, Compose, configuration, Python apps, image optimization, and production-ready deploy.'} |
| [kubernetes-101](https://github.com/yeongseon-books/kubernetes-101) | {'ko': 'Pod, Deployment, Service, Ingress, ConfigMap/Secret, Volume, HPA, Helm까지 Kubernetes 기본 객체를 다루는 시리즈.', 'en': 'An entry series covering Kubernetes core objects from Pod, Deployment, Service, Ingress, ConfigMap/Secret, Volume, HPA to Helm.'} |
| [cloud-computing-101](https://github.com/yeongseon-books/cloud-computing-101) | {'ko': 'IaaS/PaaS/SaaS, 리전, 컴퓨트, 스토리지, 네트워크, 아이덴티티, 모니터링, 비용까지 클라우드 입문 시리즈.', 'en': 'A cloud computing primer covering IaaS/PaaS/SaaS, regions, compute, storage, network, identity, monitoring, and cost.'} |
| [serverless-101](https://github.com/yeongseon-books/serverless-101) | {'ko': 'FaaS, trigger/event, cold start, scaling, state, queue, observability, cost까지 서버리스 입문 시리즈.', 'en': 'An entry series covering FaaS, triggers/events, cold start, scaling, state, queues, observability, and cost.'} |
| [devops-101](https://github.com/yeongseon-books/devops-101) | {'ko': 'CI/CD, IaC, 환경 관리, 모니터링, 배포 전략, on-call까지 DevOps 입문 전반을 다루는 시리즈.', 'en': 'A DevOps starter — CI/CD, IaC, environment management, monitoring, deployment strategy, and on-call basics.'} |
| [github-actions-101](https://github.com/yeongseon-books/github-actions-101) | {'ko': 'Workflow, Job, Trigger, 테스트 자동화, 빌드 아티팩트, 배포, secret 관리까지 GitHub Actions 전반을 다루는 시리즈.', 'en': 'Workflows, jobs, triggers, test automation, build artifacts, deployment, and secrets — a complete GitHub Actions starter.'} |
| [observability-101](https://github.com/yeongseon-books/observability-101) | {'ko': 'Metric, log, trace, dashboard, alert, SLO 기초까지 운영 시스템의 가시성을 만드는 입문 시리즈.', 'en': 'Metrics, logs, traces, dashboards, alerts, and SLO basics to make production systems observable.'} |
| [incident-response-101](https://github.com/yeongseon-books/incident-response-101) | {'ko': 'Severity 분류, 초기 대응, 커뮤니케이션, 타임라인, RCA, 완화, 포스트모템, 재발 방지, 런북 작성까지 다루는 입문 시리즈.', 'en': 'An entry series covering severity, initial response, communication, timelines, RCA, mitigation, postmortems, prevention, and runbooks.'} |
| [sre-101](https://github.com/yeongseon-books/sre-101) | {'ko': '신뢰성, SLI/SLO/SLA, 에러 버짓, 인시던트와 포스트모템, toil 감소, 용량 계획까지 다루는 SRE 입문 시리즈.', 'en': 'An entry series covering reliability, SLI/SLO/SLA, error budgets, incidents and postmortems, toil reduction, and capacity planning.'} |
| [secure-coding-101](https://github.com/yeongseon-books/secure-coding-101) | {'ko': '입력 검증, 인증, 인가, secret 관리, SQL Injection, XSS/CSRF, dependency 취약점, 안전한 로깅까지 시큐어 코딩 입문 시리즈.', 'en': 'A beginner guide to secure coding covering input validation, auth, authz, secret management, SQL Injection, XSS/CSRF, dependency vulnerabilities, and safe logging.'} |
| [open-source-101](https://github.com/yeongseon-books/open-source-101) | {'ko': '라이선스부터 첫 오픈소스 프로젝트까지, 오픈소스 기여의 기본을 다지는 시리즈.', 'en': 'An entry series covering open source contribution from licenses to your first project.'} |
| [developer-career-101](https://github.com/yeongseon-books/developer-career-101) | {'ko': '개발자 커리어를 설계하는 법.', 'en': 'How to design a developer career.'} |
| [data-science-career-101](https://github.com/yeongseon-books/data-science-career-101) | {'ko': '데이터 직무 커리어를 설계하는 법.', 'en': 'How to design a data science career.'} |
| [portfolio-project-101](https://github.com/yeongseon-books/portfolio-project-101) | {'ko': '프로젝트 선정, README, 데모, 배포, 테스트, 의사결정 기록, 블로그, 면접 설명까지 다루는 입문 포트폴리오 시리즈.', 'en': 'An introductory portfolio series covering project selection, README, demo, deploy, tests, decisions, blog, and interviews.'} |
| [capstone-project-101](https://github.com/yeongseon-books/capstone-project-101) | {'ko': '주제 선정, 문제 정의, MVP, 팀 역할, 발표, 회고까지 측스톤 전체 흐름을 다룬 입문 시리즈.', 'en': 'An introductory series covering the full capstone flow — topic, problem, MVP, team roles, demo, and retrospective.'} |
| [technical-writing-101](https://github.com/yeongseon-books/technical-writing-101) | {'ko': '독자 정의부터 발행 전 체크리스트까지, 기술 글쓰기의 기본을 다지는 시리즈.', 'en': 'An entry series covering technical writing from defining the reader to the pre-publish checklist.'} |
| [technical-writing](https://github.com/yeongseon-books/technical-writing) | {'ko': '시리즈를 설계하고, 한 편을 다듬는 법.', 'en': 'Designing a series and shipping a single article.'} |

### 데이터

| 시리즈 | 설명 |
|---|---|
| [statistics-101](https://github.com/yeongseon-books/statistics-101) | {'ko': '기술 통계, 분포, 추정, 신뢰구간, 가설검정, 회귀까지 데이터 분석에 필요한 통계의 큰 그림을 다지는 시리즈.', 'en': 'A Statistics series covering descriptive statistics, distributions, estimation, confidence intervals, hypothesis testing, and regression end to end.'} |
| [probability-101](https://github.com/yeongseon-books/probability-101) | {'ko': '사건, 조건부확률, 베이즈 정리, 확률변수, 분포, 중심극한정리까지 ML 기초로 이어지는 확률을 다지는 시리즈.', 'en': "A Probability series covering events, conditional probability, Bayes' theorem, random variables, distributions, and the Central Limit Theorem as the bridge to ML."} |
| [linear-algebra-101](https://github.com/yeongseon-books/linear-algebra-101) | {'ko': '벡터, 행렬, 내적, 선형변환, 기저, 고유값, 행렬분해, PCA까지 ML 입문 직전 단계의 선형대수를 다지는 시리즈.', 'en': 'A Linear Algebra series covering vectors, matrices, inner products, linear transformations, basis, eigenvalues, decompositions, and PCA as the bridge to ML.'} |
| [data-science-101](https://github.com/yeongseon-books/data-science-101) | {'ko': '문제 정의, 데이터 수집, 정제, EDA, 시각화, 모델링, 평가, 해석까지 데이터 사이언스 전체 흐름을 다지는 시리즈.', 'en': 'A Data Science series covering problem framing, data collection, cleaning, EDA, visualization, modeling, evaluation, and interpretation end to end.'} |
| [sql-101](https://github.com/yeongseon-books/sql-101) | {'ko': 'SELECT, JOIN, GROUP BY, subquery, window function, DML, index 기초까지 분석/개발에 바로 쓰는 SQL 입문 시리즈.', 'en': 'A practical SQL series covering SELECT, JOIN, GROUP BY, subqueries, window functions, DML, and index basics for analysts and junior developers.'} |
| [pandas-101](https://github.com/yeongseon-books/pandas-101) | {'ko': 'Series, DataFrame, 파일 입출력, filtering, missing value, groupby, merge, time series, vectorization까지 다루는 Pandas 입문 시리즈.', 'en': 'A Pandas series covering Series, DataFrame, file I/O, filtering, missing values, groupby, merge, time series, and vectorization.'} |
| [machine-learning-101](https://github.com/yeongseon-books/machine-learning-101) | {'ko': '지도/비지도, train/test, 회귀, 분류, 트리, 군집, regularization, 평가까지 ML 전체 흐름을 다지는 시리즈.', 'en': 'A complete ML walkthrough — supervised/unsupervised, train/test, regression, classification, trees, clustering, regularization, and evaluation.'} |
| [model-evaluation-101](https://github.com/yeongseon-books/model-evaluation-101) | {'ko': '모델을 제대로 평가하는 법 — train/val/test, precision/recall, ROC, calibration, error analysis까지.', 'en': 'Properly evaluating ML models — train/val/test, precision and recall, ROC, calibration, and error analysis.'} |
| [mlops-101](https://github.com/yeongseon-books/mlops-101) | {'ko': '운영 가능한 ML 시스템 — 실험 관리, 모델 배포, 모니터링, drift, feature store까지.', 'en': 'Production-grade ML systems — experiment tracking, deployment, monitoring, drift, and feature stores.'} |
| [data-warehouse-101](https://github.com/yeongseon-books/data-warehouse-101) | {'ko': 'OLTP/OLAP, Fact와 Dimension, Star Schema, Partition, ETL/ELT, BI 연동까지 분석을 위한 데이터 저장소를 설계하는 시리즈.', 'en': 'A practical Data Warehouse series covering OLTP/OLAP, fact and dimension tables, star schema, partitioning, ETL/ELT, and BI integration.'} |
| [python-dbapi-101](https://github.com/yeongseon-books/python-dbapi-101) | {'ko': 'Python의 표준 데이터베이스 인터페이스 PEP 249(DB-API 2.0)를 SQLite 기준으로 다루는 입문 시리즈.', 'en': "A beginner-friendly tour of Python's PEP 249 (DB-API 2.0) using SQLite, covering connection lifecycle, transactions, error handling, async, and production patterns."} |
| [sqlalchemy-101](https://github.com/yeongseon-books/sqlalchemy-101) | {'ko': 'SQLAlchemy 2.x를 SQLite 기준으로 다루는 입문 시리즈. Engine·Connection·Core·ORM·Session·Unit of Work·Relationship·Loading 전략·Async·Production 패턴을 배웁니다.', 'en': 'A beginner-friendly SQLAlchemy 2.x tour using SQLite. Covers Engine, Connection, Core, ORM, Session, Unit of Work, relationships, loading strategies, async, and production patterns.'} |
| [alembic-101](https://github.com/yeongseon-books/alembic-101) | {'ko': 'Alembic으로 SQLAlchemy 마이그레이션을 운영하는 입문 시리즈. autogenerate, branch와 merge, 데이터 마이그레이션, downgrade 전략, 배포 순서를 SQLite 기준으로 다룹니다.', 'en': 'A beginner-friendly Alembic tour for SQLAlchemy migrations using SQLite. Covers autogenerate, branches and merges, data migrations, downgrade strategy, and deploy ordering.'} |

### Azure 클라우드

| 시리즈 | 설명 |
|---|---|
| [azure-app-service-101](https://github.com/yeongseon-books/azure-app-service-101) | {'ko': 'Azure App Service 입문 7부작 — 호스팅, 설정, 로그, 스케일링.', 'en': 'A 7-part beginner guide to Azure App Service.'} |
| [azure-app-service-deep-dive](https://github.com/yeongseon-books/azure-app-service-deep-dive) | {'ko': 'App Service 내부 — Front-End, Worker, Sandbox, Kudu, Scaling.', 'en': 'Inside App Service — Front-End, Worker, Sandbox, Kudu, Scaling.'} |
| [azure-functions-101](https://github.com/yeongseon-books/azure-functions-101) | {'ko': 'Azure Functions 입문 7부작 — 트리거/바인딩부터 운영까지.', 'en': 'A 7-part beginner guide to Azure Functions.'} |
| [azure-functions-deep-dive](https://github.com/yeongseon-books/azure-functions-deep-dive) | {'ko': 'Azure Functions Host 소스 분석 시리즈 (commit-pinned).', 'en': 'Source-level dive into Azure Functions Host (commit-pinned).'} |
| [azure-aks-101](https://github.com/yeongseon-books/azure-aks-101) | {'ko': 'AKS 입문 시리즈.', 'en': 'AKS beginner guide.'} |
| [azure-aks-deep-dive](https://github.com/yeongseon-books/azure-aks-deep-dive) | {'ko': 'AKS control plane / data plane 내부 동작.', 'en': 'AKS control plane / data plane internals.'} |
| [azure-aca-101](https://github.com/yeongseon-books/azure-aca-101) | {'ko': 'Container Apps 입문 시리즈.', 'en': 'Container Apps beginner guide.'} |
| [azure-aca-deep-dive](https://github.com/yeongseon-books/azure-aca-deep-dive) | {'ko': 'ACA 위에 얹힌 KEDA·Dapr·Envoy 내부 동작.', 'en': 'Inside ACA — KEDA, Dapr, Envoy.'} |

## 예제 코드 규약

- **언어**: 모든 사용자용 코드는 Python 입니다.
- **테스트**: 각 레포에 pytest 기반 테스트가 포함되어 있으며, 클론 후 `pip install -r requirements.txt && pytest -q`로 검증할 수 있습니다.
- **오프라인 동작**: 외부 API 키 없이 동작하는 mock-only 예제를 기본으로 합니다 (실제 API 사용 예제는 `.env.example` 참조).
- **다국어**: 각 레포는 `ko/`와 `en/` 디렉터리를 미러링하며, 코드 주석도 양 언어로 제공됩니다.

## 발행 채널

- **Tistory (한국어 블로그)**: <https://yeongseonchoe.tistory.com/>
- **Hashnode (영어 블로그)**: <https://hashnode.com/@yeongseon>
- **Medium**: <https://medium.com/@yeongseonchoe>

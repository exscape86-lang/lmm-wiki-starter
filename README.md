# LMM WIKI Starter Vault

인스타 릴스에서 보여준 **Obsidian 링크/그래프형 지식관리 구조**를 처음부터 따라 만들 수 있게 분리한 무료 스타터입니다.

이 저장소는 개인 운영 vault(`C:\Users\wizsr\.omc\LMMWIKI`)를 그대로 공개한 것이 아니라, 공개 가능한 구조와 설정만 뽑아낸 **sanitized starter**입니다. 개인 노트, 로그, 원본 자료, API 키, 자동화 산출물은 포함하지 않습니다.

## 이 스타터로 되는 것

- 노트가 폴더별로 흩어지지 않고 `source → concept → daily/project` 흐름으로 연결됩니다.
- Obsidian 그래프에서 `sources`, `concepts`, `daily`가 색상별로 보입니다.
- 영상/글/아이디어를 하나의 wiki 노트로 축적할 수 있습니다.
- 나중에 LLM/AI 요약 자동화나 Smart Connections 계열 플러그인을 붙일 수 있는 기본 구조를 갖춥니다.

## 빠른 시작

1. 이 저장소를 ZIP으로 다운로드합니다.
2. 압축을 풉니다.
3. Obsidian에서 `Open folder as vault`로 이 폴더를 엽니다.
4. `00_START_HERE.md`를 먼저 읽습니다.
5. Community plugins를 켜고 아래 플러그인을 설치합니다.
6. `templates/`의 템플릿으로 첫 source/concept/daily 노트를 만듭니다.

## 추천 플러그인

### 필수

- **Dataview**: 노트 목록/인덱스 자동화
- **Calendar**: daily note 진입점
- **Smart Connections**: 의미 기반 연결 후보 확인
- **Smart Context**: 노트 맥락 확장
- **Smart Graph**: 그래프 탐색 강화
- **Smart File Nav**: 빠른 파일 이동

### 선택/고급

- **Excalidraw**: 개념 지도와 시각화
- **Smart Chat / Smart ChatGPT**: vault 기반 질의응답
- **Smart Dedupe**: 중복 노트 정리
- **Smart Lookup**: 빠른 조회
- **Smart Templates**: 반복 작성 자동화
- **Smart Connect Pro**: 고급 연결 워크플로우

> 주의: 플러그인 바이너리(`main.js`)는 저장소에 포함하지 않습니다. Obsidian Community Plugins에서 직접 설치하세요.

## 폴더 구조

```text
lmm-wiki-starter/
├─ 00_START_HERE.md
├─ daily/                 # 매일 추가되는 요약/링크 발견
├─ wiki/
│  ├─ concepts/           # 오래 남길 개념 노트
│  ├─ sources/            # 영상/글/책/레포 단위 원천 노트
│  ├─ channels/           # 반복해서 보는 채널/출처 인덱스
│  └─ tags/               # 태그 설명/인덱스
├─ projects/              # 실행 중인 프로젝트 노트
├─ templates/             # 복사해서 쓰는 템플릿
└─ .obsidian/             # 공개 가능한 기본 설정
```

## 운영 원칙

1. **source는 원본 1개당 1노트**로 만든다.
2. **concept는 여러 source에서 반복되는 생각만 승격**한다.
3. **daily는 오늘 들어온 것과 오늘 연결된 것만 기록**한다.
4. 자동화가 만든 요약도 사람이 한 번 보고 `confidence`를 붙인다.
5. API 키, 개인정보, 비공개 로그는 vault에 넣지 않는다.

## 무료 버전과 Pro 버전 아이디어

무료 버전은 구조와 설치법 중심입니다. Pro 버전을 만든다면 아래처럼 “시간 단축”에 가치를 둡니다.

- 완성 Vault ZIP
- 플러그인 세팅 스크린샷/영상
- 실제 사용 예시 노트 20개+
- 자동화 스크립트/업데이트
- 개인 업무별 템플릿 패키지

## 라이선스

MIT License. 단, Obsidian과 각 Community Plugin은 각 프로젝트의 라이선스를 따릅니다.

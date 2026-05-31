---
title: Start Here
# category enum: concept | source | channel | tag | reference | architecture | decision | pattern | debugging | environment | session-log | convention
category: guide
confidence: high
updated: 2026-05-25
tags: [start, obsidian, lmm-wiki]
author: lmm-wiki-starter
schemaVersion: 2
---

# 00_START_HERE

LMM WIKI는 “노트를 많이 쓰는 시스템”이 아니라 **자료가 들어오면 연결 후보가 생기고, 사람이 중요한 개념만 승격하는 시스템**입니다.

## 1단계: 첫 source 만들기

`templates/source-template.md`를 복사해서 `wiki/sources/` 아래에 넣으세요.

예시:

- 유튜브 영상: `wiki/sources/youtube-obsidian-graph-view.md`
- 블로그 글: `wiki/sources/article-second-brain.md`
- GitHub repo: `wiki/sources/github-smart-connections.md`

## 2단계: 반복되는 생각을 concept로 승격

source를 보다가 반복되는 아이디어가 생기면 `templates/concept-template.md`를 복사해 `wiki/concepts/`에 만듭니다.

예시:

- `wiki/concepts/semantic-linking.md`
- `wiki/concepts/source-to-concept-pipeline.md`
- `wiki/concepts/daily-knowledge-compile.md`

## 3단계: daily에서 오늘의 연결 기록

`templates/daily-template.md`를 복사해서 `daily/0_today-YYYY-MM-DD.md`로 만듭니다.

daily에는 길게 쓰지 말고 아래 3개만 적습니다.

1. 오늘 추가한 source
2. 오늘 업데이트한 concept
3. 오늘 새로 발견한 연결 1개

## 4단계: 그래프 보기

Obsidian Graph View를 열면 기본 설정 기준으로 다음 색상이 적용됩니다.

- `wiki/sources`: 붉은 계열
- `wiki/concepts`: 파란 계열
- `daily`: 노란 계열

처음에는 노드가 적어도 괜찮습니다. source 10개, concept 5개부터 그래프가 살아납니다.

## 첫 10분 체크리스트

- [ ] Obsidian에서 이 폴더를 vault로 열었다.
- [ ] Community plugins를 켰다.
- [ ] Dataview, Calendar, Smart Connections를 설치했다.
- [ ] `templates/source-template.md`로 source 1개를 만들었다.
- [ ] source에서 concept 1개를 연결했다.
- [ ] Graph View에서 링크가 보이는지 확인했다.

## 다음 단계: 자동화로 키우기

여기까지가 손으로 굴리는 기본 운영입니다. 이걸 계속 쌓다 보면 자연스럽게 다음 단계가 보입니다. 실제로 운영 중인 vault는 아래 모습까지 도달해 있습니다(방향만 소개합니다).

- **topic 레이어**: source/concept가 쌓이면 주제별로 "목차(무엇이 있나)"와 "답변(그래서 결론은)"을 따로 두게 됩니다. 매번 노트를 뒤지지 않고 주제 하나로 바로 답을 꺼내는 단계입니다.
- **매일 자동 다이제스트**: 그날 들어온 자료를 모아 "오늘 뭐가 새로 들어왔고, 뭘 승격할 만한가"를 매일 한 장으로 정리해 주는 단계입니다. 사람은 판단만 합니다.
- **외부 수집 → 후보 → 승격**: 유튜브·블로그·리포지토리 같은 외부 소스를 매일 자동으로 끌어와 "승격 후보"로 쌓아두고, 사람이 중요한 것만 골라 vault에 올리는 단계입니다.

이 단계들의 핵심은 하나입니다. **수집·정리는 기계가, 승격 판단은 사람이.** 자동화가 늘어도 vault의 품질을 지키는 마지막 결정은 사람이 합니다.

> 여기까지가 무료 Starter로 직접 만들 수 있는 범위입니다. 완성된 vault와 위 자동화(매일 자동 다이제스트, 외부 수집 파이프라인, topic 레이어 구현체)를 바로 쓰고 싶다면 **Pro Vault**에서 통째로 제공합니다.

---
title: Topic Layer (Inventory & Dossier)
# category enum: concept | source | channel | tag | reference | architecture | decision | pattern | debugging | environment | session-log | convention
category: concept
confidence: medium
updated: 2026-05-31
tags: [concept, topic-layer, retrieval]
author: lmm-wiki-starter
schemaVersion: 2
source_type: concept
synthesized_from: []
contradictions: []
maturity: stub
---

# Topic Layer (Inventory & Dossier)

## 정의

여러 source와 concept가 한 주제에 충분히 쌓이면, 그 주제를 한곳에서 답할 수 있게 묶어주는 레이어입니다. 핵심은 두 개의 노트입니다. **inventory(목차)** 는 "이 주제에 뭐가 있나"를 한눈에 보여주고, **dossier(답변 노트)** 는 "이 주제로 질문하면 이렇게 답한다"를 정리합니다.

## 왜 중요한가

- source가 많아지면 검색은 되지만, 매번 흩어진 노트를 다시 읽어 종합해야 합니다. 그 종합 작업을 미리 한 번 해두는 게 topic 레이어입니다.
- 질문이 들어왔을 때 개별 노트를 뒤지지 않고 dossier 한 장으로 바로 답할 수 있습니다.
- inventory가 있으면 "이 주제는 어디까지 정리됐고 뭐가 비었나"를 빨리 점검할 수 있습니다.

## 레이어 안에서의 위치

전체 흐름은 raw(원천) → wiki(지식) → projects(실행)입니다. topic 레이어는 wiki 안에서 source/concept "위"에 얹히는 정리 단계입니다.

```
source / concept  (낱장 지식)
        │  같은 주제로 충분히 모이면
        ▼
inventory.md      (목차 — 무엇이 있나)
        │  종합·요약
        ▼
dossier.md        (답변 — 질문하면 이렇게 답한다)
```

## inventory(목차) 노트에 들어가는 것

- 이 주제에 연결된 source/concept 목록 (wikilink로)
- 아직 안 채운 빈칸·다음에 볼 것
- 한 줄로 "이 주제 지금 상태가 어떤지"

## dossier(답변) 노트에 들어가는 것

- 자주 받는 질문과 그에 대한 짧은 답
- 결론 먼저, 근거가 된 source는 wikilink로
- 서로 안 맞는 내용(모순)이 있으면 솔직히 적어두기

## 수동으로 시작하는 법

처음부터 자동화할 필요 없습니다. 주제 하나당 폴더를 만들고 `inventory.md`, `dossier.md` 두 장만 손으로 채워보세요. 주제가 익으면 그때 자동 수집·정렬로 발전시킬 수 있습니다(방향만 잡아두면 충분합니다).

## 연결된 source

- [[wiki/sources/example-obsidian-graph-video]]

## 연결된 concept

- [[wiki/concepts/semantic-linking]]
- [[wiki/concepts/source-to-concept-pipeline]]

## 내 시스템에서 쓰는 방식

- 

## 다음에 보강할 것

- [ ] 자주 묻는 질문 3개를 dossier 맨 위에 모으기
- [ ] inventory의 빈칸을 채울 source 찾기

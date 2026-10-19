---
title: vault-project-doc
created: 2026-10-19
updated: 2026-10-19
tags: [domain/지식관리, area/문서관리, agent/claude-a591602f-c760-4aea-af9d-6f837e7f2d0b]
source: ai
---

# vault-project-doc

> Obsidian 볼트의 프로젝트 폴더에 새 문서를 만들 때 **빈 문서 → 프로젝트 스텝에 연결 → 내용 작성** 순서를 지키게 하는 스킬이다.

## 하는 일

- 문서를 먼저 빈 채로(프론트매터·제목만) 만들어 이름·번호와 생성 세션 태그를 확정한다.
- 그 문서가 속한 스텝 노트(또는 단계 목록)에 링크를 걸고, 그다음 내용을 쓴다. 쓰는 도중에도 문서가 어느 스텝의 것인지 드러나고, 세션이 끊겨도 스텝에서 찾을 수 없는 문서가 남지 않는다.
- 이름·번호·위치 규칙은 복제하지 않는다. 볼트와 그 프로젝트의 `rules/` 가 정하고, 이 스킬은 순서만 소유한다.

## 설치

에이전트 도구의 스킬 경로에 clone 하거나 링크한다.

```bash
git clone https://github.com/s12171934/vault-project-doc.git ~/.claude/skills/vault-project-doc
```

- 볼트 루트를 찾는 데 스킬 `vault-entry` 를 쓴다 (스킬 이름으로만 의존).

## 구성과 공개 면

- [[20_Agents/skills/vault-project-doc/SKILL|SKILL.md]] — 스킬 본문. 형식은 에이전트 도구가 정한다.
- 공개 면은 스킬 이름(`vault-project-doc`)뿐이다.

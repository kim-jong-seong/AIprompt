# AIprompt

## 개요
- Claude Code에서 사용하는 프롬프트(CLAUDE.md)를 버전별로 관리하는 프로젝트

## 기술 스택
- Markdown
- Git / GitHub

## 프로젝트 구조
- `CLAUDE.md` — 현재 적용 중인 프롬프트 규칙
- `prompts/` — 프롬프트 버전 관리 디렉토리
  - `v1.0/CLAUDE.md` — 초기 버전
- `.claude/settings.local.json` — Claude Code 권한 설정

## 주요 기능
- 프롬프트 버전 관리 (메이저/마이너)
- 루트 CLAUDE.md로 현재 버전 적용

## 변경 이력
- 2026-03-31: 프로젝트 초기 설정 (CLAUDE.md, .claude 설정)
- 2026-03-31: 프롬프트 버전 관리 구조 추가 (prompts/v1.0)
- 2026-03-31: Initial Scan 규칙 추가, 작업 계획 포맷 개선 (v1.0)

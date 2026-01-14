# 6. Templates

## 폴더 목적

반복적으로 사용하는 노트 구조와 템플릿을 보관하여 일관성과 효율성을 높입니다.

## 들어가는 템플릿

- 프로젝트 노트 템플릿
- Literature 노트 템플릿
- Permanent 노트 템플릿
- 미팅 노트 템플릿
- 일일/주간 리뷰 템플릿
- Area 관리 템플릿

## 작업 방식과 규칙

1. **템플릿 활용**: Obsidian의 템플릿 플러그인 사용
2. **일관성 유지**: 같은 유형의 노트는 같은 템플릿 사용
3. **지속적 개선**: 사용하면서 템플릿을 계속 개선
4. **필수 vs 선택**: 일부 필드는 필수, 일부는 선택 사항으로 구분

## 템플릿 명명 규칙

- `Template - [용도].md` 형식
- 예: `Template - Project.md`, `Template - Literature.md`

## 템플릿 예시

### Project Template

```markdown
---
created: {{date}}
status: 진행중
deadline:
tags: #project
---

# {{title}}

## 목표
[명확한 완료 조건]

## 마감일
YYYY-MM-DD

## 진행 상태
- [ ] 작업 1
- [ ] 작업 2

## 관련 자료
- [[]]

## 회고
[프로젝트 완료 후 작성]
```

### Daily Note Template

```markdown
---
date: {{date}}
tags: #daily
---

# {{date:YYYY-MM-DD}}

## 오늘의 목표
-

## 완료한 일
-

## 메모
-

## 내일 할 일
-
```

## Obsidian 템플릿 플러그인 설정

1. Settings → Core plugins → Templates 활성화
2. Templates → Template folder location → "6. Templates" 설정
3. 노트에서 Cmd+P → "Insert template" 실행

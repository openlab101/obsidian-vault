# 7. Attachments

## 폴더 목적

이미지, PDF, 영상 등 노트에 첨부되는 모든 파일을 중앙에서 관리하는 공간입니다.

## 들어가는 파일

- 이미지 (PNG, JPG, GIF 등)
- PDF 문서
- 오디오 파일
- 영상 파일
- Canvas 파일 (Obsidian의 시각적 다이어그램)
- 기타 바이너리 파일

## 작업 방식과 규칙

1. **자동 저장**: Obsidian 설정에서 첨부 파일 기본 위치를 이 폴더로 설정
2. **명명 규칙**: 파일명은 설명적으로 작성 (예: `growth-funnel-diagram-2025.png`)
3. **하위 폴더**: 필요시 주제별로 하위 폴더 생성 가능
   - `7. Attachments/images/`
   - `7. Attachments/pdfs/`
   - `7. Attachments/canvas/`
4. **참조 관리**: 노트에서 삭제된 첨부 파일은 정기적으로 정리

## Obsidian 첨부 파일 설정

Settings → Files & Links → Default location for new attachments
→ "In the folder specified below" 선택
→ "7. Attachments" 입력

## 파일 정리 팁

- 사용하지 않는 첨부 파일 찾기: 플러그인 "Find orphaned files and broken links" 활용
- 정기 정리: 분기별로 미사용 첨부 파일 검토
- 백업: 중요한 첨부 파일은 Git에 포함하거나 별도 백업

## 용량 관리

- 대용량 파일(>10MB)은 Git에 포함하지 않기 (`.gitignore` 활용)
- 이미지는 적절한 해상도로 압축
- 필요시 외부 클라우드 스토리지 링크 활용

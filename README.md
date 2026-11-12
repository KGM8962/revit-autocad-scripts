# revit-autocad-scripts

Revit과 AutoCAD 반복 작업을 자동화하는 스크립트 모음입니다.

## 폴더 구조

```
revit/
  pyrevit/     pyRevit 확장 스크립트 (.py)
  dynamo/      Dynamo 그래프 (.dyn) 및 Python 노드 코드
autocad/
  autolisp/    AutoLISP 루틴 (.lsp)
docs/          사용법, 메모
```

## 사용 방법

- **pyRevit**: `revit/pyrevit` 폴더를 pyRevit 확장 경로에 추가하거나 스크립트를 복사해 사용합니다.
- **Dynamo**: Dynamo에서 `.dyn` 파일을 열어 실행합니다.
- **AutoLISP**: AutoCAD에서 `APPLOAD` 명령으로 `.lsp` 파일을 불러옵니다.

## 참고

- `.rvt`, `.rfa`, `.dwg` 같은 대용량 모델 파일은 `.gitignore`로 제외됩니다.

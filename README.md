
# HTML, CSS, JS - 메모장 만들기 (+저장 기능)

## 프로젝트 개요

이 프로젝트는 HTML, CSS, 그리고 자바스크립트를 사용하여 간단한 메모장을 제작하는 것을 목표로 합니다. 사용자는 메모를 입력하고, 저장하며, 나중에 다시 불러올 수 있습니다. 또한, 메모를 로컬 파일로 저장할 수 있는 기능도 포함되어 있습니다.

## 사용된 도구 및 플랫폼

- **Visual Studio Code**: 개발 환경으로 사용
- **Github**: 소스 코드 관리를 위해 사용
- **Netlify**: 프로젝트 배포를 위해 사용

## 완성된 사이트

프로젝트는 Netlify를 통해 배포되었으며, 아래 링크에서 확인할 수 있습니다:
- [완성된 사이트 접속하기](https://warm-wisp-80c7da.netlify.app/)

## 주요 기능

1. **메모 입력 및 저장**:
   - 사용자가 제목과 메모를 입력하고, 저장된 메모는 나중에 다시 확인할 수 있습니다.

2. **메모 삭제 및 전체 지우기**:
   - 저장된 메모를 개별적으로 삭제하거나 전체 메모를 한번에 삭제할 수 있습니다.

3. **메모를 이미지 파일로 저장**:
   - 작성된 메모를 PNG 파일 형식으로 로컬에 저장할 수 있습니다.

## 결과 화면

### (1) 시작 화면
- 사용자에게 메모 제목과 내용을 입력할 수 있는 기본 화면 제공.

### (2) 메모 입력 화면
- 제목과 내용을 입력할 수 있는 UI 제공.

### (3) 메모 저장 화면
- 저장된 메모는 목록 형태로 보여지며, 개별적으로 저장할 수 있습니다.

### (4) 저장된 메모 로컬 파일로 저장
- 사용자는 메모를 PNG 이미지로 다운로드할 수 있습니다.

## 핵심 코드

```html
<!-- 메모 제목 입력 필드 -->
<div class="mb-3">
    <label for="noteTitle" class="form-label">제목</label>
    <input type="text" class="form-control" id="noteTitle" placeholder="제목을 입력하세요">
</div>
<!-- 메모 내용 입력 필드 -->
<div class="mb-3">
    <label for="noteInput" class="form-label">메모</label>
    <textarea class="form-control" id="noteInput" rows="5" placeholder="메모를 입력하세요"></textarea>
</div>
<!-- 저장 및 전체 지우기 버튼 -->
<div class="d-flex justify-content-between">
    <button id="saveButton" class="btn btn-primary flex-grow-1 me-2">저장</button>
    <button id="clearAllButton" class="btn btn-secondary flex-grow-1">전체 지우기</button>
</div>
<!-- 저장된 메모 목록 -->
<h2 class="mt-5 mb-4 text-center">저장된 메모</h2>
<div id="savedNotes" class="mt-3"></div>
```

## 태그

- HTML
- CSS
- 자바스크립트
- Netlify
- Github
- 메모장 기능
- 저장 기능

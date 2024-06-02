# 2회차 미니과제 - 할 일 목록 만들기
---
## 구현 컴포넌트
### App.js
프로그램이 시작되는 컴포넌트 입니다.
### TodoFilters.jsx
할 일 목록들을 필터링하거나 삭제하는 컴포넌트 입니다.
### TodoItem.jsx
한개의 할 일을 구성 및 표현하는 컴포넌트 입니다.
### TodoInput.jsx
할 일을 입력받는 부분의 컴포넌트 입니다. TodoItem이 생성되는 부분이기도 합니다.


---
## 구현 기능
### todoUtils.js
### 할 일 추가 (addTodo)
할 일을 추가합니다. 내용물이 없으면 추가할 수 없습니다.
### 완료여부 토글 (toggleTodo)
할 일의 완료여부를 토글합니다.
### 할 일 삭제 (deleteTodo)
할 일을 삭제합니다
### 완료된 할 일 삭제 (deleteCompleted)
완료된 할 일만 삭제합니다.
### 할 일 필터링 (filteredTodos)
할 일들을 완료여부에 따라 필터링하여 반환합니다.

---
### inputUtils.js
### 입력받기 (handleAddTodo)
할 일을 입력받고 입력란을 비워줍니다.

---

### useLocalStorage.js
### 로컬스토리지 관리 (useLocalStorage)
로컬스토리지의 값을 관리합니다.
브라우저를 새로고침하여도 값이 유지되도록 도와줍니다.

---
### 추가사항
시작은 App.js로부터 이루어집니다.
\+ 버튼을 통해 할 일을 추가하거나 Enter를 눌러 추가할 수 있습니다.
체크를 통해 일을 완료할 수 있고, 휴지통 아이콘을 통해 할 일을 삭제할 수 있습니다.
All은 전체 할 일, Active는 진행중인 할 일, Completed는 완료된 할 일을 보여줍니다.
Delete completed tasks를 통해 완료된 할 일들만 제거할 수 있습니다. 
맨 밑의 남은 할 일은 남은 할 일의 개수를 보여줍니다.

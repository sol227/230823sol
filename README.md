## 230823
# HTML 기본 내용 요약 
## HTML (HyperText Markup Language) :
 - 웹 페이지와 그 내용을 구조화하기 위해 사용하는 코드
 - 다양한 콘텐츠의 구조를 정의하는 '마크업' 언어
 - 태그 안에 요소 이름은 대소문자를 구분하지 않음, 그래서 대소문자가 섞여도 상관없음
### 요소 :
>**여는 태그, 닫는 태그,콘텐츠로 이루어짐**
- 콘텐츠의 서로 다른 부분을 각각의 형식으로 보이도록 하거나 특정한 방식으로 동작하게 함
- 속성도 가질 수 있음
- **요소 중첩**: 다른 요소를 다른 요소안에 넣는 것
- **빈 요소**: 내용을 갖지 않은 요소
### 태그 :
>**단어나 이미지를 각각 형태로 보이도록 하는 효과를 줌. 콘텐츠를 태그로 감싸 요소를 만듦**
- **여는 태그 (Opening tag)**: 요소가 시작되는 곳, 또는 효과를 시작하는 곳
- **닫는 태그 (Closing tag)**: 요소의 끝이자 문단이 끝나는 위치를 나타냄 
- **주의할 점**은 여는 태그와 닫는 태그는 세트이므로, 닫는 태그를 안할 시 이상한 결과가 표시 되는 오류가 발생함
### 태그별 역할
- `<!DOCTYPE html>`: doctype. **필수 서문**
- `<html></html>`: 페이지 전체의 콘텐츠를 감싸며, 루트(root) 요소
- `<html></html>`: HTML 페이지에 포함하고 싶어하는 모든 재료들을 위한 컨테이너 역할
- `<meta charset="utf-8">`: 사용할 수 있는 어떠한 문자 콘텐츠도 다룰 수 있음
- `<title>`: 페이지의 제목을 설정
- `<body>`: 페이지에 모든 컨텐트를 담고 있음
- `<img>`: **이미지**
- `<h1>-<h6>`: **제목**
- `<!--`과 `-->`: **HTML 주석**으로 페이지에 보이지 않음
- `<p>`: **문자의 문단**
- `<ul>`: **순서 없는 목록**
- `<ol>`: **순서 있는 목록**
- `<li>`: **목록 항목**
- `<a>`: **링크**

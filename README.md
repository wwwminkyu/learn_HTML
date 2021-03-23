# learn_HTML

  > 공부할 사이트 : [생활코딩](https://www.opentutorials.org/)</br>
  > 온라인 에디터 : [Codepen](https://codepen.io/trending)</br>
  
***
## 태그(tag)</br>
- 진하게 : strong</br>
strong 태그는 해당 콘텐츠의 중요성이나 심각함, 긴급함 등을 강조할 때 사용합니다.</br>
- 밑줄 : u </br>
u 태그는 철자가 틀린 단어나 중국어의 고유 명사처럼 문체상 일반적인 텍스트와는 달라야만 하는 텍스트를 표현할 때 사용합니다.</br>
- 제목 : h1 ~ h6</br>
HTML 문서에서 제목(heading)을 정의할 때 사용합니다.</br>
***
- 구글의 웹페이지를 분석하여 자주쓰는 HTML 태그 순위를 정리 정돈한 사이트 : [바로가기](https://www.advancedwebranking.com/html/)</br>

***
- html paragraph tag 검색</br>
- 줄바꿈 : /br</br>
- 단락 : p, /p</br>
문단(paragraph)을 정의할 때 사용합니다.</br>
CSS를 이용해서 첫번째 단락과 두번째 단락의 간격을 세밀하게 조정해 봅시다</br>
p 태그에 style="margin-top:45px"를 추가하면 p 태그의 위쪽에 45px 만큼의 여백(margin)이 생깁니다. </br>


## 속성(attribute)
- 태그를 만든 사람들은 태그 이름만으로는 정보가 부족하다는 것을 알게 되었습니다. 그래서 고민에 빠집니다. 그리고 새로운 문법을 도입하게 됩니다.
- img src=""
- html img size attribute : 이미지 사이즈 조절 검색
- width의 값으로 숫자나 %를 사용하면 원하는 크기로 조정할 수 있습니다.


## 부모, 자식 tag
- 목차, 목록을 나타내는 태그 : li 
- 목록(list)은 다른 목록과 구분할 수 있도록 경계가 필요합니다. 이 때 사용하는 태그 : ul
- li 태그는 ul 태그를 꼭 필요로 합니다. ul 태그 역시 li 태그가 없다면 존재 가치가 없습니다. 이 둘은 서로 아주 밀접한 관계입니다.
- ul 태그와 유사한 태그 : ol 태그
- ul은 unordered list의 약자이고, ol은 ordered list의 약자.


## 문서의 구조를 나타내는 태그
- 제목을 지정하기 위해서 title 태그를 사용
- meta charset="utf-8" : 영어가 아닌 문자가 깨지는 것 방지
- 본문은 body 태그로, 본문을 설명하는 태그는 head 태그
- body 태그와 head 태그를 감싸는 하나의 태그를 두기로 약속, html 태그
- 웹페이지가 HTML로서 만들어졌다는 것을 표현하기 위해서 문서의 시작에 코드를 추가 !doctype html


## 링크 태그
- a 태그 : 링크를 걸 때 사용, anchor(닻) 정보의 바다에 정박한다
- href="" (HyperText Reference의 약자)
- target=" _ blank"는 링크를 클릭했을 때 새창에서 페이지가 열리게 하는 속성
-  title은 이 링크가 어떤 내용을 담고 있는지를 툴팁으로 보여주는 기능

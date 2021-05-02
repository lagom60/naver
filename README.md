# HTML/CSS 코딩 테스트

## HTML 작성 시 요구 사항
- 기본 언어 명시
- 적절한 타이틀(&lt;title&gt;) 작성
- 논리적인 순서를 고려하여 마크업
- 시맨틱 마크업   
(클래스 네이밍은 자유, 단 <span style="color: #f00">.is--invalid</span> 예외)  

- 문법 오류가 발생하지 않도록 작성
- 1개 이상의 제목(heading) 요소 사용
- 로고는 &lt;img&gt; 요소로 마크업하고 해당 로고 클릭 시 네이버 홈페이지로 이동하도록 구현  
(네이버 홈 : https://www.naver.com/)  

- 로고 이미지는 배경이 아닌 &lt;img&gt; 요소로 마크업  
(svg를 지원하는 웹브라우저는 svg 형식으로 그렇지 않은 웹브라우저는 png 형식으로 보여지도록 구현)  

- 웹접근성을 고려한 로그인 폼 서식 마크업  
(레이블 제공의 경우 WAI-ARIA가 아닌 HTML 네이티브 방식으로 구현)  

- 아이디와 비밀번호는 필수 입력 서식임을 알 수 있도록 구현  
- 아이디와 비밀번호 입력 값이 오류일 때(.is--invalid) 에러 메시지가 보이도록 구현   
(CSS에서 display: none과 block으로 처리할 것)  

- IP 보안 텍스트 클릭 시 미리 제공 된 ip_secruity.html 파일이 새창에 보이도록 구현  
(새창 링크 시 보안 이슈를 해결하기 위한 값도 설정해야 함)  

- IP 보안 체크박스의 ON/OFF 텍스트는 CSS의 ::before 또는 ::after 등의 가상 요소를 사용하여 구현  

<div style="padding: 1em; background: #e9f0fd; border-left: 10px solid #42b983">
&#8251; 아이디와 비밀번호 입력 값이 오류일 때 해당 <span style="color:#f00;font-weight: bold">&lt;input&gt; 요소에 .is--invalid가 추가되도록 하는 기능</span>은 미리 자바스크립트 파일에 구현되어 있음.  

&#8251; 제공 된 <span style="color: #00f; font-weight: bold">form_validation.js</span> 파일을 HTML에 적용 후 <span style="color: #00f; font-weight: bold">로그인 버튼을 클릭</span>하면 해당 클래스가 추가된 상황을 확인할 수 있음.
</div>



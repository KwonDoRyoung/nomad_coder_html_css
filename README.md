# NomadCoder_html_css

to study html &amp; css in the Nomad Coder

- tag 구글에 검색할 때: html tags mdn
- semantic Tag: Content sectioning(콘텐츠 구획)
    - div 로만 이루어지게 하지 않고 의미론적으로 태깅하기!

- css 와 html 을 불리해서 두는 것이 좋음
    - html 안에 존재할 경우 head 태그 안의 style 태그
    - html 과 분리 *.css 로 생성 후, link href="*.css" ref="stylesheet" 태그

- 다른 요소가 옆에 올 수 있는 것은 inline
    - span, a, img, code, ...
    - 너비와 높이가 없음
- 다른 요소가 옆에 올수 없는 것은 block
    - div, address, p, ...
    - margin, padding, border 이라는 속성이 있음
        - margin 의 경우 값이 2개인 경우, 4개인 경우 다음과 같이
            - margin: Left-px right-px
            - top 부터 시계방향으로 설정가능
                - margin: Top-px Right-px Bottom-px Left-px;
            - collapsing margin
                - 경계가 만나면 하나로 작동.
- flexbox
  - 3가지 정도의 규칙을 지켜야 됨다.
  - 적용하고 싶은 부분에 flexbox 하는 것이 아닌 부모 부분에 적용해야됨
  - 기본값 : main axis-justify / cross axis-align
    - 이는 변경 가능함: flex-direction!

- div > span 직속 상하 관계 부모자식
- p + span 동등(형제) 관계 이지만 앞뒤고 붙어 잇어야됨
- p ~ span 형제 이지만 멀리 잇어도 됨

- matthewlein.com
- https://animista.net/
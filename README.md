# NextJS Introduction

- pages 폴더 안에 있는 파일명이 -> url
- index.js 파일만 예외 '/'

- jsx를 쓸 때 react를 import 할 필요가 없음.

# 장점

- 앱에 있는 페이지들이 미리 렌더링 된다.
- CRA는 Client-Side-Render(CSR)를 하는 앱을 만든다.

- CSR은 쉽게 말해서 클라이언트에서 모두 처리한다는 뜻이다.

# 특징

- a태크를 사용하지 말자 => 새로고침 되기 때문에 => 느려질 수 있음.
- abchor 태그를 사용하지 말고 next/Link를 사용하자! (<Link href="/"><a>home</a></Link>)
- css를 적용할 때 module.css를 이용하면 클래스명 충돌을 걱정 할 필요가 없음.
- page/\_app.js 에서 처음 OR 모든 틀을 잡아줄 수 있음

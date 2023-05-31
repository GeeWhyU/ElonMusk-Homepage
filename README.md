## ElonMusk-Homepage
이 웹사이트는 스파르타 코딩 클럽의 <ChatGPT로 10분만에 웹사이트 만들기 강의>   
를 참고하여 제작한 웹사이트입니다.

### 주요기능
- Elon Musk의 각 회사를 소개하는 카드가 웹사이트에 구성되어 있습니다.   
- 카드를 클릭하면 카드 크기가 늘어나고, 카드 내의 링크를 통해 각 회사의 공식 웹사이트로 이동할 수 있습니다.

### 개발목표
- 부트스트랩, 미디어쿼리를 이용하여 반응형 웹페이지를 제작합니다.

### 사용기술
- HTML
- CSS
- Bootstrap
- Media Query

### Advanced Feature
- 카드 위에 마우스를 올리면, 부드럽게 5% 확대되는 효과가 0.2초 동안 발생합니다.

<pre>
<code>
.card {
    transition: transform 0.2s ease-in-out;
}

.card:hover {
    transform: scale(1.05);
}
</code>
</pre>
  
- 미디어 쿼리를 사용하여 스마트폰 화면에서 카드 크기를 조정할 수 있습니다.

<pre>
<code>
@media only screen and (max-width: 767px) {
    .col-sm-6 {
        padding: 10px;
    }
}

.card {
    height: auto;
}
</code>
</pre>
  
### 웹사이트 [링크](https://geewhyu.github.io/ElonMusk-Homepage/)
  
<br/>
  
![D0190A05-5122-4A65-A20A-0E2543DFC280](https://github.com/GeeWhyU/ElonMusk-Homepage/assets/134857992/4cd3e95e-3262-4d4b-8a44-5a62bc9b3001)


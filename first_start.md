<h1 id="11-13-1-til">11/13(월) 1일차 TIL</h1>
<hr>
<h2 id="html-css-">HTML과 CSS, 웹 표준과 웹 접근성</h2>
<h3 id="html">HTML</h3>
<p>콘텐츠의 구조를 설계하는 것으로, 이미지를 구현하는 데 초점을 맞춰서는 안 된다.</p>
<h3 id="css">CSS</h3>
<p>패션이라고 생각할 것. 상황에 맞는 옷을 어떻게 입힐 것인지 생각해야 한다.</p>
<h3 id="-">웹 표준</h3>
<p>다양한 브라우저마다 태그와 코드를 어떻게 해석할 것인지를 합의해 표준으로 만드는 작업.</p>
<ul>
<li><a href="https://www.w3.org/">World Wide Web Consortiums (3WC)</a>: 웹 표준을 개발하고 장려하는 조직. 팀 버너스 리를 중심으로 설립되었다.</li>
<li><a href="http://www.aladin.co.kr/shop/wproduct.aspx?ItemId=1024887">제프리 젤드만의 웹표준 가이드</a> : 어떤 식으로 브라우저가 발전해왔는지를 보여주는 책.</li>
</ul>
<h3 id="-">웹 접근성</h3>
<p>장애나 환경을 이유로 접근할 수 없는 서비스가 늘어나고 있다. 누구나 접근할 수 있는 보편적인 개발에 관심을 가지는 것이 중요. 여러 가지 장애에 대한 이해를 가져야 한다. 
<code>ex) iOS 보이스 오버 기능</code></p>
<hr>
<h3 id="-">환경에 대한 이해</h3>
<h4 id="-platform">다양한 Platform</h4>
<p>내가 만든 서비스가 여러 플랫폼에서 돌아가는지 항상 염두에 두어야 한다.</p>
<h4 id="cross-browsing">Cross Browsing</h4>
<h4 id="seo-search-engine-optimization-">SEO(Search Engine Optimization)</h4>
<p>검색 엔진 최적화. 알고리즘 상 표준을 잘 지키고 접근성을 준수했다면 상위에 노출시켜준다. 내가 만든 서비스가 잘 노출될 수 있도록 해준다.</p>
<p>ex) 페이지 <title></title>에 모델명을 노출. 타이틀이 어떤 효과를 담당하는지 모르고 만들면 "환영합니다", "어서오세요" 정도만 담는다.</p>
<h4 id="-">저사양 또는 저속회선</h4>
<p>우리 나라는 네트워크가 빨라서, 저속회선에 대한 고민을 덜 하게 된다. 빠르게 최적화시키는 기술에 대해 알아야 한다.</p>
<h4 id="-">장애인 차별 금지 및 권리 구제 등에 관한 법률</h4>
<p>cf. <a href="https://youtu.be/llQSJ6GLNwM">원숭이 실험(동영상)</a>: 동물조차도 차별에 민감하게 반응한다!</p>
<h4 id="4-">4가지 원칙</h4>
<ol>
<li>Perceivable (인지, 자각)</li>
<li>Operable (운용)</li>
<li>Understandable (이해)</li>
<li>Robust (탄탄한, 견고한)</li>
</ol>
<hr>
<h3 id="-git-">개발환경 및 Git 설정</h3>
<p><a href="https://github.com/seulbinim/FC-FDS/blob/master/README/preferences.md">김데레사 강사님 Github 1 링크</a> 참고
 cf. Git: 버전관리 프로그램. 나중에 배울 예정!</p>
<h3 id="-">터미널 명령어</h3>
<p><a href="https://github.com/seulbinim/FC-FDS/blob/master/README/cli.md">김데레사 강사님 Github 2 링크</a> 참고</p>
<hr>
<h2 id="html-">HTML 코드 살펴보기</h2>
<div class="colorscripter-code" style="color:#f0f0f0; font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important; position:relative !important; overflow:auto"><table class="colorscripter-code-table" style="margin:0; padding:0; border:none; background-color:#272727; border-radius:4px;" cellspacing="0" cellpadding="0"><tbody><tr><td style="padding:6px; border-right:2px solid #4f4f4f"><div style="margin:0; padding:0; word-break:normal; text-align:right; color:#aaa; font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important; line-height:130%"><div style="line-height:130%">1</div><div style="line-height:130%">2</div><div style="line-height:130%">3</div><div style="line-height:130%">4</div><div style="line-height:130%">5</div><div style="line-height:130%">6</div><div style="line-height:130%">7</div><div style="line-height:130%">8</div><div style="line-height:130%">9</div><div style="line-height:130%">10</div><div style="line-height:130%">11</div><div style="line-height:130%">12</div><div style="line-height:130%">13</div><div style="line-height:130%">14</div><div style="line-height:130%">15</div><div style="line-height:130%">16</div><div style="line-height:130%">17</div><div style="line-height:130%">18</div><div style="line-height:130%">19</div></div></td><td style="padding:6px 0"><div style="margin:0; padding:0; color:#f0f0f0; font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important; line-height:130%"><div style="padding:0 6px; white-space:pre; line-height:130%"><span style="color:#f0f0f0">&lt;</span><span style="color:#ff3399">!DOCTYPE</span>&nbsp;<span style="color:#a8ff58">html</span><span style="color:#f0f0f0">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%"><span style="color:#f0f0f0">&lt;</span><span style="color:#ff3399">html</span>&nbsp;<span style="color:#a8ff58">lang</span>=<span style="color:#ffd500">"ko"</span><span style="color:#f0f0f0">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;</div><div style="padding:0 6px; white-space:pre; line-height:130%"><span style="color:#f0f0f0">&lt;</span><span style="color:#ff3399">head</span><span style="color:#f0f0f0">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#f0f0f0">&lt;</span><span style="color:#ff3399">meta</span>&nbsp;<span style="color:#a8ff58">charset</span>=<span style="color:#ffd500">"UTF-8"</span><span style="color:#f0f0f0">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#f0f0f0">&lt;</span><span style="color:#ff3399">title</span><span style="color:#f0f0f0">&gt;</span>웹카페&nbsp;-&nbsp;HTML5,&nbsp;CSS3,&nbsp;웹접근성<span style="color:#f0f0f0">&lt;</span><span style="color:#f0f0f0">/</span><span style="color:#ff3399">title</span><span style="color:#f0f0f0">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%"><span style="color:#f0f0f0">&lt;</span><span style="color:#f0f0f0">/</span><span style="color:#ff3399">head</span><span style="color:#f0f0f0">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;</div><div style="padding:0 6px; white-space:pre; line-height:130%"><span style="color:#f0f0f0">&lt;</span><span style="color:#ff3399">body</span><span style="color:#f0f0f0">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#f0f0f0">&lt;</span><span style="color:#ff3399">div</span>&nbsp;<span style="color:#a8ff58">class</span>=<span style="color:#ffd500">"container"</span><span style="color:#f0f0f0">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#f0f0f0">&lt;</span><span style="color:#ff3399">header</span>&nbsp;<span style="color:#a8ff58">class</span>=<span style="color:#ffd500">"header"</span><span style="color:#f0f0f0">&gt;</span>헤더<span style="color:#f0f0f0">&lt;</span><span style="color:#f0f0f0">/</span><span style="color:#ff3399">header</span><span style="color:#f0f0f0">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#f0f0f0">&lt;</span><span style="color:#ff3399">div</span>&nbsp;<span style="color:#a8ff58">class</span>=<span style="color:#ffd500">"visual"</span><span style="color:#f0f0f0">&gt;</span>비주얼<span style="color:#f0f0f0">&lt;</span><span style="color:#f0f0f0">/</span><span style="color:#ff3399">div</span><span style="color:#f0f0f0">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#f0f0f0">&lt;</span><span style="color:#ff3399">main</span>&nbsp;<span style="color:#a8ff58">class</span>=<span style="color:#ffd500">"main-content"</span><span style="color:#f0f0f0">&gt;</span>메인&nbsp;콘텐트<span style="color:#f0f0f0">&lt;</span><span style="color:#f0f0f0">/</span><span style="color:#ff3399">main</span><span style="color:#f0f0f0">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#f0f0f0">&lt;</span><span style="color:#ff3399">article</span>&nbsp;<span style="color:#a8ff58">class</span>=<span style="color:#ffd500">"slogan"</span><span style="color:#f0f0f0">&gt;</span>슬로건<span style="color:#f0f0f0">&lt;</span><span style="color:#f0f0f0">/</span><span style="color:#ff3399">article</span><span style="color:#f0f0f0">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#f0f0f0">&lt;</span><span style="color:#ff3399">footer</span>&nbsp;<span style="color:#a8ff58">class</span>=<span style="color:#ffd500">"footer"</span><span style="color:#f0f0f0">&gt;</span>푸터<span style="color:#f0f0f0">&lt;</span><span style="color:#f0f0f0">/</span><span style="color:#ff3399">footer</span><span style="color:#f0f0f0">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#f0f0f0">&lt;</span><span style="color:#f0f0f0">/</span><span style="color:#ff3399">div</span><span style="color:#f0f0f0">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%"><span style="color:#f0f0f0">&lt;</span><span style="color:#f0f0f0">/</span><span style="color:#ff3399">body</span><span style="color:#f0f0f0">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;</div><div style="padding:0 6px; white-space:pre; line-height:130%"><span style="color:#f0f0f0">&lt;</span><span style="color:#f0f0f0">/</span><span style="color:#ff3399">html</span><span style="color:#f0f0f0">&gt;</span></div></div><div style="text-align:right; margin-top:-13px; margin-right:5px; font-size:9px; font-style:italic"><a href="http://colorscripter.com/info#e" target="_blank" style="color:#4f4f4f; text-decoration:none">Colored by Color Scripter</a></div></td><td style="vertical-align:bottom; padding:0 2px 4px 0"><a href="http://colorscripter.com/info#e" target="_blank" style="text-decoration:none; color:white"><span style="font-size:9px; word-break:normal; background-color:#4f4f4f; color:white; border-radius:10px; padding:1px">cs</span></a></td></tr></tbody></table></div>
<ul>
<li><code>&lt;!DOCTYPE html&gt;</code>을 선언해줘야 표준.</li>
<li><code>lang</code>: 공용속성(global attribute). 명령어와 관련 없이 쓸 수 있는 것.<ul>
<li>ex) lang, id, class, title, style, data-* 등</li>
<li><code>속성(attribute)="값"</code>으로 표시해준다. (meta 태그 관련)
-아래 두 개는 같은 코드이기 때문에 하나만 적어주면 된다. 우리는 좀 더 짧고 새로운 버전을 적어준다.</li>
<li><code>&lt;meta http-equiv="Content-Type" content="text/html;charset=UTF-8"&gt;(구버전 코드)</code></li>
<li><code>&lt;meta charset="utf-8"&gt; (HTML5 코드)</code> &lt;= 갓챠!</li>
</ul>
</li>
<li>시안이 나오면 구조를 분석해야 함. 콘텐츠 관점에서 바라봐야 한다!</li>
웹 사이트는 3단 구조
<pre><code> <span class="hljs-selector-tag">header</span>
 navigator


 contents


 footer
</code></pre>
<hr>
<h2 id="-">트리구조</h2>
<p>DOM TREE라고 부른다. 문서 안에서 최상위 요소가 HTML이라고 인식. 그 아래 호환되어 있는 요소를 인식. 자식요소가 2개. 가계도가 그려짐. 브라우저가 나중에 내부적으로 그리게 됨.</p>
<h2 id="-">기타</h2>
<ul>
<li><p>줄바꿈은 왜 일어날까? -&gt; CSS 부분!</p>
</li>
<li><p>컴파일러 언어: 컴파일을 하기 전까지는 언어의 형태를 확인할 수가 없음.</p>
</li>
<li>인터프리터 언어</li>
</ul>
<hr>
<h2 id="-">단축키 사용 팁!</h2>
<ul>
<li><p><a href="emmet.io">Emmet</a></p>
<ul>
<li><code>head+body</code> + <code>tab</code>: 형제선택자</li>
<li><p><code>html:5</code> + <code>tab</code>: 기본형을 만들어준다</p>
</li>
<li><p><a href="https://docs.emmet.io/cheat-sheet/">cheatsheet 바로가기</a> </p>
</li>
</ul>
</li>
<li>VS Code<ul>
<li><code>option + 방향키</code>: 코드 위치 조정 가능</li>
<li><code>cmd + shift + P</code>: 토글!</li>
<li><code>cmd + shift + K</code>: 커서가 놓여 있는 한 줄을 전체 다 제거할 때 사용.</li>
<li><a href="https://code.visualstudio.com/docs/editor/codebasics">VS Code 도움말</a></li>
</ul>
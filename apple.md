# apple 제품 카드

### 1. 과제 요구사항

> **`CSS Grid`**를 사용하여 **반응형 레이아웃**을 구현한다.
>
> - 중단점(breakpoint)은 `**1024px**` 로 지정한다.<br>
>   (Small Screen - 1024px 이하 / Large Screen - 1024px 이상)
> - `**theme.css**` 파일에 제공 된 값(색상, 텍스트 크기, 여백 등)을 사용한다.

### 2. 과제 구현

> 1. `card-component.css` 파일에 카드 컴포넌트와 버튼 컴포넌트를 구현 하였습니다.
>
> 2. 버튼 스타일링은 primary, secondary로 나누어 primay는 블루계열 secondary는 블랙 계열을 적용하였고, non-outline, outline도 구별하여 컴포넌트를 스타일링 해두었습니다.
>
> 3. 그리드를 이용하여 컴포넌트들을 배치하였고 그리드 템플릿을 이용하여 각 애플별 제품마다 클래스를 선언하여 grid-area를 정의 해놓고 배치를 하였습니다.
>
> 4. 아이패드 프로, 에어, 아이폰15 프로 는 2컬럼을 모두 차지하게 하고 나머지는 1컬럼씩 차지하게 하여 구현하였습니다.
>
> 5. 버튼에는 hover 클래스 선택자를 이용하여 애니메이션 효과를 주었습니다.

### 3. 구현 결과

<iframe width="560" height="315" src="https://www.youtube.com/embed/DHpSR_ZD3Vc?si=yZGCdlJSvTD7qEKh" title="iOS 스위치 탐색하기" frameborder="0" allowfullscreen></iframe>

### 4. 느낀점

> 레이아웃 정렬을 Flex로만 해봤어서 Grid에 대해서는 잘 몰랐는데 좀 더 익숙해질 수 있는 기회가 되었습니다. 하지만 좀 더 복잡한 레이아웃이었다면 Grid 사용이 좀 더 어려웠을거 같아 앞으로도 익숙해질 수 있게 사용해봐야 할 것 같았습니다. 컴포넌트 부분은 flex를 이용하지 않고 inline-block 과 block으로도 구현 해보았는데 다음에 grid로도 컴퍼넌트 안의 요소들을 배치 해보도록 하려고 합니다.

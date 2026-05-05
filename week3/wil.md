## WIL

### 이번주 배운것
* style.css파일을 별도로 만들어 css를 전체적으로 적용해보았다.
* class를 만들어 특정 서식만 원하는 부분에 적용해보았다.
* devalop branch를 따로 만든 뒤 commit 후 PR를 통해 main에 marge전 리뷰를 받는 법을 배우면서 협업의 기초를 다져보았다.

### Margin과 Padding
* **Margin:** 요소의 테두리 기준 바깥쪽 여백. 주변 다른 요소들과의 간격을 조절할 때 사용.
* **Padding (안쪽 여백):** 요소의 테두리기준 안쪽 여백. 콘텐츠가 테두리에 너무 붙지 않게 내부 공간을 확보할 때 사용.

### Margin과 Padding CSS 사용법

```css
.box {
  /* 1. 상하좌우 모두 안쪽 여백 20px */
  padding: 20px; 
  
  /* 2. 상하 10px, 좌우 30px 바깥 여백 */
  margin: 10px 30px; 
  
  /* 3. 위 10px, 우 20px, 아래 30px, 좌 40px 바깥 여백*/
  margin: 10px 20px 30px 40px; 
  
  /* 특정 방향만 지정 가능*/
  padding-left: 15px;
}
```

본인의 결과물에 대해선 [이용운 자기소개 홈페이지](https://gdg-2026-1-dev-intro.vercel.app/index.html)에서 확인할 수 있다.
# paintjs

바닐라 자바스크립트로 그림판 만들기

```
funcion onMouseMove(event) {
    console.log(event);
    // ...
    // clientX,Y : 윈도우 전체의 범위 내에서 마우스 위치값을 나타냄
    // offsetX,Y : 캔버스 내에서의 좌표
}
canvas.addEventListener('mousemove', onMouseMove);

```

### canvas

convas는 context를 갖고 있는 HTML의 요소
context는 canvas 안에서 픽셀들을 컨트롤 할 수 있음
https://developer.mozilla.org/ko/docs/Web/API/Canvas_API/Tutorial/Basic_usage

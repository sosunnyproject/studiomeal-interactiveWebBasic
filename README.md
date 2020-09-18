# interactive Web Basic
studiomeal 일분코딩 인터렉티브웹 강의 따라하기

## CSS 변환과 애니메이션

- [모질라 MDN: transform](https://developer.mozilla.org/ko/docs/Web/CSS/transform)
- [모질라 MDN: transition](https://developer.mozilla.org/ko/docs/Web/CSS/transition)
    - [css transition examples](https://developer.mozilla.org/ko/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions)
- transform 스타일 스크린샷

<figure style="display: block; margin: 0 auto; text-align: center">
<img src="images/transition-inspector.PNG" width="80%">
<figcaption>css: transform</figcaption>
</figure>

<figure style="display: block; margin: 0 auto; text-align: center">
<img src="images/animation-inspector.PNG" width="80%">
<figcaption>css: transition</figcaption>
</figure>


- transition 과 animation 차이점
    - 애니메이션 특징: keyframe 추가 가능

- ANIMATION 관련 속성들
1. [animation-direction](https://developer.mozilla.org/ko/docs/Web/CSS/animation-direction)

```css
* Single animation */
animation-direction: normal;
animation-direction: reverse;
animation-direction: alternate;
animation-direction: alternate-reverse;

/* Multiple animations */
animation-direction: normal, reverse;
animation-direction: alternate, reverse, normal;

/* Global values */
animation-direction: inherit;
animation-direction: initial;
animation-direction: unset;
```

2. [animation-fill-mode](https://developer.mozilla.org/ko/docs/Web/CSS/animation-fill-mode)
- 애니메이션 오브젝트의 마지막 위치를 정해줄 수 있음.
```css
/* 속성 종류 */
/* Single animation */
animation-fill-mode: none;
animation-fill-mode: forwards;
animation-fill-mode: backwards;
animation-fill-mode: both;

/* Multiple animations */
animation-fill-mode: none, backwards;
animation-fill-mode: both, forwards, none;
```


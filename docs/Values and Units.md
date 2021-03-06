### Values and Units

#### length

**절대길이** 단위

`px` 이라는 고정 값을 사용한다.

**상대길이** 단위

`font-size` 를 `px` 로 고정하는 것은 웹 접근성 측면에서 떨어진다.

`em` 

- 부모의 `font-size` 이다.

`rem`

- `root` 의 `font-size` 이다.
- 브라우저의 기본 `font-size` 를 변경할 경우에도 그에 맞춰 변한다.

`vw`

- 뷰포트의 너비 1%와 같다.

`vh`

- 뷰포트의 높이 1%와 같다.

뷰포트는 변동적이다. 뷰포트의 가로는 `100vw` 세로는 `100vh` 로 표현할 수 있다.

`vmin`

- 뷰포트의 `vw` 나 `vh`  중 작은 것과 같다.

`vmax`

- 뷰포트의 `vw` 나 `vh`  중 큰 것과 같다.

반응형 사이트에서 가로모드 세로모드에 대응할 때 사용한다.

`%`

- 부모 요소의 길이를 `100%` 로 표현하고 그에 맞는 비율에 따른다.

`calc()`

```css
.box {
    width: calc(100% - 50px);
}
```

- 사칙연산을 사용한 값을 사용할 수 있다.
- 연산자 좌우에는 공백이 필요하다.

`min()`

```css
.box {
    width: min(100%, 200px);
}
```

- `,` 로 나열을 하는데 둘 중에 **작은** 값을 채택한다.

`max()`

```css
.box {
    width: max(100%, 500px);
}
```

- `,` 로 나열을 하는데 둘 중에 **큰** 값을 채택한다.
# 🧨font-weight

글꼴의 굵기를 지정하는 속성입니다.

기본 값 : normal

```css
font-weight: normal | bold | bolder | lighter | number | initial | inherit;
```

- normal

  기본 값 (400)

- bold

  굵게 표현(700)

- bolder

  부모 요소 보다 두껍게 표현

- lighter

  부모 요소 보다 얇게 표현

- number

  100, 200, 300, 400, 500, 600, 700, 800, 900 (클수록 더 두껍게 표현)

실무에서는 normal과 bold를 많이 사용하고, 부모 요소에 영향이 있는 bolder와 lighter는 사용을 될 수 있으면 지양하는 편입니다.

물론 상속 관계에서 바뀌어야 하는 스펙이라면 당연히 유용하게 사용될 수 있지만, 그 외의 경우에는 사용에 있어 신중해야 합니다.

font-weight는 normal, bold와 같은 키워드 외에 숫자로도 그 굵기를 표현할 수 있습니다.

100~900까지 100단위로 값을 지정하여 사용할 수 있고 숫자가 커질수록 더욱 굵게 표현됩니다.

기본적으로 400은 normal과 같고, 700은 bold와 같습니다

그러나 수치를 이용한 font-weight는 폰트 자체에서 지원을 해야 표현할 수 있습니다.

폰트에 따라 font-weight를 적용해도 굵기에 변화가 없을 수도 있으며,

normal과 bold만 지원하는 폰트일 경우에는 100~500까지는 normal로, 600~900까지는 bold로 표현됩니다.

폰트가 점차 다양해지면서 굵기 자체를 폰트 family-name으로 가지고 있는 경우도 있습니다.

또한, 디바이스별로 조금 다르게 표현될 수도 있습니다.

font-weight와 font-family, font-size는 서로 밀접하게 연관되어있습니다.

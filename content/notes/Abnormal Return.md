---
title: Abnormal Return
created: 2022-05-01T23:25:26+09:00
updated: 2023-02-21T18:36:50+09:00
publish: true
tags:
- Garden
---

# 1. Meaning
Abnormal Return (비정상 초과 수익률)
**특정 기간동안 특정 [[Stock]] 또는 [[Portfolio]]에서 [[Expected Return]]에서 벗어난 비정상적으로 큰 이익 또는 손실을 나타낸다.** 즉, [[Actual Return]]과 Expected Return 간의 괴리를 설명하는 개념이다.

투자의 성과가 [[Capital Asset Pricing Model]] 또는 과거 [[Long Run]] 평균 수익률 또는 [[Multiple]] 기법을 통해 측정된 [[Risk-Adjusted Return]]에 기반한 **Expected Return과 Actual Return의 차이를 의미한다.**

Abnormal Return은 투자자가 Risk-Adjusted Return을 결정하는 데 도움이 된다. 또한 투자자가 감수한 투자 위험의 양에 대해 적절한 보상을 받았는지 여부를 보여준다.

Abnormal Return은 예상치 못한 이벤트의 결과로 생성될 수 있다.

# 2. Calculating
Abnormal Return은 Actual Return에서 Expected Return을 뺀 값으로  positive or negative가 될 수 있다.

예를 들어, 연간 평균 10%가 예상되는 mutual fund가 30%의 수익을 올리면 20%의 플러스 Abnormal Return이 발생한다. 반면에 이 동일한 예에서 실제 수익률이 5%인 경우 이는 5%의 마이너스 Abnormal Return을 생성한다.

```ad-info
title:
$Abnormal\;Return = Actual\;Return - Expected\;Return$
```

이 수치는 Actual Return이 Expected Return과 어떻게 다른지에 대한 요약일 뿐이다.

# 3. Cumulative Abnormal Return; CAR
Cumulative Abnormal Return; CAR (누적 비정상 수익률)
모든 Abnormal Return의 합계다. 일반적으로 CAR의 계산은 짧은 기간에 이루어진다. 짧은 기간인 이유는 일일 Abnormal Return 을 합산하면 결과에 편향이 생길 수 있기 때문이다.[^1]

CAR은 소송, 매수 및 기타 이벤트가 Stock Prices에 미치는 영향을 측정하는 데 사용되며 기대 성과를 예측할 때 자산 가격 책정 모델의 정확도를 결정하는 데에도 유용하다.

## 3.1. Example of Abnormal Returns
[[Investor]]가 유가 증권 Protfolio의 전년도 Abnormal Return을 계산하려고 한다.

[[Risk-Free Rate Of Return]]이 2% 고 벤치마크 지수의 Expected Return이 15%라고 가정한다. Investor’s Portfolio는 Benchmark Index에 대해 측정했을 때 25%의 Actual Return과 1.25의 Beta를 가진다. 따라서 가정한 [[Risk]]를 감안할 때 Portfolio는 18.25%의 수익을 올렸어야 한다. 이에 따라 전년도 Abnormal Return은 6.75%다.

```ad-info
title: 
[[../Seedbox/Capital Asset Pricing Model]]을 사용하여
$ER_i = R_f + B_i(ER_m-R_f)$
$R_f = 2\%$ 
$B_i = 1.25$
$ER_m = 15\%$
$Actual\;Return = 25\%$

$18.25 = 2\% + 1.25(15\% - 2\%)$

$Abnormal\;Return = Actual\;Return - Expected\;Return$

$6.75\% = 25\% - 18.25\%$
```

동일한 계산이 주식 보유에 도움이 될 수 있다.

예를 들어, ABC 라는 주식이 Benchmark Index에 대해 측정했을 때 9%의 Actual Return을 기록했고 Beta는 2였습니다. Risk-Free Rate of Return이 5%이고 Benchmark Index의 Expected Return이 12%라고 가정한다.

```ad-note
title: 
$19\% = 5\% + 2(12\% - 5\%)$
```

CAPM을 기준으로 주식 ABC의 Expected Return은 19%다.

```ad-note
title: 
$9\% - 19\% = -10\%$
```

따라서 주식 ABC는 -10%의 Abnormal Return 값을 가지며 동일 기간의 시장 수익률을 하회하였다.

# 4. References
https://fnwiki.org/abnormal-return/
https://en.wikipedia.org/wiki/Abnormal_return
https://www.investopedia.com/terms/a/abnormalreturn.asp

[^1]: https://www.semanticscholar.org/paper/Interacting-Biases%2C-Non-Normal-Return-Distributions-Cowan-Sergeant/302aa5b66054c0d8b954f71f7d0dcf5061fe03b7?p2df
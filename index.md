# 조합현안 공유

## 추가분담금 계산기
조합원 여러분들이 쉽게 현재 조합이 입은 큰 손실에 대한 추가분담금을 미리 계산해볼 수 있는 계산기를 만들었습니다. 
선생님의 권리가액은(만원단위로입력)? (조합원 평균 권리가액 2.4억)<input id="your_money" value="0" type="number">

<div>
현재 조합의 손해액은 총
<span id="total_loss"></span>
입니다.
</div>
<div>
현재 비례율은
<span id="current_percentage"></span>
입니다.
</div>
<div>귀하의 현재 추가 분담금은
<span id="your_loss"></span>
입니다.
</div>
현재 계산에 포함된 내역은 다음과 같습니다.
<div id="detail">
</div>

{% include new_analytics.html %}
{% include compute_loss.html %}

# VOC_Situation-Sentiment_Analysis
* 핀테크 특화 감성 사전 구축을 위한 상황별 감성 교차 분석
* 상황별 감성 분석 이후, 12월/1월/2월 VOC 개선해야 할 우선 순위 파악과 동시에 개선했을 때 나타나는 결과 예측
<br> (-> 80% 개선 시나리오로 작성. 기대 만족으로 이동, 20%는 잔여(기존 감정 유지) 100% 해결이 불가능하기 때문에)
</br>

* 12월 VOC 개선해야 할 우선순위와 개선 했을 때, 나타나는 결과 예측
<table>
  <thead>
    <tr style="background-color: #f2f2f2;">
      <th>[AS-IS] 상황별 감성</th>
      <th>[AS-IS] 산출 점수 (Score)</th>
      <th>[TO-BE] 상황별 감성</th>
      <th>[TO-BE] 산출 점수 (Score)</th>
      <th>리스크 감소율 (개선 효율)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>앱 UX * 불만</b></td>
      <td>47건 * 3 * 5 = <b>705</b></td>
      <td>만족 38건 + 불만 9건</td>
      <td>(38*1*5) + (9*3*5) = <b>325</b></td>
      <td align="center"><b>53.9%</b></td>
    </tr>
    <tr>
      <td><b>사후관리 * 불안</b></td>
      <td>24건 * 4 * 5 = <b>480</b></td>
      <td>만족 24건 + 불안 6건</td>
      <td>(24*1*5) + (6*4*5) = <b>240</b></td>
      <td align="center"><b>50.0%</b></td>
    </tr>
    <tr>
      <td><b>앱 UX * 분노</b></td>
      <td>11건 * 5 * 5 = <b>275</b></td>
      <td>만족 9건 + 분노 2건</td>
      <td>(9*1*5) + (2*5*5) = <b>95</b></td>
      <td align="center"><b>65.5%</b></td>
    </tr>
    <tr>
      <td><b>심사 결과 * 불안</b></td>
      <td>15건 * 4 * 4 = <b>240</b></td>
      <td>만족 12건 + 불안 3건</td>
      <td>(12*1*4) + (3*4*4) = <b>96</b></td>
      <td align="center"><b>60.0%</b></td>
    </tr>
    <tr>
      <td><b>사후 관리 * 분노</b></td>
      <td>9건 * 5 * 5 = <b>225</b></td>
      <td>만족 7건 + 분노 2건</td>
      <td>(7*1*5) + (2*5*5) = <b>85</b></td>
      <td align="center"><b>62.2%</b></td>
    </tr>
  </tbody>
</table>
<br>

* 1월 VOC 개선해야 할 우선순위와 개선했을 때 나타나는 결과 예측 
<table>
  <thead>
    <tr style="background-color: #f2f2f2;">
      <th>[AS-IS] 상황별 감성</th>
      <th>[AS-IS] 산출 점수 (Score)</th>
      <th>[TO-BE] 상황별 감성</th>
      <th>[TO-BE] 산출 점수 (Score)</th>
      <th>리스크 감소율 (개선 효율)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>심사결과 * 불안</b></td>
      <td>116건 * 4 * 4 = <b>1,856</b></td>
      <td>만족 92건 + 불안 24건</td>
      <td>(92*1*4) + (24*4*4) = <b>752</b></td>
      <td align="center"><b>59.5%</b></td>
    </tr>
    <tr>
      <td><b>앱UX * 불만</b></td>
      <td>69건 * 3 * 5 = <b>1,035</b></td>
      <td>만족 55건 + 불만 14건</td>
      <td>(55*1*5) + (14*3*5) = <b>485</b></td>
      <td align="center"><b>53.1%</b></td>
    </tr>
    <tr>
      <td><b>사후관리 * 불안</b></td>
      <td>26건 * 4 * 5 = <b>520</b></td>
      <td>만족 20건 + 불안 6건</td>
      <td>(20*1*5) + (6*4*5) = <b>220</b></td>
      <td align="center"><b>57.7%</b></td>
    </tr>
    <tr>
      <td><b>고객지원 * 불안</b></td>
      <td>22건 * 4 * 3 = <b>264</b></td>
      <td>만족 17건 + 불안 5건</td>
      <td>(17*1*3) + (5*4*3) = <b>111</b></td>
      <td align="center"><b>58.0%</b></td>
    </tr>
    <tr>
      <td><b>고객지원 * 불만</b></td>
      <td>29건 * 3 * 3 = <b>261</b></td>
      <td>만족 23건 + 불만 6건</td>
      <td>(23*1*3) + (6*3*3) = <b>123</b></td>
      <td align="center"><b>52.9%</b></td>
    </tr>
  </tbody>
</table>
</br>

* 2월 VOC 개선해야 할 우선순위와 개선했을 때 나타나는 결과 예측 
<table>
  <thead>
    <tr style="background-color: #f2f2f2;">
      <th>[AS-IS] 상황별 감성</th>
      <th>[AS-IS] 산출 점수 (Score)</th>
      <th>[TO-BE] 상황별 감성</th>
      <th>[TO-BE] 산출 점수 (Score)</th>
      <th>리스크 감소율 (개선 효율)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>앱 UX * 불만</b></td>
      <td>108건 * 3 * 5 = <b>1,620</b></td>
      <td>만족 86건 + 불만 22건</td>
      <td>(86*1*5) + (22*3*5) = <b>760</b></td>
      <td align="center"><b>53.1%</b></td>
    </tr>
    <tr>
      <td><b>심사결과 * 불만</b></td>
      <td>80건 * 3 * 4 = <b>960</b></td>
      <td>만족 64건 + 불만 16건</td>
      <td>256 + 192 = <b>448</b></td>
      <td align="center"><b>53.3%</b></td>
    </tr>
    <tr>
      <td><b>심사결과 * 불안</b></td>
      <td>60건 * 4 * 4 = <b>960</b></td>
      <td>만족 48건 + 불안 12건</td>
      <td>192 + 192 = <b>384</b></td>
      <td align="center"><b>60.0%</b></td>
    </tr>
    <tr>
      <td><b>대출신청 * 불안</b></td>
      <td>74건 * 4 * 2 = <b>592</b></td>
      <td>만족 59건 + 불안 15건</td>
      <td>118 + 120 = <b>238</b></td>
      <td align="center"><b>59.8%</b></td>
    </tr>
    <tr>
      <td><b>심사결과 * 분노</b></td>
      <td>22건 * 5 * 4 = <b>440</b></td>
      <td>만족 17건 + 분노 5건</td>
      <td>68 + 100 = <b>168</b></td>
      <td align="center"><b>61.8%</b></td>
    </tr>
  </tbody>
</table>


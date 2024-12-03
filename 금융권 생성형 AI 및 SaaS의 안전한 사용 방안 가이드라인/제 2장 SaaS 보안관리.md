# 제 2장: SaaS 보안관리

## 개요

 해당 장은 금융보안원에서 2024년 8월에 발간한 ‘생성형 AI 및 SaaS 이용 규제특례 관련 보안대책’에 을 기반으로 구체적이고 새로운 항목들을 추가하여 제시할 예정이다. ‘금융권 SaaS활용 생성형 AI 가이드라인’ 는 자국의 자율보안체계 수립에 도움을 주기위한 참고자료로써 제공되며, 의무사항이 아닌 권고 사항에 해당한다. 본 가이드를 통해 각 금융기관이 개별적으로 적합한 보안대책을 수립활 수 있도록 지원하는 것을 목표로한다.

 해당 장의 구성은 ‘SaaS 이용 보안대책’에 대해 다룬다. 규제특례 관련 보안대책을 상세히 분석하여 보다 발전되고 구체적인 보안 대책을 제공할 예정이다. 이를 통해 금융기관들이 최신 보안 요구사항에 맞춰 효율적인 대응책을 마련할 수 있도록 지원할 것이다.

## 2. SaaS 이용 보안대책
**2.1 단말기 보안대책**<br>

2.1.1 SaaS 접속하는 단말기(이하 ‘SaaS 단말기’)의 적정성 여부<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-2fdn{border-color:#9b9b9b;text-align:left;vertical-align:top}
.tg .tg-pylf{background-color:#ddd3d3;border-color:#9b9b9b;font-weight:bold;text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-pylf">항목</th>
    <th class="tg-2fdn">2.1.1 SaaS 단말기 적정성 여부</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-pylf">인증기준</td>
    <td class="tg-2fdn">허용된 단말기만 SaaS에 접속하도록 관리하며, 외부 기기 및 비인가 단말기의 접근을 제한하여 안전성을 확보해야 한다.</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="4">점검항목</td>
    <td class="tg-2fdn">1) SaaS 접속 단말기가 고객정보 및 전자금융거래정보를 처리하는 시스템과 연결되지 않는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">2) 비인가 단말기의 SaaS 접속 차단 정책이 설정되어 있는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">3) MDM 및 UEM 솔루션을 통해 SaaS 접속 단말기의 보안 패치와 운영체제 최신 상태가 유지되는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">4) 접속 시 기기의 운영체제 버전과 보안 패치 수준을 실시간으로 점검하여 보안 요건을 충족하는 기기만 허용하고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-pylf">관련 규제</td>
    <td class="tg-2fdn">개인정보 보호법 제29조 정보통신망 이용촉진 및 정보보호 등에 관한 법률</td>
  </tr>
</tbody>
</table>

 ▶ 점검항목 해설<br>
 I. 점검항목 1<br>
 ● SaaS 접속 단말기가 고객정보 및 전자금융거래정보를 처리하는 시스템과 연결되지 않아야한다.<br>
 &nbsp; ○ 금융서비스 환경에서 민감한 데이터를 보호하기 위해 SaaS 접속 단말기(예: 클라우드 기반 서비스에 연결된 PC)가 고객정보나 전자금융거래정보와 같은 중요한 데이터를 처리하는 시스템에 직접 연결되지 않도록 제한하는 것이 필요하다. 이를 통해 SaaS 접근을 통한 데이터 유출 위험을 방지할 수 있다.<br>
 
 II.  점검항목 2<br>
 ● 비인가 단말기의 SaaS 접속 차단 정책이 설정해야한다.<br>
 &nbsp; ○ 허가되지 않은 외부 단말기가 SaaS에 접근하지 못하도록 정책을 수립하고, 해당 정책이 시스템에 적용되어 있는지 확인해야 한다. 비인가 단말기의 접근을 차단함으로써 데이터의 안전성을 강화할 수 있다.<br>
 
 III. 점검항목 3<br>
 ● MDM 및 UEM 솔루션을 통해 SaaS 접속 단말기의 보안 패치와 운영체제 최신 상태가 유지되도록 해야한다.<br>
 &nbsp; ○ 모바일 디바이스 관리(MDM)와 통합 엔드포인트 관리(UEM) 솔루션을 사용하여 SaaS 접속 단말기가 최신 보안 패치와 운영체제를 유지하고 있는지 점검해야 한다. 이를 통해 취약한 운영체제나 패치가 적용되지 않은 단말기의 사용을 방지하여 보안성을 높일 수 있다.<br>
 
 IV. 점검항목 4<br>
 ● 접속 시 기기의 운영체제 버전과 보안 패치 수준을 실시간으로 점검하여 보안 요건을 충족하는 기기만 허용해야한다.<br>
 &nbsp; ○ SaaS에 접근하는 단말기의 운영체제 버전과 보안 패치 상태를 실시간으로 점검하고, 보안 요건을 충족하지 않는 기기는 접근을 제한하여 시스템의 보안성을 유지해야 한다.<br>

2.1.2 SaaS 접속하는 단말기(이하 ‘SaaS 단말기’)의 적정성 여부<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-2fdn{border-color:#9b9b9b;text-align:left;vertical-align:top}
.tg .tg-pylf{background-color:#ddd3d3;border-color:#9b9b9b;font-weight:bold;text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-pylf">항목</th>
    <th class="tg-2fdn">2.1.2 SaaS 단말기에 대한 망분리 대체 통제 적용 여부</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-pylf">인증기준</td>
    <td class="tg-2fdn">SaaS 단말기에 망분리 수준의 보안 통제를 적용하여 내부망 접근 없이 SaaS 서비스 이용이 가능하도록 통제해야 한다.</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="2">점검항목</td>
    <td class="tg-2fdn">1) SaaS 단말기 사용 시 전산 자료가 암호화되어 전송되는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">2) VDI 환경이 제공되어 내부망 접속 없이 SaaS 서비스에 접근 가능한가?</td>
  </tr>
  <tr>
    <td class="tg-pylf">관련 규제</td>
    <td class="tg-2fdn">개인정보 보호법 제29조 정보통신망 이용촉진 및 정보보호 등에 관한 법률</td>
  </tr>
</tbody>
</table>

▶ 점검항목 해설<br>
I. 점검항목 1<br>
 ● SaaS 단말기 사용 시 전산 자료가 암호화되어 전송되어야한다.<br>
 &nbsp; ○ 전산 자료가 외부망을 통해 전송되는 과정에서 도난 및 유출을 방지하기 위해 데이터 암호화를 적용해야 한다. 이를 통해 전송 과정에서의 정보 보호 수준을 높일 수 있다.<br>
 
 II. 점검항목 2<br>
 ● VDI 환경이 제공되어 내부망 접속 없이 SaaS 서비스에 접근 가능해야한다.<br>
 &nbsp; ○ SaaS 단말기에 VDI 환경을 제공함으로써 실제 내부망에 접근하지 않고도 SaaS 서비스 이용이 가능하도록 해야 한다. 이를 통해 망분리와 유사한 보안 효과를 제공할 수 있다.<br>

2.1.3 SaaS 단말기에서 고개정보 유출 방지를 위한 보안대책의 적정성 여부<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-2fdn{border-color:#9b9b9b;text-align:left;vertical-align:top}
.tg .tg-pylf{background-color:#ddd3d3;border-color:#9b9b9b;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-pylf">항목</th>
    <th class="tg-2fdn">2.1.3 SaaS 단말기에서 고객정보 유출 방지를 위한 보안대책의 적정성 여부</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-pylf">인증기준</td>
    <td class="tg-2fdn">SaaS 전용 단말기 또는 VDI 사용, DRM 및 DLP 적용을 통해 고객정보 유출을 방지하는 보안 대책이 적절히 마련되어야 한다.</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="3">점검항목</td>
    <td class="tg-2fdn">1) SaaS 단말기에 DLP 솔루션이 적용되어 데이터 비정상 유출을 실시간으로 감지 및 차단하는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">2) RBAC을 통해 사용자별로 접근 가능한 데이터 범위를 최소화하였는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">3) DRM을 적용하여 데이터의 무단 복제와 유출을 방지하고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-pylf">관련 규제</td>
    <td class="tg-2fdn">개인정보 보호법 제29조 정보통신망 이용촉진 및 정보보호 등에 관한 법률</td>
  </tr>
</tbody>
</table>

▶ 점검항목 해설<br>
I. 점검항목 1<br>
 ● SaaS 단말기에 DLP 솔루션이 적용되어 데이터 비정상 유출을 실시간으로 감지 및 차단해야한다.<br>
 &nbsp; ○ SaaS 단말기에서 비인가된 데이터 전송을 방지하기 위해 DLP(Data Loss Prevention) 솔루션을 통해 데이터 유출을 실시간으로 감지하고 차단해야 한다. 이를 통해 비정상적인 데이터 유출 시도를 사전에 차단할 수 있다.<br>
 
 II. 점검항목 2<br>
 ● RBAC을 통해 사용자별로 접근 가능한 데이터 범위를 최소화해야한다.<br>
 &nbsp; ○ 역할 기반 접근 제어(RBAC)를 활용하여 각 사용자별로 접근 가능한 데이터 범위를 최소화함으로써 정보 유출 가능성을 줄이는 보안 조치를 마련해야 한다. 이를 통해 사용자의 역할에 따라 불필요한 데이터 접근을 방지할 수 있다.<br>

III. 점검항목 3<br>
 ● DRM을 적용하여 데이터의 무단 복제와 유출을 방지해야한다.<br>
 &nbsp; ○ DRM(Digital Rights Management)을 통해 데이터의 불법 복제와 무단 유출을 방지해야 한다. 이 기술을 통해 SaaS 단말기에서의 데이터 접근 및 사용이 제한되어 보안성을 높일 수 있다.<br>

2.1.4 SaaS 단말기 內 악성코드 감염 방지대책 마련여부<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-2fdn{border-color:#9b9b9b;text-align:left;vertical-align:top}
.tg .tg-pylf{background-color:#ddd3d3;border-color:#9b9b9b;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-pylf">항목</th>
    <th class="tg-2fdn">2.1.4 SaaS 단말기 內 악성코드 감염 방지대책 마련여부</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-pylf">인증기준</td>
    <td class="tg-2fdn">SaaS 단말기에서 악성코드의 감염을 방지하기 위한 보안대책을 마련해야한다.</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="3">점검항목</td>
    <td class="tg-2fdn">1) SaaS 단말기에 EPP 및 EDR 솔루션이 설치되어 악성코드를 실시간으로 탐지 및 차단하고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">2) SaaS 단말기의 보안 솔루션이 자동 업데이트되도록 설정되어 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">3) SaaS 단말기의 이상 행동을 지속적으로 모니터링하고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-pylf">관련 규제</td>
    <td class="tg-2fdn">개인정보 보호법 제29조 정보통신망 이용촉진 및 정보보호 등에 관한 법률</td>
  </tr>
</tbody>
</table>

▶ 점검항목 해설<br>
I. 점검항목 1<br>
 ● SaaS 단말기에 EPP 및 EDR 솔루션이 설치되어 악성코드를 실시간으로 탐지 및 차단해야한다.<br>
 &nbsp; ○ SaaS 단말기에 Endpoint Protection Platform(EPP)와 Endpoint Detection and Response(EDR) 솔루션을 설치하여 악성코드를 실시간으로 탐지하고 차단해야 한다. 이를 통해 악성코드로 인한 보안 위협을 사전에 예방할 수 있다.<br>
 
 II. 점검항목 2<br>
 ● SaaS 단말기의 보안 솔루션이 자동 업데이트되도록 설정해야한다.<br>
 &nbsp; ○ 보안 솔루션이 최신 상태로 유지되도록 자동 업데이트 설정이 필수적이다. 이를 통해 최신 보안 패치를 적용하여 알려진 보안 취약점에 대비할 수 있다.<br>

III. 점검항목 3<br>
 ● SaaS 단말기의 이상 행동을 지속적으로 모니터링해야한다.<br>
 &nbsp; ○ SaaS 단말기의 비정상적인 행동을 지속적으로 모니터링하고, 이상 발생 시 이를 실시간으로 분석하고 대응함으로써 잠재적인 악성코드 감염을 조기에 탐지하고 대응할 수 있다.<br>

2.1.5 모바일 단말기에 특화된 보안대책 마련여부<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-2fdn{border-color:#9b9b9b;text-align:left;vertical-align:top}
.tg .tg-pylf{background-color:#ddd3d3;border-color:#9b9b9b;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-pylf">항목</th>
    <th class="tg-2fdn">2.1.5 모바일 단말기에 특화된 보안대책 마련 여부</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-pylf">인증기준</td>
    <td class="tg-2fdn">모바일 단말기에서 발생할 수 있는 보안 위협을 분석하고, 이에 대한 특화된 보안 대책을 마련하여 문서화해야 한다.</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="4">점검항목</td>
    <td class="tg-2fdn">1) 외부 모바일 기기를 위한 정보보호 정책 및 관련 지침, 절차, 매뉴얼 등이 문서화되어 있는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">2) 모바일 기기 보안정책은 제·개정 시 정보보호 최고 책임자의 승인을 받고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">3) 외부 단말기 도난 방지 조치가 마련되어 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">4) 모바일 기기의 운영체제가 탈옥 여부를 검사하고, 탈옥된 운영체제 사용을 금지하는 보안 조치가 마련되어 있는가?</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="2">관련 규제</td>
    <td class="tg-2fdn">개인정보 보호법 제29조</td>
  </tr>
  <tr>
    <td class="tg-0lax">개인정보의 안전성 확보조치 기준 제4조</td>
  </tr>
</tbody>
</table>

▶ 점검항목 해설<br>
I. 점검항목 1<br>
 ● 외부 모바일 기기를 위한 정보보호 정책 및 관련 지침, 절차, 메뉴얼 등을 문서화 해야한다.<br>
 &nbsp; ○ 예를 들어, 보안위협 및 보안취약점을 기반으로 점검기준을 만족할 수 있게 임의기능 존재 여부, 최소 권한, 입력값 유효성, 중요정보 관리 등의 항목과 각 항목의 세부 점검항목을 포함하여 외부 모바일 기기를 위한 정책을 확인·관리할 수 있도록 정책 및 시행문서 내에 작성해야한다.<br>
 
II. 점검항목 2<br>
 ● 모바일 기기 보안정책은 제·개정 시 정보보호 최고 책임자의 승인을 받아야한다.<br>
 &nbsp; ○ 모바일 기기 보안 정책 및 시행문서에 대한 승인은 조직 내 전결규정 등에 따라 공식적으로 수행되어야하며, 내부 결재 등의 방법으로 승인을 받거나 또는 정보보호 최고 책임자가 정보보호 정책문서에 직접 서명 또는 직인하는 방법도 가능<br>
 
III. 점검항목 3<br>
 ● 외부 단말기 도난 방지 조치를 마련해야한다.<br>
 &nbsp; ○ 공급망 및 공급자에 의해 야기될 수 있는 단말기 도난 등의 발생 가능성을 검토하여 물리적 위협으로부터 보호조치를 마련해야한다.<br>
 &nbsp; ○ 케이블 잠금장치 등을 통해 외부 단말기의 도난 등에 대비하고, 일정 시간 자리 이석 시 PC 종료 처리<br>
  &nbsp; ○ (금융보안원, 금융회사 재택근무 보안안내서)<br>

IV. 점검항목 4<br>
 ● 모바일 기기의 운영체제가 탈옥 여부를 검사하고, 탈옥된 운영체제 사용을 금지하는 보안 조치를 마련해야한다.<br>
 &nbsp; ○ 모바일 기기의 탈옥 여부를 검사하는 도구를 사용하여 탈옥된 기기의 접속을 차단하는 정책 마련<br>


**2.2 SaaS 연계 보안 대책**<br>
2.2.1 SaaS 단말기 ↔ SaaS 간 인가된 SaaS 단말기만 접속할 수 있도록 구성하고 있는지 여부<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-2fdn{border-color:#9b9b9b;text-align:left;vertical-align:top}
.tg .tg-pylf{background-color:#ddd3d3;border-color:#9b9b9b;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-pylf">항목</th>
    <th class="tg-2fdn">2.2.1 SaaS 단말기 ↔ SaaS 간 인가된 SaaS 단말기만 접속할 수 있도록 구성하고 있는지 여부</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-pylf">인증기준</td>
    <td class="tg-2fdn">SaaS에 접속하는 모든 단말기는 등록, 인증 및 관리 절차를 거쳐 인가된 단말기만 접근할 수 있도록 설정해야한다.</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="4">점검항목</td>
    <td class="tg-2fdn">1) SaaS 접속 단말기가 인증서를 통해 식별 및 인증되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">2) IP 화이트리스트 및 접근 제어가 설정되어 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">3) SaaS 접속 시 다중 요소 인증(MFA)이 적용되어 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">4) 단말기 접근 로그가 기록 및 주기적으로 감사되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-pylf">관련 규제</td>
    <td class="tg-2fdn">ISO 27001 A.9.1</td>
  </tr>
</tbody>
</table>

▶ 점검항목 해설<br>
I. 점검항목 1<br>
 ● SaaS 접속 단말기가 인증서를 통해 식별 및 인증 되어야한다.<br>
 &nbsp; ○ SaaS에 접근하는 단말기는 고유한 디지털 인증서를 통해 식별되어야 하며, 이를 통해 인가된 단말기만이 SaaS에 접근할 수 있도록 해야 한다. 이를 통해 미승인된 단말기의 접근을 사전에 차단할 수 있다.<br>
 
 II. 점검항목 2<br>
 ● IP 화이트리스트 및 접근 제어가 설정해야한다.<br>
 &nbsp; ○ 인가된 단말기만 접근할 수 있도록 IP 화이트리스트를 설정하고 특정 네트워크 또는 IP 대역에서만 접속을 허용함으로써 외부 비인가 접근을 효과적으로 차단해야 한다.<br>

III. 점검항목 3<br>
 ● SaaS 접속 시 다중 요소 인증(MFA)이 적용해야한다.<br>
 &nbsp; ○ 단순 비밀번호 인증 외에 다중 요소 인증(MFA)을 추가로 적용하여 접근 보안을 강화해야 한다. 이를 통해 비인가된 접근을 보다 엄격하게 제한할 수 있다.<br>

IV. 점검항목 4<br>
 ● 단말기 접근 로그가 기록 및 주기적으로 감사되어야한다.<br>
 &nbsp; ○ SaaS 단말기의 접근 기록은 모두 저장되어야 하며, 접근 로그는 정기적으로 감사 및 검토하여 비정상적인 접근 시도를 확인하고 대응할 수 있도록 해야 한다.<br>

2.2.2 SaaS 비인가 접근 방지를 위한 안전한 인증방식 적용 여부<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-2fdn{border-color:#9b9b9b;text-align:left;vertical-align:top}
.tg .tg-pylf{background-color:#ddd3d3;border-color:#9b9b9b;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-pylf">항목</th>
    <th class="tg-2fdn">2.2.2 SaaS 비인가 접근 방지를 위한 안전한 인증방식 적용 여부</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-pylf">인증기준</td>
    <td class="tg-2fdn">SaaS 서비스에 접근하는 모든 사용자는 다중 요소 인증, 강력한 비밀번호 정책 및 인증 정보 보호 등의 안전한 인증방식을 통해 보호되어야 한다.</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="4">점검항목</td>
    <td class="tg-2fdn">1) SaaS 서비스에 다중 요소 인증(MFA)이 적용되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">2) 비밀번호가 암호화 및 해시 알고리즘(SHA-256 이상)을 통해 안전하게 보호되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">3) 비밀번호 정책이 적용되어 주기적으로 변경되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">4) 인증 실패 시 계정을 잠그거나 추가 인증 절차가 요구되는가?</td>
  </tr>
  <tr>
    <td class="tg-pylf">관련 규제</td>
    <td class="tg-2fdn">ISO 27001 A.9.4</td>
  </tr>
</tbody>
</table>

▶ 점검항목 해설<br>
I. 점검항목 1<br>
 ● SaaS 서비스에 다중 요소 인증(MFA)이 적용되어야한다.<br>
 &nbsp; ○ 단순 비밀번호 인증 외에 OTP, 생체 인식 등 추가적인 인증 요소를 포함한 다중 요소 인증을 통해 사용자 계정 보안을 강화하여 비인가 접근을 방지해야 한다.<br>
 
 II. 점검항목 2<br>
 ● 비밀번호가 암호화 및 해시 알고리즘(SHA-256 이상)을 통해 안전하게 보호되어야한다.<br>
 &nbsp; ○ SaaS 서비스에 사용되는 비밀번호는 SHA-256 이상의 안전한 암호화 및 해시 알고리즘을 통해 저장하고 보호하여 불법적인 접근 시도와 정보 유출을 방지해야한다.<br>

III. 점검항목 3<br>
 ● 비밀번호 정책이 적용되어 주기적으로 변경되어야한다.<br>
 &nbsp; ○ 강력한 비밀번호 정책을 적용하여 최소 길이와 복잡성을 요구하며, 사용자는 주기적으로 비밀번호를 변경하고 이전 비밀번호를 사용할 수 없도록 설정<br>

IV. 점검항목 4<br>
 ● 인증 실패 시 계정을 잠그거나 추가 인증 절차를 요구해야한다.<br>
 &nbsp; ○ 비정상적인 로그인 시도를 감지하고 일정 횟수 이상의 인증 실패 시 계정을 잠그거나 추가적인 인증 단계를 요구함으로써 비인가 접근을 예방하고 사용자 계정을 보호해야 한다.<br>

2.2.3 SaaS 이용 네트워크 트래픽과 전자금융거래 등 대고객 네트워크 트래픽이 상호 혼용되지 않도록 네트워크를 구성하고 있는지 여부<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-2fdn{border-color:#9b9b9b;text-align:left;vertical-align:top}
.tg .tg-pylf{background-color:#ddd3d3;border-color:#9b9b9b;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-pylf">항목</th>
    <th class="tg-2fdn">2.2.3 SaaS 이용 네트워크 트래픽과 전자금융거래 등 대고객 네트워크 트래픽이 상호 혼용되지 않도록 네트워크를 구성하고 있는지 여부</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-pylf">인증기준</td>
    <td class="tg-2fdn">SaaS 이용 네트워크 트래픽과 전자금융거래 등 대고객 네트워크 트래픽이 상호 혼용되지 않도록 네트워크를 구성해야한다.</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="3">점검항목</td>
    <td class="tg-2fdn">1) SaaS와 전자금융거래 네트워크 트래픽이 물리적 또는 논리적으로 분리되어 있는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">2) 방화벽 설정을 통해 두 네트워크 간의 트래픽이 혼용되지 않도록 관리하고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">3) 네트워크 트래픽을 실시간으로 모니터링하고 이상 트래픽 발생 시 경고 시스템이 작동하는가?</td>
  </tr>
  <tr>
    <td class="tg-pylf">관련 규제</td>
    <td class="tg-2fdn">ISO 27001 A.8.22</td>
  </tr>
</tbody>
</table>

▶ 점검항목 해설<br>
I. 점검항목 1<br>
 ● SaaS와 전자금융거래 네트워크 트래픽이 물리적 또는 논리적으로 분리해야한다.<br>
 &nbsp; ○ SaaS와 전자금융거래 트래픽을 서로 다른 VLAN, 서브넷, 또는 독립된 네트워크 장비를 통해 구분하여 운영해야 한다. 이를 통해 두 트래픽이 혼용되지 않도록 하여 보안성을 강화할 수 있다.<br>
 
 II. 점검항목 2<br>
 ● 방화벽 설정을 통해 두 네트워크 간의 트래픽이 혼용되지 않도록 관리해야한다.<br>
 &nbsp; ○ 방화벽과 라우터 설정을 통해 SaaS와 전자금융거래 네트워크 간의 트래픽이 서로 혼합되지 않도록 해야 한다. 이를 통해 불필요한 네트워크 간 접근을 제한할 수 있다.<br>

III. 점검항목 3<br>
 ● 네트워크 트래픽을 실시간으로 모니터링하고 이상 트래픽 발생 시 경고 시스템이 작동되어야한다.<br>
 &nbsp; ○ SaaS 및 전자금융거래 네트워크 트래픽을 실시간으로 모니터링하고, 의심스러운 트래픽 발생 시 경고 시스템을 통해 즉각적인 대응이 가능하도록 하여 네트워크 보안을 강화해야 한다.<br>

2.2.4 SaaS 단말기 ↔ SaaS 연계 네트워크 구간에 안전한 암호 알고리즘을 통한 암호화 적용 여부<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-2fdn{border-color:#9b9b9b;text-align:left;vertical-align:top}
.tg .tg-pylf{background-color:#ddd3d3;border-color:#9b9b9b;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-pylf">항목</th>
    <th class="tg-2fdn">2.2.4 SaaS 단말기 ↔ SaaS 연계 네트워크 구간에 안전한 암호 알고리즘을 통한 암호화 적용 여부</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-pylf">인증기준</td>
    <td class="tg-2fdn">SaaS 단말기와 SaaS 연계 네트워크 구간에 안전한 암호 알고리즘을 통한 암호화를 적용해야한다.</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="3">점검항목</td>
    <td class="tg-2fdn">1) TLS 1.2 이상 프로토콜과 AES-256, RSA-2048과 같은 강력한 암호화 방식이 사용되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">2) 암호화 키가 안전한 환경에서 생성 및 관리되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">3) 네트워크 통신 설정에 취약한 암호화 알고리즘이나 설정이 사용되지 않도록 구성되어 있는가?</td>
  </tr>
  <tr>
    <td class="tg-pylf">관련 규제</td>
    <td class="tg-2fdn">ISO 27001 A.8.24</td>
  </tr>
</tbody>
</table>

▶ 점검항목 해설<br>
I. 점검항목 1<br>
 ● TLS 1.2 이상 프로토콜과 AES-256, RSA-2048과 같은 강력한 암호화 방식을 사용 해야한다.<br>
 &nbsp; ○ SaaS 연계 네트워크 구간에 TLS 1.2 이상의 안전한 프로토콜과 AES-256 또는 RSA-2048과 같은 강력한 암호화 알고리즘을 사용하여 네트워크 상에서 데이터가 안전하게 전송되도록 해야 한다.<br>
 
 II. 점검항목 2<br>
 ● 암호화 키가 안전한 환경에서 생성 및 관리 되어야한다.<br>
 &nbsp; ○ 암호화 키는 HSM(하드웨어 보안 모듈)이나 클라우드 기반 키 관리 시스템을 통해 안전하게 관리되어야 하며, 생성, 저장, 갱신 및 폐기 단계 모두에서 보안 절차가 준수되어야 한다.<br>

III. 점검항목 3<br>
 ● 네트워크 통신 설정에 취약한 암호화 알고리즘이나 설정이 사용되지 않도록 구성해야한다.<br>
 &nbsp; ○ SSL, TLS 1.0/1.1 버전, RC4, MD5와 같은 취약한 암호화 알고리즘이나 구성은 제거하고, 강력한 암호화 통신 설정이 적용되도록 관리해야 한다. 이를 통해 잠재적인 보안 취약점을 예방할 수 있다.<br>

**2.3 SaaS 관리 보안대책**<br>
2.3.1 사용자 또는 그룹별 SaaS 역할 및 권한이 업무데 필요한 최소한의 범위로 제한되어 있는지 여부<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-2fdn{border-color:#9b9b9b;text-align:left;vertical-align:top}
.tg .tg-pylf{background-color:#ddd3d3;border-color:#9b9b9b;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-pylf">항목</th>
    <th class="tg-2fdn">2.3.1 사용자 또는 그룹별 SaaS 역할 및 권한이 업무에 필요한 최소한의 범위로 제한되어 있는지 여부</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-pylf">인증기준</td>
    <td class="tg-2fdn">사용자 또는 그룹별 SaaS 역할 및 권한이 업무에 필요한 최소한의 범위로 제한하여 정기적인 검토가 이루어져야한다.</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="3">점검항목</td>
    <td class="tg-2fdn">1) 사용자별 접근 권한이 직무 및 역할에 따라 최소화되어 설정되어 있는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">2) 특수권한 부여 시 모니터링 및 현황 관리가 이루어지고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">3) 외부자 접근 시 사용 기간 및 위치 제한이 설정되어 있는가?</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="2">관련 규제</td>
    <td class="tg-2fdn">개인정보의 안전성 확보조치 기준 제5조</td>
  </tr>
  <tr>
    <td class="tg-0lax">ISO 27001 A.9.2</td>
  </tr>
</tbody>
</table>

▶ 점검항목 해설<br>
I. 점검항목 1<br>
 ● 사용자별 접근 권한이 직무 및 역할에 따라 최소화되어 설정되어야한다.<br>
 &nbsp; ○ SaaS 접근 권한은 사용자의 직무와 역할에 따라 최소화되어야 하며, 이를 통해 불필요하거나 과도한 정보 접근을 방지해야 한다. 최소 권한 원칙에 따라 접근 권한을 정의하고 세분화하는 것이 중요하다.<br>
 
 II. 점검항목 2<br>
 ● 특수권한 부여 시 모니터링 및 현황관리가 이루어져야한다.<br>
 &nbsp; ○ 특수권한은 반드시 필요한 경우에만 부여해야 하며, 특수권한을 부여받은 계정에 대한 모니터링과 현황 관리를 통해 이 권한이 남용되지 않도록 관리해야 한다.<br>

III. 점검항목 3<br>
 ● 외부자 접근 시 사용 기간 및 위치 제한이 설정되어야한다.<br>
 &nbsp; ○ 정보시스템 유지보수 등을 위해 외부자에게 계정 및 접근권한을 부여하는 경우에는 사용 기간과 접근 위치를 제한하여 보안을 강화하고, 외부자의 과도한 접근을 방지해야 한다.<br>

2.3.2 SaaS 관리자는 부적절한 공유 설정이 존재하는 지 여부를 주기적으로 점검하고, 부적절한 공유 설정이 확인되는 경우 이를 제거하는 체계가 마련되어 있는지 여부<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-2fdn{border-color:#9b9b9b;text-align:left;vertical-align:top}
.tg .tg-pylf{background-color:#ddd3d3;border-color:#9b9b9b;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-pylf">항목</th>
    <th class="tg-2fdn">2.3.2 SaaS 관리자는 부적절한 공유 설정이 존재하는 지 여부를 주기적으로 점검하고, 부적절한 공유 설정이 확인되는 경우 이를 제거하는 체계가 마련되어 있는지 여부</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-pylf">인증기준</td>
    <td class="tg-2fdn">SaaS 내 오픈 쉐어 설정이 주기적으로 점검되어야 하며, 부적절한 공유 설정을 발견할 경우 이를 신속히 제거할 수 있는 절차가 마련되어야 함.</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="3">점검항목</td>
    <td class="tg-2fdn">1) 오픈 쉐어 설정에 대한 주기적인 점검이 이루어지고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">2) 부적절한 공유 설정이 발견될 경우 이를 제거하는 체계가 마련되어 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">3) 게스트 사용자 및 오픈 액세스 그룹의 공유 설정이 제한되어 있는가?</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="2">관련 규제</td>
    <td class="tg-2fdn">ISO 27001 A.9.1</td>
  </tr>
  <tr>
    <td class="tg-0lax">개인정보의 안전성 확보조치 기준 제5조</td>
  </tr>
</tbody>
</table>

▶ 점검항목 해설<br>
I. 점검항목 1<br>
 ● 오픈 쉐어 설정에 대한 주기적인 점검이 이루어져야한다.<br>
 &nbsp; ○ 오픈 쉐어 설정을 주기적으로 점검하여 부적절한 공유 설정을 사전에 발견하고 관리할 수 있어야 한다. 이를 통해 불필요한 정보 접근을 방지할 수 있다.<br>
 
 II. 점검항목 2<br>
 ● 부적절한 공유 설정이 발견될 경우 이를 제거하는 체계가 마련되어야한다.<br>
 &nbsp; ○ 부적절한 공유 설정을 확인하는 즉시 이를 신속하게 제거할 수 있는 절차와 체계가 필요하다. 이를 통해 불필요하거나 무분별한 정보 공개를 막을 수 있다.<br>

III. 점검항목 3<br>
 ● 게스트 사용자 및 오픈 액세스 그룹의 공유 설정이 제한되어 있어야한다.<br>
 &nbsp; ○ 모든 인증된 사용자나 게스트 사용자가 접근할 수 있는 오픈 액세스 그룹 내 공유 설정은 최소화하고 필요 시 제한하여 정보 유출 위험을 줄여야 한다.<br>

2.3.3 SaaS 사용자 및 관리자의 SaaS 접속 및 이용 로그를 기록하고 로그 보존 기간을 1년 이상으로 설정하고 있는지 여부<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-2fdn{border-color:#9b9b9b;text-align:left;vertical-align:top}
.tg .tg-pylf{background-color:#ddd3d3;border-color:#9b9b9b;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-pylf">항목</th>
    <th class="tg-2fdn">2.3.3 SaaS 사용자 및 관리자의 SaaS 접속 및 이용 로그를 기록하고 로그 보존 기간을 1년 이상으로 설정하고 있는지 여부</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-pylf">인증기준</td>
    <td class="tg-2fdn">SaaS 접속 및 이용 로그는 사고 발생 시 책임 추적성을 보장하기 위해 최소 1년간 안전하게 보관되어야 하며, 주요 접속 정보가 포함되어야 함.</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="3">점검항목</td>
    <td class="tg-2fdn">1) SaaS 접속 로그가 1년 이상 안전하게 보관되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">2) 접속 주체 정보, 접속 시간, IP/MAC 정보 등이 로그에 포함되어 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">3) 개인정보 다운로드가 발생한 경우 이를 별도로 기록하고 관리하고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="2">관련 규제</td>
    <td class="tg-2fdn">개인정보의 안전성 확보조치 기준 제8조</td>
  </tr>
  <tr>
    <td class="tg-0lax">ISO 27001 A.12.4</td>
  </tr>
</tbody>
</table>

▶ 점검항목 해설<br>
I. 점검항목 1<br>
 ● SaaS 접속 로그가 1년 이상 안전하게 보관되어야한다.<br>
 &nbsp; ○ SaaS 서비스의 접속 로그는 최소 1년 동안 보관되어야 하며, 5만 명 이상의 정보주체 또는 민감정보를 포함하는 경우 2년 이상 보관하여 책임 추적성을 보장해야 한다.<br>
 
 II. 점검항목 2<br>
 ● 접속 주체 정보, 접속 시간, IP/MAC 정보 등이 로그에 포함되어야한다.<br>
 &nbsp; ○ SaaS 시스템에 접근한 사용자의 계정 정보, 접속 시간, IP/MAC 주소 등이 포함된 접근기록이 남아야 하며, 이를 통해 필요 시 접근 행위에 대한 추적이 가능해야 한다.<br>

III. 점검항목 3<br>
 ● 개인정보 다운로드가 발생한 경우 이를 별도로 기록하고 관리해야한다.<br>
 &nbsp; ○ 개인정보 다운로드가 발생한 경우에는 그 사유를 별도로 기록하고, 이를 월 1회 이상 점검하여 불법적이거나 비인가된 다운로드가 발생하지 않도록 관리해야 한다.<br>

2.3.4 SaaS 관리자는 SaaS 이용 로그, SaaS 접속 인증 오류, SaaS 중요 구성 변경 등에 대해 모니터링 하고, 이상 징후 발견 시 확인 등 보안조치를 이행하는 지 여부<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-2fdn{border-color:#9b9b9b;text-align:left;vertical-align:top}
.tg .tg-pylf{background-color:#ddd3d3;border-color:#9b9b9b;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-pylf">항목</th>
    <th class="tg-2fdn">2.3.4 SaaS 관리자는 SaaS 이용 로그, SaaS 접속 인증 오류, SaaS 중요 구성 변경 등에 대해 모니터링하고 이상 후 발견 시 확인 등 보안조치를 이행하는지 여부</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-pylf">인증기준</td>
    <td class="tg-2fdn">SaaS 시스템의 이용 로그와 접속 오류, 구성 변경 사항 등을 주기적으로 모니터링하며, 이상이 발견되면 보안 조치를 즉시 이행해야 함.</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="3">점검항목</td>
    <td class="tg-2fdn">1) SaaS 이용 로그와 접속 오류에 대한 주기적인 모니터링이 이루어지고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">2) 중요 구성 변경 시 로그 기록과 이상 발생 시 보안 조치가 이루어지고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">3) 모니터링 결과 이상이 발견되었을 경우 보고 및 대응 절차가 마련되어 있는가?</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="2">관련 규제</td>
    <td class="tg-2fdn">전자금융감독규정 제14조</td>
  </tr>
  <tr>
    <td class="tg-0lax">ISO 27001 A.12.4</td>
  </tr>
</tbody>
</table>

▶ 점검항목 해설<br>
I. 점검항목 1<br>
 ● SaaS 이용 로그와 접속 오류에 대한 주기적인 모니터링이 이루어져야한다.<br>
 &nbsp; ○ SaaS 시스템 이용에 대한 로그와 접속 오류 기록을 주기적으로 모니터링하여 사용자의 의심스러운 접근 시도나 비정상적인 활동을 감지해야 한다. 예를 들어, 비정상적으로 빈번한 로그인 시도 실패가 발생했을 경우 이를 실시간으로 모니터링하여 접근 제한 조치를 취할 수 있다.<br>
 
 II. 점검항목 2<br>
 ● 중요 구성 변경 시 로그 기록과 이상 발생 시 보안 조치가 이루어져야한다.<br>
 &nbsp; ○ SaaS 시스템의 중요한 설정 변경 사항(예: 사용자 권한 변경 또는 보안 설정 수정)에 대해 로그를 남기고, 변경 후 발생할 수 있는 보안 이상에 대해 빠르게 대응할 수 있는 체계가 필요하다. 예를 들어, 관리자 권한이 비인가된 사용자에게 부여된 경우 이를 즉시 발견하고 해당 권한을 회수하는 조치가 이루어져야 한다.<br>

III. 점검항목 3<br>
 ● 모니터링 결과 이상이 발견되었을 경우 보고 및 대응 절차가 마련되어야한다.<br>
 &nbsp; ○ SaaS 시스템에서 이상 활동이 감지되었을 경우 이를 관련 책임자에게 보고하고, 정해진 절차에 따라 보안 조치를 수행하는 체계가 마련되어야 한다. 예를 들어, 특정 사용자가 민감한 데이터 다운로드를 반복적으로 시도했을 경우, 이를 보고하고 해당 사용자의 접근을 제한하거나 추가적인 인증 절차를 요구하는 등의 대응이 이루어져야 한다.<br>

2.3.5 SaaS 內 파일의 악성코드 감염 방지대책 마련 여부<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-2fdn{border-color:#9b9b9b;text-align:left;vertical-align:top}
.tg .tg-pylf{background-color:#ddd3d3;border-color:#9b9b9b;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-pylf">항목</th>
    <th class="tg-2fdn">2.3.5 SaaS 내 파일의 악성코드 감염 방지 대책 마련여부</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-pylf">인증기준</td>
    <td class="tg-2fdn">SaaS 환경에서 파일의 업로드, 다운로드 저장시 발생할 수 있는 악성코드 감염을 방지하기 위해 다츨적인 보안 체계를 구축하는 등의 보안 대책을마련해야한다.</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="4">점검항목</td>
    <td class="tg-2fdn">1) SaaS 내 파일 업로드 및 다운로드 시 실시간 악성코드 검사 솔루션이 적용되어 있는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">2) 파일 전송 및 저장 시 데이터 암호화가 이루어지고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">3) 사용자와 장치에 대해 지속적인 접근 검증이 이루어지고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">4) 파일 접근 로그가 체계적으로 기록 및 관리되고 있으며, 이상 징후에 대해 모니터링이 이루어지고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="3">관련 규제</td>
    <td class="tg-2fdn">개인정보 보호법 제 29조 (안전조치의무)</td>
  </tr>
  <tr>
    <td class="tg-0lax">개인정보 보호법 제 34조 (개인정보 유출 등의 통지·신고)</td>
  </tr>
  <tr>
    <td class="tg-0lax">정보통신망 이용촉진 및 정보보호 등에 관한 법률 제 45조의 2(정보보호 사전점검)</td>
  </tr>
</tbody></table>

▶ 점검항목 해설<br>
I. 점검항목 1 <br>
 ● SaaS 내에서 파일 업로드 및 다운로드 시 실시간 악성코드 검사를 수행하는 보안 솔루션이 적절히 설치 및 운영되고 있는지 정기적으로 점검해야 한다. 보안사고 발생 시 해당 솔루션의 성능을 재평가하고, 필요에 따라 추가적인 조치 및 업데이트가 이루어져야 한다.<br>
 &nbsp; ○ 검토 대상 : 실시간 악성코드 검사 솔루션의 설치 및 정상 작동 여부<br>
  &nbsp; ○ 검토 시기 : 최소 연 1회 이상 정기 점검, 보안 사고 발생 시 추가 검토<br>
   &nbsp; ○ 기록 항목 : 악성코드 탐지 이력, 솔루션 업데이트 내역, 보안사고 발생 시 대응 조치 등<br>
    &nbsp; ○ 추가 검토 사항 : 새로운 악성코드 위협 등장 시 솔루션의 적절성 재평가 및 업데이트 필요, 법규 변경 시 관련 사항 반영<br>
 
 II. 점검항목 2<br>
 ● 파일 전송 및 저장 시 데이터를 암호화하여 보호하는 조치가 이루어졌는지 주기적으로 점검해야 하며, 보안사고 발생이나 법규 변경 또는 새로운 위협 발견 시 추가적인 검토가 필요하다. 필요 시 암호화 정책을 즉각 갱신해야 한다.<br>
 &nbsp; ○ 검토 대상 : 전송 중 데이터 및 저장된 데이터의 암호화 여부<br>
  &nbsp; ○ 검토 시기 : 최소 연 1회 정기 점검, 법규 제·개정 또는 보안사고 발생 시 추가 점검<br>
   &nbsp; ○ 기록 항목 : 암호화 방식(예: TLS, AES), 암호화 솔루션 검토 이력, 정책 변경 내역<br>
    &nbsp; ○ 추가 검토 사항 : 암호화 알고리즘의 최신 상태 유지, 법규 변경 시 적용 기술의 적합성 재평가<br>

III. 점검항목 3<br>
 ● 사용자의 신원과 장치의 접근 권한을 지속적으로 검증하는 절차가 적용되고 있는지 확인해야 한다. 정보보호 정책이 변경되거나 주요 보안 이슈가 발생했을 때에는 해당 사항을 이용자에게 즉시 공지해야 한다.<br>
 &nbsp; ○ 검토 대상 : 사용자 및 장치의 인증 및 접근 권한 검증 프로세스<br>
 &nbsp; ○ 검토 시기 : 최소 연 1회 정기 점검, 보안 정책 변경 시 추가 점검<br>
  &nbsp; ○ 공지 사항 : 정보보호 정책 변경사항, 주요 보안 이슈<br>
   &nbsp; ○ 기록 항목 : 접근 검증 기록, 정책 변경 내역, 사용자 공지 이력<br>
   &nbsp; ○ 추가 검토 사항 : 새로운 보안 위협 또는 사용자 인증 기술의 변화에 따라 접근 검증 시스템의 적절성 재검토, 법규 및 기술 변화 시 대응 필요<br>

IV. 점검항목 4<br>
 ● 파일 접근 로그는 체계적으로 기록되어야 하며, 이를 기반으로 이상 징후를 지속적으로 모니터링해야 한다. 보안사고 발생 시 추가적인 검토와 후속 조치를 신속히 취해야 한다. 또한 법규 변경 시 관련 정책을 반영하여 업데이트해야 한다.<br>
 &nbsp; ○ 검토 대상 : 파일 접근 로그 기록 시스템 및 이상 징후 모니터링 도구<br>
 &nbsp; ○ 검토 시기 : 최소 연 1회 정기 점검, 보안사고 및 법규 변경 시 추가 점검<br>
  &nbsp; ○ 기록 항목 : 로그 기록 내역, 이상 징후 탐지 및 대응 이력, 모니터링 결과<br>
   &nbsp; ○ 추가 검토 사항 : 로그 관리 및 모니터링 시스템의 최신 상태 유지, 법규 및 기술 변화 시 모니터링 시스템의 적합성 재평가<br>

2.3.6 SaaS에 가명처리를 하지 않은 개인신용정보 등 중요 정보가 업로드 되는지 주기적으로 점검하고, 업로드 확인 시 보안조치 이행 여부<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-2fdn{border-color:#9b9b9b;text-align:left;vertical-align:top}
.tg .tg-pylf{background-color:#ddd3d3;border-color:#9b9b9b;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-pylf">항목</th>
    <th class="tg-2fdn">2.3.6 SaaS에 가명 처리를 하지 않은 개인신용정보 등 중요정보가 업로드 되는지 주기적으로 점검하고, 업로드 확인 시 보안조치 이행 여부</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-pylf">인증기준</td>
    <td class="tg-2fdn">SaaS에 가명 처리되지 않은 개인 신용 정보 등 중요 정보가 업로드되는지 주기적으로 점검하고, 발견 시 즉각적인 보안 조치를 시행해야 함.</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="3">점검항목</td>
    <td class="tg-2fdn">1) SaaS 환경에서 중요 정보 업로드를 주기적으로 모니터링하고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">2) 중요 정보 업로드 시 자동화된 보안 조치가 이루어지고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">3) 사용자 대상 중요 정보 업로드 금지 관련 정기 교육이 시행되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="2">관련 규제</td>
    <td class="tg-2fdn">개인정보의 안전성 확보조치 기준 제8조</td>
  </tr>
  <tr>
    <td class="tg-0lax">ISO 27001 A.12.4</td>
  </tr>
</tbody>
</table>

▶ 점검항목 해설<br>
I. 점검항목 1 <br>
 ● SaaS 환경에서 중요 정보 업로드를 주기적으로 모니터링 해야한다.<br>
 &nbsp; ○ SaaS 시스템에 업로드되는 모든 파일을 DLP(Data Loss Prevention) 솔루션을 통해 주기적으로 스캔하여 민감한 정보가 포함된 파일을 실시간으로 감지해야 한다. 예를 들어, 고객의 신용정보가 포함된 파일이 업로드된 경우, 이를 즉시 식별할 수 있어야 한다.<br>
 
 II. 점검항목 2<br>
 ● 중요 정보 업로드 시 자동화된 보안 조치가 이루어져야한다.<br>
 &nbsp; ○ 민감 정보가 업로드된 경우 자동으로 해당 파일을 삭제하거나 사용자를 경고하는 등 보안 조치가 즉시 이루어져야 한다. 예를 들어, 개인 신용 정보가 포함된 파일을 발견하면 즉시 삭제하고, 이를 위반한 사용자에게 경고 메시지를 발송하는 체계를 갖추어야 한다.<br>
  
III. 점검항목 3<br>
 ● 사용자 대상 중요 정보 업로드 금지 관련 정기 교육이 시행되어야한다.<br>
 &nbsp; ○ 중요 정보를 SaaS 환경에 업로드하지 않도록 정기적인 교육을 통해 사용자에게 인식을 제고해야 한다. 이를 통해 사용자는 민감 정보를 외부 SaaS 환경에 업로드하지 않는 것이 조직 내규 및 법적 규제를 준수하는 데 필수적임을 인지하게 된다.<br>

2.3.7 SaaS 內 업무 정보가 외부에 유출되지 않도록 보호대책을 적용하고 있는 지 여부<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-2fdn{border-color:#9b9b9b;text-align:left;vertical-align:top}
.tg .tg-pylf{background-color:#ddd3d3;border-color:#9b9b9b;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-pylf">항목</th>
    <th class="tg-2fdn">2.3.7 SaaS 내 업무 정보가 외부에 유출되지 않도록 보호대책을 적용하고 있는지 여부</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-pylf">인증기준</td>
    <td class="tg-2fdn">SaaS 내 민감 정보의 외부 유출을 방지하기 위해 암호화, 외부망 다운로드 차단, DLP 솔루션 등 보호대책이 적용되어야 함.</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="3">점검항목</td>
    <td class="tg-2fdn">1) SaaS 내 파일이 전송 중 및 저장 중에 AES-256 등 강력한 암호화로 보호되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">2) 외부망 다운로드가 차단되고, 네트워크 접근 제어가 적용되어 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">3) 민감 정보 전송 시 DLP 솔루션을 통한 모니터링 및 차단이 이루어지고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-pylf">관련 규제</td>
    <td class="tg-2fdn">ISO/IEC 27001 A.10.1, A.12.1</td>
  </tr>
</tbody>
</table>

▶ 점검항목 해설<br>
I. 점검항목 1 <br>
 ● SaaS 내 파일이 전송 중 및 저장 중에 AES-256 등 강력한 암호화로 보호되어야한다.<br>
 &nbsp; ○ 모든 파일이 SaaS 내에서 전송 중과 저장 중에 AES-256 같은 강력한 암호화 방식으로 보호되어야 한다. 예를 들어, 기밀 문서가 외부로 유출되더라도 암호화된 상태로 유지되어 접근이 불가능하도록 함으로써 데이터 보안을 유지할 수 있다.<br>
 
 II. 점검항목 2<br>
 ● 외부망 다운로드가 차단되고, 네트워크 접근 제어가 적용되어야한다.<br>
 &nbsp; ○ SaaS 시스템 내 민감한 정보의 외부망으로의 다운로드를 차단하는 보안 조치를 적용하여 데이터 유출 위험을 방지해야 한다. 예를 들어, VPN 없이 외부망으로의 연결이 불가능하도록 네트워크 접근 제어(NAC)를 통해 외부 접속을 제한할 수 있다.<br>
  
III. 점검항목 3<br>
 ● 민감 정보 전송 시 DLP 솔루션을 통한 모니터링 및 차단이 이루어져야한다.<br>
 &nbsp; ○ 민감 정보가 포함된 파일이 외부로 전송되거나 다운로드될 경우 DLP(Data Loss Prevention) 솔루션을 통해 이를 감지하고 자동 차단할 수 있어야 한다. 예를 들어, 내부 규정에 따라 특정 민감 데이터가 포함된 파일이 외부로 전송되면 이를 즉시 차단하고 사용자에게 경고하는 방식으로 정보 유출을 방지할 수 있다.<br>


2.3.8 SaaS와 연계된 제 3자 제공 앱 설치 시 관리자 승인 및 설치 내역의 기록·관리 여부<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-2fdn{border-color:#9b9b9b;text-align:left;vertical-align:top}
.tg .tg-pylf{background-color:#ddd3d3;border-color:#9b9b9b;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-pylf">항목</th>
    <th class="tg-2fdn">2.3.8 SaaS와 연계된 제3자 제공 앱 설치 시 관리자 승인 및 설치 내역의 기록 및 관리 여부</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-pylf">인증기준</td>
    <td class="tg-2fdn">SaaS와 연계된 제3자 앱 설치 시 사전 승인 절차와 설치 내역 기록 및 주기적인 모니터링 체계를 마련하여 보안성을 강화해야 함.</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="3">점검항목</td>
    <td class="tg-2fdn">1) 제3자 앱 설치 시 관리자 승인 절차가 마련되어 있는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">2) 모든 제3자 앱의 설치 내역이 기록 및 관리되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">3) 설치된 제3자 앱에 대한 정기적인 보안 검토가 이루어지고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-pylf">관련 규제</td>
    <td class="tg-2fdn">ISO/IEC 27001 A.12.1</td>
  </tr>
</tbody>
</table>

▶ 점검항목 해설<br>
I. 점검항목 1 <br>
 ● 제3자 앱 설치 시 관리자 승인 절차가 마련되어야 한다.<br>
 &nbsp; ○ SaaS와 연계된 제3자 앱을 설치할 때 관리자의 사전 승인을 받도록 하는 절차가 필요하다. 예를 들어, 사용자가 앱 설치 요청을 하면 관리자가 해당 앱의 보안성을 검토하고 승인하여 불필요한 보안 위험을 줄일 수 있다.<br>
 
 II. 점검항목 2<br>
 ● 모든 제3자 앱의 설치 내역이 기록 및 관리되어야한다.<br>
 &nbsp; ○ SaaS 환경에 설치되는 모든 제3자 앱의 설치 내역을 기록하여, 설치된 앱의 이름, 설치 날짜, 승인자 등의 정보를 주기적으로 검토하고 관리해야 한다. 예를 들어, 로그 관리 시스템을 통해 설치 내역을 중앙에서 관리하고, 미승인 앱이 설치되는 것을 방지하는 체계를 갖출 수 있다.<br>
  
III. 점검항목 3<br>
 ● 설치된 제3자 앱에 대한 정기적인 보안 검토가 이루어져야한다.<br>
 &nbsp; ○ SaaS와 연계된 제3자 앱에 대한 정기적인 보안 검토를 통해 보안 업데이트가 이루어지고, 문제가 있는 앱은 비활성화하거나 삭제할 수 있어야 한다. 예를 들어, 설치된 앱이 최신 보안 표준을 준수하는지 확인하여, 보안 위험을 줄이고 시스템의 안전성을 높일 수 있다.<br>

**2.4 SaaS 운영정책 보안대책**<br>
2.4.1 클라우드 서비스를 자산으로 식별하고, 서비스 특성에 맞게 분류항 관련 운영 절차에 따라 관리하고 있는지 여부<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-2fdn{border-color:#9b9b9b;text-align:left;vertical-align:top}
.tg .tg-pylf{background-color:#ddd3d3;border-color:#9b9b9b;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-pylf">항목</th>
    <th class="tg-2fdn">2.4.1 클라우드 서비스를 자산으로 식별하고, 서비스 특성에 맞게 분류하여 관련 운영절차에 따라 관리하고 있는지 여부</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-pylf">인증기준</td>
    <td class="tg-2fdn">클라우드 서비스의 자산 목록 작성, 분류, 변경 승인 절차 및 보안 요구사항 검토를 통해 체계적으로 자산을 관리하고 있어야 함.</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="3">점검항목</td>
    <td class="tg-2fdn">1) 클라우드 서비스 자산 목록이 작성되고 자산 관리 시스템(AMS)을 통해 관리되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">2) 서비스 특성에 따라 자산 분류 및 관리 주체가 명확히 지정되어 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">3) 자산 변경 시 승인 프로세스가 적용되고, 변경 내역이 기록되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-pylf">관련 규제</td>
    <td class="tg-2fdn">ISO/IEC 27001 A.8.1.1, A.8.1.2, A.14.2.2</td>
  </tr>
</tbody>
</table>

▶ 점검항목 해설<br>
I. 점검항목 1 <br>
 ● 클라우드 서비스 자산 목록이 작성되고 자산 관리 시스템(AMS)을 통해 관리되어야한다.<br>
 &nbsp; ○ 클라우드 서비스 내 자산 목록을 체계적으로 작성하여 서비스 유형, 소유자, 데이터 중요도 등을 관리해야 한다. 예를 들어, 클라우드 관리 플랫폼(CMP)을 통해 자동으로 자산을 식별하고 자산 관리 시스템(AMS)에 업데이트하여 실시간으로 자산 목록을 유지할 수 있다.<br>
 
 II. 점검항목 2<br>
 ● 서비스 특성에 따라 자산 분류 및 관리 주체가 명확히 지정되어야한다.<br>
 &nbsp; ○ 각 클라우드 서비스의 특성에 맞게 자산을 분류하고 관리 책임자를 지정해야 한다. 예를 들어, AWS IAM(Identity and Access Management)을 통해 자산별로 적절한 관리 권한을 할당하여 클라우드 자산을 안전하게 관리할 수 있다.<br>
  
III. 점검항목 3<br>
 ● 자산 변경 시 승인 프로세스가 적용되고, 변경 내역이 기록되어야한다.<br>
 &nbsp; ○ 클라우드 자산의 변경 요청이 발생할 때마다 승인 프로세스를 거쳐 보안 검토를 수행해야 한다. 예를 들어, JIRA 또는 ServiceNow 같은 시스템 변경 관리 도구를 통해 변경 요청을 기록하고 승인 절차를 거쳐 모든 변경이 추적 가능하게 관리될 수 있다.<br>

2.4.2 가명정보 처리 시 추가정보를 삭제 또는 가명정보와 분리 보존하는 지 여부<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-2fdn{border-color:#9b9b9b;text-align:left;vertical-align:top}
.tg .tg-pylf{background-color:#ddd3d3;border-color:#9b9b9b;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-pylf">항목</th>
    <th class="tg-2fdn">2.4.2 가명정보 처리 시 추가정보를 삭제 또는 가명정보와 분리 보존하는지 여부</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-pylf">인증기준</td>
    <td class="tg-2fdn">가명정보와 추가 정보를 안전하게 삭제하거나 분리하여 보관함으로써 개인정보 보호를 강화해야 함.</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="4">점검항목</td>
    <td class="tg-2fdn">1) 가명정보 처리 시 추가 식별 정보를 삭제하는 절차가 마련되어 있는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">2) 가명정보와 추가 정보가 물리적 또는 논리적으로 분리 저장되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">3) AES-256 등 강력한 암호화 알고리즘을 통해 가명정보가 보호되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">4) 재식별 방지를 위한 접근 통제 및 최소 권한 원칙이 적용되어 있는가?</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="2">관련 규제</td>
    <td class="tg-2fdn">개인정보 보호법 제24조의2</td>
  </tr>
  <tr>
    <td class="tg-0lax">ISO/IEC 27001 A.18.1.4</td>
  </tr>
</tbody>
</table>

▶ 점검항목 해설<br>
I. 점검항목 1 <br>
 ● 가명정보 처리 시 추가 식별 정보를 삭제하는 절차가 마련되어야한다.<br>
 &nbsp; ○ 가명정보 처리 시스템에서 처리 완료 후 불필요한 식별 정보를 안전하게 삭제해야 한다. 예를 들어, NoSQL 데이터베이스에 저장된 민감 데이터를 완전 삭제할 때 "shred" 명령어와 같은 물리적 삭제 기술을 통해 잔여 데이터를 확실히 삭제할 수 있다.<br>
 
 II. 점검항목 2<br>
 ● 가명정보와 추가 정보가 물리적 또는 논리적으로 분리 저장되어야한다.<br>
 &nbsp; ○ 가명정보와 이를 재식별할 수 있는 추가 정보는 서로 분리된 스토리지 또는 물리적 장치에 저장하여 보안을 강화해야 한다. 예를 들어, AWS KMS(Key Management Service)를 이용해 추가 정보를 암호화한 후 다른 스토리지에 분리 저장함으로써 물리적 분리 보안을 구현할 수 있다.<br>
  
III. 점검항목 3<br>
 ● AES-256 등 강력한 암호화 알고리즘을 통해 가명정보가 보호되어야한다.<br>
 &nbsp; ○ 가명정보는 AES-256 같은 고강도 암호화 알고리즘으로 보호되어야 하며, 암호화 키는 별도의 키 관리 시스템(KMS)을 통해 관리되어야 한다. 예를 들어, SQL Server의 TDE(Transparent Data Encryption) 기능을 활용해 저장된 데이터가 암호화된 상태로 유지되도록 관리할 수 있다.<br>
 
IV. 점검항목 4<br>
 ● 재식별 방지를 위한 접근 통제 및 최소 권한 원칙이 적용되어야한다.<br>
 &nbsp; ○ 가명정보에 접근하는 사용자에 대해 최소 권한 원칙을 적용하고, 엄격한 인증 절차를 통해 재식별을 방지해야 한다. 예를 들어, MFA(다중 인증)를 적용하여 특정 사용자의 가명정보 접근을 제한하고, 모든 접근 내역을 SIEM 시스템을 통해 실시간으로 모니터링하는 방식으로 재식별 방지 효과를 높일 수 있다.<br>

2.4.3 SaaS 이용방법 등에 대한 안내서를 마련하고, 직원 누구나 이를 열람할 수 있도록 사내 인트라넷 등에 게시하고 있는지 여부<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-2fdn{border-color:#9b9b9b;text-align:left;vertical-align:top}
.tg .tg-pylf{background-color:#ddd3d3;border-color:#9b9b9b;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-pylf">항목</th>
    <th class="tg-2fdn">2.4.3 SaaS 이용 방법(제3자 제공 앱 설치 포함)에 대한 안내서를 마련하고, 직원 누구나 이를 열람할 수 있도록 사내 인트라넷 등에 게시하고 있는지 여부2.</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-pylf">인증기준</td>
    <td class="tg-2fdn">SaaS 이용 가이드와 제3자 앱 설치 가이드를 작성하여 사내 인트라넷에 게시하고, 이를 최신 상태로 유지하여 모든 직원이 접근할 수 있도록 해야 한다.</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="4">점검항목</td>
    <td class="tg-2fdn">1) 최신 SaaS 이용 가이드가 사내 인트라넷에 게시되고, 필요 시 알림으로 공지되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">2) 제3자 제공 앱 설치 가이드가 작성되어 직원에게 위험을 알리고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">3) 가이드가 주기적으로 업데이트되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">4) 사용자 피드백이 반영되어 가이드가 개선되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-pylf">관련 규제</td>
    <td class="tg-2fdn">ISO/IEC 27001 A.7.2.2, A.12.1.1</td>
  </tr>
</tbody>
</table>

▶ 점검항목 해설<br>
I. 점검항목 1 <br>
 ● 최신 SaaS 이용 가이드가 사내 인트라넷에 게시되고, 필요 시 알림으로 공지되어야한다.<br>
 &nbsp; ○ SaaS 이용 가이드를 인트라넷에 게시하여 모든 직원이 접근할 수 있어야 하며, 중요 변경 사항이 있을 때는 알림 기능을 통해 직원들에게 즉시 공지해야 한다. 예를 들어, 보안 위협이 새롭게 발견되면 해당 내용을 포함한 업데이트 사항을 전 직원에게 알림으로 전달할 수 있다.<br>
 
 II. 점검항목 2<br>
 ● 제3자 제공 앱 설치 가이드가 작성되어 직원에게 위험을 알려야한다.<br>
 &nbsp; ○ 제 3자 제공 앱 설치 시 발생할 수 있는 보안 위험을 명확히 알리는 가이드를 작성하여 사용자가 설치 전에 이를 숙지하도록 해야 한다. 예를 들어, Cloud Security Posture Management(CSPM) 도구를 사용해 실시간으로 앱의 보안 위험을 분석하고, 이를 가이드에 반영함으로써 직원들이 앱 설치 시 사전 주의를 기울이도록 한다.<br>
  
III. 점검항목 3<br>
 ● 가이드가 주기적으로 업데이트 되어야한다.<br>
 &nbsp; ○ SaaS 이용 가이드와 설치 가이드는 최신 보안 이슈를 반영해 정기적으로 업데이트되어야 한다. 예를 들어, AWS Security Hub나 Azure Security Center 등을 통해 모니터링한 취약점이 발견되면 가이드에 반영하여 직원들이 최신 정보를 기반으로 SaaS를 이용할 수 있도록 해야 한다.<br>
 
IV. 점검항목 4<br>
 ● 사용자 피드백이 반영되어 가이드가 개선되어야한다.<br>
 &nbsp; ○ SaaS 이용 중 발생한 보안 이슈나 개선 요청을 수집하여 가이드에 반영함으로써 실질적인 개선이 이루어지도록 해야 한다. 예를 들어, 정기 설문조사를 통해 수집된 피드백을 반영하여, 사용자 경험을 향상시키고 SaaS 가이드의 실효성을 높일 수 있다.<br>

2.4.4 SaaS 사용자 및 관리자를 대상으로 SaaS 이용 절차, SaaS 보안 설정 등에 대해 정기·수시 교육을 실시하는 지 여부<br>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-2fdn{border-color:#9b9b9b;text-align:left;vertical-align:top}
.tg .tg-pylf{background-color:#ddd3d3;border-color:#9b9b9b;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-pylf">항목</th>
    <th class="tg-2fdn">2.4.4 SaaS 사용자 및 관리자를 대상으로 SaaS 이용 절차, SaaS 보안 설정 등에 대해 정기·수시 교육을 실시하는지 여부</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-pylf">인증기준</td>
    <td class="tg-2fdn">SaaS 사용자와 관리자를 위한 정기·수시 보안 교육을 제공하고, 이를 체계적으로 관리하여 보안 의식을 강화해야 한다.</td>
  </tr>
  <tr>
    <td class="tg-pylf" rowspan="4">점검항목</td>
    <td class="tg-2fdn">1) SaaS 이용 절차와 보안 설정에 대한 정기 교육이 실시되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-2fdn">2) 사용자의 역할에 따라 맞춤형 교육이 제공되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">3) 모든 교육 이수 내역이 기록되고 관리되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-0lax">4) 신규 SaaS 도입 시 별도의 교육이 제공되고 있는가?</td>
  </tr>
  <tr>
    <td class="tg-pylf">관련 규제</td>
    <td class="tg-2fdn">ISO/IEC 27001 A.7.2.1, A.12.6.2</td>
  </tr>
</tbody>
</table>

▶ 점검항목 해설<br>
I. 점검항목 1 <br>
 ● SaaS 이용 절차와 보안 설정에 대한 정기 교육이 실시되어야한다.<br>
 &nbsp; ○ SaaS 사용자와 관리자를 대상으로 보안 교육을 정기적으로 실시하여 SaaS 사용에 대한 기본 절차와 보안 설정에 대한 인식을 높여야 한다. 예를 들어, Learning Management System(LMS)를 통해 정기적인 보안 교육을 제공하여 모든 직원이 최신 보안 방안을 숙지하도록 할 수 있다.<br>
 
 II. 점검항목 2<br>
 ● 사용자의 역할에 따라 맞춤형 교육이 제공되어야한다.<br>
 &nbsp; ○ SaaS 관리자는 기술적인 보안 설정 교육을, 일반 사용자는 SaaS의 보안 사용법 교육을 받도록 역할에 맞춘 맞춤형 교육이 필요하다. 예를 들어, SaaS 관리자에게는 보안 설정과 데이터 보호 방법에 대한 교육을 제공하고, 일반 직원에게는 SaaS 보안 사용 지침을 교육하여 업무에 필요한 보안 지식을 제공할 수 있다.<br>
  
III. 점검항목 3<br>
 ● 모든 교육 이수 내역이 기록되고 관리되어야한다.<br>
 &nbsp; ○ 모든 교육 이수 기록을 LMS 시스템과 연동하여 자동으로 기록하고 관리함으로써 규제 기관의 요구사항에 대응해야 한다. 예를 들어, 교육을 완료한 직원에게는 자동으로 이수증을 발급하고, 미이수자에게는 추가 교육 안내가 전달될 수 있다.<br>
 
IV. 점검항목 4<br>
 ● 신규 SaaS 도입 시 별도의 교육이 제공되어야한다.<br>
 &nbsp; ○ 새로운 SaaS가 도입되면 이에 대한 교육을 별도로 제공하여 직원들이 새로운 시스템을 안전하게 사용할 수 있도록 해야 한다. 예를 들어, 새로운 SaaS가 도입될 때마다 해당 SaaS의 보안 설정과 사용법에 대한 교육 세션을 개최하고, 이를 통해 안전한 사용을 장려할 수 있다.<br>
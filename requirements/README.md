<table>
  <tr><th colspan="2">RQ_BCK_MENU_XX</th></tr>
  <tr><td>RQ_BCK_MENU_01</td><td>Any created or uploaded project shall be saved in real time.</td></tr>
  <tr><td>RQ_BCK_MENU_02</td><td>A saved project shall include all elements related to the item definition and the TARA.</td></tr>

  <tr><th colspan="2">RQ_BCK_ITDEF_XX</th></tr>
  <tr><td>RQ_BCK_ITDEF_01</td><td>The item definition shall be unique per project.</td></tr>
  <tr><td>RQ_BCK_ITDEF_02</td><td>The item definition shall be defined by the following elements:<br>• The components (basic, composite, or user-created) present in the drawing area.<br>• The connections between components.<br>• The non-visual information.</td></tr>
  <tr><td>RQ_BCK_ITDEF_03</td><td>All elements mentioned in RQ_BCK_ITDEF_02 shall be definable as assets for the TARA.</td></tr>
  <tr><td>RQ_BCK_ITDEF_04</td><td>A basic component shall be a drawable element without logical or hardware functionality.</td></tr>
  <tr><td>RQ_BCK_ITDEF_05</td><td>A basic component shall be nameable, connectable and able to store data.</td></tr>
  <tr><td>RQ_BCK_ITDEF_06</td><td>Data storage shall be characterized by a time parameter.<br><i>Note: This allows defining a transiting data or the type of memory to be created.</i></td></tr>
  <tr><td>RQ_BCK_ITDEF_07</td><td>A composite shall be built from basic components which are customizable according to RQ_BCK_ITDEF_04 and RQ_BCK_ITDEF_05.</td></tr>
  <tr><td>RQ_BCK_ITDEF_08</td><td>A composite shall be saved in a composite library.</td></tr>
  <tr><td>RQ_BCK_ITDEF_09</td><td>All elements mentioned in RQ_BCK_ITDEF_02 shall be associated with a TARA asset.</td></tr>

  <tr><th colspan="2">RQ_BCK_TARA_XX</th></tr>
  <tr><td>RQ_BCK_TARA_01</td><td>Each element of the TARA (asset, damage scenario, threat scenario, attack path) shall be referenceable using its attributes.</td></tr>
  <tr><td>RQ_BCK_TARA_02</td><td>Each element of the TARA (asset, damage scenario, threat scenario, attack path) shall be saved in a corresponding list (assets list, damage scenarios list, etc).</td></tr>

  <tr><th colspan="2">RQ_BCK_AS_XX</th></tr>
  <tr><td>RQ_BCK_AS_01</td><td>An asset shall include the following attributes:<br>• ID, <br>• Name, <br>• Priority, <br>• Confidentiality, <br>• Integrity, <br>• Availability, <br>• Authenticity, <br>• Non-repudiation, <br>• Item Definition Component, <br>• Threat Scenarios, <br>• Damage Scenarios, <br>• Cybersecurity Controls.</td></tr>
  <tr><td>RQ_BCK_AS_02</td><td>An asset shall be initialized with at least an ID and a name.</td></tr>

  <tr><th colspan="2">RQ_BCK_TS_XX</th></tr>
  <tr><td>RQ_BCK_TS_01</td><td>A threat scenario shall include the following attributes:<br>• ID, <br>• Description, <br>• Affected Assets, <br>• Compromised Cybersecurity Properties, <br>• Related Damage Scenarios, <br>• Attack Paths, <br>• Risk Values, <br>• Treatments.</td></tr>
  <tr><td>RQ_BCK_TS_02</td><td>A threat scenario shall be initialized with at least an ID and a description.</td></tr>

  <tr><th colspan="2">RQ_BCK_DS_XX</th></tr>
  <tr><td>RQ_BCK_DS_01</td><td>A damage scenario shall have the following attributes: <br>• ID, <br>• Description, <br>• Assets, <br>• Threat Scenarios <br>• Various impact ratings (Safety, Financial, Operational, Privacy).</td></tr>
  <tr><td>RQ_BCK_DS_02</td><td>A damage scenario shall be initialized with at least an ID and a description.</td></tr>

  <tr><th colspan="2">RQ_BCK_IR_XX</th></tr>
  <tr><td>RQ_BCK_IR_01</td><td>The impact rating of a damage scenario shall be assigned a single value among the following:<br>•  Severe<br>•  Major<br>•  Moderate<br>•  Negligible</td></tr>
  <tr><td>RQ_BCK_IR_02</td><td>The criteria for safety impact shall be defined as follows:<br>• <b>Severe:</b> Life-threatening injuries (survival uncertain), fatal injuries.<br>• <b>Major:</b> Severe and life-threatening injuries (survival probable).<br>• <b>Moderate:</b> Light and moderate injuries.<br>• <b>Negligible:</b> No injuries.</td></tr>
  <tr><td>RQ_BCK_IR_03</td><td>The criteria for financial impact shall be defined as follows:<br>• <b>Severe:</b> Catastrophic financial consequences.<br>• <b>Major:</b> Substantial financial consequences.<br>• <b>Moderate:</b> Inconvenient financial consequences with limited resources.<br>• <b>Negligible:</b> No or negligible financial effect.</td></tr>
  <tr><td>RQ_BCK_IR_04</td><td>The criteria for operational impact shall be defined as follows:<br>• <b>Severe:</b> Loss or impairment of a core vehicle function.<br>• <b>Major:</b> Loss or impairment of an important function.<br>• <b>Moderate:</b> Partial degradation of a function.<br>• <b>Negligible:</b> No or imperceptible impairment.</td></tr>
  <tr><td>RQ_BCK_IR_05</td><td>The criteria for privacy impact shall be defined as follows:<br>• <b>Severe:</b> Significant/irreversible impact. Highly sensitive and linkable to PII.<br>• <b>Major:</b> Serious impact, either:<br>&nbsp;&nbsp;a) highly sensitive, hard to link; or<br>&nbsp;&nbsp;b) sensitive, easy to link.<br>• <b>Moderate:</b> Inconvenient impact, either:<br>&nbsp;&nbsp;a) sensitive, hard to link; or<br>&nbsp;&nbsp;b) not sensitive, easy to link.<br>• <b>Negligible:</b> No/negligible impact. Not sensitive and hard to link.</td></tr>

  <tr><th colspan="2">RQ_BCK_AP_XX</th></tr>
  <tr><td>RQ_BCK_AP_01</td><td>An attack path shall have the following attributes:<br>• ID<br>• Attack steps<br>• Threat scenario<br>•  Elapsed time<br>•  Specialist expertise<br>•  Knowledge of the item or the component<br>•  Window of opportunity<br>•  Equipment<br>•  Attack feasibility value<br>•  Attack feasibility rating<br>•  Residual elapsed time<br>•  Residual specialist expertise<br>•  Residual knowledge<br>•  Residual window of opportunity<br>•  Residual equipment<br>•  Residual attack feasibility value<br>•  Residual attack feasibility rating</td></tr>
  <tr><td>RQ_BCK_AP_2</td><td>An attack step shall be associated with one attack path.</td></tr>
  <tr><td>RQ_BCK_AP_03</td><td>An attack step shall have the following attributes:<br>• ID<br>• Description<br>• Associated attack path</td></tr>
  <tr><td>RQ_BCK_AP_04</td><td>An attack step shall be initialized with all its attributes.</td></tr>
  <tr><td>RQ_BCK_AP_05</td><td>An attack path shall be initialized with at least an ID and one attack step.</td></tr>

  <tr><th colspan="2">RQ_BCK_AF_XX</th></tr>
  <tr><td>RQ_BCK_AF_01</td><td>The attack feasibility rating of an attack path shall be assigned a single value among the following:<br>• High<br>• Medium<br>• Low<br>• Very low</td></tr>
  <tr><td>RQ_BCK_AF_02</td><td>The attack feasibility shall be determined using an attack potential-based approach.</td></tr>
  <tr><td>RQ_BCK_AF_03</td><td>The attack potential-based approach shall rely on five core parameters:<br>• Elapsed time<br>• Specialist expertise<br>• Knowledge of the item or component<br>• Window of opportunity<br>• Equipment</td></tr>
  <tr><td>RQ_BCK_AF_04</td><td>Criteria and values for elapsed time:<br>(0) ≤1 day<br>(1) ≤1 week<br>(4) ≤1 month<br>(17) ≤6 months<br>(19) >6 months</td></tr>
  <tr><td>RQ_BCK_AF_05</td><td>Criteria and values for specialist expertise:<br>(0) Layman<br>(3) Proficient<br>(6) Expert<br>(8) Multiple experts</td></tr>
  <tr><td>RQ_BCK_AF_06</td><td>Criteria and values for knowledge of the item/component:<br>(0) Public information<br>(3) Restricted information<br>(7) Confidential information<br>(11) Strictly confidential information</td></tr>
  <tr><td>RQ_BCK_AF_07</td><td>Criteria and values for window of opportunity:<br>(0) Unlimited<br>(1) Easy<br>(4) Moderate<br>(10) Difficult</td></tr>
  <tr><td>RQ_BCK_AF_08</td><td>Criteria and values for equipment:<br>(0) Standard<br>(4) Specialized<br>(7) Bespoke<br>(9) Multiple bespoke</td></tr>
  <tr><td>RQ_BCK_AF_09</td><td>The attack potential shall correspond to the addition of all parameters.</td></tr>
  <tr><td>RQ_BCK_AF_10</td><td>Attack feasibility rating based on attack potential:<br><b>High:</b> 0–13<br><b>Medium:</b> 14–19<br><b>Low:</b> 20–24<br><b>Very Low:</b> ≥25</td></tr>

  <tr><th colspan="2">RQ_BCK_RD_XX</th></tr>
  <tr><td>RQ_BCK_RD_01</td><td>For each threat scenario, the risk value shall be determined from:<br>• Impact of the associated damage scenarios<br>• Attack feasibility of the associated attack paths<br><br><i>Note 1: If multiple damage scenarios or multiple impact categories exist, determine separate risk values.</i><br><i>Note 2: If multiple attack paths exist, assign the maximum attack feasibility rating.</i></td></tr>
  <tr><td>RQ_BCK_RD_02</td><td>The risk value of a threat scenario shall be a value between 1 and 5, where 1 represents minimal risk.</td></tr>
  <tr><td>RQ_BCK_RD_03
  </td><td>
  The method for risk value determination shall be based on the following risk matrix: <br><br> 
    <table border="1" cellspacing="0" cellpadding="5" style="border-collapse: collapse; text-align: center;">
      <thead>
        <tr>
          <th rowspan="2">Impact rating</th>
          <th colspan="4">Attack feasibility rating</th>
        </tr>
        <tr>
          <th>Very Low</th>
          <th>Low</th>
          <th>Medium</th>
          <th>High</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Severe</td>
          <td><b>2</b></td>
          <td><b>3</b></td>
          <td><b>4</b></td>
          <td><b>5</b></td>
        </tr>
        <tr>
          <td>Major</td>
          <td>1</td>
          <td>2</td>
          <td>3</td>
          <td>4</td>
        </tr>
        <tr>
          <td>Moderate</td>
          <td>1</td>
          <td>2</td>
          <td>2</td>
          <td>3</td>
        </tr>
        <tr>
          <td>Negligible</td>
          <td>1</td>
          <td>1</td>
          <td>1</td>
          <td>1</td>
        </tr>
      </tbody>
    </table>
  </td></tr>

  <tr><th colspan="2">RQ_BCK_RT_XX</th></tr>
  <tr><td>RQ_BCK_RT_01</td><td>For each threat scenario, considering its risk values, one or more of the following risk treatment option(s) shall be determined:<br>• Avoiding risk<br>• Reducing risk<br>• Sharing risk<br>• Retaining risk</td></tr>

  <tr><th colspan="2">RQ_BCK_CC_XX</th></tr>
  <tr><td>RQ_BCK_CC_01</td><td>When the risk treatment option of a threat scenario is reducing the risk, one or more cybersecurity controls shall be applied to the concerned asset(s).</td></tr>
  <tr><td>RQ_BCK_CC_02</td><td>When at least one cybersecurity control is applied to an asset, a residual attack feasibility rating shall be assigned to every affected attack path.</td></tr>

  <tr><th colspan="2">RQ_BCK_RR_XX</th></tr>
  <tr><td>RQ_BCK_RR_01</td><td>When an attack path has two attack feasibility ratings, each related threat scenario shall be assigned a residual risk value for every associated damage scenario and impacted categories.</td></tr>
</table>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Description</th>
    </tr>
  </thead>
    <tr><th colspan="2">RQ_FRT_COVER_XX</th></tr> 
    <tr><td>RQ_FRT_COVER_01</td><td>The cover’s background shall comply with the hexadecimal color #14142B.</td></tr>
    <tr><td>RQ_FRT_COVER_02</td><td>The cover shall display the software name in the Zen Tokyo Zoo font.</td></tr>
    <tr><td>RQ_FRT_COVER_03</td><td>The software name shall comply with a color gradient composed from #B28DFF to #A8C7FA.</td></tr>
    <tr><td>RQ_FRT_COVER_04</td><td>The cover shall display the software slogan in the software’s primary font.</td></tr>
    <tr><td>RQ_FRT_COVER_05</td><td>The software slogan shall comply with the hexadecimal color #D4E4FF.</td></tr>
    <tr><td>RQ_FRT_COVER_06</td><td>The font size of the title shall be 7.5 times the slogan's font size, maintaining visual hierarchy.</td></tr>
    <tr><td>RQ_FRO_COVER_07</td><td>The cover shall include a button that prompts the user to click it to load the main menu.</td></tr>
    <tr><td>RQ_FRT_COVER_08</td><td>The button text shall have the same font size as the slogan.</td></tr>
    <tr><td>RQ_FRT_COVER_09</td><td>The button size shall be centered around the text, with appropriate padding.</td></tr>
    <tr><td>RQ_FRT_COVER_10</td><td>The color button shall comply with a color gradient composed from #B28DFF to #A8C7FA.</td></tr>
    <tr><td>RQ_FRT_COVER_11</td><td>The text button color comply with the hexadecimal color #D4E4FF.</td></tr>
    <tr><td>RQ_FRT_COVER_12</td><td>The software name, slogan, and button shall be vertically aligned and centrally positioned within the cover.</td></tr>
    <tr><th colspan="2">RQ_FRT_VPANEL_XX</th></tr> 
    <tr><td>RQ_FRT_VPANEL_01</td><td></td></tr>
    <tr><th colspan="2">RQ_FRT_HPANEL_XX</th></tr>
    <tr><td>RQ_FRT_HPANEL_01</td><td></td></tr>
    <tr><th colspan="2">RQ_FRT_TBAR_XX</th></tr>
    <tr><td>RQ_FRT_TBAR_01</td><td></td></tr>
    <tr><th colspan="2">RQ_FRT_MENU_XX</th></tr>
    <tr><td>RQ_FRT_MENU_01</td><td></td></tr>
    <tr><th colspan="2">RQ_FRT_ITDEF_XX</th></tr>
    <tr><td>RQ_FRT_ITDEF_01</td><td></td></tr>
    <tr><th colspan="2">RQ_FRT_AS_XX</th></tr>
    <tr><td>RQ_FRT_AS_01</td><td></td></tr>
    <tr><th colspan="2">RQ_FRT_TS_XX</th></tr>
    <tr><td>RQ_FRT_TS_01</td><td></td></tr>
    <tr><th colspan="2">RQ_FRT_DS_XX</th></tr>
    <tr><td>RQ_FRT_DS_01</td><td></td></tr>
    <tr><th colspan="2">RQ_FRT_IR_XX</th></tr>
    <tr><td>RQ_FRT_IR_01</td><td></td></tr>
    <tr><th colspan="2">RQ_FRT_AP_XX</th></tr>
    <tr><td>RQ_FRT_AP_01</td><td></td></tr>
    <tr><th colspan="2">RQ_FRT_AF_XX</th></tr>
    <tr><td>RQ_FRT_AF_01</td><td></td></tr>
    <tr><th colspan="2">RQ_FRT_RD_XX</th></tr>
    <tr><td>RQ_FRT_RD_01</td><td></td></tr>
    <tr><th colspan="2">RQ_FRT_RT_XX</th></tr>
    <tr><td>RQ_FRT_RT_01</td><td></td></tr>
    <tr><th colspan="2">RQ_FRT_MIT_XX</th></tr>
    <tr><td>RQ_FRT_MIT_01</td><td></td></tr>
    <tr><th colspan="2">RQ_FRT_RR_XX</th></tr>
    <tr><td>RQ_FRT_RR_01</td><td></td></tr>
</table>
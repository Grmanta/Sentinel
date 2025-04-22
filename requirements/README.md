## Back-End requirements

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
  <tr><td>RQ_BCK_ITDEF_06</td><td>Data storage shall be characterized by a time parameter.<br><br>Note: This allows defining a transiting data or the type of memory.</td></tr>
  <tr><td>RQ_BCK_ITDEF_07</td><td>A composite shall be built from basic components which are customizable according to RQ_BCK_ITDEF_04 and RQ_BCK_ITDEF_05.</td></tr>
  <tr><td>RQ_BCK_ITDEF_08</td><td>A composite shall be saved in a composite library.</td></tr>
  <tr><td>RQ_BCK_ITDEF_09</td><td>All elements mentioned in RQ_BCK_ITDEF_02 shall be associated with a TARA asset.</td></tr>

  <tr><th colspan="2">RQ_BCK_TARA_XX</th></tr>
  <tr><td>RQ_BCK_TARA_01</td><td>Each element of the TARA (asset, damage scenario, threat scenario, attack path) shall be referenceable using its attributes.</td></tr>
  <tr><td>RQ_BCK_TARA_02</td><td>Each element of the TARA (asset, damage scenario, threat scenario, attack path) shall be saved in a corresponding list (assets list, damage scenarios list, etc).</td></tr>

  <tr><th colspan="2">RQ_BCK_AS_XX</th></tr>
  <tr><td>RQ_BCK_AS_01</td><td>An asset shall include the following attributes:
  <br>• ID: Unique identifier of the asset.
  <br>• Name: Descriptive name of the asset.
  <br>• Priority: Importance level of the asset.
  <br>• Confidentiality: Either the asset is concerned or not.
  <br>• Integrity: Either the asset is concerned or not.
  <br>• Availability: Either the asset is concerned or not.
  <br>• Authenticity: Either the asset is concerned or not.
  <br>• Non-repudiation: Either the asset is concerned or not.
  <br>• Item Definition Component: The system component to which the asset belongs.
  <br>• Threat Scenarios: The potential cause of a damage scenario.
  <br>• Damage Scenarios: The potential consequences resulting from the threat scenario.
  <br>• Cybersecurity Controls: Security measures applied to protect the asset.</td></tr>
  <tr><td>RQ_BCK_AS_02</td><td>An asset shall be initialized with at least an ID and a name.</td></tr>

  <tr><th colspan="2">RQ_BCK_TS_XX</th></tr>
  <tr><td>RQ_BCK_TS_01</td><td>A threat scenario shall include the following attributes:
  <br>• ID: Unique identifier of the threat scenario.
  <br>• Description: Detailed explanation of the threat scenario.
  <br>• Assets: The assets affected by the threat.
  <br>• Compromised Cybersecurity Properties: The impacted security properties.
  <br>• Damage Scenarios: The potential consequences resulting from the threat scenario.
  <br>• Attack Paths: The possible attack vectors used to exploit the threat.
  <br>• Risk Values and Treatments: The assessed risk levels and corresponding treatment strategies. </td></tr>
  <tr><td>RQ_BCK_TS_02</td><td>A threat scenario shall be initialized with at least an ID and a description.</td></tr>

  <tr><th colspan="2">RQ_BCK_DS_XX</th></tr>
  <tr><td>RQ_BCK_DS_01</td><td>A damage scenario shall have the following attributes:
  <br>• ID: Unique identifier of the damage scenario.
  <br>• Description: Detailed explanation of the damage scenario.
  <br>• Assets: The assets affected the damage.
  <br>• Threat Scenarios: The potential cause of a damage scenario.
  <br>• Safety impact: Rating of the safety impact.
  <br>• Safety residual impact: Rating of the safety residual impact.
  <br>• Financial impact: Rating of the financial impact.
  <br>• Financial residual  impact: Rating of the financial residual impact.
  <br>• Operational impact: Rating of the operational impact.
  <br>• Operational residual impact: Rating of the operational residual impact.
  <br>• Privacy impact: Rating of the privacy impact.
  <br>• Privacy residual impact: Rating of the privacy residual impact. </td></tr>
  <tr><td>RQ_BCK_DS_02</td><td>A damage scenario shall be initialized with at least an ID and a description.</td></tr>

  <tr><th colspan="2">RQ_BCK_IR_XX</th></tr>
  <tr><td>RQ_BCK_IR_01</td><td>The impact rating of a damage scenario shall be assigned a single value among the following:<br>•  Severe<br>•  Major<br>•  Moderate<br>•  Negligible</td></tr>
  <tr><td>RQ_BCK_IR_02</td><td>The criteria for safety impact shall be defined as follows:<br>• Severe:</b> Life-threatening injuries (survival uncertain), fatal injuries.<br>• Major:</b> Severe and life-threatening injuries (survival probable).<br>• Moderate:</b> Light and moderate injuries.<br>• Negligible:</b> No injuries.</td></tr>
  <tr><td>RQ_BCK_IR_03</td><td>The criteria for financial impact shall be defined as follows:
  <br>• Severe:</b> The financial damage leads to catastrophic consequences which the affected road user might not overcome.
  <br>• Major:</b> The financial damage leads to substantial consequences which the affected road user will be able to overcome.
  <br>• Moderate:</b> The financial damage leads to inconvenient consequences which the affected road user will be able to overcome with limited resources.
  <br>• Negligible:</b> The financial damage leads to no effect, negligible consequences or is irrelevant to the road user.</td></tr>
  <tr><td>RQ_BCK_IR_04</td><td>The criteria for operational impact shall be defined as follows:
  <br>• Severe:</b> The operational damage leads to the loss or impairment of a core vehicle function.
  <br>• Major:</b> The operational damage leads to the loss or impairment of an important vehicle function.
  <br>• Moderate:</b> The operational damage leads to partial degradation of a vehicle function.
  <br>• Negligible:</b> The operational damage leads to no impairment or non-perceivable impairment of a vehicle function.</td></tr>
  <tr><td>RQ_BCK_IR_05</td><td>The criteria for privacy impact shall be defined as follows:
  <br>• Severe:</b> The privacy damage leads to significant or even irreversible impact to the road user. The information regarding the road user is highly sensitive and easy to link to a PII principal
  <br>• Major:</b> The privacy damage leads to serious impact to the road user. The information regarding the road user is:<br>&nbsp;&nbsp;a) highly sensitive and difficult to link to a PII    
     principal; or<br>&nbsp;&nbsp;b) sensitive and easy to link to a PII principal.
  <br>• Moderate:</b> The privacy damage leads to inconvenient consequences to the road user. The information regarding the road user is:<br>&nbsp;&nbsp;a) sensitive but difficult to link to a PII principal; or<br>&nbsp;&nbsp;b) not sensitive but easy to link to a PII principal.
  <br>• Negligible:</b> The privacy damage leads to no effect or, negligible consequences or is irrelevant to the road user. The information regarding the road user is not sensitive and difficult to link to a PII principal.</td></tr>

  <tr><th colspan="2">RQ_BCK_AP_XX</th></tr>
  <tr><td>RQ_BCK_AP_01</td><td>An attack path shall have the following attributes:
  <br>• ID: Unique identifier of the damage scenario.
  <br>• Attack steps: Different ways in which a threat scenario could be realized.
  <br>• Threat scenario: The potential cause of a damage scenario.
  <br>•  Elapsed time: Time to identify a vulnerability and develop and (successfully) apply an exploit.
  <br>•  Specialist expertise: Capabilities of the attacker, relative to their skill and experience
  <br>•  Knowledge of the item: Amount of information the attacker has acquired about the item or component.
  <br>•  Window of opportunity: Access conditions (time, type) to successfully perform an attack.
  <br>•  Equipment: Tools the attacker has available to discover the vulnerability and/or to execute the attack.
  <br>•  Attack feasibility value: Addition of all parameter values.
  <br>•  Attack feasibility rating: Rating corresponding to the attack feasibility value.
  <br>•  Residual elapsed time: New time to identify a vulnerability and develop and (successfully) apply an exploit.
  <br>•  Residual specialist expertise: New required capabilities of the attacker, relative to their skill and experience.
  <br>•  Residual knowledge: New amount of information the attacker has acquired about the item or component.
  <br>•  Residual window of opportunity: New access conditions (time, type) to successfully perform an attack.
  <br>•  Residual equipment: Additional tools the attacker has available to discover the vulnerability and/or to execute the attack.
  <br>•  Residual attack feasibility value:  Addition of all residual parameter values.
  <br>•  Residual attack feasibility rating: Rating corresponding to the residual attack feasibility value.</td></tr>
  <tr><td>RQ_BCK_AP_2</td><td>An attack step shall be associated with one attack path.</td></tr>
  <tr><td>RQ_BCK_AP_03</td><td>An attack step shall have the following attributes:<br>• ID<br>• Description<br>• Associated attack path</td></tr>
  <tr><td>RQ_BCK_AP_04</td><td>An attack step shall be initialized with all its attributes.</td></tr>
  <tr><td>RQ_BCK_AP_05</td><td>An attack path shall be initialized with at least an ID and one attack step.</td></tr>

  <tr><th colspan="2">RQ_BCK_AF_XX</th></tr>
  <tr><td>RQ_BCK_AF_01</td><td>The attack feasibility rating of an attack path shall be assigned a single value among the following:<br>• High<br>• Medium<br>• Low<br>• Very low</td></tr>
  <tr><td>RQ_BCK_AF_02</td><td>The attack feasibility shall be determined using an attack potential-based approach.</td></tr>
  <tr><td>RQ_BCK_AF_03</td><td>The attack-potentiel-based approach shall rely on five core parameters:
  <br>• Elapsed time: Time to identify a vulnerability and develop and (successfully) apply an exploit.
  <br>• Specialist expertise: Capabilities of the attacker, relative to their skill and experience
  <br>• Knowledge of the item or component: Amount of information the attacker has acquired about the item or component.
  <br>• Window of opportunity: Access conditions (time, type) to successfully perform an attack.
  <br>• Equipment: Tools the attacker has available to discover the vulnerability and/or to execute the attack.</td></tr>
  <tr><td>RQ_BCK_AF_04</td><td>The criteria (and corresponding values) for elapsed time shall be defined as follows:<br>(0) ≤1 day<br>(1) ≤1 week<br>(4) ≤1 month<br>(17) ≤6 months<br>(19) >6 months</td></tr>
  <tr><td>RQ_BCK_AF_05</td><td>The criteria (and corresponding values) for specialist expertise shall be defined as follows:
  <br>(0) Layman: Unknowledgeable compared to experts or proficient persons, with no particular expertise.
  <br>(3) Proficient: Knowledgeable in that they are familiar with the security behaviour of the product or system type.
  <br>(6) Expert: Familiar with the underlying algorithms, protocols, hardware, structures, security behaviour, principles and concepts of security employed, techniques and tools for the definition of new attacks, cryptography, classical attacks for the product type, attack methods, etc. implemented in the product or system type.
  <br>(8) Multiple experts: Different fields of expertise are required at an expert level for distinct steps of an attack.</td></tr>
  <tr><td>RQ_BCK_AF_06</td><td>The criteria (and corresponding values) for knowledge of the item or component shall be defined as follows:
  <br>(0) Public information: Public information concerning the item or component (e.g. as gained from the Internet).
  <br>(3) Restricted information: Restricted information concerning the item or component (e.g. knowledge that is controlled within the developer organization and shared with other organizations under a non-disclosure agreement).
  <br>(7) Confidential information: Confidential information about the item or component (e.g. knowledge that is shared between discrete teams within the developer organization, access to which is constrained only to members of the specified teams).
  <br>(11) Strictly confidential information: Strictly confidential information about the item or component (e.g. knowledge that is known by only a few individuals, access to which is very tightly controlled on a strict need to know basis and individual undertaking).</td></tr>
  <tr><td>RQ_BCK_AF_07</td><td>The criteria (and corresponding values) for window of opportunity shall be defined as follows:
  <br>(0) Unlimited: High availability via public/untrusted network without any time limitation (i.e. asset is always accessible). Remote access without physical presence or time limitation as well as unlimited physical access to the item or component.
  <br>(1) Easy: High availability and limited access time. Remote access without physical presence to the item or component.
  <br>(4) Moderate: Low availability of the item or component. Limited physical and/or logical access. Physical access to the vehicle interior or exterior without using any special tools.
  <br>(10) Difficult: Very low availability of the item or component. Impractical level of access to the item or component to perform the attack.</td></tr>
  <tr><td>RQ_BCK_AF_08</td><td>The criteria (and corresponding values) for equipment shall be defined as follows:
  <br>(0) Standard: Equipment is readily available to the attacker. This equipment can be a part of the product itself (e.g. a debugger in an operating system), or can be readily obtained (e.g. internet sources, protocol analyser or simple attack scripts).
  <br>(4) Specialized: Equipment is not readily available to the attacker but can be acquired without undue effort. This can include purchase of moderate amounts of equipment (e.g. power analysis tools, use of hundreds of PCs linked across the internet would fall into this category), or development of more extensive attack scripts or programs. If clearly different test benches consisting of specialized equipment are required for distinct steps of an attack this would be rated as bespoke.
  <br>(7) Bespoke: Equipment is specially produced (e.g. very sophisticated software) and not readily available to the public (e.g. black market), or the equipment is so specialized that its distribution is controlled, possibly even restricted. Alternatively, the equipment is very expensive.
  <br>(9) Multiple bespoke: Is introduced to allow for a situation, where different types of bespoke equipment are required for distinct steps of an attack.</td></tr>
  <tr><td>RQ_BCK_AF_09</td><td>The attack potential shall correspond to the addition of all parameters.</td></tr>
  <tr><td>RQ_BCK_AF_10</td><td>The attack feasibility rating shall be determined based on the following attack potential ranges:<br>High: Attack potential between 0 and 13.<br>Medium: Attack potential between 14 and 19.<br>Low: Attack potential between 20 and 24.<br>Very Low: Attack potential greater than 25.</td></tr>

  <tr><th colspan="2">RQ_BCK_RD_XX</th></tr>
  <tr><td>RQ_BCK_RD_01</td><td>For each threat scenario, the risk value shall be determined from the impact of the associated damage scenarios and the attack feasibility of the associated attack paths.<br><br>Note 1: If a threat scenario corresponds to more than one damage scenario and/or an associated damage scenario has impacts in more than one impact category, a separate risk value can be determined separately for each of those impact ratings.<br>Note 2: If the threat scenario corresponds to more than one attack path, the threat scenario can be assigned the maximum of the attack feasibility ratings of the corresponding attack paths.</td></tr>
  <tr><td>RQ_BCK_RD_02</td><td>The risk value of a threat scenario shall be a value between (and including) 1 and 5, where a value of 1 represents minimal risk.</td></tr>
  <tr><td>RQ_BCK_RD_03
  </td><td>
  The method for risk value determination shall be based on the following risk matrix: <br><br> 
  <table border="1" cellspacing="0" cellpadding="5" style="border-collapse: collapse; text-align: center;">
    <thead>
      <tr>
        <th colspan="2" rowspan="2"></th>
        <th colspan="4"><b>Attack Feasibility Rating</b></th>
      </tr>
      <tr>
        <th><b>Very Low</b></th>
        <th><b>Low</b></th>
        <th><b>Medium</b></th>
        <th><b>High</b></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td rowspan="4" style="vertical-align: middle;"><b>Impact Rating</b></td>
        <td><b>Severe</b></td>
        <td><b>2</b></td>
        <td><b>3</b></td>
        <td><b>4</b></td>
        <td><b>5</b></td>
      </tr>
      <tr>
        <td><b>Major</b></td>
        <td>1</td>
        <td>2</td>
        <td>3</td>
        <td>4</td>
      </tr>
      <tr>
        <td><b>Moderate</b></td>
        <td>1</td>
        <td>2</td>
        <td>2</td>
        <td>3</td>
      </tr>
      <tr>
        <td><b>Negligible</b></td>
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

## Front-End requirements

<table>
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
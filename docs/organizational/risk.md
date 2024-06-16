# Risk Matrix

<center>
<table>
    <tr>
        <td></td>
        <td style="vertical-align: middle;"><center><b>Insignificant</b></center></td>
        <td style="vertical-align: middle;"><center><b>Minor</b></center></td>
        <td style="vertical-align: middle;"><center><b>Moderate</b></center></td>
        <td style="vertical-align: middle;"><center><b>Major</b></center></td>
        <td style="vertical-align: middle;"><center><b>Catastrophic</b></center></td>
    </tr>
    <tr>
        <td style="vertical-align: middle;"><center><b>Almost Certain</b><br>>90%</center></td>
        <td style="background: orange; vertical-align: middle;"><center>High</center></td>
        <td style="background: orange; vertical-align: middle;"><center>High</center></td>
        <td style="background: red; vertical-align: middle;"><center>Extreme</center></td>
        <td style="background: red; vertical-align: middle;"><center>Extreme</center></td>
        <td style="background: red; vertical-align: middle;"><center>Extreme</center></td>
    </tr>
    <tr>
        <td style="vertical-align: middle;"><center><b>Likely</b><br>50% - 90%</center></td>
        <td style="background: yellow; vertical-align: middle;"><center>Moderate</center></td>
        <td style="background: orange; vertical-align: middle;"><center>High</center></td>
        <td style="background: orange; vertical-align: middle;"><center>High</center></td>
        <td style="background: red; vertical-align: middle;"><center>Extreme</center></td>
        <td style="background: red; vertical-align: middle;"><center>Extreme</center></td>
    </tr>
    <tr>
        <td style="vertical-align: middle;"><center><b>Moderate</b><br>10% - 50%</center></td>
        <td style="background: green; vertical-align: middle;"><center>Low</center></td>
        <td style="background: yellow; vertical-align: middle;"><center>Moderate</center></td>
        <td style="background: orange; vertical-align: middle;"><center>High</center></td>
        <td style="background: red; vertical-align: middle;"><center>Extreme</center></td>
        <td style="background: red; vertical-align: middle;"><center>Extreme</center></td>
    </tr>
    <tr>
        <td style="vertical-align: middle;"><center><b>Unlikely</b><br>3% - 10%</center></td>
        <td style="background: green; vertical-align: middle;"><center>Low</center></td>
        <td style="background: green; vertical-align: middle;"><center>Low</center></td>
        <td style="background: yellow; vertical-align: middle;"><center>Moderate</center></td>
        <td style="background: orange; vertical-align: middle;"><center>High</center></td>
        <td style="background: red; vertical-align: middle;"><center>Extreme</center></td>
    </tr>
    <tr>
        <td style="vertical-align: middle;"><center><b>Rare</b><br><3%</center></td>
        <td style="background: green; vertical-align: middle;"><center>Low</center></td>
        <td style="background: green; vertical-align: middle;"><center>Low</center></td>
        <td style="background: yellow; vertical-align: middle;"><center>Moderate</center></td>
        <td style="background: orange; vertical-align: middle;"><center>High</center></td>
        <td style="background: orange; vertical-align: middle;"><center>High</center></td>
    </tr>
</table></center>

!!! question "What does each impact level mean?"

    <div class="grid cards" markdown>

    -   { .lg .middle } __Insignificant__

        ---

        Minor problem easily handled by normal day-to-day processes

    -   { .lg .middle } __Minor__

        ---

        Some disruption possible. e.g. damage equal to $500K, DDoS attacks, lost sales, server damage

    -   { .lg .middle } __Moderate__

        ---

        Significant time/resources required. e.g. damage equal to $1 million, low-level phishing, end-user malware, small environmental disaster

    -   { .lg .middle } __Major__

        ---

        Operations severly damaged. e.g. damage equal to $10 million, ransomware, system intrusions, APTs, severe environmental disaster, loss of privacy data

    -   { .lg .middle } __Catastrophic__

        ---

        Business survival is a risk. e.g. damage is equal to $25 million, all sites are down, backups fail, nuclear war

    </div>

## Perform a Cyber Risk Analysis

??? quote "Citations"

    Chapple, M., Stewart, J. M., &amp; Gibson, D. (2018). (ISC)² CISSP Certified Information Systems Security Professional: Official study guide (8th ed.). John Wiley &amp; Sons. 
    
    Kost, E. (2022, September 19). <em>5 step guide: How to perform a cyber risk analysis in 2022: Upguard</em>. UpGuard. Retrieved December 10, 2022, from [:octicons-link-external-16: https://www.upguard.com/blog/how-to-perform-a-cyber-risk-analysis](https://www.upguard.com/blog/how-to-perform-a-cyber-risk-analysis)


Cyber risk is calculated by considering the identified security threat, its degree of vulnerability, and the likelihood of exploitation.

<center>
$$
Cyber Risk = (Threat) x (Vulnerability) x (Information Value)
$$
</center>

### Specify Acceptable Level of Risk

Addressing all security risks is an inefficient use of security resources and in many cases unnecessary.


!!! success "Risk Responses"

    <div class="grid cards" markdown>

    -   { .lg .middle } __Mitigation__

        ---

        Putting security controls in place to attenuate the possible impact and/or likelihood of a specific risk. Prioritizing, evaluating, and implementing the appropriate risk-reducing controls/countermeasures recommended from the risk management process.

    -   { .lg .middle } __Assignment__

        ---

        Paying an external party to accept the financial impact of a given risk.

    -   { .lg .middle } __Acceptance__

        ---

        Determining that the potential benefits of a business function outweigh the possible risk impact/likelihood and performing that business function with no other action.

    -   { .lg .middle } __Deterrence__

        ---

        The process of implementing deterrents to would be violators of security and policy. 

    -   { .lg .middle } __Avoidance__

        ---

        Determining that the impact and/or likelihood of a specific risk is too great to be offset by the potential benefits and not performing a certain business function because of that determination.

    -   { .lg .middle } __Rejection__

        ---

        Denying or ignoring that a risk exists and hoping that it will never be realized. This is not a valid or prudent due-care response to risk.

    </div>
    
<center><img src="https://assets-global.website-files.com/5efc3ccdb72aaa7480ec8179/61b681f1bfb080540a5dfaa7_Inherent%20Risk%20vs.%20Residual%20Risk%20(Explained%20in%202%20Minutes).png" style="width: 100%"></center>
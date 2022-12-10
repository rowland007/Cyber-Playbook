# Supply Chain Levels for Software Artifacts (SLSA)

??? quote "Citation"
    Vijayan, J. (2022, December 9). Google: Use SLSA framework for Better Software Security. Dark Reading. Retrieved December 10, 2022, from [:octicons-link-external-16: https://www.darkreading.com/application-security/google-use-slsa-framework-for-better-software-security](https://www.darkreading.com/application-security/google-use-slsa-framework-for-better-software-security)

<figure>
    <img src="https://eu-images.contentstack.com/v3/assets/blt66983808af36a8ef/bltb1f0637f40232742/639267e2e856e932b8e8732c/supplychain_IncrediVFX_shutterstock.jpg" style="width: 100%;">
    <figcaption><center>Source: IncrediVFX via Shutterstock</center></figcaption>
</figure>

Organizations should implement the Supply Chain Levels for Software Artifacts (SLSA) framework when building software to ensure better software security and integrity, advocates Google — after the tech giant did a deep-dive into best practices for securing the software supply chain. 

In a report out on Dec. 9, Google laid out several recommendations for bolstering supply chain security, including the need for organizations to take on more direct responsibility for open source software, and taking a more holistic approach to addressing risks such as those presented by the Log4J vulnerability and the SolarWinds breach.

Google's report on software security is the first in a new "[:octicons-link-external-16: Perspectives on Security](https://services.google.com/fh/files/blogs/perspectives_on_security_volume_one_digital.pdf)" research series that examines emerging security trends and how to address them. The report's release comes on the second anniversary of the SolarWinds breach disclosure, and its recommendations are based on Google's analysis of that incident as well as numerous other software supply chain breaches since then. Those include incidents at [:octicons-link-external-16: Codecov](https://www.darkreading.com/attacks-breaches/attackers-compromised-code-checking-vendors-tool-for-two-months/d/d-id/1340765), [:octicons-link-external-16: Kaseya](https://www.darkreading.com/attacks-breaches/3-security-lessons-learned-from-the-kaseya-ransomware-attack) and those involving public code repositories such as [:octicons-link-external-16: PyPI](https://www.darkreading.com/application-security/10-malicious-packages-slither-pypi-registry).

The breaches have made software supply chain security a [:octicons-link-external-16: top item on the enterprise IT agenda](https://www.darkreading.com/attacks-breaches/the-next-generation-of-supply-chain-attacks-is-here-to-stay). A recent report from Mandiant identified supply chain compromises as [:octicons-link-external-16: contributing to 17% of all intrusions](https://www.mandiant.com/m-trends) in 2021, up from less than 1% just a year earlier. Supply chain issues were, in fact, the second most frequent initial intrusion vector after software vulnerability exploits in 2021.

## Two Main Takeaways for Security Decision-Makers

"There are two main key takeaways from this report that enterprise IT and security decision makers should consider that will help them securely build and verify the integrity of software," says Royal Hansen, vice president of engineering at Google. 

The first, as mentioned, is that security leaders need to focus on adopting a more holistic approach to strengthen defenses against software supply chain attacks: "Organizations should also implement the [:octicons-link-external-16: SupplyChain Levels for Software Artifacts (SLSA) framework](https://slsa.dev/) to ensure the security community mitigate threats across the entire software supply chain ecosystem," he says.

SLSA (pronounced "salsa") provides software developers a cadre of controls and practices to ensure software security and integrity during the entire software development life cycle through production. One of its key goals is to give organizations a way to prevent and detect tampering of the sort that happened at SolarWinds, where an adversary inserted malicious code into — and distributed it via — a signed software update.

SLSA is a prescriptive checklist, meaning it spells out the steps that organizations need to take. That includes, for instance, verifying the provenance of all open source and third-party components in their software, and for ensuring there's been no tampering with the software. 

Among other things, it also requires that organizations retain source code indefinitely and have the ability to verify the integrity of their software with tamper-proof provenance information.

Google perceives the SLSA framework as allowing organizations to optimize the benefits of things like a [:octicons-link-external-16: software bill of materials (SBOMs)](https://www.darkreading.com/dr-tech/waiting-for-sbom-take-a-look-at-asm), i.e., a list of all the components in a particular piece of software.

## Assuming More Responsibility

One of the other keys to bolstering supply chain security at an industry level is for organizations to secure their own open source and proprietary software supply chains, Google said.

This means ensuring that all software they build or acquire from other sources implements baseline security standards and controls. As an example, Google pointed to the Minimum Viable Secure Product (MVSP) requirements for enterprise-ready software that it developed in collaboration with several other companies, including Okta, Salesforce, Slack, and Venafi.

MVSP is a [:octicons-link-external-16: checklist of baseline security controls](https://mvsp.dev/) that a software developer must implement, at a minimum, to ensure a reasonably secure product. The checklist includes things such as whether the software vendor or publisher publishes vulnerability reports, conducts self-assessments and external testing, and implements practices such as SSO, HTTPS, and security headers.

Software purchasers can use the baseline to assess whether a product meets those requirements, while larger companies can incorporate MVSP as their standard questionnaire when triaging the security posture of their third-party software suppliers, Google said. Procurement teams can include them in requests for proposal (RFP) documents and use it as security baseline for vendor selection, Google said.

Hansen says security leaders and practitioners can also take other measures to bolster software supply chain security. "Findings from the report suggest a need for a more thorough understanding of software supply chain networks, identification of potential risks and implementation of risk-mitigation plans, and the establishment of security requirements for software procurement," he notes.

Security organizations can play a role as well by, for example, funding the Open Source Security Foundation (OSSF) and the open source software project maintainers who find and fix security vulnerability in open source code, Hansen says. 
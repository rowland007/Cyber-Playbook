???+ success "Data Classification Process"

    ``` mermaid
    graph TD
        A([Define the purpose of data classification]) --> B([Define the scope of the data environment]);
        B --> C([Discover all in-scope data]);
        C --> D([Define sensitivity levels and classify the data]);
        D --> E([Develop data handling guidelines to deliver the appropriate level of security for each category of data])
        style A fill:#4051b5,color:#fff
        style B fill:#4051b5,color:#fff
        style C fill:#4051b5,color:#fff
        style D fill:#4051b5,color:#fff
        style E fill:#4051b5,color:#fff
    ```

???+ abstract "Classification Examples"

    === "DoD Classifications"

        <table>
            <tr>
                <td style="vertical-align: middle;"><center>Category</center></td>
                <td style="vertical-align: middle;"><center>Unclassified</center></td>
                <td style="vertical-align: middle;"><center>Controlled Unclassified Information</center></td>
                <td style="vertical-align: middle;"><center>Confidential</center></td>
                <td style="vertical-align: middle;"><center>Secret</center></td>
                <td style="vertical-align: middle;"><center>Top Secret</center></td>
            </tr>
            <tr>
                <td style="vertical-align: middle;"><center>Color</center></td>
                <td style="background: green; vertical-align: middle;"><center>Green</center></td>
                <td style="background: purple; vertical-align: middle;"><center>Purple</center></td>
                <td style="background: blue; vertical-align: middle;"><center>Blue</center></td>
                <td style="background: red; vertical-align: middle;"><center>Red</center></td>
                <td style="background: yellow; vertical-align: middle;"><center>Yellow</center></td>
            </tr>
            <tr>
                <td style="vertical-align: middle;"><center>Definition</td>
                <td style="vertical-align: middle;">Any data that is approved for public eye and access falls under this category.</td>
                <td style="vertical-align: middle;">Government created or owned UNCLASSIFIED information that must be safeguarded from unauthorized disclosure</td>
                <td style="vertical-align: middle;">Information in which the unauthorized disclosure could reasonably be expected to cause damage to the national security.</td>
                <td style="vertical-align: middle;">Information in which the unauthorized disclosure could reasonably be expected to cause serious damage to the national security.</td>
                <td style="vertical-align: middle;">Information in which the unauthorized disclosure could reasonably be expected to cause exceptionally grave damage to the national security.</td>
            </tr>
            <tr>
                <td style="vertical-align: middle;"><center>Examples of Data</center></td>
                <td style="vertical-align: middle;">Press releases, announcements, news, etc.</td>
                <td style="vertical-align: middle;">Internal web pages, user guides, manuals, policies & procedures, inter-office memorandas, internal phone directories, etc.</td>
                <td style="vertical-align: middle;">Foreign government informatants, personnel authentication information, isolated personnel reports</td>
                <td style="vertical-align: middle;">Military plans, weapons systems, operations, foreign government information</td>
                <td style="vertical-align: middle;">Intelligence activities, cryptology, foreign relations, scientific, technological or economic matters relating to national security; programs for safeguarding nuclear materials or facilities, vulnerabilities or capabilities of systems, installations, infrastructures, projects or plans, or protection services, production, or use of weapons of mass destruction</td>
            </tr>
        </table>

    === "Other Classifications"

        <table>
            <tr>
                <td style="vertical-align: middle;"><center>Category</center></td>
                <td style="vertical-align: middle;"><center>:fontawesome-solid-people-group: Public [C1]</center></td>
                <td style="vertical-align: middle;"><center>:octicons-x-circle-fill-12: Internal Only [C2]</center></td>
                <td style="vertical-align: middle;"><center>:material-octagon: Confidential [C3]</center></td>
                <td style="vertical-align: middle;"><center>:octicons-stop-16: Restricted [C4]</center></td>
            </tr>
            <tr>
                <td style="vertical-align: middle;"><center>Color</center></td>
                <td style="background: green; vertical-align: middle;"><center>Green</center></td>
                <td style="background: blue; vertical-align: middle;"><center>Blue</center></td>
                <td style="background: yellow; vertical-align: middle;"><center>Yellow</center></td>
                <td style="background: red; vertical-align: middle;"><center>Red</center></td>
            </tr>
            <tr>
                <td style="vertical-align: middle;"><center>Definition</td>
                <td style="vertical-align: middle;">Any data that is approved for public eye and access falls under this category.</td>
                <td style="vertical-align: middle;">Any non-sensitive enterprise data that is meant to be used within the organization.</td>
                <td style="vertical-align: middle;">This type of data is still sensitive and a specific team or employees of an organization are given access to it.</td>
                <td style="vertical-align: middle;">Data that is highly sensitive in nature falls under this category. This data could cause legal consequences, reputational or financial damage, and loss of credibility upon its exposure</td>
            </tr>
            <tr>
                <td style="vertical-align: middle;"><center>Examples of Data</center></td>
                <td style="vertical-align: middle;">Vacany listings, brochures, press releases, marketing material, calendars, company news, newsletters, contracts, agreements, etc.</td>
                <td style="vertical-align: middle;">Internal web pages, user guides, manuals, company policies, inter-office memorandas, internal phone directories, etc.</td>
                <td style="vertical-align: middle;">Identity card number, address, bank information, biometric data, etc.</td>
                <td style="vertical-align: middle;">Social Security numbers, medical and criminal records, credit card numbers, CVV, financial information, health data, employee records, etc.</td>
            </tr>
            <tr>
                <td style="vertical-align: middle;"><center>Severity of Mishandling</center></td>
                <td style="vertical-align: middle;">None</td>
                <td style="vertical-align: middle;">Unauthorized disclosure **would not significantly impact** the company, or any of its stakeholders or employees.</td>
                <td style="vertical-align: middle;">Unauthorized disclosure **could result in significant adverse impact**, embarrassment, or civil/criminal liability to the company, stakeholders, employees, or business partners.</td>
                <td style="vertical-align: middle;">Unauthorized **disclosure likely to result in significant adverse impact**, embarrassment, or civil/criminal liability to the company, stakeholders, employees, or business partners.</td>
            </tr>
            <tr>
                <td style="vertical-align: middle;"><center>Controls Summary</center></td>
                <td style="vertical-align: middle;">
                    <ul>
                        <li>No restrictions on access</li>
                        <li>Copying of documents is unrestricted</li>
                        <li>May be left unsecured at any time</li>
                        <li>Disposal via normal paper waste</li>
                    </ul>
                </td>
                <td style="vertical-align: middle;">
                    <ul>
                        <li>Access restricted to named individuals and groups</li>
                        <li>Copying of documents is unrestricted</li>
                        <li>May be left unsecured in trusted environments</li>
                        <li>Shred paper waste</li>
                    </ul>
                </td>
                <td style="vertical-align: middle;">
                    <ul>
                        <li>Access restricted to named individuals and groups</li>
                        <li>Include appropriate notices regarding document or communication sensitivity</li>
                        <li>Copying of documents is unrestricted</li>
                        <li>Must be secured in locked cabinet or encrypted when not in use</li>
                        <li>Shred or burn paper waste</li>
                    </ul>
                </td>
                <td style="vertical-align: middle;">
                    <ul>
                        <li>No transmission via fax (insecure methods)</li>
                        <li>Access restricted to named individuals and groups</li>
                        <li>Include appropriate notices regarding document or communication sensitivity</li>
                        <li>Copies can only be made by roles designated by senior management in applicable business unit or department</li>
                        <li>All copies are numbered and recorded when required by the applicable regulation</li>
                        <li>Must be secured in locked cabinet or encrypted when not in use</li>
                        <li>Shred or burn paper waste</li>
                    </ul>
                </td>
            </tr>
        </table>

??? abstract "CUI Categories"

    <div class="grid cards" markdown>

    -   :material-chemical-weapon:{ .lg .middle } __Critical Infrastructure__
    
        ---

        - [X] Ammonium Nitrate
        - [X] Chemical-terrorism Vulnerability Information
        - [X] Critical Energy Infrastructure Information
        - [X] Emergency Management
        - [X] General Critical Infrastructure Information
        - [X] Information Systems Vulnerability Information
        - [X] Physical Security
        - [X] Protected Critical Infrastructure Information
        - [X] SAFETY Act Information
        - [X] Toxic Substances
        - [X] Water Assessments

    -   :material-shield:{ .lg .middle } __Defense__

        ---

        - [X] Controlled Technical Information
        - [X] DoD Critical Infrastructure Security Information
        - [X] Naval Nuclear Propulsion Information
        - [X] Unclassified Controlled Nuclear Information - Defense

    -   :material-export-variant:{ .lg .middle } __Export Control__

        ---

        - [X] Export Controlled
        - [X] Export Controlled Research

    -   :material-finance:{ .lg .middle } __Financial__

        ---

        - [X] Bank Secrecy
        - [X] Budget
        - [X] Comptroller General
        - [X] Consumer Complaint Information
        - [X] Electronic Funds Transfer
        - [X] Federal Housing Finance Non-Public Information
        - [X] Financial Supervision Information
        - [X] General Financial Information
        - [X] International Financial Institutions
        - [X] Mergers
        - [X] Net Worth
        - [X] Retirement

    -   :fontawesome-solid-people-group:{ .lg .middle } __Immigration__

        ---

        - [X] Asylee
        - [X] Battered Spouse or Child
        - [X] Permanent Resident Status
        - [X] Status Adjustment
        - [X] Temporary Protected Status
        - [X] Victims of Human Trafficking
        - [X] Visas

    -   :material-magnify-expand:{ .lg .middle } __Intelligence__

        ---

        - [X] Agriculture
        - [X] Foreign Intelligence Surveillance Act
        - [X] Foreign Intelligence Surveillance Act Business Records
        - [X] General Intelligence
        - [X] Geodetic Product Information
        - [X] Intelligence Financial Refords
        - [X] Internal Data
        - [X] Operations Security
    
    -   :fontawesome-solid-globe:{ .lg .middle } __International Agreements__

        ---

        - [X] International Agreement Information

    -   :material-police-badge-outline:{ .lg .middle } __Law Enforcement__

        ---
        
        - [X] Accident Investigation
        - [X] Campaign Funds
        - [X] Committed Person
        - [X] Communications
        - [X] Controlled Substances
        - [X] Criminal History Records Information
        - [X] DNA
        - [X] General Law Enforcement
        - [X] Informant
        - [X] Investigation
        - [X] Juvenile
        - [X] Law Enforcement Financial Records
        - [X] National Security Letter
        - [X] Pen Register/Trap & Trace
        - [X] Reward
        - [X] Sex Crime Victim
        - [X] Terrorist Screening
        - [X] Whistleblower Identity

        
    -   :fontawesome-solid-scale-unbalanced:{ .lg .middle } __Legal__

        ---

        - [X] Administrative Proceedings
        - [X] Child Pornography
        - [X] Child Victim/Witness
        - [X] Collective Bargaining
        - [X] Federal Grand Jury
        - [X] Legal Privilege
        - [X] Legislative Materials
        - [X] Presentence Report
        - [X] Prior Arrest
        - [X] Protective Order
        - [X] Victim
        - [X] Witness Protection

    -   :fontawesome-solid-tree:{ .lg .middle } __Natural and Cultural Resources__

        ---

        - [X] Archaeological Resources
        - [X] Historic Properties
        - [X] National Park System Resources

    -   :material-file-document-edit:{ .lg .middle } __North Atlantic Treaty Organization (NATO)__

        ---

        - [X] NATO Restricted
        - [X] NATO Unclassified

    -   :material-radioactive:{ .lg .middle } __Nuclear__

        ---

        - [X] General Nuclear
        - [X] Nuclear Recommendation Material
        - [X] Nuclear Security-Related Information
        - [X] Safeguards Information
        - [X] Unclassified Controlled Nuclear Information - Engery

    -   :material-file-certificate-outline:{ .lg .middle } __Patent__

        ---

        - [X] Patent Applications
        - [X] Inventions
        - [X] Secrecy Orders

    -   :material-eye-check:{ .lg .middle } __Privacy__

        ---

        - [X] Contract Use
        - [X] Death Records
        - [X] General Privacy
        - [X] Genetic Information
        - [X] Health Information
        - [X] Inspector General Protected
        - [X] Military Personnel Records
        - [X] Personnel Records
        - [X] Student Records

    -   :material-bullseye-arrow:{ .lg .middle } __Procurement and Acquisition__

        ---

        - [X] General Procurement and Acquisition
        - [X] Small Business Research and Technology
        - [X] Source Selection

    -   :fontawesome-solid-business-time:{ .lg .middle } __Proprietary Business Information__

        ---

        - [X] Entity Registration Information
        - [X] General Proprietary Business Information
        - [X] Ocean Common Carrier and Marine Terminal Operator Agreements
        - [X] Ocean Common Carrier Service Contracts
        - [X] Proprietary Manufacturer
        - [X] Proprietary Postal
     
    -   :material-clipboard-check:{ .lg .middle } __Provisional__

        ---

        - [X] Homeland Security Agreement Information
        - [X] Homeland Security Enforcement Information
        - [X] Information Systems Vulnerability Information - Homeland
        - [X] International Agreement Information - Homeland
        - [X] Operations Security Information
        - [X] Peronnel Security Information
        - [X] Physical Secrity - Homeland
        - [X] Privacy Information
        - [X] Sensitive Personally Identifiable Information

    -   :material-chart-sankey:{ .lg .middle } __Statistical__

        ---

        - [X] Investment Survey
        - [X] Pesticide Producer Survey
        - [X] Statistical Information
        - [X] US Census

    -   :fontawesome-solid-money-bill-wave:{ .lg .middle } __Tax__

        ---

        - [X] Federal Taxpay Information
        - [X] Tax Convention
        - [X] Taxpayer Advocate Information
        - [X] Written Determinations
    
    -   :material-plane-train:{ .lg .middle } __Transportation__

        ---

        - [X] Railroad Safety Analysis Records
        - [X] Sensitive Security Information

    </div>

???+ info "Classification Process Example"

    ``` mermaid
    graph TB
        A[Is the data intended for public disclosure?] --> |Yes| B>Public]
        A --> |No| C[Does it contain personal data?]
        C --> |Yes| D[Does it contain sensitive data, suspicion of illegal activities, criminal and administrative offences?]
        C --> |No| E[Does the disclosure of data cause negative impact to the company?]
        D --> |Yes| F>Restricted]
        D --> |No| G[Does the dislosure of data cause negative impact to company reputation?]
        E --> |Yes| H[Does the disclosure of data cause significant dame to company?]
        E --> |No| I>Internal Only]
        G --> |Yes| J>Confidential]
        G --> |No| I
        H --> |Yes| F
        H --> |No| J
       
        style A fill:#4051b5,color:#fff
        style B fill:green,color:#fff
        style C fill:#4051b5,color:#fff
        style D fill:#4051b5,color:#fff
        style E fill:#4051b5,color:#fff
        style F fill:red,color:#fff
        style G fill:#4051b5,color:#fff
        style H fill:#4051b5,color:#fff
        style I fill:blue,color:#fff
        style J fill:yellow,color:#000
    ```


## Creating Header & Footer Labels in Word

- Create the content of the header and footer you want.
- Select everything in the header.
- Click the Header button in the Header & Footer Tools ribbon, look at the bottom of the gallery, and click "Add selection to Header gallery".
- Enter a name (and possibly other items) in the dialog that appears.
- Select everything in the footer.
- Click the Footer button and click "Add selection to Footer gallery".
- Complete the dialog that appears.
- When exiting Word, answer yes to the prompt about saving the Building Blocks.dotx template.

## PowerPoint Labels

[Click Here](../static/docs/data-classification-labels.pptx) :simple-microsoftpowerpoint: to download the PowerPoint.
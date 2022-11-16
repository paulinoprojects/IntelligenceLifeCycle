# IntelligenceLifeCycle

![Intel LifeCycle](https://user-images.githubusercontent.com/111991325/202077793-32e8318c-fe29-4bd9-9f78-531301595872.png)

1. <b> Reqirements (Planning & Direction) </b> - The requirements phase sets out the goals for the intelligence gathering effort.
    
2. <b> Collections (& Process) </b> - The collection process is implemented by software tools, such as SIEMs, and then processed for later analysis.
  
3. <b> Analysis </b> - The analysis is performed against the given use cases from the planning phase and may utilize automated analysis, artificial intelligence, and machine learning.

4. <b> Dissemination </b> - The dissemination phase refers to publishing information produced by analysis to consumers who need to act on the insights developed: Strategic, Operational, Tactical.

5. <b> Feedback </b> - The phase that aims to clarify requirements and improve the collection, analysis, and dissemination of information by reviewing current inputs and outputs: Lessons learned. Measurable success, Evolving threat issues.

## Characteristics of Intelligence Sources

<b>You must consider the sources of your intelligence!</b>
- <b>Timeliness</b>: Property of an intelligence source that ensures it is up-to-date
- <b>Relevancy</b>: Property of an intelligence source that ensures it matches the use cases intended for it
- <b>Accuracy</b>: Property of an intelligence source that ensures it produces effective results
- <b>Confidence Levels</b>: Property of an intelligence source that ensures it produces qualified statements about reliability

## Types of Sources 

- <b>Proprietary-Source</b>
    - Threat intelligence is very widely provided as a commercial service offering,
where access to updates and research is subject to a subscription fee
- <b>Closed-Source</b>
    - Data that is derived from the provider's own research and analysis efforts, such as data from honeynets that they operate, plus information mined from its customers' systems, suitably anonymized
- <b>Open-Source</b>
    - Data that available to use without subscription, may include threat feeds similar to the commercial providers, and may contain reputation lists and malware signature databases
      - US-CERT
      - MITRE
      - MISP
      - VirusTotal
      - SANS ISC Suspicious Domains
      - Threat feeds are a form of explicit knowledge, but implicit knowledge is also useful from experience practitioners
 - <b>Open-Source Intelligence (OSINT)</b>
    - Methods of obtaining information about a person or organization through public records, websites, and social media

![Source Eval](https://user-images.githubusercontent.com/111991325/202078186-eaac1ef7-bfc6-4ef5-a193-b8f22792b916.png)

# Threat Classification - Importance of Threat Data & Intelligence
- <b>Threat Modeling</b>
    - The process of identifying and assessing the possible threat actors and attack vectors that pose a risk to the security of an app, network, or other system
    - Threat modeling may be used to analyze corporate networks in general or against specific targets like a website or application being deployed
        - How can the attack be performed?
        - What is the potential impact to the confidentiality, integrity, and availability of the data?
        - How likely is the risk to occur?
        - What mitigations are in place?

- <b>Adversary Capability</b>
    - A formal classification of the resources and expertise available to a threat actor
    -  What tools are they using?
        -  Acquired and augmented
        -  Developed
        -  Advanced
        -  Integrated
        
- <b>Attack Surface</b>
    - The points at which a network or application receives external connections or inputs/outputs that are potential vectors to be exploited by a threat actor
        - The holistic network
        - Websites or cloud-services
        - Custom software applications

- <b>Attack Vector</b>
    - A specific path by which a threat actor gains unauthorized access to a system
        - Cyber
        - Human
        - Physical
- <b>Risk</b>
    - Likelihood - The chance of a threat being realized which is usually expressed as a percentage
    - Impact - The cost of a security incident or disaster scenario which is usually expressed in cost (dollars)

## Threat Classification
  - <b>Known Threats</b>
    - A threat that can be identified using basic signature or pattern matching
  - <b>Malware</b>
    - Any software intentionally designed to cause damage to a computer, server,client, or computer network
  - <b>Documented Exploits</b>
    - A piece of software, data or sequence of commands that takes advantage of a vulnerability to cause unintended behavior or to gain unauthorized access to sensitive data
  - <b>Unknown Threats</b>
    - A threat that cannot be identified using basic signature or pattern matching
  - <b>Zero-day Exploit</b>
    - An unknown exploit in the wild that exposes a vulnerability in software or hardware and can create complicated problems well before anyone realizes something is wrong
  - <b>Obfuscated Malware Code</b>
    - Malicious code whose execution the malware author has attempted to hide through various techniques such as compression, encryption, or encoding to severely limit attempts to statically analyze the malware
  - <b>Behavior-based Detection</b>
    - A malware detection method that evaluates an object based on its intended actions before it can actually execute that behavior
  - <b>Recycled Threats</b>
    - Refers to the process of combining and modifying parts of existing exploit code to create new threats that are not as easily identified by automated scanning
  - <b>Known Unknowns</b>
    - A classification of malware that contains obfuscation techniques to circumvent signature-matching and detection
  - <b>Unknown Unknowns</b>
    - A classification of malware that contains completely new attack vectors and exploits

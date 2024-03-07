# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

Threat actors including ransomware gangs are seen exploiting newly discovered critical flaws in remote monitoring and management software called ScreenConnect. 

 The **Outbreak Response - ConnectWise ScreenConnect Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/1.0.0/README.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*, *QRadar*, *Splunk*, and *Azure Log Analytics*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/connectwise-screenconnect-attack) contains information about the outbreak alert **Outbreak Response - ConnectWise ScreenConnect Attack**. 

## Background: 

One of the flaws, CVE-2024-1709 is an authentication bypass vulnerability using an alternate path or channel that could let attackers gain administrative access to a ScreenConnect instance. The second flaw tracked as CVE-2024-1708 is a path traversal vulnerability that may allow an attacker to execute remote code. According to Shadowserver, around 8200 vulnerable ConnectWise ScreenConnect instances were found on the internet and 643 IPs were observed attacking it.

According to the company website, ConnectWise remote-access software is one of the leading provider used by Managed service providers (MSPs) to remotely connect to thier customers systems. This could pose a significant threat to end users systems who could be targreted downstream and can allow hackers to remotely plant malicious code, such as malware, on vulnerable ConnectWise customer instances. 

## Announced: 

February 19, 2024: ConnectWise published a security advisory and has released a patch covering both vulnerabilities. 
https://www.connectwise.com/company/trust/security-bulletins/connectwise-screenconnect-23.9.8

February 21, 2024: Proof of Concept (PoC) code was released on GitHub.

February 22, 2024: CVE-2024-1709 was added to CISA's known exploited catalog.
https://www.cisa.gov/known-exploited-vulnerabilities-catalog

February 22, 2024: FortiGuard Labs released a Threat Signal on ConnectWise ScreenConnect Vulnerabilities (CVE-2024-1708 and CVE-2024-1709)
https://www.fortiguard.com/threat-signal-report/5389/ 

## Latest Developments: 

Februrary 29, 2024: FortiGuard Labs recommends companies to apply the most recent upgrade or patch from the vendor as soon as possible. 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|
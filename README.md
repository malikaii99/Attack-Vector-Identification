# Attack Vector Identification
<h1>Description</h1>

In this exercise, I will evaluate the potential attack scenarios associated with a USB drive. I will examine a situation where you discover a USB drive in a parking lot, exploring it from the perspectives of both an attacker and a potential victim.

USB drives, also known as flash drives, are commonly utilized for data storage and transfer. Nevertheless, the convenience of these compact devices also brings along certain security concerns. Malicious actors often exploit USB drives to distribute harmful software, compromise hardware, or gain control over devices. An example of such an attack is USB baiting, where a threat actor strategically leaves a malware-infected USB drive in a location where an unsuspecting employee might discover it and plug it into a device, inadvertently introducing malware into a network. This tactic relies on the curiosity of individuals who come across unfamiliar flash drives and plug them into their systems.


<h2>Scenario</h2>

Review the scenario below.

You are part of the security team at Rhetorical Hospital and arrived at work one morning. On the ground of the parking lot, you find a USB stick with the hospital's logo printed on it. There’s no one else around who might have dropped it, so you decide to pick it up out of curiosity.

You bring the USB drive back to your office, where the team has virtualization software installed on a workstation. Virtualization software can be used for this very purpose because it’s one of the only ways to safely investigate an unfamiliar USB stick. The software works by running a simulated instance of the computer on the same workstation. This simulation isn’t connected to other files or networks, so the USB drive can’t affect other systems if it happens to be infected with malicious software.

You create a virtual environment and plug the USB drive into the workstation. The contents of the device appear to belong to Jorge Bailey, the human resource manager at Rhetorical Hospital.Jorge's drive contains a mix of personal and work-related files. For example, it contains folders that appear to store family and pet photos. There is also a new hire letter and an employee shift schedule.
Review the types of information that Jorge has stored on this device.
The flash drive appears to contain a mixture of personal and work-related files. Consider how an attacker might use this information if they obtained it. Also, consider whether this whole event was staged.

Pro tip: The Cybersecurity and Infrastructure Security Agency (CISA) provides some security tips on using caution with USB drives, including keeping personal and business drives separate.

You have not opened any of the files on the device, which is best practice. Attackers sometimes conduct USB baiting attacks to deliver malicious code that they've crafted.
However, this USB drive was still a security risk, even though it did not contain malicious code. It could have easily been found by an attacker who might have used its contents to plan a variety of attacks.


<h2> Report</h2>

<h3>Contents</h3>

The USB device in question holds a trove of sensitive information that encompasses crucial documents such as a new hire letter and an employee shift schedule. These documents, in themselves, are of significance to the organization, but what amplifies the potential risk is that they contain personally identifiable information (PII). PII, if accessed by malicious individuals, could result in dire consequences, as it often includes sensitive personal data like names, addresses, social security numbers, and more. The mishandling of such information, especially when it falls into the wrong hands, can lead to identity theft, financial fraud, or other forms of malicious exploitation.



<h3>Attacker Mindset </h3>

Delving into the attacker's perspective reveals even graver concerns. Armed with personal information about an individual named Jorge and certain work-related details, a threat actor could craft highly convincing and targeted attacks. For instance, they might employ the personal information as a means to exploit Jorge's relatives or associates, potentially subjecting them to various forms of manipulation, fraud, or identity theft. On the business front, the work-related information found on the USB drive could serve as a stepping stone for a malicious actor to infiltrate the organization's systems. For example, a malicious email can be designed to look as though it comes from a coworker or relative.

This underscores the multifaceted nature of the threat posed by the exposure of sensitive information on a USB drive. It not only jeopardizes the affected individual's privacy and security but also extends its reach to potentially compromise the integrity and security of the entire organization. Thus, robust security measures, stringent data handling protocols, and employee awareness become imperative in averting the myriad risks associated with such scenarios.

<h3>Risk Analysis </h3>

Malicious software that can be hidden on USB devices includes various types of malware designed to compromise computer systems and networks. Here are some examples: viruses,
trojans, ransomware, spyware, and worms.
If an infected USB drive is discovered and connected by another employee, several consequences could occur: system and network infection, data theft, and a privacy breach.
A threat actor who gains access to this information could use it for various malicious purposes: Identity Theft: Stolen personal information might be used to commit identity theft, corporate espionage, ransom or extortion, and phishing.

To mitigate these risks, organizations should have robust cybersecurity policies in place, including employee training on recognizing and handling suspicious devices and files.
Promoting employee awareness about these types of attacks and what to do when a suspicious USB drive occurs is a managerial control that can reduce the risk of a negative incident.
Setting up routine antivirus scans is an operational control that can be implemented. Another line of defense could be a technical control, like disabling AutoPlay on company PCs that will prevent a computer from automatically executing malicious code when a USB drive is plugged in.
Regular system and network security updates can also help prevent malware infections from USB drives.


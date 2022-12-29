# GoogleChromeExtension
Retrieval for Google Chrome Extension Malware Analysis


## Commercial Antivirus Limitation

Technically, the modus operandi for the identification of malicious files and servers refers to consult in named blacklist databases. The VirusTotal platform issues the diagnoses regarding malignant characteristics related to files and web servers.

When it comes to suspicious files, VirusTotal issues the diagnostics provided by the world's leading commercial antivirus products. Regarding suspicious web servers, VirusTotal uses the database responsible for sensing virtual addresses with malicious practices.

VirusTotal has Application Programming Interface (APIs) that allow programmers to query the platform in an automated way and without the use of the graphical web interface. The proposed paper employs two of the APIs made available by VirusTotal. The first one is responsible for sending the investigated files to the platform server. The second API, in turn, makes commercial antivirus diagnostics available for files submitted to the platform by the first API.

Initially, the executable malwares are sent to the server belonging to the VirusTotal platform. After that, the executables are analyzed by the 86 commercial antiviruses linked to VirusTotal. Therefore, the antivirus provides its diagnostics for the executables submitted to the platform. VirusTotal allows the possibility of issuing three different types of diagnostics: malware, benign and omission.

Then, through the VirusTotal platform, the proposed paper investigates 68 commercial antiviruses with their respective results presented in Table 2. We used 1000 malicious executables for ARM obtained from our database. The goal of the work is to check the number of virtual pests cataloged by antivirus. The motivation is that the acquisition of new virtual plagues plays an important role in combating malicious applications. Therefore, the larger the database of malwares blacklisted, the better it tends to be the defense provided by the antivirus.

As for the first possibility of VirusTotal, the antivirus detects the malignity of the suspicious file. In the proposed experimental environment, all submitted executables are public domain malwares. Therefore, in the proposed study, the antivirus hits when it detects the malignity of the investigated executable. Malware detection indicates that the antivirus provides a robust service against cyber-intrusions. As larger the blacklist database, better tends to be the defense provided by the antivirus.

In the second possibility, the antivirus attests to the benignity of the investigated file. Therefore, in the proposed study, when the antivirus attests the benignity of the file, it is a case of a false negative – since all the samples are malicious. That is, the investigated executable is a malware; however, the antivirus attests to benignity in the wrong way.

In the third possibility, the antivirus does not emit opinion about the suspect executable. The omission indicates that the file investigated has never been evaluated by the antivirus neither it has the robustness to evaluate it in real time. The omission of the diagnosis by the antivirus points to its limitation on large-scale services.

In the third possibility, the antivirus does not emit opinion about the suspect executable. The omission indicates that the file investigated has never been evaluated by the antivirus neither it has the robustness to evaluate it in real time. The omission of the diagnosis by the antivirus points to its limitation on large-scale services.

Table 2 shows the results of the evaluated 68 antivirus products. Only one of these antiviruses scored above 82,6%. This antivirus is: ESET-NOD32. Malware detection indicates that these antivirus programs provide an efficient service against cyber-intrusions.

A major adversity in combating malicious applications is the fact that antivirus makers do not share their malware blacklists due to commercial disputes. Through Table 2 analyse, the proposed paper points to an aggravating factor of this adversity: the same antivirus vendor does not even share its databases between its different antivirus programs. Note, for example, that McAfee and McAfee-GW-Edition antiviruses belong to the same company. Their blacklists, though robust, are not shared with each other. Therefore, the commercial strategies of the same company hinder the confrontation with malware. It complements that antivirus vendors are not necessarily concerned with avoiding cyber-invasions, but with optimizing their business income.

Malware detection ranged from 0% to 82.6%, depending on the antivirus being investigated. On average, the 68 antiviruses were able to detect 46.08% of the evaluated virtual pests, with a standard deviation of 35.61. The high standard deviation indicates that the detection of malicious executables may suffer abrupt variations depending on the antivirus chosen. It is determined that the protection, against cybernetic invasions, is due to the choice of a robust antivirus with a large and updated blacklist.

As for the false negatives, Malwarebytes, Baidu and Panda antiviruses, wrongly stated that malware was benign in more than 95% of cases. On average, antiviruses attested false negatives in 44.85% of the cases, with a standard deviation of 36.26. Tackling the benignity of malware can lead to irrecoverable damage. A person or institution, for example, would rely on a particular malicious application when, in fact, it is malware.

Antivirus companies Invincea, CrowdStrike, eGambit and F-Prot hardly withheld opinions on any of the 1,000 malicious samples. Therefore, about 7.35% of antivirus software were not able to diagnose a significant minimum number of malicious samples. On average, the antiviruses were missing in 8.92% of the cases, with a standard deviation of 25.76. The omission of the diagnosis points to the limitation of these antiviruses that have limited blacklists for detection of malware in real time.

It is included as adversity, in the combat to malicious applications, the fact of the commercial antiviruses do not possess a pattern in the classification of the malwares as seen in Table 3. We choose 3 of 1,000 malwares samples in order to exemplify the miscellaneous classifications of commercial antiviruses. The chosen malware are VirusShare_001627d61a1bde3478ca4965e738dc1e, VirusShare_075efef8c9ca2f675be296d5f56406fa and VirusShare_0dab86f850fd3dafc98d0f2b401377d5. In this way, the time when manufacturers react to a new virtual plague is affected dramatically. As there is no a pattern, antiviruses give the names that they want, for example, a company can identify a malware as "Trojan.Linux.Generic.69575" and a second company identify it as "ELF:DDoS-S [Trj]". Therefore, the lack of a pattern, besides the no-sharing of information among the antivirus manufacturers, hinders the fast and effective detection of a malicious application.

###### Table 2 Results of 68 commercial antiviruses:

Antivirus |	Deteccion (%) |	False Negative (%) |	Omission (%)
--------- | ------------- | ------------------ | -------------
Kaspersky |	63,64	| 36,36 |	0 |
DrWeb |	59,09 |	40,91 |	0 |
Jiangmin	|54,55	|45,45|	0
ESET-NOD32	|54,55	|45,45|	0
Antiy-AVL	|54,55|	40,91|	4,55
NANO-Antivirus	|54,55|	45,45|	0
BitDefender	|54,55	|45,45|	0
Emsisoft	|54,55|	45,45	|0
ZoneAlarm	|50|	50|	0
Avast	|50	|50	|0
Fortinet	|50	|50|	0
Microsoft	|50	|50	|0
Ikarus|	50	|40,91	|9,09
MAX	|50|	50	|0
GData|	50	|45,45	|4,55
Lionic	|50	|45,45|	4,55
Cyren	|50	|50	|0
AVG	|50	|45,45	|4,55
McAfee	|50	|50	|0
Symantec	|50	|40,91	|9,09
Yandex|	50	|50	|0
McAfee-GW-Edition	|45,45	|50	|4,55
TrendMicro	|45,45	|36,36	|18,18
TrendMicro-HouseCall	|45,45|	40,91|	13,64
Panda	|45,45	|54,55	|0
ALYac	|45,45	|54,55|	0
VBA32	|40,91	|59,09	|0
Rising	|40,91|	45,45|	13,64
Elastic	|40,91	|0|	59,09
FireEye	|40,91	|22,73|	36,36
Arcabit	|27,27	|72,73|	0
Qihoo-360	|18,18	|31,82	|50
Zillya	|9,09	|72,73	|18,18
MicroWorld-eScan	|4,55	|95,45|	0
Sangfor	|4,55	|54,55	|40,91
Avira	|4,55	|95,45	|0
Endgame	|4,55	|0	|95,45
F-Secure	|4,55	|95,45	|0
Comodo	|4,55	|95,45	|0
BitDefenderTheta	|0	|54,55	|45,45
Avast-Mobile	|0	|50	|50
MaxSecure	|0	|54,55	|45,45
TheHacker	|0	|40,91	|59,09
TotalDefense	|0	|50	|50
Babable	|0	|36,36	|63,64
Tencent	|0	|100	|0
F-Prot	|0	|36,36	|63,64
Zoner	|0	|100	|0
Bkav	|0	|90,91	|9,09
TACHYON	|0	|100	|0
AhnLab-V3	|0	|100	|0
CMC	|0	|100	|0
CAT-QuickHeal	|0	|100	|0
Malwarebytes	|0	|100	|0
VIPRE	|0	|77,27	|22,73
K7AntiVirus	|0	|100	|0
K7GW	|0	|100	|0
Baidu	|0	|100	||0
ClamAV	|0	|90,91	|9,09
SUPERAntiSpyware	|0	|100	|0
Ad-Aware	|0	|100	|0
Sophos	|0	|100	|0
Kingsoft	|0	|100	|0
Gridinsoft	|0	|50	|50
ViRobot|0	|100	|0
Cynet	|0	|50	|50
AVware	|0	|4,55	|95,45

###### Table 3 Miscellaneous classifications of commercial antiviruses:

Antivírus |	VirusShare_001627d61a1bde3478ca4965e738dc1e |	VirusShare_075efef8c9ca2f675be296d5f56406fa |	VirusShare_0dab86f850fd3dafc98d0f2b401377d5
--------- | ------------------------------------------- | ------------------------------------------- | --------------------------------------------
ALYac|Trojan.Linux.Generic.69575|Gen:Variant.Backdoor.Linux.Tsunami.1|Trojan.Linux.GenericA.73451|
AVG|ELF:DDoS-S [Trj]|ELF:Gafgyt-DO [Trj]|ELF:DDoS-S [Trj]|
Acronis|False Positive|False Positive|False Positive| 
Ad-Aware|Trojan.Linux.Generic.69575|Gen:Variant.Backdoor.Linux.Tsunami.1|Trojan.Linux.GenericA.73451|
AhnLab-V3|Linux/Mirai.Gen6|Linux/Tsunami.Gen|Linux/Gafgyt.Gen|
Antiy-AVL|Trojan[Backdoor]/Linux.Gafgyt.a|GrayWare/Linux.Generic|Trojan[Backdoor]/Linux.Gafgyt.ac|
Arcabit|Trojan.Linux.Generic.D10FC7|Trojan.Backdoor.Linux.Tsunami.1|Trojan.Linux.GenericA.D11EEB|
Avast|ELF:DDoS-S [Trj]|ELF:Gafgyt-DO [Trj]|ELF:DDoS-S [Trj]|
Avast-Mobile|ELF:DDoS-S [Trj]|ELF:Tsunami-CR [Trj]|ELF:DDoS-S [Trj]|
Avira|LINUX/Gafgyt.opnd|LINUX/Tsunami.wkuvt|LINUX/Gafgyt.opnd|
Baidu|False Positive|False Positive|False Positive| 
BitDefender|Trojan.Linux.Generic.69575|Gen:Variant.Backdoor.Linux.Tsunami.1|Trojan.Linux.GenericA.73451|
BitDefenderTheta|Gen:NN.Mirai.34608|Gen:NN.Mirai.34608|Gen:NN.Mirai.34608|
Bkav|False Positive|False Positive|False Positive| 
CAT-QuickHeal|False Positive|Elf.Trojan.A1198970|False Positive| 
CMC|False Positive|False Positive|False Positive| 
ClamAV|Unix.Malware.Agent-6769357-0|Unix.Trojan.Mirai-5607483-0|Unix.Trojan.Gafgyt-111|
Comodo|Malware@#3o8smwc385jui|Malware@#3j0a9lm761bhc|Malware@#1vbephabp2pmb|
Cynet|Malicious (score: 85)|Malicious (score: 85)|Malicious (score: 85)|
Cyren|E32/Gafgyt.C.gen!Camelot|E32/Gafgyt.C.gen!Camelot|E32/Gafgyt.C.gen!Camelot|
DrWeb|Linux.BackDoor.Fgt.1755|Linux.BackDoor.Tsunami.485|Linux.BackDoor.Fgt.9|
ESET-NOD32|a variant of Linux/Mirai.AE|a variant of Linux/Tsunami.NBV|a variant of Linux/Gafgyt.C|
Emsisoft|Trojan.Linux.Generic.69575 (B)|Gen:Variant.Backdoor.Linux.Tsunami.1 (B)|Trojan.Linux.GenericA.73451 (B)
F-Secure|Malware.LINUX/Gafgyt.opnd|Malware.LINUX/Tsunami.wkuvt|Malware.LINUX/Gafgyt.opnd|
FireEye|Trojan.Linux.Generic.69575|Gen:Variant.Backdoor.Linux.Tsunami.1|Trojan.Linux.GenericA.73451|
Fortinet|ELF/Mirai.AE!tr|ELF/Tsunami.NDJ!tr|ELF/Gafgyt.UN!tr.bdr|
GData|Linux.Trojan.Gafgyt.A|Linux.Trojan.Gafgyt.A|Linux.Trojan.Gafgyt.B|
Gridinsoft|False Positive|False Positive|False Positive| 
Ikarus|Trojan.Linux.Mirai|Trojan.Linux.Fgt|Trojan.Linux.Fgt|
Jiangmin|Backdoor.Linux.cbip|Backdoor.Linux.ksj|Backdoor.Linux.gmy|
K7AntiVirus|False Positive|False Positive|False Positive| 
K7GW|False Positive|False Positive|False Positive| 
Kaspersky|HEUR:Backdoor.Linux.Gafgyt.a|HEUR:Backdoor.Linux.Tsunami.bh|HEUR:Backdoor.Linux.Gafgyt.ac|
Kingsoft|False Positive|False Positive|False Positive| 
Lionic|Trojan.Linux.Gafgyt.4!c|malware (ai score=99)|False Positive| 
MAX|malware (ai score=99)|False Positive|malware (ai score=98)
Malwarebytes|False Positive|Trojan.Malware.121218.susgen|False Positive| 
MaxSecure|Trojan.Malware.121218.susgen|Linux/Gafgyt.h|Trojan.Malware.121218.susgen|
McAfee|Linux/Mirai.g|Linux/Gafgyt.h|Linux/Gafgyt.r|
McAfee-GW-Edition|Linux/Mirai.g|Gen:Variant.Backdoor.Linux.Tsunami.1|Linux/Gafgyt.r|
MicroWorld-eScan|Trojan.Linux.Generic.69575|Backdoor:Linux/Gafgyt.AF!MTB|Trojan.Linux.GenericA.73451|
Microsoft|DDoS:Linux/Gafgyt.YA!MTB|Trojan.ElfArm32.Tsunami.ejtrus|Backdoor:Linux/Gafgyt.AF!MTB|
NANO-Antivirus|Trojan.ElfArm32.Mirai.fkvjsm|False Positive|Trojan.ElfArm32.Gafgyt.emzwvw|
Panda|False Positive|Linux/Backdoor.9d5|False Positive| 
Qihoo-360|Linux/Backdoor.812|Trojan.Gafgyt/Linux!1.A480 (CLASSIC)|Linux/Trojan.DDoS.adc|
Rising|Backdoor.Mirai/Linux!1.BAF6 (CLASSIC)|Undetected|Backdoor.Gafgyt/Linux!1.A512 (CLASSIC)|
SUPERAntiSpyware|False Positive|False Positive|False Positive| 
Sangfor|False Positive|Linux/Tsunami-A|Malware.ELF-Script.Save.07a8c2d7|
Sophos|Linux/DDoS-CIA|Trojan.Gen.NPE|Linux/DDoS-BI|
Symantec|Trojan.Gen.NPE|False Positive|Linux.Lightaidra|
TACHYON|False Positive|Backdoor.Linux.Gafgyt.ya|False Positive| 
Tencent|Backdoor.Linux.Gafgyt.ff|False Positive|Backdoor.Linux.Gafgyt.ym|
TotalDefense|False Positive|Backdoor.Linux.BASHLITE.SMJC|False Positive| 
TrendMicro|Backdoor.Linux.BASHLITE.SMJC|Backdoor.Linux.BASHLITE.SMJC|Backdoor.Linux.BASHLITE.SMJC|
TrendMicro-HouseCall|Backdoor.Linux.BASHLITE.SMJC|Undetected|Backdoor.Linux.BASHLITE.SMJC|
VBA32|False Positive|False Positive|False Positive| 
VIPRE|False Positive|False Positive|False Positive| 
ViRobot|False Positive|False Positive|False Positive| 
Yandex|False Positive|Backdoor.Tsunami.Linux.379|False Positive| 
Zillya|Backdoor.Mirai.Linux.38039|HEUR:Backdoor.Linux.Tsunami.bh|False Positive| 
ZoneAlarm|HEUR:Backdoor.Linux.Gafgyt.a|False Positive|HEUR:Backdoor.Linux.Gafgyt.ac|
Zoner|False Positive|False Positive|False Positive| 


## Materials and Methods

This paper proposes a database aiming at the classification of Google Chrome's extensions(CRX file) benign and malware. There are 22 malicious executables, and 990 other benign executables.

The proposed work employs a strategy inspired by \linebreak biomedical engineering work. In health care, the presence of an abnormality (e.g. cancer) occurs every thousand diagnoses of healthy patients. The biomedical strategy consists in repeating the training according to the ratio between the majority and minority class (22:990 = 45 iterations). In our work, at each iteration, a new package from the majority class is presented to the minority class (22:22). This ensures that biased classifiers are not favored. This also maintains the diversity of samples from the majority class, contained in our dataset. 

Still about methodological precautions taken by state-of-the-art biomedical engineering. We reserve relevant amounts of benign and malware samples in the separate packages for training and testing.  Hypothetically, assume a package reserved for testing with little or no instance of the malware class. In this situation, a classifier biased towards the benign class would have its hit rate favored. We had the methodological care to select random, equal numbers of benign and malicious instances for the training and testing fold. 

For the construction of a pattern recognition AI (artificial intelligence), the conventional method used for its training is the use of classes and counter classes of a certain filetype. The designation chosen to refer to the categories was "benign files" for serious and safe applications and "malignant files" for applications that can be a threat to the user.The virtual plages were extracted from databases made avaiable by enthusiastic groups about the study of malwares through the digital plataform VirusShare. It should be noted that all benign executables were submitted to VirusTotal and all were its benign attested by the main commercial antivirus worldwide. The diagnostics, provided by VirusTotal, corresponding to the benign and malware executables are available in the virtual address of our database.

On a machine with 16 GB RAM, 4 CPUs, and 300 GB of storage, all experiments were carried out. There is therefore no unjust comparison. Private antivirus companies train and test cutting-edge antivirus on supercomputers.

The processing and storage requirements for the author's antivirus program are extremely low. The fact that the original antivirus may be used on any conventional desktop PC must be emphasized.


## Dynamic Feature Extraction

The features of CRX files are derived from dynamic analysis of suspicious files. Thus, in our approach, the malware is run to intentionally infect the Windows 7 in real-time  from the Cuckoo Sandbox. A total of 1,098 signatures relevant to monitoring suspicious files in the proposed controlled environment are generated from each CRX file. To make it easier to understand input layer neurons, our repository extends the description of properties checked by author antivirus.
The following describes the functional groups in detail:


######	Virtual machine related functions. The purpose is to verify that the checked file search detects  Sandboxie, VirtualBox, VirtualPC, VMware, Xen or Parallels VM. This by the presence of registry keys (regedit), files, directives and used device drivers.
	
######	Bitcoin related functions. We check if the test file tries to install the OpenCL library, the Bitcoin mining tool.
	
######	Robot-related functions (machines that perform automated network tasks, malicious or not, without the knowledge of their owners). 

######	Browser related functions. Checks if the file attempted to:

######	Features related to packing and obfuscation. The proposed digital forensic verifies if the suspect file:
-	alter browser security settings;
-	alter the browser home page;
-	obtain private information from locally installed internet browsers;
	
######	Features related to persistence, functionality of backup information in a system, without the need to register them before. Our Sandbox audit if suspicious file tries to:
-	create an ADS (Alternate Data Stream), NTFS feature that contains information to locate a specific file by author or title, used maliciously because as the information that is present in it does not change the characteristics of the file associated with it, transform them into an ideal option for building rootkits, because they are hidden (steganography);
-	install a self-executing in startup (autorun);
-	install a native executable to run at the beginning of GNU/Linux boot.

######	Firewall related functions. The suggested digital forensics analysis files that attempts to modify local firewall policies. 

######	Cloud computing related functions. We monitor files when trying to connect to storage services or files from Dropbox, Google, MediaFire, MegaUpload, RapidShare, Cloudflare, and WeTransfer. 

######	Features that seek to disable features of GNU/Linux and other utilities. The audit checks to see if the file can:

-	modify system policies to prevent the launch of specific applications or executables;
-	disable browser security warnings;
-	disable GNU/Linux security features and properties;
-	disable google SPDY network protocol support in Mozilla Firefox browsers to increase the ability of an internet malware to gain access to sensitive information;
-	disable system restore;

######	Function designed to disable Windows 7 operating system and other utility features. Our audit checks determine the file attempts: 

-	alter system policies to prevent the launch of specific applications or executables; 
-	deactivate browser security warnings;
-	disable Windows security features and properties.

######	Functions related to network traffic under the Windows 7 operating system in  PCAP format.

######	Windows 7 OS-related functions (regedit): 
-	changes in the association between the file extension and the software installed on the computer; 
-	change the current user information;
-	driver corrupt;
-	alter to Windows appearance settings and user settings, such as wallpapers, screensavers and themes;
-	change hardware settings.

######	Functions related to using the sandbox. Digital forensics investigated whether the file tried to turn off a Windows feature monitored by Cuckoo Sandbox.
-	It is audited if the suspect application tries to create or modify system certificates, security center warnings, user account control behaviors, desktop wallpaper, or ZoneTransfer.ZoneID values in the ADS(Alternate Data Stream).

######	Ransomware-related functionality (a malware that uses encryption to make a victim's files unusable and then asks for a refund in trade for normal use of the user's files; the refund is usually paid in some untraceable form, such as Bitcoin).

######	Functions related to exploit-related functions representing malware that attempts to make use of known or unpackaged vulnerabilities, bugs, or flaws in the system. Making so that one or more of system components may cause unforeseen instability and behavior of hardware and software.

######	Functions related to information stealers, malicious programs that collect sensitive information from affected computers. 

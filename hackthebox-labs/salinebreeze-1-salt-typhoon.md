# SalineBreeze-1 (Salt Typhoon)

- Link to Sherlock ⇒ [https://app.hackthebox.com/sherlocks/SalineBreeze-1](https://app.hackthebox.com/sherlocks/SalineBreeze-1)
- Category: Threat Intelligence
- Objective: Gather information about Salt Typhoon, the nation-state cyber attacker, using open sources available on the Internet.

### Scenario

Your manager has just informed you that, due to recent budget cuts, you'll need to take on additional responsibilities in threat analysis. As a junior threat intelligence analyst at a cybersecurity firm, you're now tasked with investigating a cyber espionage campaign linked to a group known as Salt Typhoon. Apparently, defending against sophisticated Nation-State cyber threats is now a "do more with less" kind of game. Your Task: Conduct comprehensive research on Salt Typhoon, focusing on their tactics, techniques, and procedures. Utilize the MITRE ATT&CK framework to map out their activities and provide actionable insights. Your findings could play a pivotal role in fortifying our defenses against this adversary. Dive deep into the data and show that even with a shoestring budget, you can outsmart the cyber baddies.

---

### OSINT Resources Used to Solve The Sherlock

- https://attack.mitre.org/groups/G1045/
- https://www.trendmicro.com/en_au/research/24/k/earth-estries.html
- https://www.picussecurity.com/resource/blog/salt-typhoon-telecommunications-threat
- https://cybersecsentinel.com/earth-estries-uses-ghostspider-malware-to-infiltrate-high-value-targets/?utm_source=chatgpt.com
- https://securelist.com/ghostemperor-from-proxylogon-to-kernel-mode/104407/

---

### Sherlock Reflection

This was my first Sherlock challenge related to threat intelligence. The task required me to investigate *Salt Typhoon*, a specific nation-state cyber threat group, by leveraging publicly available open-source materials. As I worked through each task, I learned how to extract useful intelligence from authoritative resources such as the **MITRE ATT&CK framework**. I also encountered familiar concepts like CVEs and malware—topics I had studied for the Security+ certification. Facing these concepts in a practical, hands-on scenario not only deepened my understanding but also reinforced them in my memory.

⭐ The most valuable aspect of this Sherlock was the opportunity to study ***Salt Typhoon***, a nation-sponsored threat actor linked to the People's Republic of China. I found it particularly striking how they carried out sophisticated campaigns targeting major U.S. telecommunications companies and ISPs, employing a wide range of attack vectors.

❓ One question that arose during my research was the diplomatic dimension: given that *Salt Typhoon* operates from China and directly targets U.S. entities, how are such activities perceived in the context of international relations and **cyber diplomacy**?

📈 If there was one drawback, it would be that the challenge felt too easy, which aligned with its “Very Easy” difficulty rating. In most cases, the answers could be found directly within the provided blog articles or related online sources. I would have preferred questions that required me to synthesise the given materials and apply an additional layer of reasoning, as that would have been more effective in broadening my perspective. For future threat intelligence Sherlocks, I hope to select more challenging exercises that demand **deeper insight and critical thinking.**

<details>
<summary>Korean Version</summary>
    
    이것은 내 첫번째 threat intelligence 에 관한 sherlock 이었다. 인터넷에 퍼블릭으로 올라와있는 오픈 소스 자료들을 활용하여 salt typhoon 이라는 특정 nation-state 사이버 공격 집단을 조사하는 작업을 하였다. Tasks들을 차례로 풀어 나가며 MITRE ATT&CK 같은 공신력있는 사이트에서 유용한 정보를 빼내는 방법을 익힐 수 있었다. Security+ 자격증을 준비하면서 공부했던 CVE나 Malware 같은 친숙한 컨셉을 다루기도 했는데, 이론적으로 배웠던 것을 이렇게 실전으로 마주하니 이해가 쉽고 이 컨셉들이 내 뇌속에 더욱 굳혀진 느낌이다.
    
    또한 Salt Typhoon 이라는 중국 공산당 기반의 Nation-Sponsered 공격자 집단에 대해 공부할 수 있다는 것이 이 셜록의 가장 큰 장점이었다. US의 주요 tellecommunication and ISP 회사들을 타겟으로 정말 정교하고 다양한 attack vectors 를 활용하여 공격을 펼치는 점이 인상적이었다.
    
    하나 궁금했던 점은, 이 공격자는 중국으로부터의 nation state actor 이고, 정확이 US의 회사들을 타겟하는데, 혹시 외교적으로는 이슈가 있진 않은가 하는 것이었다. (cyber diplomacy)
    
    한가지 아쉬운 점이 있다면, 이 셜록은 난이도 Very Easy답게 문제의 난이도가 전체적으로 너무 쉬웠다는 점이다. 대부분의 문제의 답을 주어진 blog article 이나 관련 인터넷 사이트들에서 다이렉트로 쉽게 찾을 수 있었다. 주어진 자료를 기반으로 하고, 내가 한번 더 생각을 거쳐야 하는 문제들이었으면 내 시야를 더욱 넓혀주는것에 효과적이었을텐데. 다음에 threat intelligence 관련 셜록을 풀 때는 조금 더 난이도가 있는 것을 골라서, 내 통찰력과 critical thingking 을 요구하는 문제를 풀어보고 싶다.

</details>
    

---

### Tasks & Answers

**Task 1.** Starting with the MITRE ATT&CK page, which country is thought be behind Salt Typhoon?

`China`

**Task 2.** According to that page, Salt Typhoon has been active since at least when? (Year)

`2019`

**Task 3.** What kind of infrastructure does Salt Typhoon target?

`Network`

**Task 4.** Salt Typhoon has been associated with multiple custom built malware, what is the name of the malware associated with the ID S1206?

`JumbledPath`

**Task 5**. What operating system does this malware target?

`Linux`

**Task 6.** What programming language is the malware written in?

`GO`

**Task 7.** On which vendor's devices does the malware act as a network sniffer?

`Cisco`

**Task 8.** The malware can perform 'Indicator Removal' by erasing logs. What is the MITRE ATT&CK ID for this?

`T1070.002`

**Task 9.** On December 20th, 2024, Picus Security released a blog on Salt Typhoon detailing some of the CVEs associated with the threat actor. What was the CVE for the vulnerability related to the Sophos Firewall?

`CVE-2022-3236`

**Task 10.** The blog demonstrates how the group modifies the registry to obtain persistence with a backdoor known as Crowdoor. Which registry key do they target?

`HKCU\Software\Microsoft\Windows\CurrentVersion\Run`

**Task 11.** What is the MITRE ATT&CK ID of the previous technique?

`T1112`

**Task 12.** On November 25th, 2024, TrendMicro published a blog post detailing the threat actor. What name does this blog primarily use to refer to the group?

`Earth Estries`

**Task 13.** The blog post identifies additional malware attributed to the threat actor. Which malware do they describe as a 'multi-modular backdoor...using a custom protocol protected by Transport Layer Security'

`GhostSpider`

**Task 14.** Most of the domains the malware communicates with have a .com top-level domain. One uses a .dev TLD. What is the full domain name for the .dev TLD?

`telcom.grishamarkovgf8936.workers.dev`

**Task 15.** What is the filename for the first GET request to the C&C server used by the malware?

`index.php`

**Task 16.** On September 30th, 2021, a blog post was released on Securelist by Kaspersky. What was the threat actor's name at that time?

`GhostEmperor`

**Task 17.** What is the name of the malware that this article focuses on?

`Demodex`

**Task 18.** What type of malware is the above malware?

`Rootkit`

**Task 19.** The first stage consists of a malicious PowerShell dropper. What type of encryption is used to obfuscate the code?

`AES`

**Task 20.** The malware uses Input/Output Control codes to perform various tasks related to hiding malicious artifacts. What is the IOCTL code used by the malware to hide its service from the list within the services.exe process address space?

`0x220300`
*Half-day workshop on web and software supply chain security*

**Date:** October 31, 2024
**Location:** [Room 1440, KTH](https://www.kth.se/places/room/id/e6d61e30-d6c4-48e4-b6d4-4ee5ed784ff5)

---

## Preliminary Agenda

| **Time**  | **Agenda**                                                                                                                                                                        |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **13:30** | Welcome and Introductions                                                                                                                                                         |
| **14:00** | Talk by [Yinzhi Cao](https://yinzhicao.org/): JavaScript Vulnerability Detection: Two Case Studies on Node.js Template Engine and React Applications                                                       |
| **14:30** | Talk by [Anders Møller](https://cs.au.dk/~amoeller/): Supply Chain Security for JavaScript at [Coana](https://www.coana.tech/)                                                                                                             |
| **15:00** | Talk by [Eric Cornelissen](https://ericcornelissen.dev/): Securing the JavaScript Software Supply Chain                                                                                                           |
| **15:30** | Coffee break                                                                                                                                                                      |
| **16:00** | Talk by [Andrei Sabelfeld](https://www.cse.chalmers.se/~andrei/): Detecting Malicious Browser Extensions Without Even Running Them or Looking at Their Code                                                              |
| **16:30** | Talk by [Ben Stock](https://swag.cispa.saarland/people/benstock.html): About Developer Usability                                                                                                                     |
| **17:00** | Discussion and closing remarks                                                                                                                                                    |

---

---

## Talk Abstracts and Speaker Bios

### Supply Chain Security for JavaScript at Coana, by Anders Møller

**Abstract:**  
JavaScript is one of the most widely used programming languages. Modern software critically relies on reusable, open-source software packages. They enable fast development of advanced applications, but also introduce major challenges with security vulnerabilities and breaking changes. In this talk, I will describe ongoing work on building new JavaScript program analysis tools that can assist library and application developers by providing accurate information about how dependencies are being used.

**Bio:**  
Anders Møller is a professor at Aarhus University. His main research area is program analysis. He has received a Consolidator Grant from the European Research Council (ERC), the Danish Elite Research Prize 2020, and seven times a Distinguished Paper Award from ACM SIGSOFT or SIGPLAN. He is an ACM Distinguished Member, vice-chair of ACM SIGPLAN, and associate editor of ACM TOPLAS and ACM TOSEM. Together with former PhD students, he is the co-founder of [Coana](https://coana.tech), which aims to make software more robust and secure using program analysis technology.

---

### Detecting Malicious Browser Extensions Without Even Running Them or Looking at Their Code, by Andrei Sabelfeld

**Abstract:**  
Browser extensions represent a critical yet often overlooked component of the web software supply chain. Similar to smartphone app stores, browsers like Chrome distribute browser extensions via their Web Store, enabling a thriving market of third-party developed extensions. Unfortunately, the open nature of the review system is subject to reputation manipulation. This talk presents FakeX, a framework that detects fake reviews by focusing on inference from review metadata. FakeX employs methods such as temporal distribution analysis and relationship clustering to unveil patterns indicative of fake reviews. Our evaluation reveals FakeX's effectiveness in identifying fake review campaigns and uncovering malicious extensions affecting millions of users.

**Bio:**  
Andrei Sabelfeld is a Professor at Chalmers University of Technology, Visiting Professor at KTH, and previously a Researcher at Cornell University. His research spans software security, web security, IoT security, and applied cryptography. He has received numerous awards from ERC, KAW, SSF, VR, WASP, and others.

---

### Securing the JavaScript Software Supply Chain, by Eric Cornelissen

**Abstract:**  
Node.js is the most popular runtime for server-side JavaScript, with the npm registry serving as its primary source of reusable packages. This vast ecosystem introduces a supply chain risk. This work provides a developer-friendly runtime hardening for Node.js applications against supply chain attacks through the combination of a Software Bill Of Materials (SBOM) and a new extension, CapabilityBOM. CapabilityBOM formalizes practices that help developers make informed choices about what their dependencies are allowed to do.

**Bio:**  
Eric Cornelissen is a PhD student at the KTH Royal Institute of Technology specializing in Supply Chain Security under the supervision of Musard Balliu. His research focuses on both offensive and defensive security in the JavaScript ecosystem, with work on prototype pollution, runtime hardening, and DOM clobbering.

---

### About Developer Usability, by Ben Stock

**Abstract:**  
TBD

**Bio:**  
Ben Stock is a tenured faculty at the CISPA Helmholtz Center for Information Security in Saarbrücken, Germany. He leads the Secure Web Application Group, focusing on web and network security, particularly (un)usability of security mechanisms. His group regularly publishes at major security conferences, and Ben serves on the PC and in chair roles for various conferences. Beyond academic research, he engages with practitioners through talks at conferences like OWASP AppSec and Ruhrsec.

---

### JavaScript Vulnerability Detection: Two Case Studies on Node.js Template Engine and React Applications, by Yinzhi Cao

**Abstract:**  
This talk will cover JavaScript vulnerability analysis over the past six years, resulting in 400+ zero-day vulnerabilities, 2,500+ vulnerable websites, and 30+ prototype pollution chains. We present two approaches: Undefined-oriented Programming Framework (UoPF) for Node.js template engines and ReactAppScan for React.js applications. UoPF detects vulnerabilities via concolic execution with undefined properties as symbols, while ReactAppScan uses a Component Graph (CoG) for tracking React Data Flow vulnerabilities.

**Bio:**  
Yinzhi Cao is an associate professor at Johns Hopkins University and Technical Director of the JHU Information Security Institute. His research focuses on security and privacy of the Web, smartphones, and machine learning using program analysis. He has received multiple awards, including the NSF CAREER Award 2021 and DARPA Director's Fellowship Award 2024.

---

**Contact:**
For more information, please contact **Musard Balliu** at **musard@kth.se** .


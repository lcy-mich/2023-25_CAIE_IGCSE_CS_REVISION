# **CAIE IGCSE Computer Science (0478) Revision guide/ notes for 2023-25 syllabus**

## **_forewords_**

i am writing this as of two days before my first computer science exam. behold, the inscrutable scramble of information by a desperate nutter 🙀.

most of the information given and notes are from the _Cambridge IGCSE and O Level Computer Science Second Edition textbook published by Hodder Education_ and from personal research guided by the 2023-25 Cambridge Assessment Internation Education syllabus. _Any extra-curricular information will be noted as such with sources provided at the end of that particular section of text_

> ⚠ becareful that the revision guides you find and use online are up to date, many are still using the old syllabus rather than te 2023-25 syllabus

- [🔗 link to the CAIE IGCSE Computer Science 2023-25 syllabus](https://www.cambridgeinternational.org/Images/595424-2023-2025-syllabus.pdf)

- [🔗 link to CAIE IGCSE CS Revision notes on www.savemyexams.co.uk (i believe at the moment of me writing this, they have not mentioned databases)](https://www.savemyexams.co.uk/igcse/computer-science/cie/23/revision-notes/)

- [🔗 link to 2023 CAIE IGCSE CS specimen papers on the cambridge site](https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-computer-science-0478/past-papers/)

- [🔗 link to znotes revision guide (⚠ they are missing the final topic "boolean logic")](https://znotes.org/caie/igcse/computer-science-0478/)


> this guide is designed to be **self-contained**; to reduce the need to search far and wide for information, and to that affect, if you find that you need to search elsewhere for clarifications, add an issue to the repo about it!

> any other addendums, edits or clarifications are welcome, contribute as you please!

now that's out of the way:

# contents
#### **insa ala pi lipu sona**
- [assessment information 🥰](#assessment-information-🥰)
    - [changes to the syllabus 😖](#changes-to-the-syllabus-😖)
    - [papers 🤓](#papers-🤓)
    - [command words 💀](#command-words-💀)
    - [assessment objectives 🤗](#assessment-objectives-🤗)
    - [mathematical requirements 🤢](#mathematical-requirements-🤢)

#### **insa pi lipu sona**
#### *theory / computer systems*
1. [data representation](#1-data-representation)
    <br>
    1.1 [number systems](#11-number-systems)
    <br>
    1.2 [text, sound and images 😎](#12-text-sound-and-images-😎)
    <br>
    1.3 [data storage and compression 🥶](#13-data-storage-and-compression-🥶)
2. [data transmission](#2-data-transmission)
    <br>
    2.1 [types and methods of data transmission 😂](#21-types-and-methods-of-data-transmission-😂)
    <br>
    2.2 [methods of error detection 🙈](#22-methods-of-error-detection-🙈)
    <br>
    2.3 [encryption 👯‍♀️](#23-encryption-👯‍♀️)
3. [hardware](#3-hardware)
    <br>
    3.1 [computer architecture 💻](#31-computer-architecture-💻)
    <br>
    3.2 [input and output devices 🔔](#32-input-and-output-devices-🔔)
    <br>
    3.3 [data storage 🥱](#33-data-storage-🥱)
    <br>
    3.4 [network hardware 😚](#34-network-hardware-😚)
4. [software](#4-software)
    <br>
    4.1 [types of software and interrupts 🤐](#41-types-of-software-and-interrupts-🤐)
    <br>
    4.2 [types of programming language, translators and integrated development environments (IDEs) 🤓](#42-types-of-programming-language-translators-and-integrated-development-environments-ides-🤓)
5. [the internet and its uses](#5-the-internet-and-its-uses)
    <br>
    5.1 [the internet and the world wide web 🤯](#51-the-internet-and-the-world-wide-web-🤯)
    <br>
    5.2 [digital currency 🤑](#52-digital-currency-🤑)
    <br>
    5.3 [cyber security 👾](#53-cyber-security-👾)
6. [automated and emerging technologies](#6-automated-and-emerging-technologies)
    <br>
    6.1 [automated systems 🤗](#61-automated-systems-🤗)
    <br>
    6.2 [robotics 🤣](#62-robotics-🤣)
    <br>
    6.3 [artificial intelligence 💩](#63-artificial-intelligence-💩)

#### *algorithms, programming and logic*
- [some information](#some-information)
    - [flowchart symbols](#flowchart-symbols)
    - [logic gate symbols](#logic-gate-symbols)
7. [algorithm design and problem-solving](#7-algorithm-design-and-problem-solving)
8. [programming](#8-programming)
    <br>
    8.1 [programming concepts 😫](#81-programming-concepts-😫)
    <br>
    8.2 [arrays 👨‍❤️‍💋‍👨](#82-arrays-👨‍❤️‍💋‍👨)
    <br>
    8.3 [file handling 🤏](#83-file-handling-🤏)
9. [databases](#9-databases)
10. [boolean logic 🤪](#10-boolean-logic-🤪)

# assessment information 🥰
[[🤡 elevator back to contents]](#contents)

---

## changes to the syllabus 😖

_i've removed some changes that i've deemed irrelevant. for the entire changes to syllabus content, check page 53 of [new syllabus](https://www.cambridgeinternational.org/Images/595424-2023-2025-syllabus.pdf)_

| changes to syllabus content | changes to assessment |
| --- | --- | 
| structure of subject content, updated for coherency | wording of assessment objectives, updated for clarity |
| learning objectives, updated for clarity | Paper 1 Theory renamed to *Paper 1 Computer Systems*|
| ethics topic has been removed (morals are no more) | Paper 2 Problem-solving and Programming renamed to *Paper 2 Algorithms, Programming and Logic*|
| robotics, artificial intelligence and 2D arrays are added to topics | both papers are now weighted at 50% and Paper 2 now has 75 marks |
| boolean logic will be in paper 2 now | no more pre-release material for paper 2. teplaced by unseen scenario question |
| pseudocode guide has been revised | scenario question will be worth 15 marks. you write an algorithm in either pseudocode or program code and expected to spend half an hour doing it. it will always be the final question |

---

## papers 🤓
You are not allowed calculators in either test and both are 1 hour 45 minutes long

There are **2** papers, **they are both equally weighted**:

| Paper 1 | Paper 2 |
| ------- | ------- |
| **Computer systems** _(used to be just 'theory')_ | **Algorithms, Programming and Logic** _(used to be just 'Problem-solving and Programming')_|
| 1 hour 45 minutes | 1 hour 45 minutes |
| 75 marks _(50% of the IGCSE)_ | 75 marks _(50% of the IGCSE)_|
| short and structured questions | short, structured questions and one scenario-based |
| topics **1-6** of subject content | topic **7-10** of subject content |
| no calculators allowed | no calculators allowed |
| externally assessed | externally assessed | 

---

## command words 💀
|  term  | definition |
| ------ | ------- |
| calculate | work out from *given* information |
| compare | comment on similarities and differences |
| define | give precise meaning |
demonstrate | show how/ give example
| describe | give characteristics and main features |
| evaluate | judge the importance/ quality of something
| explain | give reasons/ relationships between things and support it with evidence |
| give | produce answer from memory or given information |
| identify | name/select/recognise |
| outline | give main points |
| show (that) | give structured evidence leading to the given result |
| state | express in clear terms |
| suggest | apply knowledge to situation with a variety of valid responses |

---

## assessment objectives 🤗

| AO1 | AO2 | AO3 |
| --- | --- | --- |
| demonstrate understanding of concepts in computer science *(basically just: be able to recall knowledge)* | apply understanding of concepts to a given context, including analysis and design of problems *(basically just: apply your knowledge)* | provide solutions by evaluating computer systems, making reasoned judgements, and presenting conclusions *(basically just: analyse and give solution, give reasons, present conclusion)* |

### <ins>weighting for assessment objectives</ins>

#### AO as percentage of qualification
| assessment objective | weighting in IGCSE % |
| --- | --- |
| AO1 | 40 |
| AO2 | 40 |
| AO3 | 20 |
| Total | 100 |

#### AO as percentage of each component
| assessment objective | weighting in components % | |
| --- | --- | --- |
|  | Paper 1 | Paper 2 |
| AO1 | 60 | 20 |
| AO2 | 20 | 60 |
| AO3 | 20 | 20 |
| Total | 100 | 100|

---

## mathematical requirements 🤢

calculators are **not** allowed in the exams

you should be able to:
- add, subtract, multiply and divide
- use averages, random numbers, decimals, fractions, percentages and ratios
- use both positive and negative integers and real numbers (all the numbers including the ones with decimal places)
- use arithmetic and boolean operators
- use different number systems (binary, denary and hexadecimal)
- use methods of counting (number of something), totalling (sum of numbers) and rounding (round up and down numbers)


---

# **subject content 🤡** 

# 1. data representation
[[🤡 elevator back to contents]](#contents)

---

## 1.1 number systems 😋

---

## 1.2 text, sound and images 😎

---

## 1.3 data storage and compression 🥶


# 2. data transmission
[[🤡 elevator back to contents]](#contents)

---

## 2.1 types and methods of data transmission 😂

---

## 2.2 methods of error detection 🙈

---

## 2.3 encryption 👯‍♀️

---

# 3. hardware
[[🤡 elevator back to contents]](#contents)

---

## 3.1 computer architecture 💻

---

## 3.2 input and output devices 🔔

---

## 3.3 data storage 🥱

---

## 3.4 network hardware 😚

---

# 4. software
[[🤡 elevator back to contents]](#contents)

---

## 4.1 types of software and interrupts 🤐

---

## 4.2 types of programming language, translators and integrated development environments (IDEs) 🤓

---

# 5. the internet and its uses
[[🤡 elevator back to contents]](#contents)

---

## 5.1 the internet and the world wide web 🤯

---

## 5.2 digital currency 🤑

---

## 5.3 cyber security 👾

---

# 6. automated and emerging technologies
[[🤡 elevator back to contents]](#contents)

---

## 6.1 automated systems 🤗

---

## 6.2 robotics 🤣

---

## 6.3 artificial intelligence 💩

---

# **paper 2 content: Algorithms, programming and logic**

### **some information :**
- you should program solutions using either pseudocode or one of these high-level programming languages: Python, VB.NET or Java

- you must use the standard flowchart symbols outlined in the syllabus

- you must use the standard logic gate symbols outlined in the syllabus

- you must use the standard pseudocode outlined in the syllabus

- the scenario question at the end of the paper is worth 15 marks and you should spend half an hour on it

### **flowchart symbols**

![flowchart symbols (page 33 of syllabus)](/assets/flowchart.png)

### **logic gate symbols**

![logic gates symbols (page 34 of syllabus)](/assets/logic_gates.png)



# 7. algorithm design and problem-solving
[[🤡 elevator back to contents]](#contents)

---

# 8. programming
[[🤡 elevator back to contents]](#contents)

---

## 8.1 programming concepts 😫

---

## 8.2 arrays 👨‍❤️‍💋‍👨

---

## 8.3 file handling 🤏

---

# 9. databases
[[🤡 elevator back to contents]](#contents)

---

# 10. boolean logic 🤪
[[🤡 elevator back to contents]](#contents)

---

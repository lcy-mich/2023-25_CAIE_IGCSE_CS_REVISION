# **CAIE IGCSE Computer Science (0478) Revision guide/ notes for 2023-25 syllabus**

## **_forewords_**

i am writing this as of two days before my first computer science exam. behold, the inscrutable scramble of information by a desperate nutter 🙀.

most of the information given and notes are from the _Cambridge IGCSE and O Level Computer Science Second Edition textbook published by Hodder Education_ and from personal research guided by the 2023-25 Cambridge Assessment Internation Education syllabus. _Any extra-curricular information will be noted as such with sources provided at the end of that particular section of text_

- [🔗 link to the CAIE IGCSE Computer Science 2023-25 syllabus](https://www.cambridgeinternational.org/Images/595424-2023-2025-syllabus.pdf)

- [🔗 link to CAIE IGCSE CS Revision notes on www.savemyexams.co.uk (at the moment of writing this, they are missing topics 7,9,10)](https://www.savemyexams.co.uk/igcse/computer-science/cie/23/revision-notes/)

- [🔗 link to 2023 CAIE IGCSE CS specimen papers on the cambridge site](https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-computer-science-0478/past-papers/)

- [🔗 link to znotes revision guide (they are missing the final topic "boolean logic")](https://znotes.org/caie/igcse/computer-science-0478/)

> *⚠ becareful that the revision guides you find and use online are <ins>**up to date**</ins>, many are still using the old syllabus rather than the 2023-25 syllabus.*

> *⚠ some online revision guides you find are <ins>**missing topics in the syllabus, so always double check!**</ins>*

> *⚠ this guide is designed to be **self-contained**; to reduce the need to search far and wide for information. please do still use the textbook as I may omit or forget sections, in which case, if you find that you need to search elsewhere for clarifications, or realised that I missed an important section, issue an issue on the repo about it!*

any other addendums, edits or clarifications are welcome, contribute as you please!

answers to practice questions will be at the end of the topic chapters (it will also be linked under the questions)

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
1. [data representation 😴](#1-data-representation)
    <br>
    1.1 [number systems](#11-number-systems)
        <br>
        &emsp;1.1.1 [how and why binary?](#111-how-and-why-computers-use-binary-to-represent-data)
        <br>
        &emsp;1.1.2 [number systems](#112-binary-denary-and-hexadecimal)
        <br>
        &emsp;1.1.3 [how and why hex?](#113-how-and-why-we-use-hexadecimal-to-represent-data)
        <br>
        &emsp;1.1.4 [binary addition](#114-binary-addition)
        <br>
        &emsp;1.1.5 [logical binary shifts](#115-logical-binary-shifts)
        <br>
        &emsp;1.1.6 [negative binary numbers](#116-twos-complement-and-negative-binary-numbers)
        <br>
        &emsp;• [exam style questions](#1.1-exam-style-questions)
    <br>
    1.2 [text, sound and images 😎](#12-text-sound-and-images-😎)
        <br>
        &emsp;1.2.1 [text 😬](#121-text)
        <br>
        &emsp;1.2.2 [sounds 📢](#122-sounds)
        <br>
        &emsp;1.2.3 [images 🖼](#123-images)
        <br>
        &emsp;• [exam style questions](#1.2-exam-style-questions)
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

## **1.1 number systems 😋**

### **<ins>learning objectives</ins>**

| learning objectives | notes and guidance |
| --- | --- |
|1. understand how and why computers use binary to represent data | • data needs to be converted to binary to be processed by a computer <br> • data is processed with logic gates and stored in registers |
|2. (a) understand denary, binary and hexadecimal | • denary is base 10 <br> • binary is base 2 <br> • hexadecimal is base 16 |
|(b) convert between:<br>(i) positive denary and binary<br>(ii) positive denary and hexadecimal<br>(iii) positive hexadecimal and binary | • values used will be integers only <br> • conversions in both directions, e.g. denary to binary or binary to denary <br> • maximum binary number length of 16-bit |
|3. understand how and why hexadecimal is used to represent data | • areas in computer science that uses hexadecimal should be identified, e.g. memory dumps <br> • hexadecimal is easier to understand because it is shorter |
|4. (a) add two positive 8-bit binary integers | |
|(b) understand what is overflow and why it occurs in addition | • overflow error will occur if value is greater than 255 in an 8-bit register <br> • computers have predefined limit that it can store/ represent, e.g. 16-bit <br> • overflow error occurs when value outside this limit should be returned |
|5. perform logical binary shifts on positive 8-bit binary integer and understand the effects | • perform logical left and right shifts <br> • bits shifted from the end of register are lost and zeros are shifted in at opposite end of register <br> • positive binary integer is multiplied or divided according to shift performed |
| 6. use two's complement to represent positive and negative 8-bit binary integers | • convert positive binary/ denary integer to a two's complement 8-bit integer and vice versa <br> • convert negative binary/ denary integer to two's complement 8-bit integer and vice versa |

---

### **<ins>1.1.1 how and why computers use binary to represent data</ins>**

- all data needs to be converted into a binary format to be processed by the computer
- this is because it only consists of 1s and 0s and computers use switches (transistors) that are either ON or OFF.
- the 1s and 0s are called **bits**. which is short for **binary digits**
- bits can be grouped into larger units of data such as bytes (8 bits), kilobytes (1000 bytes), kibibytes (1024 bytes), etc.
- switches (transistors) are used to make use of [logic gates](#10-boolean-logic-🤪) which performs logical operations on binary data
- they are also used to store and process data

### **<ins>1.1.2 binary, denary and hexadecimal</ins>**

- we denote the used number system with subscripts (why? because maths.)

### denary

- denary is a base-10 number system
- denary is the number system people usually use. numbers such as 420<sub>10</sub> or 69<sub>10</sub>
- denary uses 10 digits to represent numbers: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9
- after 9, we add 1 to the digit on the left and start over from 0
- each digit in a denary number represents a power of 10

to represent the number 80085<sub>10</sub> we can use a grid

|10 000| 1 000 | 100 | 10 | 1 |
| ---- | ----- | --- | -- | - |
| 10<sup>4</sup> | 10<sup>3</sup> | 10<sup>2</sup> | 10<sup>1</sup> | 10<sup>0</sup> |
| 8 | 0 | 0 | 8 | 5 |

every time the digit hops left, you add one to the power of 10.

we then add them all together to get the number:

8\*10<sup>4</sup> + 0\*10<sup>3</sup> + 0\*10<sup>2</sup> + 8\*10<sup>1</sup> + 5\*10<sup>0</sup> = 80085<sub>10</sub>

### binary

for binary we can do something similar
- binary is a base-2 number system, hence, **bi**-nary (*bi* meaning two)
- in programming, 0b is added at the start to denote a number to be binary ([not in the syllabus](https://en.wiktionary.org/wiki/0b))
- binary is the number system computers are able to use. numbers such as 000110100100<sub>2</sub> or 01000101<sub>2</sub>
- binary uses 2 digits to represent numbers: 0, 1
- after 1, we add 1 to the digit on the left and start over from 0
- each digit in a binary number represents a power of 2

to represent the number 69<sub>10</sub> in binary, we can use a grid

| 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
| --- | -- | -- | -- | - | - | - | - |
| 2<sup>7</sup> | 2<sup>6</sup> | 2<sup>5</sup> | 2<sup>4</sup> | 2<sup>3</sup> | 2<sup>2</sup> | 2<sup>1</sup> | 2<sup>0</sup> |
|0|1|0|0|0|1|0|1|

every time the digit hops left, you add one to the power of 2.

so 69<sub>10</sub> in binary is 01000101<sub>2</sub>

to convert binary back to denary, we then add them all together to get the denary number:

0*2<sup>7</sup> + 1\*2<sup>6</sup> + 0\*2<sup>5</sup> + 0\*2<sup>4</sup> + 0\*2<sup>3</sup> + 1\*2<sup>2</sup> + 0\*2<sup>1</sup> + 1\*2<sup>0</sup> = 69<sub>10</sub>

### hexadecimal

- hexadecimal is a base-16 number system. hexa- meaning six and decimal meaning ten. what's six plus ten? oh wow its 16!
- in programming, 0x is added at the start to denote a number to be hexadecimal ([not in the syllabus](https://en.wiktionary.org/wiki/0x))
- it is also referred to as 'hex'
- hexadecimal is the number system computer scientists use, as binary can be long and hard to read. hex numbers look like: A0E25<sub>16</sub>
- hexadecimal uses 16 digits to represent numbers: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F
- after F, we add 1 to the digit on the left and start over from 0
- each digit in a hexadecimal number represents a power of 16

to represent the number 42069<sub>10</sub> in hex, we can use a grid

| 4096 | 256 | 16 | 1 | 
| ---- | --- | -- | - |
| 16<sup>3</sup> | 16<sup>2</sup> | 16<sup>1</sup> | 16<sup>0</sup> |
| A   |  4 | 5 | 5 |

every time the digit hops left, you add one to the power of 16

so 42069<sub>10</sub> in hexadecimal is A455<sub>16</sub>

### hexadecimal conversion to binary tips

- as 16 is 2 to the power of 4, you can split a binary number by 4 bits to convert into hexadecimal
- so 01000101<sub>2</sub> becomes 0100<sub>2</sub> and 0101<sub>2</sub>
- we can then convert those two 4-bit binary numbers into hex

so
| 8 | 4 | 2 | 1 |
| - | - | - | - |
| 2<sup>4</sup> | 2<sup>3</sup> | 2<sup>2</sup> | 2<sup>1</sup> | 2<sup>0</sup> |
|0|1|0|1|

= 5

and
| 8 | 4 | 2 | 1 |
| - | - | - | - |
| 2<sup>4</sup> | 2<sup>3</sup> | 2<sup>2</sup> | 2<sup>1</sup> | 2<sup>0</sup> |
|0|1|0|0|

= 4

this means 01000101<sub>2</sub> = 45<sub></sub>

---

### **<ins>1.1.3 how and why we use hexadecimal to represent data</ins>**

- computers can only work with binary data, but we use hexadecimal to represent it as it is more convenient.
- a long binary number such as 01000010000011111010110111101101<sub>2</sub> can be represented as 420FADED<sub>16</sub>
- it is easier to remember, copy, read and work with
- there are many uses of hex, such as:
    - error codes
    - MAC addresses
    - IPv6 addresses
    - HTML colour codes
    - memory dumps
    - memory addresses

### error codes

- error codes are often represented by hex
- they refer to the memory location of the error
- programmers learn to interpret them

example of error codes
![windows systems error codes](/assets/error_codes_example.png)

### MAC (Media Access Control) Addresses

- a number that identifies a device on a network
- it is unique
- it refers to the NIC card (network interface card)/ network adapter 
- it is set by the manufacturer
- it is rarely changed
- it is usually made up of 48 bits, shown in 6 groups of 2 hex digits
- there are also 64-bit addresses
- the first half of the MAC address is the ID of the manufacturer
- the second half is the serial number of the device
- it does not change when reconnecting to a network, unlike dynamic IP addresses

examples:
00 - 14 - 22 - 4F - 25 - FE
00 - A0 - C9 - 12 - 90 - A1

### IP (Internet Protocol) addresses

- devices connected to a network is given an IP address.
- there are two versions of IP addresses: IPv4 and IPv6
- IPv4 addresses are 32-bit long and broken into 4 8-bit chunks
- IPv4 addresses are separated with decimals (.)
- usually represented in denary like: 66.254.114.41
- IPv4 only allow for 4 billion addresses and so are running out
- IPv6 addresses are 128-bit long and broken into 8 16-bit chunks
- IPv6 addresses are separated with colons (:)
- IPv6 addresses are represented in hex like: 2606:4700:0020:0000:0000:0000:681A:00EA
- IPv6 addresses can be shortened by removing leading zeros and replacing contiguous 0s with ::
- for example: 2606:4700:0020:0000:0000:0000:681A:00EA becomes 2606:4700:20::681A:EA

![example of ip addresses](/assets/ip_address_example.png)

### HTML (HyperText Mark-up Language) colour codes
- the colour codes are 6 digits long
- it has a pound symbol (#) in front of the digits to denote it being a colour code
- it is split into 3 chunks of 2 digits to represent red, green and blue respectively
- #FF 00 00 is red, #00 FF 00 is green, #00 00 FF is blue
- this means there are 256 shade for red, green and blue
- this means there are 16 million possible colours

![example of colour picker with colour codes displayed](/assets/colour_codes_example.png)

---

### **<ins>1.1.4 binary addition</ins>**

- in denary, when two number added together is greater than 9<sub>10</sub>, we carry a 10<sub>10</sub> over to the next digit
- this occurs similarly in binary

here are the rules:

0<sub>2</sub> + 0<sub>2</sub> = 0<sub>2</sub>

0<sub>2</sub> + 1<sub>2</sub> = 1<sub>2</sub>

1<sub>2</sub> + 0<sub>2</sub> = 1<sub>2</sub>

1<sub>2</sub> + 1<sub>2</sub> = 10<sub>2</sub> (1<sub>2</sub> is carried over to the 2<sub>10</sub><sup>2</sup> place)

here is an example:

01100100<sub>2</sub> + 01110111<sub>2</sub>

| carry bit |   |   |   |   |   |   |   | 0 |
| --------- | - | - | - | - | - | - | - | - |
| first num | 0 | 1 | 1 | 0 | 0 | 1 | 0 | 0 |
|second num | 0 | 1 | 1 | 1 | 0 | 1 | 1 | 1 |
|  result   |   |   |   |   |   |   |   |   |

0<sub>2</sub> + 1<sub>2</sub> = 1<sub>2</sub>
as there are no carry bits, the carry bit of next digit is set to 0

| carry bit |   |   |   |   |   |   | 0 | 0 |
| --------- | - | - | - | - | - | - | - | - |
| first num | 0 | 1 | 1 | 0 | 0 | 1 | 0 | 0 |
|second num | 0 | 1 | 1 | 1 | 0 | 1 | 1 | 1 |
|  result   |   |   |   |   |   |   |   | 1 |

0<sub>2</sub> + 1<sub>2</sub> = 1<sub>2</sub>

| carry bit |   |   |   |   |   | 0 | 0 | 0 |
| --------- | - | - | - | - | - | - | - | - |
| first num | 0 | 1 | 1 | 0 | 0 | 1 | 0 | 0 |
|second num | 0 | 1 | 1 | 1 | 0 | 1 | 1 | 1 |
|  result   |   |   |   |   |   |   | 1 | 1 |

1<sub>2</sub> + 1<sub>2</sub> = 10<sub>2</sub>
as there is a carry bit, the sum value becomes 0 and a carry bit for the next digit is added

| carry bit |   |   |   |   | 1 | 0 | 0 | 0 |
| --------- | - | - | - | - | - | - | - | - |
| first num | 0 | 1 | 1 | 0 | 0 | 1 | 0 | 0 |
|second num | 0 | 1 | 1 | 1 | 0 | 1 | 1 | 1 |
|  result   |   |   |   |   |   | 0 | 1 | 1 |

carry bit + first num bit + second num bit = 1<sub>2</sub> + 0<sub>2</sub> + 0<sub>2</sub> = 1<sub>2</sub>

| carry bit |   |   |   | 0 | 1 | 0 | 0 | 0 |
| --------- | - | - | - | - | - | - | - | - |
| first num | 0 | 1 | 1 | 0 | 0 | 1 | 0 | 0 |
|second num | 0 | 1 | 1 | 1 | 0 | 1 | 1 | 1 |
|  result   |   |   |   |   | 1 | 0 | 1 | 1 |

0<sub>2</sub> + 1<sub>2</sub> = 1<sub>2</sub>

| carry bit |   |   | 0 | 0 | 1 | 0 | 0 | 0 |
| --------- | - | - | - | - | - | - | - | - |
| first num | 0 | 1 | 1 | 0 | 0 | 1 | 0 | 0 |
|second num | 0 | 1 | 1 | 1 | 0 | 1 | 1 | 1 |
|  result   |   |   |   | 1 | 1 | 0 | 1 | 1 |

1<sub>2</sub> + 1<sub>2</sub> = 10<sub>2</sub>

| carry bit |   | 1 | 0 | 0 | 1 | 0 | 0 | 0 |
| --------- | - | - | - | - | - | - | - | - |
| first num | 0 | 1 | 1 | 0 | 0 | 1 | 0 | 0 |
|second num | 0 | 1 | 1 | 1 | 0 | 1 | 1 | 1 |
|  result   |   |   | 0 | 1 | 1 | 0 | 1 | 1 |

1<sub>2</sub> + 1<sub>2</sub> + 1<sub>2</sub> = 10<sub>2</sub> + 1<sub>2</sub> = 11<sub>2</sub>

| carry bit | 1 | 1 | 0 | 0 | 1 | 0 | 0 | 0 |
| --------- | - | - | - | - | - | - | - | - |
| first num | 0 | 1 | 1 | 0 | 0 | 1 | 0 | 0 |
|second num | 0 | 1 | 1 | 1 | 0 | 1 | 1 | 1 |
|  result   |   | 1 | 0 | 1 | 1 | 0 | 1 | 1 |

1<sub>2</sub> + 0<sub>2</sub> + 0<sub>2</sub> = 1<sub>2</sub>

and so the answer =  **11011011<sub>2</sub>**

| carry bit | 1 | 1 | 0 | 0 | 1 | 0 | 0 | 0 |
| --------- | - | - | - | - | - | - | - | - |
| first num | 0 | 1 | 1 | 0 | 0 | 1 | 0 | 0 |
|second num | 0 | 1 | 1 | 1 | 0 | 1 | 1 | 1 |
|  result   | 1 | 1 | 0 | 1 | 1 | 0 | 1 | 1 |

### overflow error

- when the result is larger than the register size, an overflow error occurs
- example of 8-bit binary addition overflow: 10000000<sub>2</sub> + 10000000<sub>2</sub>
- the result is larger than 255 and would need a 9th bit to store
- this would lead to the loss of the most significant bit (rightmost bit) 

---

### **<ins>1.1.5 logical binary shifts</ins>**

- a logical shift moves binary digits to the left/ right
- **left** shifts **multiplies** the binary number by 2
- **right** shifts **divides** binary number by 2
- when bits are shifted, the new empty positions are replaced with 0
- after a number of shifts, the register would end up only containing zeros, which results in an error.

for example:

**0 1 0 0 1 1 0 1** 

shifted to the left by 1

**1 0 0 1 1 0 1 0**

is the same as adding itself by itself (multiplying by 2)

| carry bit | 1 | 0 | 0 | 1 | 1 | 0 | 1 | 0 |
| --------- | - | - | - | - | - | - | - | - |
| first num | 0 | 1 | 0 | 0 | 1 | 1 | 0 | 1 |
|second num | 0 | 1 | 0 | 0 | 1 | 1 | 0 | 1 |
|  result   | 1 | 0 | 0 | 1 | 1 | 0 | 1 | 0 |

01001101<sub>2</sub> + 01001101<sub>2</sub> = 01001101<sub>2</sub> * 2<sub>10</sub> = 10011010<sub>2</sub>

---

### **<ins>1.1.6 two's complement and negative binary numbers</ins>**

- binary integers can be either signed or unsigned
- in two's complement, the leftmost bit (most significant bit) is set to negative
- this means a signed 8-bit binary integer can either be -128<sub>10</sub> (10000000<sub>2</sub>) or +127<sub>10</sub> (01111111<sub>2</sub>)

| -128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
| --- | -- | -- | -- | - | - | - | - |
| -2<sup>7</sup> | 2<sup>6</sup> | 2<sup>5</sup> | 2<sup>4</sup> | 2<sup>3</sup> | 2<sup>2</sup> | 2<sup>1</sup> | 2<sup>0</sup> |
|0|1|0|0|0|1|0|1|

- this means a 1 in the leftmost bit will **always** denote a negative number
- and a 0 in the leftmost bit will **always** denote a positive number

### converting 8-bit binary numbers to negative and vice versa

for the example, we will use the value: 01000101<sub>2</sub>/ 69<sub>10</sub>

we will first flip all the digits. this process is called the one's complement

| -128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
| --- | -- | -- | -- | - | - | - | - |
| -2<sup>7</sup> | 2<sup>6</sup> | 2<sup>5</sup> | 2<sup>4</sup> | 2<sup>3</sup> | 2<sup>2</sup> | 2<sup>1</sup> | 2<sup>0</sup> |
|1|0|1|1|1|0|1|0|

this produces a result of -70

we then add the number by 1 bit to make it correct. this process is called the two's complement

| -128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
| --- | -- | -- | -- | - | - | - | - |
| -2<sup>7</sup> | 2<sup>6</sup> | 2<sup>5</sup> | 2<sup>4</sup> | 2<sup>3</sup> | 2<sup>2</sup> | 2<sup>1</sup> | 2<sup>0</sup> |
|1|0|1|1|1|0|1|1|

-128<sub>10</sub> + 32<sub>10</sub> + 16<sub>10</sub> + 8<sub>10</sub> + 2<sub>10</sub> = -69<sub>10</sub>

thus

10111011<sub>2</sub> = -69<sub>10</sub>

---

### **<ins>1.1 exam-style questions<ins>** 

to be added. 🙏

---

## **1.2 text, sound and images 😎**

| learning objectives | notes and guidance |
| --- | --- |
|1. understand how and why a computer represents texts using character sets, like American standard code for information interchange (ASCII) and Unicode | • text is converted to binary to be processed by a computer <br> • unicode allows for greater range of characters, allowing for other languages and emojis <br> • unicode requires more bits per character than ASCII |
|2. understand how and why a computer represents sounds, and how sample rate and sample resolution affects it | • sound waves are sampled in order to be converted to binary to be processed by a computer <br> • sample rate is the number of samples taken per second <br> • sample resolution is the number of bits per sample <br> • increase in sample rate and resolution increases accuracy of recording |
|3. understand how and why a computer represents images, and how resolution and colour depth affects it| • images are series of pixels that are convert into binary to be processed by a computer <br> • resolution is the number of pixels in an image <br> • colour depth is the number of bits used to represent each colour <br> • increase in resolution and colour depth increases file size and quality of image |

---

### **<ins>1.2.1 text</ins>**

- there are two character sets, ASCII code and unicode.

### ASCII

- ASCII characters use one byte to represent a character
- standard ASCII character set uses 7-bit codes (uses codes 0 - 127) to represent 128 characters
- it has 32 control codes at the start (uses codes 0 - 31)
- the uppercase and lowercase characters are easily interchangeable
- because the sixth bit changes from 1 to 0, 1 making it lowercase, 0 making it uppercase
- this also speeds up usability

| letter | binary |
| ------ | ------ |
| 'a' | 1 **1** 0 0 0 0 1 |
| 'A' | 1 **0** 0 0 0 0 1 |
| 'y' | 1 **1** 1 1 0 0 1 |
| 'Y' | 1 **0** 1 1 0 0 1 |  

![ASCII codes table of codes 32 - 127](/assets/ascii_codes_table.png)

- there also exists Extended ASCII which uses 8-bit codes (uses codes 0 - 255) to represent 256 characters
- this allows non-English characters and graphical characters to be included

![Extended ASCII codes table of codes 128 - 255](/assets/extended_ascii_codes_table.png)

### unicode

- the first 128 characters are the same in unicode as with ASCII code
- unicode can support up to four bytes per character
- allows it to support several thousand different characters
- unicode is published to create a universal standard that covered all writing systems
- is more efficient than ASCII
- uses uniform encoding where every character is encoded as either 16-bit or 32-bit code
- uses codes that always represented the same character
- reserves parts of code for private use/ allows user to assign codes for their own characters

![unicode character code example](/assets/unicode_character_example.png)

### ASCII vs Unicode

| ASCII code | Unicode |
| ---- | ---- |
| • takes less space, only has 256/ 128 characters <br>but <br>• does not represent non-western languages like chinese<br>• different systems have different characters for same ASCII code| • can encode every writing system<br>• supports many operating systems and browsers<br> •  first 128 characters are the same as with ASCII allowing for support in ASCII encoded texts<br>• has a reserve part of the code for private use<br>but<br>• uses more space (up to 4 bytes per character) |

---

### **<ins>1.2.2 sounds</ins>**

- sound waves have frequency, wavelength and amplitude
- frequency is the pitch of the sound
- amplitude is the loudness of the sound

![high and low frequency wave signals](/assets/high_and_low_frequency_sound_waves.png)

- sound waves are continuous, making it analogue
- computers cannot work with analogue data
- this means the sound has to be sampled with an ADC (analogue to digital converter)

### sampling rate

- sampling is done at regular time intervals
- *sampling rate* is the number of sound samples taken **per second** measured in hertz (Hz)
- 1 Hz (hertz) is one sample per second
- approximate values of sound amplitude is stored with every time interval

### sampling resolution

- *sampling resolution* is the number of bits per sample (aka bit depth)
- this is the accuracy of the sampled sound amplitude

- higher sampling resolutions and rate = more accurate sound but larger file size

### to record a sound clip

- the amplitude of sound wave is determined at set time intervals
- this gives an approximation of the sound
- each sample is then encoded into binary values

- CDs typically have a 16-bit sampling resolution and 44.1 kHz (44 100 Hz) sample rate
- this gives it a high-quality sound reproduction

### pros and cons of larger sampling resolution

| pros | cons |
| ---- | ---- |
| larger dynamic range | larger file size |
| better sound quality | takes longer to upload/download files |
| less sound distortion| requires greater processing power |

---

### **<ins>1.2.3 images</ins>**

- there are two types of images, vector and bitmap images
- bitmap images are made up of a 2-D matrix of pixels (picture elements)
- each pixel can be represented as a binary number
- images have colour depth and resolution

### colour depth

- colour depth is the number of bits used to represent each colour
- the amount of possible colours in a colour depth is calculated through 2<sup>n</sup>
- where n is the colour depth
- a colour depth of 3 can represent 8 colours because 2<sup>3</sup> = 8

- modern computers have a 24-bit colour depth, allowing for 16 million different colours

### image resolution

- image resolution is the number of pixels in an image
- it is calculated by multiplying the width and height of the image in pixel units

- a higher resolution means the image is less pixelated ('fuzzy'/'unclear')
- but this means larger file size

### pros and cons of larger resolution and colour depth

| pros | cons |
| ---- | ---- |
| improved colour accuracy | larger file size/ less images can be stored |
| reduced colour banding | takes longer to upload/download files |
| more vibrant images | requires greater processing power |

---

### **<ins>1.2 exam-style questions<ins>** 

to be added. 🙏

---

## **1.3 data storage and compression 🥶**

| learning objectives | notes and guidance |
| --- | --- |
|1. understand how data storage is measured | • including: <br>- bit<br>- nibble<br>- byte<br>- kibibyte (KiB)<br>- mebibyte (MiB)<br>-gibibyte (GiB)<br>- tebibyte (TiB)<br>- pebibyte (PiB)<br>- exbibyte (EiB)<br>• the amount of previous denomination present in data storage size: <br>- 8 bits in a byte<br>- 1024 mebibytes in a gibibyte|
|2. calculate file size of an image and sound using information given | • answers must be given in units specified in question <br> • information given may include <br> - image resolution and colour depth <br> - sound sample rate, resolution and length of track |
|3. understand the purpose and need for data compression| • compression exists to reduce size of file <br> • the impacts: <br> - less bandwidth required <br> - less storage space required <br> - shorter transmission time|
|4. understand how files are compressed using lossy and lossless compression | • lossless compression reduces file size without permanent loss of data, e.g. run length encoding (RLE) <br> • lossy compression reduces the file size by permanently removing data, e.g. reducing resolution or colour depth, reducing sample rate or resolution |

---

### **<ins>1.3.1 data storage</ins>**

- a bit (binary digit) is the smallest unit of memory and can either be 1 or 0
- 1 byte is 8 bits
- 1 nibble is 4 bits (half a byte)
- this means 2 nibbles make a ~~bite~~ byte (yum 🤪)

there are two types of memory size measurements.
- SI (international system of units) units and IEC (international electrotechnical commission) units

- **the syllabus uses IEC units only** this means no kilobytes (1000 B) and megabytes (1000 KB), instead it's kibibytes (1024 B) and mebibytes (1024 KB)

- the IEC units are more technically accurate but a hell of a lot more annoying to calculate

| name of memory size and its unit | number of bytes | amount of bytes in denary |
| -- | -- | -- |
| 1 kibibyte (1 KiB) | 2<sup>10</sup> | 1 024 bytes |
| 1 mebibyte (1 MiB) | 2<sup>20</sup> | 1 048 576 bytes |
| 1 gibibyte (1 GiB) | 2<sup>30</sup> | 1 073 741 824 bytes |
| 1 tebibyte (1 TiB) | 2<sup>40</sup> | 1 099 511 627 776 bytes |
| 1 pebibyte (1 PiB) | 2<sup>50</sup> | 1 125 899 906 842 624 bytes |
| 1 exbibyte (1 EiB) | 2<sup>60</sup> | 1 152 921 504 606 846 976 bytes |

---

### **<ins>1.3.2 file size calculations</ins>**

- to calculate an image size, we use the formula:
`image resolution (in pixels) * colour depth (in bits)`

- to calculate a sound file, we use the formula:
`sample rate (in Hz) * sample resolution (in bits) * length of sample (in seconds) * number of channels`
- if it is a mono sound file, the number of channels is 1. if it's stereo, then it's 2 channels

- remember that both sample resolution and colour depth is in **bits**
- and since sample rate has to be in **hertz**, the length of the sample has to be in **seconds**

---

### **<ins>1.3.3 reason for data compression</ins>**

- files can become very large
- compression is used to reduce the size of a file
- to save storage space
- to reduce time taken to stream a music or video file
- to reduce time taken to upload/ download a file across a network
- to reduce bandwidth usage (bandwidth is the maximum rate of transfer of data across a network, measured in bits per second)
- reduce costs in using cloud storage, or downloading files (ISP charges)

---

### **<ins>1.3.4 how data compression works </ins>**

- data compression is either lossless or lossy

### lossy file compression
- a file compression algorithm is used to remove unnecessary data from a file
- original file cannot be reconstructed after compression
- causes loss of detail when compared to original file

a lossy file compression algorithm may
- in an image
    - reduce resolution
    - reduce colour depth
- in a sound file
    - reduce sampling rate
    - reduce resolution
    - remove inaudible sounds (perceptual music shaping)

- common lossy file compression algorithms include:
    - MPEG-3 (MP3)
    - MPEG-4 (MP4)
    - JPEG

### MPEG-3 (MP3) and MPEG-4 (MP4)

- MP3 is used for music
- reduces size of normal music file by 90%
- MP3 retains acceptable file quality after compression
- it uses perceptual music shaping
    - removes sounds outside of human ear range (20 Hz - 20kHz)
    - when there's two simultaneous sounds, only the louder one is heard, so the softer sound is removed

- MP4 is for both sound and video
- it allows for the storage of multimedia files (files with sound and video)
- it retains acceptable quality
- movies can be streamed without losing any discernible quality

### JPEG

- a camera produces a raw bitmap file that is very large in size
- JPEG is a lossy file compression algorithm used for bitmap images
- the original file cannot be reconstructed after compression
- the process is based on two key concepts
    - human eyes can't detect differences in colour very well, only brightness
    - separating pixel colour from brightness allows it to be split to 8 x 8 pixel blocks to allow information to be discarded from image

### lossless file compression
- a file compression algorithm used to reduce file size but still be able to reconstruct original file
- used in files where data must not be lost

### run-length encoding (RLE)
- form of lossless/ reversible file compression
- reduces size of string of adjacent repeated data
- repeating string is encoded into two values
    - first value represents number of identical data in the run
    - second value represents the code of data item
- RLE is only effecive where there is a long run of repeated bits

for example:

- the text string "aaaaabbbbccddddd" can be encoded into "05 97 04 98 02 99 05 100"

- an issue happens when there are repeating units in pairs, i.e. "cdcdcdcdcd" 
- to cope, a flag is used to indicate the amount of items with a certain code
- this allows the omission of the amount of items in singular items in the encoding

|aaaaaaaa | bbbbbbbbbb | c | d | c | d | c | d | eeeeeeee |
| -| -| -| -| -| -| -| -| -|
| 255 08 97 | 255 10 98 | 99 | 100 | 99 | 100 | 99 | 100 | 255 08 101 |

---

to be added. 🙏

### **<ins>1.3 exam-style questions<ins>** 

to be added. 🙏

---

# 2. data transmission
[[🤡 elevator back to contents]](#contents)

---

to be added. 🙏

## 2.1 types and methods of data transmission 😂

---

to be added. 🙏

## 2.2 methods of error detection 🙈

---

to be added. 🙏

## 2.3 encryption 👯‍♀️

---

to be added. 🙏

# 3. hardware
[[🤡 elevator back to contents]](#contents)

---

to be added. 🙏

## 3.1 computer architecture 💻

---

to be added. 🙏

## 3.2 input and output devices 🔔

---

to be added. 🙏

## 3.3 data storage 🥱

---

to be added. 🙏

## 3.4 network hardware 😚

---

to be added. 🙏

# 4. software
[[🤡 elevator back to contents]](#contents)

---

to be added. 🙏

## 4.1 types of software and interrupts 🤐

---

to be added. 🙏

## 4.2 types of programming language, translators and integrated development environments (IDEs) 🤓

---

to be added. 🙏

# 5. the internet and its uses
[[🤡 elevator back to contents]](#contents)

---

to be added. 🙏

## 5.1 the internet and the world wide web 🤯

---

to be added. 🙏

## 5.2 digital currency 🤑

---

to be added. 🙏

## 5.3 cyber security 👾

---

to be added. 🙏

# 6. automated and emerging technologies
[[🤡 elevator back to contents]](#contents)

---

to be added. 🙏

## 6.1 automated systems 🤗

---

to be added. 🙏

## 6.2 robotics 🤣

---

to be added. 🙏

## 6.3 artificial intelligence 💩

---

to be added. 🙏

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

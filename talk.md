---
title: barKod - Demystifying the Dark Art of Software Architecture
theme: solarized
revealOptions:
  transition: 'fade'
---

## **Demystifying the Dark Art of Software Architecture**


**Srđan Đorđević** \
[shellmonk.io](https://shellmonk.io)



![NTPNS](/assets/ntp_small.png) ![NTPNS](/assets/barkod_logo.png)

---

## $ whoami

```json

{
    "name": "Srđan Đorđević",
    "age": 34,
    "ocupation": "Senior Software Engineer",
    "works_at": "Pollard Digital Solutions",
    "location": "Novi Sad",
    "origin": "Paraćin",
    "hair": false
}

```
---

## Introduction

- Some light theory <!-- .element: class="fragment" data-fragment-index="1" -->
- Role of the architect in modern enterprise environment <!-- .element: class="fragment" data-fragment-index="2" -->
- If you want it, how to get it <!-- .element: class="fragment" data-fragment-index="3" -->

---

## What We Do Is Inherently Difficult

> “The most disastrous thing that you can ever learn is your first programming language” - **Alan Kay**

> “Programming is one of the most difficult branches of applied mathematics” - **Edsger W. Dijkstra**

---

## But Why?

---

## Limits of Human Cognitive Processing

> “The Magical Number Seven, Plus or Minus Two: Some Limits on our Capacity for Processing Information” - **George Armitage Miller, Psychological Review. 63 (2): 81–97., 1956.**

---

## Nature of Abstraction

- “The process of removing or generalising physical, spatial, or temporal details or attributes in the study of objects or systems to focus attention on details of greater importance” - **Kramer, Jeff (1 April 2007). "Is abstraction the key to computing?". Communications of the ACM. 50 (4): 36–42**

---

## Power and Curse of Abstractions

![Abstractions meme](/assets/abstractions_toy_story.jpg)

---

## Layering in Real World

![Layers of abstraction](/assets/layers-of-abstraction.png)

---

## Mapping to Roles

![Roles and abstractions](/assets/roles-heatmap.png)

---

## Not All Architects Are Created Equal 
![Types of architects](/assets/various-architects.png)


Note: Why we needed to split responsibilities? Technical vs non technical architects (sales engineers). Technical architects - infrastructure, cloud, mobile, frontend

---

## What Architect Is and What is Not?

- Architect's responsibilities
    - Supporting project management <!-- .element: class="fragment" data-fragment-index="1" -->
    - Enforcing best engineering practices <!-- .element: class="fragment" data-fragment-index="2" -->
    - Analyzing the technology environment <!-- .element: class="fragment" data-fragment-index="3" -->
    - Controlling solution development <!-- .element: class="fragment" data-fragment-index="4" -->
    - Technology selection <!-- .element: class="fragment" data-fragment-index="5" -->
    - Creating prototypes / PoCs <!-- .element: class="fragment" data-fragment-index="6" -->
    - DOCUMENTING STUFF <!-- .element: class="fragment" data-fragment-index="7" -->
    - Making developers' lives miserable (my favourite) <!-- .element: class="fragment" data-fragment-index="8" -->
    - ...many more <!-- .element: class="fragment" data-fragment-index="9" -->

---

## Architect's Goals

![Architect's Goals](/assets/goals.svg)

Note: It's all about the money. Evaluating options to get closer to the unicorn

---
## Architect as a Glorified Developer Fallacy
![Dilbert](/assets/dilbert.gif)


Note: Architecture is human activity. Software is just a code, but not really. Seeing the bigger picture. Understanding internal and external stakeholder's needs

---
### System Design vs Software Architecture
![Gigachad](/assets/soyboy_vs_chad.jpg)



---
## Architectural Decisions
> "The perfect kind of architecture decision is the one which never has to be made" - **Robert C. Martin**
- Architectural decisions are <!-- .element: class="fragment" data-fragment-index="1" --> **hard** <!-- .element: class="fragment" data-fragment-index="1" -->
    - Wrong decisions cost a lot <!-- .element: class="fragment" data-fragment-index="3" -->
    - Unicorn is too fast, you can't catch it <!-- .element: class="fragment" data-fragment-index="3" -->
- How do I evaluate options? <!-- .element: class="fragment" data-fragment-index="4" -->
    - You'll never have enough information

Note: You must find push for time to make an informed decision. (Non) functional requirements / Architectural characteristics. Build vs Buy. Decisions must be made eventually. Examples.
---

## There's No Silver Bullet

#### (But don't worry, you can still shoot yourself in the foot)

- Magic words: "It depends" <!-- .element: class="fragment" data-fragment-index="1" -->
- Technology tribalism is not our friend <!-- .element: class="fragment" data-fragment-index="2" -->
- If you could, doesn't mean you should <!-- .element: class="fragment" data-fragment-index="3" -->
- Go wild, but never sacrifice good engineering principles or, God forbid, compromise project’s delivery <!-- .element: class="fragment" data-fragment-index="4" -->

---

## Shiny Object Syndrome

> “Shiny object syndrome is the situation where people focus undue attention on an idea that is new and trendy, yet drop this as soon as something new takes it’s place” - **Wikipedia**

- If you like software engineering, you suffer from Shiny Object Syndrome

Note: Boom of specific technologies: Microservices, Blockchain, now even AI
---

## Standards and Documents are Our Friends

- Standards are foolproof <!-- .element: class="fragment" data-fragment-index="1" -->
- Documents are boring, but necessary <!-- .element: class="fragment" data-fragment-index="2" -->
- Power of architectural artefacts <!-- .element: class="fragment" data-fragment-index="3" -->


Note: Artefacts: SRS, SDS, Architecture Decision Log, C4, ISO/IEC/IEEE 42010 System and software engineering architecture description

---

## Big and Scary C-Word: Clients

- Presales process <!-- .element: class="fragment" data-fragment-index="1" -->
- Common language <!-- .element: class="fragment" data-fragment-index="2" -->
- Business domain <!-- .element: class="fragment" data-fragment-index="3" -->
- Setting expectations <!-- .element: class="fragment" data-fragment-index="4" -->

Note: We are building software for people (unfortunately). Clients can be technical or non technical. Or worse, something in between

---


## Rough Reality and How to Beat It?

- Impostor Syndrome <!-- .element: class="fragment" data-fragment-index="1" -->
    - You cannot avoid it <!-- .element: class="fragment" data-fragment-index="1" -->
    - It hits the hardest when you advance to the architect role <!-- .element: class="fragment" data-fragment-index="1" -->
    - How can you beat it <!-- .element: class="fragment" data-fragment-index="1" -->
- Following the technology advances <!-- .element: class="fragment" data-fragment-index="2" -->
- Keeping your hands dirty <!-- .element: class="fragment" data-fragment-index="3" -->
- Embracing the process <!-- .element: class="fragment" data-fragment-index="4" -->
- Utilizing the organization you're in <!-- .element: class="fragment" data-fragment-index="5" -->

---
## Staying in Touch With the Tech World

- Tutorials are becoming less and less helpful <!-- .element: class="fragment" data-fragment-index="1" -->
- You often don't even know what to Google <!-- .element: class="fragment" data-fragment-index="1" -->
- Books, blogs, podcasts, etc. are architect's gold <!-- .element: class="fragment" data-fragment-index="2" -->
- Embrace your ignorance and practice intellectual humility <!-- .element: class="fragment" data-fragment-index="3" -->
- Find your way to quickly absorb information <!-- .element: class="fragment" data-fragment-index="4" -->

---

## Wrapping it All Up

- We need more architects in the industry <!-- .element: class="fragment" data-fragment-index="1" -->
- Being an architect might look hard, but is hell of a fun <!-- .element: class="fragment" data-fragment-index="2" -->
    - indeed.com's best job for 2020 [https://www.indeed.com/lead/bestjobs-2020](https://www.indeed.com/lead/bestjobs-2020) <!-- .element: class="fragment" data-fragment-index="3" -->
- If you really love software, solutions architect is the best role to aim for <!-- .element: class="fragment" data-fragment-index="4" -->

---

## Thank you!

---

## Questions?

---

## More Info and References

![QR Code](/assets/qr.png)

[https://github.com/shellmonk/software-architecture-talk](https://github.com/shellmonk/software-architecture-talk)
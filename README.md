# Introduction

This framework allows software engineering managers to have meaningful conversations with their direct reports around the expectations of each position and how to plan for the next level in their career ladder.

The framework relies heavily in radar charts to show visually the different perspectives and expectations of a given position:

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="charts/template-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="charts/template.png">
  <img alt="Template Chart" src="charts/template.png">
</picture>

# Career Ladders

The framework has 4 different ladders:

* [**Engineer**](Engineer.md): role also known as programmer or developer, requires a deep level of technical expertise
* [**Tech Lead**](TechLead.md): role also known as dev lead, is the owner of the system and requires a unique balance between hands-on development, architecture knowledge and production support
* [**Staff Engineer**](TechnicalProgramManager.md): role responsible for coordinating and driving to completion initiatives that span multiple teams
* [**Engineering Manager**](EngineeringManager.md): role also known as dev manager, is responsible for the consistent delivery, career growth and level of happiness of the team

If you are confused about the difference between a [Tech Lead](TechLead.md) and an [Engineering Manager](EngineeringManager.md), please refer to the [Tech Lead vs Engineering Manager](TechLead-EngineeringManager.md) page for a detailed comparison.

| Level | Senior | [Engineer](Engineer.md) | [Tech Lead](TechLead.md) | [Staff Engineer](StaffEngineer.md) | [Engineering Manager](EngineeringManager.md) |
| :---: | :---: | :---: | :---: | :---: |  :---: |
| 1 | No | [E1](Engineer.md#e1---engineer-1) | | | |
| 2 | No | [E2](Engineer.md#e2---engineer-2) | | | |
| 3 | No | [E3](Engineer.md#e3---engineer-3) | | | |
| 4 | Yes | [E4](Engineer.md#e4---engineer-4) | [TL4](TechLead.md#tl4---tech-lead-4) | [SE4](StaffEngineer.md#SE4---staff-engineer-4) | |
| 5 | Yes | [E5](Engineer.md#e5---engineer-5) | [TL5](TechLead.md#tl5---tech-lead-5) | [SE5](StaffEngineer.md#SE5---staff-engineer-5) | [EM5](EngineeringManager.md#em5---engineering-manager-5) |
| 6 | Yes | [E6](Engineer.md#d6---engineer-6) | [TL6](TechLead.md#tl6---tech-lead-6) | [SE6](StaffEngineer.md#SE6---staff-engineer-6) | [EM6](EngineeringManager.md#em6---engineering-manager-6) |
| 7 | Yes | [E7](Engineer.md#d7---engineer-7) | [TL7](TechLead.md#tl7---tech-lead-7) | [SE7](StaffEngineer.md#SE7---staff-engineer-7) | [EM7](EngineeringManager.md#em7---engineering-manager-7) |

(click on position name for more details)

# Axes

The chart shown above has the following 5 axes:
* **Technology**: knowledge of the tech stack and tools
* **System**: level of ownership of the system(s)
* **People**: relationship with the team(s)
* **Process**: level of engagement with the development process
* **Influence**: scope of influence of the position

The **influence** axis can be seen as a *different dimension* since it is orthogonal and applies to all the other axes.

Each axis has 5 different levels of performance. It is important to highlight that every level includes the previous one(s). For example, someone that *evangelizes* technology, *specializes* and *adopts* it as well.

Keep reading to better understand each level.

# Levels

## Technology

1. **Adopts**: actively learns and adopts the technology and tools defined by the team
2. **Specializes**: is the go-to person for one or more technologies and takes initiative to learn new ones
3. **Evangelizes**: researches, creates proofs of concept and introduces new technologies to the team
4. **Masters**: has very deep knowledge about the whole technology stack of the system
5. **Creates**: designs and creates new technologies that are widely used either by internal or external teams

## System

1. **Enhances**: successfully pushes new features and bug fixes to improve and extend the system
2. **Designs**: designs and implements medium to large size features while reducing the system's tech debt
3. **Owns**: owns the production operation and monitoring of the system and is aware of its SLAs
4. **Evolves**: evolves the architecture to support future requirements and defines its SLAs
5. **Leads**: leads the technical excellence of the system and creates plans to mitigate outages

## People

1. **Learns**: quickly learns from others and consistently steps up when it is required
2. **Supports**: proactively supports other team members and helps them to be successful
3. **Mentors**: mentors others to accelerate their career-growth and encourages them to participate
4. **Coordinates**: coordinates team members providing effective feedback and moderating discussions
5. **Manages**: manages the team members' career, expectations, performance and level of happiness

## Process

1. **Follows**: follows the team processes, delivering a consistent flow of features to production
2. **Enforces**: enforces the team processes, making sure everybody understands the benefits and tradeoffs
3. **Challenges**: challenges the team processes, looking for ways to improve them
4. **Adjusts**: adjusts the team processes, listening to feedback and guiding the team through the changes
5. **Defines**: defines the right processes for the team's maturity level, balancing agility and discipline

## Influence

1. **Subsystem**: makes an impact on one or more subsystems (eg. Android Team)
2. **Team**: makes an impact on the whole team, not just on specific parts of it (eg. Frontend Team)
3. **Multiple Teams**: makes an impact not only his/her team but also on other teams (i.e. Frontend Team and Backend Team)
4. **Company**: makes an impact on the whole tech organization (i.e. whole Entertainment or Nuuday)
5. **Community**: makes an impact on the tech community (eg. Google Developer Advocate)

# FAQs

**What if some of the people don't meet all the points?**

That is very normal, people are usually stronger in some areas and weaker in others. The framework should not be used as a checklist to promote people but instead as guidance to have meaningful career conversations.

**When is a person ready to move to the next level?**

You are expected to be performing at the next level *consistently for several months* before formalizing a promotion.

**How do I collect evidence to support the discussion with my direct reports?**

Different teams collect evidence in different ways. A recommended approach is to use a combination of:
* 1:1 conversations
* Feedback from peers and other teams
* Self-evaluation

**Could the framework provide more specific examples of behavior to support each level?**

Specific examples of behavior require knowledge about the way that the team works, the system architecture and its technology stack. It is recommended to allow each team to define their own examples.

**Why does the framework stop at level 7?**

Levels 8 and above vary drastically from teams to teams. We will continue evolving this framework to find out next levels.

**Do you have any additional resources about the topic?**

* [The Manager's Path](http://shop.oreilly.com/product/0636920056843.do): Camille Fournier does an excellent job at describing the expectations and challenges of many engineering positions. Also, she provides good advice about writing a career ladder in chapter 9.

* [How to Be Good at Performance Appraisals](https://store.hbr.org/product/how-to-be-good-at-performance-appraisals-simple-effective-done-right/10295): Dick Grote explains in simple terms how to define job responsibilities and how to evaluate performance (results and behaviors).

**How can this be applied on QA team?**

* [QA Engineer Ladder](https://wiki.nuuday.dk/display/DQA/QA+Engineering+Ladder): Please refer to this wiki for elaboration/examples for QA.

# Other Pages

* [**Engineer**](Engineer.md)
* [**Tech Lead**](TechLead.md)
* [**Staff Engineer**](StaffEngineer.md)
* [**Engineering Manager**](EngineeringManager.md)
* [**Tech Lead vs Engineering Manager**](TechLead-EngineeringManager.md)
* [**Managing Managers**](Managing-Managers.md)

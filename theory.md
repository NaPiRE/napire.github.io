---
layout: default
title: Theory
description: Status Quo of Requirements Engineering
permalink: /theory.html
---

The NaPiRE initiative, through repeated global surveys of requirements engineering practitioners, produces the "Status Quo" theory about what is common practice in requirements engineering.

## Reading the Theory

The theory consists of several sets of binary propositions, which - when supported - imply a common practice in requirements engineering.
The following tables list all of these propositions and their evolution across the major iterations of NaPiRE:

- **2012**: Fernández, D. M., & Wagner, S. (2013, April). Naming the pain in requirements engineering: design of a global family of surveys and first results from Germany. In Proceedings of the 17th International Conference on Evaluation and Assessment in Software Engineering (pp. 183-194).
- **2014**: Wagner, S., Fernández, D. M., Felderer, M., Vetrò, A., Kalinowski, M., Wieringa, R., ... & Winkler, D. (2019). Status quo in requirements engineering: A theory and a global family of surveys. ACM Transactions on Software Engineering and Methodology (TOSEM), 28(2), 1-48.
- **2024**: Wagner, S., Mombrey, C., Frattini, J., Mendez, D., ... (2026). Status Quo in Requirements Engineering: An Updated Theory and Longitudinal Perspective. Under Review.

Interpret each cell in the tables (i.e., each combination of proposition and year) as follows:

<table>
  <colgroup>
  <col style = "width: 20%;">
  <col style = "width: 80%;">
</colgroup>
<thead>
  <tr>
    <th>Code</th>
    <th>Meaning</th>
  </tr>
</thead>
  <tbody>
    <tr>
      <td>(Empty)</td>
      <td>The proposition was not investigated in that iteration of the surveys.</td>
    </tr>
    <tr>
      <td>{% include status-label.html status="New" %}</td>
      <td>The proposition was not investigated in that iteration of the surveys.</td>
    </tr>
    <tr>
      <td>{% include status-label.html status="Supported" %}</td>
      <td>The proposition was supported again.</td>
    </tr>
    <tr>
      <td>{% include status-label.html status="Updated" %}</td>
      <td>The proposition was slightly changed.</td>
    </tr>
    <tr>
      <td>{% include status-label.html status="Removed" %}</td>
      <td>There proposition was no longer supported by empirical evidence.</td>
    </tr>
  </tbody>
</table>

## Theory

### Elicitation

Elicitation refers to one of the core activities in requirements engineering, where requirements are obtained from its various sources, i.e., relevant stakeholders.

<table class="status-table">
  {% include status-table-head.html %}
  <tbody>
    <tr>
      <td>P1</td>
      <td>Requirements are elicited via interviews.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
    </tr>
    <tr>
      <td>P2</td>
      <td>Requirements are elicited via scenarios.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P3</td>
      <td>Requirements are elicited via prototyping.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
    </tr>
    <tr>
      <td>P4</td>
      <td>Requirements are elicited via facilitated meetings (including workshops).</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
      <td>{% include status-label.html status="Removed" %}</td>
    </tr>
    <tr>
      <td>P5</td>
      <td>Requirements are elicited via observation.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
    </tr>
    <tr>
      <td>P50</td>
      <td>Requirements are elicited and/or refined in several iterations.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
    </tr>
    <tr>
      <td>P51</td>
      <td>Requirements are elicited via document analysis.</td>
      <td></td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
    </tr>
  </tbody>
</table>

The NaPiRE initiative conjectured the following explanations for the propositions:

- E1 (for P1, P3, P5, P51, P52): Interviews, prototyping, observations, experimentation with users, and document analysis allow requirements engineers to include many different viewpoints, including those from non-technical stakeholders.
- E2 (for P3, P52): Prototypes and experimentation with users promote a shared understanding of the requirements among stakeholders.

### Documentation

Documentation refers to another one of the core activities in requirements engineering, where requirements are manifested in requirements artifacts which can be shared, versioned, and reused.

<table class="status-table">
  {% include status-table-head.html %}
  <tbody>
    <tr>
      <td>P6</td>
      <td>Structured requirements lists are documented textually in free form or textually with constraints.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
    </tr>
    <tr>
      <td>P7</td>
      <td>Requirements artifacts, including use cases and user stories, are documented textually in free form or textually with constraints.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Updated" %}</td>
    </tr>
    <tr>
      <td>P8</td>
      <td>Use case models are documented semi-formally (e.g. using UML).</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Removed" %}</td>
    </tr>
    <tr>
      <td>P9</td>
      <td>Domain/business process models are documented textually in free form.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Removed" %}</td>
    </tr>
    <tr>
      <td>P10</td>
      <td>Goal models are commonly used in a textual form.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Removed" %}</td>
    </tr>
    <tr>
      <td>P11</td>
      <td>Goal models are not documented semi-formally or formally.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
    </tr>
    <tr>
      <td>P12</td>
      <td>Data models are documented semi-formally (e.g., using UML).</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Removed" %}</td>
    </tr>
    <tr>
      <td>P13</td>
      <td>Non-functional requirements are documented textually either quantified or non-quantified.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
    </tr>
    <tr>
      <td>P52</td>
      <td>Requirements engineers have failed to document at least one requirement. </td>
      <td></td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
    </tr>
    <tr>
      <td>P53</td>
      <td>The information categories most commonly documented include architectural constraints, functional properties, goals, (business) rules, system behavior, technical interfaces, usage scenarios, user interfaces, and acceptance criteria.</td>
      <td></td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
    </tr>
  </tbody>
</table>

The NaPiRE initiative conjectured the following explanations for the propositions:

- E3 (for P6, P7, P11): Free-form and constraint textual requirements are sufficient for many contexts such as in agile projects where they only act as reminders for further conversations.
- E4 (for P8 and P12): Use case models and data models might not often be shared with non-technical stakeholders. Hence, requirements engineers can use well-known semi-formal description techniques such as entity-relationship diagrams or UML to document them.
- E5 (for P13): The quantification depends on the type of non-functional requirement. Performance is rather documented quantitatively while maintainability is rather documented non-quantitatively.
- E29 (for P52): Requirements knowledge is often tacit; engineers who are deeply familiar with the system may not perceive documentation as necessary.
- E30 (for P53): Requirements documentation records what the system is to do, the context it must fit into, and the criteria by which it is judged: the functional core (functional properties, system behavior, usage scenarios, goals), the interfaces to users and other systems, the constraints and rules under which the system is built, and the acceptance criteria that close the loop to validation.

### Requirements Changes

Change management pertains to the constant challenge of keeping requirements up-to-date.

<table class="status-table">
  {% include status-table-head.html %}
  <tbody>
    <tr>
      <td>P14</td>
      <td>A requirements change management is established after formally accepting a requirements specification.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P15</td>
      <td>Product backlogs are updated because of requirements changes after the initial release.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P16</td>
      <td>Requirements changes after the initial release are reflected only in change requests.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P17</td>
      <td>Traces between requirements and code are explicitly managed.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P18</td>
      <td>Traces between requirements and design documents are explicitly managed.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P19</td>
      <td>For analyzing the effect of changes to requirements, impact analysis on the code is done.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P20</td>
      <td>For analyzing the effect of changes to requirements, impact analysis between requirements is not done.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td></td>
    </tr>
  </tbody>
</table>

The NaPiRE initiative conjectured the following explanations for the propositions:

- E6 (P14): In many development processes, requirements are fixed at some point(s) in time. A formal change management is only needed afterwards.
- E7 (P14a): In agile development process, change is continuous.
- E8 (P15, P16) Requirements change during a development project and also after the initial release. Many organisations only work with change requests in issue trackers. Agile organisations work with some kind of product backlog (as in Scrum) and change it regularly between iterations.
- E9 (P17, P18): Explicit traces make impact analysis more effective and efficient. P 17, P 18
- E10 (P19, P20): Despite traces between requirements and code, the effect of changes is most directly seen on the code level.

### Test Alignment

To guarantee that a system meets its requirements, it is necessary to align them with tests.

<table class="status-table">
  {% include status-table-head.html %}
  <tbody>
    <tr>
      <td>P21</td>
      <td>To align tests with requirements, testers participate in requirements reviews.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
    </tr>
    <tr>
      <td>P22</td>
      <td>To align tests with requirements, the coverage of requirements with tests is checked.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
    </tr>
    <tr>
      <td>P23</td>
      <td>To align tests with requirements, acceptance criteria are defined for requirements.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
    </tr>
    <tr>
      <td>P24</td>
      <td>To align tests with requirements, tests are derived from system models.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td></td>
    </tr>
  </tbody>
</table>

The NaPiRE initiative conjectured the following explanations for the propositions:

- E11 (P21-P23): To fully align tests with requirements, organizational and artifact-based measures are necessary to link requirements and tests.
- E12 (P24): Often, there are no system models that are complete or formal enough to derive tests.

### Standards

Standards pertain to normative rules governing the RE process at a company.

#### Application and Tailoring of Requirements Engineering Process Standards

<table class="status-table">
  {% include status-table-head.html %}
  <tbody>
    <tr>
      <td>P25</td>
      <td>Requirements engineers use their own RE standard.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P25a</td>
      <td>Requirements engineers use a standard that is predefined by the development process.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P26</td>
      <td>The RE standard is neither mandatory nor practiced.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P27</td>
      <td>The application of the RE standard is controlled via analytical quality assurance.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P27a</td>
      <td>The application of requirements engineering standards is checked by project assessments.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Updated" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P27b</td>
      <td>The application of requirements engineering standards is checked by constructive quality assurance (e.g., via checklists or templates).</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Updated" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P28</td>
      <td>The RE standard is tailored at the beginning of a project by the project lead based on experiences.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
      <td></td>
    </tr>
  </tbody>
</table>

The NaPiRE initiative conjectured the following explanations for the propositions:

- E13 (P25, P26) Requirements engineering differs quite strongly over domains and contexts and, thus, needs to adapt to these to be effective.
- E14 (P25a): Many practiced development processes prescribe or are associated with a specific way of performing requirements engineering.
- E15 (P28): The project lead knows the specific of the domain and project context best.

#### Reasons and Barriers for Defining a Requirements Engineering Process Standard

<table class="status-table">
  {% include status-table-head.html %}
  <tbody>
    <tr>
      <td>P29</td>
      <td>Compliance to regulations and standards (like CMMI) does not motivate a standard.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Removed" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P30</td>
      <td>Seamless development by integrating RE into the development process motivates a standard.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P31</td>
      <td>Better tool support motivates a standard.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P32</td>
      <td>Formal prerequisites for project acquisition do not motivate a standard.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Removed" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P33</td>
      <td>Support of distributed development motivates a standard.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P34</td>
      <td>Support of progress control motivates a standard.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P35</td>
      <td>Better quality assurance of artefacts motivates a standard.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P36</td>
      <td>Support of benchmarks does not motivate a standard.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Removed" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P37</td>
      <td>Support of project management and planning motivates a standard.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P38</td>
      <td>Higher efficiency motivates a standard.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P39</td>
      <td>Knowledge transfer motivates a standard.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P40</td>
      <td>Higher process complexity barriers defining a standard.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P41</td>
      <td>Higher demand for communication barriers defining a standard.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Removed" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P42</td>
      <td>Lower efficiency does not barrier defining a standard.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P43</td>
      <td>Missing willingness to change barriers defining a standard.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P44</td>
      <td>Missing possibilities of standardisation does not barrier defining a standard.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Removed" %}</td>
      <td></td>
    </tr>
  </tbody>
</table>

The NaPiRE initiative conjectured the following explanations for the propositions:

- E16 (P30): An RE standard can help to integrate RE activities and artefacts with other development activities and artefacts.
- E17 (P31): It is more efficient to build or acquire tool support for RE if the activities and artefacts are standardised.
- E18 (P34): Standardised RE artefacts make it easier to check if they are created and, hence, support progress control.
- E19 (P35): If RE artefacts are standardised, then standardised QA can be used such as checklists or automatic checks.
- E20 (P37): If the project lead can rely on a standardised RE, then the planning can rely on the standardised activities and artefacts.
- E21 (P38): A standardised RE allows the project participants to become experts in it and, therefore, become more efficient.
- E22 (P39): The RE standard codifies good practices and experiences, which can be transferred to new projects and project participants.
- E23 (P40): An RE standard might force projects to a more complex RE process than necessary for the concrete context.
- E24 (P42): Using RE process standards is considered more efficient (see also P38).
- E25 (P43): People in general are resistant to change.

### Requirements Engineering Improvement

Improvement is important for any software engineering practice and particularly for a volatile and complex part like requirements engineering.

<table class="status-table">
  {% include status-table-head.html %}
  <tbody>
    <tr>
      <td>P45</td>
      <td>Requirements engineering is continuously improved.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P46</td>
      <td>A continuous improvement is done to determine strengths and weaknesses.</td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P47</td>
      <td>Requirements engineering is improved via an own business unit / role.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P48</td>
      <td>RE is improved by an internally defined standard.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td></td>
    </tr>
    <tr>
      <td>P49</td>
      <td>RE is improved using external normative standards.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td></td>
    </tr>
  </tbody>
</table>

The NaPiRE initiative conjectured the following explanations for the propositions:

- E26 (P45, P46): Many companies have realised the importance of requirements engineering and of continuous improvement of development processes and methods.Working on it continuously helps to not forget strengths and weaknesses of the current RE approach.
- E27 (P47): RE improvement is performed by internally defined standards and best supported by an own business unit or role.
- E28 (P48): External normative standards are often considered too complex and elaborate to apply.

### Communication

Communication is key to requirements engineering, both with external stakeholder, but also within the project team and the overall company.

<table class="status-table">
  {% include status-table-head.html %}
  <tbody>
    <tr>
      <td>P54</td>
      <td>The relationship between the project team and its customer is rated positively.</td>
      <td></td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
    </tr>
    <tr>
      <td>P55</td>
      <td>Intra-team communication quality is rated positively.</td>
      <td></td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
    </tr>
    <tr>
      <td>P56</td>
      <td>Inter-team communication quality is rated positively.</td>
      <td></td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
    </tr>
    <tr>
      <td>P57</td>
      <td>Team members meet almost daily.</td>
      <td></td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
    </tr>
  </tbody>
</table>

The NaPiRE initiative conjectured the following explanations for the propositions:

- 31 (P54–P57): Close and frequent interaction within the project team and with the customer promotes shared understanding and enables effective requirements elicitation and validation.

### Handling Missing Information

Oftentimes, requirements engineering practitioners encounter lack of knowledge or missing information.

<table class="status-table">
  {% include status-table-head.html %}
  <tbody>
    <tr>
      <td>P58</td>
      <td>When lacking information, practitioners ask the customer.</td>
      <td></td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
    </tr>
  </tbody>
</table>

The NaPiRE initiative conjectured the following explanations for the propositions:

- E32 (P58): Direct consultation of the customer is the most reliable way to resolve ambiguities and avoid incorrect assumptions propagating into downstream development.

### Reaction to Unknown Documentation Benefit

The benefit of effort invested into the requirements engineering phase may not always be obvious to those investing it. 

<table class="status-table">
  {% include status-table-head.html %}
  <tbody>
    <tr>
      <td>P59</td>
      <td>Requirements documentation considered essential for the project is produced even when its direct benefit is unclear.</td>
      <td></td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
    </tr>
    <tr>
      <td>P60</td>
      <td>Requirements documentation is not omitted solely because current project members do not require it.</td>
      <td></td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
    </tr>
  </tbody>
</table>

The NaPiRE initiative conjectured the following explanations for the propositions:

- E33 (P59-P60): Practitioners distinguish between current utility and long-term essentialness; the perception that a document is essential for the project outweighs the lack of an immediately identifiable beneficiary.

### Non-Functional Requirements

Non-functional requirements describe system properties and qualities beyond functional aspects of a system.


<table class="status-table">
  {% include status-table-head.html %}
  <tbody>
    <tr>
      <td>P61</td>
      <td>The NFR classes most commonly documented include compatibility, maintainability, performance efficiency, reliability,
security, and usability.</td>
      <td></td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
    </tr>
  </tbody>
</table>

The NaPiRE initiative conjectured the following explanations for the propositions:

- E34 (P61): These NFR classes correspond to widely recognised quality attribute categories, making them more likely to be systematically addressed during requirements engineering.

### Stopping Criteria

Stopping the requirements analysis can occur for different reasons in practice.

<table class="status-table">
  {% include status-table-head.html %}
  <tbody>
    <tr>
      <td>P62</td>
      <td>Unilateral decisions by project leads are not a common reason for stopping requirements analysis.</td>
      <td></td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
    </tr>
  </tbody>
</table>

The NaPiRE initiative conjectured the following explanations for the propositions:

- E35 (P62): Collective agreement distributes the decision to stop requirements analysis across the team, reflecting shared ownership of the RE process; unilateral pressure from project leads is not accepted as a legitimate stopping criterion.

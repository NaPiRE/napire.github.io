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
    <tr>
      <td>P52</td>
      <td>Requirements are elicited via experimentation with users.</td>
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
      <td></td>
    </tr>
    <tr>
      <td>P13</td>
      <td>Non-functional requirements are documented textually either quantified or non-quantified.</td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
      <td>{% include status-label.html status="Supported" %}</td>
    </tr>
    <tr>
      <td>P53</td>
      <td>Requirements engineers have failed to document at least one requirement. </td>
      <td></td>
      <td></td>
      <td>{% include status-label.html status="New" %}</td>
    </tr>
  </tbody>
</table>

The NaPiRE initiative conjectured the following explanations for the propositions:

- E3 (for P6, P7, P11): Free-form and constraint textual requirements are sufficient for many contexts such as in agile projects where they only act as reminders for further conversations.
- E5 (for P13): The quantification depends on the type of non-functional requirement. Performance is rather documented quantitatively while maintainability is rather documented non-quantitatively.
- E7 (for P53): Requirements knowledge is often tacit; engineers who are deeply familiar with the system may not perceive documentation as necessary.

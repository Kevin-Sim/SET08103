**Assessment Brief Template**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 74%" />
</colgroup>
<thead>
<tr>
<th><blockquote>
<p><strong>Module Title and Number</strong></p>
</blockquote></th>
<th>SET08103 Software Engineering Methods</th>
</tr>
</thead>
<tbody>
<tr>
<td><blockquote>
<p><strong>Module Leader</strong></p>
</blockquote></td>
<td>Kevin Sim</td>
</tr>
<tr>
<td><blockquote>
<p><strong>Contact for Assessment</strong></p>
</blockquote></td>
<td>As above</td>
</tr>
<tr>
<td><blockquote>
<p><strong>Assessment Method</strong></p>
</blockquote></td>
<td>Group Project</td>
</tr>
<tr>
<td><strong>Weighting</strong></td>
<td>‘60% of module’.</td>
</tr>
<tr>
<td><strong>Size and/or Time Limits for Assessment</strong></td>
<td>Group project runs from week 2 until week 12 and is assessed in
weeks 4, 6, 9 and 12. Students are expected to put in at least 20 hours
for each of the four assessment points.</td>
</tr>
<tr>
<td><blockquote>
<p><strong>Learning Outcomes</strong></p>
</blockquote></td>
<td>LO1: Demonstrate understanding of a modern software development
lifecycle.<br />
LO3: Define and analyse systems requirements and needs and specify a
system design to deliver these requirements.<br />
LO4: Apply modern software engineering methods and techniques to a
software development project.</td>
</tr>
<tr>
<td><blockquote>
<p><strong>Purpose and Rationale</strong></p>
</blockquote></td>
<td>The group project introduces modern DevOps tools and best practices.
Students work on a project as part of a scrum team learning not just the
modern methods and tools but also efficient team working and use of
project management techniques used widely in industry</td>
</tr>
<tr>
<td><blockquote>
<p><strong>Requirements for the Assessment</strong></p>
</blockquote></td>
<td>Added at the end of this document along with the marking
criteria.</td>
</tr>
<tr>
<td><strong>Use of Gen AI in this Assessment</strong></td>
<td>With caution. Students must be able to explain their code during the
code reviews.</td>
</tr>
<tr>
<td><blockquote>
<p><strong>Statement on Inclusion</strong></p>
</blockquote></td>
<td style="text-align: left;"><p>We recognise that some students may
find “group work” challenging or anxiety-inducing. If you have any
concerns about this aspect of the assessment, please arrange to speak
with the Module Leader on a one-to-one basis. Only one member of the
group needs to present the work.</p>
<p>Where there is a requirement documented within your Learning Profile,
we may be able to make reasonable adjustments:</p>
<p>Adjustments will be considered on an individual basis. Please get in
touch</p></td>
</tr>
<tr>
<td><blockquote>
<p><strong>Alternative Assessment Option(s)</strong></p>
</blockquote></td>
<td>See above</td>
</tr>
<tr>
<td><blockquote>
<p><strong>Deadline for Submission</strong></p>
</blockquote></td>
<td><p><em>The group project should be completed over the semester and
will be assessed by means of a review of your progress in weeks 4, 6, 9
&amp; 12.</em></p>
<p><em>Marks will be awarded during the review</em></p></td>
</tr>
<tr>
<td><blockquote>
<p><strong>Submission Method</strong></p>
</blockquote></td>
<td>Via Moodle and GitHub. See the coursework specification for more
details</td>
</tr>
<tr>
<td><blockquote>
<p><strong>Feedback</strong></p>
</blockquote></td>
<td><p>Feedback will be provided during the code reviews</p>
<p>Students who wish further feedback should get in touch with the
teaching team.</p></td>
</tr>
<tr>
<td><p><strong>Assessment</strong></p>
<blockquote>
<p><strong>Regulations &amp; Academic Conduct</strong></p>
</blockquote></td>
<td><strong>All assessments at Edinburgh Napier University are subject
to the University’s Academic Regulations, Academic Integrity
Regulations, Student Community Code. Students are expected to adhere to
the Student Community Code and maintain acceptable standards of academic
practice, as set out in the Academic Integrity
Regulations.</strong></td>
</tr>
</tbody>
</table>

## 

## Coursework Specification

You will work on the project as a Scrum team. Details on Scrum are
provided in [Unit01b](../units/unit01/unit01b.md), including an FAQ on how
to apply Scrum in the module.

You work for an organisation that requires reporting on population
information. You have been tasked with designing and implementing a new
system to allow easy access to this population information. The
organisation has provided you with an SQL database to work from
available [here](https://downloads.mysql.com/docs/world-db.zip).

The organisation has asked for the following reports to be generated:

-   All the countries in the world organised by largest population to
    smallest.
-   All the countries in a continent organised by largest population to
    smallest.
-   All the countries in a region organised by largest population to
    smallest.
-   The top `N` populated countries in the world where `N` is provided
    by the user.
-   The top `N` populated countries in a continent where `N` is provided
    by the user.
-   The top `N` populated countries in a region where `N` is provided by
    the user.
-   All the cities in the world organised by largest population to
    smallest.
-   All the cities in a continent organised by largest population to
    smallest.
-   All the cities in a region organised by largest population to
    smallest.
-   All the cities in a country organised by largest population to
    smallest.
-   All the cities in a district organised by largest population to
    smallest.
-   The top `N` populated cities in the world where `N` is provided by
    the user.
-   The top `N` populated cities in a continent where `N` is provided by
    the user.
-   The top `N` populated cities in a region where `N` is provided by
    the user.
-   The top `N` populated cities in a country where `N` is provided by
    the user.
-   The top `N` populated cities in a district where `N` is provided by
    the user.
-   All the capital cities in the world organised by largest population
    to smallest.
-   All the capital cities in a continent organised by largest
    population to smallest.
-   All the capital cities in a region organised by largest to smallest.
-   The top `N` populated capital cities in the world where `N` is
    provided by the user.
-   The top `N` populated capital cities in a continent where `N` is
    provided by the user.
-   The top `N` populated capital cities in a region where `N` is
    provided by the user.
-   The population of people, people living in cities, and people not
    living in cities in each continent.
-   The population of people, people living in cities, and people not
    living in cities in each region.
-   The population of people, people living in cities, and people not
    living in cities in each country.

Additionally, the following information should be accessible to the
organisation:

-   The population of the world.
-   The population of a continent.
-   The population of a region.
-   The population of a country.
-   The population of a district.
-   The population of a city.

Finally, the organisation has asked if it is possible to provide the
number of people who speak the following the following languages from
greatest number to smallest, including the percentage of the world
population:

-   Chinese.
-   English.
-   Hindi.
-   Spanish.
-   Arabic.

### Country Report

A country report requires the following columns:

-   Code.
-   Name.
-   Continent.
-   Region.
-   Population.
-   Capital.

### City Report

A city report requires the following columns:

-   Name.
-   Country.
-   District.
-   Population.

### Capital City Report

A capital city report requires the following columns:

-   Name.
-   Country.
-   Population.

### Population Report

For the population reports, the following information is requested:

-   The name of the continent/region/country.
-   The total population of the continent/region/country.
-   The total population of the continent/region/country living in
    cities (including a %).
-   The total population of the continent/region/country not living in
    cities (including a %).

## Group Submission

The coursework **must** be delivered by a group. The aim of the module
is to assess your ability to work as a team to deliver a product.
Therefore, the majority of your coursework grade will be based on your
team’s ability to work together using the methods defined in the module.

The submission is monitored during lab stand-up meetings, and formally
via the 4 assessment points. Your submissions are delivered via your
GitHub repository. The master branch of your GitHub repository should
also be submitted to Moodle at each assessment point along with a
spreadsheet in Excel format (csv, xls or xlsx) detailing Individual team
members’ contributions.

## Individual Assessment

Individual contributions to the team will be assessed by your peers and
the module teaching team based on attendance at the various meetings and
individual contributions towards each code review, and via the metrics
gathered from tools such as GitHub. **Individual contributions will lead
to a scaling of the overall coursework grade if the module team have
evidence that illustrates a lack of contribution to the team
deliverable.**

#### Groups must maintain a spreadsheet detailing individual team members contribution at each of the assessment points. Use the Excel Template On Moodle for this.

We wish to determine the individual contribution to the team project. To
do this, the team have to submit a single spreadsheet to Moodle defining
the agreed contribution of each team member to the individual delivery
points. This should be submitted in percentages with the total sum of
individual contributions adding up to 100% at each point of assessment.
For example:

<table>
<colgroup>
<col style="width: 14%" />
<col style="width: 16%" />
<col style="width: 23%" />
<col style="width: 23%" />
<col style="width: 23%" />
</colgroup>
<thead>
<tr>
<th>Matriculation Number</th>
<th>Code Review 1</th>
<th>Code Review 2</th>
<th>Code Review 3</th>
<th>Code Review 4</th>
</tr>
</thead>
<tbody>
<tr>
<td>4000xxxx</td>
<td>25</td>
<td>50</td>
<td>0</td>
<td>25</td>
</tr>
<tr>
<td>4000xxxx</td>
<td>25</td>
<td>50</td>
<td>50</td>
<td>25</td>
</tr>
<tr>
<td>4000xxxx</td>
<td>25</td>
<td>0</td>
<td>50</td>
<td>25</td>
</tr>
<tr>
<td>4000xxxx</td>
<td>25</td>
<td>0</td>
<td>0</td>
<td>25</td>
</tr>
<tr>
<td><strong>Total</strong></td>
<td><strong>100</strong></td>
<td><strong>100</strong></td>
<td><strong>100</strong></td>
<td><strong>100</strong></td>
</tr>
</tbody>
</table>

The team need to agree these scores. **If the team cannot agree, or a
team member believes the spreadsheet submitted does not represent the
actual contributions, then contact a member of the teaching team.** In
these circumstances, the metrics and other information provided on
GitHub will be used.

The data supplied in this spreadsheet will be used to weight each team
members final mark for each assessment point.

For example, if the group received 18 out of 20 for code review one then
all 4 members would get the full 18 marks as all had contributed
equally. For code review 2 Members 1 & 2 would get the group mark but
Members 3 & 4 would receive zero

## Disciplinary Procedures

The coursework **must** be delivered as part of a team. **If anyone is
dismissed from their team this means they cannot deliver the coursework
and will fail.** Dismissal from a team involved the following process:

-   An individual is evidenced as breaching the code of conduct as
    set-out by the student team.
-   Evidence is presented at the next available meeting with a member of
    the module delivery team.
-   The individual evidenced will have the opportunity to evidence
    mitigating circumstances either to the student team or privately to
    a member of the module delivery team.
-   The module delivery team retains the right to the final decision of
    whether the dismissal is warranted.

Any dismissed team member has a week to appeal the decision to the
module team with suitable evidence provided.

## Code Review Meetings

Each group will undertake **four** graded code reviews:

Note that Teaching starts in Week 2. Week Commencing 15th September

1.  Week 4 Code Review 1 (25% of CW mark).
2.  Week 6 Code Review 2 (25% of CW mark).
3.  Week 9 Code Review 3 (25% of CW mark).
4.  Week 12 Code Review 4 (25% of CW mark).

The code reviews will take place during your usual Lab sessions. Each
group will be given **15 minutes maximum** for the code review. Your
group will be **allocated a time for the code review**. The details of
the individual review points are below. These meetings **must be
attended** at the **stated time**. Guidelines for grading the group:

-   **Being late** for the meeting or **not being ready** when the
    meeting starts will result in the grade for that review being capped
    at 40%.
-   **Not attending** the meeting will mean the code review will be
    marked at 0%.

**All team members** should attend the code review, however commitments
and other considerations will be taken into account. **Individuals
attendance at reviews will be monitored** to ensure the team is
contributing collectively to the project.

**Being ready** means that you are ready to present the points for the
code review. This means that you have a computer with the various tools
logged into (e.g., GitHub, etc.) and a building version of the
application in IntelliJ.

Note that the Code Review are graded out of 20 but each is worth 25% of
the coursework marks

### Code Review 1

#### REVIEW MEETING: Lab of Week 4

The aim of this code review meeting is to check that the project
workflow is set-up for the team. You may choose to meet some of the
feature requirements during this review point, but it is not as
necessary.

#### Checklist Submission 1 (16 marks)

The following must be in place:

-   GitHub project for coursework set-up.
-   Product Backlog created.
-   Project builds to self-contained JAR with Maven.
-   Dockerfile for project set-up and works.
-   GitHub Actions for project set-up and build is working using JAR,
    and Docker on GitHub Actions.
-   Correct branches for GitFlow workflow created - includes `master`,
    `develop`, and `release` branches.
-   First release created on GitHub.
-   Code of Conduct defined.

#### Graded Criteria Submission 1 (4 marks)

The following criteria will be assessed for overall quality:

-   Metrics from GitHub. Also used to assess individual contribution.
-   Code quality including comments.

### Code Review 2

#### REVIEW MEETING: Lab of Week 6

The aim of this code review is to check that task management is set-up
and that the initial requirements gathering has taken place via user
stories and use cases. You should have completed at least 25% of the
work for the project at this point based on your own estimates.

#### Checklist Submission 2 (14 marks)

The following must be in place:

-   Issues being used on GitHub.
-   Tasks defined as user stories.
-   Issues integrated with GitHub Projects (Kanban).
-   Kanban/Project Board being used.
-   Evidence of Sprints being used.
-   Full use cases defined.
-   Use case diagram created.

#### Graded Criteria Submission 2 (6 marks)

The following criteria will be assessed for overall quality:

-   Metrics from GitHub. Also used to assess individual contribution.
-   Code quality including comments.
-   Correct usage of branches.
-   Continuous integration working.
-   Use cases well defined.
-   Project requirements met.

### Code Review 3

#### REVIEW MEETING: Lab of of Week 9

The aim of this code review is to check that testing has been correctly
specified. At this stage, at least 50% of the work of the project should
be completed.

#### Checklist Submission 3 (12 marks)

The following must be in place:

-   Suitable unit tests defined.
-   Suitable integration tests defined.
-   Tests running on GitHub Actions.

#### Graded Criteria Submission 3 (8 marks)

The following criteria will be assessed for overall quality:

-   Metrics from GitHub. Also used to assess individual contribution.
-   Code quality including comments.
-   Correct usage of branches.
-   Continuous integration working.
-   Kanban/Project Board being used.
-   Quality and coverage of unit tests.
-   Project requirements met.

### Code Review 4

#### REVIEW MEETING: Lab of Week 12

The aim of this code review is to check that the project is deploying
correctly. At this stage, at least 75% of the work of the project should
be completed.

#### Checklist Submission 4 (10 marks)

The following must be in place:

-   Deployment working.
-   Bug reporting system set-up.

#### Graded Criteria Submission 4 (10 marks)

The following criteria will be assessed for overall quality:

-   Metrics from GitHub. Also used to assess individual contribution.
-   Code quality including comments.
-   Correct usage of branches.
-   Continuous integration working.
-   Kanban/Project Board being used.
-   Quality and coverage of unit tests.
-   Project requirements met.

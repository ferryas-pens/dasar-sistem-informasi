*PART II INFORMATION AS SOMETHING OF VALUE*

*Chapter 4*

*Information Quality*

*Chapter Map*

*Sub-CPMK (Course Learning Outcome):* Able to explain the dimensions of quality and value of information and their relationship to decision-making at each management level.

This chapter covers the first part of the Sub-CPMK, which is the dimensions of quality. The second part, information value and decision-making, is covered in Chapter 5.

After reading this chapter, you will be able to:
1. List the seven dimensions of information quality along with their respective testing questions;
2. Explain how each dimension degrades and its consequences on decisions;
3. Explain why all seven dimensions cannot be maximized simultaneously;
4. Evaluate the quality of an actual output using these seven dimensions;
5. Determine which dimension can be sacrificed for a specific decision.

*Prerequisites:* Chapter 1 for the difference between data and information, Chapter 2 for the four components of information systems.

*Keywords:* Accuracy, timeliness, completeness, relevance, consistency, traceability, accessibility, trade-off.

*Deliverable:* A written assessment of the quality of an actual output, accompanied by a determination of which dimension is most critical for the decision it serves.

---

*The Right Number that Has Already Expired*

It is study plan registration day. You log into the academic system at two minutes past eight and search for a class with a matching schedule. The system displays the remaining quota for that class: three.

You select the class, double-check the schedule to ensure there are no conflicts, and click the save button. A message appears stating that the class quota is full.

The number three was not wrong. It was accurate when the page loaded four minutes earlier. During those four minutes, three other people pressed the save button before you did.

Notice that there was no calculation error anywhere. The system did not sum incorrectly, did not misread the database, and did not display the wrong data. What was wrong was your assumption that a correct number would remain useful several minutes later.

This illustrates the core theme of this chapter: being correct and being useful are two different properties, and an item of information can have one without the other.

---

### 4.1 Information Quality Is Not Just One Thing

When people evaluate information, their assessment almost always stops at a single question: is it correct or not? That evaluation is too narrow, and its narrowness incurs real costs.

The opening story shows information that was accurate but late. There is also information that is accurate but incomplete, accurate but unrelated to the decision at hand, or accurate but inaccessible to the person who needs it. These four conditions have different causes and require different remedies.

> **Information quality is a set of properties that must be satisfied together, not a single property. Information can excel in several properties while failing completely in others.**

---

### 4.2 The Seven Dimensions

This book uses seven dimensions. The count varies across literature, but the exact number is unimportant. What matters is that each dimension has its own testing question so that evaluation moves beyond mere impression.

***Figure 4.1 The Seven Dimensions of Information Quality and Their Testing Questions***

Using them is straightforward: take an actual output, ask the seven questions one by one, and write down the answers. Any dimension for which you cannot provide an answer is a dimension that no one has ever audited.

---

### 4.3 How Each Dimension Degrades

Knowing the names of the dimensions is of little help by itself. What helps is recognizing the symptoms of their failure, as those are what you will encounter first in the field.

* **Accuracy** degrades when record content does not match reality. The cause can be a simple typo or careless data entry by someone who finds the field nonsensical. The second cause is far more common and much harder to detect because the result appears plausible.
* **Timeliness** degrades when information arrives after a decision has already been made. Note that this dimension does not mean "fast." A monthly report published on the third is timely if the decision is made on the fifth, but useless if the decision is made on the first.
* **Completeness** degrades when parts are missing without notice. Explicitly stated gaps do not destroy completeness; hidden gaps do, because the reader will assume the information received is whole.
* **Relevance** degrades when the presented information is unrelated to the decision being made. This is the most frequently overlooked failure because irrelevant information remains correct and appears useful on the surface.
* **Consistency** degrades when two sources give different numbers for the same item. The impact is larger than it seems: as soon as people find two conflicting numbers, trust in both is lost simultaneously, including the one that was actually correct.
* **Traceability** degrades when no one can show where a number came from. Untraceable information cannot be corrected because it is impossible to identify which part needs fixing.
* **Accessibility** degrades when information exists but fails to reach the person who needs it. A report neatly stored in a folder that is never opened satisfies the first six dimensions and fails on the seventh—and that failure alone renders it useless.

---

### 4.4 All Seven Cannot Be Maximized Simultaneously

After reading about the seven dimensions, the temptation is to demand all of them at once. That temptation must be resisted because several dimensions directly conflict with one another.

***Figure 4.2 The Three Most Common Trade-offs***

The first trade-off is the most common. Waiting for completeness causes delays, while delivering faster means some data will be missing. There is no middle ground that satisfies everyone, and the right to choose belongs to the person making the decision, not the person preparing the report.

The third trade-off is often ignored because it seems trivial. A more complete report is always longer, and a longer report is read to the end far less frequently. Adding pages for the sake of completeness can lower the overall quality of the information, even if every additional page is entirely accurate.

> **Information quality is not a state of maximum achievement, but a conscious compromise chosen for a specific decision.**

---

### 4.5 Who Determines What Is "Enough"

If quality is a compromise, someone must choose that compromise. The question is who.

The conventional answer is the system developer, but that answer is wrong. System developers do not bear the consequences if the compromise is wrong. The person who bears the consequences is the decision-maker relying on that information, and therefore they hold the right to determine what is sufficient.

For you as a prospective designer, this means building a habit starting now: when someone requests a report, do not stop at asking about its content. Ask what decision will be made based on that report and how quickly that decision must be taken. Without those two pieces of context, you have no basis for choosing any compromise, and you will typically end up picking whatever is easiest to build.

---

### 4.6 Information Quality vs. Data Quality

These two terms sound similar and are often used interchangeably, yet their scopes are distinct.

| | **Data Quality** | **Information Quality** |
| --- | --- | --- |
| **What is evaluated** | The content of the record itself | The usefulness of the record for a specific decision |
| **Can be evaluated without knowing the decision?** | Yes | No |
| **Example of defect** | Misspelled street address | Correct address, but entirely unneeded |

The second row is the differentiator. Data quality can be inspected by anyone reviewing the records. Information quality cannot be evaluated without knowing what decision it serves, because relevance and timeliness only make sense in relation to a specific decision.

Techniques for auditing and cleaning data are covered in database courses. What is practiced here is the layer above: evaluating whether clean data actually helps someone make a decision.

---

> **Behind the Scenes: Why the Remaining Quota You Saw Was Outdated**
> 
> When the course selection page loads, the system reads the remaining quota once and sends that number to your phone or computer. From that moment on, the number you see is a copy. It does not change even if the state at the data center changes every second.
> 
> Refreshing that number continuously is not impossible, but it carries a real cost. Thousands of students opening the same page at the same time generate thousands of requests per second, precisely when system load is at its peak during registration day.
> 
> Therefore, almost all systems choose a compromise: display the number as-is upon page load, and verify its accuracy only when the save button is pressed. That final check is what rejected your request.
> 
> This compromise sacrifices timeliness for accessibility, because without it, the system might crash completely during peak hours. This is a real-world example of Figure 4.2, and proof that such trade-offs are deliberately chosen by humans, not occurring by accident.

---

> **Common Misconceptions**
> 
> * **"Accurate information is always useful."** Accuracy is only one of seven dimensions. Information that is accurate but late, irrelevant, or unreachable is completely useless.
> * **"The more complete, the better."** Completeness trades off with timeliness and accessibility. A more detailed report takes longer to publish and is less likely to be read entirely.
> * **"Information quality is a technical matter."** Most quality issues originate from human and process components, as seen in Chapter 2. A field filled carelessly by an operator degrades accuracy without any technical system error occurring.

---

### Guided Case Study: Exam Schedule Board

A department posts the final exam schedule as an image file on an announcement webpage. The file contains all courses, classes, dates, times, and room assignments. When changes occur, a new file is uploaded and the old one is deleted, without any notes explaining what was changed.

Evaluate the quality of this information output using the seven dimensions:

| **Dimension** | **Evaluation** | **Reasoning** |
| --- | --- | --- |
| **Accuracy** | Good | Content is compiled from official departmental data. |
| **Timeliness** | Doubtful | Students cannot tell when the file was last updated. |
| **Completeness** | Good | All courses and classes are included. |
| **Relevance** | Poor | A student needs 6 lines but receives 300 lines. |
| **Consistency** | Doubtful | Some students still hold saved copies of the older file version. |
| **Traceability** | Poor | There is no version number or changelog. |
| **Accessibility** | Moderate | Downloadable, but difficult to read on mobile screens. |

#### Reading the Assessment Results
The first three dimensions are good or fair, which is precisely why the creator felt their work was finished. The defects concentrate in the final four dimensions, none of which can be fixed by double-checking the schedule's content.

Note how poor traceability exacerbates poor consistency. If a version number were present, a student holding an older copy could realize it was outdated. Without versioning, two students can argue over exam times, both convinced their file is correct.

#### Proposed Improvements (Ordered by Cost)
1. **Add dates and version numbers to the file.** Almost zero cost; fixes traceability while mitigating consistency issues.
2. **Include a short changelog with every new upload.** Takes a few minutes each time; eliminates the need for students to manually compare two files.
3. **Provide filtering by class.** Fixes relevance and accessibility simultaneously, but carries the highest cost as it requires changing how schedules are constructed and presented rather than just uploaded.

This sequence is intentional. The first two proposals fix four dimensions at almost no cost. The third fixes two dimensions at a much higher cost. If time is limited, execute the low-cost improvements first and clearly communicate that the high-cost solution remains pending.

#### Self-Critique of the Assessment
1. The evaluation above assumes the student's perspective. From the academic office's perspective, relevance is high because they genuinely need the entire schedule at once. Information quality is always tied to its user, and an assessment that omits the target user is incomplete.
2. This assessment does not verify whether the schedule itself is correct. The seven dimensions assume the underlying data is correct. If the source content is flawed, all improvements above merely make those errors easier to access.

---

### Summary

* Being correct and being useful are two different properties. Information can possess one without the other.
* Information quality consists of seven dimensions, each with its own testing question.
* Timeliness does not mean "fast." It means arriving before a decision needs to be made.
* Declared omissions do not ruin completeness. Hidden omissions do.
* As soon as people encounter conflicting figures for the same item, trust in both is lost simultaneously.
* The seven dimensions cannot be maximized all at once. Quality is a deliberate compromise.
* The authority to choose the compromise lies with the decision-maker, not the report creator.
* Data quality can be assessed without knowing the decision context. Information quality cannot.

---

### Exercises

#### Level A: Remembering
1. List the seven dimensions of information quality and their respective testing questions. `[Sub-CPMK-2]`
2. Why is timeliness not synonymous with speed? Provide an example. `[Sub-CPMK-2]`
3. Explain why a loss of consistency causes greater damage than it appears to on the surface. `[Sub-CPMK-2]`
4. List three inter-dimension trade-offs and state who has the authority to decide each. `[Sub-CPMK-2]`
5. What is the difference between data quality and information quality? `[Sub-CPMK-2]`

#### Level B: Applying
1. Select an actual output from your campus academic system (e.g., Study Plan Card or Grade Transcript). Evaluate its quality across all seven dimensions using a table similar to the case study. `[Sub-CPMK-2]`
2. For every dimension you rated poorly in Question 1, write a proposed improvement along with an estimated implementation effort/cost, ordered from lowest to highest cost. `[Sub-CPMK-2]`
3. Refer to Figure 4.2. Identify a fourth trade-off that you frequently observe, and explain who holds the authority to decide it. `[Sub-CPMK-2]`

#### Level C: Analyzing & Evaluating
1. An organization claims its reports are of high quality because all figures are double-checked. Critique this statement. Which dimensions are guaranteed by double-checking, and which are completely unaddressed by it? Format your response as a formal memo to leadership without sounding combative. `[Sub-CPMK-2]`
2. Pick an output you consider to be of poor quality, then defend the opposite position: argue that the output is actually sufficient for a specific decision. Clearly specify what that decision is. (This exercise tests your understanding of how quality is intrinsically tied to the user.) `[Sub-CPMK-2]`

---

### References
1. Laudon, K. C., & Laudon, J. P. *Management Information Systems: Managing the Digital Firm*. Pearson (Latest Edition). Section on Information and Data Quality.
2. Rainer, R. K., Prince, B., & Watson, H. *Introduction to Information Systems*. Wiley (Latest Edition). Section on Attributes of Information.
3. Bourgeois, D. *Information Systems for Business and Beyond*. Open Textbook. Chapter on Data and Information.

---

### Appendix: List of Figures
*This page is not printed in the book. Both vector figures are completed and ready.*

| No. | Title | Print Height | Status |
| --- | --- | --- | --- |
| 4.1 | Seven dimensions of information quality and their testing questions | 3.0 inches | Complete |
| 4.2 | Three most common trade-offs | 2.1 inches | Complete |
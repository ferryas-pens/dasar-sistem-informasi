**PART I UNDERSTANDING INFORMATION SYSTEMS**

**Chapter 1**

**Systems, Data, and Information**

# **Chapter map**

**Sub-CPMK addressed.** Able to explain the concepts of system, data, and information, the components of an information system, and the roles and professions in the field of information systems.

This is the first chapter of the book and the first chapter you read in this course. It requires no prior knowledge whatsoever. What is trained here is a single skill: seeing something as a system, and knowing what that implies for the way you will work later.

After reading this chapter you will be able to:

1.  explain what is meant by a system, together with its elements;

2.  draw the boundary of a system and defend where that boundary is placed;

3.  distinguish data, information, and knowledge using your own examples;

4.  explain why an information system is not a synonym for an application;

5.  recognise that a system boundary is a decision, not something that is discovered.

**Prerequisite chapter.** None.

**Keywords.** System, element, boundary, environment, input, process, output, feedback, data, information, knowledge.

**What you will produce.** One written statement about the boundary of a system you choose, together with the reasons why one element is included and another is not.

# **Eighty-seven**

The number eighty-seven.

So far, that number means nothing. It could be an exam score, a body weight, the number of seats in a lecture hall, the price of something in thousands of rupiah, or a house number. There is nothing you can do with it.

Now add a single note: eighty-seven is your final exam score in this course. The same number, but now you can do something. You know whether you must retake it, whether you need to see the lecturer, or whether you can accept that score.

What changed is not the number. What changed is the presence of a note about what was measured, who was measured, and what it relates to. That note is what turns data into information, and the difference between the two is one of the two things discussed in this chapter.

The second thing is larger. Before you can talk about data and information, you need a way of looking that holds both. That way of looking is called a **system**.

# **1.1 The system as a way of looking**

The word *system* is used every day for almost anything. There is the digestive system, the solar system, the queueing system, the operating system, and the academic information system. Because it is applied to so many things, the word feels unclear.

That unclarity vanishes the moment you realise one thing: a system is not a kind of object, but a way of looking at objects.

|                                                                                                                        |
|------------------------------------------------------------------------------------------------------------------------|
| *A system is a set of interrelated elements that work toward a single goal and are separated from their surroundings by a boundary.* |

Notice that this definition can be applied to anything, and that is not a weakness but its usefulness. When you look at something as a system, you are deciding to attend to the relationships between its parts, rather than to the parts one by one.

This difference in perspective has real consequences. Someone who views traffic congestion as a collection of undisciplined drivers will propose enforcement. Someone who views it as a system will ask about traffic lights, school start times, and the location of markets. Both see the same event and propose different things.

# **1.2 The elements of a system**

A system described in full contains five elements.

<img src="asset/bab-01-gambar-1.png" style="width:4.76042in;height:2.02083in" />

**Figure 1.1 The elements of a system and its boundary**

**Input** is anything that comes from outside and is processed by the system. **Process** is the processing itself. **Output** is the result returned to the outside.

**Feedback** is a note about the output that is used to correct the next input or process. This element is what distinguishes a system that can correct itself from a system that keeps repeating the same error without end.

**The boundary** separates the system from its **environment.** The environment influences the system but cannot be controlled by it. For an academic information system, for instance, ministry policy sits in the environment: it influences the system but cannot be changed by it.

Of the five elements, feedback is the one most often missing in a beginner's design. A system without feedback can run for years while producing incorrect output, because there is no path for that error to return.

# **1.3 The boundary is a decision, not a discovery**

This section contains the most important idea in the chapter, and that idea runs counter to the usual way of thinking.

When someone is asked to describe a system, they usually look for a boundary that is already there, as though the boundary were merely waiting to be found. In reality it is not so. The boundary is set by the person doing the describing, and that placement depends on the question they intend to answer.

Take the course-registration service as an example. If the question is why the page was slow on the first day, the useful boundary includes the software, the campus network, and the number of students accessing it at the same time. If the question is why many students chose the wrong class, the useful boundary includes the students, the academic advisors, and the way the schedule is arranged, whereas network speed is not relevant at all.

|                                                                                                                                                                       |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| *The correct boundary is not the boundary that matches reality, but the boundary that is wide enough to hold the problem you are investigating and narrow enough to be solvable.* |

Because the boundary is a decision, it must be stated. A model that does not state its boundary will be read by others as a picture of the whole situation, and that can mislead. This habit of stating the boundary is one you will use again in Chapter 7 when drawing process models.

# **1.4 Data, information, and knowledge**

Now return to the number 87.

<img src="asset/bab-01-gambar-2.png" style="width:4.76042in;height:2.51042in" />

**Figure 1.2 Data, information, and knowledge**

**Data** is a raw record of something that happened. It is not yet meaningful on its own, and precisely for that reason it can be stored in very large quantities.

**Information** is data that has been given a note so that it can answer someone's question. Note the last word. Without someone asking, there is no information, only neatly arranged data.

**Knowledge** is a pattern that holds across many events, so that it can be used to anticipate the next event. It is formed from a great deal of information gathered and tested repeatedly.

The difference among the three is not a difference in degree of sophistication, but a difference in reach. Data applies to one event, information to one question, and knowledge to many events that have not yet happened.

## **1.4.1 Why this distinction is useful**

This distinction is not merely a matter of terms. It determines where the problem lies when something does not work.

| **The complaint you hear**                              | **Where the problem lies** | **What to check**                          |
|---------------------------------------------------------|----------------------------|--------------------------------------------|
| "The data isn't there."                                 | Data layer                 | Was the event actually recorded?           |
| "The data is there but it doesn't answer my question."  | Information layer          | Was the question ever formulated?          |
| "We have the report but we still decided wrong."        | Knowledge layer            | Does the pattern really exist, or is it coincidence? |

These three complaints sound similar and demand entirely different fixes. The ability to tell them apart already makes you more useful than someone who immediately offers an application for all three.

# **1.5 An information system is not a synonym for an application**

By this point you have two ingredients: a way of looking at something as a system, and the distinction between data, information, and knowledge. The two can be joined.

|                                                                                                                                                                       |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| *An information system is a system that collects, processes, stores, and distributes information to help people make decisions within an organisation.* |

Notice that the definition does not mention software at all.

A laundry outlet that uses a notebook, numbered receipts, and an agreement that the receipt is always clipped to the laundry bag is already running an information system. It collects, processes, stores, and distributes information. It helps people make decisions. That its tools are paper rather than a database does not change its status as an information system.

Conversely, an application that no one uses, or that is used but does not help in making any decision, is not a successful information system even if its software is flawless. You will meet examples of this kind in Chapter 5 and Chapter 9.

For Informatics Engineering students, this distinction will feel unsettling at first, and it should. Over the next eight semesters you will learn to build software. This course is a reminder that software is only one part of something larger, and that the other parts are far more often the cause of failure.

# **1.6 What is not covered here**

This chapter introduces a way of looking, not a way of building. Several things you might expect to find here are deliberately deferred or omitted.

- General systems theory as a field of study in its own right is not discussed. Only the part useful for seeing organisations is taken.

- The four components of an information system are discussed in Chapter 2, so this chapter deliberately stops before reaching them.

- How to store data and design where it is stored is part of the scope of the Databases course.

- How to build software is the scope of the programming and software-engineering courses.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Behind the scenes: one tap and several systems</strong></p>
<p>When you press the save button on course registration, what happens next is a crossing of several systems with different boundaries, each maintained by different people.</p>
<p>There is a system that makes sure you are really you. There is a system that holds the list of courses along with their quotas. There is a system that checks whether you have paid your tuition (UKT). And there is a system that records that your request occurred, so it can be traced if a dispute arises later.</p>
<p>To you, it all looks like a single button. To the people who maintain it, these are several separate systems that happen to work together, and most of the problems arise precisely at the borders between them.</p>
<p>Notice that these four systems are not separated by a natural boundary. Someone, at some point, decided that the payment check is a system of its own and not part of course registration. That decision may be sound, or it may simply be an inheritance from an organisational arrangement that no longer exists.</p></td>
</tr>
</tbody>
</table>

# **Guided case study: drawing the boundary on course registration**

This section works through one boundary-drawing from beginning to end, and shows that different questions yield different boundaries.

## **First question: why the page was slow on the first day**

| **Inside the boundary**   | **In the environment**              | **Entirely outside**       |
|---------------------------|-------------------------------------|----------------------------|
| The registration software | Number of students accessing        | How the class schedule is arranged |
| The campus data centre    | The simultaneous-opening policy     | Course content             |
| The campus network        | Students' mobile networks           | Teaching quality           |

Look at the second column. The number of students accessing at the same time affects the slowness, but it cannot be controlled by the system, so it sits in the environment, not inside the boundary. Distinguishing the two matters, because what is in the environment can only be anticipated, not fixed.

## **Second question: why many students chose the wrong class**

| **Inside the boundary**                | **In the environment**              | **Entirely outside** |
|----------------------------------------|-------------------------------------|----------------------|
| The student and how they choose        | The work schedule of working students | Network speed      |
| The class-list display                 | The habit of asking friends for advice | Data-centre capacity |
| The academic advisor and how they approve | The academic calendar             | Hardware             |

Compare the two tables. Network speed moves from inside the boundary to entirely outside. The student moves from unmentioned to being the central element. The service is the same, the people are the same, and the day is the same. The only thing that changed is the question.

## **What this comparison shows**

If you are later asked to fix something and immediately start drawing, you are making a decision about the boundary without realising it. A decision made unawares cannot be examined, debated, or improved.

The correct habit is to write down the question first, in a single sentence, before drawing anything. That habit sounds excessive for small problems, and it is precisely on large problems that it saves weeks.

## **A critique of my own result**

1.  The two tables above were drawn up from general knowledge about academic services, not from observation of a particular service. In an actual service, several elements might move columns. Drawing up a table of this kind without checking the field is useful as an exercise, but dangerous as the basis for a decision.

2.  Dividing things into three columns makes everything look clear, when in fact many elements sit on the border between columns. The number of students accessing at the same time, for instance, can be partly controlled by staggering the opening schedule. When an element can be moved inside the boundary by changing a policy, placing it in the environment is really a choice, not a fact.

# **Summary**

- A system is not a kind of object, but a way of looking at objects.

- A system contains input, process, output, feedback, and a boundary that separates it from its environment.

- Feedback is the element most often missing, and without feedback an error can repeat indefinitely.

- The boundary is set by the person doing the describing, depending on the question to be answered.

- The correct boundary is wide enough to hold the problem and narrow enough to be solvable.

- Data applies to one event, information to one question, and knowledge to many events that have not yet happened.

- Without someone asking, there is no information, only neatly arranged data.

- An information system does not require software. A notebook, numbered receipts, and an agreement are enough.

# **Exercises**

Each item is marked with the Sub-CPMK it measures.

## **Level A Making sure you remember**

1.  Name the five elements of a system and explain the role of each. \[Sub-CPMK-1\]

2.  Why is feedback called the element most often missing, and what are its consequences? \[Sub-CPMK-1\]

3.  Explain the difference between a boundary and an environment, with one example. \[Sub-CPMK-1\]

4.  Distinguish data, information, and knowledge with your own example, not an example from this book. \[Sub-CPMK-1\]

5.  Why is a laundry outlet that uses a notebook still said to run an information system? \[Sub-CPMK-1\]

## **Level B Applying**

1.  Choose one service you use on campus. Draw its elements as in Figure 1.1, complete with feedback. If you think there is no feedback, simply say so. \[Sub-CPMK-1\]

2.  For the service in question 1, build a three-column table as in the case study for one question of your own choosing. Write the question down first in a single sentence. \[Sub-CPMK-1\]

3.  Take one complaint you have heard about a campus service. Determine whether the problem lies in the data layer, the information layer, or the knowledge layer, and explain your reasoning. \[Sub-CPMK-1\]

## **Level C Analysing and evaluating**

1.  Redo question 2 of Level B for the same service, but with a different question. Compare the two tables and show which elements move columns. Write one paragraph on what that movement means for someone who wants to improve the service. \[Sub-CPMK-1\]

2.  A friend claims that this course is useless for Informatics Engineering students because it does not teach how to build anything. Write a one-page written response. A good response does not defend this course blindly, but acknowledges which part of your friend's objection is reasonable. \[Sub-CPMK-1\]

# **Chapter references**

1.  Laudon, K. C. and Laudon, J. P. *Management Information Systems: Managing the Digital Firm.* Pearson, latest edition. The opening chapter on information systems and organisations.

2.  Bourgeois, D. *Information Systems for Business and Beyond.* Open textbook. The chapter on what an information system is.

3.  Alter, S. (2013). "Work System Theory: Overview of Core Concepts, Extensions, and Challenges for the Future." *Journal of the Association for Information Systems,* 14(2). For readers who wish to pursue the idea of systems further.

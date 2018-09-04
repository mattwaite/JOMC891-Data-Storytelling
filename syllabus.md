# JOMC 891 Data Storytelling
__Term Year__  

Instructor: Matt Waite  
Email: mwaite3@unl.edu  
Twitter: @mattwaite  
Phones: (402) 802-5202 cell, (402) 472-5840 office  
Office: 244 Andersen  

__Course description:__  

Every day, more of our lives are being stored in a database somewhere. With that explosion of data, storytellers now more than ever need the skills to analyze and understand data to then produce the stories hidden in the information. In this class, we’ll use brainpower and software to look at raw data -- not summarized and already reported information -- to reveal insights and build strong narratives. We’re going to get our hands dirty with code, data, basic stats and the thinking that goes with it. And we're going to write stories from our analysis. So buckle up and hold on.

__Prerequisites:__

None.

__Course goals:__  

* Understand the basics of data and data journalism, including the history of the practice
* Master the use of data in storytelling
* Master basic data analysis for storytelling
* Master the use of analysis libraries and the tools of transparency for data storytelling.

__Required Materials:__  

* A functioning laptop computer and ~800 MB of free hard drive space.
* The administrative privileges to install software on your computer.
* A copy of [Numbers in the Newsroom](http://store.ire.org/products/numbers-in-the-newsroom-using-math-and-statistics-in-news-second-edition-e-version). $10.
* A copy of Data Literacy: A Users's Guide by David Herzog. Available in the bookstore and online.
* Online materials and class handouts, as needed.
* A sense of humor.

__Learning outcomes:__

By the end of this class, you should be able to:

* Use basic analysis techniques to find interesting insights in a dataset
* Use the R statistical language to create replicable workflows for analysis
* Use the R statistical language to create visuals of data for storytelling and insights
* Use storytelling techniques to make your data analysis interesting, approachable and readable by general audiences.  

__Grading:__  

The grading will be based on the stories you produce, the work you put into them and your participation in class.

The bulk of the graded work in this class is as follows:

|Assignment|Percentage of your grade|
|----------|------------------------|
|Data assignments|60%|
|Enterprise story|40%|

___Enterprise story___: You will be required to pitch and execute a data story on your own due at the end of the term. The story must include original analysis of data you have obtained, a graphic or visualization of that data and a story worth publishing.

___Assignments___: Throughout your analysis of data, you need to keep a running diary of what you have done -- what actions you took, commands you ran, thinking behind what you are doing. Yes, it will seem odd, but think of it like writing future you a note explaining how to do this again.

__Notes on keeping pace:__  

Yes, we all get sick. Yes, things happen. You’ve got no fewer than four ways to get ahold of me, including my cell number. If you are going to miss an assignment or a deadline, tell me before it is due. We’ll work it out. But you have to tell me before for me to help you.

This said: this class builds each lesson onto the next one. Miss something and you are behind. We’re going to be covering a lot of new material in this class. Fall behind at your own peril.

__Policies__

Here's the short version.

You cheat, you fail, no exceptions.

If I’m doing something that’s keeping you from learning, tell me. Tell the Dean. Tell someone, because that’s not cool. I won’t tolerate it from myself and you shouldn’t either.

Now the longer versions.

__ACEJMC Competencies__

After this class, you should be able to:

* Understand and apply the principles and laws of freedom of speech and press for the country in which the institution that invites ACEJMC is located, as well as receive instruction in and understand the range of systems of freedom of expression around the world, including the right to dissent, to monitor and criticize power, and to assemble and petition for redress of grievances;
* Demonstrate an understanding of the history and role of professionals and institutions in shaping communications;
* Demonstrate an understanding of gender, race ethnicity, sexual orientation and, as appropriate, other forms of diversity in domestic society in relation to mass communications;
* Demonstrate an understanding of professional ethical principles and work ethically in pursuit of truth, accuracy, fairness and diversity;
* Think critically, creatively and independently;
* Conduct research and evaluate information by methods appropriate to the communications professions in which they work;
* Write correctly and clearly in forms and styles appropriate for the communications professions, audiences and purposes they serve;
* Critically evaluate their own work and that of others for accuracy and fairness, clarity, appropriate style and grammatical correctness;
* Apply basic numerical and statistical concepts;
* Apply tools and technologies appropriate for the communications professions in which they work.

__Academic integrity:__  

Every student must adhere to the policy on academic integrity set forth in the UNL Student Code of Conduct as outlined in the UNL Bulletin. Students who plagiarize may receive a failing grade on an assignment or for an entire course and may be reported to the Student Judicial Review Board. The work a student submits in a class must be the student's own work and must be work completed for that particular class and assignment. Students wishing to build on an old project or work on a similar project in two classes must discuss this with both professors. Academic dishonesty includes:

*  handing in another's work or part of another's work as your own.
*  turning in one of your old papers (including something you wrote in high school) for a current class.
*  turning in the same or similar paper for two different classes,
*  using notes or other study aids or otherwise obtaining another's answers for a quiz or an examination.

Anything and everything you include in your papers that comes from another source must be attributed with proper citation. That includes ideas and opinions.
Plagiarism consists of using phrases, sentences or paragraphs from any source and republishing them without alteration or attribution. The sources include, but are not limited to, books, magazines, newspapers, television or radio reports, Web sites and other students’ papers.  

__Students with disabilities:__

Students with disabilities are encouraged to contact the instructor for a confidential discussion of their individual needs for academic accommodation. It is the policy of the University of Nebraska-Lincoln to provide flexible and individualized accommodation to students with documented disabilities that may affect their ability to fully participate in course activities or meet course requirements. To receive accommodation services, students must be registered with the Services for Students with Disabilities (SSD) office, 132 Canfield Administration, 472-3787 voice or TTY.  

__Diversity:__  

The College of Journalism and Mass Communications values diversity, in the broadest sense of the word – gender, age, race, ethnicity, nationality, income, religion, education, geographic, physical and mental ability or disability, sexual orientation. We recognize that understanding and incorporating diversity in the curriculum enables us to prepare our students for careers as professional communicators in a global society. As communicators, we understand that journalism, advertising and other forms of strategic communication must reflect society in order to be effective and reliable. We fail as journalists if we are not accurate in our written, spoken and visual reports; including diverse voices and perspectives improves our accuracy and truthfulness. In advertising, we cannot succeed if we do not understand the value of or know how to create advertising that reflects a diverse society and, thus, appeals to broader audiences.

## Class Schedule:

NOTE: If things change, I will update the syllabus on Canvas and I will update you.

UNLESS NOTED, DEADLINE 1 WILL BE WEDNESDAY AT MIDNIGHT CENTRAL TIME, DEADLINE 2 WILL BE SUNDAY AT MIDNIGHT CENTRAL TIME.

### Week 1

**Deadline 1:**

Covered: What is data journalism? Using Excel to find stories in data.

* The foundations of analysis: The general questions you ask.
* Summary statistics, central tendency, and more.
* Basic Spreadsheets: rows, columns, cells, importing, sorting, filtering
* Applied analysis basics: calculating the formula for percent change

Assignments:

* Read: [Chapter 1 of the Data Journalism Handbook](http://datajournalismhandbook.org/1.0/en/introduction.html)
* Read: Read Meyer Chapter 1 (on Canvas under Files) and realize it was (re)written in 2002.
* Read: Herzog Chapter 1.
* Read: The Myth of the Machine by Michael Berens in Nerds and Words in Files on Canvas. If you have time, read a few others (like Steve Doig) and realize that document was written in 1999.  
* Read: Numbers in the Newsroom, Chapters 1 and 2.
* Using tax data from the Nebraska Department of Revenue, calculate the following in Excel or Google Sheets:
* The change in Federal Adjusted Gross Income between 2000 and 2013 for every county in Nebraska.
* The average the number of exemptions per return in 2000 and 2013 for every county in Nebraska.
* The change in average Nebraska Net Taxable Income per return between 2000 and 2013 for every county in Nebraska.
* In narrative form, explain what you did. How did you arrive at the answers you got? What steps did you have to take?

**Deadline 2 :**

Covered: Replication, transparency and explanation

* Does anyone see the problem here?
* Reliability, replicability, transparency.
* Changing how we approach data journalism
* Analysis notebooks and data in R
* Explaining your steps and thinking
* General care and maintenance

Assignments:

* Read [Reducing barriers between programmers and non-programmers in the newsroom](http://towcenter.org/reducing-barriers-between-programmers-and-non-programmers-in-the-newsroom/)
* Read Data Journalism in the Age of Replicability in Files in Canvas
* Read The Data Diary in Files in Canvas

### Week 2

**Deadline 1:**

Covered: R Basics.

* Basic R concepts: Libraries, variables, operators, lists, functions, libraries.
* Working in the RStudio environment

Assignments:

* Read: Herzog chapters 2, 3 and 4.
* Read: [Sun Sentinel: Speeding Cops](http://www.sun-sentinel.com/news/local/speeding-cops/)

**Deadline 2:**

Covered: Aggregates

* Means, medians and sorting in R
* Working with NU salaries: Group by, counting, averages and medians by job titles.

Assignments:

* Read Herzog
* Read Numbers in the Newsroom
* Complete assignment at the end of the Aggregates walkthrough

### Week 3

**Deadline 1:**

Covered: Formats and Filters

* Converting to and from different data types  
* Converting factors to dates

Assignments:

* Read Herzog
* Read Numbers in the Newsroom
* Complete assignment at the end of the Formats and Filters walkthrough

**Deadline 2:**

Covered: Formulas

* Percent change in R
* Rates in R

Assignments:

* Read Herzog
* Read Numbers in the Newsroom
* Complete percent change calculations at the end of the walkthrough

### Week 4

**Deadline 1:**

Covered: Joins

* Why join?
* Types of joins
* Common joins in data storytelling

Assignments:

* Complete the join assignment at the end of the walkthrough
* Read Herzog

**Deadline 2:**

Covered: Statistics

* Regressions
* Significance testing

Assignments:

* Basic descriptive statistics assignment at the end of the walkthrough
* Read Numbers in the Newsroom

### Week 5

**Deadline 1:**

Covered: Data cleaning

* Sanity checks and data smells
* Basic sanity checks: Descriptives
* Data smells in Agate

Assignments:

* Install [Open Refine](http://openrefine.org/).
* Complete the data smells and data cleaning walkthrough


**Deadline 2:**

Covered: Charts I

* The Grammar of Graphics in R
* Bar, line and scatterplots as a reporting tool

Assignments:

* Read TBD
* Do the ggplot2 walkthrough and complete the assignment at the end

**Deadline 1:**

Covered: Charts II

* Waffle charts, treemaps and lattice charts

Assignments:

* Read TBD
* Do the other charts walkthrough and complete the assignment at the end.
* Develop a pitch for a story using data and the analysis techniques you have learned. It can be specific to your course of study or interests (i.e. professional journalism students should do a written story, strategic communications students should look at a white paper format, etc.) Submit your story pitch for review.

**Deadline 2:**

Covered: Maps I

* Setup and environment
* Attribute selection
* Buffering
* Spatial selection

Assignments:

* Reading TBD
* Complete the beginning maps walkthrough and the assignment at the end.

### Week 7

**Deadline 1:**

Covered: Maps II

* Spatial joins
* Attribute joins
* Chloropleth maps

Assignments:

* Reading TBD
* Complete the advance mapping walkthrough and the assignment at the end.  

**Deadline 2:**

Covered: Ethics

* Working with data on race and ethnicity
* Public vs. In Front of a Large Audience

Assignments:

* Read through the ethics walkthrough and complete the assignment at the end.
* Read [Handling Data on Race and Ethnicity](https://source.opennews.org/articles/handling-data-about-race-and-ethnicity/)
* Read [Public Info Doesn't Always Want To Be Free](https://source.opennews.org/articles/public-info-doesnt-always-want-be-free/)
* Read [The Ethics of Data Journalism](https://digitalcommons.unl.edu/cgi/viewcontent.cgi?article=1010&context=journalismprojects)  

### Week 8

**Deadline 1:**

Covered: Writing with numbers

* Writing with numbers
* Truth and epistemic justification

Assignments:

* Read [True Facts, Maybe](https://source.opennews.org/articles/true-facts-maybe/)
* Work on stories

**Deadline 2:**

Story edits. Sign up for individual edit times via Skype/Facetime/Hangout/Zoom, etc. 

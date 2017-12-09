## Assignment Overview:

+ A portfolio of at least 8 documents, composed in [MultiMarkdown](http://fletcherpenney.net/multimarkdown/) and [R Markdown](http://rmarkdown.rstudio.com/)
+ Individual work submitted; collaborative development encouraged
+ Entries due 1 week after associated lab or coding session
+ At least 4 entries due by February 20

## Details:

Technologies of Text is an experiential course and defined by hands-on labs throughout the semester. There will be a diversity of activities associated with labs in particular, from observations made at museums to physical documents printed on a letterpress. Some of these activities will be conducted individually and some in groups.

Your ToT fieldbook will constitute your central scholarly activity during the semester. I call this assignment a "fieldbook" rather than a "journal" to convey its hybridity: week by week, your entries will include a mix of description, analysis, code, and figures or images. This ongoing assignment will give you the chance to organize the diverse tasks of the class' experiential work, practice the skills introduced in the labs and coding sessions, bring your experiential work into conversation with class readings and personal research, and experiment with ideas that will be further developed in your [Unessay projects](#unessay).

### Organizing Your Fieldbook

Your fieldbook will be organized as a set of .md and/or .rmd files in a folder, which might also contain supplemental files such as images referenced in the documents. We'll work on setting this up in our first code session, so you don't need to understand precisely what this means right now. Periodically during the semester I will ask you to submit your fieldbooks, which will entail compressing your folder (into a zip file or similar) and emailing it to me. Alternatively, you might maintain one growing .rmd file with an underscore in between each entry, but this might begin to feel unwieldy.  

### Composition

Your fieldbook entries will vary quite a bit from week to week. However, there are a few elements I will expect in each entry:

1. Completion of any lab- or code-session-specific activities. Most of our experiential activities will include a specific set of outcomes. For example, I might ask you to reflect on a set of questions about your experiences or challenge you to adapt the day's code to solve some practice problems, or you might produce a specific material product such as a letterpress printed sheet. The first task of any fieldbook entry will be to demonstrate completion of these tasks. In the case of a coding session, you will likely integrate code snippets directly into the .RMD file; for labs you might instead reference external proof of your work (and possibly submit that external evidence separately).

2. Prose that both describes the work done and reflects analytically on that work. This prose need not be as formal as a research paper, but it should demonstrate careful thought and preparation. You should integrate our course readings into these reflections, often through direct quotation. Use your fieldbooks to explore ideas from the readings that you found particularly interesting, and especially ideas we did not have time to discuss in class. Use this writing to experiment with intellectual pairings you think might be generative to your larger thinking and help you prepare for the class' Unessay projects.

3. Evidence of your experiential work, particularly for code entries. One reason we will write in R Markdown is that it provides a way to integrate executable code with prose that comments and reflects on that code. You needn't include every snippet of code you attempted (though keep in mind "failed" code can be interesting as a subject of reflection). Instead, you should include the most enlightening or intellectual productive bits of code that help illustrate the larger ideas you are working through in your fieldbook.

4. A header that makes clear precisely which code or lab activity this entry responds to. As an example, you might include the following lines at the top of each file (or each entry if you're using a single file), modified to suit the specifics of each week:

    ```
    Name: Ryan Cordell
    Fieldbook Entry: 3
    Code: Not Reading (02/27)
    Lab: n/a
    Date of Completion: 03/03  
    ```

5. A filename that makes it very clear who you are and which fieldbook entry this is, such as ```cordell-fieldbook3.md```. 

### Flexibility

ToT is a challenging and full class. The semester will include 10 labs. To give you some flexibility, you must complete a fieldbook entry for 8/10 labs over the semester. You may complete more than 10 entries over the semester, so long as you continue to meet the guidelines for timing and submission outlined below. If you complete more than 8 entries, I will include only the strongest 8 in my gradebook (meaning you can make up for a weaker submission). 

### Pacing Your Field Work

Your fieldbook should be a developing record of your thinking about our class and its activities. Thus you should be working on it steadily, responding to the labs and code sessions in a timely manner, in part to keep your thinking fresh and in part to avoid falling too far behind as new labs and code sessions approach. 

Unless otherwise noted, a fieldbook entry is due within 1 week of the associated lab or code session. If a particular lab or code session extends through multiple classes, its fieldbook entry is due within 1 week of the final classroom session devoted to that activity. You may not wait until late in the semester to complete fieldbook entries for activities earlier in the semester, and I will collect your fieldbooks periodically to ensure you are working steadily. The coding exercises, in particular, will build on each other and you will find it difficult to complete fieldbooks for sessions 3-7

I regularly assign ongoing assignments in my classes and every semester I strongly urge students to start working early in order to complete the work. Each semester at least a few students ignore this urging, usually to their later dismay. Complications will almost certainly arise during the semester, and if you put off starting your fieldbook entries you will struggle to earn full credit on this assignment. In order to pressure you a bit toward responsibility: **you must complete at least 4 entries by President's Day, February 20**. I strongly recommend you complete more before this date, but I will not assess more than 5 entries completed after this date if at least 5 were not completed before. 

### Why Markdown?

I am asking you to write in Markdown for two primary reasons: 

1. The R Markdown implementation makes it very easy to weave together code and prose, which I see as a necessity for a class that wants to think humanistically about code. 

2. Markdown itself will help us think about text and remediation in a very direct way. Writing outside of a GUI (Graphical User Interface) like Word will challenge use to think about the structure of our texts and how that structure translates among different media. I don't want to pretend like the plain text of Markdown is somehow less mediated than a GUI; Markdown is an interface just like Word is an interface. But I suspect it is an unfamiliar interface for many of you, which will prompt you to think about how interface shapes our interactions with text. A single Markdown document can be instantly translated through a program like [Pandoc](http://pandoc.org/) into HTML, DOCX, PDF or a range of other formats, and we can use these transformations to think through the affordances and limitations of those formats for contemporary writing. 
Visualizing Student Problem Solving In Real Time
===============

## Team Members

1. Yvonne Chen evechen@uw.edu
2. Nell O'Rourke eorourke@cs.washington.edu

## Summary

In this work, we explore the design of visualizations for communicating student problem-solving progress to teachers in real-time. We partnered with Enlearn, a non-profit company that creates tablet-based adaptive problem-solving software for K-12 classrooms. To conduct this research, we first characterized the domain problem, then designed appropriate data abstractions, and finally developed two new visual encoding for student problem-solving data to support teacher tasks. Our final website simulates how our visualization designs would look displayed on tablet devices with real-time streaming data.

For more information about this project, check out the following resources:

[Visualization] (http://cse512-15s.github.io/fp-evechen-emor/code/visualization.html)
[Project Page] (http://cse512-15s.github.io/fp-evechen-emor/)
[Poster] (http://cse512-15s.github.io/fp-evechen-emor/final/poster.pdf)
[Paper] (http://cse512-15s.github.io/fp-evechen-emor/final/paper.pdf)



## Development Process

We began the development process by working closely with Enlearn to learn about the problem space. Enlearn had conducted a one-week study of two pre-existing visualizations shortly before we began our work, so we met with them to discuss their findings and develop a set of design guidelines for our new visualizations. After this problem characterization phase, we worked with Enlearn to understand their logging database structure. We pulled student problem-solving data from five 6th grade classes that took place last fall, and performed data transformations in python to create the nested JSON data format required to visualize problem-solving data by student and by concept.

At this stage, we worked together to design visual encodings of the problem-solving data to address the teacher tasks that we had identified, namely quickly assess student performance and deterring which students need individual assistance in the present moment. We came up with two initial designs and also decided to simulate streaming data using a timeline interface. We implemented initial prototypes of the visualizations and iterated on the designs, adding the tablet graphic and adding functionality to switch between the two visualizations.


## Breakdown of Work

We split up work on this project very evenly. Yvonne spent a little more time on the code and Nell spent a little more time on the paper, based on our availability as a result of other project conflicts. Since we were working a CSCW submission earlier in the quarter, the bulk of our project work began after Memorial Day. The dates listed below are approximate:

- Week of 5/11: We both met with Enlearn staff to discuss the results of their spring study and learn about the in-class visualization needs of teachers
- Week of 5/18: We worked together to prepare the Literature Review document and our slides for the in-class presentation
- Week of 5/25: We met to sketch initial visualization design ideas. Yvonne created initial mockups of our deigns in D3 while Nell pulled and transformed the Enlearn student data
- Week of 6/1: We implement the bulk of our visualization code. Yvonne spends more time on the code during the week while Nell writes an IRB for another project.  Both meet over the weekend to add final features to the visualization code and fix bugs. We work together to create the poster; Nell creates the initial poster design and Yvonne edits and polishes the content.
- Week of 6/8: We both present our poster and demo at the poster session. We divide work on the paper. Nell spends more time working on the paper while Yvonne spends more time working on the final project website and readme document. Both contribute final polish and editing.
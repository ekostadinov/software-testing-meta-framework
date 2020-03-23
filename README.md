# software-testing-meta-framework v5.0.0

A basic conceptional structure (as of ideas) that capture something real and do this in a way that is easy to remember and apply. As opposed to a reading list, or collection of links that one must go through and read - this testing framework aims to provide a set of guidelines or act as a thinking device, in combination with good practices and tools that are designed to help QA professionals test more efficiently. As a model, it makes rather gross simplification to clarify a more complex set of dynamics. And more precisely, turn a weighted bidirected graph into a tree, with the clear notion of the accuracy vs simplicity trade-off.

[Click here](https://ekostadinov.github.io/software-testing-meta-framework/) to view it live (GitHub Pages).

As a **meta**-framework, it essentially defines methods of context-aware and scalable abstractions for solving QA strategy problems involving multiple pieces. It describes how to create a framework that can manage and execute other frameworks, while supporting them in a common manner. Also, provides a way to manage the increasingly complex testing needs by providing a middle ground between the various tools and frameworks, and the test case management system.  This allows for easily extensibility for new (automation) tools that need to be incorporated into a larger QA strategy. As a meta-build tool, it is capable of building many different projects using a subset of existing tesing solutions.

## Main ideas used as base

1. **Human testers** — the good ones, anyway — do a lot. They explore, observe, experiment, eliminate sources of error, compare some theory with experimental findings, think around problems, and, finally, draw whatever conclusions stand the test of time based on their observations. And even then they have to be open to challenge; they can’t become a prisoner of your own ideas or their own results because quality is a shifting perception of value over time. Human testers must have faculties of observation, exploration, imagination, and contemplation. Those are combined with experimental skill, often meticulous record keeping, and a good dose of sheer determination. Human testers embody the full relationship between observation, hypothesis, deduction, induction, confirmatory experimentation, falsifying experimentation, and the act of implausifying ideas (such as the idea that everything is working or that value is being delivered). (-- Jeff Nyman)

2. Testing is an adaptive process of **learning and analysis** involving a great variety of experiments, observations and inferences about products ... We therefore choose to use a methodology that maximizes **freedom, self-regulation, and responsibility**. We can do this by ... scalable training methods (along with expert mentoring) to build skills and create a culture of excellence. The people who do the work then structure their processes as needed. ([Rapid Software Testing](http://www.satisfice.com/rst-appendices.pdf))

3. The need of better handling our ever growing structured & (mainly) unstructured data, pushed us to the realization - the we need some sort of a searchable database. After close consideration we decided to go with [Full-text search engine](http://www.ideaeng.com/database-full-text-search-0201) and migrate our knowledgebase to a VCS like Git. We aim to power our process with data-driven features, so our activities are compelled by data, rather than by intuition or by (solely) personal experience. The major improvement here is the ability to process the data (context) to ultimately help us make better decisions regarding testing. As [this article](http://www.mckinsey.com/business-functions/mckinsey-analytics/our-insights/the-role-of-expertise-and-judgment-in-a-data-driven-world) by McKinsey says, data and humans are complementary. As powerful as it may be, data only helps to understand a [part of the context](https://www.duperrin.com/english/2017/07/20/being-data-driven-means-being-contex-driven/) but does not provide an human story and narrative.

4. Extreme ownership ([book](https://www.amazon.com/Extreme-Ownership-U-S-Navy-SEALs-ebook/dp/B00VE4Y0Z2)) is teaching us 
-  that leading a team to success means taking responsibility for each and every one of its failures
- to successfully execute your mission, understand its importance
- to treat your allies as a support network, not as competition
- remain effective under pressure by setting clear priorities and acting upon them
- planning for success means comprehensively identifying and mitigating risks ahead of time
- instead of resenting interference by your superiors, make sure you’re giving them the information they need
> Don’t ask your leader what you should do, tell them what you are going to do.

5. Eat your own dog food! We test the HDTF in real-world usages on multiple tech stacks, products and work environments.

6. We only fit what makes most sense to us (from all the concepts, methodologies and practices), in our context. “Oh, this sounds a bit like some test principle, and we could work with it this way,” and if that helps somebody, that’s great. We don't have something to gain personally–for example, we are not consultants for this or that methodology, or we wrote a book about it and want to sell more books.

7. In theory, there is no difference between theory and practice. But, in practice, there is. (-- Jan L. A. van de Snepscheut) ...it is simplicity that is difficult to make. (-- Bertholdt Brecht)

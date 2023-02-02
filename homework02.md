# Member Names
* Janushi Shastri
* Rohit Taware
* Akhil Gandhi

## <ins>Silver Bullet<ins>
<hr>

#### Question 1: <ins>Define the term essential difficulties as it is used by Brooks. Provide background and context with your answer and at least one example of an essential difficulty.
#### Ans:
- Essential difficulties, as defined by Brooks, are difficulties in software technology that are inherent in the nature of software.
- According to Brooks, these inherent difficulties in software development are something that cannot be overcome and must be accepted as part of the process, or we can say that there is no silver bullet that can significantly improve these essential difficulties.

- _An example of an essential difficulty is the difficulty of predicting and controlling the complexity of software systems_.
- Brooks argues that software systems become more complex as they are developed, and this increase in complexity makes it difficult to accurately predict the time and resources required to complete any project.

<hr>

#### Question 2: <ins>Define the term accidental difficulties as it is used by Brooks. Provide background and context with your answer and at least one example of an accidental difficulty.
#### Ans:
- According to Brooks, accidental difficulties are those that today attend software's production, but they are not inherent.
- These difficulties are the consequences of the technology, design, and implementation choices made during the development process, and therefore, they are not core difficulties.
- Additionally, Brooks also argues that accidental difficulties are side effects of how humans have created and designed computer systems and, hence, can be eliminated as improvements are made.

- _For example, accidental difficulties can occur when software is dependent on rapidly changing technologies or tools, making it hard to keep up with the latest advancements_.
- Moreover, these difficulties also occur when there is poor communication between team members, leading to misunderstandings, conflicts, and rework.
- _Another example of accidental difficulty is when there is improper testing, which causes defects to be found too late in the development process_.

<hr>

#### Question 3: <ins>List and briefly describe the four essential difficulties of developing software systems that Brooks identifies. Provide additional examples of each type of the four essential difficulties.


##### Ans: According to Brooks, the four essential difficulties of developing software are:
-	<ins>Complexity</ins>: Computer programs or software systems are complex in terms of interaction or communication among teams, components to be used, number of possible paths through the code, invoking new functions, and understanding all possible states of the program.
     Example: Consider a system that combines numerous APIs to offer consumers customized recommendations. This system must manage data from numerous sources, process and analyze the data, and provide the user with the results. The system's behavior is challenging to predict at this level of complexity.

-	<ins>Conformity</ins>: The fact that software exists in an arbitrary environment filled with varying interfaces, standards, security protocols, etc. To work, the software must conform to these external factors. Example: In the case of software development, there are no fundamental guidelines to follow. If we assign the task of writing a single program to five different developers, each one will use a different logic to implement it. Some may use recursion, some may use for loops, and some may use while loops. Despite using different approaches, they can all achieve the same goal. As a result, it is highly challenging to achieve uniformity in the case of software development as there are no defined fundamental principles that everyone must abide by, and different technologies and logic might be used to solve the same problem.

-	<ins>Changeability</ins>: Software is continuously subject to change. These requirements for software systems to change and evolve, due to any new requirements, performance improvements or to fix any new bugs increase the difficulty of software deployment.
     Example: Consider a shopping website that needs to be updated as new stocks come in or the new season of sale or clothes begins. These need to update constantly to meet customer preferences and requirements can impact large changes in the entire system and make it difficult to predict the outcome of the new changes.

-	<ins>Invisibility</ins>: The fact that software is invisible and unvisualizable. There exists no easy way to make people visualize the whole software within any graphs or diagrams. Despite progress in restricting and simplifying the structures of software, they remain inherently unvisualizable and thus do not permit the mind to use some of its most powerful conceptual tools which leads to difficulty in development.
     Example: Consider a supervised algorithm to predict stock prices. The system may appear to be working correctly during testing, but unexpected behavior may become apparent when it is used in the real world. The invisibility makes it difficult to predict and prevent such behavior.

To create a successful software system, these obstacles must be carefully evaluated and managed as they can provide substantial challenges for software development teams.

<hr>

#### Question 4: <ins>Define what Brooks means by a silver bullet and reconstruct his argument as to why he believes there is no silver bullet for software engineering. In lecture, software engineering's relationship to computer science was described by analogy by discussing the differences between a chemist (chemistry) and a chemical engineer (chemical engineering). Define software engineering and its relationship to computer science; make use of the chemist vs. chemical engineer analogy when answering this question.

#### Ans:
According to Brooks, the field of software engineering has lots of hidden issues like blown-out budgets and missing schedules that are not easy to spot as they resemble werewolves that appear like a human but can transform without any warning causing havoc.
Thus, a silver bullet is needed to resolve the problem.
According to Brooks, we require more approaches to problems to go a step closer to an order-of-magnitude solution.
Software engineering, often known as a systematic engineering approach to software development, deals with the design, development, testing, deployment, and maintenance of software. The notion of "Abstraction" is the most important instrument available to be used.
Software engineering deals with the following issues.
- Issue of Design
- Issue of Regulation
- Issue of Communication
- Issue of Scale

The field of software engineering focuses on putting computer science's results to practical use. For example, we employ data structures and algorithms that we either directly build or consume using a library (but it's the concepts that count) when we design real-world algorithms. Having said that, software engineering and computer science depend on one another there is some overlap between the two fields.


We may use the distinction between chemical engineers and chemists to help us better comprehend. Chemists frequently concentrate on creating new materials and procedures, evaluating substances, determining their physical qualities, and verifying hypotheses. Computer science works with theory and diverse algorithms similarly. Chemical engineers concentrate on developing these novel concepts and discoveries into marketable products. The majority of work is involved in the planning, building, and running of factories and equipment, with a concentration on producing goods at a scale that is affordable to most people and for profit. The same thing is accomplished through software engineering, which uses theoretically created methods to solve practical issues while preserving the systems' general functionality.

<hr>

#### Question 5: <ins>In the lecture, we discussed the importance of the following concepts to software engineers: abstractions, conversations, specification, translation, and iteration. Define each of these concepts as they are related to software engineering and discuss their importance.

#### Ans:
- <ins>Abstraction</ins>: Whenever we are implementing any software at that time we should be able to hide the degree of complexity of the code and the things that are happening in the background. Also, software developers will try to break down the hard problems into smaller problems and then try to tackle every smaller problem, find the solution for each problem separately, and then use solutions of one problem to solve the other problem. For example creating an abstraction of database connection, creating separate abstraction which will deal with getting data from the database.  We use the concept of abstraction, whenever we are implementing the software we will try to hide the things working in the background and the user or the layer above that layer doesn’t know what is happening in the background. It may be possible that we have multiple layers of abstraction for example we may have a user interface that only communicates to the backend and it is only concerned with getting the data and it doesn’t concern about how the backend is trying to get data from the database, what is the business logic it is implementing. The importance of this abstraction is that things can work in a modular way, one layer doesn’t depend upon the other layer for their work, and they are independent of each other.

- <ins>Conversations</ins>: Conversations are also one of the important parts of software engineering, There are various scenarios where we need to converse about various things for example, when we are implementing a problem at that time we need to review with the SME to solve a particular problem as he has that domain expertise. If we update the code, if the code is not self-explanatory, then we need to do conversations with the one who has written that code. Also, conversations are an important part of requirements gathering, there will be several meeting that happens with the clients to get the requirements, and we do discussions with the clients regarding the what are use cases what are the requirements. Conversations are an important part of software engineering as they reduce the time required for example if we directly discuss the code that someone wrote rather than spending time understanding them it will reduce the time of maintenance. If we are stuck somewhere while implementing code discussing with the SMEs of the component will help to do code fasters.

- <ins>Translations</ins>: One of the important works in software engineering is translation. Developers receive the requirements from the users/ clients, they specify what they wanted, now it is the job of the developers to translate the requirements into business logic, and write the code accordingly so that it reflects and completes users' requirements. Similarly, the translations may work from one level to another level of abstractions as well, one layer will your data in a specific format, now the other data needs to translate into the form that it can use that data, for instance, backend given the data in the form of JSON, but the front end needs the data in the form of XML, so we need to translate data accordingly. Also, translations come into the picture when we are designing the system, when we are designing the architecture of the system, the requirements should be properly translated in such a way that it satisfies the user requirement.

- <ins>Iteration</ins>: In software engineering, most of the things are done in form of iterations, they help us to understand the requirement's current status and based on those in the next iteration we will try to incorporate the new changes, make the changes according to drawbacks, missing things or new requirements from clients and based on that try to produce the product. Now in the next iteration, we will try to incorporate new things and new features. The main importance of iteration is that we can review our product, and based on the same we can improve and add new features, we can keep on doing iterations until we get our final products. Sometimes once you publish the product we still do various iterations to add some new missing features and also provide maintenance.

- <ins>Specifications</ins>: whenever we start building new products software engineers need to specify the requirements, they need to specify the test plans, specify the design they want, they need to create a new architecture. They need the clients to specify all of the requirements. So before building any product in software engineering we need the specifications. The most important use of specifications is that it helps the developers to know what clients want, how the code should behave, and how the product should behave. Sometimes some developers will specify the working of the code, they may specify it using comments so that when the new developer or other developer looks at the code he will understand what that code is trying to do.

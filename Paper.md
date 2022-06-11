# CSSE 3012 Exam
Pranav Dhoolia
46333694

___
### 1(a)
- IT Department - **Incremental model**
	- primary focus on long term projects
	- project goals and requirements are clear and labelled
	- Less risks and don't need delivery immediately

- Consulting companies - **Agile model**
	- Fixed and matured processes 
	- Easy to estimate costs
	- Project requirements are clear but still require some testing

- Research and Development - **Prototypical Model**
	- Experimental processes
	- Harder to estimate costs (unique requirements)
	- Focus more on testing the viability of a product rather than developing it

___

### 1(b)
Fagan inspections take a long time and, if performed on a large scale, might stall project development. 

extreme programming is an agile practice that relies on quality team members who are dedicated to the success of the project. This practice also ensures that code is continually assessed throughout the process. Fagan inspections try to do the same (analysis of the code), which makes them redundant.

Even so, fagan inspections prove to be inefficient on a large scale because organizations tend to fall back to their average and it may cause delays. 

___
### 1(c)

For a software to accurately achieve its requirements, developers need to not only understand the software component, but the wholistic business aspect of the software as well.

Business Model describes the rationale of how an organisation creates delivers, and captures value. If the business model is not clearly defined in the beginning, then consequent corrections in the business model can render a lot of usecases, prototypes and calculations made in the software process useless.

Having a business model enables better decisions, designs and suggestions because developers are a part of the process generating actual business value.

Also, Primary sources of requirements are
	- Stakeholders
	- Users
	- Environment

Business model canvas aims at finding out the primary sources of requirements that will be taken into account while calculating the requirements of the software.

___
### 1(d)


___
### 1(e)

**Defined**
• Process for both management and engineering activities is documented and standardised
• Projects tailor the standard process (develop their own process to account for unique characteristics of the project)

Why not managed?
Large scale scrum is a viable solution for large teams but not the industry standard for the same. It is at best an upgrade to the already existing scrum practices used for small teams. It doesn't have the following properties of the Managed CMMI level:
- Performance is predictable.
	- some processes involved in large scale scrum are unnecessarily complicated and can be done better in other methodologies
- Relationships between cost, schedule and quality are understood in numerical terms
	- Large Scale scrum relies a lot on the team ability to do task analysis and estimation skill rather than proper quantifiable methods

It doesn't have the following qualities required for the **managed** cmmi level
• Relationships between cost, schedule and quality are understood in numerical terms
• Performance is predictable

___
### 2(a)

**Problem**
• Even small programs have too many inputs to fully test them 
	• int diff (int A, int B) 
	• each variable has over 4 billion possible values (32-bit machine) 

**Solution**
• To tackle the above problem testers search a huge input space use fewest inputs to find the most problems 

**Benefits**
• Coverage criteria give structured, practical ways to search the input space 
	• search the input space thoroughly 
	• reduce overlap in the tests 
	• Coverage criteria gives testers a **stopping rule** … when testing is finished 
	• Coverage criteria can be well supported with powerful tools

___
### 2(b)
![[Paper 2022-06-10 18.10.05.excalidraw]]



___
### 2(c)
`x=2`

**branch coverage**
`b1, b4, b6, b5 b2`
total - 6, covered - 5, 83.33% coverage

**statement coverage**
`s1, s2, s3, s4, s5, s6, s7, s9, s8, s10`
total - 10, covered - 9, 90% coverage


___
### 3(a)

```
RE = Probability Of occurance * cost to project
Risk Reduction Leverage = (RE(before) - RE(efter))/cost of intervention

RE(before) = 10,000,000 * 0.02 = 200,000

RE(after)(choice 1) = 10,000,000 * 0.0005 = 5000
RRL(choice 1) = (200,000 - 5000)/100,000 = 1.95

RE(after)(choice 2) = 10,000,000 * 0.00001 = 100
RRL(choice 2) = (200,000 - 100)/500,000 = 0.3998

```

Hence, **Choice 1** is the obvious choice because it has a higher Risk Reduction Leverage, which means it is more economical to invest in this choice than choice  keeping in mind the Cost to Project in case of risk occurrence.

Choice 1 also has `RRL >= 1` which means that the **cost of intervention** is a worthy investment in the mitigation of risk and it is advisable to go with it.

___
### 3(b)

![[Paper 2022-06-10 19.03.04.excalidraw]]

**Reduction Strategy**
System assumes the responsibility of notifying the authorities instead of the care provider

**Additional Risks**
- Extra overhead costs for connecting to the Emergency services API
- Reputational damage if the emergency api doesn't work

![[Paper 2022-06-10 19.11.34.excalidraw]]


___
### 3(c)

**Lean**

*"The application will collect accelerometer sensor data from smartwatch in a set interval/sampling period. A sequence/stream of accelerometer sensor data will be used to predict fall or not fall as an output."*

The above paragraph implies that:
- The requirements are vague and based on many assumptions
	- The duration of development of features cannot be calculated accurately
- The idea has not been fully tested yet
	- The exact business model has not been elaborated yet
	- It requires constant user feedback
	- It requires an iterative approach so that features can be quickly delivered and tested from a business standpoint

This narrows down the methodologies to:
- incremental (or iterative)
- agile
- lean

- Agile uses fixed, uniform time boxes in each iteration of the process. For example, each sprint is exactly 2 weeks. 
	- However, for lean, each iteration can be for different lengths depending on the amount of work required.

- Agile is a framework outlining exact processes and roles required. 
	- However Lean is a set of principles which developers can implement at their discretion.

This software requires more flexibility and needs to include elements of uncertainty, hence **Lean** is the most appropriate methodology for developing this software

___
### 3(d)
- The intent of the idea is clear
	- The idea **isn't too exploratory**. The only changes will be done in the techniques used to implement the idea.
		- e.g. The challenge is not to decide **WHAT** the solution is going to be. It is to decide **HOW** to implement that solution in the best possible manner.
	- We need broad data for finding out the best techniques and improving the technology
		- Lots of user feedback is needed
		- We need to find out things which the user **can't always describe**
			- example: when they fall

**Observations** seem to be an appropriate requirement elicitation technique


___
### 3(e)
![[Pasted image 20220610185948.png]]

As **user** I want to be able to **report a fall** so that I can **get help**
As a **care provider** I want to be able to **be notified when a user falls** so that I can help the user


**ASSUMPTION**: The question wanted to imply "fall detection application" instead of "personal academic record application"

___
### 3(f)
![[Pasted image 20220610184120.png]]

___
### 3(g)
![[Pasted image 20220610184133.png]]

___
### 3(h)

- *Product > Reliability*
	- System should be reliable. It should have a **less than 2%** false positive and false negative rate when reporting a fall.

- *External > Legislative > Privacy*
	- The system shall not disclose any personal information about customers apart from their **name**, **identification number** and **accelerometer sensor data** to the operators of the system.


**ASSUMPTION**: The question wanted to imply "fall detection application" instead of "personal academic record application"


___


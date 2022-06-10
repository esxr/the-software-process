# CSSE 3012 Exam
___
### 1 (c)
![[Pasted image 20220610160620.png]]
- Developers & Stakeholders need a shared understanding of the project’s purpose
	- easier when they collaborate continuously 
- Focus on value to be delivered – not just the requirements 
- Enables better decisions, designs and suggestions 
	- developers are part of the value chain 
- not just serving it
- Business Model - describes the rationale of how an organisation creates, delivers, and captures value
- Primary sources of requirements
	- Stakeholders
	- Users
	- Environment
- Business model canvas aims at finding out the primary sources of requirements that will be taken into account while calculating the requirements of the software


___
### 1(e)
![[Pasted image 20220610170923.png]]
**Defined**
• Process for both management and engineering activities is documented and standardised
• Projects tailor the standard process (develop their own process to account for unique characteristics of the project)

Why not managed?
large scale scrum is a viable solution for large teams but not the industry standard for the same. It is at best an upgrade to the already existing scrum practices used for small teams

It doesn't have the following qualities required for the **managed** cmmi level
• Relationships between cost, schedule and quality are understood in numerical terms
• Performance is predictable


___
### 3(a)
![[Pasted image 20220610170935.png]]
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
### 3(c)
![[Pasted image 20220610170944.png]]
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
![[Pasted image 20220610170958.png]]
- The intent of the idea is clear
	- The idea **isn't too exploratory**. The only changes will be done in the techniques used to implement the idea.
		- for e.g. The challenge is not to decide **WHAT** the solution is going to be. It is to decide **HOW** to implement that solution in the best possible manner.
	- We need broad data for finding out the best techniques and improving the technology
		- Lots of user feedback is needed
		- We need to find out things which the user **can't always describe**
			- example: when they fall

**Observations** seem to be an appropriate requirement elicitation technique



___
### 3(e)


___
### 3(h)



___


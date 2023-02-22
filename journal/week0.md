
# Week 0 — Billing and Architecture

Note to Self

	• Ephemeral-first micro-blogging platform
	• Fractional CTO
	• Partly developed app - keep or build?
	• How to monetize the platform
	• Frontend = JavaScript using React
	• Backend application = Python Using Flask
	• API only
	• Be careful of budget
	• User content(upload?)

		• User - College students, Younger students, professionals
		• User validation?
		• Age limit
		
	• AWS
		• What services? Containers?
		• Set up budget monitoring
	• User engagement
	• Technical report due for investors!
		• Architecture
		• Budget


Why User Personas?

Personas
	• Tony = continuity and context
	• Web dev group = current state
	• Investors = cost and timing 
	• CTO = technical requirements and future state
  
 
 Lesson learned
	• Not all context is relevant
	• No true "greenfield"
	• Manage time and effort
	• Tradeoffs for all projects
	• Learn, irritate, and show back
  
 
 Architecture

What is good architecture?
	Things the project *Must* achieve, it can be technical or business oriented
	Requirement must be:
	   * Verifiable
	   * monitorable
	   * traceable
	   * **feasible**
	Examples:
	   * Meets ISO standards
	   * 99.9% uptime
	   * user can do specific task
	

Addresses the Risks, Assumptions & Constraints

 Risks can prevent the project from being successful (must be mitigated)
     * SPoFs
     * user commitment 
     * late Delivery
     
  Assumptions are factors held as true for the planning & implementation phases
      * Sufficient network bandwidth
      * Stakeholders will be available to make decisions
       * Budget is approved

Constraints are policy or technical limitations for the project
       * Time
       * Budgets
       * Vendor selection

From gathering the RRACs, you then create your designs:

Conceptual Design
	• Created by business stakeholders and architects
	• Organizes and defines concepts and rules
	• "Napkin Design"
	
Logical Design (blueprint)
	• Defines how the system should be implemented
	• Environment without actual names or sizes
	• Examples: undeployed CFT
	
Physical Design
	• Representation of the actual thing that was built
	• IP Addresses, EC2 Instances

It's important to Develop a Common Dictionary
	• Ask "dump questions"
	• Play be the packet
	• Document everything*

What is TOGAF?

"TOGAF is an architecture framework that provides the methods and tools for assisting in the acceptance, production, use, and maintenance of an enterprise architecture. It is bases on an iterative process model supported by best practices and reusable set of existing architecture assets".
	• The most popular framework for EA
	• Common dictionary of words to convey desired outcomes
	• Meta-model for the creations of the underlying projects
	• Maps closely to the Well-Architected Tool

Assignmens
* Create a conceptual design of the crudder app using lucid application

 link to my submitted work for the conceptual design:  https://lucid.app/lucidchart/invitations/accept/inv_98bf7850-6174-408f-994f-7c549c9c5354
 
 link to the logical design: https://lucid.app/lucidchart/invitations/accept/inv_cdcfb3e7-6d31-4ae1-b362-b5f303a1e699

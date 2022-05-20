#Framework/Vue 
#Framework/Vue/Components
#Programming/BestPractices


# Components in vue

## Content
1. Description
2. The use of READMEs
3. Cleanup. 
4. Architecture
5. 


#### #1. Description
- Below are things one should think about, in regard of vue components.
- Idea behind a component are re-usability.
	- To use an component several places in a project.
	- Or in multiple projects.
- Should be as clean as possible, while easily adjustable to the need of the situation.


#### #2. The use of READMEs
- This is where you give all needed information in regard of the component.
- Usage for this, are to reduce the implementation time it takes to use it.
- Aswell as giving useful information.

- Content:
	- Description: of what the component does, and its usecases.
	- Features to come: If the component are expected to be updated in any shape or form.
	- Installation: If this component require any dependencies or custom installment.
	- Notes: Any information that are relevant toward this component.
		- Can be: change id to the correct tenant_id.    adjust the query call and such.
	- Examples: If there are different usecases, or such. 
		- Give some examples for it, like:
			- Versions of axios methods used.
			- Blocks of code.


#### #3. Cleanup.
- Clean the component code.
	- Removing console.logs that are not needed.
	- Ghost code that are commented out.
	- Functions and similar that are not in use.


#### #4. Architecture
- Abit in regard of the architecture of components in a project.
- There are multiple ways to do it, and while there is no best or worst ways, having an idea about the differances can be beneficial.
- Ways:
	1. Sorted by Type of components.
		- Description:
			- Dialogs goes into the dialog folder.
			- Table goes into the table folder.
		- Pros:
			- Easy to find the kind of component one wish to use.
		- Cons:
			- In a larger project, this can become hard to keep track of.
	2. Sorted by individual component.
		- Description:
			- Course component goes into its folder.
				- With its main component, and all sub component that are linked to that one.
			- Pros:
				- Easy to find the component and its "childs"
			- Cons:
				- Need some more thought about structure, and names of the component.
					- Which one should think about anyway.
		3. By Page.
			- Description:
				- All home page components, lies within home page folder.
			- Pros: 
				- Good in smaller projects.
			- Cons:
				- Can become hard to find component, if a page contain ALOT of different components.
		4. Alittlebit of everything.
		    - Description:
			    - While sticking to one way is good, being flexible is better.
			    - Example:
					- Home page component folder, with sub folders based on point 1 or 2.


#### 5. 

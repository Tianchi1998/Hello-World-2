# Part 1
#### the names & IDs of BOTH MEMBERS of the group.   
- Name : JiaQi Deng          Massey ID :17140035
- Name : TianChi Zhang       Massey ID :17139797


***

# Part 2
#### clear instructions on how to run your program, and if there are any other folders, what they contain.
- The Part 2 directory contains all of java codes and reports.
- If people want to run our program, firstly, run the start.java and input "https://localhost:8443" that appears on the console to web browser
  and run , then people can see the result of our program, add button can add information(name,description,due date, project title)to Task List,
  clear button can remove completed tasks, people can get the result of completed task, all task as well as active tasks(uncompleted tasks) by
  clicking the completed task, all tasks and active tasks repectively. The number of incompleted tasks can count the number of uncompleted tasks,
  XML-based Serialization can convert the contents in the Task List into XML file. Finally, import the todo txt file button can import the todo 
  txt file and add it into Task List.
- There is a report folder that contains the pmd report
 
***
  
# Part 3
#### for each student, a couple of git commit IDs that show the work of each individual member of the group.
- For Tianchi Zhang:
8ad40d2
7d21daf
f169938
e221b57
025c0de
f7e9e0f
dc35611
e037ecd
f185a63
ea62aee
935bdc1
b14d713
1576f0d
d2bc4c2
85a6aee
dae0571
8b2f9a9
2ee8fae
533600c
164f511

- For Jiaqi Deng:
73496d1
023b801
a0223fa
1623ecc
8420504

***

# Part 4
#### Metrics analysis report from Eclipse Metrics Plugin and code quality analysis report from PMD.
## Here is the result of pmd report:  
src/main/java/nz/ac/massey/cs/ClearForm.java:12:	Header comments are required</br>
src/main/java/nz/ac/massey/cs/ClearForm.java:18:	Avoid excessively long variable names like SERIALIZED_FILE_NAME</br>
src/main/java/nz/ac/massey/cs/ClearForm.java:18:	Field comments are required</br>
src/main/java/nz/ac/massey/cs/ClearForm.java:20:	Avoid variables with short names like id</br>
src/main/java/nz/ac/massey/cs/ClearForm.java:20:	Parameter 'id' is not assigned and could be declared final</br>
src/main/java/nz/ac/massey/cs/ClearForm.java:20:	Public method and constructor comments are required</br>
src/main/java/nz/ac/massey/cs/ClearForm.java:25:	Found 'UR'-anomaly for variable 'task' (lines '25'-'36').</br>
src/main/java/nz/ac/massey/cs/ClearForm.java:25:	Protected method constructor comments are required</br>
src/main/java/nz/ac/massey/cs/ClearForm.java:25:	The method 'onSubmit()' has a NCSS line count of 17.</br>
src/main/java/nz/ac/massey/cs/ClearForm.java:28:	Local variable 'app' could be declared final</br>
src/main/java/nz/ac/massey/cs/ClearForm.java:29:	Local variable 'collection' could be declared final</br>
src/main/java/nz/ac/massey/cs/ClearForm.java:29:	Potential violation of Law of Demeter (object not created locally)</br>
src/main/java/nz/ac/massey/cs/ClearForm.java:30:	Local variable 'tasksList' could be declared final</br>
src/main/java/nz/ac/massey/cs/ClearForm.java:30:	Potential violation of Law of Demeter (object not created locally)</br>
src/main/java/nz/ac/massey/cs/ClearForm.java:33:	Local variable 'completedList' could be declared final</br>
src/main/java/nz/ac/massey/cs/ClearForm.java:34:	Local variable 'task' could be declared final</br>
src/main/java/nz/ac/massey/cs/ClearForm.java:42:	Comment is too large: Line too long</br>
src/main/java/nz/ac/massey/cs/ClearForm.java:43:	Found 'DD'-anomaly for variable 'encoder' (lines '43'-'46').</br>
src/main/java/nz/ac/massey/cs/ClearForm.java:46:	Avoid instantiating FileInputStream, FileOutputStream, FileReader, or FileWriter</br>
src/main/java/nz/ac/massey/cs/ClearForm.java:50:	System.out.println is used</br>
src/main/java/nz/ac/massey/cs/ClearForm.java:56:	Potential violation of Law of Demeter (object not created locally)</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:3:	Avoid unused imports such as 'org.apache.wicket.MarkupContainer'</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:6:	Avoid unused imports such as 'org.apache.wicket.model.IModel'</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:11:	Header comments are required</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:13:	Field comments are required</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:13:	Found non-transient, non-static member. Please mark as transient or provide accessors.</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:13:	Private field 'nameField' could be made final; it is only initialized in the declaration or constructor.</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:14:	Field comments are required</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:14:	Found non-transient, non-static member. Please mark as transient or provide accessors.</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:14:	Private field 'descriptionField' could be made final; it is only initialized in the declaration or constructor.</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:15:	Field comments are required</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:15:	Found non-transient, non-static member. Please mark as transient or provide accessors.</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:15:	Private field 'dueDateField' could be made final; it is only initialized in the declaration or constructor.</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:16:	Field comments are required</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:16:	Found non-transient, non-static member. Please mark as transient or provide accessors.</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:16:	Private field 'projectTitleField' could be made final; it is only initialized in the declaration or constructor.</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:19:	Avoid variables with short names like id</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:19:	Parameter 'id' is not assigned and could be declared final</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:19:	Public method and constructor comments are required</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:32:	Protected method constructor comments are required</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:32:	The method 'onSubmit()' has a NCSS line count of 17.</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:34:	Local variable 'name' could be declared final</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:35:	Local variable 'description' could be declared final</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:36:	Local variable 'dueDate' could be declared final</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:37:	Local variable 'projectTitle' could be declared final</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:48:	Local variable 'app' could be declared final</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:49:	Local variable 'collection' could be declared final</br>
src/main/java/nz/ac/massey/cs/EntryForm.java:49:	Potential violation of Law of Demeter (object not created locally)</br>
src/main/java/nz/ac/massey/cs/Task.java:8:	Avoid short class names like Task</br>
src/main/java/nz/ac/massey/cs/Task.java:8:	Classes implementing Serializable should set a serialVersionUID</br>
src/main/java/nz/ac/massey/cs/Task.java:8:	Header comments are required</br>
src/main/java/nz/ac/massey/cs/Task.java:8:	The class 'Task' is suspected to be a Data Class (WOC=10.526%, NOPA=0, NOAM=15, WMC=19)</br>
src/main/java/nz/ac/massey/cs/Task.java:10:	Field comments are required</br>
src/main/java/nz/ac/massey/cs/Task.java:11:	Field comments are required</br>
src/main/java/nz/ac/massey/cs/Task.java:12:	Field comments are required</br>
src/main/java/nz/ac/massey/cs/Task.java:13:	Field comments are required</br>
src/main/java/nz/ac/massey/cs/Task.java:14:	Field comments are required</br>
src/main/java/nz/ac/massey/cs/Task.java:16:	Avoid variables with short names like id</br>
src/main/java/nz/ac/massey/cs/Task.java:16:	Field comments are required</br>
src/main/java/nz/ac/massey/cs/Task.java:17:	Field comments are required</br>
src/main/java/nz/ac/massey/cs/Task.java:19:	Document empty constructor</br>
src/main/java/nz/ac/massey/cs/Task.java:19:	Public method and constructor comments are required</br>
src/main/java/nz/ac/massey/cs/Task.java:24:	Parameter 'description' is not assigned and could be declared final</br>
src/main/java/nz/ac/massey/cs/Task.java:24:	Parameter 'dueDate' is not assigned and could be declared final</br>
src/main/java/nz/ac/massey/cs/Task.java:24:	Parameter 'name' is not assigned and could be declared final</br>
src/main/java/nz/ac/massey/cs/Task.java:24:	Parameter 'projectTitle' is not assigned and could be declared final</br>
src/main/java/nz/ac/massey/cs/Task.java:24:	Public method and constructor comments are required</br>
src/main/java/nz/ac/massey/cs/Task.java:42:	Parameter 'dueDate' is not assigned and could be declared final</br>
src/main/java/nz/ac/massey/cs/Task.java:56:	Parameter 'projectTitle' is not assigned and could be declared final</br>
src/main/java/nz/ac/massey/cs/Task.java:70:	Parameter 'description' is not assigned and could be declared final</br>
src/main/java/nz/ac/massey/cs/Task.java:84:	Parameter 'completed' is not assigned and could be declared final</br>
src/main/java/nz/ac/massey/cs/Task.java:98:	Parameter 'name' is not assigned and could be declared final</br>
src/main/java/nz/ac/massey/cs/Task.java:112:	Avoid variables with short names like id</br>
src/main/java/nz/ac/massey/cs/Task.java:112:	Parameter 'id' is not assigned and could be declared final</br>
src/main/java/nz/ac/massey/cs/Task.java:126:	Parameter 'date' is not assigned and could be declared final</br>
src/main/java/nz/ac/massey/cs/Task.java:130:	Public method and constructor comments are required</br>
src/main/java/nz/ac/massey/cs/Task.java:134:	Parameter 'complete' is not assigned and could be declared final</br>
src/main/java/nz/ac/massey/cs/Task.java:134:	Public method and constructor comments are required</br>
src/main/java/nz/ac/massey/cs/TaskList.java:9:	Classes implementing Serializable should set a serialVersionUID</br>
src/main/java/nz/ac/massey/cs/TaskList.java:9:	Header comments are required</br>
src/main/java/nz/ac/massey/cs/TaskList.java:10:	Field comments are required</br>
src/main/java/nz/ac/massey/cs/TaskList.java:10:	Found non-transient, non-static member. Please mark as transient or provide accessors.</br>
src/main/java/nz/ac/massey/cs/TaskList.java:10:	Private field 'collection' could be made final; it is only initialized in the declaration or constructor.</br>
src/main/java/nz/ac/massey/cs/TaskList.java:12:	Public method and constructor comments are required</br>
src/main/java/nz/ac/massey/cs/TaskList.java:16:	Public method and constructor comments are required</br>
src/main/java/nz/ac/massey/cs/TaskList.java:20:	Parameter 'task' is not assigned and could be declared final</br>
src/main/java/nz/ac/massey/cs/TaskList.java:20:	Public method and constructor comments are required</br>
src/main/java/nz/ac/massey/cs/TaskList.java:24:	Parameter 'task' is not assigned and could be declared final</br>
src/main/java/nz/ac/massey/cs/TaskList.java:24:	Public method and constructor comments are required</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:3:	Avoid unused imports such as 'org.apache.wicket.Component'</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:5:	Avoid unused imports such as 'org.apache.wicket.ajax.markup.html.AjaxFallbackLink'</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:6:	Avoid unused imports such as 'org.apache.wicket.ajax.markup.html.AjaxLink'</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:16:	Avoid unused imports such as 'org.apache.wicket.request.mapper.parameter.PageParameters'</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:19:	Avoid unused imports such as 'org.apache.wicket.request.resource.ResourceReference'</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:30:	Header comments are required</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:30:	The class 'TasksPage' has a Modified Cyclomatic Complexity of 25 (Highest = 24).</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:30:	The class 'TasksPage' has a Standard Cyclomatic Complexity of 25 (Highest = 24).</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:33:	Avoid excessively long variable names like SERIALIZED_FILE_NAME</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:33:	Field comments are required</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	Avoid really long methods.</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	Found 'UR'-anomaly for variable 't' (lines '35'-'207').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	Found 'UR'-anomaly for variable 't' (lines '35'-'207').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	Found 'UR'-anomaly for variable 't' (lines '35'-'207').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	Found 'UR'-anomaly for variable 't' (lines '35'-'207').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	Found 'UR'-anomaly for variable 't' (lines '35'-'207').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	Found 'UR'-anomaly for variable 't' (lines '35'-'207').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	Found 'UR'-anomaly for variable 't' (lines '35'-'207').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	Found 'UR'-anomaly for variable 'task' (lines '35'-'46').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	Found 'UR'-anomaly for variable 'task' (lines '35'-'46').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	Found 'UR'-anomaly for variable 'task' (lines '35'-'46').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	Found 'UR'-anomaly for variable 'task' (lines '35'-'46').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	Found 'UR'-anomaly for variable 'task' (lines '35'-'46').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	Found 'UR'-anomaly for variable 'task' (lines '35'-'46').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	Found 'UR'-anomaly for variable 'task' (lines '35'-'46').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	Found 'UR'-anomaly for variable 'task' (lines '35'-'46').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	It is a good practice to call super() in a constructor</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	Public method and constructor comments are required</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	The constructor 'TasksPage' has a Modified Cyclomatic Complexity of 24.</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	The constructor 'TasksPage' has a Standard Cyclomatic Complexity of 24.</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	The constructor 'TasksPage()' has a NCSS line count of 117.</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	The constructor 'TasksPage()' has an NPath complexity of 2592</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:35:	The constructor with 0 parameters has an NCSS line count of 104</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:38:	Local variable 'form' could be declared final</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:40:	Protected method constructor comments are required</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:42:	Potential violation of Law of Demeter (object not created locally)</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:43:	Potential violation of Law of Demeter (object not created locally)</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:44:	Avoid unused local variables such as 'completedList'.</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:44:	Found 'DD'-anomaly for variable 'completedList' (lines '44'-'94').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:44:	Found 'DD'-anomaly for variable 'completedList' (lines '44'-'94').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:44:	Found 'DD'-anomaly for variable 'completedList' (lines '44'-'94').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:44:	Found 'DD'-anomaly for variable 'completedList' (lines '44'-'94').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:44:	Found 'DD'-anomaly for variable 'completedList' (lines '44'-'94').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:44:	Found 'DD'-anomaly for variable 'completedList' (lines '44'-'94').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:44:	Found 'DD'-anomaly for variable 'completedList' (lines '44'-'94').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:44:	Found 'DD'-anomaly for variable 'completedList' (lines '44'-'94').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:46:	Avoid unnecessary comparisons in boolean expressions</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:47:	There is log block not surrounded by if</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:55:	Local variable 'button1' could be declared final</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:56:	Public method and constructor comments are required</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:58:	Potential violation of Law of Demeter (object not created locally)</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:59:	Potential violation of Law of Demeter (object not created locally)</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:60:	Avoid unused local variables such as 'completedList'.</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:62:	There is log block not surrounded by if</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:71:	Local variable 'button2' could be declared final</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:72:	Public method and constructor comments are required</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:74:	Potential violation of Law of Demeter (object not created locally)</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:75:	Potential violation of Law of Demeter (object not created locally)</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:76:	Avoid unused local variables such as 'completedList'.</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:78:	Avoid unnecessary comparisons in boolean expressions</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:79:	There is log block not surrounded by if</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:89:	Local variable 'button3' could be declared final</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:90:	Public method and constructor comments are required</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:92:	Potential violation of Law of Demeter (object not created locally)</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:93:	Potential violation of Law of Demeter (object not created locally)</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:94:	Avoid unused local variables such as 'completedList'.</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:94:	Found 'DD'-anomaly for variable 'completedList' (lines '94'-'113').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:94:	Found 'DD'-anomaly for variable 'completedList' (lines '94'-'113').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:94:	Found 'DD'-anomaly for variable 'completedList' (lines '94'-'113').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:94:	Found 'DD'-anomaly for variable 'completedList' (lines '94'-'113').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:94:	Found 'DD'-anomaly for variable 'completedList' (lines '94'-'113').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:94:	Found 'DD'-anomaly for variable 'completedList' (lines '94'-'113').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:94:	Found 'DD'-anomaly for variable 'completedList' (lines '94'-'113').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:95:	Found 'DD'-anomaly for variable 'count' (lines '95'-'98').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:95:	Found 'DD'-anomaly for variable 'count' (lines '95'-'98').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:95:	Found 'DD'-anomaly for variable 'count' (lines '95'-'98').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:95:	Found 'DD'-anomaly for variable 'count' (lines '95'-'98').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:95:	Found 'DD'-anomaly for variable 'count' (lines '95'-'98').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:95:	Found 'DD'-anomaly for variable 'count' (lines '95'-'98').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:95:	Found 'DD'-anomaly for variable 'count' (lines '95'-'98').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:97:	Avoid unnecessary comparisons in boolean expressions</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:101:	There is log block not surrounded by if</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:108:	Local variable 'button4' could be declared final</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:109:	Public method and constructor comments are required</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:111:	Potential violation of Law of Demeter (object not created locally)</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:112:	Potential violation of Law of Demeter (object not created locally)</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:119:	Found 'DD'-anomaly for variable 'encoder' (lines '119'-'121').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:119:	Found 'DD'-anomaly for variable 'encoder' (lines '119'-'121').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:119:	Found 'DD'-anomaly for variable 'encoder' (lines '119'-'121').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:119:	Found 'DD'-anomaly for variable 'encoder' (lines '119'-'121').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:119:	Found 'DD'-anomaly for variable 'encoder' (lines '119'-'121').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:119:	Found 'DD'-anomaly for variable 'encoder' (lines '119'-'121').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:119:	Found 'DD'-anomaly for variable 'encoder' (lines '119'-'121').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:121:	Avoid autogenerated methods to access private fields and methods of inner / outer classes</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:121:	Avoid instantiating FileInputStream, FileOutputStream, FileReader, or FileWriter</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:136:	Local variable 'form3' could be declared final</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:138:	Protected method constructor comments are required</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:141:	Found 'DD'-anomaly for variable 'collection' (lines '141'-'181').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:141:	Found 'DD'-anomaly for variable 'collection' (lines '141'-'181').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:141:	Found 'DD'-anomaly for variable 'collection' (lines '141'-'181').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:141:	Found 'DD'-anomaly for variable 'collection' (lines '141'-'181').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:141:	Found 'DD'-anomaly for variable 'collection' (lines '141'-'181').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:141:	Found 'DD'-anomaly for variable 'collection' (lines '141'-'181').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:141:	Found 'DD'-anomaly for variable 'collection' (lines '141'-'181').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:141:	Potential violation of Law of Demeter (object not created locally)</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:144:	Avoid variables with short names like in</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:144:	Potential violation of Law of Demeter (object not created locally)</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:145:	Avoid variables with short names like b</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:145:	Found 'DD'-anomaly for variable 'b' (lines '145'-'149').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:145:	Found 'DD'-anomaly for variable 'b' (lines '145'-'149').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:145:	Found 'DD'-anomaly for variable 'b' (lines '145'-'149').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:145:	Found 'DD'-anomaly for variable 'b' (lines '145'-'149').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:145:	Found 'DD'-anomaly for variable 'b' (lines '145'-'149').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:145:	Found 'DD'-anomaly for variable 'b' (lines '145'-'149').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:145:	Found 'DD'-anomaly for variable 'b' (lines '145'-'149').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:145:	Potential violation of Law of Demeter (object not created locally)</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:146:	Found 'DU'-anomaly for variable 'len' (lines '146'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:146:	Found 'DU'-anomaly for variable 'len' (lines '146'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:146:	Found 'DU'-anomaly for variable 'len' (lines '146'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:146:	Found 'DU'-anomaly for variable 'len' (lines '146'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:146:	Found 'DU'-anomaly for variable 'len' (lines '146'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:146:	Found 'DU'-anomaly for variable 'len' (lines '146'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:146:	Found 'DU'-anomaly for variable 'len' (lines '146'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:147:	Found 'DD'-anomaly for variable 'temp' (lines '147'-'148').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:147:	Found 'DD'-anomaly for variable 'temp' (lines '147'-'148').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:147:	Found 'DD'-anomaly for variable 'temp' (lines '147'-'148').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:147:	Found 'DD'-anomaly for variable 'temp' (lines '147'-'148').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:147:	Found 'DD'-anomaly for variable 'temp' (lines '147'-'148').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:147:	Found 'DD'-anomaly for variable 'temp' (lines '147'-'148').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:147:	Found 'DD'-anomaly for variable 'temp' (lines '147'-'148').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:148:	Avoid assignments in operands</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:148:	Found 'DU'-anomaly for variable 'temp' (lines '148'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:148:	Found 'DU'-anomaly for variable 'temp' (lines '148'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:148:	Found 'DU'-anomaly for variable 'temp' (lines '148'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:148:	Found 'DU'-anomaly for variable 'temp' (lines '148'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:148:	Found 'DU'-anomaly for variable 'temp' (lines '148'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:148:	Found 'DU'-anomaly for variable 'temp' (lines '148'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:148:	Found 'DU'-anomaly for variable 'temp' (lines '148'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:148:	Potential violation of Law of Demeter (object not created locally)</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:149:	Found 'DD'-anomaly for variable 'b' (lines '149'-'149').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:149:	Found 'DD'-anomaly for variable 'b' (lines '149'-'149').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:149:	Found 'DD'-anomaly for variable 'b' (lines '149'-'149').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:149:	Found 'DD'-anomaly for variable 'b' (lines '149'-'149').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:149:	Found 'DD'-anomaly for variable 'b' (lines '149'-'149').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:149:	Found 'DD'-anomaly for variable 'b' (lines '149'-'149').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:149:	Found 'DD'-anomaly for variable 'b' (lines '149'-'149').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:150:	Found 'DU'-anomaly for variable 'len' (lines '150'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:150:	Found 'DU'-anomaly for variable 'len' (lines '150'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:150:	Found 'DU'-anomaly for variable 'len' (lines '150'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:150:	Found 'DU'-anomaly for variable 'len' (lines '150'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:150:	Found 'DU'-anomaly for variable 'len' (lines '150'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:150:	Found 'DU'-anomaly for variable 'len' (lines '150'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:150:	Found 'DU'-anomaly for variable 'len' (lines '150'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:152:	Potential violation of Law of Demeter (object not created locally)</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:153:	Potential violation of Law of Demeter (object not created locally)</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:155:	Avoid catching generic exceptions such as NullPointerException, RuntimeException, Exception in try-catch block</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:156:	Avoid printStackTrace(); use a logger call instead.</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:172:	Local variable 'listForm' could be declared final</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:176:	Local variable 'now' could be declared final</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:177:	Local variable 'dateTimeLabel' could be declared final</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:180:	Local variable 'app' could be declared final</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:181:	Local variable 'collection' could be declared final</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:182:	Local variable 'tasks' could be declared final</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:184:	Local variable 'taskListView' could be declared final</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:185:	Found 'DU'-anomaly for variable 'serialVersionUID' (lines '185'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:185:	Found 'DU'-anomaly for variable 'serialVersionUID' (lines '185'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:185:	Found 'DU'-anomaly for variable 'serialVersionUID' (lines '185'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:185:	Found 'DU'-anomaly for variable 'serialVersionUID' (lines '185'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:185:	Found 'DU'-anomaly for variable 'serialVersionUID' (lines '185'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:185:	Found 'DU'-anomaly for variable 'serialVersionUID' (lines '185'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:185:	Found 'DU'-anomaly for variable 'serialVersionUID' (lines '185'-'214').</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:188:	Parameter 'item' is not assigned and could be declared final</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:197:	Document empty method body</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:197:	Parameter 'ajaxRequestTarget' is not assigned and could be declared final</br>
src/main/java/nz/ac/massey/cs/TasksPage.java:206:	Local variable 't' could be declared final</br>
src/main/java/nz/ac/massey/cs/WicketApplication.java:11:	Each class should declare at least one constructor</br>
src/main/java/nz/ac/massey/cs/WicketApplication.java:13:	Field comments are required</br>
src/main/java/nz/ac/massey/cs/WicketApplication.java:13:	Found non-transient, non-static member. Please mark as transient or provide accessors.</br>
src/main/java/nz/ac/massey/cs/WicketApplication.java:35:	Public method and constructor comments are required</br>
src/test/java/nz/ac/massey/cs/Start.java:19:	Comment is too large: Line too long</br>
src/test/java/nz/ac/massey/cs/Start.java:23:	All methods are static.  Consider using a utility class instead. Alternatively, you could add a private constructor or make the class abstract to silence this warning.</br>
src/test/java/nz/ac/massey/cs/Start.java:29:	Parameter 'args' is not assigned and could be declared final</br>
src/test/java/nz/ac/massey/cs/Start.java:29:	The method 'main(String)' has a NCSS line count of 40.</br>
src/test/java/nz/ac/massey/cs/Start.java:33:	Local variable 'server' could be declared final</br>
src/test/java/nz/ac/massey/cs/Start.java:35:	Local variable 'http_config' could be declared final</br>
src/test/java/nz/ac/massey/cs/Start.java:35:	Only variables that are final should contain underscores (except for underscores in standard prefix/suffix), 'http_config' is not final.</br>
src/test/java/nz/ac/massey/cs/Start.java:40:	Local variable 'http' could be declared final</br>
src/test/java/nz/ac/massey/cs/Start.java:46:	Local variable 'keystore' could be declared final</br>
src/test/java/nz/ac/massey/cs/Start.java:47:	Potential violation of Law of Demeter (object not created locally)</br>
src/test/java/nz/ac/massey/cs/Start.java:56:	Local variable 'sslContextFactory' could be declared final</br>
src/test/java/nz/ac/massey/cs/Start.java:61:	Local variable 'https_config' could be declared final</br>
src/test/java/nz/ac/massey/cs/Start.java:61:	Only variables that are final should contain underscores (except for underscores in standard prefix/suffix), 'https_config' is not final.</br>
src/test/java/nz/ac/massey/cs/Start.java:64:	Local variable 'https' could be declared final</br>
src/test/java/nz/ac/massey/cs/Start.java:70:	System.out.println is used</br>
src/test/java/nz/ac/massey/cs/Start.java:71:	System.out.println is used</br>
src/test/java/nz/ac/massey/cs/Start.java:73:	System.out.println is used</br>
src/test/java/nz/ac/massey/cs/Start.java:76:	Avoid variables with short names like bb</br>
src/test/java/nz/ac/massey/cs/Start.java:76:	Local variable 'bb' could be declared final</br>
src/test/java/nz/ac/massey/cs/Start.java:81:	Comment is too large: Line too long</br>
src/test/java/nz/ac/massey/cs/Start.java:83:	Comment is too large: Line too long</br>
src/test/java/nz/ac/massey/cs/Start.java:92:	Local variable 'mBeanServer' could be declared final</br>
src/test/java/nz/ac/massey/cs/Start.java:93:	Local variable 'mBeanContainer' could be declared final</br>
src/test/java/nz/ac/massey/cs/Start.java:102:	Avoid catching generic exceptions such as NullPointerException, RuntimeException, Exception in try-catch block</br>
src/test/java/nz/ac/massey/cs/Start.java:104:	Avoid printStackTrace(); use a logger call instead.</br>
src/test/java/nz/ac/massey/cs/Start.java:105:	System.exit() should not be used in J2EE/JEE apps</br>
src/test/java/nz/ac/massey/cs/TestHomePage.java:10:	Each class should declare at least one constructor</br>
src/test/java/nz/ac/massey/cs/TestHomePage.java:12:	Field comments are required</br>
src/test/java/nz/ac/massey/cs/TestHomePage.java:12:	Found non-transient, non-static member. Please mark as transient or provide accessors.</br>
src/test/java/nz/ac/massey/cs/TestHomePage.java:15:	Public method and constructor comments are required</br>
src/test/java/nz/ac/massey/cs/TestHomePage.java:21:	JUnit tests should include assert() or fail()</br>
src/test/java/nz/ac/massey/cs/TestHomePage.java:21:	Public method and constructor comments are required</br>
## Here is the result of metrics report:
<?xml version="1.0" encoding="UTF-8"?>
<Metrics scope="159251" type="Project" date="2018-11-19" xmlns="http://metrics.sourceforge.net/2003/Metrics-First-Flat">
   <Metric id = "VG" description ="McCabe Cyclomatic Complexity" max ="10" hint ="use Extract-method to split the method up">
      <Values per = "method" avg = "1.176" stddev = "0.706" max = "4">
         <Value name="onSubmit" source ="ClearForm.java" package ="nz.ac.massey.cs" value ="4"/>
         <Value name="TasksPage.anonymous#[!5#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="4"/>
         <Value name="TasksPage.anonymous#[!6#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="4"/>
         <Value name="main" source ="Start.java" package ="nz.ac.massey.cs" value ="4"/>
         <Value name="TasksPage.anonymous#[!3#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="3"/>
         <Value name="TasksPage.anonymous#[!4#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="3"/>
         <Value name="TasksPage.anonymous#[#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="3"/>
         <Value name="TasksPage.anonymous#[!2#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="2"/>
         <Value name="TasksPage.anonymous#[!8#onClick" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="2"/>
         <Value name="ClearForm" source ="ClearForm.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="EntryForm" source ="EntryForm.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="onSubmit" source ="EntryForm.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="Task" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="Task" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getDate" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getDescription" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getDueDate" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getId" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getName" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getProjectTitle" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getname" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="isComplete" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="isCompleted" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setCompleted" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setComplete" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setDate" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setDescription" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setDueDate" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setId" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setName" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setProjectTitle" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TaskList" source ="TaskList.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="addTask" source ="TaskList.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getTasks" source ="TaskList.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="removeTask" source ="TaskList.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TasksPage" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TasksPage.anonymous#[!7#populateItem" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TasksPage.anonymous#[!7.anonymous##onUpdate" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getHomePage" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getTaskList" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="init" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="homepageRendersSuccessfully" source ="TestHomePage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setUp" source ="TestHomePage.java" package ="nz.ac.massey.cs" value ="1"/>
      </Values>
   </Metric>
   <Metric id = "PAR" description ="Number of Parameters" max ="5" hint ="Move invoked method or pass an object">
      <Values per = "method" avg = "0.5" stddev = "0.776" max = "4">
         <Value name="Task" source ="Task.java" package ="nz.ac.massey.cs" value ="4"/>
         <Value name="ClearForm" source ="ClearForm.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="EntryForm" source ="EntryForm.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setCompleted" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setComplete" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setDate" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setDescription" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setDueDate" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setId" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setName" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setProjectTitle" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="addTask" source ="TaskList.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="removeTask" source ="TaskList.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TasksPage.anonymous#[!7#populateItem" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TasksPage.anonymous#[!7.anonymous##onUpdate" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="main" source ="Start.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="onSubmit" source ="ClearForm.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="onSubmit" source ="EntryForm.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="Task" source ="Task.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="getDate" source ="Task.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="getDescription" source ="Task.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="getDueDate" source ="Task.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="getId" source ="Task.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="getName" source ="Task.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="getProjectTitle" source ="Task.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="getname" source ="Task.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="isComplete" source ="Task.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="isCompleted" source ="Task.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TaskList" source ="TaskList.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="getTasks" source ="TaskList.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!2#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!3#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!4#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!5#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!6#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!8#onClick" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="getHomePage" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="getTaskList" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="init" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="homepageRendersSuccessfully" source ="TestHomePage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="setUp" source ="TestHomePage.java" package ="nz.ac.massey.cs" value ="0"/>
      </Values>
   </Metric>
   <Metric id = "NBD" description ="Nested Block Depth" max ="5" hint ="use Extract-method to split the method up">
      <Values per = "method" avg = "1.206" stddev = "0.758" max = "5">
         <Value name="TasksPage" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="5"/>
         <Value name="TasksPage.anonymous#[!6#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="4"/>
         <Value name="onSubmit" source ="ClearForm.java" package ="nz.ac.massey.cs" value ="3"/>
         <Value name="TasksPage.anonymous#[!3#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="3"/>
         <Value name="TasksPage.anonymous#[!4#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="3"/>
         <Value name="TasksPage.anonymous#[!5#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="3"/>
         <Value name="TasksPage.anonymous#[#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="3"/>
         <Value name="TasksPage.anonymous#[!2#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="2"/>
         <Value name="TasksPage.anonymous#[!7#populateItem" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="2"/>
         <Value name="TasksPage.anonymous#[!8#onClick" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="2"/>
         <Value name="main" source ="Start.java" package ="nz.ac.massey.cs" value ="2"/>
         <Value name="ClearForm" source ="ClearForm.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="EntryForm" source ="EntryForm.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="onSubmit" source ="EntryForm.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="Task" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="Task" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getDate" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getDescription" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getDueDate" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getId" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getName" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getProjectTitle" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getname" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="isComplete" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="isCompleted" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setCompleted" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setComplete" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setDate" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setDescription" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setDueDate" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setId" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setName" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setProjectTitle" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TaskList" source ="TaskList.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="addTask" source ="TaskList.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getTasks" source ="TaskList.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="removeTask" source ="TaskList.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TasksPage.anonymous#[!7.anonymous##onUpdate" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getHomePage" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getTaskList" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="init" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="homepageRendersSuccessfully" source ="TestHomePage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setUp" source ="TestHomePage.java" package ="nz.ac.massey.cs" value ="1"/>
      </Values>
   </Metric>
   <Metric id = "CA" description ="Afferent Coupling">
      <Values per = "packageFragment" avg = "0" stddev = "0" max = "0">
         <Value name="nz.ac.massey.cs" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="nz.ac.massey.cs" package ="nz.ac.massey.cs" value ="0"/>
      </Values>
   </Metric>
   <Metric id = "CE" description ="Efferent Coupling">
      <Values per = "packageFragment" avg = "3" stddev = "1" max = "4">
         <Value name="nz.ac.massey.cs" package ="nz.ac.massey.cs" value ="4"/>
         <Value name="nz.ac.massey.cs" package ="nz.ac.massey.cs" value ="2"/>
      </Values>
   </Metric>
   <Metric id = "RMI" description ="Instability">
      <Values per = "packageFragment" avg = "1" stddev = "0" max = "1">
         <Value name="nz.ac.massey.cs" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="nz.ac.massey.cs" package ="nz.ac.massey.cs" value ="1"/>
      </Values>
   </Metric>
   <Metric id = "RMA" description ="Abstractness">
      <Values per = "packageFragment" avg = "0" stddev = "0" max = "0">
         <Value name="nz.ac.massey.cs" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="nz.ac.massey.cs" package ="nz.ac.massey.cs" value ="0"/>
      </Values>
   </Metric>
   <Metric id = "RMD" description ="Normalized Distance">
      <Values per = "packageFragment" avg = "0" stddev = "0" max = "0">
         <Value name="nz.ac.massey.cs" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="nz.ac.massey.cs" package ="nz.ac.massey.cs" value ="0"/>
      </Values>
   </Metric>
   <Metric id = "DIT" description ="Depth of Inheritance Tree">
      <Values per = "type" avg = "2.75" stddev = "1.854" max = "5">
         <Value name="TasksPage.anonymous#[!7.anonymous#" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="8"/>
         <Value name="TasksPage.anonymous#[!2" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="7"/>
         <Value name="TasksPage.anonymous#[!3" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="7"/>
         <Value name="TasksPage.anonymous#[!4" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="7"/>
         <Value name="TasksPage.anonymous#[!5" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="7"/>
         <Value name="TasksPage.anonymous#[!7" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="7"/>
         <Value name="TasksPage.anonymous#[!8" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="6"/>
         <Value name="ClearForm" source ="ClearForm.java" package ="nz.ac.massey.cs" value ="5"/>
         <Value name="EntryForm" source ="EntryForm.java" package ="nz.ac.massey.cs" value ="5"/>
         <Value name="TasksPage" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="5"/>
         <Value name="TasksPage.anonymous#[" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="5"/>
         <Value name="TasksPage.anonymous#[!6" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="5"/>
         <Value name="WicketApplication" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="3"/>
         <Value name="Task" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TaskList" source ="TaskList.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="Start" source ="Start.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TestHomePage" source ="TestHomePage.java" package ="nz.ac.massey.cs" value ="1"/>
      </Values>
   </Metric>
   <Metric id = "WMC" description ="Weighted methods per Class">
      <Values per = "type" total = "40" avg = "5" stddev = "5.431" max = "19">
         <Value name="Task" source ="Task.java" package ="nz.ac.massey.cs" value ="19"/>
         <Value name="ClearForm" source ="ClearForm.java" package ="nz.ac.massey.cs" value ="5"/>
         <Value name="TaskList" source ="TaskList.java" package ="nz.ac.massey.cs" value ="4"/>
         <Value name="TasksPage.anonymous#[!5" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="4"/>
         <Value name="TasksPage.anonymous#[!6" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="4"/>
         <Value name="Start" source ="Start.java" package ="nz.ac.massey.cs" value ="4"/>
         <Value name="TasksPage.anonymous#[" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="3"/>
         <Value name="TasksPage.anonymous#[!3" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="3"/>
         <Value name="TasksPage.anonymous#[!4" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="3"/>
         <Value name="WicketApplication" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="3"/>
         <Value name="EntryForm" source ="EntryForm.java" package ="nz.ac.massey.cs" value ="2"/>
         <Value name="TasksPage.anonymous#[!2" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="2"/>
         <Value name="TasksPage.anonymous#[!8" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="2"/>
         <Value name="TestHomePage" source ="TestHomePage.java" package ="nz.ac.massey.cs" value ="2"/>
         <Value name="TasksPage" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TasksPage.anonymous#[!7" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TasksPage.anonymous#[!7.anonymous#" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
      </Values>
   </Metric>
   <Metric id = "NSC" description ="Number of Children">
      <Values per = "type" total = "0" avg = "0" stddev = "0" max = "0">
         <Value name="ClearForm" source ="ClearForm.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="EntryForm" source ="EntryForm.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="Task" source ="Task.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TaskList" source ="TaskList.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!2" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!3" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!4" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!5" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!6" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!7" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!7.anonymous#" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!8" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="WicketApplication" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="Start" source ="Start.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TestHomePage" source ="TestHomePage.java" package ="nz.ac.massey.cs" value ="0"/>
      </Values>
   </Metric>
   <Metric id = "NORM" description ="Number of Overridden Methods">
      <Values per = "type" total = "0" avg = "0" stddev = "0" max = "0">
         <Value name="TasksPage.anonymous#[" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TasksPage.anonymous#[!2" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TasksPage.anonymous#[!3" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TasksPage.anonymous#[!4" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TasksPage.anonymous#[!5" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="ClearForm" source ="ClearForm.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="EntryForm" source ="EntryForm.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="Task" source ="Task.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TaskList" source ="TaskList.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!6" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!7" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!7.anonymous#" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!8" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="WicketApplication" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="Start" source ="Start.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TestHomePage" source ="TestHomePage.java" package ="nz.ac.massey.cs" value ="0"/>
      </Values>
   </Metric>
   <Metric id = "LCOM" description ="Lack of Cohesion of Methods">
      <Values per = "type" avg = "0.109" stddev = "0.289" max = "0.874">
         <Value name="Task" source ="Task.java" package ="nz.ac.massey.cs" value ="0.874"/>
         <Value name="ClearForm" source ="ClearForm.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="EntryForm" source ="EntryForm.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TaskList" source ="TaskList.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!2" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!3" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!4" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!5" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!6" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!7" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!7.anonymous#" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!8" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="WicketApplication" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="Start" source ="Start.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TestHomePage" source ="TestHomePage.java" package ="nz.ac.massey.cs" value ="0"/>
      </Values>
   </Metric>
   <Metric id = "NOF" description ="Number of Attributes">
      <Values per = "type" total = "14" avg = "1.75" stddev = "2.332" max = "7">
         <Value name="Task" source ="Task.java" package ="nz.ac.massey.cs" value ="7"/>
         <Value name="EntryForm" source ="EntryForm.java" package ="nz.ac.massey.cs" value ="4"/>
         <Value name="TaskList" source ="TaskList.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="WicketApplication" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TestHomePage" source ="TestHomePage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="ClearForm" source ="ClearForm.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!2" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!3" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!4" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!5" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!6" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!7" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!7.anonymous#" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!8" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="Start" source ="Start.java" package ="nz.ac.massey.cs" value ="0"/>
      </Values>
   </Metric>
   <Metric id = "NSF" description ="Number of Static Attributes">
      <Values per = "type" total = "4" avg = "0.5" stddev = "0.866" max = "2">
         <Value name="ClearForm" source ="ClearForm.java" package ="nz.ac.massey.cs" value ="2"/>
         <Value name="TasksPage" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="2"/>
         <Value name="TasksPage.anonymous#[!7" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="EntryForm" source ="EntryForm.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="Task" source ="Task.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TaskList" source ="TaskList.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!2" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!3" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!4" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!5" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!6" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!7.anonymous#" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!8" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="WicketApplication" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="Start" source ="Start.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TestHomePage" source ="TestHomePage.java" package ="nz.ac.massey.cs" value ="0"/>
      </Values>
   </Metric>
   <Metric id = "NOM" description ="Number of Methods">
      <Values per = "type" total = "33" avg = "4.125" stddev = "5.732" max = "19">
         <Value name="Task" source ="Task.java" package ="nz.ac.massey.cs" value ="19"/>
         <Value name="TaskList" source ="TaskList.java" package ="nz.ac.massey.cs" value ="4"/>
         <Value name="WicketApplication" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="3"/>
         <Value name="ClearForm" source ="ClearForm.java" package ="nz.ac.massey.cs" value ="2"/>
         <Value name="EntryForm" source ="EntryForm.java" package ="nz.ac.massey.cs" value ="2"/>
         <Value name="TestHomePage" source ="TestHomePage.java" package ="nz.ac.massey.cs" value ="2"/>
         <Value name="TasksPage" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TasksPage.anonymous#[" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TasksPage.anonymous#[!2" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TasksPage.anonymous#[!3" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TasksPage.anonymous#[!4" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TasksPage.anonymous#[!5" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TasksPage.anonymous#[!6" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TasksPage.anonymous#[!7" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TasksPage.anonymous#[!7.anonymous#" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TasksPage.anonymous#[!8" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="Start" source ="Start.java" package ="nz.ac.massey.cs" value ="0"/>
      </Values>
   </Metric>
   <Metric id = "NSM" description ="Number of Static Methods">
      <Values per = "type" total = "1" avg = "0.125" stddev = "0.331" max = "1">
         <Value name="Start" source ="Start.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="ClearForm" source ="ClearForm.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="EntryForm" source ="EntryForm.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="Task" source ="Task.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TaskList" source ="TaskList.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!2" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!3" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!4" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!5" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!6" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!7" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!7.anonymous#" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!8" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="WicketApplication" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TestHomePage" source ="TestHomePage.java" package ="nz.ac.massey.cs" value ="0"/>
      </Values>
   </Metric>
   <Metric id = "SIX" description ="Specialization Index">
      <Values per = "type" avg = "0" stddev = "0" max = "0">
         <Value name="TasksPage.anonymous#[!2" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="7"/>
         <Value name="TasksPage.anonymous#[!3" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="7"/>
         <Value name="TasksPage.anonymous#[!4" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="7"/>
         <Value name="TasksPage.anonymous#[!5" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="7"/>
         <Value name="TasksPage.anonymous#[" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="5"/>
         <Value name="ClearForm" source ="ClearForm.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="EntryForm" source ="EntryForm.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="Task" source ="Task.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TaskList" source ="TaskList.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!6" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!7" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!7.anonymous#" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!8" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="WicketApplication" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="Start" source ="Start.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TestHomePage" source ="TestHomePage.java" package ="nz.ac.massey.cs" value ="0"/>
      </Values>
   </Metric>
   <Metric id = "NOC" description ="Number of Classes">
      <Values per = "packageFragment" total = "8" avg = "4" stddev = "2" max = "6">
         <Value name="nz.ac.massey.cs" package ="nz.ac.massey.cs" value ="6"/>
         <Value name="nz.ac.massey.cs" package ="nz.ac.massey.cs" value ="2"/>
      </Values>
   </Metric>
   <Metric id = "NOI" description ="Number of Interfaces">
      <Values per = "packageFragment" total = "0" avg = "0" stddev = "0" max = "0">
         <Value name="nz.ac.massey.cs" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="nz.ac.massey.cs" package ="nz.ac.massey.cs" value ="0"/>
      </Values>
   </Metric>
   <Metric id = "NOP" description ="Number of Packages">
      <Value value="2"/>
   </Metric>
   <Metric id = "TLOC" description ="Total Lines of Code">
      <Value value="460"/>
   </Metric>
   <Metric id = "MLOC" description ="Method Lines of Code">
      <Values per = "method" total = "281" avg = "8.265" stddev = "26.264" max = "150">
         <Value name="TasksPage" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="150"/>
         <Value name="main" source ="Start.java" package ="nz.ac.massey.cs" value ="48"/>
         <Value name="onSubmit" source ="ClearForm.java" package ="nz.ac.massey.cs" value ="24"/>
         <Value name="TasksPage.anonymous#[!6#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="21"/>
         <Value name="TasksPage.anonymous#[!5#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="18"/>
         <Value name="onSubmit" source ="EntryForm.java" package ="nz.ac.massey.cs" value ="16"/>
         <Value name="TasksPage.anonymous#[!4#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="11"/>
         <Value name="TasksPage.anonymous#[!3#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="10"/>
         <Value name="TasksPage.anonymous#[#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="10"/>
         <Value name="EntryForm" source ="EntryForm.java" package ="nz.ac.massey.cs" value ="9"/>
         <Value name="TasksPage.anonymous#[!7#populateItem" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="9"/>
         <Value name="TasksPage.anonymous#[!2#onSubmit" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="8"/>
         <Value name="Task" source ="Task.java" package ="nz.ac.massey.cs" value ="5"/>
         <Value name="TasksPage.anonymous#[!8#onClick" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="3"/>
         <Value name="init" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="2"/>
         <Value name="homepageRendersSuccessfully" source ="TestHomePage.java" package ="nz.ac.massey.cs" value ="2"/>
         <Value name="ClearForm" source ="ClearForm.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getDate" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getDescription" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getDueDate" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getId" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getName" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getProjectTitle" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getname" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="isComplete" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="isCompleted" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setCompleted" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setComplete" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setDate" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setDescription" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setDueDate" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setId" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setName" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setProjectTitle" source ="Task.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="TaskList" source ="TaskList.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="addTask" source ="TaskList.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getTasks" source ="TaskList.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="removeTask" source ="TaskList.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getHomePage" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="getTaskList" source ="WicketApplication.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="setUp" source ="TestHomePage.java" package ="nz.ac.massey.cs" value ="1"/>
         <Value name="Task" source ="Task.java" package ="nz.ac.massey.cs" value ="0"/>
         <Value name="TasksPage.anonymous#[!7.anonymous##onUpdate" source ="TasksPage.java" package ="nz.ac.massey.cs" value ="0"/>
      </Values>
   </Metric>
   </Metrics>


***

# Part 5
#### any other features you feel worth mentioning.
 
 

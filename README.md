# Todo
S.no	Page	Input	Output
1	Index	Login: already register user can click login	Redirected to login page
		Signup: new user can click signup	Redirected to signup page
2	Signup	If the fields are empty	Redirected to the same page with error messages
		If the name entered is already registered user 	Redirected to the same page with error message
		If the password and repeat password field are not equal	Redirected to the same page with error message
		If all the details are entered correctly	You will be redirected to the conform details page
3	Conform details	You can check the details and click conform details button	You will be redirected to the login page
		If you click edit 	It will redirect to edit details page
4	Login	Enter the invalid user name or password 	You will be redirected to the same page with error message
		Enter the valid user name and password	Yow will be redirected to the manage task page
5	Manage task	Create task	It will redirect to create task page
		List pending task	It will redirect to listing page.
		List completed task	It will redirect to listing page.
		List all task	It will redirect to listing page.
		Notification 	It will redirect to listing page.
6	Create task	Invalid details	Redirected to the same page with some error messages
		Valid details	Task is created and redirected to listing page
7	List pending task	List pending task	The tasks with the status as undone will be displayed
8	Edit	Edit the status as done	The task will be moved to completed task page
9	List completed task	List completed task	The tasks with status completed will be displayed
10	List all task 	List all task	It will display all the task history with status done and undone
11	Notification 	The task which is to be completed today will be displayed	The task with deadline given as todays dates will be displated


Tools used: eclipse, h2, Tomcat.
Technology used: xml, angular Js, spring, hibernate and h2 db.
								Submitted by 
									M.B.A.SHANJITH JOY

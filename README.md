
![# CodeScanner](/CodeVulnerabilityChecker/Content/logo.png)

A very simple ASP.NET web application created for University coursework. Minimal functionality, the coursework was focused on security.

<hr>

### The Task

>Any	serious	application	will	have	several	thousands	to	millions	of	lines	of	
code,	which	makes	it	really	hard	for	anyone	to	manually	review	the	code.	It	
is	in light	of	this	expanded	codebase	that	I	would	like	you	to create	a	
service	which	hosts	automated	online	code	reviews.	The	application	will	be	
accessed	remotely.	After	someone	has	successfully	authenticated	they	will	
be	able	to	upload	code	snippets	or	a	code	file.	The	automated	service	will	
review	the	code	and	generate	a	report	that will	be	sent	back	to	the	user	
with	comments	on	the	code.	Obviously	writing	a	fully-fledged automated	
code	review	system	is a	complex	task	hence	for	this	assignment	we	will	aim	
for	an	imitation	service.	 Your	application	should	return	all	lines	of	code	
with any known	security	flaws in	the	submitted	code.

<hr />

As part of University coursework, this web application called CodeScanner has been created. The web app functionality is a prototype or “dummy” code vulnerability scanner that will take in code snippets written in C# (.NET framework) as text or from a file to match against known vulnerabilities. The application allows users to login and upload text or files to be reviewed and checked for vulnerabilities. The focus on the application is on security rather than functionality, so vulnerabilities that it detects are simply matched against hard-coded string in a C# dictionary object. Information was taken from a database from circl.lu using their database API available at: https://cve.circl.lu/api/.The API connection was made and returned JSON as expected, however it was not used in the end due to unnecessary implementation for the nature of this project. The application is temporarily deployed at https://codescanner.azurewebsites.net/ 

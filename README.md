# Cross-site-scripting-page-injection
I wanted to test the security of the stuyvesant homework servers

### Vulnerabilities: 
* cross-site scripting
  * Solution: escaping and custom markup langauge for links
* cgi error throwing (invalid student name)
  * Solution: log errors into a file instead of showing them on the page

##### Simulation:
If you want to see how the attack would look, clone this project and run grabber.py as a flask app

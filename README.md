# Exam Question Keywords - Thomas Ebsen
 
## 1.1 We have looked at some static analysis tools like StyleCop, PMD, FindBugs and SonarLint. Explain how static analysis can improve code quality. Explain how it helped you or could have helped you in your project</h1>   
<b>STATIC ANALYSIS - NO CODE REQUIRED</b>

- <b>StyleCop, PMD, FindBugs</b>
    - SonarQube use all the above
    - Analyze code and find bugs
    - Made me change console print to logs (blocking call)
- <b>Linters, SonarLint</b>
    - Improve code as you write it - Live code correction
    - Decrease need of refactoring
    - Easy to spot mistakes / bugs
    - <img src="media/lint.png">
- <b>Security</b>
    - Static application security testing (SAST)
    - Highlight Security Vulnerabilities
    - Whitebox Testing
    - Runtime Vulnerabilities
- <b>Code Smells</b>
    - NOT BUGS
    - Indicate violation of fundamentals
    - Code might work, but setup is flawed
    - Fix unused variables (dead stores), wasted processor time and memory
    - Cleanup code, make it run more smooth
- <b>Technical Debt</b>
    - Agile Manifesto
    - Cost of rework / refactoring
     - Cruft - badly designed, unnecessarily complicated, or unwanted code  
    - <img width=500px src="media/techdebt.png">

## 1.2 Explain test levels, and what characterizes the individual levels. Then, relate to your own project.
- **Unit Testing** - <a href="https://github.com/SOFT2020-Test/Assignment-3/tree/main/src/test/java/unit/servicelayer">Assignment-3</a>
    - Testing software components
    - Testing functionality
    - Validate that the programs units are working as intended

- **Integration Testing** - <a href="https://github.com/SOFT2020-Test/Assignment-3/tree/main/src/test/java/integration">Assignment-3</a>
    - Test data flow from one module to another
    - E.g. test that a customer is created and stored in database
    - Test integration between program and database
    - Unit vs Integration
    - <img src="media/unitintegration.gif">
- **System Testing**
    - Evaluate Functional and Non-Functional needs for testing
    - Test the system as a whole
    - It is **Black Box** Testing
    - **Testing Types** - Performance, Load, Stress & Scalability Testing
    - **The Process** - Test Environment Setup -> Create Test Case -> Create Test Data -> Defect Reporting -> Regression Testing -> Log Defects -> Retest  
    <img src="media/441.jpg" width=500px>



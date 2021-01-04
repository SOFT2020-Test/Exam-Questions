# Exam-Questions
 
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
    - <img width=500px src="media/techdebt.png">

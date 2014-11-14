Meister's Design & Development Process

# Deployment Plan

## Test/ Update files/ features loaclly

##### Make change to file
> 1. git add -A
> 2. git commit -m “detailed update of changes”

### Promote to Staging
* $ git push stage1 master

### Test Staging
* Replicate any issues in local dev environment
* A new local dev branch may be needed to start over

### Promote to Production/ sLive
* Have other users try it out prior to going live in production
* If no issues are present promote to Production server

### Promote to Live Server
* $ git push sLive master



=======
Analyze & Design
-------------

...In this phase I will be reviewing the topics and writing **pseudo-code** and designing a **flow chart** based on the requirements of the project.

- link to **[pseudo-code][0]**
 


[0]: https://github.com/MeisterWebzr/MDD/blob/gh/pseduo-code.txt
 
Develope Debug & Test
----------

...In this phase I will be reviewing the Analyze & Design **pseudo-code**  making updates in code and flowchart where changes have been made. then moving onto developing the css, javascript. Upon successful developement of the pseudo-code and flowchart i will be debugging and testing for flow and function per projects requirements. 

- link to **[pseudo-code][2]**


[2]: https://github.com/meisterwebzr/
>>>>>>> fcccffb986257e0cc6114a544814c541738d5268

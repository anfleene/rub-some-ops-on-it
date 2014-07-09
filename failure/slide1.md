!SLIDE center transition=uncover
# Failure

!SLIDE center transition=uncover
## Internal Failure
 .notes what happens when this application fails

!SLIDE center transition=uncover
## External Failure
 .notes know your dependencies
 .notes What happens if they go down?
 .notes What happens if they are responding slowly

!SLIDE center transition=uncover
## Design for failure
 .notes Build in timeouts
 .notes Expect an api will fail
 .notes Write tests with a failing api
 .notes mission critical add fault tolerence(multiple email providers)

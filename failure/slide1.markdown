!SLIDE center transition=uncover
# Failure

!SLIDE center transition=uncover
# Understanding internal failure
 .note what happens when this application fails

!SLIDE center transition=uncover
# Understanding external failure
 .note know your dependencies
 .note What happens if they go down?
 .note What happens if they are responding slowly

!SLIDE center transition=uncover
# Design for failure
 .note Build in timeouts
 .note Expect an api will fail
 .note Write tests with a failing api
 .note mission critical add fault tolerence(multiple email providers)

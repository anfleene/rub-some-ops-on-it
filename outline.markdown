Debugging
  Track the code path  
  .note When debugging a running system it helps to think about the path through the system
  Reproduction
  .note If you can find the path through the system/app then you can fix it.
  .note Systems thinking(need more)
  Good Monitoring & Logging 

Risk Management
  Assessment -  How Risky is this change?
  .note How will your users be impacted by it?
  .note What is the absolute worst thing that could happen?
  .note What happens if 2 servers are serving different versions of this code?
  Reduction - How Can you reduce this risk of this change?
  .note Slow rollout with feature flags
  .note Migrating data(column names)
  Small changes are safer

Failure
  Understanding internal failure
  .note what happens when this application fails
  Understanding external failure
  .note know your dependencies
  .note What happens if they go down?
  .note What happens if they are responding slowly
  Design for failure
  .note Build in timeouts
  .note Expect an api will fail
  .note Write tests with a failing api
  .note mission critical add fault tolerence(multiple email providers)

Contious Improvment
  .notes Over time lots of small changes can turn a clunker into a well oiled machine.
  .notes Everyone wants the app to run smothly


Debugging
  When debugging a running system it helps to think about the path
through the system
  If you can find the path through the system/app then you can fix it.
  Good Monitoring/Logging can take over from there.

Risk Assessment
  How Risky is this change?
  How will your users be impacted by it?
  What is the absolute worst thing that could happen?
  What happens if 2 servers are serving different versions of this code?

Risk Reduction
  How Can you reduce this risk of this change?
  Slow rollout with feature flags
  Migrating data(column names)
  Small changes are safer

Failure
  How does this code handle failure?
  Know your external dependencies.
  Are they hard dependencies?
  What happens if they go down?/Responding slowly
  Design for failure

Shared Goal
  Contious Improvment - Over time lots of small changes can turn a clunker into a well oiled
machine.
  We all want the app to run smothly


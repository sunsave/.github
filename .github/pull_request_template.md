<!--
This is meant as a guide and memory jog, not a prescriptive list of tasks you must do!
Feel free to modify as suits, just please do read over and make sure you've at least thought about the points and if there's any impact.
-->

<!--
Append the ticket *task ID* to the PR description like so: Awesome update [GEN-123]

Notion will detect this and add a link to the original ticket as a comment.
-->

## Testing

- [ ] I have tested this change against all known scenarios and considered new ones.
  - E.g. net negative import scenario for solution summary graph.
- [ ] I have tested this change against real data

## Monitoring

- [ ] This change can be deployed to prod without triggering any alarms
- [ ] This change will be covered by our existing monitoring
  - No new CloudWatch alarm or Sentry logging is required
- [ ] This change will have no (or positive) effect on resources and/or limits
  - Including CPU, memory, AWS resources, calls to other services

## Rollout

- [ ] This change can be merged immediately into the pipeline upon approval
  - No upstream/downstream/config updates required first
- [ ] All dependent changes are already deployed to prod

## Rollback

- [ ] This change can be rolled back without any issues after deployment to prod.
  - Write out the steps to rollback the change below if helpful.

## UI

- [ ] I added images demonstrating the changes in desktop and mobile views
- [ ] I've checked the changes in Firefox and Safari

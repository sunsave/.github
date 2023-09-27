## What does this change?

<!-- 
**NOTE**: This is meant as a guide and memory jog, not a prescriptive list of tasks you must do!
Feel free to modify as suits, just please do read over and make sure you've at least thought about the points and if there's any impact.
-->

<!-- 
Add details of the change here. A PR should have enough detail to be understandable far in the future. e.g what is the problem/why is the change needed, how does it solve it and any questions or points of discussion.  

Add any relevant tickets or links, eg: Resolves [ticket](http://link-to-ticket)
-->



## Testing

- [ ] I wrote new unit tests for this change
- [ ] I wrote new integration/e2e tests for this change
- [ ] I updated existing tests for this change
- [ ] I ran test commands to test this change (list below)

```
npm run test
```

## Monitoring

- [ ] This change can be deployed to prod without triggering any alarms
- [ ] This change will be covered by our existing monitoring
      (no new /metrics/dashboards/alarms are required)
- [ ] This change will have no (or positive) effect on resources and/or limits
      (including CPU, memory, AWS resources, calls to other services)

## Rollout

- [ ] This change can be merged immediately into the pipeline upon approval (no upstream/downstream/config updates required first)
- [ ] All dependent changes are already deployed to prod
- [ ] This change can be rolled back without any issues after deployment to prod

## UI
<!-- Usually only applicable to UI changes: what did it look like before and what will it look like after? -->

### Design review

- [ ] I requested review from @jacklsmith
      
### Images
- [ ] I added images demonstrating the changes in desktop and mobile views


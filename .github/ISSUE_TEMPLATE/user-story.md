**As a** User  
**I need** a service that has a counter  
**So that** I can keep track of how many times something has been done.

### Details and Assumptions
* The counter should start from zero.
* The user should be able to increase the counter.
* The current counter value should be displayed to the user.

### Acceptance Criteria

```gherkin
Given the counter is available
When the user increments the counter
Then the counter value should increase by one

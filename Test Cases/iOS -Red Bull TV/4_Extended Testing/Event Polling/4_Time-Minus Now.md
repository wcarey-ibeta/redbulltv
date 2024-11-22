Precondition
```
### Access to liveops dashboard
- https://liveopsdashboard-qa.redbull.com
- Event Profile - rrn:content:event-profiles:ad937e0d-02bd-4402-b97e-390f11ca7b10

### Set event start date to Now
1. Update event stop start time to Now
```

Step 1:
```
### Update badge for `<test asset>`
1. Update event stop badge to "Delayed"
2. Update "Message and Image" field to "About to Start"
3. Save the Event Stop
4. Update event livestream badge to "Delayed"
5. Update "Message and Image" field to "About to Start"
4. Save the livestream
5. Allow 10 seconds to pass
```
```
The associated `<test asset>` badge will be updated after 10 seconds
```

Step 2:
```
### Verify Home Page `<test asset>` is updated
1. Observe `<featured event>` Badging
2. Observe `<featured live program>` Badging
3. Observe `<16x9 card>` Badging
```
```
The associated `<test asset>` is updated
- Badging will display "Delayed"
```

Step 3:
```
### Verify Event Page `<test asset>` is updated
1. Observe `<featured event>` Badging
2. Observe `<featured live program>` Badging
3. Observe `<16x9 card>` Badging
```
```
The associated `<test asset>` is updated
- Badging will display "Delayed"
```

Step 4:
```
### Verify Event Stop `<test asset>` is updated
1. Select `<test asset>` from the Events Page
2. Observe `<page header>` Badging
3. Observe `<schedule card>` Badging
```
```
The associated Featured Live Program Carousel Card is updated
- Badging will display "Delayed"
```
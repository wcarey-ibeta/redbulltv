Precondition
```
### Access to liveops dashboard
- https://liveopsdashboard-qa.redbull.com
- Event Profile - rrn:content:event-profiles:ad937e0d-02bd-4402-b97e-390f11ca7b10

### Set event start date to 3 hours in the future
1. Update event stop start time to 3 hours from now
2. Close and relaunch the application
```

Step 1:
```
### Update badge for `<test asset>`
1. Update event stop badge to "Unconfirmed"
2. Update "Message and Image" field to "5 minute polling"
3. Save the Event Stop
4. Update event livestream badge to "Unconfirmed"
5. Update "Message and Image" field to "5 minute polling"
4. Save the livestream
5. Allow 5 minutes to pass
```
```
The associated `<test asset>` badge will be updated after 5 minutes
```

Step 2:
```
### Verify Home Page `<test asset>` is updated every 5 minutes
1. Observe `<featured event>` Badging
2. Observe `<featured live program>` Badging
3. Observe `<16x9 card>` Badging
```
```
The associated `<test asset>` is updated every 5 minutes
- Badging will display "Unconfirmed"
```

Step 3:
```
### Verify Event Page `<test asset>` is updated every 5 minutes
1. Observe `<featured event>` Badging
2. Observe `<featured live program>` Badging
3. Observe `<16x9 card>` Badging
```
```
The associated `<test asset>` is updated every 5 minutes
- Badging will display "Unconfirmed"
```

Step 4:
```
### Verify Event Stop `<test asset>` is updated every 5 minutes
1. Select `<test asset>` from the Events Page
2. Observe `<page header>` Badging
3. Observe `<schedule card>` Badging
```
```
The associated Featured Live Program Carousel Card is update every 5 minutes
- Badging will display "Unconfirmed"
```
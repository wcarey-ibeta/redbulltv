Precondition
```
### Access to liveops dashboard
- https://liveopsdashboard-qa.redbull.com
- Event Profile - rrn:content:event-profiles:ad937e0d-02bd-4402-b97e-390f11ca7b10
```

Step 1:
```
### Update phase for `<test asset>`
1. Update event stop end time to 2 hours ago
2. Update event stop phase to "Post"
3. Update "Message and Image" field to "Post Phase"
4. Save the Event Stop
5. Update event livestream end time to 2 hours ago
6. Update event livestream phase to "Post"
7. Update "Message and Image" field to "Post Phase"
8. Save the livestream
9. Allow 2 minutes to pass
```
```
The associated `<test asset>` badge will be updated after 2 minutes
```

Step 5:
```
### Verify Home Page `<test asset>` is updated every 2 minutes
1. Observe `<featured event>` Badging
2. Observe `<featured live program>` Badging
3. Observe `<16x9 card>` Badging
```
```
The associated `<test asset>` is updated every 2 minutes
- Badging will display "Replay available"
```

Step 6:
```
### Verify Event Page `<test asset>` is updated every 2 minutes
1. Observe `<featured event>` Badging
2. Observe `<featured live program>` Badging
3. Observe `<16x9 card>` Badging
```
```
The associated `<test asset>` is updated every 2 minutes
- Badging will display "Replay available"
```

Step 7:
```
### Verify Event Stop `<test asset>` is updated every 2 minutes
1. Select `<test asset>` from the Events Page
2. Observe `<page header>` Badging
3. Observe `<schedule card>` Badging
```
```
The associated Featured Live Program Carousel Card is update every 2 minutes
- Badging will display "Replay available"
```
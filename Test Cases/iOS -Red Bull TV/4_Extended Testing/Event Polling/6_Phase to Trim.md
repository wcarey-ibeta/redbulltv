Precondition
```
### Access to liveops dashboard
- https://liveopsdashboard-qa.redbull.com
- Event Profile - rrn:content:event-profiles:ad937e0d-02bd-4402-b97e-390f11ca7b10
```

Step 1:
```
### Update phase for `<test asset>`
1. Update event stop phase to "Trim"
2. Update "Message and Image" field to "Trim Phase"
3. Save the Event Stop
4. Update event livestream phase to "Trim"
5. Update "Message and Image" field to "Trim Phase"
4. Save the livestream
5. Allow 10 seconds to pass
```
```
The associated `<test asset>` badge will be updated after 10 seconds
```

Step 2:
```
### Verify Home Page `<test asset>` is updated every 10 seconds
1. Observe `<featured event>` Badging
2. Observe `<featured live program>` Badging
3. Observe `<16x9 card>` Badging
```
```
The associated `<test asset>` is updated every 10 seconds
- Badging will display "Awaiting replay"
```

Step 3:
```
### Verify Event Page `<test asset>` is updated every 10 seconds
1. Observe `<featured event>` Badging
2. Observe `<featured live program>` Badging
3. Observe `<16x9 card>` Badging
```
```
The associated `<test asset>` is updated every 10 seconds
- Badging will display "Awaiting replay"
```

Step 4:
```
### Verify Event Stop `<test asset>` is updated every 10 seconds
1. Select `<test asset>` from the Events Page
2. Observe `<page header>` Badging
3. Observe `<schedule card>` Badging
```
```
The associated Featured Live Program Carousel Card is update every 10 seconds
- Badging will display "Awaiting replay"
```
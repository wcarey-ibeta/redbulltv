Precondition
```
### Access to liveops dashboard
- https://liveopsdashboard-qa.redbull.com
- Event Profile - rrn:content:event-profiles:ad937e0d-02bd-4402-b97e-390f11ca7b10

### Set event start date to 2+ days in the future
1. Update event stop start time to 2+ days from now
2. Update event stop phase to "Pre"
3. Update event stop badge to "Time TBA"
4. Save the Event Stop
5. Update event livestream start time to 2+ days from now
6. Update event stop phase to "Pre"
7. Update event stop badge to "Time TBA"
8. Save the livestream
9. Launch application
```

Step 1:
```
### Verify Home Page `<test asset>` is updated on app launch
1. Observe `<featured event>` Badging
2. Observe `<featured live program>` Badging
3. Observe `<16x9 card>` Badging
```
```
The associated `<test asset>` is updated on app launch
- Badging will display "Time TBA"
```

Step 1:
```
### Verify Event Page `<test asset>` is updated on app launch
1. Observe `<featured event>` Badging
2. Observe `<featured live program>` Badging
3. Observe `<16x9 card>` Badging
```
```
The associated `<test asset>` is updated on app launch
- Badging will display "Time TBA"
```

Step 2:
```
### Verify Event Stop `<test asset>` is updated on app launch
1. Select `<test asset>` from the Events Page
2. Observe `<page header>` Badging
3. Observe `<schedule card>` Badging
```
```
The associated Featured Live Program Carousel Card is update on app launch
- Badging will display "Time TBA"
```
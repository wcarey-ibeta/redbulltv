Precondition
```
# A new instance of `<application>` is installed
```

Step 1:
```
### Verify "Ask App Not to Track" sets OS Consent toggle to "OFF"
1. Launch `<application>` from a fresh install
2. Select "Ask App Not to Track"
3. background the application
4. Open the OS Settings App
5. Navigate to "Privacy & Security > Tracking"
```
```
Allow Tracking toggle will be set to the "ON" position.
```

Step 2:
```
### Verify the tracking setting persists
1. Force Close `<application>`
2. Relaunch `<application>`
```
```
On subsequent launches, the prompt does not reappear, indicating the application remembers the user's choice.
```
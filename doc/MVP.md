- Created the Argo CD app demo for tracking the https://github.com/den-vasyliev/go-demo-app project.
  
- Sync Policy: Automatic
  
![Sync Policy](images/automatic-sync.png)
- After creating the app, it started to sync automatically:
  
![Auto syncing](images/syncing.png)

- The app:
  
![App](images/demo-app.png)

- Port forwarding: `k port-forward -n demo svc/ambassador 8081:80`
  
- Demo: https://asciinema.org/a/0fxdx7gKBGAxeEK8i64awjrtP

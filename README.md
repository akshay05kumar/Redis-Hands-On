**Steps:**
1. Create two Sprintboot applications lets say app1 and app2. App1 will call an api from app2 to get a value.
2. Use Redis cache as a dependency in the code, and then compare if there is any improvement in API call?
3. Start a different server for Redis to mimic that it should not be deployed in the same server where app is deployed to avoid any memory issues.
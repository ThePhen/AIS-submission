# AIS Submission

I decided that...

+ **FE**: Front end - uses REST to expose data from a BE. Can be configured to use any BE via a setting. Likes QR codes for that.
+ **BE**: Back end. Used by FEs. Exposes data and a QR code for FEs to use for their configuration. Uses Blob storage for all 'useful' operations.
+ **TF**: Terraform
+ I'll make a few BEs and FEs. I want to demo using TF in a few settings AND to set the stage for (local) development on a laptop where possible, which I think is critical.

## Layout

|Dir|Thoughts|
|---|----|
|android/|FE needs a REST-ful BE to talk to|
|az-aks/|Web FE|
|az-vm/|Web FE (ideally reachable via LB)|
|docker-compose/|full stack with FE, BE|
|ios/|front-end, needs a REST-ful BE to talk to|
|local-be/|local blob-store and REST API to access that BE| 
|local-web-fe/|full stack. Can be connected to from all clients|


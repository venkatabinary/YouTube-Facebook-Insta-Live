# LiveStreaming
Live Streaming with AWS services
https://docs.aws.amazon.com/solutions/latest/live-streaming-on-aws/architecture-overview.html


![image](https://github.com/venkatabinary/LiveStreaming/assets/96198186/ddf4b511-c95b-45b8-a11e-6c5b9bca1e14)


AWS Well-architected Framework considerations -
Operational excellence - AWS CloudTrail to log all the resources log files
Security - CDN identiffier is created & stored in AWS Secrets Managet
Reliability - redundant live streams are provisioned through AWS Elemental MediaLive and AWS Elemental MediaPackage
performance efficiency - built in to these native AWS services
Cost optimization - cost varies based on a lot of factors like encoded profile, bitrate, total concurrent viewers, etc. 
Sustainability - Live Streaming on AWS is provisoned with managed & serverless services. Hence can be stopped after the live steam. 

Heroku Buildpack for AWS X-Ray
===

Installation
---

Add it to your app:

```
heroku buildpacks:add https://github.com/sutrolabs/heroku-buildpack-xray
```

Configuration
---

The AWS X-Ray daemon (https://github.com/aws/aws-xray-daemon/tree/master/daemon) will pick up environment variables like `AWS_XRAY_ACCESS_KEY_ID`, `AWS_XRAY_SECRET_ACCESS_KEY` and `AWS_XRAY_REGION` to configure itself.


Thanks
---

To the team at Urban Dictionary for creating this buildpack! This is a fork of their excellent work: https://github.com/urbandictionary/heroku-buildpack-xray

# Lab 3: Using build-in functions

Use input parameters to be able to re-use CloudFormation templates-

## Overview
1. Create a CloudFormation template using build-in functions ``Fn::Base64`` and ``Fn::Join``.
1. Create a CloudFormation stack based on your template.

Bash script installing httpd-tools and running a small HTTP load test.

```
#!/bin/bash -ex
yum install -y httpd-tools
ab -n 1000 -c 4 $URL
```

## Documentation
[Build-in functions](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/intrinsic-function-reference.html)

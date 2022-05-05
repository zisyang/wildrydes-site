+++
copyright = "Copyright Amazon.com, Inc. or its affiliates. All Rights Reserved."
spdx-license-identifier = "CC-BY-SA-4.0"
title = "Module 1"
date = 2019-09-09T17:42:10+01:00
weight = 40
+++

### 4. Module 1 - Web Application Cleanup
Delete the AWS Amplify Console application and optionally the AWS CodeCommit or GitHub repository created:

**:white_check_mark: Step-by-step directions**

#### For the Amplify Console web application:

1. Launch the [Amplify Console console page][amplify-console-console].
1. Select the application you launched today.
1. From **Actions** in the top right corner, select *Delete App*
1. Complete the application deletion process.

#### For the IAM Role:

1. Go to the [AWS IAM Console][iam-console]
1. Select **Roles** from the navigation menu.
1. Type `wildrydes-backend-role` into the filter box.
1. Select the role you created in module 1.
1. On the top left, click on the **Delete role** button.
1. Choose **Yes, Delete** when prompted to confirm.

#### For the CodeCommit repository:

1. Open the [AWS CodeCommit console][codecommit-console]
1. Select the radio button next to the repository created today.
1. Select **Delete repository** from the upper right of the page.
1. Complete the repository deletion process.

[amplify-console-console]: https://console.aws.amazon.com/amplify/home
[iam-console]: https://console.aws.amazon.com/iam/home
[codecommit-console]: https://console.aws.amazon.com/codesuite/codecommit/repositories

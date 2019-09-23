# user-service
User Service for User LCM

Serverless express app for User LCM.

<b>Prerequisties:</b>
<br>S3 Bucket creation for the app bundle<

<b>Scripts:</b><br>
To configure the app to run on cloud.<br>
<b>npm run config --account-id=<aws-account-id> --bucket-name=<s3-bucket-name> --function-name=<lambda-function-name></b>

To package the app bundle.<br>
<b>npm run package</b>

To deploy the package on aws<br>
<b>npm run deploy.</b>

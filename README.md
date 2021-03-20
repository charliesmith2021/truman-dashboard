<h1> Truman Dashboard</h1>
<hr>
Take a clone of repo and create two repo secrets with valid aws iam keys. 
This is for proof of concept purposes only, I would recommand running on self-hosted runner in aws which would remove the need for keys. 
<h2>AWS Prerequisites</h2>
 <p>AWS_ACCESS_KEY_ID <br>
 AWS_SECRET_ACCESS_KEY
</p>

<h2> Usage</h2>
<p> Branch name is reference during bucket creation as environment name so branch names need to s3 bucket naming rules https://docs.aws.amazon.com/AmazonS3/latest/dev-retired/BucketRestrictions.html </p>

<h2>Example</h2>
<p> http://develop-truman.s3-website.eu-west-2.amazonaws.com/</p>
<p> http://qa-truman.s3-website.eu-west-2.amazonaws.com/</p>
<p> http://main-truman.s3-website.eu-west-2.amazonaws.com/</p>

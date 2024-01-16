https://stackoverflow.com/questions/59135352/write-s3-objects-with-cdk

need to run this to bootstrap first
`cdk bootstrap aws://<account>/<region>`
then look at the package.json for the "app"
it's looking for cdk-stack.ts under lib folder
now edit cdk-stack.ts to include your s3 bucket etc
`cdk deploy`
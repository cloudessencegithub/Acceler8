# AWS S3 Exercise

## Learning Objectives
- Understand the concepts and principles of S3

### Estimated Time: 1 hour

## Exercise
These exercises should help you practice your knowledge of AWS S3. Good luck!

### Instructions
IMPORTANT NOTE: Read all instructions carefully before starting the exercise.

- Create an S3 bucket in a specific region. List all your S3 buckets. Delete the bucket you just created.
- Upload a file to your S3 bucket. Then, download that file to your local system. Delete the file from your S3 bucket.
- Experiment with different bucket policies and IAM policies to control access to your S3 bucket. Test the policies to ensure they are working as expected.
- Upload a file to your S3 bucket in the STANDARD storage class. Then, transition that file to another storage class, like INTELLIGENT_TIERING, STANDARD_IA, ONEZONE_IA, GLACIER, or GLACIER_DEEP_ARCHIVE.
- Enable versioning on your S3 bucket. Upload a file, make a few changes to the file and upload it again each time you make a change. List all versions of the file in your bucket.
- Turn on static website hosting for your S3 bucket. Upload an HTML file and access it using the endpoint provided by AWS.
- Enable transfer acceleration on your bucket and upload a large file. Measure the time taken and compare it with the time taken when transfer acceleration is not enabled.
- Set up an event notification on your S3 bucket to send a message to an SNS topic or SQS queue whenever a new object is created.
- Set up a lifecycle policy to transition objects from one storage class to another or to delete objects after a certain period.

### Submit your work
- Create a document with the answers/commands you used to complete the exercise.
- Add screenshots of the output of the commands you used to complete the exercise.
- Submit your work on the slack channel for this activity.

------

_If you spot any bugs or issues in this activity, you can [open an issue with your proposed change.](https://github.com/cloudessencegithub/Acceler8/issues/new)_

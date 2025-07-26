### What's Inside the `Documentation` Folder?

This folder contains a visual walkthrough of every key step I took during the S3 bucket security project. Here's what you'll find:

* **Bucket Setup:**
  Screenshots of the two S3 buckets I created, one for storing files and the other for storing server access logs.

* **File Upload:**
  A snapshot showing the successful upload of `sensitive.txt` to the file bucket.

* **Public Policy Applied and the Unchecked Block Access Boxes:**
  A screenshot of the public policy in place and the unchecked block acess boxes.

* **Initial Misconfiguration:**
  Proof that the bucket was publicly accessible, a screenshot displaying `sensitive.txt` successfully accessed through a public URL.

* **IAM User Creation:**
  A screenshot showing the creation of the `junior-analyst` IAM user.

* **Bucket Policy JSON:**
  The full JSON of the IAM bucket policy I applied to restrict access to only the intended user.

* **Public Access Removed:**
  A screenshot showing the "Access Denied" error when attempting to access `sensitive.txt` after tightening permissions.

* **Logging Configuration Enabled:**
  A snapshot of the S3 server access logging setup, confirming logging was correctly enabled.

* **Log Bucket Activity:**
  A screenshot showing log files being successfully written to the log bucket, proof that access events are now being tracked.

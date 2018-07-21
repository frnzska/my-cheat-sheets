## AWS commands

### S3
| what                     | command       
| ------------------------ |:-------------
| **list all** buckets     | `aws s3 ls`
| **list bucket** content  | `aws s3 ls bucket_name`
| **new bucket**           | ` aws s3 mb s3://my-new-bucket`
| **delete bucket**        | `aws s3 rb s3://my-new-bucket --force`
| **copy local to bucket** | `aws s3 cp my_file s3://my-bucket` <br> `aws s3 cp my_folder s3://my-bucket/folder --recursive`
| **copy bucket to local** | `aws s3 cp s3://my-bucket local/path`
| **copy bucket to bucket**| `aws s3 cp s3://my-bucket/file.txt s3://other-bucket`  
| **sync obj**             | `aws s3 sync target dest`

### EC2
| what                     | command       
| ------------------------ |:-------------
| **describe instances**   | `aws ec2 describe-instances` <br> `aws ec2 describe-instances --region eu-west-1` <br> ` aws ec2 describe-instances --filters Name=instance-state-name,Values=running`
| **describe key pairs**   | `aws ec2 describe-key-pairs`

### IAM
| what                     | command       
| ------------------------ |:-------------
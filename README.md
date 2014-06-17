aws-s3-bash-upload
==================

you can upload file to aws s3 using bash, openssl, and curl.

## Usage

```
$ curl -O https://raw.githubusercontent.com/sangwook/aws-s3-bash-upload/master/aws_s3_bash_upload.sh
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   525  100   525    0     0   3876      0 --:--:-- --:--:-- --:--:--  4268
$ chmod u+x aws_s3_bash_upload.sh
$ ./aws_s3_bash_upload.sh your-aws-key-xxxxxxx your-aws-secretkey-XXXXXXXXXXXXXXXXXXXXX your-bucket-name /to/upload/file/tmp.dump s3-ap-northeast-1.amazonaws.com
```

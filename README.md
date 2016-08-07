# This is a ansible playbook for creat an ec2, rds, s3 and build a wordpress with them

## how to use
```
ansible-playbook site.yml
```
PS: 当然你没有配置AWS许可是不能运行成功的，运行之前你需要把你的access加到环境变量里比如说：
```
export AWS_ACCESS_KEY_ID='AK123'
export AWS_SECRET_ACCESS_KEY='abc123'
```

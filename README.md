# aws-cli-linux

#### To install the AWS CLI, run the following commands.
```
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
```

```
unzip awscliv2.zip
```

```
sudo ./aws/install
```
#### After installing the AWS CLI, you'll need to configure it with your AWS credentials

```
aws configure
```

#### Enter your AWS Access Key ID:
When prompted, enter your AWS Access Key ID. You can find this in the AWS Management Console under **IAM > Users > Your Username > Security Credentials.**

#### Enter your AWS Secret Access Key:
Enter the corresponding AWS Secret Access Key. This is also available in the same location as your Access Key ID.

#### Enter your default region:
Specify the AWS region you want to use by default (e.g., us-east-1, us-west-2, etc.). This will be used for AWS CLI commands unless you specify a different region.

#### Enter your default output format:
You can choose the output format for AWS CLI commands. The options are json, text, or table. If you're unsure, json is a safe default.

### Note: If AWS secrete key is not created earlier do the below setup

**IAM > Users > Your Username > Create Access Key.**

![image](https://github.com/user-attachments/assets/9360c51c-ab90-4d6d-a705-bbe1fd9553d3)


#### Select CLI

![image](https://github.com/user-attachments/assets/00eff533-c91d-41af-b920-9b436fd3a1cb)

#### Click on Download. CSV 
**Copy Access Key**<br>
**Copy Secret Access Key**



# Exposed AWS Identity Pool ID Nuclei Template

This Nuclei template is designed to identify exposed AWS Identity Pool IDs in web applications. 

AWS Identity Pool IDs are critical components in AWS Cognito that, if exposed and misconfigured, can lead to potential security risks.

You can read my write-up [here](https://medium.com/@abdelrahmanyousef33/full-control-over-companys-s3-buckets-access-to-all-files-serving-main-domains-6081e49794ad) about how I used it to gain access to all company's S3 buckets.

## Usage

```sh
nuclei -t exposed-aws-identity-pool-id.yaml -u https://example.com
```
![image](https://github.com/user-attachments/assets/ebad3840-7378-472b-b810-a492a6578b98)


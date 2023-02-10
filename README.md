# Cloud Custodian Test

'''bash
custodian run --output-dir output --region all policies/aws/ec2-tag-compliance.yml
custodian report --output-dir output --region all policies/aws/ec2-tag-compliance.yml

custodian run --output-dir output --region all policies/aws/ec2-old-instances.yml
custodian report --output-dir output --region all policies/aws/ec2-old-instances.yml
'''

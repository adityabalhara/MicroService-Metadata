Instructions:

1. Downlaod both files to linux OS.
2. Make metadata.sh file executable using command "chmod +x metadata.sh"
3. MetaData for AWS EC2 Instance is written in metadata.json file in same directory.

BONUS:
You can retrieve value of any subsequent keys from the output stored in json file using below command:
#cat metadata.json | jq -r '.<keyname>'

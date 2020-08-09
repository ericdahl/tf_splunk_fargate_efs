# tf_splunk_fargate_efs

Demo app of Splunk running on AWS ECS Fargate with EFS for storage

Note: Using EFS for this is not generally a good idea for performance. This is
just a prototype/experiment. Why EFS for a demo? partly to learn and partly because
Fargate's 20 GB container limit was a problem for Splunk index data

## TODO

- debug logs not working for first 30 min? random?
- reduce delivery stream delay
- HTTPS only on console?

- clean up SGs

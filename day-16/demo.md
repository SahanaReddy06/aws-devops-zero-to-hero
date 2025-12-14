ec2 ->  ssh -i /drives/c/Users/reddy/Downloads/demo.pem ubuntu@<public ip>
in ec2 -> monitoring -> manage detailed monitoring(enable)
in cloud watch -> metrics->ec2->cpu utilization
open nano file put code cpu_spike.py
`python3`
run `python3 cpu_spike.py`

create alaram
select metric
ec2
across all instance
select ec2 instance id
stastics - avg
period -1min
threshold value 50
create a new topic - give name- provide email - create topic
next
alarm name
create alarm

# AutoScaling EC2 infrastructure with AutoScalingGroup

- Using Target Tracking Scaling Policy

## Working snapshots:-

- Creating cfn stack, and adding parameters:
<img width="1915" height="959" alt="Screenshot 2025-11-12 145358" src="https://github.com/user-attachments/assets/066eb27c-d0bd-41f0-95fd-b723172a9257" />

- Stack creation events logs:
<img width="1919" height="970" alt="Screenshot 2025-11-12 145757" src="https://github.com/user-attachments/assets/41256e40-8961-4b89-8308-35871aa650f7" />

- SSH and run `stress` to simulate traffic spike to ec2 instance (for ~10-15 minutes):
<img width="1176" height="600" alt="Screenshot 2025-11-12 150153" src="https://github.com/user-attachments/assets/fea8dad2-9097-48bc-a923-e6ad30fea2ad" />

- EC2 `CPU Utilization` metrics increased:
<img width="1915" height="973" alt="Screenshot 2025-11-12 150627" src="https://github.com/user-attachments/assets/d8aafdbb-5f46-4ae9-9ebb-c7dea2211677" />

- AutoScaling acitivity logs:
<img width="1916" height="968" alt="Screenshot 2025-11-12 152940" src="https://github.com/user-attachments/assets/c8106d8a-66f3-4bb2-9c12-b025eed55aea" />

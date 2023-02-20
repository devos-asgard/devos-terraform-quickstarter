# Getting started with DevOS Terraform Provisioning

Dev OS Terraform Provisioning 을 처음 시작할때 익힐 수 있는 예제 프로젝트입니다.
Dev OS Terraform Provisioning 을 사용해 AWS EC2 를 생성하는 예제 입니다.

## Provisioning 생성 시 Extra Variables 입력
- key_pair: 키 페어 이름을 입력하세요. 
  - 예: key-name
- region: 리전 아이디를 입력하세요. 
  - 예: ap-northeast-0
- security_groups: 시큐리티 그룹 아이디를 입력하세요. 
  - 예: "[sg-xxxxxxxxxxx]"
- subnet_id: 서브넷의 아이디를 입력하세요.
  - 예: "vpc-subnet-id"
- ec2_name: 생성하고자 하는 인스턴스의 이름을 입력하세요.
  - 예: "instance-name"
- instance_type: 인스턴스 유형을 입력하세요. 
  - 예: "t2.micro"
- assign_ip: Public IP 할당 여부.
  - 예: true
                    

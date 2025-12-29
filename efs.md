EFS is a serverless, fully elastic file storage.

You can use EFS with EC2, Lambda, ECS, other AWS compute services, or on-prem servers.

When creating EFS you typically choose whether it is regional (1 region but available in multiple AZs) or one zone...reduced costs for reduced durability. However it is possible to use VPC peering to access the EFS from other regions or to use an AWS VPN connection to access the EFS from on prem servers.
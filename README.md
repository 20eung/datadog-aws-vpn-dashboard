# Datadog Dashboard for AWS VPN Site

## AWS: Site2Site VPN Connections
1. AWS > VPC > Customer Gateways에 등록 후
2. Site-to-Site VPN Connections에서 Customer Gateway와 Connection 생성
3. Tunnel details > Outside IP address로 Customer VPN과 연결(Status Up) 상태

![AWS-S2S-VPN-Connection](img/aws-s2s-vpn-connections.png)

## Datadog: AWS Integration
- Amazon VPN

![Datadog-AWS-Integration](img/datadog-aws-integrations.png)

## Datadog: AWS VPN Dashboard Graph
![Datadog-AWS-VPN-Dashboard](img/datadog-aws-vpn-dashboard.png)

# Datadog: AWS VPN Dashboard Settings
- Metric: aws.vpn.tunnel_data_in / aws.vpn.tunnel_data_out <-- Bytes
- from: name: _verizon--connection_ <-- AWS Site-to-Site VPN Connections Name

![Datadog-AWS-VPN-Dashboard-Settings](img/datadog-aws-vpn-dashboard-settings.png)

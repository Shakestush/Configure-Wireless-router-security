# Wireless Network Security Configuration Lab
## Project Overview
This repository contains documentation and configuration files for a wireless network security lab implemented in Cisco Packet Tracer. The lab demonstrates the practical implementation of secure wireless network configurations for both primary and guest networks, following industry best practices for SOHO (Small Office/Home Office) environments.
## Lab Objectives
- Configure and secure a primary wireless network
- Implement a separate guest wireless network
- Apply appropriate encryption and authentication methods
- Demonstrate proper SSID broadcast configuration
- Document security best practices for wireless networks

## Implementation Details
### Primary Network Configuration
The main wireless network is configured with the following security settings:
**SSID**: HomeNet
**SSID Broadcast**: Enabled
**Security Mode**: WPA2 Personal
**Encryption**: AES
**Authentication**: Pre-shared key (passphrase)

### Guest Network Configuration
A separate guest network is configured to provide internet access for visitors while maintaining network segmentation:
**SSID** : GuestNet
**SSID Broadcast**: Enabled
**Security Mode**: WPA2 Personal
**Encryption**: AES
**Authentication**: Separate guest passphrase

### Security Considerations
The lab addresses several important wireless security concepts:

1. **SSID Broadcasting**: Demonstrates why disabling SSID broadcast is not an effective security measure (and can attract attackers)
2. **Encryption Standards**: Implements AES encryption as the strongest available option
3. **Network Segmentation**: Isolates guest traffic from the primary network
4. **Authentication Methods**: Utilizes strong passphrases for network access
## Prerequisites
- Cisco Packet Tracer 8.0 or higher
- Basic understanding of networking concepts
- Familiarity with wireless network terminology

## Step-by-Step Implementation
1. Open the Packet Tracer file included in this repository
2. Access the wireless router configuration page
3. Configure the primary HomeNet SSID with WPA2/AES security
4. Enable SSID broadcasting for all wireless networks
5. Create and configure the separate GuestNet SSID
6. Test connectivity from wireless clients
7. Verify security settings are applied correctly

## Security Best Practices Demonstrated
- Using WPA2 Personal with AES encryption instead of older standards
- Creating separate networks for guests and primary users
- Understanding that security through obscurity (hiding SSIDs) is ineffective
- Implementing appropriate authentication mechanisms

## Future Enhancements
- Add MAC address filtering configuration
- Implement wireless intrusion detection
- Configure VLANs for further network segmentation
- Add enterprise authentication using RADIUS server

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Cisco Learning Network for providing Packet Tracer
- Network security community for established best practices

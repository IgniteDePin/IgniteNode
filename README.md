# Ignite Network Node

Contribute your unused bandwidth to the Ignite Network and earn $IGNITE token rewards.

## What is Ignite Network?

Ignite Network is a decentralized bandwidth sharing platform. Users run this node software to contribute their residential internet bandwidth, which is monetized through verified enterprise partners for legitimate use cases like:

- Price comparison and market research
- Ad verification
- SEO monitoring
- Academic research

## Security & Transparency

- **Open Source**: This code is fully open for inspection
- **No Malware**: Scan with [VirusTotal](https://www.virustotal.com/) to verify
- **Verified Partners**: Bandwidth is sold only to vetted enterprise customers through [Pawns.app](https://pawns.app) (by IPRoyal)
- **User Control**: Stop anytime by closing the node
- **Privacy**: We don't access your browsing history, files, or personal data

## Requirements

- Node.js 16 or higher
- An Ignite Network account ([Register here](https://ignitedepin.xyz))
- Residential internet connection

## Installation

```bash
# Download the node script
curl -O https://ignitedepin.xyz/ignitenode.js

# Or clone this repo
git clone https://github.com/YOUR-USERNAME/ignite-node.git
cd ignite-node

## Usage
# Run with credentials
node ignitenode.js --email your@email.com --password yourpassword
# Or use environment variables
export IGNITE_EMAIL=your@email.com
export IGNITE_PASSWORD=yourpassword
node ignitenode.js
How It Works
Authentication: Node logs into your Ignite account
Monitoring: Tracks your real network bandwidth usage
Reporting: Sends bandwidth data to Ignite servers every 30 seconds
Earning: You earn points based on bandwidth contributed
Rewards: Points are converted to $IGNITE tokens via weekly airdrops
Platform Support
Platform	Status
Windows	Supported
macOS	Supported
Linux	Supported
Android	Coming Soon
Earning Points
Activity	Points Earned
Upload (100MB)	1 point
Download (100MB)	0.5 points
Uptime report	1 point

##FAQ
Is this safe?
Yes. The node only monitors and reports your bandwidth usage. It does not access your files, browsing history, or personal data.

Will it slow down my internet?
The node has minimal impact on your connection. It primarily tracks existing bandwidth usage.

How much can I earn?
Earnings depend on your bandwidth contribution and are distributed via weekly $IGNITE airdrops.

##Support
Website: ignitedepin.xyz

##License
MIT License - See LICENSE file for details.

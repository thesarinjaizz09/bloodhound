# 🐺 BloodHound - Active Directory Enumeration Tool

BloodHound is a powerful tool designed to map and analyze Active Directory (AD) environments. It helps penetration testers, red teamers, and security professionals to identify attack paths and privilege escalation opportunities within Active Directory networks. BloodHound provides a graphical interface to visualize these attack paths, making it a crucial tool for AD security assessments.

---

## 🔍 What is BloodHound?

BloodHound is an open-source tool that uses graph theory to model Active Directory (AD) permissions and identify attack paths within the network. It allows attackers (ethical ones in this case) to visualize relationships and privileges between users, groups, and machines within an Active Directory environment. By analyzing these paths, security professionals can identify weaknesses and potential privilege escalation vectors.

---

## 📥 Getting Started

### Prerequisites

- Windows, Linux, or macOS (cross-platform)
- .NET Framework or Mono (for running BloodHound)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/BloodHoundAD/BloodHound.git
   cd BloodHound
Install dependencies:

bash
Copy code
npm install
Download SharpHound (BloodHound’s enumeration tool):

Download the latest release of SharpHound from the BloodHound Releases page.

Run BloodHound:

To start BloodHound and analyze attack paths:

bash
Copy code
BloodHound
Import data collected with SharpHound into the BloodHound interface.

🛠️ Features
Attack Path Visualization: Graphically displays privilege escalation paths and lateral movement opportunities within Active Directory.
AD Enumeration: BloodHound can collect AD data using SharpHound and store it in a graph database.
Cypher Queries: BloodHound provides a powerful query language for detailed analysis and exploration of the AD graph.
Cross-Platform: Works on Windows, macOS, and Linux.
📚 Usage
Running SharpHound
SharpHound is the data collection tool for BloodHound. It collects information about users, groups, trusts, and permissions within Active Directory. To run SharpHound, use the following command:

bash
Copy code
SharpHound.exe -c All
This collects the full set of AD data, including group memberships, trusts, and ACLs.

BloodHound Interface
After collecting data with SharpHound, launch BloodHound and load the collected data:

bash
Copy code
BloodHound
Explore the graph to identify attack paths and analyze the network for privilege escalation opportunities.

📘 Resources
Official Repository: BloodHound GitHub
Documentation: BloodHound Wiki
SharpHound Repository: SharpHound GitHub
BloodHound Community: BloodHound Discussions
🤝 Contributing
We welcome contributions! If you'd like to improve BloodHound, whether by submitting bug fixes, enhancements, or features, please feel free to fork the repository and submit a pull request.

🛡️ License
BloodHound is distributed under the MIT License. See the LICENSE file for more details.

🌐 About BloodHound
BloodHound is developed and maintained by the BloodHound team, including contributors from the security community. It is widely used by red teamers, penetration testers, and cybersecurity professionals for assessing and securing Active Directory environments.

⭐ Show Your Support
If you find BloodHound useful, please give it a ⭐ and share it with your colleagues or the cybersecurity community!

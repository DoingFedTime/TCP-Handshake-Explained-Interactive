# TCP Handshake Interactive Visualization

Live view [here](https://doingfedtime.com/new-interactive-tcp-handshake-visualization-tool-free/)

A dynamic, interactive visualization of the TCP three-way handshake process with additional network scenarios for educational purposes.

![TCP Handshake Visualization](https://i.postimg.cc/k5ghH40h/visualization.png)

## Overview

This project provides an in-browser, interactive visualization of the TCP handshake process. It's designed for educational purposes to help students understand the fundamentals of how TCP connections are established, and what happens in various edge cases and attack scenarios.

## Features

### Interactive Scenarios
- **Normal TCP 3-Way Handshake**: Visualize the standard SYN → SYN-ACK → ACK process
- **SYN-ACK Loss Scenario**: Demonstrate how TCP handles packet loss during connection establishment
- **RST Packet Scenario**: Show connection rejection when a service is unavailable
- **SYN Flood Attack**: Visualize how DDoS attacks can overwhelm servers with half-open connections

### Visual Learning Tools
- Color-coded packets with animated trails
- Real-time state changes for client and server nodes
- Detailed packet information panel showing flag states
- Step-by-step mode for classroom demonstrations

### Educational Content
- Detailed explanations of the TCP handshake process
- Socket programming examples in C
- TCP packet structure breakdown
- Security implications and attack vectors

## Technical Details

This visualization is built with:
- **D3.js**: For handling animations and dynamic elements
- **Pure JavaScript**: No framework dependencies
- **HTML5/CSS3**: For styling and layout

The project works entirely client-side with no server requirements.

## Usage

### For Students
1. Choose a scenario using the buttons at the top
2. Watch the animation and follow along with the status messages
3. Switch between tabs to learn about different aspects of TCP

### For Educators
1. Use the "Step-by-Step Mode" to control the pace of the demonstration
2. Pause at any point to explain what's happening
3. Use the different scenarios to illustrate various networking concepts
4. Reference the code and packet structure tabs for deeper technical discussions

## Installation

No installation required! This is a standalone HTML application:

1. Clone the repository:
```
git clone https://github.com/DoingFedTime/TCP-Handshake-Explained-Interactive.git
```

2. Open the HTML file in any modern browser:
```
open tcp-handshake-visualization.html 
```

## License

This project is released under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- TCP/IP protocol documentation
- D3.js visualization library

## Author

Created by [DoingFedTime](https://github.com/DoingFedTime)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Roadmap
*(would be cool not actually doing it)
- Add four-way connection termination visualization
- Add TCP window scaling and congestion control scenarios
- Create a version with Wireshark packet capture integration
- Add additional attack scenarios (TCP hijacking, etc.)

# PinGrab

PinGrab is a suite of tools designed to transfer data over the ICMP protocol securely and stealthily. This suite consists of three main components: Server, Client, and Decoder. The tools work together to encode, send, and decode data packets hidden within ICMP packets.

## Components

- **pinGrab-Server**: Receives and decodes ICMP packets.
- **pinGrab-Client**: Encodes and sends data via ICMP packets.
- **pinGrab-Decode**: Decodes data received by the server.

## Requirements

- Bash
- ICMP handling network tools (ping, tcpdump)
- Linux-based OS

## Installation

```bash
git clone https://github.com/AyoobAli/pinGrab.git
cd pinGrab
```

Ensure each script is executable:


```bash
chmod +x pinGrab-Server pinGrab-Client pinGrab-Decode
```

## Usage

Each component comes with a set of options and usage instructions, which can be found at the beginning of each script.

- For sending data: ./pinGrab-Client <file_path> <target>
- For receiving data: ./pinGrab-Server [options]
- For decoding data: ./pinGrab-Decode <file_path>

## License

This project is licensed under the GNU GPLv3 - see the [LICENSE](LICENSE) file for details.

## Disclaimer

PinGrab is intended for legal and educational purposes only. It should not be used for unauthorized data transmission over networks.

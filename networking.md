# Networking

- A network is a collection of devices interconnected with each other to perform various functions like sharing data, hardware, and sometimes they can even act as a server to provide services to clients.
- Think of a network like a group of people assembled together to play a football match, play a game, or do studies. Every person has their specific role in the network. For example, in a football team, each player plays at a specific location on the ground and is assigned a specific role. A player might be a defender, a goalkeeper, or an attacker. 
- Similarly, in a network, different devices have different roles depending on the needs.

## Why Learn Networking?

- Networking is the basis of Cyber Security. To defend ourselves from hackers, we must know which network we are connected to, how to block that network from unauthorized access, and much more.
- Since a network links multiple devices, it becomes easier for a hacker to gain unauthorized access if they are knowledgeable about exploiting the network's security vulnerabilities.
- Other practical examples include gaming, social media, education, geo-location, and more.

## Internet

- The Internet is a collection of networks containing small and large networks of different types.
- It was introduced by Tim Berners-Lee in 1989 with the introduction of the World Wide Web.
- It works on the basics of one of the first network models introduced by the US military, ARPANET.

## IP Address

- An IP address is defined as an address that is assigned when a device is connected to the internet.
- It can be of 2 types:
  1. **Public**: A public IP is unique for each device on the internet. It is assigned by Internet Service Providers (ISPs) to devices like routers, servers, or any device communicating directly with the internet.
  2. **Private**: A private IP is assigned to a device in a private network. These IPs are not directly routable on the internet. Instead, these devices connect to the outside world using a public IP. Examples include devices like PCs, laptops, smartphones, etc.

- The following ranges are reserved for private IP addresses:
  - `10.0.0.0` to `10.255.255.255`
  - `172.16.0.0` to `172.31.255.255`
  - `192.168.0.0` to `192.168.255.255`

### IPv4 and IPv6

#### IPv4
- It is one of the core protocols of the IP suite.
- It is made up of 32 bits.
- These 32 bits are divided into 4 octets, where the value of each octet lies between 0-255.
- The IPv4 address space can be subdivided into smaller segments called subnets, allowing for efficient IP address management.

- There are 5 classes in IPv4:

1. **Class A**: Ranges from `1.0.0.0` to `126.255.255.255`
   - First bit of the 8 bits is always `0`.
   - Default subnet mask for this class is `255.0.0.0`.
   - Number of networks available: 128.
   - Total number of hosts (excluding broadcasting): 16 million.
   - This class is typically used for very large networks.

2. **Class B**: Ranges from `128.0.0.0` to `191.255.255.255`
   - First 2 bits are `1` and `0`.
   - Subnet mask is `255.255.0.0`.
   - Number of networks available: 16,384.
   - Number of hosts per network: 65,534.
   - This class is mainly used for medium to large-sized networks.

3. **Class C**: Ranges from `192.0.0.0` to `223.255.255.255`
   - Its first 3 bits are always `1`, `1`, and `0`.
   - Total number of networks: more than 2 million.

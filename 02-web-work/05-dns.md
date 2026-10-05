# What is DNS?

The Domain Name System (DNS) is the phone book of the internet that translates human-readable website names into machine-readable numeric IP addresses.

When you type a web address into your browser, your computer needs an IP address to find that website's server. Because people remember names easily and computers use numbers, DNS bridges this gap.

## How DNS works?

- **The Request** : You type a web address like <mark>example.com</mark> into your web browser.

- **The Resolver** : Your computer asks a DNS recursive resolver (often run by your internet service provider) for the IP address.

- **The Search** : If the resolver does not have the address saved, it asks root nameservers, top-level domain (TLD) servers (like <mark>.com</mark>), and authoritative nameservers until it finds the correct match.

- **The Connection** : The resolver returns the numeric IP address to your computer, allowing your browser to load the website.

## Key Parts of DNS

• **IP Address**: A unique string of numbers that identifies a device or server on a network.

• **Caching**: Saving previously found IP addresses locally or on servers to make future lookups much faster.

• **DNS Records**: Specific data entries (like A, AAAA, and MX records) that store IP addresses, mail servers, and other details for a domain.

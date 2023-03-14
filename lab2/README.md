# Lab Title: [Insert title here]

## Challenge Answers

- **Challenge 1:** [Insert answer here, i.e., a Chuck Norris fact]
- **Challenge 2:** [Insert answer here, i.e., a `password` to unlock the next lab]

## Other Relevant Information

[Insert here, if applicable]

## Lab Prep Questions and Answers

1. What is the _Address Resolution Protocol (ARP)_, and what is its role in a network?

   - ARP is a protocol used in computer networks to map a network address (such as IP address) to a physical adress (MAC address). It enables devices to find each other on the network.

2. What is a _Man-in-the-Middle (MitM)_ attack, and how does ARP spoofing enable it?

   - MitM attack is a type of attack where an attacker intercepts communication between two parties. ASP spoofing -> attacker sends fake ASP messages to associate their own MAC address with the IP address of a device on the network.

3. How does an attacker use ARP spoofing to intercept network traffic?

   - Fake messages that are sent by the attacker contain a spoofed MAC address, which maps to the attacker's device instead of the legitmate device.

4. How is the _cookie_ used to derive the encryption/decryption key?

   - The cookie is passed to the derive_key function which derives the encryption/decryption key from the given key_seed. Uses modern key derivation function scrpyt.

5. What REST API request do you need to send to the _crypto oracle_ the secret cookie?

   - GET /arp/cookie

6. How do you obtain the authentication token?

   - Requesting it from crypto oracle server using the right credentials.

7. How do you use the authentication token to obtain the cookie?

   - By sending a REST API request using the authentication token we can obtain the cookie.

8. What encryption mode is used to encrypt the challenge in this lab?

   - AES-CBC

9. What tool can you use to capture network traffic on a local network interface?
   - tcpdump

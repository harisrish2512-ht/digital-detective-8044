# Mission 7 — How computers communicate

## 1. Task / objective

Explain network concepts, observe connectivity and DNS, and describe what happens when a website opens.

## 2. Work completed

Completed the concepts table, ran a ping test and DNS lookup on example.com, and wrote a 6-step website explanation.

## 3. Commands / tools used
- `ping -c 4 example.com` (Windows: `ping example.com`): checks the site is reachable and how fast
- `nslookup example.com`: shows the IP address linked to the domain

### Task 7.1 — Explain network concepts

| Concept | In my words | Example |
|---|---|---|
| LAN | Network in a small area | Home Wi-Fi |
| MAN | Network across a city/campus | University campus network |
| WAN | Network across large distances | The internet |
| DNS | Turns domain names into IP addresses | example.com → IP |
| Router | Connects networks and forwards data | Home Wi-Fi router |
| Protocol | Rules devices follow to communicate | HTTP/HTTPS |
| Packet switching | Data split into packets that travel separately | A web page arriving in pieces |
| Client-server | Client requests, server responds | Browser and a web server |

### Task 7.2 — Observe network information

- ping checks whether you can reach a host and how long it takes. A DNS lookup shows the IP address for a domain name. DNS lets you type a name instead of remembering numbers.

● Explain what a connectivity test helps you check.
A connectivity test (ping) checks whether your computer can reach another computer or website over the network, and whether the connection is working. 
It also shows how long the round trip takes (response time in milliseconds) and whether any packets were lost. 
If the ping fails, it tells you the problem could be your connection, the website, or something in between.

● Explain what information a DNS lookup displays.
A DNS lookup shows the IP address (the numeric network address) that belongs to a domain name such as example.com.
It also shows which DNS server answered the query.

● Describe the role of DNS when you enter a website name in a browser.
Computers communicate using IP addresses, not names.
When I type a website name, the browser asks a DNS server to translate the name into an IP address. 
Once the browser has the IP address, it can connect to the right server. Without DNS, I’d have to remember the numeric address of every site.

### Task 7.3 - What happens when I open a website?

1. I type a URL , my browser (the client) starts the request.
2. The browser asks DNS to turn the domain into an IP address.
3. The request is split into packets and goes through my router to the internet.
4. The packets reach the server using a protocol (HTTP/HTTPS).
5. The server processes the request and sends a response back.
6. My browser puts the pieces together and shows the page.

## 4. My understanding

I understood what is the backend process occuring when I click on to open a browser.

## 5. Difficulties faced

In the starting I faced difficulties in understanding the backend process between servers. The commands were new and so was little time-taking to cope up with.

## 6. How I resolved them

I asked and learned from my friends. I did my own research and explored about DNS, internet protocols and server intercations.

## 7. Evidence / files

This README. IP addresses and Wi-Fi name redacted from any output. `evidence/Mission 7`

## 8. Commit details
"Explain networking concepts and website communication" — pushed and verified.
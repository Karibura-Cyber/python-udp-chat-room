# Python UDP Chat room

<h2>What is UDP</h2>
<h4>The User Datagram Protocol, or UDP, is a communication protocol used across the Internet for especially time-sensitive transmissions such as video playback or DNS lookups. It speeds up communications by not formally establishing a connection before data is transferred. This allows data to be transferred very quickly, but it can also cause packets to become lost in transit — and create opportunities for exploitation in the form of DDoS attacks.</h4>

<h2>How does UDP work?</h2>
<h4>Like all networking protocols, UDP is a standardized method for transferring data between two computers in a network. Compared to other protocols, UDP accomplishes this process in a simple fashion: it sends packets (units of data transmission) directly to a target computer, without establishing a connection first, indicating the order of said packets, or checking whether they arrived as intended. (UDP packets are referred to as ‘datagrams’.)</h4>

<h4>UDP is faster but less reliable than TCP, another common transport protocol. In a TCP communication, the two computers begin by establishing a connection via an automated process called a ‘handshake.’ Only once this handshake has been completed will one computer actually transfer data packets to the other.</h4>

<img src="https://www.cloudflare.com/img/learning/ddos/glossary/user-datagram-protocol-udp/tcp-vs-udp.svg">


# How to use
<code>1.Download File from github</code><br>
<code>2.Unzip file</code><br>
<code>3.Open cmd or terminal</code><br>
<code>4.python main.py for Server side</code><br> 
<code>python main.py [server ip] for client side</code><br>

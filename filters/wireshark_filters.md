# Wireshark Display Filters

## HTTP

```wireshark
http
```

---

## DNS

```wireshark
dns
```

---

## TCP

```wireshark
tcp
```

---

## ICMP

```wireshark
icmp
```

---

## ARP

```wireshark
arp
```

---

## TCP Handshake

```wireshark
tcp.flags.syn==1
```

---

## HTTP GET Requests

```wireshark
http.request.method=="GET"
```

---

## DNS Queries

```wireshark
dns.flags.response==0
```

---

## DNS Responses

```wireshark
dns.flags.response==1
```

---

## TCP Retransmissions

```wireshark
tcp.analysis.retransmission
```

---

## Reset Packets

```wireshark
tcp.flags.reset==1
```

---

## Follow TCP Stream

Right Click Packet

↓

Follow

↓

TCP Stream

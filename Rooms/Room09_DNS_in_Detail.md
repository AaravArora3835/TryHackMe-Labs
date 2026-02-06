# Room 09 — DNS in Detail

**Date:** 2026-02-05  
**Path:** Pre Security  

## What I did
- Learn about DNS and how it works in detail, and domains as well.

## Key concepts
- DNS is Domain Name System and it helps make a way for us to communicate with devices on the internet without needing to know complex numbers.
- Instead of remembering ips you remember a website name.
- A TLD or Top level domain is the righthand part of a domain so for example the .com or .gov.
- gTLD and ccTLD (generic and country code) gTLD is used for tlling the user the context of a domain like .com commerical, .org for a orginzation. ccTLD is for countries like .ca for canada etc.
- Second level domain is the actual name for example tryhackme in tryhackme.com
- Subdomain is on the lefthand side and there is not limit for what you can make but 253 length limit. ex. admin.tryhackme.com 63 charcter limit, only a-z 0-9 and - cannot start with hyphen
<img width="1078" height="548" alt="image" src="https://github.com/user-attachments/assets/299318a0-51d3-4154-9ae4-d1a9071feb95" />
- DNS can also be used for records. A record is ipv4, AAAA record is ipv6, CNAME record is when a domain name you type leads you to somwhere else but you use that domain name, MX Record used for emails and like a backup server, TXT records are for free text fields where any text based data can be stored

## Evidence
- `2026-02-05_THM_Room09_DNS_in_Detail_Completed.png`

## One takeaway
- Honestly the TLD and Second level domain and tghe sub domain which are all parts of a dns was the biggest takeaway for me

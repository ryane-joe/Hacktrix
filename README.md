# Hacktrix
intro: glyched, is a toolset which contains many use full tools(only a few have been added so far)

tools: file encrytion using fernet,port scanner, sherlock, mass-emailer, mac-changer, network scanner, arp spoofer, network sniffer,dns spoofer, file interceptio

_note- sherlock is not made by me, my program simply installs it and makes it easier to use

language__: python

libraries required: _cryptography, socket, sys, os, datetime, smptplib, csv, subprocess, colorama, email, pyfiglet,scapy,time,scapy_http,netfilterqueue _,re,

                                       _
                                             **TOOLS**
file encryption: it uses fernet to encrypt a text/csv/document and produce a key, it makes it so that the encrypted file cannot be decrypted without the filekey

port scanner: does what the name says! it scans a network for open ports

sherlock: it is a tool which will scan all social media platforms to search for a specifed username, works well for targets using the same name on multiple social meida platforms

*bulk emailer: send a simple email to all emails listed in csv file using smtplib

mac changer: spoofs your mac address, makes it harder to trace your device

network scanner: will scan a network and return all devices connected to the network(ipv4 adresses and MAC adresses) personal tips:

*ARP SPOOF: will send packets to both, target and router saying that our machine is the target to the router and that our machine is the router to the target, this makes it so that all traffic that the target and router are sending to eachother goes through the attacker, NOTE: this ony makes the attacker a man in the middle, for seeing traffic use a 3rd party packet sniffer(USE WITH INCLUDED SNIFFER)

NETWORK SNIFFER: will use scapy to sniff out all http packets, then will spearate all urls and print them without giberish, and uses keywords(very limited number have been added) to check for usernames/passwords, and prints them seperatly NOTE: MENT TO BE USED WITH ARP SPOOFER FOR PROPER ATTACKS

DNS SPOOFER: allows you to redirect a dns reest to a ip of choice

FILE INTERCEPTION: allows you to replace all downloads with a your own download(must specify which file ext to replace), ONLY WORKS WITH HTTP SSL strip: lets you strip the ssl(secure sockets layer or tls(transfer layer security) from packets which are going through you, should let you bypass https(WARNING STILL EXPERIMENTAL)

if the program doesnt run, then try installing all the required dependancies



NOTE: THIS PROGRAM IS ALSO MENTIONED ON MY OLD ACCOUNT. BOTH ACCOUNTS ITS POSTED ON IS OWNED BY ME

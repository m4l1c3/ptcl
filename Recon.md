# Recon

## Sub domains

enumall

sublist3r - scrape search engines for sub domains

massdns - fastest

brutesubs - docker image for recon

cloudflare_enum

gobuster - second fastest

## Acquisitions

crunchbase

## Port scanning

masscan - useful for scanning a high number of hosts, only issue is that all ports to be scanned must be declared

eyewitness - useful for taking screenshots of a list of URLs for visual confirmation or identification of resources under a URL

## Platform identification

burp-vulners-scanner - burp plugin that goes over domains in scope and extract version/platform info about items that are in scope, useful for getting CVEs in an application

## Content discovery

robots disallowed: https://github.com/danielmiessler/RobotsDisallowed

gobuster: https://github.com/OJ/gobuster

go run main.go -u http://192.168.1.48 -m dir -f -w /Users/m4l1c3/Dev/RobotsDisallowed/Top10000-RobotsDisallowed.txt

CMSmap: https://github.com/Dionach/CMSmap.git

dirbuster

## Parameter brute forcing

parameth - brute force discover get and post parameters

backslash-powered-scanner - burp  list of top used parameters from alexa

## Blind XSS

polyglots

seclists

flash

blind xss frameworks

- sleepy puppy - good for managing campaigns
- xss hunter - good payload generation tool
- ground control
- polyglots
- oxsabky/hackvault
- xss mindmap

## Template engines

server side template injection

tplmap + tplmap burp extension

## server side request forgery

open redirects, returnUrl=file:////etc/passwd

ssrf bible -- cheatsheet

## Code injection, command injection, fuzzing

commix

cmdi

supports php code injection

backslash powered scanner ?? burp plugin

emulate backtick or backslash across a large app to then test manually

## infrastructure and coding

subdomain takeover

- check for cnames that resolve to services, if the server has lapsed register and takeover

hostilesubbruteforcer

tko subs

autosubtakeover

sandcastle -- aws

bucket finder -- aws

## scanning git repos

gitrob

trufflehog

check out: jhaddix/tbhm

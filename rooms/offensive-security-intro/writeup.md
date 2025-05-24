## Instructions

We will use a command-line application called [Gobuster](https://github.com/OJ/gobuster) to brute-force FakeBank's website to find hidden directories and pages. Gobuster will take a list of potential page or directory names and try accessing a website with each of them; if the page exists, it tells you.

## Theory

Offensive security aims to **identify** and **exploit system vulnerabilities** to enhance security measures. This includes exploiting **software bugs**, leveraging **insecure setups**, and taking advantage of **unenforced access control policies**, among other strategies. 

## Commands

```sh
gobuster -u http://fakebank.thm -w wordlist.txt dir
```
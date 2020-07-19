# Introduction
This repo is an introduction to cybersecurity, and a list of cybersecurity resources for pentesters and security students. This document assumes no technical knowledge.

This is a big list, and the resources are all pretty technical. It's common for beginners in this field to get overwhelmed by the sheer amount of material to go through, not to mention the complexity. If this happens to you, just take a deep breath and remember that to master hacking takes years of experience. Take one step at a time.



## Books
* [Hacking: The Art of Exploitation, 2nd Edition, Jon Erickson(2008):](https://www.thriftbooks.com/w/hacking-the-art-of-exploitation_jon-erickson/273280/#isbn=1593271441&idiq=5461322)

This is a great book, and an excellent starting point for those already comfortable with technology, though it is complicated and requires careful reading. In this field, books become dated very quickly, but this book overcomes that barrier by focusing mostly on principles, instead of specific tools. You will learn the basics of C programming (a must for reverse engineers) and the techincal details of how to exploit vulnerabilities, plus a primer on cryptography. It provides a holistic explanation of what hacking is, and what it looks like.

* [Penetration Testing: A Hands-on Introduction to Hacking - Georgia Weidman(2014)](https://www.amazon.com/Penetration-Testing-Hands-Introduction-Hacking/dp/1593275641)

A very readable starting point, though outdated. The author is writing a second edition which will come out at some point.

* [Violent Python, T.J Connor(2012)](https://www.academia.edu/4903104/Violent_Python_-_A_Cookbook_for_Hackers_Forensic_Analysts_Penetration_Testers_and_Security_Engineers)

* [Black Hat Python: Python programming for hackers and pentesters, Justin Seitz(2014)](https://olinux.net/wp-content/uploads/2019/01/python.pdf)

* [Gray Hat Python: Python programming for hackers and reverse engineers, Justin Seitz(2009)](https://nostarch.com/ghpython.htm)

Keep in mind that Python has come a long way since this book was written. Code examples may not run on the latest copy of Python.

* [The Hacker Playbook 3: A Practical Guide to Penetration Testing](https://www.amazon.com/Hacker-Playbook-Practical-Penetration-Testing-ebook/dp/B07CSPFYZ2)

* [Social Engineering: The Art of Human Hacking](https://www.amazon.com/Social-Engineering-Art-Human-Hacking/dp/0470639539)

## Links

[Reverse Engineering course using Ghidra](https://hackaday.io/project/172292-introduction-to-reverse-engineering-with-ghidra)

## Tools

* [Kali Linux](https://www.kali.org/) - This is a [Linux distro](https://en.wikipedia.org/wiki/Linux_distribution) designed specifically for penetration testing, It comes preloaded with all the tools a professional needs. Note: Kali Linux is not intended to replace your daily OS. It's meant to be run as a [virtual machine](https://www.howtogeek.com/196060/beginner-geek-how-to-create-and-use-virtual-machines/), usually.

* [Metasploit](https://www.metasploit.com/) - This is basically a compilation of exploit code for known vulnerabilities. It can do many, many other things too, but it's primary use is for pentesters quickly check if a system is vulnerable.

* [Wireshark](https://www.wireshark.org/) - This is a network traffic analyzer and packet sniffer. Widely used across the world to analyze communications between computers.

* [Nmap](https://nmap.org/) - stands for 'network mapper'. It's an extremely versatile information gathering tool whose uses are too many to list.

* [Ghidra](https://ghidra-sre.org/) - An NSA-developed decompiler. Allows you to essentially take programs apart to look at their source code. Indispensable for reverse engineering.

Ghidra is [open source,](https://opensource.com/resources/what-open-source) so you can rest easy knowing you aren't downloading spyware. Well, probably. You did audit the source code, right?

## Terminology

* Penetration testing - Legal hacking, essentially. Pentesters are hired to attempt to hack into corporate networks to assess their security.

* Black hat - Criminal hacker. When you hear about companies being attacked with ransomware or credit card credentials being sold on the dark net, it's this guy.

* White hat - Ethical hacker. This is your run of the mill pentester, security specialist, blue teamer, and all-around law-abiding citizen. This is what you want to be, right?

* Gray hat - Not quite a bad guy, but not a paragon of justice either. What separates a gray hat hacker from a white is his willingness to break laws, but what separates him from a black hat is that he has no malicious intent. He might just use vulnerabilities for pranks, or for learning, or for bragging rights, or whatever else.

### Contribute

If you would like to add to or revise this document, submit a pull request! If you don't know how to do that, here is a [tutorial](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners) on using git.

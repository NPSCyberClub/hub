# What are CTFs? 

Capture the Flag events are a gamified way of putting your technical skills to the test by solving puzzles with the result of discovering the "flag" which serves as proof of completion of the given task. A common convention is for flags to adhere to a format similar to "ctf{UNIQUE_FLAG_VALUE}", but the flag may also be the answer to a question.

CTFs can take a few forms. 
Some are jeopardy-style, knowledge-based and others are more open-world, hands-on movement through a series of steps. 
Common topics covered are cryptography, forensics, web applications/pwn, Open Source Intelligence (OSINT), binary reverse engineering, Artificial Intelligence (AI) / Large Language Models (LLMs), Red Teaming, IoT, etc. 
They will often consist of challenges ranging from easy/beginner-friendly tasks to advanced/more involved adventures. There should be something for everybody. 
Many CTFs will allow teams to compete, so folks can share their abilities and tackle more than a single individual could.

A very simple example would be the following:

> }galf_a_fo_elpmaxe_n@_si_s1ht{ftc

...where to get the flag, we [reverse the string](https://cyberchef.io/#recipe=Reverse('Character')&input=fWdhbGZfYV9mb19lbHBtYXhlX25AX3NpX3MxaHR7ZnRj), resulting in:

> ctf{th1s_is_@n_example_of_a_flag}

# Common / Base Knowledge

Going from zero to one can often be the most difficult. After you've got a little momentum, you can more easily level yourself up.
Here, we will provide some pointers regarding the most basic assumptions and required knowledge to help get you started.

While the ultimate flag will often take the form of "ctf{SOME_VALUE}", the flag will sometimes be disguised using various other representations of data. 
The flag may be encrypted or encoded using a number of different methods. Learning to recognize the common data formats can help you determine how to decrypt or decode the obfuscated flag.

You should read up on the following [encodings](https://www.youtube.com/watch?v=8ue8febDDKU): 
- [base64](https://www.youtube.com/watch?v=cq83Czbo82A)
- hexadecimal
- [binary](https://www.youtube.com/watch?v=LpuPe81bc2w)
- [ASCII, Unicode, & UTF-8](https://www.youtube.com/watch?v=DntKZ9xJ1sM)
- url encoding

Encryption algo: 
- DES
- AES
- RSA
- XOR

Hashing algos:
- MD5
- SHA1, SHA2, SHA3
- bcrypt
- NTLM

## Common Protocols

There are hundreds of ways of moving data around in cyberspace; however, we will mention some of the most common ones here.
You should learn the basics of what each does and how it works under the hood. These are the basic ways of moving in cyberspace, so you should be familiar with them to be effective.

- [HTTP](https://www.youtube.com/watch?v=TvRyJmPjcbw)
- SSH
- DNS
- RDP
- VNC
- FTP
- SMB

# Mindset / Approach

We all start somewhere. It is up to you to find the next best step to solve the challenge. No one person has all the answers, so it is 100% fair game to use any and all available resources and creativity toward solving the challenge (within the scope / Rules of Engagement / rules for the CTF).
Use AI. Use your favorite search engine. Use your previous experience. Use your team. 

After spending some time working on a challenge without solving it, consider stepping away from your computer to get some fresh air and free your brain. You'll be shocked at how many times clearing your mind will help things click back into place.

[LiveOverflow's Thoughts](https://www.youtube.com/watch?v=Lus7aNf2xDg)

## Tools

Do spend time to learn your tools. Do explore better alternatives to the tools you currently know and use, but do try and avoid "tool-hopping" at the expense of getting good at a specific tool.
It can be tempting to spend more time chasing the new, shiny tool. Some of this is healthy, but it has diminishing returns with time. 

## Notes / Your Second Brain

Do consider spending a reasonable amount of time designing your "second brain." There are many approaches, and again...it can be tempting to get caught up in the process rather than settling on a solution that is good enough. This is a means to an end.

# 06. HOW DOES THE WEB WORK?

## Introduction

Before you can understand how to program the web, you need a more rigorous understanding
of the web itself than you likely have now. These concepts provide a more holistic
understanding of the ecosystem in which you will be working and will enable you to talk
intelligently with other developers about your work.

## Lesson overview

- Describe what the internet is
- Describe what packets are and how they are used to transfer data
- Understand the differences between a web page, web server, web browser and search engine
- Briefly explain what a client is
- Briefly explain what a server is
- Explain what IP addresses are
- Explain what DNS servers are

# ASSIGNMENT

1. Watch this BBC short for an overview of how the internet works.

https://www.youtube.com/watch?v=eHp1l73ztB8 [ X ]

2. Read this Mozilla article on “How does the internet work?”.

https://developer.mozilla.org/en-US/Learn/Common_questions/How_does_the_Internet_work [ X ]

3. Watch How the Internet Works in 5 Minutes.

https://youtu.be/7_LPdttKXPc?t=46s [ X ]

4. Read up on the differences between a web page, a web server, and a search engine.

https://developer.mozilla.org/en-US/Learn/Common_questions/Pages_sites_servers_and_search_engines [ X ]

5. Watch this Google short explaining what a web browser is. Then, use this site to find out your current web browser and version.

https://youtu.be/BrXPcaRlBqo [ X ]

https://www.whatsmybrowser.org/ [ X ]

6. Read about how different parts of the web interact with each other and read this MDN article about how a DNS request works. Alternatively, here is a video about how a DNS request works.

https://developer.mozilla.org/en-US/Learn/Getting_started_with_the_web/How_the_Web_works#clients_and_servers [ X ]

https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/What_is_a_domain_name#how_does_a_dns_request_work [ X ]

https://www.youtube.com/watch?v=72snZctFFtA&t=45s [ X ]

## KNOWLEDGE CHECK

- What is a web server?

A computer connected to the internet that stores (and serves) web pages and services.

- What is a network?

A group of two or more computer machines connected together so that they are able to
communicate.

- What is the internet?

A network of networks that spans across the globe.

- What is an IP address?

A unique address that identifies a device on a network e.g. 192.0.2.172

- What is a router?

A special type of computer that forwards/receives messages between networks.

- What is an ISP?

A company that manages some special routers that are all linked together, and can also
access other ISPs' routers.

- What are packets and how are they used to transfer data?

Packets are fractional chunks of data from a web server being sent to a client, that are
broken up and addressed from sender to recipient. They are assembled at the recipient's
end to form the data that the recipient requested. A check occurs at the recipient's end
to see if any packets are missing (have "dropped out"), and if so, a request is sent again
for those missing packets.

- What is a client?

A computer that is used to request resources from a web server e.g. a user on their PC

- What is a server?

A computer intended to serve content or information to a client computer, via a network 
(e.g. a web server sends data for a web page to a user's web browser)

- What is a web page?

A document accessible via the web that you can view in a web browser

- What is a web browser?

An application on your computer specially designed to view web pages.

- What is a search engine?

A website that allows you to search for web pages on the internet based on certain 
criteria.

- What is a DNS request?

A DNS request resolves the human-readable domain address (www.etc.com) to a real web IP 
address, which is what's needed to access a resource across the web. Your browser/router
contacts a DNS server to initiate a lookup for the address; a DNS request.

- Which browser are you currently using?

Firefox 148

- In your own words, describe the process that takes place when you initiate a search on google.com in terms of what we discussed.

1. User enters search term
2. Google checks through it's listings, for pages with relevant metadata, ranked on
relevancy and number of hits/popularity
3. Google creates a weighting against its listings for pages that are deemed most relevant
for the search query
4. This is returned to the user

## COMPLETE
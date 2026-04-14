Throughout your journey in cybersecurity, you will often come across a magnitude of different applications and services. For example, a CMS whilst they all have the same purpose, often have very different designs and behaviours (and, in turn, potentially different vulnerabilities).

Thankfully for us, there are resources on the internet that keep track of vulnerabilities for all sorts of software, operating systems and more! This room will showcase two databases that we can use to look up existing vulnerabilities for applications discovered in our infosec journey, specifically the following websites:

1. NVD (National Vulnerability Database)(opens in new tab)

2. Exploit-DB(opens in new tab)

Before we dive into these two resources, let's ensure that our understanding of some fundamental key terms is on the same page:

<img width="1564" height="391" alt="image" src="https://github.com/user-attachments/assets/89e199d8-eb1e-4dcd-9dd4-ca963b221bd7" />

## NVD – National Vulnerability Database

The National Vulnerability Database is a website that lists all publically categorised vulnerabilities. In cybersecurity, vulnerabilities are classified under “Common Vulnerabilities and Exposures” (Or CVE for short).

These CVEs have the formatting of CVE-YEAR-IDNUMBER. For example, the vulnerability that the famous malware WannaCry used was CVE-2017-0144.

NVD allows you to see all the CVEs that have been confirmed, using filters by category and month of submission. For example, it is three days into August; there have already been 223 new CVEs submitted to this database.

<img width="1685" height="821" alt="image" src="https://github.com/user-attachments/assets/fb7beb3e-7eed-4e34-8305-b38434daa659" />

While this website helps keep track of new vulnerabilities, it is not great when searching for vulnerabilities for a specific application or scenario.

## Exploit-DB

Exploit-DB(opens in new tab) is a resource that we, as hackers, will find much more helpful during an assessment. Exploit-DB retains exploits for software and applications stored under the name, author and version of the software or application.

We can use Exploit-DB to look for snippets of code (known as Proof of Concepts) that are used to exploit a specific vulnerability.

<img width="1780" height="884" alt="image" src="https://github.com/user-attachments/assets/7db6a20d-d974-4a27-b73e-3ad18fb059c1" />

## Answer the question below
1. Using NVD (opens in new tab), how many CVEs were published in July 2021?
  - 1554
2. Who is the author of Exploit-DB (opens in new tab)?
  - OffSec


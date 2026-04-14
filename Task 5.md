In this task, I’m going to demonstrate the process of finding one minor vulnerability, coupled with some research of the vulnerability databases leading to a much more valuable vulnerability and exploit ultimately.

Throughout an assessment, you will often combine multiple vulnerabilities to get results. For example, in this task, we will leverage the “Version Disclosure” vulnerability to find out the version of an application. With this version, we can then use Exploit-DB(opens in new tab) to search for any exploits that work with that specific version. 

Applications and software usually have a version number. This information is usually left with good intentions; for example, the author can support multiple versions of the software and the likes. Or sometimes, left unintentionally.

For example, in the screenshot below, we can see that the name and version number of this application is “Apache Tomcat 9.0.17”

<img width="1270" height="903" alt="image" src="https://github.com/user-attachments/assets/1f25fa02-d856-48a0-98a2-d0d5cd077596" />

With this information in hand, let’s use the search filter on Exploit-DB to look for any exploits that may apply to “Apache Tomcat 9.0.17”.

<img width="1758" height="691" alt="image" src="https://github.com/user-attachments/assets/b66ca373-8e3d-4a15-bcd7-4cd6d5424edf" />

Great! After searching Exploit-DB, there are a total of five exploits that may be useful to us for this specific version of the application. 

## Answer the question below

1. What type of vulnerability did we use to find the name and version of the application in this example?
 - Version Disclosure

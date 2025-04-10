---
YGcloudsec: Cyber Security Professional Home Page
---

[https://github.com/YGcloudsec](./another-page.html).

[https://www.linkedin.com/in/youngguerra/](./another-page.html).

Currently looking for work

# YGcloudsec Cyber Security Home

Hello everyone, thanks for coming to check out my page. This is where I will list my CyberSec projects and talk a little about my self and my journey.

I am a Cyber Security Professional currently looking to join a team working as a Cloud Security Engineer or a similar position . After working several years at one of the top crypto currency exchanges here in the States. I was a Security Analyst L2 working mostly on EDR, breaches and triaging. After working that position for a couple of years I decided to move more towards IAM and Cloud/Network Egineering. I find the problems to be more interesting and hours less grueling.

Some of the certifications I got to further re-enforce my background are: Comtpia Network + and Security +, SPLUNK CORE Certified User and AZ-900. More to come shortly

I have done some projects on AWS but definitely more familiar with Azure but I think all cloud computing platforms are all pretty similar.

My passions outside of work are gamin, golf and crypto. Looking into how Bitcoin works and podcasts/articles around the creation of Bitcoin is what lead me to be interested Cyber Security. Trying to understand how Bitcoin is secured lead to me look into what SHA 256 is and so I went down the rabbit hole.

## Inspirations

<p>
  <a href="https://nakamotoinstitute.org/library/cypherpunk-manifesto/"><i>A Cypherpunk's Manifesto</i></a>
</p>
<em> "Privacy is necessary for an open society in the electronic age. Privacy is not secrecy. A private matter is something one doesn’t want the whole world to know, but a secret matter is something one doesn’t want anybody to know. Privacy is the power to selectively reveal oneself to the world." </em>

 -Eric Hughes, March 9, 1993


***

<h1> ePortfolio Projects and Demos</h1>

<h4>#1 Spinning up VMs and Pen Testing </h4>

[https://github.com/YGcloudsec/Pen-testing-lab](./another-page.html).

This project demonstrates a basic pen-testing lab setup using VMware Workstation Pro, where a Kali Linux VM is used to brute-force an Ubuntu VM over a Host-Only network. The lab includes network configuration, SSH installation, brute-force attacks with Hydra, and basic security hardening with Fail2Ban.

Lab Setup

<ul>
    <li>Host: Windows</li>
    <li>Hypervisor: VMware Workstation Pro</li>
    <li>Network: Host-Only (VMnet1, 192.168.100.0/24)</li>
    <li>VMs:
        <ul>
            <li>Kali Linux
                <ul>
                    <li>IP: 192.168.100.20</li>
                    <li>Tools: nmap, hydra</li>
                </ul>
            </li>
            <li>Ubuntu 20.04
                <ul>
                    <li>IP: 192.168.100.10</li>
                    <li>Services: SSH (port 22), Nginx (port 80)</li>
                    <li>User: lab</li>
                    <li>Security: Fail2Ban</li>
                </ul>
            </li>
        </ul>
    </li>
</ul>

***

<h4>#2 RBAC Demo</h4>
[https://github.com/YGcloudsec/rbac_demo](./another-page.html).

For this project I created a simple RBAC Web App System using free and open source software.
    
   <h5>Tools used:</h5>
  <ul>
        <li><strong>Python:</strong> For the backend logic.</li>
        <li><strong>Flask:</strong> A lightweight web framework.</li>
        <li><strong>SQLite:</strong> A simple database to store users and roles.</li>
        <li><strong>Flask-Login:</strong> To handle user sessions.</li>
        <li><strong>AI:</strong> Troubleshooting</li>
  </ul>

First, I created a Project Folder and named it rbac_demo. After installing the necessary tools listed above, I then set up a virtual environment in (venv) C:\Users\MyName\rbac_demo>. Usings Flask's login management system really streamlined the process for the set up. Then I set up the login process, created a simple database of example users, set routes for each user and finally created templates for each login page based on the user's assigned role. The user's permissions were assigned in the templates and when each user signed in, they were restricted based on their roles and permissions.

RBAC enhances security, streamlines administrative tasks, and promotes compliance. A vital part of least priveledge. zero trust architecture and healthy security practices.


<h4>#3 AWS IAM Policy Auditor</h4>
[https://github.com/YGcloudsec/aws-iam-auditor](./another-page.html).

Although I have been mainly focused on Azure, I wanted to play around with AWS as it is the leading cloud service provider. It is similary enough to Azure that I think transitioning from Azure to AWS will be relatively simple. I hope I dont have to eat my words later haha.

This project focuses on Cloud Security best practices and automating tasks via Python and AWS SDK (Boto3).

My favorite part of this project was getting introduced to hiding the AWS Secret Access Key. I have to deacvitave and create a new key becuase I had acidentally posted the Secret Key to Git Hub when pushing my original project. I had read of a recent breach due to Secret Keys being exposed and glad I made this mistake on this demo to keep in mind for future production changes.


1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![CloudSec]image.jpg


### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```

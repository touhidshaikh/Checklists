# VoIP Assesment Methodology

-   APPLICATION SCOPING

-   MAPPING AND SERVICE IDENTIFICATION

-   RECONNAISSANCE AND ENUMERATION

-   VULNERABILITY ANALYSIS

-   Exploitation

-   STRATEGIC MITIGATION

-   PATCH VERIFICATION

    **RECONNAISSANCE AND ENUMERATION**

We enumerate entire implementation, The devices connected to the VoIP network, their open ports, and running services users information (extension, the device information, and logs).

In this phase we aslo concentrate on finding extensions and usernames/passwords for users across the VoIP network. The main focus of this phase is to find your way(s) in. Utilizing who and how someone uses the VoIP is key when trying to get in.

And many more questions also below,

What types of phones are in use?

Who makes them?

Model of the devices?

Where is the SIP Server implemented?

What’s the software in use?

Are they using TCP or UDP for traffic?

Are they sending it through secure means?

What are their IPs and what other ports are open on these devices? etc.

These are all questions that need to be answered during the initial phase of the VoIP assesment and pentest.

**VULNERABILITY ANALYSIS**

In this phase we focus to identifiy the security vulnerability on the implentation on the VoIP according to our organization standard and know standards.

We look for different vulnerabilities listed below.

· Extension Enumeration & Number Harvesting

· Identification of insecure services

· Testing for Default Credentials

· SIP attacks

Rogue SIP B2BUA

SIP rogue as a proxy

SIP registration hijacking

Capturing SIP Authentication

· Application level vulnerabilities

· Denial of Service (DoS) attacks

Smurf flooding attack

TCP SYN flood attack

UDP flooding attack

· Registration Manipulation and Hijacking

· Authentication attacks

· Caller ID spoofing

· Man-in-the-middle attacks

· VLAN Hopping

· Passive and Active Eavesdropping

· Spamming over Internet Telephony (SPIT)

· VoIP phishing (Vishing)

· RTP injection

· Signaling Manipulation

· Voice Mail Attacks

· Phone Firmware Analysis

**EXPLOITATION**

This is the phase we exploitated the found flaws and try to get more information or impact using the flaws and also try to get a persistance access.

**STRATEGIC MITIGATION**

In these phase we recommended the mitigation from the found attack with proper explainatioin and support.

**STRATEGIC MITIGATION**

In these phase we retest the vulnerabilitie wheather they fixed of not and also try to bypass the current mitigation to reverify the mitigation is proper implemented.

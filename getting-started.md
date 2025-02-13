---
layout: page
title: onboarding
---

# Computational Oncology Group - Onboarding

## Purpose
This document is a collection of steps to perform when onboarding as a new member to the Computational Oncology group led by Naveed Ishaque. It collects information on general administrative topics (such as VPN) and also information on group specific resources (such as the OTP for data processing).

Please adjust outdated or inaccurate information and feel free to **add whatever you feel is useful**!

* TOC
{:toc}
 
## General IT
Most information on the topics in this part of the onboarding can be found by searching the Charité Intranet https://intranet.charite.de

### Program installation and admin rights

#### Charite Software IT Portal: Matrix42
Some standard software can be installed from the Charite Software IT Portal (`Matrix42`). You can find a link to it on your Desktop or in your taskbar. Note that this service is only accessible on-premise (it will not work when using VPN in HomeOffice). A tutorial of how to use this service can be found by clicking on the `Software selbst installieren` shortcut on your Charite laptop desktop (or go [directly to the guide](https://intranet.charite.de/fileadmin/user_upload/portal/service/service_06_geschaeftsbereiche/service_06_14_it/a-software-selbst-installieren.pdf)), and follow the guide. Some important tools on Matrix42:
 - Office tools: Acrobat reader, PDF24, PDFForge
 - Referencing: EndNote, Mendeley 
 - Graphics software: Gimp (bitmap graphics/Photoshop alternative), Inkscape (vector graphics/Illustrator alternative), IrfanView
 - Statistical modelling: Octave,  Matlab, SPSS, Python, R, 
 - Productivity tools: Slack, FreeMind, 
 - VPN/SSH: OpenVPN, putty
 - Media: VLC

#### Install Slack
Download via https://slack.com/intl/en-gb/downloads/windows 

### VPN
To be able to work from home you will need to apply for VPN access. You can find all necessary information under the following link. 
* https://intranet.charite.de/it/it_serviceueberblick/vpn/vpn_antrag

This grants you access to general Charité systems as well as the Internet-proxy so you can access journals and articles.
However to access the cluster, the BIH GitLab, and other ressources you will also need to fill out the form “VPN Zusatzantrag B” on the above mentioned link and have it signed by Sandra Bodogh (she can sign it as proxy for Prof. Eils as required by the form).

### Helpdesk
For technical issues with the computer reach out to the helpdesk via *helpdesk@charite.de* or (99) 575 444
* https://intranet.charite.de/it/helpdesk/stoerungen_informationen

### PKI
The Charité provides a Public Key Infrastructure (PKI) that allows you to get a private certificate that you can use to sign PDFs or emails (or also encrypt emails). You can find all information on what it is, how it works and how to get one and use it here:
* https://intranet.charite.de/it/it_serviceueberblick/charite_pki_benutzer_und_server_zertifikate/pki_anleitungen 

## Getting ready to work

#### Install VScode
Open https://code.visualstudio.com/, and download by clicking `Windows x64 **User Installer** Stable`.

#### Setup a suitable linux environment
* For windows machines, setup WSL
* For windows machines, install putty and WinSCP

#### Setup a suitable linux environment
* Setup conda

### DHC Cluster Connection
The Cluster of the BIH is only accessible once you registered for VPN access with the extension form “VPN Zusatzantrag B”. You will also need to be added to the corresponding access groups to be able to login to the cluster. *Talk to Naveed Ishaque or Stefan Schneider*.

Further information regarding the cluster can be found at https://git.bihealth.org/biomedical-datascience/organisational/-/wikis/eils-hpc (you already need access to GitLab to access this and might need to be added to the GitLab project by Naveed Ishaque).

### Charite SC cluster
The Charité HPC cluster is only accessible once you registered for VPN access with the extension form “VPN Zusatzantrag B”. You will also need to be added to the corresponding access groups to be able to login to the cluster. *Talk to Naveed Ishaque or Stefan Schneider*.

Further information regarding the cluster can be found at：
[1] **User Guide**: https://git.bihealth.org/charite-sc-public/sc-wiki/-/wikis/Resources/User%20Documentation/User%20Guide:%20HPC%20@Charite#access
[2] **HOWTOs**: https://git.bihealth.org/charite-sc-public/sc-wiki/-/wikis/Resources/HOWTOs

## Group Resources

### Slack
The Slack is available under https://digitalhealth-berlin.slack.com. Have Naveed Ishaque invite you.

### GitLab (+ GitHub)
The GitLab of the BIH is only accessible once you registered for VPN access with the extension form “VPN Zusatzantrag B”.
* https://git.bihealth.org

The GitLab uses the Standard credentials. However, upon first login your account will be locked and you will need to send an email to *health-data@charite.de* (but all information/links are also detailed on the Webpage).

Our group documentation is stored under https://git.bihealth.org/biomedical-datascience. In the Organisational subgroup you will find some instructions on cluster suage but also information on LabMeetings etc.

Also ask Naveed to add you to the GitHub of the HiDiH at https://github.com/orgs/HiDiHlabs where you can also find this document.

### OTP
OTP, the acronym for One Touch Pipeline, is used for managing and processing the NGS data. To get familiar with it have a look at the following links
* https://github.com/naveedishaque/pedion-bioinformatics-workshop/blob/main/what-is-OTP.md
* https://www.sciencedirect.com/science/article/pii/S0168165617315924
* https://otp-dh.bihealth.org/ (requires "VPN Zusatzantrag B"?)


## Other

### Web presence

#### ORCiD
If you do not have one already generate an ORCID iD that can be used to identify you when publishing papers, etc.
* https://info.orcid.org

### GitHub
We make alot of code available online, so a GitHub account is very important:
* http://www.github.com/

#### Webpage
Talk to Franziska Mueller to get added to the department’s web page (best including a photo).
* https://www.hidih.org/research/computational-oncology
* https://www.bihealth.org/de/forschung/schwerpunkte/digitale-gesundheit/forschungsgruppen/computational-oncology

#### BlueSky https://bsky.app/
If you have BluSky feel free to follow:
* @naveed-ishaque.bsky.social
* @bihatcharite.bsky.social
* @denbi.bsky.social

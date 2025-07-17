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
Download via https://slack.com/intl/en-gb/downloads/windows. Join with your personal email https://digitalhealth-berlin.slack.com/ as a guest with access to #ag-ishaque. When you  you have a charite email then you can join as a full member. 

### VPN
To be able to work from home you will need to apply for VPN access. You can find all necessary information under the following link. First fill the VPN_O form which grants you access to general Charité systems as well as the Internet-proxy so you can access journals and articles. 
 - https://intranet.charite.de/it/it_serviceueberblick/vpn/vpn_antrag
   - For normal VPN you need to fill the VPN-O form. You need to do this
     - Download the VPN-O form
     - Fill in personal details on the top right (academic title, surname, first name, charite email, BIH-MHDS, Researcher)
     - Tick "Office VDI"
     - Tick "Dienst" and to add access to `https://otp-dh.bihealth.org/` in Dienst(e) (UDP/TCP) and `charite-hpc-user-access` in Zeilsystem
     - Tick the agreement "Ich versichere, dass durch die ..."
     - Date and sign
     - Fill "Laufzeit" as 3 years
   - To access the DHC cluster, the BIH GitLab, and other ressources you will also need to fill out the form “VPN Zusatzantrag B” have it signed by Alexandra FRiedrich (she can sign it as proxy for Prof. Eils as required by the form).
     - Download the VPN-B form
     - Fill in personal details on the top right (academic title, surname, first name, charite email, BIH-MHDS, Researcher)
     - Tick CUBI, BIH, Eils
     - Tick accept at the bottom and sign

### Charite C-mobil
... someone to update

### Helpdesk
 - Charite helpdesk
    - For technical issues with the computer reach out to the helpdesk via *helpdesk@charite.de* or (99) 575 444; https://intranet.charite.de/it/helpdesk/stoerungen_informationen
 - DHC helpdesk
    - For DH cluster technical issues, contact dh-helpdesk@bih-charite.de for a ticket.... (or Slack Foo Wei Ten)
 - SC cluster helpdesk
    - Georgios Nikolis <georgios.nikolis@charite.de>
   

### Digital signage and PKI
The Charité provides a Public Key Infrastructure (PKI) that allows you to get a private certificate that you can use to sign PDFs or emails (or also encrypt emails). You can find all information on what it is, how it works and how to get one and use it here:
* https://intranet.charite.de/it/it_serviceueberblick/charite_pki_benutzer_und_server_zertifikate/pki_anleitungen 

## Getting ready to work

#### Install software environments
 - VSCode Open https://code.visualstudio.com/, and download by clicking `Windows x64 **User Installer** Stable`.
 - R-studio/POSIT
 - For DHC cluster you need to install JupyterLab (instructions on our department GitLab)

#### Setup a suitable linux environment
- For windows machines, setup WSL... but "PowerShelll is a good thing" (J.J.  30/04/25)
- For windows machines you need to connect to a cluster somehow
   - `ssh` via CMD
   - install putty
   - for moving files you can use `scp` or WinSCP

#### Setup a suitable linux environment via conda
- install miniconda and then install mamba... or micromamba
- remove default channels
- move conda-forge before bioconda

### DHC Cluster Connection
The department cluster (the DHC cluster) is only accessible once you registered for VPN access with the extension form “VPN Zusatzantrag B”. You will also need to be added to the corresponding access groups to be able to login to the cluster. *Talk to Naveed Ishaque or Stefan Schneider*.

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
If you have BlueSky feel free to follow:
* @naveed-ishaque.bsky.social
* @bihatcharite.bsky.social
* @denbi.bsky.social

# Diamond Model

The Diamond Model (the Diamond Model of Intrusion Analysis) is an intelligence tool used as a framework to analyse cyber intrusions, mapping correlations between:

    Adversary: Who is responsible for the attack?
    Capability: What steps did they take to perform the attack?
    Infrastructure: What physical & logical services were used?
    Victim: Who was targeted and why were they targeted?

When used efficiently by the defenders, it can help with answering several perspectives regarding the attack and its context. The context can be categorised into subchapters to keep a clear objective:

## Adversary

Whomever is attacking gets defined in this subchapter. Whether this is a nation-state, cybercriminal, disgruntled employee or script kiddie. There's a distinction between the following:

    Adversary operator: Entity/person who performs the attack
    Adversary customer: Entity/person that reaps the fruit of the performed attack

Adversaries can assume either of these roles or both. Usually high-profile cyberattacks involve multiple teams, like:

    Initial Access
    Development of Malware
    Exfiltrating Data

The scene has the following structure:

    Initial access broker: Provides services
    Ransomware gang: Licenses ransomware software
    Affiliate: Performs the attack

One or all of these positions may be taken up by an adversary. Several operations teams are usually involved in high-profile cyberattacks: one for initial access, another for malware development, and a third for data exfiltration. The ransomware scene has evolved a structure in which an associate actually carries out the attack, a ransomware gang licenses their software, and an initial access broker offers a service.

The organization of who is really carrying out the attack and the number of operations teams can soon get complex. The distinction between official activities and government-sanctioned operations may grow hazy when nation-states use proxy groups and ransomware gangs employ associates. Therefore, tracking the Adversary customer—who stands to gain the most from an attack—rather than the particular person or virus utilized is typically more fruitful.

Using incursion data in this way isn't always the simplest.

Instead of naming a state or gang right away, start by tracking the online presence used, accounts observed (social media, email, etc.), and the aim of an attack. This will allow you to more precisely link the attacks to an entity or campaign based on available data by correlating these Adversary data points with other campaigns.

## Infrastructure

An adversary will use infrastructure to deploy their capabilities. An attacker can utilize any of these things to demonstrate their abilities. It can be logical, like an email address or service account, or physical, like a command-and-control (C2) server.

The victim may connect to a third-party file-sharing site where data is exfiltrated, such as file.io or Pastebin, or the attacker may use this infrastructure directly, such as a C2 server they connect to when conducting their attacks.

The process that executes a malicious DLL or the name badge that an attacker copied in order to enter the target building might both be considered infrastructure. Infrastructure is more than simply domains and IP addresses.

The following are some typical infrastructure types that you will frequently encounter:

    Service accounts
    Email addresses
    IP addresses
    Domains
    C2 servers
    Personas (social media handles, phone numbers, Telegram channels, etc.)
    Cloud services
    File-sharing websites
    Tor nodes
    Compromised websites

## Capability

The tactics, methods, and procedures (TTPs) that the adversary employs to carry out the attack are referred to as capability. This falls into the following categories:

Tools: Malware, exploits, and hacking tools used in an attack. Tradecraft: The hacking methods employed by the adversary, such as taking advantage of commands or living-off-the-land binaries and scripts (LOLBAS). These are well covered by the MITRE ATT&CK matrix.

When mapping Capabilities to the Diamond Model, prioritize specifics. When it comes to tracking, general tools or tradecraft are ineffective. Concentrate on data points that stand out, which are typically represented by decisions made by an adversary, such as specialized malware configuration settings, custom malware, and novel attack methodologies or command-line options.

These could be considered crucial signs. Indicators that stay consistent throughout intrusions identify an attack campaign and correspond to a stage of the Cyber Kill Chain. They are indications that can be used to monitor attack campaigns or threat actors, differentiate incursions, and locate them in your environment.

These could be considered crucial signs. Indicators that stay consistent throughout intrusions identify an attack campaign and correspond to a stage of the Cyber Kill Chain. They are indications that can be used to monitor attack campaigns or threat actors, differentiate incursions, and locate them in your environment.

## Victim

The victim is the target of the attack, or "Capabilities disseminated across Infrastructure by the Adversary." The victim can be an individual or an organization whose assets have been impacted by the assault (computer systems, networks, data, etc.). Victims are rarely directly related to the attacker; instead, they are linked via infrastructure or capability.

A victim is simply a means to an end for the Adversary. A threat actor's purpose is to jeopardize the confidentiality, integrity, or availability of the data or services that a victim controls. They are unconcerned about the victim; all they worry about are the things that the victim possesses and the benefits they might derive from abusing them.

It is also necessary to ascertain who the true victim of an incident is. An attacker may use a software provider to launch a supply chain assault on their intended target. The actual victim of the incident will have different implications for your analysis.

An analyst can apply the Diamond Model from various perspectives:

They could adopt the Victim's perspective and look for infrastructure or capability that connects an attacker. They could be an infrastructure supplier looking for attackers targeting victims who use their services. They could even adopt the attacker's perspective and employ Capability and Infrastructure to locate a Victim.

This pivoting aspect of the approach, in which you begin with one component and progress to another, is what makes it so beneficial for threat intelligence analysts. As an analyst, you can utilize the model to identify questions that will produce leads, insights, and actionable intelligence.

To understand how these four components interact and how to apply the model successfully, you must first grasp the axioms that underpin the Diamond Model. These agreed assumptions are required to use the model effectively.

# Sources:

## Websites

https://kravensecurity.com/diamond-model-analysis/

https://www.activeresponse.org/diamond-model-axioms/


## claude.ai

Prompted on 18/03/2026 around 17:45: 


I would like to see similair framework for Cybersecurity like: the Diamond Model and the Cyber Kill Chain.

Make sure the source is correct and make no mistakes.

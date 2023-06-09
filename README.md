# *Full Contact Zero Trust*

## *Secure - Extensible - Reliable - Scalable - Repeatable*
### KravZT Tenants
    1. Be aggressive but smart in your problem solving.
    2. Be vigilant in identifying and addressing challenges.
    3. Be proactive based on your current weaknesses or vulnerabilities; react quickly when you have to.
    4. Be tool agnostic.
    5. Invoke precision when executing tasks.
    6. Employ simple and repeatable techniques.
    7. Include situational awareness in all aspects of your practice.
    8. Understand the impact of stress on your planning and response.
    
## Krav Zero Trust Approach

Krav means contact in Hebrew and Maga means combat. Together Krav Maga means Contact Combat. KravZT is an approach to Zero Trust that creates a *mindset* enforcing policies, such as the principle of least privilege; secure IT architecture design, microsegmentation; and technologies including multifactor authentication, user and entity behavior analytics, and endpoint monitoring.

KravZT applies the best principles and practices of athletic and martial arts practice to the field of [Zero Trust Architecture](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-207.pdf). Modern security and networking activities are an effort in teamwork and KravZT practioners practice in KravZT Dojos - Similar to [DevOps Dojos](https://infraswarm.io/devops-dojos-safe-places-for-practice-and-mentorship) where they focus on the ten [teamwork](https://en.wikipedia.org/wiki/Teamwork) principles.

KravZT is primarily focused on safety and the real world, exactly like Krav Maga which is considered the most practical and efficient self defense system in the world.

What you learn by studying KravZT will carry over into other aspects of your life, including the strength, focus, and self-confidence you learn through the practice and eventual [mastery](https://blog.doist.com/mastery/) of Zero Trust Architectural systems analysis and design.

Studying KravZT isn’t just for career development. Many who study it do so for the mental skills, and community aspects as well.

The techniques and skills of Krav Maga don’t rely on a person’s strength or size. Because Krav Maga focuses on *quick movements*, anyone can train and learn the self-defense aspects of the art. Similarly, KravZT is focused entirely focused on a practioner's "developer experience". The KravZT approach is to examplify these *quick movements* and make a network or security engineer into a very powerful [Chief Zero Trust Officer](https://blog.cloudflare.com/chief-zero-trust-officer/). 


## Principles of Krav Zero Trust

**Employ Krav Maga’s** ***Retzev*** **- "Continuous Motion"**

Retzev is a concept that urges the Krav Maga practitioner to utilize and harness the natural power in movement throughout both **defensive** and **offensive** initiatives within a self-defense technique(s).

**Four Pillars of Krav Maga**

    1. Awareness
    2. Avoidance
    3. De-escalation and escape
    4. Last-resort decisive, simultaneous attack and defense

**THREATs**

    1. Technical Threats
    2. Health Threats
    3. Raids/Robbery Threats
    4. Environmental Threats
    5. Terrorism Threats

**Situational Awareness =** ***Mindfullness***
Situation awareness has been recognized as a critical, yet often elusive, foundation for successful decision-making across a broad range of situations, many of which involve the protection of human life and property, including law enforcement, aviation, air traffic control, ship navigation, health care, emergency response, military command and control operations, self defense, and offshore oil and nuclear power plant management. Lacking or inadequate situation awareness has been identified as one of the primary factors in accidents attributed to human error.

**The Five Levels of Situational Awareness:**

    - “Tuned Out” - Not paying attention.
    - “Relaxed Awareness” - Enjoying life while paying attention.
    - “Focused Awareness” - Carefully observing a perceived threat.
    - “High Alert” - Confirmed threat, must act.
    - “Comatose” - Not able to function.

## History of Krav Maga

Krav Maga is a military self-defence and fighting system developed for the Israel Defense Forces (IDF) and Israeli security forces derived from a combination of techniques sourced from Boxing, Wrestling, Judo, Aikido, and Karate. Krav Maga is known for its focus on **real-world situations** and its **extreme efficiency.** It was derived from the street-fighting experience of Hungarian-Israeli martial artist **Imi Lichtenfeld**, who made use of his training as a **boxer** and **wrestler**, while defending the Jewish quarter against fascist groups in Bratislava, Czechoslovakia, during the mid-to-late 1930s. In the late 1940s, after his aliyah to Mandatory Palestine, he began to provide lessons on combat training to what was to become the IDF.


> **Krav Maga has a philosophy emphasizing aggression, and simultaneous defensive and offensive maneuvers.**
>

Some of the key focus is instinctive response under stress. To that end, Krav Maga is an **eclectic** system that has not sought to replace existing effective techniques, taking what is useful from available systems, for example:


- **Strikes** - as per karate, and boxing
- **Take-downs and throws** - per judo, akido and wrestling
- **Ground work** - per judo and wrestling
- **Escapes from chokes and holds** - per judo, akido, wrestling
- **Empty-hand weapon defenses** - per akido


----------
## Zero Trust Components from the [Zero Trust Roadmap](https://zerotrustroadmap.org/)

**Users**

    1. Establish a corporate identity
    2. Enforce MFA for all applications

**Endpoints and Devices**

    1. Implement MDM/UEM to control corporate devices
    2. Implement endpoint protection
    3. Inventory all corporate devices, APIs and services

**Internet Traffic**

    1. Block DNS requests to known threats
    2. Block threats behind SSL/TLS

**Networks**

    1. Segment user network access
    2. Use Internet backbones for branch to branch connectivity
    3. Close all inbound ports open to the Internet for application delivery

**Applications**

    1. Monitor inbound emails and filter out phishing attempts
    2. Inventory all corporate applications
    3. Zero Trust policy enforcement for Applications
        1. Publicly addressable
        2. Privately addressable
        3. SaaS applications
        4. Non-browser apps (SSH, RDP, SMB, thick clients)
    4. Protect applications from Layer 7 attacks (DDoS, injection, bots, etc)
    5. Enforce HTTPS and DNSsec

**Data Loss Prevention and Logging**

    1. Establish a process to log and review traffic on sensitive applications
    2. Define what data is sensitive and where it exists
    3. Stop sensitive data from leaving your applications (e.g. PII, CCNs, SSNs, etc)
    4. Identify misconfigurations and publicly shared data in SaaS tools
    5. Establish a SOC for log review, policy updates and mitigation
    6. Stay up to date on known threat actors

**Steady State**

    1. Employ a DevOps approach to ensure policy enforcement for all new resources
    2. Implement auto-scaling for on-ramp resources

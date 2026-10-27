# Phishing Simulation & Security Awareness Training

A controlled phishing simulation built with **Zphisher** to demonstrate real-world credential-harvesting techniques, delivered as part of a hands-on security awareness training session for students at the college Centre of Excellence for Cybersecurity.

> ⚠️ **Disclaimer:** This project was conducted strictly for educational purposes under institutional authorization at the Centre of Excellence for Cybersecurity. It was performed in a controlled environment with informed, consenting participants. Phishing simulations must never be run against real users without explicit authorization — doing so is illegal.

## Objective

To help students understand how phishing attacks work from the attacker's perspective, so they can better recognize, avoid, and defend against them in real life.

## What This Covers

- Cloning a legitimate login page (Instagram) using Zphisher to create a convincing fake login portal
- Hosting the fake page and generating a shareable phishing link
- Capturing credentials submitted by consenting training participants
- Walking participants through what happened, how the attack worked, and the red flags they missed

## Tools Used

- **Zphisher** – automated phishing page generator
- Kali Linux / Linux terminal environment
- Localhost / tunnelling service for link hosting during the live demo

## Training Session Structure

1. **Live demo** – Simulated the phishing attack in real time, showing how quickly a convincing fake page can be built and deployed.
2. **Debrief** – Explained what data was captured and how, to make the risk tangible. Session was attended by 10 students and 2 faculty members.
3. **Awareness training** – Covered common phishing indicators (mismatched URLs, urgency cues, spoofed branding, suspicious sender domains) and prevention practices (checking URLs, enabling MFA, verifying requests through a second channel, reporting suspicious links).

## Learning Outcomes

This project was built to practice:

- Social engineering and phishing attack mechanics
- Security awareness training and communication
- Translating a technical attack into practical, actionable guidance for a non-technical audience

## Future Improvements

- Expand to cover additional phishing vectors (email-based phishing, QR code phishing)
- Add a post-training quiz to measure awareness improvement
- Build a simple phishing-detection checklist handout for participants

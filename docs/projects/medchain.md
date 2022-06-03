---
title: Medchain
---

{% info Source code %}
The project source code is available on [Github](https://github.com/Samrhan/MedChain)
{% end %}


## Reminder of the subject

A medical procedure is often associated with a prescription issued by a health professional. This prescription is traditionally written on a sheet of paper. In order to reduce this significant consumption of paper, the ideal would be to eliminate this physical support.

A solution to dematerialize medical prescriptions. The goal is to have the same level of confidence in this document (especially in relation to pharmacies and the regulations in force), an optimal level of security (to avoid, for example, a modification of the prescription which can be catastrophic), and an even smoother communication between health professionals, the CPAM, mutual insurance companies, etc. Would the miracle solution be, for example, the blockchain technology?

## Presentation of the solution

Medchain is a system that aims to replace paper prescriptions with a dematerialized version.
We propose an innovative and secure system for doctors, pharmacies, and the population.

Our system allows doctors to fill a digital prescription that will be anonymized and stored on our servers. His or her patient will then receive an email containing a code representing this prescription, which he or she can store in a mobile application. When the patient arrives at the pharmacy, he or she simply presents the code, which the pharmacist can scan to obtain the details of the prescription and dispense the medication.

## Technical stack

{% info %}
The project was conceptualized and developed in only 1 month
{% end %}
This project was done at the end of my 3th year in Efrei. We hadn't experienced devops approach with CI/CD pipeline yet, so the technical stack is pretty basic.

There's 3 applications, and a server. The two desktop applications are made with Angular, and then packaged with Electron. The mobile application is also made with angular, it's a PWA (progressive web app). The server is really simple, it's made with Express.js, without any framework, and without using an ORM for the database.

The choice to develop a PWA rather than a native application is debatable. However, we had no knowledge of mobile development, and we had very little time.

However the PWA offers some advantages, it is easily distributable, does not require manual updates, simple to install and easy to develop. I think it could be used a lot more. The problem is that it is not yet very popular, and is only supported by recent versions of mobile OS.
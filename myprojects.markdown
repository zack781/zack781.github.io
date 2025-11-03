---
layout: post
title: Projects
subtitle: Things I recently worked on
carousels-corelink-audio:
  - images:
    - image: ../assets/audio1.jpg
    - image: ../assets/audio2.png
    - image: ../assets/audio3.png
    - image: ../assets/audio4.png
    - image: ../assets/audio5.png
    - image: ../assets/audio6.jpg
permalink: /myprojects/
---

## 1. Real-Time Applications

**Project Name:** Real-time Audio Transport Plugin

**Link to Project:** [https://github.com/zack781/corelink-audio](https://github.com/zack781/corelink-audio)

{% include carousel_audio.html height="75" unit="%" duration="3" number="1" %}

Corelink Audio is a novel Networked Music Performance (NMP) solution designed to address the limitations of versatility and ease of use in existing NMP systems while maintaining high-fidelity audio and minimal latency.

At the heart of Corelink Audio is the Corelink network framework, a server-based system that manages routing for various network topologies, including pipelines, broadcasts, and multicasts. Corelink's relay architecture allows for high-level routing across the internet, making it possible to manage complex audio setups with ease. For instance, a band with multiple members can have independent channels dedicated to each musician, facilitating personalized audio mixes. Corelink's data agnostic and platform neutral characteristic allows for complex multi-modal topology between different data types like audio, video, and motion capture data. Corelink Audio is aimed to be an utility of the NYU High-Speed Research Network (HSRN), a high bandwidth low latency network infrastructure dedicated to academic purposes, supporting researchers with real-time audio applications.


{: style="clear:both;" :}

**Project Name:** Wireless Real-Time Subtitling Glasses

**Link to Project:** [https://github.com/zack781/speech_to_text_server](https://github.com/zack781/speech_to_text_server/tree/main/backend)

![code1](../assets/glass1.jpg){: style="width: 100%;" :}

{: style="clear:both; height:0px;" :}
![NYU IT HSRN](../assets/glass3.png){: style="width: 45%; margin: 1%;" :}
{: style="clear:both; height:0px;" :
{: style="margin: 0rem;" :}
Rapid Assembly and Design Challenge (RAD)

There are 2 components to this device the glass and the server. The glass has a monitor which is handled by the Arduino UNO over I2C and the audio is handled by the ESP32 which is connected to wireless internet to send requests to the server containing the audio data for speech to text conversion. The server is a Flask server that uses the SciPy Speech to Text API to convert the audio to text and send it back to the glass for display.

The goal of the project is to assist individuals with hearing difficulty by providing real-time subtitles for conversations. The device is designed to be lightweight and portable, making it easy to use in a variety of settings. The glasses are equipped with a small monitor that displays the text in real-time, allowing users to follow along with the conversation.
{: style="margin: 0rem;" :}

{: style="clear:both;" :}

## 2. Security

**Project Name:** Decentralized Discretionary Access Control Policy on Blockchain Network

**Link to Project:** [https://github.com/zack781/Network-Framework-with-Transparent-Access-Control](https://github.com/zack781/Network-Framework-with-Transparent-Access-Control)


![code1](../assets/kaistweb3_1.png)
![code1](../assets/kaistweb3_2.png)

The most well known apps in the world today with the largest users are built on gigantic backend systems that are inherently centralized. Since we have no way of knowing what is under the hood, we can not fully trust corporations to ensure that our data is not manipulated or tampered with in undesirable ways. One recent and popular breach of this trust is Facebook's Cambridge Analytica scandal where millions of users' personal data were leaked to individuals and organizations with no association to Facebook.

This Dapp aims to impose a transparency standard where the access control policy of the different backend architectures are open to the public. Any request from a client to the control server has to be validated by the access control policy implemented on a smart contract. Examples of these requests are “create_audio_sender,” “create_audio_receiver," “create_video_sender,” and  “create_video_receiver.” To set up or create any type of data stream to send or receive data, the users’ profile or identity needs to have the privilege to do so, this is similar to a discretionary access control model.

The access control policy is implemented in Solidity smart contract using the OpenZeppelin’s role based access control library. In addition, the control server, which was written in Rust for optimized performance, uses the Web3 crates to interact with the blockchain network and the smart contract functions. The React Dashboard also uses the Web3.js library to retrieve the public states through the use of Solidity events.

**3 main components were implemented:**
- Policy.sol
- React DASHBOARD
- Rust Control_Server

**Project Name:** Mini RSA

**Link to Project:** [https://github.com/zack781/Mini-RSA/tree/master](https://github.com/zack781/Mini-RSA/tree/master)

RSA, which stands for Rivest–Shamir–Adleman, is a widely used public-key cryptosystem that enables secure data transmission and digital signatures over insecure networks. The RSA algorithm involves the use of two keys: a public key and a private key. The public key is used for encryption and can be freely distributed, while the private key is kept secret and is used for decryption. The security of the RSA algorithm is based on the difficulty of factoring the product of two large prime numbers, which forms the basis of the RSA key pair.

**Programming Language Used:** Ocaml

**Project Name:** Mini AES

**Link to Project:** [https://github.com/zack781/Mini-AES/](https://github.com/zack781/Mini-AES/tree/master)

AES, which stands for Advanced Encryption Standard, is a symmetric encryption algorithm widely used to secure sensitive data. It was established as the standard encryption algorithm by the U.S. National Institute of Standards and Technology (NIST) in 2001. AES is a symmetric key algorithm, meaning the same key is used for both encryption and decryption.

**Programming Language Used:** Ocaml

## 3. Web Development

**Project Name:** Facebook Clone

**Link to Project:** [https://github.com/zack781/zack-fb-clone](https://github.com/zack781/zack-fb-clone)

![code1](../assets/fb-clone1.png){: style="width: 45%;" :}
![code1](../assets/fb-clone2.png){: style="float:left; width: 45%;" :}

{: style="clear:both;" :}

**Project Name:** Flight Booker

**Link to Project:** [https://github.com/zack781/odin-flight-booker](https://github.com/zack781/odin-flight-booker)

This project is more than just a flight booking platform; it's a part of my journey into the world of Ruby on Rails web development. Created as a hobby project, this web app reflects my commitment to exploration, experimentation, and the joy of acquiring new skills.

**Project Name:** Attendance Tracker

**Link to Project:** [https://github.com/zack781/attendance_tracker/](https://github.com/zack781/attendance_tracker/tree/master)

![code1](../assets/atracker1.png){: style="width: 47%;" :}
![code1](../assets/atracker2.png){: style="float:left; width: 47%;" :}

{: style="clear:both;" :}


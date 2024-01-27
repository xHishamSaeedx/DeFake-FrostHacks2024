This project is made at Frost Hacks 2024, a hackathon organized by MLH.
## Inspiration:

**Trustworthy Media:**
Building a deepfake detection project to safeguard trust in digital media, ensuring authenticity and reliability.

**Guard Against Misinformation:**
Our project stands as a guardian against the spread of misinformation and deceptive content, making a positive impact on digital integrity.

**Innovation for Positive Change:**
Using technology responsibly to innovate for good, contributing to the defense against malicious manipulation of digital content.

**Global Impact:**
Contributing to the global effort in cybersecurity by developing a deepfake detection system, addressing a worldwide concern.

**Responsible Tech Usage:**
Inspire future innovators to prioritize ethical development and application of AI, fostering a community that values responsible technology use.

## What it does:

Our project **Defake** aims to identify fake videos created by manipulating faces or content. It's crucial due to the rising use of deceptive content online, safeguarding against misinformation and preserving trust in visual media. The system uses smart technology to distinguish between real and manipulated videos, contributing to online authenticity.

## How we built it:

We trained multiple LSTM models with ResNext on Google Colab notebooks using PyTorch, incorporating datasets such as FaceForensics++, Celeb-DF, and the Deepfake Detection Challenge. Subsequently, we utilized Django to deploy the AI model locally, offering a user-friendly interface.
We used HTML, CSS & JS to build the UI of the application.
The primary language used here is Python with Django Framework.

## Challenges we ran into

1) Managing Large Datasets and Uploading Them on Colab
2) Proper Version Control for Python Libraries
3) Integration of Models Through Django

## Accomplishments that we're proud of

**The models we trained achieved +90% accuracy with a good looking UI**

## What we learned

We learned how to leverage power of AI and Web Development to solve a modern real life problem.
We also learned how to train & implement LSTM model with help of Python & Django.

## What's next for DeFake

In our further version we are planning to detect & identify deepfake audio too. We are also planning to introduce Subscription Plans & Consulting Services to make this  project profitable.

Check out the working video here : https://youtu.be/SW5c_4ZLbrE

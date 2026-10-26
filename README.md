# TechSpeeltuin – ToasterBox

## About the Project

**Burning Voices** is a DIY jukebox that I built myself as part of the TechSpeeltuin project.

The jukebox contains an LDR (Light-Dependent Resistor), a DFPlayer Mini, a speaker, and a white LED.

When you insert a disc into the jukebox, the white LED illuminates the disc, and the LDR detects its colour by measuring the reflected light. The detected value is then mapped to a specific colour. Each colour is linked to its own topic, with unique music and corresponding information displayed on the website.

The Arduino sends two pieces of information to the website:
- **Colour:** Identifies the selected topic.
- **Track number:** Indicates which track is currently being played.

The website uses this information to display content related to the selected topic, creating an interactive music experience.

## Features

- **Colour detection:** Uses an LDR to detect the colour of an inserted disc.
- **LED illumination:** Lights up the disc using a white LED.
- **Music playback:** Uses a DFPlayer Mini and speaker to play music associated with each topic.
- **Topic-based content:** Each colour corresponds to a different topic, with its own music and website content.
- **Website integration:** Receives colour and track information from the Arduino and displays the relevant content.

## Tech Stack

**Hardware**
- Arduino Uno
- DFPlayer Mini
- LDR (Light-Dependent Resistor)
- White LED
- Speaker

**Software**
- HTML
- CSS
- C/C++ (Arduino)

## What I Learned

This project was a valuable learning experience that helped me develop my technical skills through hands-on work. I gained experience working with electronic components, programming an Arduino, detecting colours using light measurements, and connecting hardware to a website.

## Demo

[Watch the Burning Voices project demo on YouTube](https://www.youtube.com/watch?v=W3MwVEPC1I8)

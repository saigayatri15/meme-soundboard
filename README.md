# Meme Soundboard Application

A responsive, highly interactive web application designed to look and feel like a physical hardware sound pad. Built using **HTML5**, **Bootstrap 5**, and a custom **Vanilla JavaScript** audio engine, this application allows users to play, layer, and manage 20 classic meme audio tracks seamlessly.

## Features

* **Layered Audio Engine:** Built using pure JavaScript, allowing multiple tracks to play simultaneously without cutting each other off.
* **Smart State Management:** Dynamically tracks active sounds using a runtime array (`activeAudios`), cleanly purging elements upon track completion to maintain zero memory leaks.
* **Master Panic Button:** Includes a global "Stop All" button that instantly halts all active audio playback and resets the tracks.
* **Interactive Control Deck:** Features a master volume slider that updates text percentage metrics in real-time.
* **Festive UI Structure:** Organized into distinct, structured regions (Control Deck vs. Sound Pads) utilizing Bootstrap grid utilities and a vibrant, high-contrast color scheme.
* **Optimized Audio Assets:** Configured to fetch completely balanced, normalized audio tracks for a consistent volume experience across all samples.


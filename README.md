<div align="center">
<h1>🎙️ Auto Podcast Mixer 🎛️</h1>

<p>
A lightning-fast, client-side web app to automatically mix podcast vocals with background music. Features smart audio ducking, fade in/out, waveform preview, and local MP3/WAV export. 100% private, runs entirely in your browser with zero server uploads!
</p>

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/18b56a57238e45289ab85bb1e3d7d54d)](https://app.codacy.com/gh/R0mb0/Auto_podcast_mixer/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
[![pages-build-deployment](https://github.com/R0mb0/Auto_podcast_mixer/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/R0mb0/Auto_podcast_mixer/actions/workflows/pages/pages-build-deployment)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/R0mb0/Auto_podcast_mixer)
[![Open Source Love svg3](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/R0mb0/Auto_podcast_mixer)
[![MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/license/mit)
[![Donate](https://img.shields.io/badge/PayPal-Donate%20to%20Author-blue.svg)](http://paypal.me/R0mb0)

<h2><a href="https://r0mb0.github.io/Auto_podcast_mixer/">👉 Click here to test the app! 👈</a></h2>

</div>

[![0001.png](https://github.com/R0mb0/Auto_podcast_mixer/blob/main/Readme_imgs/0001.png?raw=true)](https://r0mb0.github.io/Auto_podcast_mixer/)
[![0002.png](https://github.com/R0mb0/Auto_podcast_mixer/blob/main/Readme_imgs/0002.png?raw=true)](https://r0mb0.github.io/Auto_podcast_mixer/)
[![0003.png](https://github.com/R0mb0/Auto_podcast_mixer/blob/main/Readme_imgs/0003.png?raw=true)](https://r0mb0.github.io/Auto_podcast_mixer/)


<hr>

<h2>🚀 Features</h2>
<ul>
<li><strong>100% Privacy-First</strong>: Everything happens locally in your browser. Audio files are never uploaded to a server, ensuring your content remains completely private.</li>
<li><strong>Smart Audio Ducking</strong>: Automatically lowers the background music volume exactly when your voice track starts, and raises it back up when you finish speaking.</li>
<li><strong>Advanced Automations</strong>: Customize fade-ins, fade-outs, ducking anticipation time, and volume transition smoothness with millimeter precision.</li>
<li><strong>Interactive Waveform Player</strong>: Preview your generated mix instantly. Click on the visual audio wave to navigate through the track, or use the custom playback speed controls (0.5x to 2.0x).</li>
<li><strong>Multi-Format Export</strong>: Download your final masterpiece in high-quality <code>.mp3</code>, pristine <code>.wav</code>, or compatibility-friendly <code>.ogg</code> format.</li>
<li><strong>Drag & Drop Interface</strong>: Intuitive and smooth file management for both Voice and Background tracks. Includes a fully responsive, adaptive Dark/Light mode UI.</li>
</ul>

<h2>🛠️ How it works</h2>
<ol>
<li><strong>Drag and drop</strong> your podcast voice file and your background music into the dropzones.</li>
<li>Tweak your mixer settings (Fade durations, Ducking volume, Playback Speeds).</li>
<li>Click <strong>"Generate Mix"</strong>. The app uses the browser's native <code>OfflineAudioContext</code> to render the audio at maximum CPU speed, completely bypassing real-time playback.</li>
<li>It calculates the exact mathematical timings to center your voice track over the music, utilizing <code>GainNode</code> automations to sculpt the volume curves.</li>
<li>The app generates a temporary local <code>Blob</code> and renders an interactive waveform using <em>WaveSurfer.js</em>.</li>
<li>Listen to the preview and click download to instantly save the file via the built-in <em>LameJS</em> encoder!</li>
</ol>

<h2>🏆 What makes it special?</h2>
<ul>
<li><strong>Serverless Audio Processing</strong>: Performing complex audio mixing, ducking, and MP3 encoding entirely on the front-end is incredibly rare. It completely replaces the need for heavy backend tools like FFmpeg.</li>
<li><strong>Instant Offline Access</strong>: Once the local libraries are set up, you can literally save the folder on your desktop, disconnect your Wi-Fi, and use it offline forever.</li>
</ul>

<h2>💡 Why use this tool?</h2>
<ul>
<li><strong>Podcasters & YouTubers</strong>: Quickly add intro/outro music and background beds to your vocal tracks without having to open heavy DAWs (Digital Audio Workstations) like Audacity, Premiere, or Logic.</li>
<li><strong>Content Creators</strong>: Merge voiceovers with soundtracks in seconds with professional-sounding volume transitions, saving hours of manual keyframing.</li>
</ul>

<h2>⚡ Getting Started</h2>

<h3>Online</h3>
<p>Simply visit the <a href="https://r0mb0.github.io/Auto_podcast_mixer/">Live Demo hosted on GitHub Pages</a>.</p>

<h3>Local Installation (Fully Offline)</h3>
<p>Running this tool locally without internet is extremely easy:</p>
<ol>
<li><strong>Clone this repository</strong> or download the source code ZIP.</li>
<li>Ensure the <code>libs/</code> folder is present (it contains the local copies of Tailwind, WaveSurfer, LameJS, and FontAwesome).</li>
<li>Double-click <code>index.html</code> to open it in your favorite browser.</li>
<li>Start mixing!</li>
</ol>

<a href="https://github.com/R0mb0/Crafted_with_AI">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://github.com/R0mb0/Crafted_with_AI/blob/main/Badge/SVG/CraftedWithAIDark.svg">
<source media="(prefers-color-scheme: light)" srcset="https://github.com/R0mb0/Crafted_with_AI/blob/main/Badge/SVG/NotMadeByAILight.svg">
<img alt="Not made by AI" src="https://github.com/R0mb0/Crafted_with_AI/blob/main/Badge/SVG/NotMadeByAIDefault.svg">
</picture>
</a>

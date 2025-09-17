BharatAkshar - Street Sign Transliteration App
A modern, mobile-first web app designed to instantly transliterate street signs from various Indian scripts. This prototype simulates real-world OCR and provides high-quality voice playback for accessibility.
Live at :https://kankalanandu.github.io/BharatAkshar.github.io/
Features
Live Camera Transliteration: Access your device's camera to get a live feed and capture signs in real-time.

Image Upload: Transliterate signs from photos already on your device.

Multi-Script Support: Works with major Indian scripts including Hindi (Devanagari), Tamil, Telugu, Bengali, and Gujarati.

Device-Independent TTS: High-quality, cloud-based text-to-speech ensures consistent and accurate audio playback for all languages, on any device.

Interactive Sample Tester: Test the transliteration engine without using the camera by selecting from a pre-populated list of common signs in various scripts.

History: Automatically saves your last 10 transliterations for quick reference.

Modern UI/UX:

A minimal, aesthetic "glassmorphism" design.

An interactive, animated particle field background that reacts to your cursor.

Fully responsive for a seamless mobile experience.

Accessibility Options:

High-Contrast Mode: Switches to a solid, high-contrast theme for better readability.

Large-Text Mode: Increases font sizes across the app.

How to Use
Select Scripts: Choose the script you want to transliterate from ("Source Script") and the script you want to see ("Target Script"). "Auto Detect" is on by default for the source.

Capture or Upload:

Click "Capture Sign" to take a picture using your live camera feed.

Click "Upload" to select an image from your device.

View Results: The app will display the original text and the transliterated version.

Listen to Audio: Click the green "Play" button to hear the transliterated text spoken aloud.

New Scan: Click "Scan New Sign" to clear the results and return to the live camera feed.

Local Development
Save the index.html file to your computer.

Use a local server extension (like "Live Server" in VS Code) to run the file.

Important: The cloud-based audio playback will show a CORS error in the console and will not work on a local server. This is expected behavior due to browser security policies. The audio is guaranteed to work once deployed.

Deployment
This app is designed to be deployed to a static web host. For detailed instructions, please refer to the deployment_guide.md file.

Technologies Used
HTML5

Tailwind CSS

JavaScript (ES6+)

WebRTC (Camera Access)

HTML Canvas API (Image Capture & Particles)

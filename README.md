# BuildCored-Orcas-Day12
SnapAnnotator — BUILDCORED ORCAS Day 12

What it does. It turns the webcam into a smart eye. When you hit space, it "takes a photo," sends it to a local AI brain called Moondream, and lists out exactly what it sees. You can then press a number to "talk" to that object and get more details about it.

Hardware concept. It’s a Vision Pipeline. It’s the exact same flow used in self-driving cars or warehouse robots:
Sensor (Camera) → ISP (Cleaning the image) → Inference (The AI thinking) → Action (The text on your screen).

What I would do differently. I would add "Memory". Right now, the AI forgets everything the moment you ask a new question. You could change the code to keep a "chat history" so it remembers what you talked about before.

Run it. python day12_starter.py

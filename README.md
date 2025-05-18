# EchoSchedule: Your Voice-Powered AI Scheduler

EchoSchedule is a real-time voice assistant powered by the ElevenLabs Conversational AI API. It listens to your voice, understands your needs, and responds intelligently—with awareness of your daily schedule!

---

**🚀 Features**

1.🎙️ Voice interaction via microphone and speaker

2.🤖 LLM-powered natural conversations

3.📅 Context-aware scheduling support

4.⟳ Interrupt detection for responsive dialogue

5.🔐 Secure API credential handling via .env

---

**🛠️ Setup Instructions**

**1. Clone the Repo**

git clone https://github.com/your-username/echoschedule.git
cd echoschedule

**2. Install Python Dependencies**

Ensure Python is installed, then run:

pip install elevenlabs elevenlabs[pyaudio] python-dotenv

**3. Install OS-Level Audio Libraries**

Linux:

sudo apt install portaudio19-dev

MacOS:

brew install portaudio

**🔐 4 .Environment Configuration**

1.Create a .env file at the root of the project:

AGENT_ID=your_agent_id
API_KEY=sk_XXXXXX

Get these values from your ElevenLabs account under Conversational AI > Agents > API Keys.

**🎯5.Customize the Assistant**

In assistant.py, you can personalize the assistant’s greeting and prompt

**▶️6. Run the Assistant**

python assistant.py

**Make sure your microphone and speakers are properly configured in your system settings.**

---

**🧹 Extend EchoSchedule**

Here are a few ideas for expanding your assistant:

1.Integrate with Google Calendar or Outlook

2.Add smart home control (e.g., Home Assistant API)

3.Implement voice commands (e.g., “Open Gmail”)

---

**Built using:**

-ElevenLabs

-Python

-PyAudio

-dotenv




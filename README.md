<div align="center">

📜 Mythra: Smart Cultural Storyteller
Reviving Oral History for the Digital Generation ✨
</div>

👋 About The Project
Traditional cultural stories are disappearing. The wisdom of the past is often locked in text-based books, while today's digital-native children prefer immersive videos and interactive media.

Mythra bridges this gap. It is a Generative AI pipeline that adapts folklore and history into immersive, narrated, visual "comic-movies." By combining Large Language Models (LLMs), Image Generation, and Text-to-Speech (TTS), Mythra turns static text into a living, breathing storytelling experience.

🚀 Key Features
🎭 Multiple Story Modes
Folk Tale: Revives ancient legends with a complete narrative arc.

Historical: Narrates factual events through dramatic dialogue.

Oral History: Simulates an elder sharing personal memories.

Interactive Role-Play: Lets the user influence the story's direction in real-time.

✨ Core Capabilities
🗣️ Multilingual Support: Generates stories and audio in English, Hindi, and Tamil.

🎨 Dynamic Visuals: Uses FLUX.1 to generate vibrant, comic-book style illustrations for every scene on the fly.

🎙️ Character Voices: Distinct audio narration using Sarvam AI, bringing characters to life with Indic-context speech.

🎬 Auto-Play Theater: A custom Streamlit player that sequences images and audio automatically for a movie-like experience.

⚙️ Under the Hood
Mythra creates a chain of generative agents to build a story:

Story Engine (Llama-3 via Groq): Writes the script in a strict dialogue format based on the selected mode.

Visual Director (Llama-3): Analyzes the scene and writes a descriptive prompt for the image generator.

Illustrator (FLUX.1 via Hugging Face): Takes the visual prompt and renders a "graphic novel" style image.

Voice Actor (Sarvam AI): Converts the dialogue into speech, handling specific regional nuances.

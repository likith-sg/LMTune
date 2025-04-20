# 🎵 LMTune: Text-to-Music Generation using Meta's MusicGen

**LMTune** is a text-to-music generation project that uses Meta’s [MusicGen](https://github.com/facebookresearch/audiocraft) to produce high-quality audio from natural language prompts. It’s implemented as a Python notebook file and uses pretrained models to synthesize instrumental and vocal music in WAV format.

---

## 🌟 Highlights

- Generate **original music** from natural language
- Customize **duration**, **style**, and **instrumentation**
- Save outputs as `.wav` files
- Built with Meta’s **MusicGen** via the `audiocraft` library
- Includes inline playback in supported environments

---

## 📁 Project Structure

```
LMTune/
├── LMTune.ipynb          # Notebook with code (Python Notebook Format)
├── generated_music.wav   # Sample generated audio file
└── README.md             # Project description and usage
```

---

## 📦 Installation

To use this project:
- Follow the instructions in the notebook file.

---

## 🧠 Model Initialization

Choose the MusicGen model size based on your hardware:
- `"small"` *(default, fast and efficient)*
- `"medium"`
- `"large"` *(more detailed, requires more RAM)*

---

## 🛠 How to Use

Set your music prompt and generate the audio:

```python
prompt = "Kannada romantic melody with soft vocals and flute music"
generate_music(prompt, duration=30, output_file="generated_music.wav")
```

Play the generated music:

```python
play_audio("generated_music.wav")
```

---

## 🎼 Sample Prompts by Genre

Here are some example prompts you can try out with LMTune:

### 🎻 Classical
- "Baroque style instrumental with harpsichord and violins"
- "Romantic era piano solo with emotional dynamics"
- "Indian classical raga with veena and tabla"

### 🎷 Jazz
- "Smooth jazz with saxophone and double bass"
- "Upbeat bebop jazz trio"
- "Lo-fi jazz background for evening cafe"

### 🎧 Electronic / Pop
- "80s synthwave with retro drums and electric guitar"
- "Upbeat K-pop style song with danceable rhythm"
- "Lo-fi chillhop with ambient textures"

### 🎥 Cinematic / Ambient
- "Epic orchestral trailer music with heavy percussion"
- "Ambient space music with evolving pads and reverb"
- "Fantasy film score with strings and ethereal choir"

### 🎸 Rock / Indie
- "Indie rock with drums, bass, and electric guitar"
- "Melodic soft rock with slow tempo and echo"
- "Psychedelic rock instrumental"

### 🇮🇳 Indian Fusion
- "Kannada romantic melody with soft vocals and flute music"
- "Carnatic violin and mridangam duet"
- "Bollywood-style upbeat dance track"

---

## 🎧 Output

- Default format: `.wav`
- Sample rate: `32000 Hz` (MusicGen default)
- Output is saved locally after generation

---

## 📬 Feedback

Feel free to fork, star, or submit issues and pull requests. Happy generating!

# Deception Detection Using MU3D Dataset

This repository contains the code and resources for deception detection using the **MU3D (Miami University Deception Detection Database)**. The project explores facial expressions, textual cues, and voice features to predict deception using machine learning models.

**Dataset Link:** [Miami University Deception Detection Database (MU3D)](https://sc.lib.miamioh.edu/handle/2374.MIA/6067)

---

## Project Structure

```
├── Face_coords_Processing/
│   └── face_proc_main.ipynb       # Notebook for processing facial coordinates
├── Text_Processing/
│   ├── SVMC.ipynb                 # SVM-based classification for textual data
│   └── text_proc_main.ipynb       # Main notebook for text data processing
├── Voice_Processing/
│   ├── Video_to_Audio.ipynb       # Extracts audio from video files
│   └── voice_proc_main.ipynb      # Processes voice data for deception detection
├── FINAL ML Project Report.pdf    # Final report detailing methods, experiments, and results
```

---

## Features

### 1. **Face Processing**
   - Extracts and processes facial landmarks from video frames.
   - Analyzes facial microexpressions to identify deception cues.

### 2. **Text Processing**
   - Processes transcriptions of conversations or statements.
   - Uses support vector machine classifiers (SVMs) for deception detection based on textual patterns.

### 3. **Voice Processing**
   - Converts video files to audio.
   - Analyzes voice pitch, tone, and stress levels to determine deceptive speech.

---

## Getting Started

### Prerequisites
- Python 3.8+
- Required Libraries: `numpy`, `pandas`, `scikit-learn`, `librosa`, `opencv-python`, `matplotlib`

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/deception-detection.git
   cd deception-detection
   ```



2. Download the MU3D dataset from [here](https://sc.lib.miamioh.edu/handle/2374.MIA/6067) and organize it into the appropriate directories.

---

## How to Run

1. **Facial Data Processing**
   - Navigate to the `Face_coords_Processing` folder.
   - Open and run `face_proc_main.ipynb` to process facial data.

2. **Text Data Processing**
   - Navigate to the `Text_Processing` folder.
   - Open and run `text_proc_main.ipynb` or `SVMC.ipynb` to process text-based deception cues.

3. **Voice Data Processing**
   - Navigate to the `Voice_Processing` folder.
   - Run `Video_to_Audio.ipynb` to extract audio files from videos.
   - Run `voice_proc_main.ipynb` to analyze voice data.

---

## Results

- A detailed analysis of results can be found in the report: `FINAL ML Project Report.pdf`.

---

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- The **MU3D (Miami University Deception Detection Database)** team for the dataset.
- Resources and inspiration from various open-source projects.

--- 

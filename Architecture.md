## System Workflow and Design
flowchart TD
    A[User Video Input] --> B[Frame & Audio Extraction]
    B --> C[Face + Pose Detection (MediaPipe)]
    C --> D[Expression & Eye Contact Analysis]
    D --> E[Speech-to-Text (SpeechRecognition)]
    E --> F[Tone, Clarity, Emotion Analysis (NLP + Audio)]
    F --> G[Score Computation & Feedback Generation]
    G --> H[Streamlit Dashboard Visualization]
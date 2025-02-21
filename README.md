# Multilingual News Audio Translator 🎧🌍  

This project is a real-time multilingual news audio translator that:  
- **Speech Recognition:** Uses **Wav2Vec 2.0 + CTC Loss**.  
- **Neural Machine Translation:** Utilizes **mBART + Reinforcement Learning (BLEU reward)**.  
- **Text-to-Speech:** Implements **FastSpeech 2 + Knowledge Distillation**.  

## Supported Languages:  
- Hindi, Gujarati, French, German  

## Features:  
- Real-time multilingual translation  
- User-friendly language selection  
- High accuracy with fine-tuning and reinforcement learning  

## How to Use:  
1. Upload an audio file.  
2. Choose the target language.  
3. Download the translated audio output.  

## Dependencies:  
```bash
!pip install SpeechRecognition
!pip install SpeechRecognition pydub googletrans==4.0.0-rc1
!pip install gtts
!pip install pydub
```
## Future Enhancements:
- More language support
- Improved real-time performance

## Contributing:
Contributions are welcome! Feel free to open issues or submit pull requests.

## License:
This project is licensed under the MIT License.

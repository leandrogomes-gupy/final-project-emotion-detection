# Emotion Detection Application

Aplicação web de detecção de emoções construída com Python, Flask e a biblioteca
Watson NLP (Embedded AI Libraries).

## Estrutura

```
final_project/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── static/
│   └── mywebscript.js
├── templates/
│   └── index.html
├── server.py
└── test_emotion_detection.py
```

## Como executar

```bash
python3 server.py
```

Acesse `http://localhost:5000`.

## Testes unitários

```bash
python3 test_emotion_detection.py
```

## Análise estática de código

```bash
pylint server.py
```

# Projeto de Transcrição de Áudio com Whisper (Português)

Este script realiza a transcrição de arquivos de áudio usando a API da OpenAI (modelo `whisper-1`) com timestamps.

## Funcionalidades

- Gera dois arquivos automaticamente:
  - `.txt`: ideal para leitura da transcrição com marcação de tempo
  - `.csv`: ideal para análise com Python, Excel ou Power BI (com separador `;`)

## Como usar

1. Grave ou adicione seu áudio em `audios/audio_PT.mp3`
2. Configure sua chave da OpenAI no arquivo `.env`
3. Execute o script `Transcricao_Audio_PT.py` na pasta `PT`

Os arquivos gerados serão:
- `audio_PT_transcricao.txt`
- `audio_PT_transcricao.csv`  
Ambos estarão na mesma pasta do arquivo de áudio.

> ⚠️ Este projeto é apenas para fins educacionais.  
> Os áudios utilizados são de autoria própria, sem violar direitos autorais.


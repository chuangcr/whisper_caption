conda create --name whisper python=3.12
activate whisper

pip install openai-whisper==20240930
pip install stable-ts==2.17.5
pip install moviepy==1.0.3
pip install googletrans==4.0.0rc1
conda install ffmpeg==6.1.0


簡單使用whisper model對影片上字幕、翻譯

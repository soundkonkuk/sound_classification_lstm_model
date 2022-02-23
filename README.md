# model
1. data augmentation

   ✔ White noise
   
   ✔ Reverse sound
   
    ✔ Shifting
    
    ✔ Stretching
    
    ✔ Minus 
    
    
* librosa 0.8.0 부터 librosa.output.write_wav 지원 ❌❌❌

* 대신

  import soundfile as sf
  
  sf.write('stereo_file.flac', data, samplerate, format='flac', subtype='PCM_24') 사용 ⭕⭕⭕

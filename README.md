###  Wav2lip in Vector Quantized space
##### an unofficial implementation of _Towards Generating Ultra-High Resolution Talking-Face Videos with Lip synchronization_

- VQGAN 
  - https://github.com/CompVis/taming-transformers
  - image_size = 256
- syncnet_vq.py
  - face_encoder: (B, T x 256, 16, 16) -> (B, 512, 1, 1)
  - audio_encoder: (B, 1, 80, 16) -> (B, 512, 1, 1)
- color_syncnet_train_vq.py
  - vqgan config / ckpt

### Reference
- https://github.com/Rudrabha/Wav2Lip.git
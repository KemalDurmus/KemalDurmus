# Kemal Durmuş

Student at Ege University, Tire Kutsan Vocational School.

## Graduation project: DeepGuard (in progress, 2026–2027)

Local deepfake detection for live screen/audio, video and photos.

**Visual side (my part):** trained an EfficientNet-B4 face-manipulation / AI-generated face detector (self-blended images + own FLUX.1-schnell generations, licensed real photos), with a frozen calibration threshold and a one-time locked test on an unseen generator (Kandinsky 2.2).

**Product integration:** Flask + vanilla JS app scoring live frames, videos and photos; raw model scores only, no verdict without calibration and acceptance evidence.

Source code is private for now (team project); details available on request.

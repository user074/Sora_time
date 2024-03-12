# Sora_time

Investigate the temporal consistency of Sora model

1.⁠ ⁠Data scouting: Finding >=15 seconds video including text input. Deadline: March 12

2.⁠ ⁠⁠Feature Extraction: Using 16x16 patching to extract video features to input DIT. Deadline: March 20th

3.⁠ ⁠⁠DIT training starting in March 20th.


Existing Repo we can use:
[open-sora](https://github.com/hpcaitech/Open-Sora), and they are using [MSR-VTT
](https://cove.thecvf.com/datasets/839) dataset.

Additionally we can use [DiT](https://github.com/facebookresearch/DiT) for the model architecture.

A simple method is to use same cropped sized videos to test the time consistency



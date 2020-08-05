This is the demo page for the paper [AUTOMATIC COMPOSITION OF GUITAR TABS BY TRANSFORMERS AND GROOVE MODELING](https://arxiv.org/abs/2008.01431)

## Abstract
Recent years have witnessed great progress in using deep learning algorithms to learn to compose music in the form of a MIDI file.  However, whether such algorithms apply equally well to compose guitar tabs, which are quite different from MIDIs, remain relatively unexplored. To address this, we build a model for composing fingerstyle guitar tabs with Transformer-XL, a neural sequence model architecture. With this model, we investigate the following research questions. First, whether the neural net generates note sequences with meaningful  note-string combinations, which is important for the guitar but not other instruments such as the piano. Second, whether it generates compositions with coherent rhythmic groove, crucial for fingerstyle guitar music. And, finally, how pleasant the composed music is in comparison to real, human-made compositions. Our work provides preliminary empirical evidence of the promise of deep learning for tab composition, and suggests areas for future study.

### Demo audio

|   |Real data|No grooving|Hard grooving|
|1.|<audio src="result/real data/0.wav" controls="" preload=""></audio>|<audio src="result/no grooving/0.wav" controls="" preload=""></audio>|<audio src="result/hard grooving/0.wav" controls="" preload=""></audio>|
|2.|<audio src="result/real data/1.wav" controls="" preload=""></audio>|<audio src="result/no grooving/1.wav" controls="" preload=""></audio>|<audio src="result/hard grooving/1.wav" controls="" preload=""></audio>|
|3.|<audio src="result/real data/2.wav" controls="" preload=""></audio>|<audio src="result/no grooving/2.wav" controls="" preload=""></audio>|<audio src="result/hard grooving/2.wav" controls="" preload=""></audio>|
|4.|<audio src="result/real data/3.wav" controls="" preload=""></audio>|<audio src="result/no grooving/3.wav" controls="" preload=""></audio>|<audio src="result/hard grooving/3.wav" controls="" preload=""></audio>|
|5.|<audio src="result/real data/4.wav" controls="" preload=""></audio>|<audio src="result/no grooving/4.wav" controls="" preload=""></audio>|<audio src="result/hard grooving/4.wav" controls="" preload=""></audio>|

### Demo Video
This video recording is a guitarist from our team playing a generated tab which is generated from scratch.
<iframe width="800" height="500" src="https://www.youtube.com/embed/yccH6kvinq0">
</iframe>

### Contact 
Yu-Hua Chen r08946011@ntu.edu.tw

A list of demo websites for automatic music generation research

[interactive piano composition]
* Piano Genie— https://piano-genie.glitch.me/
* AI duet— https://experiments.withgoogle.com/ai/ai-duet/view/


[compose melody]
* [SSMGAN](https://drive.google.com/file/d/1Ol4Ym3KqUkjcfL_Yeu0It3BP7NFS2mor/view) (VAE+LSTM+GAN; jhamtani19ml4md): https://drive.google.com/drive/folders/1TlOrbYAm7vGUvRrxa-uiH17bP-4N4e9z
* [StructureNet](http://ismir2018.ircam.fr/doc/pdfs/126_Paper.pdf) (LSTM; medeot18ismir) https://www.dropbox.com/sh/yxkxlnzi913ba50/AAA_mDbhdmaGJC9qj0zSlqCea?dl=0
* [MidiNet](https://arxiv.org/abs/1703.10847) (CNN+GAN; yang17ismir): https://richardyang40148.github.io/TheBlog/midinet_arxiv_demo.html
* [folkRNN](https://github.com/IraKorshunova/folk-rnn) (LSTM): https://folkrnn.org/


[compose single-track polyphonic music]
* [VGMIDI](http://www.lucasnferreira.com/papers/2019/ismir-learning.pdf) (LSTM; ferreira19ismir): N/A
* [Modularized VAE](https://arxiv.org/pdf/1811.00162.pdf) (GRU+VAE; wang19icassp): https://github.com/MiuLab/MVAE_Music
* [BachProp](https://arxiv.org/abs/1812.06669) (GRU; colombo18arxiv): https://sites.google.com/view/bachprop


[given chord, compose melody]
* [JazzGAN](http://musicalmetacreation.org/mume2018/proceedings/Trieu.pdf) (GAN; trieu18mume): https://www.cs.hmc.edu/~keller/jazz/improvisor/
* [XiaoIce Band](http://staff.ustc.edu.cn/~qiliuql/files/Publications/Hongyuan-Zhu-KDD2018.pdf) (GRU; zhu18kdd): http://tv.cctv.com/2017/11/24/VIDEo7JWp0u0oWRmPbM4uCBt171124.shtml


[compose drum loops]
* Generating structured drum pattern using variational autoencoder and self-similarity matrix (wei19ismir): N/A
* [DrumVAE](https://arxiv.org/abs/1902.03722) (GRU+VAE; thio19milc): http://vibertthio.com/drum-vae-client


[compose melody+chords (two tracks)]
* [LeadsheetGAN](https://arxiv.org/abs/1807.11161) (CRNN+GAN; liu18icmla): https://liuhaumin.github.io/LeadsheetArrangement/results
* [LeadsheetVAE](https://drive.google.com/file/d/10uGRGEI9IOfu_LyzDSG393fGhwUrEOi4/view) (RNN+VAE; liu18ismir-lbd): https://liuhaumin.github.io/LeadsheetArrangement/results


[generate melody, compose arrangement]
* LeadsheetGAN: see above
* LeadsheetVAE: see above
* XiaoIce Band (the "multi-instrument co-arrangement model"): N/A


[compose melody+bass+drum]
* [MusicVAE](https://arxiv.org/abs/1803.05428) (LSTM+VAE; roberts18icml): https://magenta.tensorflow.org/music-vae


[compose multitrack music]
* [LakhNES](https://arxiv.org/abs/1907.04868) (Transformer; donahue19ismir): https://chrisdonahue.com/LakhNES/
* [MuseNet](https://openai.com/blog/musenet/) (Transformer): https://openai.com/blog/musenet/
* [MIDI-VAE](https://arxiv.org/abs/1809.07600) (GRU+VAE; brunner18ismir): https://www.youtube.com/channel/UCCkFzSvCae8ySmKCCWM5Mpg
* [Multitrack MusicVAE](https://arxiv.org/abs/1806.00195) (LSTM+VAE; simon18ismir): https://magenta.tensorflow.org/multitrack
* [MuseGAN](https://arxiv.org/abs/1709.06298) (CNN+GAN; dong18aaai): https://salu133445.github.io/musegan/


[given prime melody, compose melody+chords]
* [local_conv_music_generation](http://ouyangzhihao.com/wp-content/uploads/2018/12/MUSIC-GENERATION-WITH-LOCAL-CONNECTED-CONVOLUTIONAL-NEURAL-NETWORK.pdf) (CNN; ouyang18arxiv): https://somedaywilldo.github.io/local_conv_music_generation/


[given prime melody, compose melody+chords+bass]
* [BandNet](https://arxiv.org/abs/1812.07126) (RNN; zhou18arxiv): https://soundcloud.com/yichao-zhou-555747812/sets/bandnet-sound-samples-1 


[given piano score, compose an orchestration]
* [LOP](https://qsdfo.github.io/LOP/index.html) (RBM; crestel17smc): https://qsdfo.github.io/LOP/results.html


[symbolic-domain genre style transfer]
* [supervised](https://arxiv.org/abs/1907.02265) (RNN; cífka19ismir): https://github.com/cifkao/ismir2019-music-style-translation
* [RaGAN](https://www.aaai.org/Papers/AAAI/2019/AAAI-LuC.2259.pdf) (GAN; lu19aaai): https://github.com/ChienYuLu/Play-As-You-Like-Timbre-Enhanced-Multi-modal-Music-Style-Transfer
* [CycleGAN](https://arxiv.org/pdf/1809.07575.pdf) (CNN+GAN; brunner18ictai): https://github.com/sumuzhao/CycleGAN-Music-Style-Transfer
* [FusionGAN](https://dac.cs.vt.edu/wp-content/uploads/2017/11/learning-to-fuse.pdf) (GAN; chen17icdm): http://people.cs.vt.edu/czq/publication/fusiongan/


[given score, generate musical audio (performance): Piano only]
* [GGNN](http://proceedings.mlr.press/v97/jeong19a/jeong19a.pdf) (graph NN + hierarchical attention RNN; jeong19icml): https://slideslive.com/38917395/applications
* [VirtuosoNet](https://nips2018creativity.github.io/doc/virtuosonet.pdf) (LSTM+hierarchical attention network; jeong18nipsw): https://www.youtube.com/playlist?list=PLkIVXCxCZ08rD1PXbrb0KNOSYVh5Pvg-c
* [Wave2Midi2Wave](https://arxiv.org/abs/1810.12247) (transformer+wavenet; hawthorne19iclr): https://magenta.tensorflow.org/maestro-wave2midi2wave
* [PerformanceRNN](https://magenta.tensorflow.org/performance-rnn) (RNN): https://magenta.tensorflow.org/performance-rnn


[given score, generate musical audio (performance): Not limited to Piano]
* [GrooVAE](https://magenta.tensorflow.org/groovae) (seq2seq+VAE; gillick19icml): https://magenta.tensorflow.org/groovae
* [PerformanceNet](https://arxiv.org/abs/1811.04357) (CNN+GAN; wang19aaai): https://github.com/bwang514/PerformanceNet


[audio synthesis]
* [AdVoc](https://arxiv.org/abs/1904.07944) (; neekhara19arxiv): http://chrisdonahue.com/advoc_examples/
* [GANSynth](https://arxiv.org/abs/1902.08710) (CNN+GAN; engel19iclr): https://magenta.tensorflow.org/gansynth
* [TFGAN](https://arxiv.org/abs/1902.04072) (CNN+GAN; marafioti19arxiv): https://tifgan.github.io/
* [WaveGAN](https://arxiv.org/abs/1802.04208) (CNN+GAN; donahue19iclr): https://github.com/chrisdonahue/wavegan
* [NSynth](https://arxiv.org/abs/1704.01279) (WaveNet; engel17arxiv): https://magenta.tensorflow.org/nsynth


[audio-domain music generation]
* [dadabots](https://arxiv.org/abs/1811.06633) (sampleRNN; carr18mume): http://dadabots.com/music.php


[audio-domain singing synthesis]
* http://home.ustc.edu.cn/~yiyh/interspeech2019/


[audio-domain singing style transfer]
* https://mtg.github.io/singing-synthesis-demos/voice-cloning/
* https://enk100.github.io/Unsupervised_Singing_Voice_Conversion/
* [cybegan](https://arxiv.org/pdf/1807.02254.pdf) (CNN+GAN; wu18faim): http://mirlab.org/users/haley.wu/cybegan/

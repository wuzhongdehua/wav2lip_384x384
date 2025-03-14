# wav2lip_384x384 introduction
This is a project about talking faces. We use384X384 sized facial images for training, which can generate720p, 1080p, 2k ,4k Digital Humanhuman videos.
We have done the following work:
1. Add video cutting codes.
2. Add filelists to generate code.
3. Trained 1000 people, 50 hours, and over 50000 pieces of data.
4. Open sourced the checkpoint for a discriminator with 700000 steps and a val_rass of 0.29.
5. Open sourced a checkpoint for a generator with 300000 steps and a val_rass of 0.35 , But the effect is not good, it is recommended not to use it. You can continue training by loading it..
6. Dear friends,we did not release the best generator checkpoint, However, generators with over 500000 steps have surpassed all open source projects on the market in terms of direct inference performance, and have reached a basic commercial level.
7. Dear friends,Although we did not release the best generator checkpoint, but we released the best discriminator checkpoint, you need load pre training weights for easy subsequent training, many people have loaded our color_checkpoints for training, and achieved good results.
8. Due to the wav2lip high-definition algorithm series, it cannot achieve high fidelity of faces and teeth, and the training difficulty is relatively high, which cannot adapt well to current commercial needs.. So we have changed the algorithm for commercial digital humans and adopted new algorithms such as diffusion.
9. Friends who want to train the wav2lip high-definition series, please think carefully before taking action.

# wav2lip-384x384 Project situation
<p align='center'>
  <b>
    <a href="https://space.bilibili.com/431556168">Video </a>
    | 
    <a href="https://github.com/langzizhixin">Project Page</a>
    |
    <a href="https://github.com/langzizhixin/wav2lip-576x576">Code</a> 
  </b>
</p> 

checkpoints for wav2lip_384x384   https://pan.baidu.com/s/1eibDdqZXwCmV2yTW33qA2g?pwd=lzzx 

## The following pictures are comparison images of the training generator training 500000 steps.
<p align='center'>  
    <img src='picture/11.jpg' width='1400'/>
</p>


# Release Plan
For the wav2lip series, we will continue to train and release higher definition weights in the future.
The plan is as follows:
Pre training checkpoints for wav2lip_288x288 will be released in January 2025.
Pre training checkpoints for wav2lip_384x384 will be released in February 2025.
Pre training checkpoints for wav2lip_576x576 or 512x512 will be released in June 2025.

# Citing
Thank you to the other three authors, Thank you for their wonderful work.

https://github.com/primepake/wav2lip_288x288

https://github.com/nghiakvnvsd/wav2lip384

https://github.com/Rudrabha/Wav2Lip

# Disclaimers
This repositories made by langzizhixin from Langzizhixin Technology company 2025.1.30 , in Chengdu, China .
The above code and weights can only be used for personal/research/non-commercial purposes.
If you need a higher definition model, please contact me by email 277504483@qq.com , or add WeChat for communication: langzizhixinkeji

<div align="center">
  
# Deep Learning-Driven Ultra-High-Definition Image Restoration: A Survey

<!--
[Liyan Wang](https://wlydlut.github.io/), Weixiang Zhou, [Cong Wang](https://supercong94.wixsite.com/supercong94), Kin-Man Lam, [Zhixun Su](https://scholar.google.com/citations?user=ycFs33AAAAAJ&hl=en), and [Jinshan Pan](https://jspan.github.io/)
-->

---
</div>


## Overview
<div align="center">
<img src="https://github.com/wlydlut/UHD-Image-Restoration-Survey/blob/main/milestone.png" border="0"></a>
</div>

## Datasets
<table>
    <thead>
        <tr>
            <th>Datasets </th>
            <th>Restoration Task</th>
            <th>Number(Train/Test)</th>
            <th>Synthetic/Real</th>
            <th>Format</th>
            <th>Publication</th>
            <th>DownLoad</th>
        </tr>
    </thead>
    <tbody align="center" valign="center">
         <tr>
            <td>UHDSR4K</td>
            <td>Image Super-Resolution</td>
            <td>5,999 / 2,100</td>
            <td>Real</td>
            <td>PNG</td>
            <td>ICCV'21</td>
            <td><a href="https://github.com/HDCVLab/UHD4K_UHD8K">Link</a></td>
        </tr>
        <tr>
            <td>4KRD</td>
            <td>Video Deblurring</td>
            <td>19,958 / 1600</td>
            <td>Synthetic</td>
            <td>JPG</td>
            <td>ICCV'21</td>
            <td><a href="https://drive.google.com/drive/folders/19bjJLMgQkwIAQaZYvsUhEVaxzJQFwhHF?usp=sharing">Link</a></td>
        </tr>
         <tr>
            <td>UHD-Blur</td>
            <td>Image Deblurring</td>
            <td>1,964 / 300</td>
            <td>Synthetic</td>
            <td>JPG</td>
            <td>AAAI'24</td>
            <td><a href="https://drive.google.com/drive/folders/1O6JYkOELLhpEkirAnxUB2JGWMqgwVvmX">Link</a></td>
        </tr>
         <tr>
            <td>4KID</td>
            <td>Image Dehazing</td>
            <td>8,000 / 200</td>
            <td>Synthetic</td>
            <td>JPG</td>
            <td>CVPR'21</td>
            <td><a href="https://github.com/zzr-idam/4KDehazing">Link</a></td>
        </tr>
          <tr>
            <td>Updated 4KID</td>
            <td>Image Dehazing</td>
            <td>10,400 / 200</td>
            <td>Synthetic</td>
            <td>JPG</td>
            <td>Signal Process.'24</td>
            <td>❌</td>
        </tr>
         <tr>
            <td>UHD-Haze</td>
            <td>Image Dehazing</td>
            <td>2,290 / 230</td>
            <td>Synthetic</td>
            <td>JPG</td>
            <td>AAAI'24</td>
            <td><a href="https://drive.google.com/drive/folders/1PVCPkhqU_voPVFZj3FzAtUkJnQnF9lSa">Link</a></td>
        </tr>
         <tr>
            <td>4KIL</td>
            <td>Low-Light Image Enhancing</td>
            <td>1,000 / 100</td>
            <td>Synthetic</td>
            <td>JPG</td>
            <td>Inf. Sci'22</td>
            <td>❌</td>
        </tr>
       <tr>
            <td>UHD-LOL4K</td>
            <td>Low-Light Image Enhancing</td>
            <td>5,999 / 2,100</td>
            <td>Synthetic</td>
            <td>PNG</td>
            <td>AAAI'23</td>
             <td><a href="https://mailnwpueducn-my.sharepoint.com/personal/2018302756_mail_nwpu_edu_cn/_layouts/15/onedrive.aspx?id=%2Fpersonal%2F2018302756%5Fmail%5Fnwpu%5Fedu%5Fcn%2FDocuments%2Fshared%2Fprojects%2Fll%2Dformer%2FUHD%5F4K&ga=1">Link</a></td>
        </tr>
          <tr>
            <td>UHD-LL</td>
            <td>Low-Light Image Enhancing</td>
            <td>2,000 / 150</td>
            <td>Real</td>
            <td>JPG</td>
            <td>ICLR'23</td>
             <td><a href="https://drive.google.com/drive/folders/1IneTwBsSiSSVXGoXQ9_hE1cO2d4Fd4DN">Link</a></td>
        </tr>
        <tr>
            <td>4K-Rain13K</td>
            <td>Image Deraining</td>
            <td>12,500 / 500</td>
            <td>Synthetic</td>
            <td>JPG</td>
            <td>ArXiv'24</td>
             <td><a href="https://github.com/cschenxiang/UDR-Mixer">Link</a></td>
        </tr>
         <tr>
            <td>4K-RealRain</td>
            <td>Image Deraining</td>
            <td>- / 320</td>
            <td>Real</td>
            <td>JPG</td>
            <td>ArXiv'24</td>
             <td><a href="https://github.com/cschenxiang/UDR-Mixer">Link</a></td>
        </tr>
        <tr>
            <td>UHD-Rain</td>
            <td>Image Deraining</td>
            <td>3,000 / 200</td>
            <td>Synthetic</td>
            <td>JPG</td>
            <td>ArXiv'24</td>
             <td><a href="https://drive.google.com/drive/u/1/folders/1AHWlsyExpIQLhQ-ECBfvmlk296hZzzrK?hl=zh_CN">Link</a></td>
        </tr>
         <tr>
            <td>UHD-Snow</td>
            <td>Image Deraining</td>
            <td>3,000 / 200</td>
            <td>Synthetic</td>
            <td>JPG</td>
            <td>ArXiv'24</td>
             <td><a href="https://drive.google.com/drive/u/1/folders/1DBqekDEans9sM_chW3o1hz908WoPwPA7?hl=zh_CN">Link</a></td>
        </tr>
    </tbody>
</table>

## UHD Image Restoration Methods
<table>
    <thead>
        <tr>
            <th>Category<br>(分类)</th>
            <th>Methods<br>(方法)</th>
            <th>Tasks<br>(任务)</th>
            <th>Title<br>(标题)</th>
            <th>Venue<br>(发表场所)</th>
            <th>Source<br>(资源)</th>
        </tr>
    </thead>
      <tbody align="center" valign="center">
       <tr>
            <td>Downsampling-Enhancement-Upsampling</td>
            <td>MANet</td>
            <td>SR</td>
            <td>Benchmarking ultra-high-definition image superresolution</td>
            <td>ICCV'21</td>
            <td><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9711004">Paper</a>/</td>
        </tr>
       <tr>
            <td>Downsampling-Enhancement-Upsampling</td>
            <td>UHD</td>
            <td>Dehaze</td>
            <td>Ultra-high-definition image dehazing via multi-guided bilateral learning</td>
            <td>CVPR'21</td>
            <td><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=95784334">Paper</a>/<a href="https://github.com/zzr-idam/4KDehazing">Code</a></td>
        </tr>
          <tr>
            <td>Downsampling-Enhancement-Upsampling</td>
            <td>Lin et al.</td>
            <td>LLIE</td>
            <td>UHD low-light image enhancement via interpretable bilateral learning</td>
            <td>Inf. Sci'22</td>
            <td><a href="https://www.sciencedirect.com/science/article/pii/S002002552200740X">Paper</a>/<a href="https://github.com/zzr-idam/UHD-Low-light-image-enhancement">Code</a></td>
        </tr>
          <tr>
            <td>Downsampling-Enhancement-Upsampling</td>
            <td>Cubic-Mixer</td>
            <td>Deblur</td>
            <td>Ultra-High-Definition Image Deblurring via Multi-scale Cubic-Mixer</td>
            <td>ArXiv'24</td>
            <td><a href="https://arxiv.org/abs/2206.03678">Paper</a>/<a href="https://github.com/zzr-idam/deblur">Code</a></td>
        </tr>
          <tr>
            <td>Downsampling-Enhancement-Upsampling</td>
            <td>UHDFour</td>
            <td>LLIE</td>
            <td>Embedding fourier for ultra-high-definition low-light image enhancement</td>
            <td>ICLR'23</td>
            <td><a href="https://arxiv.org/abs/2302.11831">Paper</a>/<a href="https://github.com/Li-Chongyi/UHDFour">Code</a></td>
        </tr>
          <tr>
            <td>Downsampling-Enhancement-Upsampling</td>
            <td>DMixer</td>
            <td>Dehaze</td>
            <td>Dimensional transformation mixer for ultra-high-definition industrial camera dehazing</td>
            <td>IEEE Trans. Ind. Inf.'24</td>
            <td><a href="[https://arxiv.org/abs/2302.11831](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10323236)">Paper</a>/</td>
        </tr>
          <tr>
            <td>Downsampling-Enhancement-Upsampling</td>
            <td>MixNet</td>
            <td>LLIE/Deblur</td>
            <td>Mixnet: Towards effective and efficient UHD low-light image enhancement</td>
            <td>ArXiv'24</td>
            <td><a href="https://arxiv.org/abs/2401.10666">Paper</a>/></td>
        </tr>
          <tr>
            <td>Downsampling-Enhancement-Upsampling</td>
            <td>UDR-Mixer</td>
            <td>Derain</td>
            <td>Towards ultra-high-definition image deraining: A benchmark and an efficient method</td>
            <td>ArXiv'24</td>
            <td><a href="https://arxiv.org/abs/2405.17074">Paper</a>/<a href="https://github.com/cschenxiang/UDR-Mixer">Code</a></td>
        </tr>
           <tr>
            <td>Downsampling-Enhancement-Upsampling</td>
            <td>UHDformer</td>
            <td>LLIE/Deblur/Dehaze</td>
            <td>Correlation matching transformation transformers for UHD image restoration</td>
            <td>AAAI'24</td>
            <td><a href="https://arxiv.org/abs/2406.00629">Paper</a>/<a href="https://github.com/supersupercong/UHDformer">Code</a></td>
        </tr>
           <tr>
            <td>Downsampling-Enhancement-Upsampling</td>
            <td>UHDDIP</td>
            <td>LLIE/Deblur/Dehaze/Derain/Desnow</td>
            <td>Ultra-high-definition restoration: New benchmarks and A dual interaction prior-driven solution</td>
            <td>ArXiv'24</td>
            <td><a href="https://arxiv.org/abs/2406.13607">Paper</a>/<a href="https://github.com/wlydlut/UHDDIP">Code</a></td>
        </tr>
             <tr>
            <td>Downsampling-Enhancement-Upsampling</td>
            <td>SimpleIR</td>
            <td>All-in-One</td>
            <td>Review learning: Advancing all-in-one ultra-high-definition image restoration training method</td>
            <td>ArXiv'24</td>
            <td><a href="https://arxiv.org/abs/2408.06709">Paper</a>/</td>
        </tr>
             <tr>
            <td>Encoder-Decoder with Stepwise Up-downsampling</td>
            <td>UHDVD</td>
            <td>Deblur</td>
            <td>Review learning: Advancing all-in-one ultra-high-definition image restoration training method</td>
            <td>ICCV'21</td>
            <td><a href="https://ieeexplore.ieee.org/document/9711223">Paper</a>/<a href="https://github.com/dseny/UHDVD">Code</a></td>
        </tr>
        <tr>
            <td>Encoder-Decoder with Stepwise Up-downsampling</td>
            <td>LLFormer</td>
            <td>Deblur</td>
            <td>Ultrahigh-definition low-light image enhancement: A benchmark and transformer-based method</td>
            <td>AAAI'23</td>
            <td><a href="https://arxiv.org/abs/2212.11548">Paper</a>/<a href="https://github.com/TaoWangzj/LLFormer">Code</a></td>
        </tr>
        <tr>
            <td>Encoder-Decoder with Stepwise Up-downsampling</td>
            <td>LapDehazeNet</td>
            <td>Dehaze</td>
            <td>Single UHD image dehazing via interpretable pyramid network</td>
            <td>Signal Process.'24</td>
            <td><a href="https://www.sciencedirect.com/science/article/pii/S0165168423002992">Paper</a>/<a href="https://github.com/zzr-idam/Interpretable-Pyramid-Network">Code</a></td>
        </tr>
        <tr>
            <td>Encoder-Decoder with Stepwise Up-downsampling</td>
            <td>Wave-Mamba</td>
            <td>LLIE</td>
            <td>Wave-mamba:Wavelet state space model for ultra-high-definition low-light image enhancement</td>
            <td>ACM MM'24</td>
            <td><a href="https://dl.acm.org/doi/10.1145/3664647.3681580">Paper</a>/<a href="https://github.com/AlexZou14/Wave-Mamba">Code</a></td>
        </tr>
        <tr>
            <td>Encoder-Decoder with Stepwise Up-downsampling</td>
            <td>TSFormer</td>
            <td>LLIE/Deblur/Dehaze/Derain/Desnow</td>
            <td>Tsformer: A robust framework for efficient uhd image restoration</td>
            <td>ArXiv'24</td>
            <td><a href="https://arxiv.org/abs/2411.10951">Paper</a>/</td>
        </tr>
        <tr>
            <td>Resampling-Enhancement</td>
            <td>NSEN</td>
            <td>LLIE/Dehaze</td>
            <td>Learning non-uniform-sampling for ultra-high-definition image enhancement</td>
            <td>ACM MM'23</td>
            <td><a href="https://dl.acm.org/doi/abs/10.1145/3581783.3611836">Paper</a>/</td>
        </tr>
        <tr>
            <td>Resampling-Enhancement</td>
            <td>LMAR</td>
            <td>LLIE</td>
            <td>Empowering resampling operation for ultra-high-definition image enhancement with model-aware guidance</td>
            <td>CVPR'24</td>
            <td><a href="https://ieeexplore.ieee.org/abstract/document/10655566">Paper</a>/<a href="https://github.com/YPatrickW/LMAR">Code</a></td>
        </tr>
    <tbody>
    </table>



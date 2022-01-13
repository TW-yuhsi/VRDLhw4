# VRDLhw4



## SRResNet (best score: 28.0523)


<details>
<summary>Setup</summary>

```bash
$ conda create -n VRDLhw4_SRResNet python=3.7
$ conda activate VRDLhw4_SRResNet
$ conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch
$ cd /home/yuhsi44165/NYCU/G2/VRDL/HW4/
$ git clone https://github.com/TW-yuhsi/VRDLhw4.git
$ cd VRDLhw4/
$ pip install -r requirements.txt
```
  
</details>




<details>
<summary>Folder structure</summary>
  
```text
$ cd /home/yuhsi44165/NYCU/G2/VRDL/HW4/
├── data
│   ├── testing_lr_images
│   │   ├── 00.png
│   │   ├── 01.png
│   │   ├── .
│   │   ├── .
│   │   ├── .
│   │   ├── 13.png
│   ├── training_hr_images
│   │   ├── 2092.png
│   │   ├── 8049.png
│   │   ├── .
│   │   ├── .
│   │   ├── .
│   │   ├── tt27.png
```
  
</details>




<details>
<summary>Split training data</summary>

```bash
$ python train_val_split.py
```
  
</details>




<details>
<summary>Training</summary>

```bash
$ python train.py
```
  
</details>




<details>
<summary>Inference</summary>

```bash
$ python test.py
```
  
</details>





<details>
<summary>Reference</summary>

- https://arxiv.org/abs/1609.04802
- https://github.com/twtygqyy/pytorch-SRResNet
- https://github.com/sgrvinod/a-PyTorch-Tutorial-to-Super-Resolution
  
</details>



## EDSR (best score: 26.1087)


<details>
<summary>Reference</summary>

- https://arxiv.org/abs/1707.02921
- https://github.com/sanghyun-son/EDSR-PyTorch
  
</details>



## RCAN (best score: 26.7379)
  
  
  
<details>
<summary>Reference</summary>

- https://arxiv.org/abs/1807.02758
- https://github.com/yulunzhang/RCAN
  
</details>


  
  
## HAN (best score: 26.4231)


<details>
<summary>Reference</summary>

- https://arxiv.org/abs/2008.08767
- https://github.com/wwlCape/HAN

  
</details>


  
  

  
  
  





## Related URLs

- Dataset link: https://drive.google.com/file/d/1SJYi-q56NMuT_YOD_8kTXivwDM96AvUx/view?usp=sharing
- Experimental results: https://docs.google.com/spreadsheets/d/1ttBWq64IWFo7lawCdKRM4RoGpyF_aazjS7nnvZY4BUw/edit?usp=sharing
- Model weights after training (best_checkpointsrresnet.pth.tar): https://drive.google.com/file/d/15NSIxFjINvXvQczfAMk89uyrU4m8mJzb/view?usp=sharing



## Reference
- https://github.com/saeed-anwar/DRLN
- https://github.com/haoyuc/A2N



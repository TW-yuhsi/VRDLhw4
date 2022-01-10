# VRDLhw4



## SRResNet (best score: 26.9829)


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
│   ├── testing_hr_images
│   │   ├── 2092.png
│   │   ├── 8049.png
│   │   ├── .
│   │   ├── .
│   │   ├── .
│   │   ├── rr27.png
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




## RCAN (best score: 26.7379)
  
  
  
## HAN (best score: 26.4231)


  
  
## EDSR (best score: 26.1087)
  
  
  





## Related URLs

• Dataset link

https://drive.google.com/file/d/1SJYi-q56NMuT_YOD_8kTXivwDM96AvUx/view?usp=sharing

• GitHub Repository



• Model weights after training ()



# PLRDiff
Official codes of "Unsupervised Pansharpening via Low-rank Diffusion Model"

## Download Dataset

Chikusei: [https://naotoyokoya.com/Download.html](https://naotoyokoya.com/Download.html)

Houston: [https://hyperspectral.ee.uh.edu/?page id=459](https://hyperspectral.ee.uh.edu/?page_id=459)

Pavia: [https://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes](https://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes)

## Prepare test dataset

## Testing
run ``python3 test_single.py -gpu '(gpu)' -dr (dataroot) -dn (dataname) -rs (resume_state)``

gpu: int

dataroot: str, e.g. /path/Chikusei.mat



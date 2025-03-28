
## 环境安装
```
pip install torch==1.12.1+cu113 torchvision==0.13.1+cu113 torchaudio==0.12.1 --extra-index-url https://download.pytorch.org/whl/cu113
pip install -U openmim
mim install mmengine
mim install "mmcv>=2.0.0"
```

## 下载demo
```
git clone https://github.com/open-mmlab/mmdetection.git
cd mmdetection
pip install -v -e .
```

## Instructions
- simple demo for mmdetection: https://blog.csdn.net/clearlove7777776/article/details/130834965?spm=1001.2101.3001.6650.2&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7ERate-2-130834965-blog-137594759.235%5Ev43%5Epc_blog_bottom_relevance_base6&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7ERate-2-130834965-blog-137594759.235%5Ev43%5Epc_blog_bottom_relevance_base6&utm_relevant_index=3

- running mmpretrain: https://zhuanlan.zhihu.com/p/702210475
# detr_interface
本リポジトリはInterface 4月号の参考リポジトリになります。
なお、本記事のコードと環境は全て下記で公開されています。
- GitHub: [https://github.com/daedalus-jp/detr_interface](https://github.com/daedalus-jp/detr_interface)
- Docker Hub: [https://hub.docker.com/repository/docker/daedalusinc/detr_interface/general](https://hub.docker.com/repository/docker/daedalusinc/detr_interface/general)

本記事のお問い合わせは`contact@daedalus.co.jp`までご連絡ください。

## ColabでDETRの体験
下記リンクで、記事内のGoogle Cokaboratoryを実行することができます。  
https://colab.research.google.com/drive/1hJqXyB3peGtK15ODimavWlH3h8LA7Pqt#scrollTo=GJhCp8y0-b-H

なお、DETR公式Colabは下記になります。  
https://colab.research.google.com/github/facebookresearch/detr/blob/colab/notebooks/detr_demo.ipynb#scrollTo=BiwSmd2i-Wkf

## DETRの学習の実行
以下に実行手順を示します。
1. **folders.ipynb**の実行
1. **change_category_id.ipynb**の実行
1. **load_pretrained_model.ipynb**の実行
1. `cd detr`
1. `python3 main.py --dataset_file custom --coco_path ../data/custom --output_dir ./outputs/ --resume ./detr-r50.pth --num_workers 8 --batch_size 2 --num_classes 1 --epochs 80 --lr 1e-5`
1. **predictor.ipynb**の実行

## 参考
1. [https://paperswithcode.com/sota/object-detection-on-coco](https://paperswithcode.com/sota/object-detection-on-coco)
2. [https://docs.docker.com/engine/install/ubuntu/#install-using-the-convenience-script](https://docs.docker.com/engine/install/ubuntu/#install-using-the-convenience-script)
3. [https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/install-guide.html](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/install-guide.html)
4. [https://catalog.ngc.nvidia.com/orgs/nvidia/containers/pytorch/tags](https://catalog.ngc.nvidia.com/orgs/nvidia/containers/pytorch/tags)
5. [https://github.com/jsbroks/coco-annotator](https://github.com/jsbroks/coco-annotator)
6. Zaidi, Syed Sahil Abbas, et al. "A survey of modern deep learning based object detection models." *Digital Signal Processing*
 (2022): 103514.
7. Carion, Nicolas, et al. "End-to-end object detection with transformers." *European conference on computer vision*
. Springer, Cham, 2020.
8. Vision Transformer入門 2022年
9. [https://github.com/facebookresearch/detr](https://github.com/facebookresearch/detr)

## 弊社紹介
Daedalus株式会社では、多様な業界に人工知能技術を提供し、業務効率化・自動化を行っています。
最先端の技術を駆使してソリューションを提供することで、全ての企業と人に対し創造的な時間と金銭を創出します。 人々がより自分らしく生きる「余裕」を持てる世界を、私達は目指しています。

人工知能・機械学習を駆使して、社会を変革する志のある方を弊社は募集しています。
興味のある方は、下記お問い合わせフォームからご連絡ください。  
https://daedalus.co.jp/recruit/


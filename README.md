# ObjDetection
- Retina_Colab.ipynb <br/>
RetinaNet= Resnet + FPN<br/>
(Use CUDA 10.1 and upgrade torch, torchvision with pip because torchvision 0.8 is required for embed CoCo pretrained RetinaNet)

- Retina_Torch_VOC.ipynb <br/>
cpu컴 epoch5까지 돌고 pc다운<br/>
longtensor -> floattesnor에 xy넣어주고 run했는데 딥컴(rtx 2080): epoch0에서 pc 다운<br/>

- FasterRCNN_Colab.ipynb<br/>
Faster R-CNN, Mask data load -> Transfer learning ->  test (Torch) <br/>
-> tqdm에서 tensor인데 tesor넣으라는 에러.. <br/>
-> 전이학습aihub로 시켜보기<br/>

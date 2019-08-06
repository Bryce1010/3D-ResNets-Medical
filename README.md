# 3D-ResNets-Medical

- GroupNormalization(without pretrained)  
CUDA_VISIBLE_DEVICES=1 python main.py --root_path ./data --video_path kuoda_feihou_png --annotation_path medicine_01.json --result_path results --dataset medicine --model resnet --model_depth 101 --resnet_shortcut B --batch_size 16 --n_threads 0 --checkpoint 5 --n_classes 4 | tee output5.txt &

accuracy:  0.744
log: output5.txt 



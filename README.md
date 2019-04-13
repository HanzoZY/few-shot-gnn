# few-shot-gnn
tensorflow version 1.13  
python version 3.6  
only 'nn' option is usable  
The project is still in the process of improvement  
usage:CUDA_VISIBLE_DEVICES=5 python train.py --dataset omniglot --n 5 --k 1 --num_gcn_blocks 5  --hop 1 --lr 1e-3 --batch_size 64 --nn_option nn --label_cut yes

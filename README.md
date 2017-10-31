Robust Scene Text Recognition with Automatic Rectification
======================================

This software implements the Robust Scene Text Recognition with Automatic Rectification (SRN only) in pytorch.

Train for VGG text data
--------------
1. create a link to mnt folder
2. python data/create_mnt_list.py
3. python main.py --trainlist data/train_list.txt --vallist data/test_list.txt --cuda --adam --lr=0.001

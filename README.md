首先，在data/assets文件夹中添加mjcf_smplx文件夹，里面存放着smpl robot的相关文件，如果你有的话（doge
其次，进入ase文件夹，在命令行中运行如下指令
python --test--task HumanoidAMP --num_envs 512 --cfg_env data/cfg/humanoid.yaml --cfg_train data/cfg/train/rlg/amp_humanoid.yaml --motion_file data/motions/reference_motion.npy --checkpoint output/Humanoid_29-17-25-06/nn/Humanoid.pth
希望代码能够直接运行起来hhh

output文件加中共有2个训练结果：
Humanoid_29-04-21-18 为训练10000个epoch后的结果
Humanoid_29-17-25-06 为训练20000个epoch后的结果

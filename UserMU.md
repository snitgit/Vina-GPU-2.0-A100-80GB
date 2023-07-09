-$ git clone https://github.com/snitgit/Vina-GPU-2.0-A100-80GB.git
-$ cd Vina-GPU-2.0-A100-80GB/Vina-GPU+
-$ singularity shell --nv -B .:/workspace /shared/software/singularity/images/vina-gpu-2-plus.sif
singularity> /opt/Vina-GPU-2.0/Vina-GPU+/Vina-GPU  --config ./input_file_example/2bm2_config.txt

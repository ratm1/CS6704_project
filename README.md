## CS6704_project
1. AFL needs to be installed and execute. The link is https://github.com/google/AFL
2. Go to AFL_CROMU_00007/CROMU_00007/ and execute sudo bash -c "echo core > /proc/sys/kernel/core_pattern"
3. In the same folder execute ./afl-fuzz -i input -o out_test ./cromu_00007
4. The experiments with artificial neural networks are in https://colab.research.google.com/drive/1iDp79Bxm2jm3AK1X_GPxDs_Mid14zDlA?usp=sharing
5. In GoogleCollab "/content/drive/MyDrive/AFL_files". AFL_files is the folder that can be changed accordingly.

### Information
* CROMU_00007 is taken from https://github.com/mykter/afl-training and https://github.com/trailofbits/cb-multios
* The samples from Darpa Challenge are https://github.com/CyberGrandChallenge/samples/tree/master/examples/CROMU_00007

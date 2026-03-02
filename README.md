![](banner/tA.png)

### build guide?
```
# step 1, clone the kernel source
git clone https://github.com/eclipse-nun/moonstone.git -b theAperion
cd moonstone

# step 2, setup clang (recommand zyc clang 14 repo by EmanuelCN) - clone in home directory
git clone https://github.com/EmanuelCN/zyc_clang-14.git zyc-clang

# optional before build: setup defconfig
# configs is in: arch/arm64/configs

# step 3, build time!
bash build_kernel.sh

# build done? let's go to step 4: let it can flashable
# you can choose r4in and anykernel3
# copy Image output to r4in/ak3 directory and compress it.
# done fr:D

# i hope u build successfully and it can boot!
```

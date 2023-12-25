# ubuntu_learning

# 创建编译目录
mkdir build
cd build
# 执行cmake 生成 makefile
cmake ..
make
# 返回源码目录
cd ${OLDPWD}

cd到build文件夹，然后运行这个命令，可以清空编译目录
rm * -rf

编译提速(多线程编译)：
make -j8
# C-cli-homework-extra
For the first 5 questions which not in repo C-cli-homework



1. 找到在 Ubuntu 系统中可以用于计算文件内容 [MD5](https://www.jianshu.com/p/81c30781d4f7) 值的命令
   过于简单，暂无参考答案

   ```shell
   md5sum [filename]
   
   # example
   sudo touch test.txt
   md5sum test.txt
   ```

   

2. 找到在 Ubuntu 系统中可以用于比较两个文件的内容的差异的命令
   过于简单，暂无参考答案

   ```
   diff [file1] [file2]
   ```

   

3. 实现一个名为 `odd-or-even` 的 function，可以用来判断给其提供的第一个参数是奇数还是偶数，奇数时输出 `odd`，偶数时输出 `even`
   参考答案还未准备好

   ```shell
   #!/bin/bash
   Num=${1}
   if [ `expr ${Num} % 2` -eq 0 ]; then
   	echo "even"
   elif [ `expr ${Num} % 2` -eq 1 ]; then
   	echo "odd"
   else
   	echo "Invalid"
   fi
   ```

   

4. 实现一个名为 `next` 的脚本，当在 CLI 里执行 `$ next` （`$`为提示符，不需要输入）时就返回一个整数，第一次返回 1，每执行一次加 1
   参考答案还未准备好

5. 一个文件含有 N 行内容，每行的内容都是一个大于等于 0 的整数，无任何空行或其它内容，使用 [one-liner](https://onceupon.github.io/Bash-Oneliner/) 的形式对该文件中的数字求和
   参考答案还未准备好
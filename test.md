将要隐写的信息以二进制形式写入图片中,将test.txt的内容以二进制形式写入到a.jpg的末尾，形成新文件b.jpg
然后用winhex或者压缩文件查看图片的二进制内容，在末尾可以看到隐藏的内容，具体步骤：
一张图片（b.jpg），一个要隐写的txt文件(test.txt).360压缩工具，放在D盘。
把要隐藏的文件 test.txt用 360压缩。生成 test.zip 压缩包
打开命令提示符输入copy /b D:a.jpg + D:test.zip D:b.jpg
双击b.jpg的图片可以隐写后的图片
若要看到隐写的内容，打开360压缩对b解压缩选择文件-打开然后再文件类型里选择全部文件就可以得到原来的test.txt了

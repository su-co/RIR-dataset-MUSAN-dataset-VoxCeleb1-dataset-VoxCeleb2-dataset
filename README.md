# RIR dataset/MUSAN dataset/VoxCeleb1 dataset/VoxCeleb2 dataset下载
## 方式一：服务器脚本下载（推荐）
此方式提供md5校验
```
./download_data.sh
```
ps: 下载会获得多个分片，我们提供了提取、合并、转换语音格式的脚本
```
cd data
mkdir aac
python dataprep.py --save_path YOUR/DOWNLOAD/DATA/DIR --extract
python dataprep.py --save_path YOUR/DOWNLOAD/DATA/DIR --convert
```
如果你想要数据增强，运行下面脚本
```
python ./dataprep.py --save_path YOUR/DOWNLOAD/DATA/DIR --augment
```
## 方式二：VoxCeleb1/VoxCeleb2官网下载

- 在下面链接找到`Audio and video files`，点击`here`

```
https://mm.kaist.ac.kr/datasets/voxceleb/
```

- 填写表单，你会直接收到下载链接，如图

  ![image-20230426110029928](https://cdn.jsdelivr.net/gh/su-co/Image@main/img/image-20230426110029928.png)

## 方式三：VoxCeleb1/VoxCeleb2百度网盘下载
链接：https://pan.baidu.com/s/1Mx3Ps9IyL-bxfesGFvv5fQ
提取码：8qxb

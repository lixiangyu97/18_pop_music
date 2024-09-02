# 流行音乐节拍跟踪数据集 | Pop Music Beat Tracking Dataset

此仓库包含18首流行音乐的WAV格式数据集，专门用于节拍跟踪深度学习模型的训练与测试。  
This repository contains a dataset of 18 pop music tracks in WAV format, specifically prepared for training and testing deep learning models focused on beat tracking.

## 数据集概述 | Dataset Overview

- **音乐曲目**: 18首流行音乐。  
  **Music Tracks**: 18 pop music tracks.
- **格式**: WAV格式，采样率为44,100 Hz。  
  **Format**: WAV format with a sample rate of 44,100 Hz.
- **片段细节**: 每首音乐被手动分割成30秒的片段，取自每40秒中的第8到38秒。  
  **Segment Details**: Each track has been manually segmented into 30-second intervals, using the 8-38 second portion from each 40-second segment.
- **手动节拍标注**: 每首音乐经过三轮手动标注，取其平均值作为节拍参考。  
  **Manual Beat Annotation**: Each music track has undergone three rounds of manual beat annotation. The average of these annotations was calculated to provide a more accurate beat tracking reference.
- **节拍数据**: 节拍标注数据以TXT格式保存并上传至GitHub。  
  **Beat Data Format**: The beat annotations are stored in TXT format and uploaded to GitHub.
- **音乐上传**: 音乐文件存储在Google Drive中并未上传至GitHub。  
  **Music Upload**: The music files are stored on Google Drive and are not uploaded to GitHub.
- **节拍数据缺失**: 某些音乐的节拍数据因手动标注差异较大被删除。  
  **Missing Beat Data**: Beat data for some tracks was deleted due to significant differences found during manual annotation review.

## 用途 | Usage

该数据集可用于开发和测试节拍跟踪算法，特别是针对流行音乐的节拍检测。  
This dataset can be used for developing and testing beat tracking algorithms, particularly for detecting beats in pop music.

## 下载链接 | Download Link

音乐文件可以通过以下Google Drive链接下载：  
The music files can be downloaded from the following Google Drive link:  
[Google Drive Link](https://drive.google.com/drive/folders/1xH_kmExtwPw8CSXcrMXI7pS152BOj246?usp=sharing)

## 使用方法 | Usage Instructions

请将此数据集下载到本地后，根据您的需求将WAV文件输入到您的深度学习模型中进行训练或测试。可以使用现有的音频处理工具对数据集进行预处理，例如切分音频、转换格式或提取特征。  
Download the dataset locally, and then input the WAV files into your deep learning model for training or testing according to your needs. You can use existing audio processing tools to preprocess the dataset, such as segmenting the audio, converting formats, or extracting features.

## 许可证 | License

此数据集仅供学术研究使用，不得用于商业用途。  
This dataset is provided for academic research purposes only and may not be used for commercial purposes.

## 使用条款 | Terms of Use

请在使用这些数据前仔细阅读以下使用条款：  
Please read the following terms of use carefully before using this data:

- 本数据集仅限于学术研究和教育用途。  
  This dataset is limited to academic research and educational purposes only.
- 禁止将这些数据用于任何商业目的。  
  Commercial use of this data is prohibited.
- 如果您在研究中使用了这些数据，请引用此GitHub项目。  
  If you use this data in your research, please cite this GitHub project.
- **本数据集中的所有音乐版权归原作者所有。此数据集仅供研究和教育用途，不得用于商业用途。如果您在研究中使用此数据集，请务必遵守相关版权规定，并引用原作者。**  
  **All music in this dataset is copyrighted by the original authors. This dataset is provided for research and educational purposes only and may not be used for commercial purposes. If you use this dataset in your research, please comply with the relevant copyright regulations and cite the original authors.**

## 联系方式 | Contact Information

如果您有任何问题或需要进一步的信息，请通过以下方式联系我们：[lixiangyu97@sina.com]  
If you have any questions or need further information, please contact us at: [lixiangyu97@sina.com]

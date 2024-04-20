## 1.使用 `InternLM2-Chat-1.8B` 模型生成 300 字的小故事

![image-20240420174022721](C:\Users\97205\AppData\Roaming\Typora\typora-user-images\image-20240420174022721.png)

## 2.熟悉 `huggingface` 下载功能，使用 `huggingface_hub` python 包，下载 `InternLM2-Chat-7B` 的 `config.json` 文件到本地

1.安装hugging-face

```markdown
pip install -U huggingface_hub
```

2.下载congfig文件

```python
import os 
from huggingface_hub import hf_hub_download  # Load model directly 

hf_hub_download(repo_id="internlm/internlm2-7b", filename="config.json")
```

3.结果

![image-20240420174934518](C:\Users\97205\AppData\Roaming\Typora\typora-user-images\image-20240420174934518.png)

## 作业3，4因算力需求无法完成


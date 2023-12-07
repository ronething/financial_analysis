# 招商银行 pdf 流水提取分析工具

# usage

- modify `pdf_file_path = "/path/to/your/2023.pdf"`

```
pip(3) install -r req.txt
python(3) main.py
```

# ⚙️ 设置项说明

| 配置项       | 说明                                    |
|-----------|---------------------------------------|
| save_path | 导出文件的存储目录，可以写绝对路径或相对路径                |
| area      | pdf边距定义，[top, left, bottom, right] ， 一般不需要更改   |
| area1     | pdf第一页边距定义，[top, left, bottom, right]， 一般不需要更改 |

_此项目为本人学习Python所用，仅供个人学习使用_

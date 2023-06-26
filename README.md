# SwaggerAPIExtractor
这是一个Python脚本，用于从Swagger YAML文件中提取API信息并将其保存到Excel文件中。

安装依赖
在运行脚本之前，请确保已安装以下Python库：

pip install pyyaml openpyxl

将上述代码保存到一个名为api_extractor.py的文件中。

修改yaml_file_path变量，使其指向你的Swagger YAML文件。

运行脚本：

python api_extractor.py

脚本将创建一个名为output.xlsx的Excel文件，其中包含从Swagger YAML文件中提取的API信息。

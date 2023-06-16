# SwaggerAPIExtractor
Extract API information from Swagger file
使用方法
将您的Swagger YAML文件放置到合适的路径，例如path/to/your/swagger.yaml。
按照实际情况修改extract_api_info_to_excel.py中的yaml_file_path变量，使其指向Swagger YAML文件的路径。
（可选）修改excel_file_path变量以更改输出文件的路径。
运行脚本：
python extract_api_info_to_excel.py
脚本运行后，您可以在指定的路径（默认为output.xlsx）找到包含提取的API信息的Excel文件。
功能
从Swagger YAML文件中提取API接口路径、HTTP方法和操作ID。
将提取的API信息导出到Excel文件，方便查看和分析。

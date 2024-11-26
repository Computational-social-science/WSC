# WSC

1.data process
    读取文件，统一转换为json格式进行后续处理

2.x （生成评估指标excel，jfleg_data_all.xlsx）
    clone https://github.com/jlko/semantic_uncertainty
    替换semantic_uncertainty/semantic_uncertainty/uncertainty/models/huggingface_models.py

3.plot
    替换shap库中的force_matplotlib.py

4.rollback
# promotor_mlflow

参考说明详见2023.11.3.pptm



重要参数：

input_data：输入的txt文件名称，例：xxx.txt

device：cuda:gpu cpu:cpuz

特征集格式:

    data
        xxx.txt

xxx.txt格式：

    ATAGCAGCTTCTGAACTGGTTACCTGCCGTGAGTAAATTAAAATTTTATT （原有长度50的dna 序列，不含N）
    TAATTTTTATCTGTCTGTGCGCTATGCCTATATTGGTTAAAGTATTTAGT （优化设计后dna序列，)
    AATTAAAATTTTATTGACTTAGGTCACTAAATACTTTAACCAATATAGGC
    CATCAGTGGCAAATGCAGAACGTTTTCTGCGTGTTGCCGATATTCTGGAA

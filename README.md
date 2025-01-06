[![DOI](https://zenodo.org/badge/912572771.svg)](https://doi.org/10.5281/zenodo.14602650)

# Colab-CITATION.cff-Validator: 基於cffr套件的CITATION.cff驗證工具
A CITATION.cff validator based on the cffr package.

輸入 CFF 格式的檔案，例如 CITATION.cff，這個工具會使用 cffr套件驗證檔案的內容，並輸出驗證結果，以此確認 CITATION.cff 檔案是否符合規範。

This tool validates the content of CITATION.cff files (or other CFF formatted files) using the cffr package and outputs the validation results to ensure the file adheres to the specified format.

![](https://blogger.googleusercontent.com/img/a/AVvXsEhWuaTU-UNWe1pQw5hMZmvB1BELN6C03lQzlr-l-uYev44HjBoadTpNRLiKNVxM0AsWYOEfZYck_x2AWFW9lMWM8wpJsAjGLXLdK28mElnkEMvHkuKWcW1GY86E6UWThSYIb5Fi7TaxAUqhHP6HSgsLfcNiZC-aNCOn22OLEgbuv21U8XakE7j0Jg)

# Demo

https://colab.research.google.com/github/pulipulichen/Colab-CITATION.cff-Validator/blob/main/CITATION.cff%20Validator.ipynb

# Key Techniques

- **CFF (Citation Format File)**: 一種以 YAML 格式撰寫的檔案，用於儲存軟體引用資訊的標準格式。
- **YAML**: 一種人類可讀的資料序列化語言。
- **R**: 一種用於統計計算和圖形的程式語言及軟體環境。
- **cffr 套件**: 用於讀取及驗證 CITATION.cff 檔案的 R 套裝軟體。

# Citation

## APA 

Chen, Y.-T. (2025). *Colab-CITATION.cff-Validator* (Version 0.9.0) [Jupyter Notebook]. [https://doi.org/10.5281/zenodo.14602650](https://doi.org/10.5281/zenodo.14602650)

## BibTex

````
@software{
    Chen_Colab-CITATION_cff-Validator,
    author = {Chen, Yung-Ting},
    doi = {10.5281/zenodo.14602650},
    license = {GPL3},
    title = {{Colab-CITATION.cff-Validator}},
    url = {https://github.com/pulipulichen/Colab-CITATION.cff-Validator},
    version = {0.9.0}
}
````



# Reference

Hernangómez, D., (2021). cffr: Generate Citation File Format Metadata for R Packages. Journal of Open Source Software, 6(67), 3900, [https://doi.org/10.21105/joss.03900](https://doi.org/10.21105/joss.03900)
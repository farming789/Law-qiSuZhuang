conda create --name langchainLearn python=3.10
conda activate langchainLearn

pip install -r .\requirements.txt -i https://pypi.mirrors.ustc.edu.cn/simple/

streamlit run app.py
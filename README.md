# SX
scRNA
[单细胞转录时空转录20260413.ipynb](https://github.com/user-attachments/files/26697099/20260413.ipynb)
# 1. 克隆仓库
git clone https://github.com/SCCCCC-Collab/SX.git
cd SX

# 2. 将 notebook 文件放入仓库
# 先手动下载你的 .ipynb 文件，然后放进来
cp ~/Downloads/20260413.ipynb ./单细胞转录时空转录20260413.ipynb

# 3. 添加 .gitignore
echo -e "*.h5ad\n*.h5\n__pycache__/\n.ipynb_checkpoints/" > .gitignore

# 4. 提交
git add .
git commit -m "Add notebook and project structure"
git push

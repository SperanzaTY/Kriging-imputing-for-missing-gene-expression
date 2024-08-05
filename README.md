# Kriging-imputing-for-missing-gene-expression 运行说明
## 文件结构  
不改变文件夹内文件相对路径，直接运行notebook.ipynb即可。

## 相关依赖  
``` python
%pip install anndata
%pip install --upgrade h5py
%pip install numpy
%pip install scipy
%pip install pandas
%pip install matplotlib
%pip install pyvista --upgrade
%pip install trame --upgrade
%pip install vtk --upgrade
%pip install scikit-learn seaborn
%pip install magic-impute
%pip install scanpy
```

## 验收说明  
如果只是验收最终结果，请从大纲中找到"Kringing方法正确性验证"之后的内容，在确保上述依赖添加后运行可得到相关结果。  
前面代码为一些前期试错与探索工作。  

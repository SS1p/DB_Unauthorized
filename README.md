# DB_Unauthorized
基于unauthorized-check-master魔改优化

### 优化项：

1. **优化代码：**
    
    - `main.py` 使用了 `check_service` 函数，减少了重复的代码，通过传递函数指针来执行具体的检查逻辑。
2. **结果导出：**
    
    - 导出扫描结果到scan_results.txt。
3. **使用新的进度条和输出管理：**
    
    - 使用 `tqdm.write` 来输出结果，替换原始进度条，同时在结果前添加编号。

个贷违约预测 
=========== 
## Step 1 
将赛题原始数据集   
`test_public.csv`  
`train_internet.csv`  
`train_public.csv`  
手动添加至 `ori_data` 文件夹  
## Step 2 
运行`Modify_Data.ipynb`脚本  
生成修改过`early_return`字段的文件  
`test_public.csv`  
`train_internet.csv`  
`train_public.csv`  
保存至`data`文件夹中  
## Step 3 
运行`Main.ipynb`脚本  
生成中间文件`submission.csv`  
保存至`submit`文件夹中  
## Step 4 
运行`Add_Test2Train.ipynb`脚本  
生成`train_public.csv`扩展后的文件`new_train_public.csv`  
保存至`data`文件夹中  
## Step 5 
运行`Main-Modified.ipynb`脚本  
生成最终结果文件  
`final_submission.csv`  
保存至`submit`文件夹中  

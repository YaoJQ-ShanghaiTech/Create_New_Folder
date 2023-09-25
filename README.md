# Create_New_Folder
判断是否存在path文件夹，如果不存在就创建，如果存在就跳过



#### 该函数判断是否存在path文件夹，如果不存在就创建，如果存在就跳过

`def mkdir(path):`
`    folder = os.path.exists(path)`
`    if not folder:                   # 判断是否存在文件夹如果不存在则创建为文件夹`
`	os.makedirs(path)            # makedirs 创建文件时如果路径不存在会创建这个路径`
`    else:
	print("文件夹已存在，无需创建")`


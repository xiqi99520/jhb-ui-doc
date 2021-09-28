# Tabs 标签页

分隔内容上有关联但属于不同类别的数据集合

## 基础用法

```html
	<JHB-tabs v-model="activeName" @tab-click="handleClick">
		<el-tab-pane label="用户管理" name="first">用户管理</el-tab-pane>
		<el-tab-pane label="配置管理" name="second">配置管理</el-tab-pane>
		<el-tab-pane label="角色管理" name="third">角色管理</el-tab-pane>
		<el-tab-pane label="定时任务补偿" name="fourth">定时任务补偿</el-tab-pane>
	</JHB-tabs>

	<JHB-tabs v-model="activeName" size="small" @tab-click="handleClick">
		<el-tab-pane label="用户管理" name="first">用户管理</el-tab-pane>
		<el-tab-pane label="配置管理" name="second">配置管理</el-tab-pane>
		<el-tab-pane label="角色管理" name="third">角色管理</el-tab-pane>
		<el-tab-pane label="定时任务补偿" name="fourth">定时任务补偿</el-tab-pane>
	</JHB-tabs>
```

## 卡片式

```html
	<JHB-tabs v-model="activeName" type="card" @tab-click="handleClick">
		<el-tab-pane label="用户管理" name="first">用户管理</el-tab-pane>
		<el-tab-pane label="配置管理" name="second">配置管理</el-tab-pane>
		<el-tab-pane label="角色管理" name="third">角色管理</el-tab-pane>
		<el-tab-pane label="定时任务补偿" name="fourth">定时任务补偿</el-tab-pane>
	</JHB-tabs>

	<JHB-tabs v-model="activeName" size="small"  type="card" @tab-click="handleClick">
		<el-tab-pane label="用户管理" name="first">用户管理</el-tab-pane>
		<el-tab-pane label="配置管理" name="second">配置管理</el-tab-pane>
		<el-tab-pane label="角色管理" name="third">角色管理</el-tab-pane>
		<el-tab-pane label="定时任务补偿" name="fourth">定时任务补偿</el-tab-pane>
	</JHB-tabs>
```
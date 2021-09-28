# Result 结果

用于对用户的操作结果或者异常状态做反馈

## 基础用法

```html
	<JHB-result icon="success" title="成功提示" subTitle="请根据提示进行操作">
		<template slot="extra">
		  <el-button type="primary" size="mini">返回</el-button>
		</template>
	</JHB-result>

	<JHB-result icon="warning" title="警告提示" subTitle="请根据提示进行操作">
		<template slot="extra">
		  <el-button type="primary" size="mini">返回</el-button>
		</template>
	</JHB-result>

	<JHB-result icon="error" title="错误提示" subTitle="请根据提示进行操作">
		<template slot="extra">
		  <el-button type="primary" size="mini">返回</el-button>
		</template>
	</JHB-result>

	<JHB-result icon="info" title="信息提示" subTitle="请根据提示进行操作">
		<template slot="extra">
		  <el-button type="primary" size="mini">返回</el-button>
		</template>
	</JHB-result>
```

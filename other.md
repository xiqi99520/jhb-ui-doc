# 其他标签集合

暂未分类

## Pagination

```html
	<JHB-pagination @size-change="handleSizeChange" @current-change="handleCurrentChange" :current-page.sync="currentPage1" :page-size="10" :page-sizes="[10, 20, 30, 40]" layout="total,sizes, prev, pager, next" :total="100"></JHB-pagination>
```

## Color Picker

```html
	<JHB-color-picker v-model="color1"> </JHB-color-picker>
```

## Rate

```html
	<JHB-rate v-model="value2" allow-half text-color="#FFBF47" disabled-void-color="red"></JHB-rate>
```

## Badge

```html
	<JHB-badge :value="12">
		<el-button>评论</el-button>
	</JHB-badge>

	<JHB-badge :value="200" :max="99">
		<el-button>评论</el-button>
	</JHB-badge>

	<JHB-badge value="new">
		<el-button>评论</el-button>
	</JHB-badge>

	<JHB-badge is-dot>
		<el-button>数据查询</el-button>
	</JHB-badge>
```

## Progress

```html
	<JHB-progress :percentage="69"></JHB-progress>
	<JHB-progress :percentage="100" status="success"></JHB-progress>
	<JHB-progress :percentage="100" status="warning"></JHB-progress>
	<JHB-progress :percentage="50" status="exception"></JHB-progress>
```

## Slider

```html
	<JHB-slider v-model="value3"></JHB-slider>

	<JHB-slider v-model="value4"></JHB-slider>

	<JHB-slider v-model="value5" range show-stops :max="10"> </JHB-slider>
```

## steps

```html
	<JHB-steps :active="2" align-center finish-status="success">
		<el-step title="步骤01" description="这是一段很长很长很长的描述性文字"></el-step>
		<el-step title="步骤02" description="这是一段很长很长很长的描述性文字"></el-step>
		<el-step title="步骤03" description="这是一段很长很长很长的描述性文字"></el-step>
		<el-step title="步骤04" description="这是一段很长很长很长的描述性文字"></el-step>
	</JHB-steps>

	<JHB-steps direction="vertical" :active="2" align-center finish-status="success">
		<el-step title="步骤01" description="这是一段很长很长很长的描述性文字"></el-step>
		<el-step title="步骤02" description="这是一段很长很长很长的描述性文字"></el-step>
		<el-step title="步骤03" description="这是一段很长很长很长的描述性文字"></el-step>
		<el-step title="步骤04" description="这是一段很长很长很长的描述性文字"></el-step>
	</JHB-steps>
```

## Timeline

```html
	<JHB-timeline :reverse="reverse">
		<el-timeline-item v-for="(activity, index) in activities" :key="index" :timestamp="activity.timestamp">
			{{ activity.content }}
		</el-timeline-item>
	</JHB-timeline>

	<JHB-timeline>
		<el-timeline-item timestamp="2018/4/12" placement="top">
			<el-card>
				<h4>更新 Github 模板</h4>
				<p>王小虎 提交于 2018/4/12 20:46</p>
			</el-card>
		</el-timeline-item>
		<el-timeline-item timestamp="2018/4/3" placement="top">
			<el-card>
				<h4>更新 Github 模板</h4>
				<p>王小虎 提交于 2018/4/3 20:46</p>
			</el-card>
		</el-timeline-item>
		<el-timeline-item timestamp="2018/4/2" placement="top">
			<el-card>
				<h4>更新 Github 模板</h4>
				<p>王小虎 提交于 2018/4/2 20:46</p>
			</el-card>
		</el-timeline-item>
	</JHB-timeline>
```

## Card

```html
	<JHB-card :body-style="{ padding: '0px' }">
		<div style="padding: 14px;display: flex;align-items: center;">
		<img src="https://shadow.elemecdn.com/app/element/hamburger.9cf7b091-55e9-11e9-a976-7f4d0b07eef6.png" class="image-small-right" />
			<div class="content" style="padding-left: 8px;">
				<span>主标题文字</span>
			<div>辅助文字</div>
			</div>
		</div>
	</JHB-card>
	
	<JHB-card :body-style="{ padding: '0px' }">
		<div class="content" style="padding: 16px;">
			<img src="https://shadow.elemecdn.com/app/element/hamburger.9cf7b091-55e9-11e9-a976-7f4d0b07eef6.png" class="image-small" />
			<span>主标题文字</span>
			<div>辅助文字或者描述性文字都可以</div>
		</div>
	</JHB-card>
	
	<JHB-card :body-style="{ padding: '0px' }">
		<img src="https://shadow.elemecdn.com/app/element/hamburger.9cf7b091-55e9-11e9-a976-7f4d0b07eef6.png" class="image" />
		<div class="content" style="padding: 16px;">
			<span>主标题文字</span>
			<div>辅助文字或者描述性文字都可以</div>
		</div>
	</JHB-card>
```

## Tooltip

```html
	<el-tooltip class="item" effect="dark" content="Top Left 提示文字" placement="top">
		<el-button>top</el-button>
	</el-tooltip>

	<el-tooltip class="item" effect="dark" content="Top Left 提示文字" placement="left">
		<el-button>left</el-button>
	</el-tooltip>

	<el-tooltip class="item" effect="dark" content="Top Left 提示文字" placement="right">
		<el-button>right</el-button>
	</el-tooltip>

	<el-tooltip class="item" effect="dark" content="Top Left 提示文字" placement="bottom">
		<el-button>bottom</el-button>
	</el-tooltip>
```


## Upload

```html
	<JHB-upload class="avatar-uploader" action="https://jsonplaceholder.typicode.com/posts/" :show-file-list="false" :on-success="handleAvatarSuccess" :before-upload="beforeAvatarUpload">
		<img v-if="imageUrl" :src="imageUrl"  class="avatar" />
		<div class="avatar-uploader-icon" v-else>
			<i class="el-icon-plus"></i>
			<span>上传图片</span>
		</div>
	</JHB-upload>
	
	<JHB-upload class="avatar-uploader disabled" action="https://jsonplaceholder.typicode.com/posts/" :show-file-list="false" :on-success="handleAvatarSuccess" :before-upload="beforeAvatarUpload">
		<img v-if="imageUrl" :src="imageUrl" class="avatar" />
		<div class="avatar-uploader-icon" v-else>
			<i class="el-icon-plus"></i>
			<span>上传图片</span>
		</div>
	</JHB-upload>
```
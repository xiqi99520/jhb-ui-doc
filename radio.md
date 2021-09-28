# Radio 单选框

在一组备选项中进行单选

## 基础使用

```html
	<JHB-radio v-model="radio1" label="1" @change="radioChange">已选</JHB-radio>
	<JHB-radio v-model="radio1" label="2">未选</JHB-radio>
	<JHB-radio v-model="radio2" label="1" disabled>已选-禁用</JHB-radio>
	<JHB-radio v-model="radio2" label="2" disabled>未选-禁用</JHB-radio>
```

## 带边框

```html
	<JHB-radio v-model="radio5" label="1" border>已选</JHB-radio>
	<JHB-radio v-model="radio5" label="2" border>未选</JHB-radio>
	<JHB-radio v-model="radio4" label="1" disabled border>已选-禁用</JHB-radio>
	<JHB-radio v-model="radio4" label="2" disabled border>未选-禁用</JHB-radio>
```

## radio实现tab切换效果

```html
	<JHB-radio-group v-model="radio3" @change="groupChange">
		<JHB-radio-button label="上海"></JHB-radio-button>
		<JHB-radio-button label="北京"></JHB-radio-button>
		<JHB-radio-button label="广州"></JHB-radio-button>
		<JHB-radio-button label="深圳"></JHB-radio-button>
	</JHB-radio-group>
```
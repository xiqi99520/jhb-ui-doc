# Checkbox 多选框

一组备选项中进行多选

## 基础使用

```html
	<JHB-checkbox v-model="radio1">已选</JHB-checkbox>
	<JHB-checkbox v-model="radio2">未选</JHB-checkbox>
	<JHB-checkbox v-model="radio1" disabled>已选--禁止</JHB-checkbox>
	<JHB-checkbox v-model="radio2" disabled>未选--禁止</JHB-checkbox>
	<JHB-checkbox v-model="radio1" :indeterminate="indeterminate">全选</JHB-checkbox>
```

## 带边框

```html
	<JHB-checkbox v-model="radio1" border>已选</JHB-checkbox>
	<JHB-checkbox v-model="radio2" border>未选</JHB-checkbox>
	<JHB-checkbox v-model="radio1" disabled border>已选--禁止</JHB-checkbox>
	<JHB-checkbox v-model="radio2" disabled border>未选--禁止</JHB-checkbox>
```

## checkbox实现tab多选效果

```html
	<JHB-checkbox-group v-model="checkboxGroup1" size="small">
		<JHB-checkbox-button v-for="city in cities" :label="city" :key="city">城市</JHB-checkbox-button>
	</JHB-checkbox-group>
```


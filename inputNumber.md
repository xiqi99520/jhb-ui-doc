# InputNumber 计数器

仅允许输入标准的数字值，可定义范围

## 样式1

```html
	<JHB-input-number v-model="num1" size="small" controls-position="right" @change="handleChange" ontrolsIconType="updown" :min="1" :max="10" label="描述文字"></JHB-input-number>

	<JHB-input-number v-model="num1" error size="small" controls-position="right" @change="handleChange" ontrolsIconType="updown" :min="1" :max="10" label="描述文字"></JHB-input-number>

	<JHB-input-number v-model="num1" disable size="small" controls-position="right" @change="handleChange" ontrolsIconType="updown" :min="1" :max="10" label="描述文字"></JHB-input-number>
```

## 样式2

```html
	<JHB-input-number v-model="num1" size="small"  @change="handleChange" ontrolsIconType="updown" :min="1" :max="10" label="描述文字"></JHB-input-number>

	<JHB-input-number v-model="num1" error size="small" @change="handleChange" ontrolsIconType="updown" :min="1" :max="10" label="描述文字"></JHB-input-number>

	<JHB-input-number v-model="num1" disable size="small" @change="handleChange" ontrolsIconType="updown" :min="1" :max="10" label="描述文字"></JHB-input-number>
```

## 样式3

```html
	<JHB-input-number v-model="num1" size="small"  @change="handleChange" :min="1" :max="10" label="描述文字"></JHB-input-number>

	<JHB-input-number v-model="num1" error size="small" @change="handleChange" :min="1" :max="10" label="描述文字"></JHB-input-number>

	<JHB-input-number v-model="num1" disable size="small" @change="handleChange" :min="1" :max="10" label="描述文字"></JHB-input-number>
```
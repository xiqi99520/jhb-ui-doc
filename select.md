# Select 选择器

当选项过多时，使用下拉菜单展示并选择内容

## 基本使用

```html
	<JHB-select placeholder="请选择" v-model="value">
		<el-option v-for="item in options" :key="item.value" :label="item.label" :value="item.value" :disabled="item.disabled"></el-option>
	</JHB-select>

	<JHB-select v-model="value" placeholder="请选择" @input="handleInput1" @focus="handlefocus1" @change="handleChange1" @blur="handleblur1" @clear="handleClear1"></JHB-select>

	<JHB-select disabled v-model="value" placeholder="请选择" @input="handleInput1" @focus="handlefocus1" @change="handleChange1" @blur="handleblur1" @clear="handleClear1"></JHB-select>
```

## 带输入框搜索

```html
	<JHB-select filterable v-model="value" placeholder="请选择" @input="handleInput1" @focus="handlefocus1" @change="handleChange1" @blur="handleblur1" @clear="handleClear1"></JHB-select>

	<JHB-select filterable disabled v-model="value" placeholder="请选择" @input="handleInput1" @focus="handlefocus1" @change="handleChange1" @blur="handleblur1" @clear="handleClear1"></JHB-select>
```

## 带错误提示和多选

```html
	<JHB-select v-model="value1" multiple filterable allow-create default-first-option error :required="required" :tipTitle="tipTitle" placeholder="请输入内容" @input="handleInput1" @focus="handlefocus1" @change="handleChange1" @blur="handleblur1" @clear="handleClear1">
        <el-option v-for="item in options" :key="item.value" :label="item.label" :value="item.value"></el-option>
    </JHB-select>
```

## 级联选项

```html
	<JHB-cascader v-model="value4" :options="options4" placeholder="请选择" @input="handleInput1" @focus="handlefocus1" @change="handleChange1" @blur="handleblur1" @clear="handleClear1"></JHB-cascader>
```
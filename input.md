# Input 输入框

通过鼠标或键盘输入字符

## 基础用法

```html
	<JHB-input type="text" v-model="value1" maxlength="20" tipTitle="请输入内容" show-word-limit placeholder="请输入内容" @input="handleInput1"  @focus="handlefocus1" @change="handleChange1" @blur="handleblur1" @clear="handleClear1"></JHB-input>

	<JHB-input type="text" v-model="value1" maxlength="20" tipTitle="请输入内容" show-word-limit error placeholder="请输入内容" @input="handleInput1"  @focus="handlefocus1" @change="handleChange1" @blur="handleblur1" @clear="handleClear1"></JHB-input>

	<JHB-input type="text" v-model="value1" maxlength="20" tipTitle="请输入内容" show-word-limit disabled placeholder="请输入内容" @input="handleInput1"  @focus="handlefocus1" @change="handleChange1" @blur="handleblur1" @clear="handleClear1"></JHB-input>
```

## 文本域

```html
	<JHB-input type="textarea" v-model="inputvalue1" maxlength="20" :required="required" :tipTitle="tipTitle" show-word-limit placeholder="请输入内容" @input="handleInput1" @focus="handlefocus1" @change="handleChange1" @blur="handleblur1" @clear="handleClear1"></JHB-input>

	<JHB-input type="textarea" v-model="inputvalue1" maxlength="20" :required="required" :tipTitle="tipTitle" show-word-limit error placeholder="请输入内容" @input="handleInput1" @focus="handlefocus1" @change="handleChange1" @blur="handleblur1" @clear="handleClear1"></JHB-input>

	<JHB-input type="textarea" v-model="inputvalue1" maxlength="20" :required="required" :tipTitle="tipTitle" show-word-limit disable placeholder="请输入内容" @input="handleInput1" @focus="handlefocus1" @change="handleChange1" @blur="handleblur1" @clear="handleClear1"></JHB-input>
```

## 密码框

```html
	<JHB-input show-password v-model="inputvalue1" maxlength="20" :required="required" :tipTitle="tipTitle" clearable show-word-limit placeholder="请输入内容" @input="handleInput1" @focus="handlefocus1" @change="handleChange1" @blur="handleblur1" @clear="handleClear1"></JHB-input>

	<JHB-input show-password v-model="inputvalue1" maxlength="20" :required="required" :tipTitle="tipTitle" clearable show-word-limit error placeholder="请输入内容" @input="handleInput1" @focus="handlefocus1" @change="handleChange1" @blur="handleblur1" @clear="handleClear1"></JHB-input>

	<JHB-input show-password v-model="inputvalue1" maxlength="20" :required="required" :tipTitle="tipTitle" clearable show-word-limit disable placeholder="请输入内容" @input="handleInput1" @focus="handlefocus1" @change="handleChange1" @blur="handleblur1" @clear="handleClear1"></JHB-input>
```

## 带搜索图标

```html
	<JHB-input type="text" v-model="inputvalue1" prefix-icon="el-icon-search" maxlength="20" :required="required" :tipTitle="tipTitle" clearable show-word-limit placeholder="请输入内容" @input="handleInput1" @focus="handlefocus1" @change="handleChange1" @blur="handleblur1" @clear="handleClear1"></JHB-input>

	<JHB-input type="text" v-model="inputvalue1" prefix-icon="el-icon-search" maxlength="20" error :required="required" :tipTitle="tipTitle" clearable show-word-limit placeholder="请输入内容" @input="handleInput1" @focus="handlefocus1" @change="handleChange1" @blur="handleblur1" @clear="handleClear1"></JHB-input>

	<JHB-input type="text" v-model="inputvalue1" prefix-icon="el-icon-search" maxlength="20" disable :required="required" :tipTitle="tipTitle" clearable show-word-limit placeholder="请输入内容" @input="handleInput1" @focus="handlefocus1" @change="handleChange1" @blur="handleblur1" @clear="handleClear1"></JHB-input>
```
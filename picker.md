# Picker 选择器

多种弹出模式（时间模式、地区模式、单列模式、多列模式）

## 模式一

```html
	<JHB-time-select v-model="value" :picker-options="{ start: '08:30', step: '00:15', end: '18:30' }" placeholder="选择时间"></JHB-time-select>
      
	<JHB-time-select disabled v-model="datetime" placeholder="请选择" ></JHB-time-select>
```

## 模式二

```html
	<JHB-time-picker v-model="value1" :picker-options="{ selectableRange: '18:30:00 - 20:30:00' }" placeholder="任意时间点"></JHB-time-picker>
     
	<JHB-time-picker disabled v-model="value1" :picker-options="{ selectableRange: '18:30:00 - 20:30:00' }" placeholder="任意时间点"></JHB-time-picker>
```

## 模式三

```html
	<JHB-time-picker is-range v-model="value3" range-separator="至" start-placeholder="开始时间" end-placeholder="结束时间" placeholder="选择时间范围"></JHB-time-picker>

	<JHB-time-picker is-range disabled v-model="value3" range-separator="至" start-placeholder="开始时间" end-placeholder="结束时间" placeholder="选择时间范围"></JHB-time-picker>
```

## 模式四

```html
	<jhb-date-picker type="date" v-model="datetime"  placeholder="选择日期" @change="changeblur"></JHB-date-picker>
	
	<JHB-date-picker type="date" v-model="value4" placeholder="选择日期" disabled ></JHB-date-picker>
```

## 模式五

```html
	<JHB-date-picker v-model="value5" type="daterange" range-separator="至" start-placeholder="开始日期" end-placeholder="结束日期"></JHB-date-picker>

	<JHB-date-picker v-model="value6" disabled type="daterange" range-separator="至" start-placeholder="开始日期" end-placeholder="结束日期"></JHB-date-picker>
```
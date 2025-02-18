---
title: Bar
order: 3
---

### Plot Container

`markdown:docs/common/chart-options.en.md`

### Data Mapping

#### data

<description>**required** _array object_</description>

Configure the data source. The data source is a collection of objects. For example:`[{ time: '1991'，value: 20 }, { time: '1992'，value: 20 }]`。

`markdown:docs/common/xy-field.en.md`

#### seriesField

<description>**optional** _string_</description>

Grouping field. It is the same meaning as groupField、colorField in Grouped Bar, and the same as stackField、colorField in Stacked Bar.

#### groupField

<description>**optional** _string_</description>

Grouping field for Stacked Bar and Grouped Bar. Its priority is higher than seriesField. When isGroup is `true`, the data will be grouped by `groupField`.

#### isGroup

<description>**optional** _boolean_</description>

Whether the plot is Grouped Bar.

#### isStack

<description>**optional** _boolean_</description>

Whether the plot is Stacked Bar.

#### isRange

<description>**optional** _boolean_</description>

Whether the plot is Range Bar.

#### isPercent

<description>**optional** _boolean_</description>

Whether the plot is Percent Bar. When isPercent is `true`, isStack must be `true`.

#### meta

`markdown:docs/common/meta.en.md`

### Graphic Style

`markdown:docs/common/color.en.md`

#### pattern ✨

<description>**optional** _object | Function_</description>

`markdown:docs/common/pattern.en.md`

`markdown:docs/common/bar-style.en.md`

#### barWidthRatio

<description>**optional** _number_</description>

The ratio of bar width( Range:[0-1] ).

#### marginRatio

<description>**optional** _number_</description>

The ratio of spacing between columns in groups( Range:[0-1] ), only for Grouped Bar.

#### shape

<description>**可选** _string_</description>

内置 shape 类型有：`hollow-rect`, `tick`; 此外，还可以搭配 [`registerShape`](https://g2.antv.vision/zh/docs/api/advanced/register-shape) 进行自定义使用. 

[Demo](/zh/examples/bar/basic#shape)

#### state

<description>**optional** _object_</description>

`markdown:docs/common/state-style.en.md`

### Plot Components

`markdown:docs/common/common-component.zh.md`

#### Slider

`markdown:docs/common/slider.zh.md`

#### Scrollbar

`markdown:docs/common/scrollbar.zh.md`

#### Conversion Tag

Applicable to base bar charts and base bar charts, the Conversion Rate component allows the user to focus on the rate of change in the data.

`markdown:docs/common/conversion-tag.en.md`

#### Connected Area

`markdown:docs/common/connected-area.en.md`

### Plot Event

`markdown:docs/common/events.en.md`

### Plot Method

`markdown:docs/common/chart-methods.en.md`

### Plot Theme

`markdown:docs/common/theme.en.md`

### Plot Interactions

Built-in interactions of scatter are as follows:

| Interaction | Description                              | Configuration                  |
| ----------- | ---------------------------------------- | ------------------------------ |
| brush | 用于刷选交互，配置该交互后，可进行刷选。 | `brush: { enabled: true }` |

`markdown:docs/common/brush.en.md`

`markdown:docs/common/interactions.en.md`

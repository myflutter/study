## flutter 组件
1.flutter组件按照是否包含子组件可分为单个子组件和多个子组件
### Container 使用注意点
1.Container容器组件若无固定大小，大小由该容器的子组件宽高决定，若无子组件，该组件大小占满父组件
### Row 使用注意点
1.Row布局组件默认水平占满父组件，垂直方向随其子组件的大小而变化
### Column 使用注意点
1.Column布局组件默认垂直占满父组件，水平方向随其子组件的大小而变化
### Flex 使用注意点
1.Flex弹性布局组件大小由其direction和children决定
### Stack 使用注意点
1.Stack堆叠布局组件大小由fix属性决定是否占满父组件，StackFix,expand表示占满父组件，StackFix.loose表示以子组件的大小决定Stack组件的大小
2.设置了Stack的fit值，其子组件设置宽高是无效的，一般跟position结合使用，与web前端开发中德绝对定位相似
### ListView使用注意点
1.ListView列表组件与Column混用时，会报没有高度的错误

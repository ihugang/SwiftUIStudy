# SwiftUIStudy
SwiftUI 学习与代码示例

## 属性修饰器 PropertyWrapper

### @State 
view绑定的相关变量，属性变化时，触发view更新，建议private，View 中的私有状态值，不能为其它view使用。
### @Binding
视图的属 性传递至 子视图，默认传递值，@Binding修饰后，传递引用类型，当值发送变化，子视图自动更新 传递时用$前缀来传递。
### @EnvironmentObject
全局环境传递变量 .environmentObject(x) ，在子视图里 @EnvironmentObject 声明即可引用。
### Environment
swiftUI 本身的系统级别的设定，通过@Environment 来获取。
### @ObservedObject 
修饰对象，对象需要实现ObservableObject协议，然后用Published 修饰对象属性，属性会被监听，变化引起UI更新。

## List

## View及相互调用 

## Navigation

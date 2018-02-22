macOS-pod-template
============

### 使用方法:
 ```ruby
 pod lib create YourLibrary --template-url="https://github.com/Alexiuce/mac-pod-template.git" 
 ```
### 使用注意 (pay attention) 
   - Swift的类和方法,需要使用public 关键字进行声明,才可以在项目测试工程使用!!!   
   a Swift library needs to have its classes declared as public for you to see them in your example library.

## Requirements:

- CocoaPods 1.0.0+

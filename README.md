# libminipng
通过lodepng解析png图片，使用pngquant算法进行压缩的swift-framework

pngquant:https://github.com/ImageOptim/libimagequant

lodepng:https://github.com/lvandeve/lodepng

### 快速使用

1、编译生成`libminipng.framework`

2、项目引入`libminipng.framework`

3、编写代码：
```swift
        import libminipng
        let path:String = "/Users/mleo/Downloads/Cloud.png"
        let data:Data? = minipng.path2Data(path)
```
  

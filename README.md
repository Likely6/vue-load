# vue-loading
loading
loading组件

npm install --save vue-load
import Loading from 'vue-load'
components: {Loading}

props:
    url //加载图标的地址
    width/height //图标宽高
    text //文本
    position:top|bottom //文本相对于图标位置
    textStyle:{color:'#ccc'} //文本样式
  
methods:
  show()
  hide()

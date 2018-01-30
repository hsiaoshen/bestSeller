# 进度，技术和问题解决

## 2018-1-30

### 进度


### 问题

1. 使用icont和span时如何居中?

```html
      <div class="templatedown" id="infoTempDown">
        <i class="iconfont icon-downloadfill icon"></i><span class="span">设备信息模板下载</span>
      </div>
```
```css
.templatedown{
    /*width: 100%;*/
    height: 3rem;
    clear: both;

}
.templatedown .icon{
    display:inline-block;
    height: 3rem;
    font-size: 3rem;     
    float: left;
    cursor: pointer;                    
}
.templatedown,.span{    
    font-size: 12px;   
    line-height: 3rem;    
    float: left;
    cursor: pointer;              
}
```


### 技术

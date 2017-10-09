# x-password

一个基于jQuery、用于显示和隐藏密码框和显示密码强度的插件

## 依赖

jQuery

## 使用手册

1、初始化参数

<table>
   <tr>
       <th>参数名</th>
       <th>类型</th>
       <th>默认值</th>
       <th>含义</th>
   </tr>
   <tr>
       <td>strength</td>
       <td>boolean</td>
       <td>false</td>
       <td>是否显示密码强度</td>
   </tr>
   <tr>
       <td>pattern</td>
       <td>object</td>
       <td>
           {
          
            level0:/^[a-zA-Z]{6,}$/,
          
            level01:/^[0-9]{6,}$/,
            
            level1:/^(?=.*?[a-z])(?=.*?[0-9]).{7,}$/,
            
            level2:/^(?=.*?[A-Z])(?=.*?[a-z])(?=.*?[0-9]).{10,}$/,
            
            level3:/^(?=.*?[A-Z])(?=.*?[a-z])(?=.*?[0-9])(?=.*?[^\w\s]).{7,}$/,
         
            level4:/^(?=.*?[A-Z])(?=.*?[a-z])(?=.*?[0-9])(?=.*?[^\w\s]).{10,}$/ 
            
            }
          
  </td>
       <td>用于判断密码强度的正则表达式</td>
   </tr>
   <tr>
       <td>iconPrefix</td>
       <td>String</td>
       <td>iconfont</td>
       <td>用于显示图标的字体文件的前缀</td>
   </tr>
   <tr>
       <td>iconOpenEye</td>
       <td>String</td>
       <td>icon-open-eye</td>
       <td>显示密码的图标字体类名</td>
   </tr>
   <tr>
       <td>iconCloseEye</td>
       <td>String</td>
       <td>icon-close-eye</td>
       <td>隐藏密码的图标字体类名</td>
   </tr>
</table>

## 用法：

$(selector).xPassword();

## 演示

请下载demo文件夹



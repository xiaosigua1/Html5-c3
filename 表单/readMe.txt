 常见的表单元素：
   文本框        type="text"    默认值
   密码框        type="password"
   单选按钮      type="radio"
            <input type="radio" name="sex" value="男">男
            <input type="radio" name="sex" value="女">女<br/>
          name属性值必须一致！否则会都能选择！
         value属性值必须设置！否则后台无法获取属性值！
         后台只能获取一个值！

   复选框        type="checkbox"
     name属性值必须一致！否则会都能选择！
     value属性值必须设置！否则后台无法获取属性值！
     后台获取时，需要做非空验证！

     单选按钮和 复选框 默认被选中使用checked

   列表框        type="select"
       默认被选中,在option中使用selected


   按钮          type="button"  普通按钮   只是一个按钮 后面学了js可以绑定事件
                 type="reset"   重置按钮   把表单中所有的元素内容变为初始值
                 type="submit"  提交按钮   会把表单中的所有内容提交到服务器

   多行文本域     type="textarea"
   邮箱          type="email"
   数字          type="number"
   滑块          type="range"
   搜索          type="search"
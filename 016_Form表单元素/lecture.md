Form表单元素

文本框
文本域通过<input type="text">标签来设定，当用户要在表单中键入字幕数字等时，就会用到文本域
例如
<form>
   First name: <input type="text" name=firstname>
   <br>
   Last name: <input type="text" name="lastname">
</form>



密码框
密码字段通过 <input type="password">标签来设定
<form>
   First name: <input type="text" name=firstname>
   <br>
   Last name: <input type="text" name="lastname">
   <br>
   Password: <input type="password" name=“pwd”>
</form>

密码字段不会明文显示，而是以星号或者圆点提到


提交按钮
当用户单击确认按钮时，表单的内容会被传送到另一个文件。表单的动作属性定义了目的文件的文件名。由动作属性定义的这个文件通常会对接受到的输入数据进行相关的处理
<form name="input" action="url" method="get">
    Username: <input type="text" name="user">
    <input type="submit" value="Submit">
</form>

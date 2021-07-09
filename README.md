# jdbc-learning

#  font 类,导入java.awt,主函数缺失

## java frame 框架,java  UI, native UI,frame.setVisible (true)
_for  search + why  frame   setvisible  is  true  by default_

And remember when you add components to a visible GUI the components will not appear anyway because you need to invoke the layout manager to layout all the components. So even if the frame was visible automatically, in this case you would still need to invoke frame.validate() to make sure the components are layed out properly.

记住，当您向可见的 GUI 添加组件时，组件不会出现，因为您需要调用布局管理器来布局所有组件。因此，即使框架是自动可见的，在这种情况下，您仍然需要调用 frame.validate ()来确保组件被正确排出。

I think it is a better design to add all the components and then make it visibile once you have finished adding everything to the frame. This way you only layout the components once, not after every component is added. Maybe with other languages that use absolute sizes and positioning this is not a big deal because they don't have the concept of layout managers.

我认为这是一个更好的设计，添加所有的组件，然后使它可见一旦你已经完成添加到框架的一切。这样，您只需要布局组件一次，而不是在添加每个组件之后。也许对于其他使用绝对大小和定位的语言来说，这没什么大不了的，因为他们没有布局管理器的概念。


#  java  柱状图与折线图

_参考链接  https://blog.csdn.net/starter_____/article/details/78827506_


** 是什么 **
    每当公司要建立一个新项目时，我们都需要从头开始搭建项目结构，经历过几次之后就不难发现，各个项目之间其实有很多相同的模块（如http、对话框等）。
    因此没必要每次新建项目的时候都重写一遍它们。
    虽然使用网上的各类开源库、代码可以帮我们快速的完成任务，但是笔者认为各类框架虽好，但里面会有很多我们用不到的功能。
    因此决定自己创建一个模板项目，每当新开启项目时都以它为起点。

    AndroidTemplate就是模板项目。

<br>** 内容 **
  为了防止正项目过于臃肿，将代码分别写在tp_base、tp_media、tp_translaod三个module里了。

     tp_base用于存放最基本的一些模块：http、对话框、RecyclerView、BaseActivity、各类Util类等。
     tp_media用于存放多媒体相关的类：目前只有一个流媒体播放器和GifView。
     tp_transload用于存放上传和下载模块，它支持上传下载队列。

<br>** 提示 **
   本项目主要是笔者自己使用，所以也就并不打算写详细的文档。

   感兴趣的朋友可以对本项目进行任意修改、据为己有，本人放弃本项目的全部权利。
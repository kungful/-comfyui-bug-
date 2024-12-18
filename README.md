# -comfyui-bug-
日常解决comfyui的bug收集日志
## flux采样解码是白图？
这个原因困扰了我一周多，主要是因为ae.safetensors损坏，
因为我的固态硬盘六年了估计有坏道复制所有模型的时候损坏了。中间误以为是底模和cuda还有驱动一直在循环更换加上测试花了一周，
最后换了linux系统还是这样。最后在其它工作流发现不一样的vae模型更换之后发现了问题，是我的ae.safetensors损坏了

[bug的样子](https://github.com/kungful/-comfyui-bug-/blob/9847da6a84ab162dfe1beeb3b6b67ad3f4086351/%E5%9B%BE%E6%96%87/%E8%A7%A3%E7%A0%81%E7%99%BD%E5%9B%BE.png)

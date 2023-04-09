![titleimage](https://github.com/superowner/VRM-to-Pmx-Converter/blob/master/sdfsdfsdfdg.png)

you can fork from https://www.jianshu.com/p/8a4a5993d89f now (I just use mobile,no more..you know..)

Download：
历史版本：
链接: https://pan.baidu.com/s/1kngUeLuRPgqfXaAYBVFrGA 提取码: 2yuu
Git:https://github.com/superowner/VRM-to-Pmx-Converter/tree/master

下载版本号最大的即是最新的

指路：
1.原版VRoid Studio内大部分默认动画，在https://assetstore.unity.com/packages/3d/characters/unity-chan-model-18705可以免费下载使用，或者到unitychan官网下载，但是自己捏的动作是无法导出的，你可以通过VA，UMotion(推荐，可以导出fbx动画)等等第三方Unity插件捏动画导出。
2.可以到VRoid Hub下载海量VRM模型，并转化为pmx!
3.可以通过Unity的UniVRM插件，把任意人形(必须)骨模型导出VRM模型，再用这个工具直接转化为pmx! 例如：你通过AssetStudio等工具导出蹦3的fbx模型，然后经过UniVRM转化为VRM，然后可以一键pmx！

注意：
A：里面的勾选触发器(旋转模型180度)不要随便点，这个是为了修正有些模型反转的错误，一般模型是没有必要点的！若要使用这个功能必须先勾，选然后打开VRM模型，然后点转换按钮。
B：每次转换完事后，设置都会重置一次，包括你将选择VRM却取消
预览：
C：软件运行环境：XP以上(不知道，待验证，溜了..)，64bit系统
D：配置要求：100M安装空间，2G内存



有什么bug可以下面回复。
目前已修复BUG：
1：缺失部分贴图没有导出（布吉岛，制作比较仓促，就做了5小时）（已修复）
2：贴图未附加到pmx上，需要手动用Pmxeditor添加（已修复）
3：支持其他软件导出的VRM格式，包括Unity等
目前已知BUG：
none
History:

v0.5
Add:General VRM format support(just not only for VRoid)
Add:per model folder
UniVRM-samples-0.51.0_1b36
VRMtoPMXExporter_v0.5.3
VRoidStudio-v0.5.4(?)-p2~VRoidStudio-v0.6.4
PS:VRMtoPMXExporter_v0.5.5 has some UV errors and lose smoothing group so I use VRMtoPMXExporter_v0.5.3

v0.4
UniVRM-samples-0.51.0_1b36
VRMtoPMXExporter_v0.5.3
VRoidStudio-v0.5.4(?)-p2~VRoidStudio-v0.6.4
PS:VRMtoPMXExporter_v0.5.5 has some UV errors and lose smoothing group so I use VRMtoPMXExporter_v0.5.3

v0.3:
UniVRM-0.49_43af
VRMtoPMXExporter_v0.5.3
VRoidStudio-v0.4.0-p1~VRoidStudio-v0.5.4-p2

v0.2:
none

转载请附上以下内容(上面的随意)：
本插件没有任何技术含量，所有的核心内容来自以下两位大佬的开源项目，
制作本工具的目的仅仅是方便广大Vroid Studio或者UniVRM等用户

Ref:
Great Thanks to Furia(twitter) and dwango(github)!
Free to use, but to comply with the model usage specification.


MIT license

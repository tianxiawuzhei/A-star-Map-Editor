# A-star-Map-Editor
A star Map Editor(一个简单的A* 寻路的地图编辑器，基于web)

使用说明：
1、
选择文件按钮，可以选择需要编辑的地图图片， add Grid按钮用于添加网格，remove Grid用于移除添加的网格，save按钮用于
保存编辑后的地图数据，change Mode可以改变编辑模式(空格键键也可以)。

2、
编辑模式：
两种：
1、鼠标点击一个格子，两种状态之间切换，用于调整精确编辑。
2、鼠标划过一个格子，两种状态切换，用于快速编辑。

3、
导出数据格式：xml文本
x: 横向多少格子
y: 纵向多少格子
path: 每个代表一个格子，0:可通过 1:不可通过
<MapData><x>100</x><y>26</y><path>0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000,111110000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000....</path></MapData>

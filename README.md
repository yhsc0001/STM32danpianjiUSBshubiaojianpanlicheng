# STM32单片机USB鼠标键盘例程

## 资源描述

本实验旨在通过STM32单片机实现USB鼠标和键盘的识别与数据读取功能。实验的主要功能如下：

1. **开机提示信息**：系统启动时，首先显示一些提示信息，告知用户系统正在初始化。

2. **USB HOST初始化**：系统初始化USB HOST模块，并进入轮询状态，等待USB设备的插入。

3. **设备检测与识别**：当检测到USB鼠标或键盘插入时，系统会显示设备的类型（鼠标或键盘），并开始读取设备的输入数据。

4. **数据展示**：
   - **USB鼠标**：系统将显示鼠标的移动坐标（X、Y坐标）、滚轮滚动数值（Z坐标）以及按键状态（左键、中键、右键）。
   - **USB键盘**：系统将显示键盘输入的数字、字母等内容。需要注意的是，并非所有按键都支持解码，例如F1~F12等功能键可能无法正确显示。

## 注意事项

1. **引脚配置**：本实验需要使用D+引脚（PA12）和D-引脚（PA11）。请确保这些引脚正确连接。

2. **USB_SLAVE接口**：在实验过程中，请勿将任何设备插入USB_SLAVE接口，以免影响实验结果。

3. **设备兼容性**：本实验支持USB键盘和有线鼠标。请确保使用的设备符合实验要求。

## 使用说明

1. **硬件连接**：将USB鼠标或键盘通过USB HOST接口连接到STM32单片机。

2. **软件运行**：启动系统后，观察显示屏上的提示信息。当设备插入后，系统会自动识别设备类型并显示相应的输入数据。

3. **数据查看**：通过显示屏查看鼠标或键盘的输入数据，验证实验功能是否正常。

## 总结

本实验通过STM32单片机实现了USB鼠标和键盘的识别与数据读取功能，适用于学习和研究USB协议的应用场景。希望本资源能够帮助您更好地理解STM32的USB HOST功能。

## 下载链接
[STM32单片机USB鼠标键盘例程](https://pan.quark.cn/s/b59f6c184c0c) 

(备用: [备用下载](https://pan.baidu.com/s/1yQ_JlHLPtdaep8y5qD5ELg?pwd=1234))

# 插入工作表

插入新的工作表到工作簿中，可实现新建工作表插入到指定位置，和复制已有工作表插入到指定位置

## 属性

输入

- **新工作表名称** ：插入的新工作表名称。仅支持字符串变量和字符串
- **插入位置** ：将新工作表插入到的目标位置。例如&quot;1&quot;，即插入工作表的位置为第一个。当为空时，默认插入到最后。仅支持整形变量和整形
- **模式** ：插入工作表时的模式选择。含两项：新建工作表，复制工作表
- **源工作表名** ：若模式选择&quot;复制工作表&quot;，此项为必填项，将取此工作表并复制到新工作表。仅支持字符串变量和字符串

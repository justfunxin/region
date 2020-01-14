# region
2020年淘宝4级地址库，菜鸟网络4级地址库，包含48755条数据

1:country/国家;
2:province/省/自治区/直辖市;
3:city/地区(省下面的地级市);
4:district/县/市(县级市)/区;
5.street/镇/街道

# 格式
```
{
    "id": "标准行政区域代码",
    "name": "地域名称",
    "abbr": "地域简称",
    "pinyin": "地域拼音",
    "tname": "地域繁体",
    "pid": "父节点区域代码",
    "type": "区域类型, 1:country/国家;2:province/省/自治区/直辖市;3:city/地区(省下面的地级市);4:district/县/市(县级市)/区;abroad:海外;5.street/镇/街道",
    "zip": "邮编",
    "enabled": "是否可用, true:可用 false:已删除"
}
```        

**Example 1: 执行操作系统转换**

针对实例 ins-6pb6lrmy 执行操作系统转换

Input: 

```
tccli cvm ConvertOperatingSystems --cli-unfold-argument  \
    --InstanceIds ins-6pb6lrmy
```

Output: 
```
{
    "Response": {
        "SupportTargetOSList": [
            {
                "TargetOSType": "TencentOS",
                "TargetOSVersion": "2.4"
            }
        ],
        "TaskId": "12345678",
        "RequestId": "abc"
    }
}
```


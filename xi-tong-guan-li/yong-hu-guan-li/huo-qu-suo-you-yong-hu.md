### 数据格式

```json
[
    {
        "id": 1,
        "name": "嘉诚信息",
        "deptType": 1,
        "parentId": 0,
        "user": [],
        "subDept": [
            {
                "id": 1003,
                "name": "软件研发部",
                "deptType": 0,
                "parentId": 1,
                "user": [
                    {
                        "id": 1,
                        "displayName": "管理员",
                        "deptId": 1003,
                        "orderNo": 10
                    }
                ],
                "subDept": [
                    {
                        "id": 1003001,
                        "name": "系统架构部",
                        "deptType": 0,
                        "parentId": 1003,
                        "user": [
                            {
                                "id": 100172,
                                "displayName": "孙纪福",
                                "deptId": 1003001,
                                "orderNo": 207
                            }
                        ],
                        "subDept": []
                    },
                    {
                        "id": 2003001027,
                        "name": "产品开发部",
                        "deptType": 0,
                        "parentId": 1003,
                        "user": [],
                        "subDept": [
                            {
                                "id": 2003001062,
                                "name": "产品UI组",
                                "deptType": 0,
                                "parentId": 2003001027,
                                "user": [
                                    {
                                        "id": 100284,
                                        "displayName": "王皓",
                                        "deptId": 2003001062,
                                        "orderNo": 205
                                    }
                                ],
                                "subDept": []
                            }
                        ]
                    }
                ]
            },

        ]
    }
]
```




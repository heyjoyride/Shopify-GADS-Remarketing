{
    "exportFormatVersion": 2,
    "exportTime": "2021-05-03 15:17:57",
    "containerVersion": {
        "path": "accounts/144483319/containers/44685111/versions/0",
        "accountId": "144483319",
        "containerId": "44685111",
        "containerVersionId": "0",
        "container": {
            "path": "accounts/144483319/containers/44685111",
            "accountId": "144483319",
            "containerId": "44685111",
            "name": "Shopify-Dynamic-Remarketing",
            "publicId": "GTM-5JQFLR8",
            "usageContext": [
                "WEB"
            ],
            "fingerprint": "1620047348551",
            "tagManagerUrl": "https://tagmanager.google.com/#/container/accounts/144483319/containers/44685111/workspaces?apiLink=container"
        },
        "tag": [
            {
                "accountId": "144483319",
                "containerId": "44685111",
                "tagId": "9",
                "name": "Conversion Linker",
                "type": "gclidw",
                "parameter": [
                    {
                        "type": "BOOLEAN",
                        "key": "enableCrossDomain",
                        "value": "false"
                    },
                    {
                        "type": "BOOLEAN",
                        "key": "enableUrlPassthrough",
                        "value": "false"
                    },
                    {
                        "type": "BOOLEAN",
                        "key": "enableCookieOverrides",
                        "value": "false"
                    }
                ],
                "fingerprint": "1620052628071",
                "firingTriggerId": [
                    "2147479553"
                ],
                "tagFiringOption": "ONCE_PER_EVENT",
                "monitoringMetadata": {
                    "type": "MAP"
                }
            },
            {
                "accountId": "144483319",
                "containerId": "44685111",
                "tagId": "11",
                "name": "GAds - Remarketing",
                "type": "sp",
                "parameter": [
                    {
                        "type": "TEMPLATE",
                        "key": "eventItems",
                        "value": "{{dlv - items}}"
                    },
                    {
                        "type": "TEMPLATE",
                        "key": "eventValue",
                        "value": "{{dlv - value}}"
                    },
                    {
                        "type": "BOOLEAN",
                        "key": "enableDynamicRemarketing",
                        "value": "true"
                    },
                    {
                        "type": "TEMPLATE",
                        "key": "eventName",
                        "value": "{{Event}}"
                    },
                    {
                        "type": "TEMPLATE",
                        "key": "conversionId",
                        "value": "849535282"
                    },
                    {
                        "type": "TEMPLATE",
                        "key": "customParamsFormat",
                        "value": "NONE"
                    },
                    {
                        "type": "BOOLEAN",
                        "key": "rdp",
                        "value": "false"
                    }
                ],
                "fingerprint": "1620052856403",
                "firingTriggerId": [
                    "10"
                ],
                "tagFiringOption": "ONCE_PER_EVENT",
                "monitoringMetadata": {
                    "type": "MAP"
                }
            }
        ],
        "trigger": [
            {
                "accountId": "144483319",
                "containerId": "44685111",
                "triggerId": "10",
                "name": "custom - remarketing",
                "type": "CUSTOM_EVENT",
                "customEventFilter": [
                    {
                        "type": "MATCH_REGEX",
                        "parameter": [
                            {
                                "type": "TEMPLATE",
                                "key": "arg0",
                                "value": "{{_event}}"
                            },
                            {
                                "type": "TEMPLATE",
                                "key": "arg1",
                                "value": "view_search_results|view_item_list|view_item|add_to_cart|purchase"
                            }
                        ]
                    }
                ],
                "fingerprint": "1620052961856"
            }
        ],
        "variable": [
            {
                "accountId": "144483319",
                "containerId": "44685111",
                "variableId": "4",
                "name": "dlv - value",
                "type": "v",
                "parameter": [
                    {
                        "type": "INTEGER",
                        "key": "dataLayerVersion",
                        "value": "2"
                    },
                    {
                        "type": "BOOLEAN",
                        "key": "setDefaultValue",
                        "value": "false"
                    },
                    {
                        "type": "TEMPLATE",
                        "key": "name",
                        "value": "value"
                    }
                ],
                "fingerprint": "1620049983621",
                "formatValue": {}
            },
            {
                "accountId": "144483319",
                "containerId": "44685111",
                "variableId": "5",
                "name": "dlv - items",
                "type": "v",
                "parameter": [
                    {
                        "type": "INTEGER",
                        "key": "dataLayerVersion",
                        "value": "2"
                    },
                    {
                        "type": "BOOLEAN",
                        "key": "setDefaultValue",
                        "value": "false"
                    },
                    {
                        "type": "TEMPLATE",
                        "key": "name",
                        "value": "items"
                    }
                ],
                "fingerprint": "1620050011217",
                "formatValue": {}
            }
        ],
        "builtInVariable": [
            {
                "accountId": "144483319",
                "containerId": "44685111",
                "type": "PAGE_URL",
                "name": "Page URL"
            },
            {
                "accountId": "144483319",
                "containerId": "44685111",
                "type": "PAGE_HOSTNAME",
                "name": "Page Hostname"
            },
            {
                "accountId": "144483319",
                "containerId": "44685111",
                "type": "PAGE_PATH",
                "name": "Page Path"
            },
            {
                "accountId": "144483319",
                "containerId": "44685111",
                "type": "REFERRER",
                "name": "Referrer"
            },
            {
                "accountId": "144483319",
                "containerId": "44685111",
                "type": "EVENT",
                "name": "Event"
            }
        ],
        "fingerprint": "1620055077892",
        "tagManagerUrl": "https://tagmanager.google.com/#/versions/accounts/144483319/containers/44685111/versions/0?apiLink=version"
    }
}

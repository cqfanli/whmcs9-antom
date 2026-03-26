# whmcs9-antom
whmcs9 antom alipay+ gateways
此版本包含了：正確的全球站端點、自動實時匯率（HKD->CNY）、手續費/稅費疊加、原路退款、失敗自動開工單、安全驗簽、以及版本更新檢查功能。

antom_v2.3.6.zip
└── modules/
    └── gateways/
        ├── antom.php                 (插件主配置與升級邏輯)
        ├── antom/
        │   ├── library.php           (RSA256 簽名與 API 通訊類)
        │   └── redirect.php          (支付跳轉處理)
        └── callback/
            └── antom.php             (異步通知驗簽與入賬)

flowchart TD
    Start([開始]) --> Step1[1. 取得麻醉部值班表]
    Step1 --> Step2[2. 確認請假住院醫師]
    Step2 --> Step3[3. 排出住院醫師白班人力]
    Step3 --> Step4[4. 排入周六人力]
    Step4 --> Step5[5. 主治醫師班表轉換]
    Step5 --> Step6[6. 住院醫師班表轉換<br/><small>使用住院醫師值班表</small>]
    Step6 --> Step7[7. 生成照會表]
    Step7 --> Step8[8. 生成門診表]
    Step8 --> End([完成])
    
    style Start fill:#e1f5e1
    style End fill:#e1f5e1
    style Step1 fill:#fff4e6
    style Step2 fill:#fff4e6
    style Step3 fill:#e3f2fd
    style Step4 fill:#e3f2fd
    style Step5 fill:#f3e5f5
    style Step6 fill:#f3e5f5
    style Step7 fill:#fce4ec
    style Step8 fill:#fce4ec

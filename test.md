flowchart TD
    A03[ A03 計劃提交及預算審批 ] --> A01[ A01-1 抽籤及確認流程 ]
    A01 --> A02[ A02 活動收費判斷 ]
    A02 --> A02_1[ A02_1 收費流程 ]
    A02 --> A04[ A04 活動點名及義工記錄 ]
    A02_1 --> A04
    A04 --> A05[ A05 活動後報告及反饋 ]
    A05 --> A06[ A06 提交提醒功能 ]
    A06 --> A07[ A07 文件上載及統計報告 ]
    
    %% 額外獨立流程
    A08[ A08 退款流程 ]

    %% 樣式
    style A01 fill:#d0e6f9,stroke:#1c5d99,stroke-width:1px
    style A02 fill:#d0e6f9,stroke:#1c5d99,stroke-width:1px
    style A02_1 fill:#f9e0d0,stroke:#c97b1d,stroke-width:1px
    style A03 fill:#e0f9d0,stroke:#2e7d32,stroke-width:1px
    style A04 fill:#d0f9f1,stroke:#00897b,stroke-width:1px
    style A05 fill:#f9f1d0,stroke:#9e7d00,stroke-width:1px
    style A06 fill:#f1d0f9,stroke:#6a1b9a,stroke-width:1px
    style A07 fill:#f9d0d0,stroke:#b71c1c,stroke-width:1px
    style A08 fill:#ffffff,stroke:#444,stroke-width:1px

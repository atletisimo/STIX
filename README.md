# STIX
Со користење на STIX 2.1 моделот, документот ги претставува следните компоненти на нападот: 
    • Identity: Critical Infrastructure Organization – жртва на нападот
    • Threat Actor: LockBit Ransomware Operators
– Цел: финансиска добивка преку ransomware
    • Malware: LockBit 4.0
– Тип: ransomware, брзо криптирање на фајлови, double extortion
    • Intrusion Set: LockBit Operations
– Се однесува на активностите на Threat Actor
    • Attack Patterns: PowerShell execution, DLL injection
    • Indicators: SHA‑256 хешови на .PS1 и DLL фајлови
    • Observed Data: процес 5182.tmp и ransom note kF0wnCN24.README.txt
    • Course of Action: препораки за одбрана (EDR/XDR, сегментација на VLAN, блокирање IOC хешови, phishing awareness)
    • Report: ги обединува сите  објекти и нивните релации

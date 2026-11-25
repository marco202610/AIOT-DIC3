# Abstract — AI Fitness Coach

## 中文摘要

2025 年臺灣運動現況調查顯示，民眾運動參與比例達 83.3%，然而規律運動人口比例僅為 35.6%，兩者相差 47.7 個百分點，凸顯持續性與個人化運動支援的研究價值。此外，2025 年食物影像分析研究指出，部分通用生成式人工智慧模型在熱量估算上的平均絕對百分比誤差（MAPE）達 35.8%，顯示人工智慧應用於運動與營養管理時，仍面臨定量分析可靠性與資訊不確定性的挑戰。

本研究提出 **AI Fitness Coach**，一套以領域智慧代理（Domain AI Agent）為核心，整合人工智慧物聯網（AIoT）、大型語言模型（LLM）、模型情境協定（MCP）、地理資訊系統（GIS）、區塊鏈及多模態人機互動技術的情境感知智慧運動教練。系統以智慧型手機作為主要感測入口，在不強制依賴心率穿戴裝置的條件下，整合 GPS、三軸加速度、步頻、氣象資訊及使用者需求，建立「感知、分析、決策、回饋」的閉環式運動支援架構。

系統透過大型語言模型進行情境理解、意圖辨識與任務規劃，並藉由 MCP 協調領域工具，完成運動能量消耗估算、環境資訊分析、地理興趣點（POI）推薦及營養分析。不同於單純的活動紀錄與地理位置查詢，本研究將環境條件、路線可達性、繞行成本及使用者需求納入決策過程，提供補給、休息、路線調整與活動結束等情境式建議。同時，透過視覺語言模型（VLM）、使用者確認及營養資料庫建立人機協作分析流程，管理營養估算的不確定性，並結合文字、語音及 3D 數位人提供個人化互動回饋。

為因應個人運動感測資料的隱私與完整性問題，本研究進一步建構結合錢包身分驗證、AES-256-GCM 加密、SHA-256 摘要驗證及 IOTA EVM 錨定介面的資料管理原型，採用鏈下密文儲存與規劃中的鏈上摘要錨定架構，使個人資料內容與完整性驗證資訊分離，並透過使用者授權及公開摘要介面支援 AI 助理整合。

目前，區塊鏈相關功能、AI 助理整合、數位人及音訊處理模組已完成 56 項本機與模擬測試，均通過測試。後續研究將透過基準方法比較、情境模擬及使用者實驗，評估情境式推薦品質、氣象告警效能、營養估算誤差、人機互動效率、系統穩健性及資料完整性驗證能力。

本研究的學術貢獻在於建立一套整合環境感知、跨領域工具協作、智慧決策、多模態互動與可信資料管理的智慧運動教練架構，探討人工智慧如何從被動式活動紀錄與資訊生成，轉化為具備情境理解及行動決策支援能力的個人化運動代理。預期研究成果將為低使用門檻、具可解釋性及資料完整性驗證能力的智慧運動服務提供可擴充、可評估的研究基礎，其運動安全效益與長期運動持續性仍有待後續實證驗證。

**關鍵詞：** 智慧運動教練、人工智慧物聯網、智慧代理、情境感知、模型情境協定、多模態人機互動、區塊鏈、資料完整性。

---

## English Abstract

According to Taiwan's 2025 sports participation survey, 83.3% of the population participated in sports or exercise, whereas only 35.6% engaged in regular exercise, representing a gap of 47.7 percentage points and highlighting the research value of sustained and personalized exercise support. Furthermore, a 2025 study reported a mean absolute percentage error (MAPE) of 35.8% in food image-based caloric estimation by certain general-purpose generative AI models, indicating persistent challenges in quantitative reliability and uncertainty management within AI-assisted fitness and nutrition services.

This study proposes **AI Fitness Coach**, a context-aware intelligent fitness coaching system powered by a domain-specific AI agent and integrating the Artificial Intelligence of Things (AIoT), Large Language Models (LLMs), Model Context Protocol (MCP), Geographic Information Systems (GIS), blockchain technology, and multimodal human–AI interaction. Using smartphones as the primary sensing platform, the proposed system integrates GPS, triaxial acceleration, cadence, weather information, and user requirements without mandating heart-rate wearable devices, establishing a closed-loop sensing–analysis–decision–feedback architecture.

The proposed system employs LLMs for contextual understanding, intent recognition, and task planning, while MCP facilitates the orchestration of domain-specific tools for energy expenditure estimation, environmental analysis, point-of-interest (POI) recommendation, and nutritional assessment. Beyond conventional activity tracking and location-based queries, the system incorporates environmental conditions, route accessibility, detour costs, and user requirements into its decision-making process to provide context-aware recommendations for replenishment, rest, route adjustment, and activity termination. A human–AI collaborative dietary assessment workflow combines vision-language models (VLMs), user confirmation, and nutritional databases to manage estimation uncertainty. Text, voice, and three-dimensional avatars further support personalized multimodal interaction.

To address privacy and data integrity challenges associated with personal exercise sensing data, this study introduces a data management prototype incorporating wallet-based authentication, AES-256-GCM encryption, SHA-256 integrity verification, and an IOTA EVM anchoring interface. The architecture combines off-chain encrypted storage with planned on-chain hash anchoring, separating personal data content from integrity verification information while supporting AI assistant integration through consent-based public summaries.

At the current development stage, 56 local and simulated tests covering blockchain-related functions, AI assistant integration, digital avatars, and audio processing have passed. Subsequent research will employ baseline comparisons, scenario-based simulations, and user studies to evaluate contextual recommendation quality, weather alert performance, nutritional estimation error, interaction efficiency, system robustness, and data integrity verification.

The academic contribution of this study lies in establishing an intelligent fitness coaching architecture that integrates environmental awareness, cross-domain tool orchestration, agent-based decision-making, multimodal interaction, and verifiable data management. The proposed framework investigates the transition from passive activity tracking and information generation toward personalized, context-aware, and actionable fitness decision support. The expected outcomes provide an extensible and evaluable research foundation for accessible, explainable, and data-integrity-aware fitness services. Potential improvements in exercise safety and long-term exercise adherence remain subject to empirical validation.

**Index Terms—** AI Fitness Coach, Artificial Intelligence of Things (AIoT), AI Agent, Context Awareness, Model Context Protocol (MCP), Multimodal Human–AI Interaction, Blockchain, Data Integrity.

---

## References

1. 2025 年臺灣運動現況調查 — https://news.pts.org.tw/article/787192
2. Food Image-Based Nutritional Estimation Study, 2025 — https://pubmed.ncbi.nlm.nih.gov/41081011/
3. Research Framework — https://github.com/marco202610/AIOT-DIC3/blob/main/docs/A_to_F.md
4. Blockchain Development — https://github.com/marco202610/AIOT-DIC3/blob/main/docs/blockchain-development.md

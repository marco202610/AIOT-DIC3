# 摘要（Abstract）

2025 年臺灣運動現況調查顯示，民眾運動參與比例達 83.3%，然而規律運動人口比例僅為 35.6%，兩者相差 47.7 個百分點，凸顯持續性運動支援的研究價值。此外，2025 年食物影像分析研究指出，部分通用生成式人工智慧模型在熱量估算上的平均絕對百分比誤差（MAPE）高達 35.8%，顯示人工智慧在個人化運動與營養管理領域，仍面臨資料可靠性、情境理解及定量分析等挑戰。

本研究提出 **AIOT-DIC3（AI Fitness Coach）**，一套整合人工智慧物聯網（AIoT）、大型語言模型（LLM）、模型情境協定（MCP）、地理資訊系統（GIS）、區塊鏈（Blockchain）及多模態人機互動技術的情境感知智慧運動代理。系統以智慧型手機作為主要感測入口，在不強制依賴心率穿戴裝置的條件下，整合 GPS、三軸加速度、步頻、氣象資訊及使用者需求，建立「感知、分析、決策、回饋」的閉環式運動支援架構。

本研究採用領域智慧代理（Domain AI Agent）與工具協作機制，由大型語言模型負責情境理解、意圖辨識及任務規劃，並透過 MCP 協調領域工具進行資料檢索、運動當量（MET）估算、地理興趣點（POI）推薦及營養分析。系統結合環境條件、路線可達性與使用者需求，提供補給、休息及活動結束等情境式行動建議；同時導入視覺語言模型（VLM）、使用者確認與營養資料庫，降低直接依賴生成式 AI 進行營養估算的不確定性，並透過文字、語音及 3D 數位人建立多模態互動介面。

為因應 AIoT 感測資料的隱私與完整性問題，本研究另建構結合錢包身分驗證、IndexedDB 本機持久化、AES-256-GCM 加密、SHA-256 摘要驗證及 IOTA EVM 錨定介面的資料管理原型，採用鏈下密文儲存與規劃中的鏈上摘要錨定架構，並透過經授權的公開摘要介面支援 AI 助理整合。

截至目前開發階段，區塊鏈相關功能、AI 助理整合、數位人及音訊處理模組共完成 56 項本機與模擬測試，均通過測試。後續研究將透過基準方法比較、情境模擬及使用者實驗，評估地點推薦適切性、氣象告警效能、營養估算誤差、人機互動效率、系統穩健性及資料完整性驗證能力。

本研究的學術貢獻在於建立一套整合情境感知、跨領域工具協作、人機互動與資料完整性驗證的智慧代理架構，探討人工智慧如何從被動式活動紀錄與資訊生成，轉化為具備環境感知、領域分析及行動決策支援能力的智慧運動服務。預期研究成果可作為低使用門檻、具可解釋性及可驗證資料管理能力之 AIoT 個人化運動系統的研究基礎，其實際安全效益與長期運動持續性仍有待後續實證驗證。

---

# Abstract

According to Taiwan's 2025 National Sports Survey, 83.3% of the population participated in sports or exercise, whereas only 35.6% engaged in regular exercise, representing a gap of 47.7 percentage points and highlighting the importance of sustained exercise support. Furthermore, a 2025 study reported a mean absolute percentage error (MAPE) of 35.8% in caloric estimation by certain general-purpose generative AI models using food images, revealing challenges in data reliability, contextual understanding, and quantitative analysis within AI-assisted fitness and nutrition management.

This study proposes **AIOT-DIC3 (AI Fitness Coach)**, a context-aware intelligent fitness agent integrating the Artificial Intelligence of Things (AIoT), Large Language Models (LLMs), Model Context Protocol (MCP), Geographic Information Systems (GIS), blockchain technology, and multimodal human–AI interaction. Using smartphones as the primary sensing platform, the proposed system integrates GPS, triaxial acceleration, cadence, weather information, and user requirements without mandating heart-rate wearable devices, establishing a closed-loop sensing–analysis–decision–feedback architecture.

The proposed framework employs a domain-specific AI agent for contextual understanding, intent recognition, task planning, and tool orchestration. Through MCP, the agent coordinates domain tools for information retrieval, metabolic equivalent of task (MET) estimation, point-of-interest (POI) recommendation, and nutritional analysis. Context-aware recommendations for replenishment, rest, and activity termination incorporate environmental conditions, route accessibility, and user requirements. A human–AI collaborative dietary assessment workflow combines vision-language models (VLMs), user confirmation, and nutritional databases to address estimation uncertainty. Text, voice, and three-dimensional avatars further support multimodal interaction and personalized feedback.

To address privacy and data integrity challenges in AIoT sensing environments, a data management prototype incorporates wallet-based authentication, IndexedDB persistence, AES-256-GCM encryption, SHA-256 integrity verification, and an IOTA EVM anchoring interface. The architecture combines off-chain encrypted storage with planned on-chain hash anchoring and supports AI assistant integration through a consent-based public summary interface.

At the current development stage, 56 local and simulated tests covering blockchain-related functions, AI assistant integration, digital avatars, and audio processing have passed. Subsequent research will employ baseline comparisons, scenario-based simulations, and user studies to evaluate recommendation appropriateness, weather alert performance, nutritional estimation error, interaction efficiency, system robustness, and data integrity verification.

The academic contribution of this study lies in integrating context awareness, cross-domain tool orchestration, human–AI interaction, and verifiable data management into a unified intelligent agent architecture. The proposed framework investigates the transition from passive activity tracking and information generation toward context-aware, explainable, and actionable fitness decision support. The expected outcome provides a research foundation for accessible and extensible AIoT fitness services, while potential improvements in exercise safety and long-term adherence remain subject to empirical validation.

**Index Terms—** Artificial Intelligence of Things (AIoT), AI Agent, Context Awareness, Model Context Protocol (MCP), Geographic Information Systems (GIS), Blockchain, Multimodal Human–AI Interaction, Data Integrity.

---

## References

1. Taiwan's 2025 National Sports Survey — https://news.pts.org.tw/article/787192
2. Food image-based nutritional estimation study, 2025 — https://pubmed.ncbi.nlm.nih.gov/41081011/
3. AIOT-DIC3 Research Framework — https://github.com/marco202610/AIOT-DIC3/blob/main/docs/A_to_F.md
4. Blockchain Development and Technical Documentation — https://github.com/marco202610/AIOT-DIC3/blob/main/docs/blockchain-development.md

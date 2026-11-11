# 預期貢獻與學術價值摘要

隨著戶外健走與跑步普及，運動服務的需求已從活動紀錄，延伸至環境感知、補給指引與持續陪伴。2025年台灣運動現況調查顯示，運動參與比例達83.3%，規律運動比例則為35.6%，凸顯持續性運動支援的研究價值。 本研究提出AI Fitness Coach領域智慧代理，聚焦未配戴心率裝置的使用者，整合GPS、步頻、氣象與地理興趣點資訊，提供情境化戶外運動建議。 [news.pts.org](https://news.pts.org.tw/article/787192)

系統採用FastAPI後端與MCP工具協作架構，串接GIS空間檢索、運動當量估算、食物影像辨識、營養資料庫及3D數位人介面。核心設計包含三項：依天候、使用者需求與路線可達性推薦補給或撤退地點；透過食物辨識、份量確認與資料庫檢索降低飲食紀錄負擔；以語音及數位人提供建議說明與互動回饋。針對影像營養估算的不確定性，系統保留人工確認與降級機制，避免將估算結果視為精準量測。

研究將比較最近地點查詢、規則式方法與代理式決策，評估POI推薦適切性、繞行成本、氣象告警延遲、營養估算誤差，以及文字、語音與數位人的互動差異。預期建立低穿戴門檻、具可解釋性與失效處理能力的智慧教練原型；其安全效益與長期運動持續性，仍須透過後續使用者研究驗證。

**關鍵詞：** 情境感知、智慧健身代理、系統整合、人機協作、多模態互動。

---

# Expected Contributions and Academic Significance

This study addresses the fragmentation of sensing data, environmental risk information, and replenishment decisions in outdoor walking and running services. A context-aware AI fitness coaching system is proposed to integrate heterogeneous data retrieval, domain knowledge, and interactive feedback within a closed-loop sensing–analysis–decision–feedback architecture. Four contributions are anticipated. First, a modular architecture integrates GPS, cadence, weather information, and points of interest to support context-aware services without requiring heart-rate wearables, while explicitly distinguishing activity expenditure estimation from physiological fatigue assessment. Second, a context-constrained recommendation method is developed for replenishment and activity-exit destinations, jointly considering user requirements, route accessibility, and detour costs. Comparisons with nearest-location and rule-based baselines are designed to assess the incremental value of agent-based tool orchestration. Third, a human–AI collaborative dietary logging workflow combines food image recognition, user confirmation, and nutritional database retrieval to investigate the tradeoff between logging burden and estimation error, incorporating uncertainty communication and fallback mechanisms. Fourth, controlled comparisons of text, voice, and three-dimensional avatar interfaces, with recommendation content held constant, are designed to isolate their effects on comprehension, interaction burden, and intention to use. The academic significance lies in a cross-module coordination approach and a reproducible, multilevel evaluation framework for examining the applicability and limitations of agent-based decision-making, human–AI collaboration, and multimodal interaction. The expected outcome is an explainable and extensible system prototype; improvements in safety and long-term exercise adherence remain subject to subsequent empirical validation.

**Index Terms—** Context awareness, AI fitness coaching, systems integration, human–AI collaboration, multimodal interaction.

# Taipei-AI-Incident-Map

Analyze past traffic incidents in Taipei City, assess whether a destination needs heightened safety attention **today**, and speak a Chinese safety advisory via TTS.  
Visualize incidents on interactive Folium maps with marker clustering.

> 針對台北市歷史事故資料，評估特定地區是否需提高交通安全注意，並以中文 TTS 提醒；同時以 Folium 顯示 12 月事故點與群聚。
## Demo
<p align="center">
  <img src="<AI map1.png>" width="420" alt="Map 1">
  <img src="<AI map2.png>" width="420" alt="Map 2">
</p>

---

## Features
- **Risk summary by district / road**：統計各「區」總事故數與高風險「區–路」。
- **Threshold-based advisory**：依門檻自動組合中文安全提示（例：區 ≥ 2000 件、路段 ≥ 200 件，可於程式中調整）。
- **Text-to-Speech (TTS)**：以 `pyttsx3` 將提示語音播報。
- **Interactive maps**：使用 Folium 建立 `point_map` / `circle_map`，並以 `MarkerCluster` 群聚顯示事故點。
- **UI switching**：用 `ipywidgets` 下拉選單在兩張地圖間切換。



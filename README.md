⚠️ Forklift Blind Zone 3D Simulator

An interactive 3D visualization of forklift blind zones for occupational safety education.
Built with vanilla JavaScript and Three.js — no installation required.

🔗 Try it Live →
이미지 표시
이미지 표시
이미지 표시

🎯 Purpose
Forklift-related fatalities account for approximately 85 deaths and 34,900 serious injuries per year in the United States alone (Bureau of Labor Statistics). A significant portion of these incidents occur because pedestrians enter blind zones that the operator cannot physically see.
This simulator makes those invisible danger zones visible — in 3D, in real time.

📊 Blind Zone Coverage (OSHA 29 CFR 1910.178 / ANSI B56.1)
ZoneAngular RangeConditionFront Mast±35° / 1.2 m widthAlways presentRear Counterweight±20° restrictionAlways presentSide A-Pillars13–18° each sideAlways presentLoad ObstructionUp to +40% additionalWhen carrying load

Unloaded: ~27% of surrounding area is blind
Loaded (2-pallet stack): up to ~45% of surrounding area is blind


🎮 Controls
Camera
ActionControlRotate viewMouse dragZoom in / outScroll wheelTouch rotateSingle finger dragTouch zoomPinch gesture
Buttons
ButtonFunction🔄 FREE ROTATEOrbit around the forklift freely🚗 DRIVER POV1st-person view from operator's seat🔼 TOP VIEWBird's-eye view of all blind zones◀ SIDE VIEWLateral profile of mast height👁 BLIND ZONESToggle hazard volume overlay📦 ADD LOADSimulate carrying a pallet load▶ WALK PEDESTRIANAuto-walk worker around the forklift
Pedestrian Position Sliders

Fwd / Rear (X) — move pedestrian forward or backward
Left / Right (Z) — move pedestrian side to side
Fork Height — raise forks (increases blind zone at height > 0.8 m)


When the pedestrian enters a blind zone, the status indicator switches to ⚠ DANGER! and an alert banner appears.


🚀 Quick Start
Option A — Use online (no download)
https://johub1.github.io/forklift-blindzone-simulator/
Option B — Run locally
bashgit clone https://github.com/Johub1/forklift-blindzone-simulator.git
cd forklift-blindzone-simulator
# Open index.html in any modern browser — no server needed

🛠️ Tech Stack

Three.js r128 — 3D rendering engine
Vanilla JS / HTML5 / CSS3 — zero dependencies beyond Three.js
WebGL — hardware-accelerated graphics
Single .html file — runs entirely in the browser


📚 References & Standards

OSHA 29 CFR 1910.178 — Powered Industrial Trucks
ANSI/ITSDF B56.1 — Safety Standard for Low Lift and High Lift Trucks
NIOSH Publication No. 2001-109 — Preventing Injuries and Deaths of Workers Who Operate or Work Near Forklifts
Bureau of Labor Statistics — Census of Fatal Occupational Injuries (CFOI)


👤 Author
Jo Hojun (조호준)
Safety Engineering Student — Chungbuk National University
CHST Candidate 
이미지 표시
이미지 표시

📄 License
MIT License — free to use, share, and modify with attribution.

If this tool is useful for your safety training or education, consider giving it a ⭐ star!

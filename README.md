# ☀️ AI Solar Planner

ระบบวิเคราะห์ศักยภาพการติดตั้งโซลาร์เซลล์เชิงพื้นที่ด้วยปัญญาประดิษฐ์

## 📌 ที่มาและปัญหา (Problem Statement)
การตัดสินใจติดตั้งโซลาร์เซลล์ในปัจจุบันขาดข้อมูลที่แม่นยำเฉพาะพื้นที่ 
เจ้าของบ้าน/อาคารมักไม่ทราบว่าหลังคาของตนเหมาะสมเพียงใด 
ทำให้การลงทุนไม่คุ้มค่าหรือประเมินระยะเวลาคืนทุนผิดพลาด

## 🎯 วัตถุประสงค์ (Objectives)
- [ ] วิเคราะห์ปัจจัยที่ส่งผลต่อศักยภาพการติดตั้งโซลาร์เซลล์ (พื้นที่, ทิศทาง, การบังเงา)
- [ ] คำนวณและแสดงผลคะแนนความเหมาะสมเป็นแผนที่
- [ ] คาดการณ์การผลิตไฟฟ้าและระยะเวลาคืนทุน

## 🔍 ขอบเขตของโปรเจกต์ (Scope)
- รับ input พื้นที่/ทิศทางหลังคาจากผู้ใช้
- ใช้ข้อมูลรังสีแสงอาทิตย์จาก API
- คำนวณคะแนนความเหมาะสมด้วยสูตรทางฟิสิกส์
- การวิเคราะห์ภาพถ่ายดาวเทียม/โดรนด้วย Computer Vision
- ระบบแนะนำยี่ห้อ/รุ่นแผงโซลาร์

## 🛠️ เทคโนโลยีที่ใช้ (Tech Stack)
- Frontend + Backend  [Streamlit](https://streamlit.io/) (Python) 
- Data Source [NASA POWER API](https://power.larc.nasa.gov/)
- Data Processing  Pandas, NumPy 
- Visualization (Chart)  Streamlit built-in charts / Plotly 
- Visualization (Map)  [Folium](https://python-visualization.github.io/folium/) 
- ML TensorFlow

## 📚 อ้างอิงข้อมูล (References)
- NASA POWER Project. (n.d.). *NASA Prediction of Worldwide Energy 
   Resources (POWER)*. NASA Langley Research Center. 
   Retrieved from https://power.larc.nasa.gov/
-Streamlit Inc. (n.d.). *Streamlit Documentation*. 
   Retrieved from https://docs.streamlit.io/
-Python Visualization. (n.d.). *Folium Documentation*.
   Retrieved from https://python-visualization.github.io/folium/

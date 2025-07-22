# 🌀 What Really Moves the Market? Absurd Correlations with the S&P 500

**An interactive dashboard that compares the S&P 500 stock market performance with completely unrelated cultural, environmental, and cosmic trends.**  

Because sometimes, the market moves for *mysterious* reasons… or maybe it’s just Beyoncé’s fault.  

---

## 🎯 Project Concept

This project explores **absurd correlations** between the stock market and random trends.  
Users can pick a signal from a dropdown and see how it “aligns” with the S&P 500 timeline.

Possible signals include:  

- 🎵 **Spotify Music Trends** – Are stocks more bullish when songs are more danceable or energetic?  
- 🏎 **Formula 1 World Champions** – Does the reigning F1 champion’s era impact stock performance?  
- ☀️ **Global Weather Trends** – Do rising global temperatures coincide with market growth or decline?  
- 🌓 **Moon Phases & Astronauts** – Are markets calmer during full moons or when more people are in space?  

This is a **fun, tongue-in-cheek data storytelling project** combining finance with pop culture, science, and randomness.

---

## 📊 Planned Features

✅ **Dual-axis time series charts**  
Compare S&P 500 vs chosen signal  

✅ **Correlation indicator**  
Show a (mostly meaningless) correlation coefficient  

✅ **Funny insights**  
Auto-generated commentary, e.g.  
> *“In years when Hamilton dominated F1, the S&P 500 was unstoppable. Coincidence?”*  

✅ **Interactive dropdown**  
Switch between Spotify, F1, Weather, and Moon/Space data  

✅ **Fully hosted online**  
Accessible via Streamlit Cloud  

---

## 🗂 Data Sources & APIs

| Signal | Dataset/API | Notes |
|--------|-------------|-------|
| **S&P 500** | [Yahoo Finance API](https://pypi.org/project/yfinance/) | Historical stock prices & returns |
| **Spotify Trends** | [Spotify Web API](https://developer.spotify.com/documentation/web-api/) | Avg danceability, energy, tempo of Top 50 songs per year |
| **F1 Champions** | [Ergast F1 API](https://ergast.com/mrd/) | Yearly F1 world champions since 2000 |
| **Global Weather** | [NASA GISTEMP](https://data.giss.nasa.gov/gistemp/) | Global temperature anomaly data |
| **People in Space** | [Open Notify API](http://api.open-notify.org/astros.json) | Number of humans in space over time |
| **Moon Phases** | [Astral Python Library](https://pypi.org/project/astral/) | Calculate moon phases for given dates |

---

## 🛠 Tech Stack

- **Python** (Pandas, NumPy) → data wrangling  
- **Plotly** → dual-axis time series charts  
- **Streamlit** → lightweight interactive dashboard  
- **APIs** → Spotify, Ergast F1, Open Notify, Yahoo Finance  
- **Hosting** → [Streamlit Cloud](https://streamlit.io/cloud) (free)  

---

## 📌 Roadmap

### Phase 1 – Core Setup
- [ ] Fetch **S&P 500** historical data with `yfinance`
- [ ] Build a simple dual-axis chart in Plotly  
- [ ] Create minimal Streamlit app  

### Phase 2 – Spotify vs S&P 500
- [ ] Fetch yearly Top 50 Spotify tracks  
- [ ] Calculate average **danceability/energy/tempo**  
- [ ] Compare with S&P 500 annual returns  
- [ ] Add funny correlation insights  

### Phase 3 – Add F1 Champions
- [ ] Fetch F1 champions from Ergast API  
- [ ] Categorize S&P performance by **champion era**  
- [ ] Add toggle for Spotify ↔ F1  

### Phase 4 – Add Weather & Moon/Space
- [ ] Pull NASA climate anomaly data  
- [ ] Integrate Open Notify astronauts-in-space API  
- [ ] Add moon phase calculations  

### Phase 5 – Polish & Deploy
- [ ] Clean UI & styling  
- [ ] Add funny random quotes for each signal  
- [ ] Deploy to Streamlit Cloud  
- [ ] Write short blog post about the project  

---

## 🖼 Example User Flow

1. **Landing Page** → *“Does music, F1, or the moon really move the market?”*  
2. **Dropdown Selection** → User picks **Spotify Music Trends**  
3. **Chart View** → Dual-axis: S&P 500 vs Avg Danceability  
4. **Correlation Box** → *“Correlation: +0.37 (completely meaningless)”*  
5. **Funny Insight** → *“In 2017, music got more upbeat… and so did the market!”*  
6. **Try Another Signal** → User switches to **Moon Phases**  

---

## 🤔 Why This Project?

- **Shows API integration skills** (Spotify, Yahoo Finance, etc.)  
- **Combines finance with culture/science for a unique twist**  
- **Storytelling + humor makes it memorable for a portfolio**  
- **Fully interactive & shareable online**  

---

## 🚀 Planned Output

- **Live Dashboard:** hosted on Streamlit Cloud  
- **GitHub Repo:** with code, data fetching scripts, and README  
- **Blog/Portfolio Link:** explaining the funniest “correlations”  

---

## 💡 Next Steps

- [ ] Implement Phase 1 (basic S&P vs Spotify dual-axis chart)  
- [ ] Expand signals and build dropdown selector  
- [ ] Add fun commentary & deploy  

---

*Because sometimes, the stock market doesn’t care about fundamentals… it cares about danceability, moon phases, and Lewis Hamilton.*  

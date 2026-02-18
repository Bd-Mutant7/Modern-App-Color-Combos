# 🔴 Clue - Period & Fertility Tracker Case Study

<div align="center">
  
  [![App](https://img.shields.io/badge/App-Clue-FF6B6B?style=flat-square)]()
  [![Category](https://img.shields.io/badge/Category-Health-4ECDC4?style=flat-square)](../)
  [![Users](https://img.shields.io/badge/Users-12M+-4A90E2?style=flat-square)]()
  [![Rating](https://img.shields.io/badge/Rating-4.8⭐-FFD700?style=flat-square)]()
  [![Founded](https://img.shields.io/badge/Founded-2013-00A86B?style=flat-square)]()
  
  ---
  
  | [⬅️ Back to Examples](./) | [🏠 Health Home](../README.md) | [🎨 Primary Palette](../primary-palette.md) | [🌙 Dark Mode](../dark-mode.md) | [💎 Luxury Style](../luxury-style.md) |
  |:---:|:---:|:---:|:---:|:---:|
  
</div>

## 📱 App Overview

**Clue** is a science-backed period and fertility tracker used by over 12 million people worldwide. Founded in 2013, it helps users understand their cycles, predict periods, and track fertility with accurate, data-driven insights. Clue is known for its clean, clinical approach to reproductive health, avoiding euphemisms and providing factual, unbiased information.

### Key Features
- **Cycle Prediction**: Accurate period start date predictions
- **Fertility Window Tracking**: Identify fertile days for conception or avoidance
- **Symptom Logging**: Track 30+ symptoms and moods
- **Health Insights**: Data-driven patterns and predictions
- **Private & Secure**: Strong privacy focus with anonymous data
- **Reminders**: Custom notifications for pills, periods, and more
- **Apple Health Integration**: Syncs with iOS health data

## 🎨 Color Palette Used

```css
:root {
  --primary: #4ECDC4;        /* Teal - Trust & Science */
  --secondary: #2C3E50;       /* Slate Gray - Information */
  --background: #FFFFFF;       /* White - Clean, Clinical */
  --period: #FF6B6B;           /* Coral - Menstruation */
  --fertile: #BFFF00;          /* Lime - Fertile Window */
  --ovulation: #6C5CE7;        /* Purple - Ovulation Day */
  --symptom: #4A90E2;          /* Blue - Symptoms Tracking */
  --prediction: #FFD93D;       /* Yellow - Approaching Dates */
  --success: #A8E6CF;          /* Mint - Positive Health */
}
```
## 📸 Screen Analysis
### Calendar View
The calendar is the heart of Clue, using intuitive color coding:

```text
March 2024
┌─────────────────────────────┐
│ M  T  W  T  F  S  S         │
│ 25 26 27 28 29 1░ 2░        │
│ 3░ 4░ 5░ 6░ 7░ 8░ 9░        │
│10░11░12░13░14░15░16▓▓       │
│17▓▓18▓▓19▓▓20▓▓21▓▓22▓▓     │
│23▓▓24▓▓25░░26░░27░░28░░      │
│29░░30░░31░░ 1  2  3  4       │
└─────────────────────────────┘
Legend: ░░ Fertile | ▓▓ Period | ██ Ovulation
```
## Symptom Logger

```css
.symptom-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 12px;
  padding: 16px;
}

.symptom-tag {
  background: #4A90E2;      /* Blue for neutral symptoms */
  color: white;
  padding: 12px;
  border-radius: 24px;
  text-align: center;
  font-size: 14px;
  transition: all 0.2s;
}

.symptom-tag.period-related {
  background: #FF6B6B;      /* Coral for period symptoms */
}

.symptom-tag.selected {
  transform: scale(1.05);
  box-shadow: 0 4px 12px rgba(0,0,0,0.2);
}
```
Blue icons (#4A90E2): Neutral, informative for general symptoms
Coral selection (#FF6B6B): When logging period-related symptoms
Clean white background (#FFFFFF): Easy data entry, clinical feel

## Insights Dashboard

```text
📊 CYCLE INSIGHTS
┌─────────────────────────────────┐
│ Average Cycle: 28 days    📈    │
│ Period Length: 5 days     🩸    │
│ Next Period: In 3 days    🔴    │
│ Fertile Window: Jun 12-18 🌱    │
│ Ovulation: Jun 16         ✨    │
└─────────────────────────────────┘

📈 TRENDS
┌─────────────────────────────────┐
│ Mood: 😊 Happy (45%)            │
│ Energy: ⚡ Medium (38%)         │
│ Sleep: 😴 7.2h avg              │
│ Symptoms: Headache (12% increase)│
└─────────────────────────────────┘
```
Teal graphs (#4ECDC4): Scientific, trustworthy data visualization
Coral trends (#FF6B6B): Cycle length patterns, period predictions
Purple highlights (#6C5CE7): Fertility insights, special events
Mint indicators (#A8E6CF): Positive health patterns


## 🧠 Why This Palette Works
1. Intuitive Color Coding

```css
/* The color logic is self-explanatory */
.period-day {
  background: #FF6B6B;  /* Red = menstruation - universal */
  color: white;
  border-radius: 50%;
}

.fertile-window {
  background: #BFFF00;  /* Green = go, fertile - hopeful */
  color: #2C3E50;
  animation: pulse 2s infinite;
}

.ovulation-day {
  background: #6C5CE7;  /* Purple = special, peak - celebratory */
  color: white;
  box-shadow: 0 0 10px rgba(108, 92, 231, 0.5);
}
```
## 💻 Implementation Details
Complete CSS Variables

```css
:root {
  /* Clue Theme - Complete System */
  --clue-primary: #4ECDC4;
  --clue-primary-dark: #3A9B94;
  --clue-primary-light: #7AD9D2;
  
  --clue-secondary: #2C3E50;
  --clue-secondary-light: #5A6A7A;
  
  --clue-background: #FFFFFF;
  --clue-surface: #F8FAFC;
  --clue-card: #FFFFFF;
  
  /* Cycle Tracking Colors */
  --clue-period: #FF6B6B;
  --clue-period-dark: #E04F4F;
  --clue-period-light: #FF8A8A;
  
  --clue-fertile: #BFFF00;
  --clue-fertile-dark: #A0D800;
  --clue-fertile-light: #CFFF33;
  
  --clue-ovulation: #6C5CE7;
  --clue-ovulation-dark: #5A4AC7;
  --clue-ovulation-light: #8A7CE9;
  
  --clue-symptom: #4A90E2;
  --clue-prediction: #FFD93D;
  --clue-success: #A8E6CF;
  
  /* Semantic Variables */
  --clue-text-primary: #2C3E50;
  --clue-text-secondary: #5A6A7A;
  --clue-border: #E2E8F0;
  --clue-shadow: rgba(0, 0, 0, 0.1);
}
```
Calendar Component CSS

```css
/* Calendar Grid */
.calendar-grid {
  display: grid;
  grid-template-columns: repeat(7, 1fr);
  gap: 4px;
  padding: 16px;
  background: var(--clue-surface);
  border-radius: 16px;
}

/* Day Cell Base */
.calendar-day {
  aspect-ratio: 1;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 14px;
  font-weight: 500;
  border-radius: 50%;
  cursor: pointer;
  transition: all 0.2s;
  position: relative;
}

/* Day Type Variations */
.calendar-day.period {
  background: var(--clue-period);
  color: white;
  box-shadow: 0 2px 8px rgba(255, 107, 107, 0.3);
}

.calendar-day.period:hover {
  background: var(--clue-period-dark);
  transform: scale(1.1);
}

.calendar-day.fertile {
  background: var(--clue-fertile);
  color: var(--clue-text-primary);
  border: 2px solid var(--clue-fertile-dark);
}

.calendar-day.fertile:hover {
  background: var(--clue-fertile-dark);
  color: white;
}

.calendar-day.ovulation {
  background: var(--clue-ovulation);
  color: white;
  animation: glow 2s infinite;
}

.calendar-day.ovulation::after {
  content: "✨";
  position: absolute;
  top: -5px;
  right: -5px;
  font-size: 12px;
}

.calendar-day.prediction {
  background: var(--clue-prediction);
  color: var(--clue-text-primary);
  opacity: 0.7;
}

.calendar-day.prediction::before {
  content: "~";
  margin-right: 2px;
}

@keyframes glow {
  0% { box-shadow: 0 0 5px var(--clue-ovulation); }
  50% { box-shadow: 0 0 20px var(--clue-ovulation); }
  100% { box-shadow: 0 0 5px var(--clue-ovulation); }
}

/* Selected State */
.calendar-day.selected {
  transform: scale(1.1);
  border: 3px solid white;
  box-shadow: 0 0 0 2px var(--clue-primary);
}
```

Symptom Tracker Component

```css
/* Symptom Categories */
.symptom-section {
  margin-bottom: 24px;
}

.symptom-section-title {
  color: var(--clue-text-primary);
  font-size: 16px;
  font-weight: 600;
  margin-bottom: 12px;
  padding-bottom: 4px;
  border-bottom: 2px solid var(--clue-primary);
}

/* Symptom Grid */
.symptom-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(100px, 1fr));
  gap: 12px;
}

/* Symptom Tags */
.symptom-tag {
  background: var(--clue-symptom);
  color: white;
  padding: 10px 16px;
  border-radius: 24px;
  font-size: 14px;
  text-align: center;
  cursor: pointer;
  transition: all 0.2s;
  border: none;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.symptom-tag:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(74, 144, 226, 0.3);
}

.symptom-tag.period-related {
  background: var(--clue-period);
}

.symptom-tag.period-related:hover {
  background: var(--clue-period-dark);
  box-shadow: 0 4px 12px rgba(255, 107, 107, 0.3);
}

.symptom-tag.selected {
  background: var(--clue-primary);
  transform: scale(1.05);
  box-shadow: 0 4px 12px rgba(78, 205, 196, 0.4);
}

/* Symptom Intensity */
.intensity-indicator {
  display: flex;
  gap: 4px;
  margin-top: 4px;
}

.intensity-dot {
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background: var(--clue-border);
  transition: background 0.2s;
}

.intensity-dot.active {
  background: var(--clue-period);
}
```
Insights Dashboard CSS

```css
/* Insights Cards */
.insight-card {
  background: var(--clue-card);
  border-radius: 16px;
  padding: 20px;
  margin-bottom: 16px;
  box-shadow: 0 4px 12px var(--clue-shadow);
  border: 1px solid var(--clue-border);
}

.insight-title {
  color: var(--clue-text-secondary);
  font-size: 14px;
  text-transform: uppercase;
  letter-spacing: 0.5px;
  margin-bottom: 8px;
}

.insight-value {
  color: var(--clue-text-primary);
  font-size: 32px;
  font-weight: 300;
  margin-bottom: 4px;
}

.insight-trend {
  display: flex;
  align-items: center;
  gap: 8px;
  color: var(--clue-text-secondary);
  font-size: 14px;
}

.trend-up {
  color: var(--clue-success);
}

.trend-down {
  color: var(--clue-period);
}

/* Charts */
.chart-container {
  background: var(--clue-surface);
  border-radius: 12px;
  padding: 20px;
  margin: 20px 0;
}

.chart-bar {
  height: 8px;
  background: var(--clue-primary);
  border-radius: 4px;
  margin: 4px 0;
  transition: width 0.3s;
}

.chart-bar.period {
  background: var(--clue-period);
}

.chart-bar.fertile {
  background: var(--clue-fertile);
}

.chart-legend {
  display: flex;
  gap: 20px;
  margin-top: 12px;
}

.legend-item {
  display: flex;
  align-items: center;
  gap: 6px;
  font-size: 12px;
  color: var(--clue-text-secondary);
}

.legend-color {
  width: 12px;
  height: 12px;
  border-radius: 4px;
}
```
React Component Example

```jsx
import React, { useState } from 'react';
import './ClueTheme.css';

const CycleCalendar = ({ cycleData, onDaySelect }) => {
  const [selectedDay, setSelectedDay] = useState(null);

  const getDayType = (day) => {
    if (day.isPeriod) return 'period';
    if (day.isOvulation) return 'ovulation';
    if (day.isFertile) return 'fertile';
    if (day.isPrediction) return 'prediction';
    return 'normal';
  };

  const handleDayClick = (day) => {
    setSelectedDay(day.date);
    onDaySelect(day);
  };

  return (
    <div className="calendar-grid">
      {['M', 'T', 'W', 'T', 'F', 'S', 'S'].map(day => (
        <div key={day} className="calendar-weekday">{day}</div>
      ))}
      
      {cycleData.map((day, index) => (
        <button
          key={index}
          className={`calendar-day ${getDayType(day)} ${selectedDay === day.date ? 'selected' : ''}`}
          onClick={() => handleDayClick(day)}
        >
          {day.date}
          {day.isOvulation && <span className="ovulation-star">✨</span>}
        </button>
      ))}
    </div>
  );
};

const SymptomLogger = ({ onSymptomsChange }) => {
  const [selectedSymptoms, setSelectedSymptoms] = useState([]);

  const symptoms = [
    { name: 'Cramps', category: 'period' },
    { name: 'Headache', category: 'general' },
    { name: 'Bloating', category: 'period' },
    { name: 'Fatigue', category: 'general' },
    { name: 'Spotting', category: 'period' },
    { name: 'Tender Breasts', category: 'period' },
    { name: 'Acne', category: 'general' },
    { name: 'Mood Swings', category: 'emotional' },
  ];

  const toggleSymptom = (symptom) => {
    const newSelected = selectedSymptoms.includes(symptom)
      ? selectedSymptoms.filter(s => s !== symptom)
      : [...selectedSymptoms, symptom];
    
    setSelectedSymptoms(newSelected);
    onSymptomsChange(newSelected);
  };

  return (
    <div className="symptom-grid">
      {symptoms.map((symptom, index) => (
        <button
          key={index}
          className={`symptom-tag ${symptom.category === 'period' ? 'period-related' : ''} ${
            selectedSymptoms.includes(symptom.name) ? 'selected' : ''
          }`}
          onClick={() => toggleSymptom(symptom.name)}
        >
          {symptom.name}
        </button>
      ))}
    </div>
  );
};

const InsightsDashboard = ({ cycleStats }) => {
  return (
    <div className="insights-dashboard">
      <div className="insight-card">
        <div className="insight-title">Average Cycle</div>
        <div className="insight-value">{cycleStats.averageCycle} days</div>
        <div className="insight-trend">
          <span>⬆️ +2 days from last cycle</span>
        </div>
      </div>

      <div className="insight-card">
        <div className="insight-title">Next Period</div>
        <div className="insight-value">In {cycleStats.daysUntilPeriod} days</div>
        <div className="insight-trend">
          <span className="trend-up">📅 {cycleStats.nextPeriodDate}</span>
        </div>
      </div>

      <div className="insight-card">
        <div className="insight-title">Fertile Window</div>
        <div className="insight-value">{cycleStats.fertileWindow}</div>
        <div className="insight-trend">
          <span className="trend-up">🌱 Ovulation: {cycleStats.ovulationDate}</span>
        </div>
      </div>

      <div className="chart-container">
        <h4>Symptom Trends</h4>
        {cycleStats.symptoms.map((symptom, index) => (
          <div key={index} style={{ marginBottom: '12px' }}>
            <div style={{ display: 'flex', justifyContent: 'space-between' }}>
              <span>{symptom.name}</span>
              <span>{symptom.frequency}%</span>
            </div>
            <div 
              className={`chart-bar ${symptom.category === 'period' ? 'period' : ''}`}
              style={{ width: `${symptom.frequency}%` }}
            />
          </div>
        ))}
      </div>
    </div>
  );
};

const ClueApp = () => {
  const [selectedDate, setSelectedDate] = useState(null);
  const [selectedSymptoms, setSelectedSymptoms] = useState([]);

  // Mock data
  const cycleData = Array.from({ length: 35 }, (_, i) => ({
    date: i + 1,
    isPeriod: i >= 22 && i <= 26,
    isFertile: i >= 15 && i <= 19,
    isOvulation: i === 18,
    isPrediction: i >= 28 && i <= 31,
  }));

  const cycleStats = {
    averageCycle: 28,
    daysUntilPeriod: 3,
    nextPeriodDate: 'Jun 24',
    fertileWindow: 'Jun 12-19',
    ovulationDate: 'Jun 16',
    symptoms: [
      { name: 'Cramps', frequency: 78, category: 'period' },
      { name: 'Bloating', frequency: 65, category: 'period' },
      { name: 'Headache', frequency: 42, category: 'general' },
      { name: 'Fatigue', frequency: 58, category: 'general' },
    ],
  };

  return (
    <div className="clue-app">
      <header style={{ background: 'var(--clue-primary)' }}>
        <h1>Clue</h1>
        <nav>
          <button>Calendar</button>
          <button>Log</button>
          <button>Insights</button>
          <button>Profile</button>
        </nav>
      </header>

      <main>
        <section className="calendar-section">
          <h2>March 2024</h2>
          <CycleCalendar 
            cycleData={cycleData} 
            onDaySelect={(day) => setSelectedDate(day)}
          />
        </section>

        <section className="logging-section">
          <h2>Log Symptoms</h2>
          <SymptomLogger onSymptomsChange={setSelectedSymptoms} />
        </section>

        <section className="insights-section">
          <h2>Your Insights</h2>
          <InsightsDashboard cycleStats={cycleStats} />
        </section>
      </main>
    </div>
  );
};

export default ClueApp;
```
React Native Component

```jsx
// CycleCalendar.js
import React from 'react';
import { View, Text, TouchableOpacity, StyleSheet } from 'react-native';

const CycleCalendar = ({ cycleData, onDaySelect }) => {
  const getDayStyle = (day) => {
    if (day.isPeriod) return styles.periodDay;
    if (day.isOvulation) return styles.ovulationDay;
    if (day.isFertile) return styles.fertileDay;
    if (day.isPrediction) return styles.predictionDay;
    return styles.normalDay;
  };

  return (
    <View style={styles.calendar}>
      {['M', 'T', 'W', 'T', 'F', 'S', 'S'].map(day => (
        <Text key={day} style={styles.weekday}>{day}</Text>
      ))}
      
      {cycleData.map((day, index) => (
        <TouchableOpacity
          key={index}
          style={[styles.dayCell, getDayStyle(day)]}
          onPress={() => onDaySelect(day)}
        >
          <Text style={styles.dayText}>{day.date}</Text>
          {day.isOvulation && <Text style={styles.ovulationEmoji}>✨</Text>}
        </TouchableOpacity>
      ))}
    </View>
  );
};

const styles = StyleSheet.create({
  calendar: {
    flexDirection: 'row',
    flexWrap: 'wrap',
    padding: 16,
    backgroundColor: '#F8FAFC',
    borderRadius: 16,
  },
  weekday: {
    width: '14.28%',
    textAlign: 'center',
    color: '#5A6A7A',
    fontWeight: '600',
    marginBottom: 8,
  },
  dayCell: {
    width: '14.28%',
    aspectRatio: 1,
    justifyContent: 'center',
    alignItems: 'center',
    borderRadius: 20,
    marginVertical: 2,
  },
  normalDay: {
    backgroundColor: '#F8FAFC',
  },
  periodDay: {
    backgroundColor: '#FF6B6B',
  },
  fertileDay: {
    backgroundColor: '#BFFF00',
  },
  ovulationDay: {
    backgroundColor: '#6C5CE7',
  },
  predictionDay: {
    backgroundColor: '#FFD93D',
    opacity: 0.7,
  },
  dayText: {
    fontSize: 14,
    fontWeight: '500',
    color: '#2C3E50',
  },
  ovulationEmoji: {
    position: 'absolute',
    top: -5,
    right: -5,
    fontSize: 12,
  },
});

export default CycleCalendar;
```
SwiftUI Implementation

```swift
import SwiftUI

struct ClueTheme {
    static let primary = Color(hex: "4ECDC4")
    static let secondary = Color(hex: "2C3E50")
    static let background = Color.white
    static let surface = Color(hex: "F8FAFC")
    static let period = Color(hex: "FF6B6B")
    static let fertile = Color(hex: "BFFF00")
    static let ovulation = Color(hex: "6C5CE7")
    static let symptom = Color(hex: "4A90E2")
    static let prediction = Color(hex: "FFD93D")
}

struct CycleDay: Identifiable {
    let id = UUID()
    let date: Int
    var isPeriod: Bool = false
    var isFertile: Bool = false
    var isOvulation: Bool = false
    var isPrediction: Bool = false
}

struct CycleCalendarView: View {
    let days: [CycleDay]
    @State private var selectedDay: CycleDay?
    
    var body: some View {
        VStack {
            // Weekday headers
            HStack {
                ForEach(["M", "T", "W", "T", "F", "S", "S"], id: \.self) { day in
                    Text(day)
                        .frame(maxWidth: .infinity)
                        .foregroundColor(ClueTheme.secondary.opacity(0.7))
                }
            }
            
            // Calendar grid
            LazyVGrid(columns: Array(repeating: GridItem(.flexible()), count: 7)) {
                ForEach(days) { day in
                    DayCell(day: day)
                        .onTapGesture {
                            selectedDay = day
                        }
                }
            }
        }
        .padding()
        .background(ClueTheme.surface)
        .cornerRadius(16)
    }
}

struct DayCell: View {
    let day: CycleDay
    
    var backgroundColor: Color {
        if day.isPeriod { return ClueTheme.period }
        if day.isOvulation { return ClueTheme.ovulation }
        if day.isFertile { return ClueTheme.fertile }
        if day.isPrediction { return ClueTheme.prediction }
        return Color.clear
    }
    
    var body: some View {
        ZStack {
            if backgroundColor != .clear {
                RoundedRectangle(cornerRadius: 20)
                    .fill(backgroundColor)
                    .frame(width: 40, height: 40)
            }
            
            Text("\(day.date)")
                .foregroundColor(day.isPeriod || day.isOvulation ? .white : ClueTheme.secondary)
            
            if day.isOvulation {
                Text("✨")
                    .font(.caption)
                    .offset(x: 10, y: -10)
            }
        }
        .frame(height: 40)
    }
}

struct SymptomTag: View {
    let name: String
    let isPeriodRelated: Bool
    @Binding var isSelected: Bool
    
    var body: some View {
        Text(name)
            .font(.system(size: 14))
            .padding(.horizontal, 16)
            .padding(.vertical, 8)
            .background(isPeriodRelated ? ClueTheme.period : ClueTheme.symptom)
            .opacity(isSelected ? 1 : 0.7)
            .foregroundColor(.white)
            .cornerRadius(20)
            .overlay(
                RoundedRectangle(cornerRadius: 20)
                    .stroke(isSelected ? Color.white : Color.clear, lineWidth: 2)
            )
            .scaleEffect(isSelected ? 1.05 : 1)
            .animation(.spring(), value: isSelected)
    }
}

struct ClueAppView: View {
    @State private var selectedSymptoms: Set<String> = []
    
    let days: [CycleDay] = {
        var days: [CycleDay] = []
        for i in 1...35 {
            var day = CycleDay(date: i)
            if i >= 22 && i <= 26 { day.isPeriod = true }
            if i >= 15 && i <= 19 { day.isFertile = true }
            if i == 18 { day.isOvulation = true }
            if i >= 28 && i <= 31 { day.isPrediction = true }
            days.append(day)
        }
        return days
    }()
    
    let symptoms = [
        ("Cramps", true),
        ("Headache", false),
        ("Bloating", true),
        ("Fatigue", false),
    ]
    
    var body: some View {
        NavigationView {
            ScrollView {
                VStack(spacing: 20) {
                    // Calendar Section
                    VStack(alignment: .leading) {
                        Text("March 2024")
                            .font(.headline)
                            .foregroundColor(ClueTheme.secondary)
                        
                        CycleCalendarView(days: days)
                    }
                    
                    // Symptoms Section
                    VStack(alignment: .leading) {
                        Text("Log Symptoms")
                            .font(.headline)
                            .foregroundColor(ClueTheme.secondary)
                        
                        ScrollView(.horizontal, showsIndicators: false) {
                            HStack {
                                ForEach(symptoms, id: \.0) { symptom in
                                    SymptomTag(
                                        name: symptom.0,
                                        isPeriodRelated: symptom.1,
                                        isSelected: .constant(selectedSymptoms.contains(symptom.0))
                                    )
                                    .onTapGesture {
                                        if selectedSymptoms.contains(symptom.0) {
                                            selectedSymptoms.remove(symptom.0)
                                        } else {
                                            selectedSymptoms.insert(symptom.0)
                                        }
                                    }
                                }
                            }
                        }
                    }
                    
                    // Insights Section
                    VStack(alignment: .leading) {
                        Text("Your Insights")
                            .font(.headline)
                            .foregroundColor(ClueTheme.secondary)
                        
                        VStack(spacing: 12) {
                            InsightCard(
                                title: "Average Cycle",
                                value: "28 days",
                                trend: "+2 days"
                            )
                            
                            InsightCard(
                                title: "Next Period",
                                value: "In 3 days",
                                trend: "Jun 24",
                                color: ClueTheme.period
                            )
                            
                            InsightCard(
                                title: "Fertile Window",
                                value: "Jun 12-19",
                                trend: "Ovulation: Jun 16",
                                color: ClueTheme.fertile
                            )
                        }
                    }
                }
                .padding()
            }
            .navigationTitle("Clue")
            .background(ClueTheme.background.ignoresSafeArea())
        }
    }
}

struct InsightCard: View {
    let title: String
    let value: String
    let trend: String
    var color: Color = ClueTheme.primary
    
    var body: some View {
        VStack(alignment: .leading, spacing: 8) {
            Text(title)
                .font(.caption)
                .foregroundColor(ClueTheme.secondary.opacity(0.7))
            
            Text(value)
                .font(.title2)
                .fontWeight(.light)
                .foregroundColor(color)
            
            Text(trend)
                .font(.caption)
                .foregroundColor(ClueTheme.secondary)
        }
        .frame(maxWidth: .infinity, alignment: .leading)
        .padding()
        .background(ClueTheme.surface)
        .cornerRadius(12)
    }
}
```
Dark Mode Support

```css
@media (prefers-color-scheme: dark) {
  :root {
    --background: #1A1E2B;
    --surface: #252A3A;
    --text: #E0E0E0;
    --period: #B84A4A;      /* Dimmed coral */
    --fertile: #8AA84A;      /* Dimmed lime */
    --ovulation: #5A4AC7;    /* Dimmed purple */
    --primary: #3A9B94;      /* Dimmed teal */
  }
  
  .calendar-day {
    color: var(--text);
  }
  
  .calendar-day.period {
    color: white;  /* Keep text readable */
  }
}
```


# 🏥 Health App - Real-World Examples

## Available Examples

| App | Description | Primary Colors | Link |
|-----|-------------|----------------|------|
| **MyChart** | Patient portal & medical records | `#4ECDC4` `#2C3E50` | [View Case Study](./mychart-example.md) |
| **Headspace** | Meditation & mindfulness | `#4ECDC4` `#FF6B6B` | [View Case Study](./headspace-example.md) |
| **Clue** | Period & fertility tracker | `#4ECDC4` `#2C3E50` | [View Case Study](./clue-example.md) |

## Navigation
- [Back to Health Category](../README.md)
- [Health Primary Palette](../primary-palette.md)
- [Health Dark Mode](../dark-mode.md)
- [Health Luxury Style](../luxury-style.md)
- [Back to Main README](../../README.md)

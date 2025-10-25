# AI_Project
SmartSpend  is an AI-powered expense tracking app built with React Native and Expo, designed to help users manage and analyze personal spending efficiently. The app allows users to add, view, and categorize expenses, visualize spending patterns, and receive AI-based financial insights. It uses React Context API for state management.

##  Features

-  **Track Expenses:** Add, view, and categorize transactions easily.  
-  **AI Insights:** Generates smart spending summaries and suggestions.  
-  **Local + Cloud Sync:** Uses Context API with optional Firebase sync.  
-  **Data Visualization:** Interactive pie charts using `react-native-chart-kit`.  
-  **Cross-Platform:** Runs on Android, iOS, and Web (via Expo).  
-  **Modular Architecture:** Clean separation of components, screens, and logic.

---

##  Project Structure

|
├── App.js
├── app.json
├── emptyModule.js
├── webpack.config.js
├── git_replay.sh
├── package.json
├── package-lock.json
│
├── expo/
│ └── devices.json
│
├── src/
│ ├── components/
│ │ ├── ExpenseItem.js
│ │ ├── SummaryCard.js
│ │ └── CategoryPieChart.js
│ │
│ ├── context/
│ │ ├── ExpenseContext.js
│ │ └── expenseReducer.js
│ │
│ ├── navigation/
│ │ └── AppNavigator.js
│ │
│ ├── screens/
│ │ ├── HomeScreen.js
│ │ ├── AddExpenseScreen.js
│ │ └── SummaryScreen.js
│ │
│ └── services/
│ ├── firebaseHelpers.js
│ └── aiSummary.js

---

## Installation & Setup

### 1️⃣ Clone the repository
git clone https://github.com/<your-username>/SmartSpend_v2.git
cd SmartSpend_v2
### 2️⃣ Install dependencies
Copy code
npm install
#### 3️⃣ Run the app
For mobile (Expo Go):
npx expo start --tunnel
For web (browser):
npx expo start --web


## Architecture Overview
1.State Management: React Context + Reducer pattern.
2.UI Components: Modular, reusable structure.
3.Data Layer: AsyncStorage and Firebase (optional).
4.AI Logic: /src/services/aiSummary.js analyzes expenses and suggests insights.
5.Charts: Rendered with react-native-chart-kit.
6.Navigation: Managed with React Navigation (Stack + Tabs).

## Future Enhancements
1. Integrate real OpenAI API for deeper spending insights.
2. Add Firebase authentication and cloud sync.
3. Export expense reports to PDF/CSV.
4. Add dark mode UI.

## Author
 Seema Kandi
B.Tech ECE | Aspiring Software Developer
seemakandi1298@gmail.com

## License

This project is licensed under the MIT License — feel free to modify and distribute it with attribution.

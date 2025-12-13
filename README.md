# 🧘‍♂️ Indian AI Fitness Coach – *Guru-ji*

**Your Personalized AI Guru for Health & Wellness 🇮🇳**

Indian AI Fitness Coach is a modern, AI-powered **Progressive Web App (PWA)** designed specifically for the **Indian demographic**.  
Unlike generic fitness apps, it leverages **Google Gemini models** to deliver **hyper-personalized diet plans, workouts, and coaching**, aligned with Indian food habits, budgets, and lifestyles.

Whether your goal is **fat loss, muscle gain, or overall fitness**, *Guru-ji* acts as your **24/7 AI fitness coach**, right in your pocket.

---

## 🚀 Key Features

### 🥗 Hyper-Localized Diet Planning
- **Region-Specific Meals**  
  North, South, East & West Indian cuisines (Roti/Dal, Idli/Dosa, Rice meals, etc.)
- **Diet Preferences Supported**  
  Vegetarian, Non-Vegetarian, Jain
- **Budget Aware AI**  
  - Low: Lentils, seasonal vegetables  
  - Medium: Balanced staples  
  - Flexible: Premium options like Greek yogurt, nuts, avocados
- **Allergy-Safe Recipes**  
  Strict AI guardrails to exclude allergens
- **One-Click Meal Swap**  
  Instantly replace meals with calorie-matched alternatives

---

### 🏋️ Adaptive Workout Routines
- **Home or Gym Workouts**
  - Equipment-free home workouts
  - Full gym splits (Push / Pull / Legs, 7-day plans)
- **AI-Designed Structure**
  - Warm-up
  - Main workout (sets & reps)
  - Cool-down
- **Manual Activity Logging**
  - Walking, cricket, yoga, etc.
  - Auto calorie burn estimation

---

### 🤖 AI Body Analysis (Computer Vision)
- **Gemini Vision Integration**
- Upload a full-body image to receive:
  - Somatotype analysis (Ectomorph / Mesomorph / Endomorph)
  - Basic posture insights
- **Privacy-Focused**: No image storage, local processing intent only

---

### 💬 “Guru-ji” AI Chatbot
- **Context-Aware Coaching**
  - Knows your goals, diet type, workouts & injuries
- **Ask Anything**
  - Exercise form tips
  - Food alternatives
  - Daily motivation
- Friendly, encouraging **Indian Guru persona**

---

### 📊 Smart Dashboard & Tracking
- **Calorie Command Center**
  - Calories In vs Calories Out visual rings
- **Macro Tracking**
  - Auto-calculated Protein, Carbs, Fats
  - Custom macro goals supported
- **Gamification**
  - Daily streaks
  - Weekly fitness verdicts

---

## 🛠 Tech Stack

### Frontend
- **React.js (v19)**
- **TypeScript**
- **Tailwind CSS**
  - Dark Mode support

### AI Integration
- **Google GenAI SDK** (`@google/genai`)
- **Models Used**
  - `gemini-3-pro-preview` – Diet & Workout reasoning
  - `gemini-2.5-flash` – Chat & text generation
  - `gemini-2.5-flash-image` – Body analysis (vision)

### Other Tools
- **Icons:** Lucide React
- **State Management:** React Hooks
- **Storage:** LocalStorage (No backend required)

---

## 📱 User Experience
- **Mobile-First PWA Design**
- **Dark Mode**
  - System-aware theme switching
- **Privacy First**
  - All user data stored locally
  - No external database or tracking
- **Smooth Onboarding**
  - Step-by-step wizard:
    - Age, height, weight
    - Fitness goals
    - Diet preferences & restrictions

---

## 🔮 Future Roadmap
- 📦 Offline PWA support
- 🎙 Voice interaction – *“Talk to Guru-ji”*
- 📤 Social sharing (WhatsApp / Instagram)
- 📈 Advanced analytics & progress insights

---

## 🧑‍💻 Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/indian-ai-fitness-coach.git

# Install dependencies
npm install

# Start development server
npm run dev

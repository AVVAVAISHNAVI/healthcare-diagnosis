Healthcare Diagnosis System 🩺
A multilingual, AI-powered terminal application that helps users identify possible diseases based on their symptoms and provides custom health recommendations — all from your command line!
🚀 Features
🔎 Symptom-to-Disease Diagnosis – Matches user symptoms against a curated disease database.
🌐 Multilingual Input – Supports both English and Hinglish (Hindi in Roman script).
📄 PDF Report Export – Automatically generates a professional report with diagnosis details.
🗂️ Diagnosis History Log – Saves patient name, age, symptoms, and predictions to diagnosis_history.txt.
💡 Treatment Guidance – Offers do’s and don’ts for each predicted condition.
📚 Rich Database – 50+ diseases with symptoms, severity scores, and Hindi translations.
⚙️ How It Works
User selects their preferred language (English or Hinglish).
They enter their name, age, and a comma-separated list of symptoms.
The system:
Translates symptoms if needed,
Matches them to possible conditions,
Calculates confidence percentages,
Displays the top 3 most likely diseases,
Provides guidance tips for each.
Results are:
Logged to diagnosis_history.txt
Exported as a PDF report for future reference.
├── diagnosis.py           # Main program (input, logic, PDF export, logging)
├── database.py            # Disease database with symptoms, weights, Hindi names
├── symptom_translation.py # Symptom translation (English ↔ Hinglish)
├── diagnosis_history.txt  # Log file storing all past results
📌 Example Usage
Enter your name: Vaish
Enter your age: 21
Enter symptoms: cough, fever
Possible Conditions:
- Flu (66%)
- Swine Flu (60%)
- Measles (50%)
🌟 Possible Improvements
🖥 GUI Interface (Tkinter or React-based web app)
🎤 Voice Input (speech recognition for symptoms)
🤖 AI/ML Integration (train ML models for smarter predictions)
📱 Mobile App Version (Android/iOS support)
🌍 Support More Languages (Gujarati, Marathi, Tamil, Telugu, etc.)
🔎 Symptom Autocomplete (fuzzy matching as user types)
☁️ Cloud Sync (secure online history with analytics dashboard)
🖨 Printable Reports (clinic-style formatted outputs)
📊 Stats Dashboard (visualize common diagnoses over time)
🔐 User Authentication (secure personal health logs)


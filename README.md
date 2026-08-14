# 🌍 Smart Tourism Travel Planning Automation

An AI-powered travel planning automation system built using **n8n, Groq, Google Sheets, Google Calendar, Gmail, Geocoding API, Weather API, and JavaScript**.

The system collects customer travel preferences, recommends a suitable destination using AI, retrieves location and weather information, generates a personalized itinerary, creates a calendar event, stores the final record, and sends the travel plan through email.

---

## 📄 Abstract

The **Smart Tourism Travel Planning Automation** is an AI-powered workflow designed to automate the travel planning process using **n8n and Groq AI**. The system collects customer preferences such as budget, travel dates, duration, number of travelers, interests, accommodation, and transportation preferences.

The workflow analyzes this information using AI to recommend suitable destinations and generate personalized travel itineraries. It integrates **Geocoding and Weather APIs** to enrich the recommendations with location and weather information. The final travel plan is automatically stored in **Google Sheets**, scheduled in **Google Calendar**, and delivered through **Gmail**.

This project demonstrates how AI, APIs, and workflow automation can be combined to create an efficient, personalized, and scalable smart tourism solution with minimal manual intervention.

---

## 🎯 Problem Statement

Traditional travel planning involves several manual tasks:

- Collecting customer requirements
- Selecting suitable destinations
- Checking weather conditions
- Creating itineraries
- Maintaining customer records
- Scheduling trips
- Sending personalized travel plans

This project automates these activities using an AI-powered n8n workflow.

---

## 💡 Solution

The complete workflow is:

**Customer Registration → Data Processing → AI Recommendation → Geocoding → Weather API → Personalized Itinerary → Google Calendar → Premium Recommendations → Google Sheets → Gmail**

---

## 🚀 Key Features

- 📝 Automated travel registration
- 🤖 AI-powered destination recommendation using Groq
- 🧠 Personalized itinerary generation
- 🌍 Destination geocoding
- 🌦️ Weather API integration
- 📊 Google Sheets data storage
- 📅 Google Calendar event creation
- 📧 Automated Gmail notification
- 💎 Premium travel recommendations
- 🔀 Conditional branching using IF nodes
- 💻 JavaScript data processing

---

## 🏗️ Workflow Architecture

### 1. Customer Registration

The customer provides:

- Full Name
- Email
- Phone Number
- Travel Date
- Number of Travelers
- Budget
- Trip Duration
- Travel Interests
- Accommodation Preference
- Transportation Preference

### 2. AI Destination Recommendation

Groq analyzes the customer's:

- Budget
- Trip duration
- Number of travelers
- Interests
- Accommodation preference
- Transportation preference

and recommends a suitable destination.

### 3. Destination & Weather Enrichment

The recommended destination is processed using:

- **Geocoding API** — retrieves location information
- **Weather API** — retrieves weather information

### 4. Personalized Itinerary

Groq generates a personalized day-wise travel plan containing:

- Activities
- Food recommendations
- Estimated costs
- Travel tips
- Weather precautions
- Packing suggestions

### 5. Final Automation

The workflow automatically:

- Creates a Google Calendar event
- Stores the final travel record in Google Sheets
- Generates premium recommendations
- Sends a personalized Gmail

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| **n8n** | Workflow automation and orchestration |
| **Groq / Llama 3.3 70B** | AI-powered destination recommendations and itinerary generation |
| **Google Sheets** | Customer data and final travel record storage |
| **Google Calendar** | Automatic trip/event scheduling |
| **Gmail** | Personalized email delivery |
| **Geocoding API** | Converts destinations into location coordinates |
| **Weather API** | Retrieves destination weather information |
| **JavaScript** | Data transformation and processing |
| **GitHub** | Project version control and documentation |

---

## 📊 Example

### Customer Input

- Travelers: 3
- Budget: ₹40,000
- Duration: 10 days
- Interests: Beaches, Cafe, Sunset
- Accommodation: 5 Star
- Transportation: Train

### Generated Output

**Destination:** Goa, India

The system generates:

- Personalized itinerary
- Weather information
- Estimated trip cost
- Travel tips
- Premium recommendations
- Google Calendar event
- Google Sheets record
- Personalized Gmail

---

## 📸 Screenshots

### 📝 Travel Registration Form

The registration form collects essential customer travel preferences, including personal details, travel date, number of travelers, budget, trip duration, interests, accommodation, and transportation preferences. This information is used by the automation workflow to generate a personalized travel plan.

![Travel Registration Form](form.png)

### 🔄 Complete n8n Workflow

The complete automation workflow showing the flow from customer registration to AI processing, API integrations, itinerary generation, and final communication.

![Complete n8n Workflow](n8n-workflow.png)

---

### 📅 Google Calendar

Automatically creates a Google Calendar event containing the customer's planned travel details.

![Google Calendar](google-calendar.png)

---

### 🗓️ Google Calendar Itinerary

Displays the scheduled travel itinerary and important trip activities directly in Google Calendar.

![Google Calendar Itinerary](google-calendar-it.png)

---

### 🧳 Personalized Itinerary

Shows the AI-generated personalized travel plan based on the customer's destination, budget, duration, interests, and preferences.

![Personalized Itinerary](personalized-itinerary1.png)

---

### 📧 Gmail Output

The final personalized travel plan is automatically delivered to the customer through Gmail, including itinerary details, weather information, travel tips, and recommendations.

![Gmail Output](confirmation-email.png)

---
# 🎓 Capstone Highlights

This project demonstrates practical implementation of:

- 🤖 **AI-powered decision making**
- 🔄 **End-to-end workflow automation**
- 🔗 **REST API integration**
- 🌍 **Location-based travel services**
- 🌦️ **Weather-aware travel planning**
- 🧠 **AI-generated destination recommendations**
- 🗓️ **Personalized itinerary generation**
- 🔀 **Conditional workflow branching**
- 💻 **JavaScript data processing**
- 📊 **Automated Google Sheets data storage**
- 📅 **Google Calendar automation**
- 📧 **Automated Gmail communication**
- 💎 **AI-powered premium recommendations**
- 🔐 **Secure credential management**
- 🚀 **Complete business process automation**
- 🔗 **Integration of multiple external services**
- 📈 **Centralized travel record management**

---

# 🌍 Real-World Applications

The system can be adapted for:

- ✈️ Travel agencies
- 🌐 Tourism companies
- 💼 Corporate travel management
- 🧳 Personalized travel platforms
- 🏨 Hotel and resort services
- 📍 Destination recommendation platforms
- 👨‍💼 Travel consultants
- 🤖 AI travel assistants

---

# ⚠️ Limitations

- AI recommendations may require human verification.
- Weather information depends on external API availability.
- Estimated costs may differ from actual travel prices.
- External API failures may affect workflow execution.
- Real-time hotel and flight booking is not currently included.
- The system currently focuses on travel planning rather than direct booking.

---

# 🔮 Future Scope

Future versions can include:

- ✈️ Flight booking integration
- 🏨 Hotel booking integration
- 🚆 Train booking integration
- 💬 WhatsApp travel notifications
- 🤖 AI travel chatbot
- 💳 Online payment integration
- 💰 Real-time travel pricing
- 🗺️ Interactive travel maps
- 📍 Live location tracking
- ⭐ Customer feedback automation
- 🌍 Multi-destination trip planning
- 📈 Travel analytics dashboard
- ⏰ Automated travel reminders
- 👤 Human approval workflow
- 🔁 Advanced error handling and retry mechanisms

---

# 🏆 Capstone Project

This project was developed as an **AI-powered workflow automation capstone project**, demonstrating how modern AI services, APIs, and automation platforms can be combined to solve a real-world business problem.

The system transforms a simple customer travel request into a complete personalized travel experience with minimal manual intervention.

---

# 👨‍💻 Author

## Palak

**Project:** Smart Tourism Travel Planning Automation

**GitHub:** [Palak](https://github.com/palak-singh-20)

---

# 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Commit your changes.
5. Push the branch.
6. Open a Pull Request.

---

# 📜 License

This project is licensed under the **MIT License**.

---

<div align="center">

# 🌍 Smart Tourism Travel Planning Automation

### 🤖 Plan Smarter • Travel Better • Automate Everything

Built with ❤️ using **n8n, Groq AI, Google APIs, JavaScript, and Automation**

⭐ If you found this project useful, consider giving the repository a Star!

</div>

ShieldX – AI-Based Income Protection for Delivery Workers

ShieldX is an AI-powered parametric insurance platform designed to protect the income of delivery workers from external disruptions.

Problem:- 
       In today’s fast-growing gig economy, delivery partners such as those working for Swiggy, Zomato, and other platforms depend completely on daily work to earn money. However, their income is highly affected by external factors like heavy rain, pollution, or sudden curfews. During such situations, they are unable to work and end up losing a significant portion of their earnings. At present, there is no proper system that protects their income during these unavoidable disruptions.

Our Idea:-
       To solve this problem, we developed ShieldX, a simple AI-based insurance platform that focuses only on protecting the income of delivery workers. Instead of traditional insurance, our system automatically detects external disruptions and provides compensation without requiring the user to manually file a claim.

Persona Scenario:-
       Let us consider a delivery partner named Ravi. He usually works around 10 hours a day and earns approximately ₹800. On a day with heavy rain, he is unable to work for several hours and loses almost half of his daily income. With ShieldX, the system detects the rain condition and automatically provides a payout to compensate for his lost income.

How the System Works:-
      The workflow of our system is very simple and user-friendly. First, the delivery partner registers on the platform. The system then evaluates environmental conditions such as weather and pollution levels. Based on this, it calculates a risk score. Using this score, a weekly premium is generated. The system continuously monitors for disruptions, and whenever a condition like heavy rain occurs, it automatically triggers a claim and provides an instant payout to the user.

Weekly Premium Model:-
     Our pricing model is designed according to the weekly earning pattern of gig workers. We start with a base premium of ₹50 per week and add a small amount based on the calculated risk. For example, if the risk score is 70, the premium becomes ₹85 per week. This makes the system affordable and practical for delivery workers.

Innovation:-
     Fully automated claim system (no manual request)
     Real-time disruption detection
     Weekly pricing tailored for gig workers

Parametric Triggers:-
    Instead of manual claim requests, our system uses predefined conditions to trigger claims. These include heavy rainfall, high pollution levels, and restricted movement due to curfews. Once any of these conditions crosses a certain limit, the system automatically approves the claim and initiates the payout.

AI Integration:-
    Although this is a prototype, we have simulated AI-based decision-making in the system. The application calculates a risk score using environmental data and adjusts the premium accordingly. It also includes basic fraud detection by checking user location and preventing duplicate claims. In future versions, this can be enhanced using real machine learning models.

Platform Choice:-
    We chose to build this as a web application because it is easy to access, faster to develop within the hackathon time, and does not require installation. It can be used on both mobile and desktop devices.

Flowchart:-

Start  
↓  
User Opens App  
↓  
Register / Login  
↓  
Collect Data (Weather + Pollution)  
↓  
Calculate Risk Score  
↓  
Generate Weekly Premium  
↓  
User Buys Policy  
↓  
Monitor Conditions  
↓  
Disruption Occurred?  
→ No → Continue Monitoring  
→ Yes → Trigger Claim  
↓  
Fraud Check  
↓  
Claim Approved  
↓  
Instant Payout  
↓  
End  

Tech Stack:-
     For the frontend, we used React along with HTML and CSS to build a simple and interactive user interface. The backend logic is currently simulated using JavaScript. External APIs such as weather services are mocked for demonstration purposes.

Development Plan:-
     In this phase, we focused on building the basic idea, designing the user interface, and implementing core features like risk calculation, premium generation, and claim simulation. In future phases, we plan to integrate real APIs, improve the AI model, add payment gateways, and build a detailed analytics dashboard.

Key Features Implemented:-
    The current prototype includes risk score calculation, weekly premium generation, automatic claim simulation based on rain conditions, and a simple dashboard for user interaction.

Conclusion:-
   ShieldX provides a simple and practical solution to protect the income of delivery workers. By using automation and basic AI logic, the system removes the need for manual claims and ensures quick financial support during difficult situations.

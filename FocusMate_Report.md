
Privacy-Focused, Context-Aware Digital Wellbeing System (FocusMate)

Design and Fabrication Project (DFP–16)
PDPM Indian Institute of Information Technology, Design and Manufacturing, Jabalpur
Supervisor: Dr. Yashpal Singh Katharria, Department of Natural Sciences
Academic Year: 2025–26

Team Members:
Aayushman Anand (23BCS005)
Shelke Sakshi Vishwas (23BCS231)
Kunal Meena (23BEC065)
Sahil (23BEC098)
Pawni Jain (23BDS038)
Anjali Kamal (23BSM009)

Abstract
The increasing prevalence of shared workspaces such as hostels, libraries, co-working spaces, and open offices has brought new challenges related to privacy, concentration, and digital wellbeing. Existing solutions, including software-based Do Not Disturb modes and headphones, offer only partial relief and do not address the gap between digital intent and physical presence. This project introduces FocusMate, a privacy-focused, context-aware digital wellbeing system designed as a smart desktop companion. FocusMate integrates proximity sensing, intelligent notification classification, automatic device locking, and mindful usage reminders in a non-intrusive physical form.

The system combines hardware sensing and software logic to detect user presence (5–7 m), classify notifications, lock devices, mute microphones when the user moves away, and provide wellness prompts through a TFT display and ambient light cues. User studies, survey analysis, and SWOT evaluation confirm the relevance and feasibility of the proposed solution. FocusMate aims to enhance productivity, protect privacy, and promote healthy digital habits in shared environments.

Table of Contents
1. Introduction
2. Literature Review
3. User Study and Validation
4. System Overview
5. Hardware Architecture
6. Software Architecture
7. Mechanical Design
8. Mindful Interaction Design
9. Fabrication Plan
10. SWOT Analysis
11. Expected Outcomes
12. Ethics and Privacy Considerations
13. Conclusion
14. Future Scope
15. References
16. Appendix

1. Introduction
Modern digital life is characterized by continuous notifications, prolonged screen exposure, and frequent interruptions. In shared environments, these issues are amplified by the absence of physical boundaries and privacy cues. Students and professionals often experience distraction, reduced productivity, and discomfort during private calls or focused work.

Digital wellbeing tools are predominantly software-centric and invisible to people physically present. There is a clear need for a tangible, context-aware system that communicates focus and privacy states while helping users manage digital overload.

Problem Statement
• Frequent interruptions in shared workspaces
• Private calls and conversations easily overheard
• Software-only DND modes are invisible in physical spaces
• Lack of automated privacy control when users step away from devices

Objectives
• Design a physical, context-aware system that enhances focus and privacy
• Integrate proximity-based automation for device locking and microphone control
• Intelligently classify notifications and reduce non-essential interruptions
• Encourage healthy digital habits through mindful reminders
• Validate the system through user studies and design analysis

2. Literature Review
Privacy in Shared Workspaces
Open-plan offices and shared workspaces foster collaboration but also lead to increased distraction and reduced speech privacy. Studies (Banbury & Berry, 1998) show that background speech is highly disruptive. ISO 3382-3:2012 provides guidelines for acoustic privacy.

Acoustic Privacy Technologies
White noise and babble noise are used to mask speech and enhance confidentiality. Adaptive sound masking, which adjusts to ambient noise, is considered best practice (Hongisto, 2005).

Context-Aware Systems
Context-aware systems adapt to user and environmental data in real time (Weiser, 1991). Advances in IoT and edge computing enable secure, responsive privacy solutions.

3. User Study and Validation
Digital Device Usage Analysis
Survey results:
• Less than 4 hours: 12%
• 4–8 hours: 46%
• 8–12 hours: 30%
• More than 12 hours: 12%

User Interest in Context-Aware Systems
• Strongly Interested: 58%
• Interested: 27%
• Neutral: 10%
• Not Interested: 5%

Key Insights
• Frequent interruptions during study/work
• Privacy discomfort during calls
• Existing solutions are insufficient
• Strong demand for physical, context-aware indicators

4. System Overview
Concept Description
FocusMate is a desktop companion that monitors user presence and context to manage notifications, privacy, and wellbeing automatically. It bridges digital systems and physical environments.

Key Features
• Smart Notification Classification
• Automatic Device Locking
• Mindful Usage Reminders
• Physical Presence Awareness
• Visual and Ambient Feedback

[Place for Concept Sketch or Render]

5. Hardware Architecture
Major Hardware Components
• Embedded Controller (Raspberry Pi class)
• Proximity Sensor (5–7 m range)
• TFT Display (Dashboard and Notifications)
• Microphone Control Module
• Speaker / Audio Output
• Power Management Unit
• Robot-like Enclosure

Hardware Block Description
The controller receives inputs from sensors, executes logic, and drives outputs such as display, audio, and lock signals.

[Place for Hardware Block Diagram]

6. Software Architecture
Functional Modules
• Presence Detection Module
• Notification Classification Engine
• Focus Scheduling and Control Logic
• Device Control Interface
• Mobile App (Simulator)

Software Flow
1. System Initialization
2. Continuous Context Monitoring
3. Decision Logic Execution
4. Action Trigger (Lock, Notify, Remind)
5. Visual and Audio Feedback Update

[Place for Software Flowchart]

7. Mechanical Design
Form Factor
The device features a compact, friendly appearance suitable for desktop placement. It is fabricated using 3D printing techniques.

Design Considerations
• Non-intrusive aesthetics
• Stable base
• Clear display visibility
• Efficient heat dissipation

[Place for CAD Model or Mechanical Drawing]

8. Mindful Interaction Design
Smart Notification Display
Urgent calls and messages are shown prominently, while low-priority notifications are deferred during focus sessions.

Wellness Prompts
Reminders include:
• Deep breaths
• Hydration
• Light exercises
• Healthy snacks
These prompts are delivered using soft visuals and ambient lighting.

[Place for Notification Display and Wellness Prompt Examples]

9. Fabrication Plan
Manufacturing Process
• 3D printing chassis
• Wet-sanding, priming, painting
• Laser-cut acrylic processing

Assembly Integration
• Mounting Raspberry Pi
• Connecting display and sensors
• Assembling enclosure

[Place for Exploded Assembly View]

10. SWOT Analysis
Strengths
• Context-aware decision making
• Physical and digital integration
• Enhanced privacy and focus
• Fabrication-ready design
• Non-intrusive experience

Weaknesses
• Sensor calibration
• Setup complexity
• Environment dependency
• User trust in automation

Opportunities
• Growth of shared workspaces
• Digital wellbeing awareness
• Smart workspace integration
• Assistive technology applications

Threats
• Privacy concerns
• Cost sensitivity
• Software-only competitors
• Adoption resistance

11. Expected Outcomes
• Reduced distractions
• Improved privacy
• Increased healthy digital habits
• Enhanced productivity

12. Ethics and Privacy Considerations
FocusMate is designed with privacy-by-design principles. No sensitive audio is stored or transmitted; all processing is local, ensuring user confidentiality and compliance with ethical standards.

13. Conclusion
FocusMate offers a holistic approach to digital wellbeing by combining context-aware sensing, physical presence awareness, and mindful interaction design. The system addresses gaps left by software-only solutions and provides a tangible, user-friendly method to enhance privacy and focus. Validation through user studies and design analysis confirms the need for such systems.

14. Future Scope
• ML-based notification prioritization
• Gesture-based interaction
• Expanded mobile app integration
• Smart home and workspace compatibility
• Battery-powered portable version

15. References
1. Banbury & Berry, "Disruption of office-related tasks by speech," British Journal of Psychology, 1998.
2. ISO 3382-3:2012, "Acoustics – Measurement of room acoustic parameters – Part 3: Open plan offices."
3. Hongisto, "A model predicting the effect of speech of varying intelligibility on work performance," Indoor Air, 2005.
4. Weiser, "The Computer for the 21st Century," Scientific American, 1991.
5. Li, Xu, Zhao, "The internet of things: a survey," Information Systems Frontiers, 2022.

16. Appendix
[Place for Additional Images, Survey Data, or Supporting Material]

End of Report

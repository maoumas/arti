📡 Zmau Broadcast Master Suite
Overview
The Zmau Broadcast Master Suite is a set of web-based tools designed to streamline the workflow of live broadcasts, presentations, and mission reports. It separates the technical complexity of setup from the operational simplicity required during a live show.
The ecosystem consists of two primary applications:
	1	Teleprompter Studio (Admin): For script creation and staging.
	2	Master Control Generator (Gen-KZ): For creating the operator's environment.
🛠️ Application 1: Master Control Generator (gen-kz)
URL: https://zmau.dev/master/gen-kz
Purpose
This tool solves the "tech anxiety" problem for operators. It allows a producer to take disparate resources (Slide URLs, Script URLs, Protocol Notes) and compile them into a single, standalone HTML file (The "Control Center").
How It Works
	1	Input Data: The producer fills in the "Mission Data" (ID, Location, Title, Description) and pastes the links to the Google Slides and the Teleprompter.
	2	Configuration:
	•	Language: Select German (DE), Spanish (ES), or English (EN). This localizes the interface for the operator.
	•	Theme: Select a visual style (Original Blue/Gold, Nebula Purple, or Daylight) to match the lighting conditions or mood of the broadcast.
	3	Generate: The tool generates a new HTML file.
	4	Deploy: This file is sent to the operator or hosted. The operator simply opens this file to have everything they need in one view.
The Result (The "Control Center")
The generated file is a robust, offline-capable (except for iframes) dashboard containing:
	•	Embedded Presentation: A live view of the Google Slides.
	•	Teleprompter Link: A direct, styled button to launch the script.
	•	Protocol Notes: Clear instructions on tone and delivery.
	•	Visual Feedback: Status indicators (System Online, Secure Connection) to reassure the operator.
📝 Application 2: Teleprompter Studio (admin)
URL: https://zmau.dev/master/admin
Purpose
A professional-grade script editor and teleprompter engine.
Workflow
	1	Write/Import: Write the script using Markdown syntax (# for Titles, * for Instructions).
	2	Configure: Set the scroll speed and font size.
	3	Publish: Generate a "Player" link or file.
	4	Link: This "Player" link is what you paste into the Master Control Generator.
🔄 The Workflow Cycle
	1	Create Script in Teleprompter Studio -> Get URL.
	2	Create Slides in Google Slides -> Get URL.
	3	Open Master Control Generator.
	4	Paste URLs and configure Mission Data.
	5	Download HTML and hand it off to the Talent/Operator.

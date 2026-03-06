⚡ Mahadiscom Website Automation Using UiPath
📌 Project Description

This project demonstrates Robotic Process Automation (RPA) using UiPath to automate tasks on the Maharashtra State Electricity Distribution Company Limited (Mahadiscom / MSEDCL) website.

The automation bot interacts with the Mahadiscom portal to automatically retrieve electricity bill details using a consumer number, eliminating manual searching and repetitive data entry.

The system launches a browser, navigates to the Mahadiscom website, inputs the consumer number, extracts bill information, and stores the results in structured files such as Excel or CSV.

This project is useful for learning web automation, data extraction, and RPA workflow design using UiPath.

🎯 Project Objectives

Automate electricity bill retrieval from the Mahadiscom portal

Reduce human effort in repetitive web tasks

Demonstrate RPA implementation using UiPath Studio

Extract and store data in structured formats (Excel/CSV)

Improve efficiency and accuracy in data collection

🧠 Key Concepts Used
1️⃣ Robotic Process Automation (RPA)

RPA uses software robots to automate repetitive digital tasks such as logging into websites, entering data, and extracting information.

2️⃣ Web Automation

UiPath interacts with web elements like:

Buttons

Text fields

Links

Tables

3️⃣ Data Scraping

The bot extracts data such as:

Consumer number

Bill amount

Due date

Billing cycle

Payment status

4️⃣ Excel Integration

Extracted data is automatically stored into Excel for further analysis or record keeping.

⚙️ Technologies Used
Technology	Purpose
UiPath Studio	RPA Development
Web Automation Activities	Automating website interaction
Excel Activities	Storing and processing extracted data
Windows OS	Running automation bot
Mahadiscom Web Portal	Source of electricity bill information
🌐 Target Website

The automation interacts with the official electricity distribution portal of Maharashtra State Electricity Distribution Company Limited.

Services automated may include:

Bill details retrieval

Consumer information lookup

Billing status checking

🔄 Automation Workflow
Step 1 — Start Process

The bot starts execution in UiPath Studio.

Step 2 — Launch Browser

A browser instance opens automatically.

Step 3 — Navigate to Website

The bot navigates to the Mahadiscom website.

Step 4 — Enter Consumer Number

The bot enters the electricity Consumer Number in the input field.

Step 5 — Retrieve Data

The system extracts bill information such as:

Consumer name

Billing period

Bill amount

Due date

Payment status

Step 6 — Store Data

Extracted data is saved in an Excel file.

Step 7 — Close Browser

The bot closes the browser and completes execution.

📂 Project Folder Structure
Mahadiscom-UiPath-Automation
│
├── Main.xaml
├── project.json
├── README.md
│
├── Data
│   └── ConsumerNumbers.xlsx
│
├── Output
│   └── BillDetails.xlsx
│
└── Screenshots
    ├── workflow.png
    ├── execution.png
▶ How to Run the Project
1️⃣ Install UiPath Studio

Download and install UiPath Studio Community Edition.

2️⃣ Clone the Repository
git clone https://github.com/yourusername/mahadiscom-uipath-automation.git
3️⃣ Open the Project

Open the project folder in UiPath Studio.

4️⃣ Configure Input Data

Update the Consumer Number in:

Data/ConsumerNumbers.xlsx
5️⃣ Run the Automation

Click Run inside UiPath Studio.

The bot will automatically retrieve the bill details.

📊 Output Example
Consumer Number	Consumer Name	Bill Amount	Due Date	Status
1234567890	ABC Patil	₹1250	25-10-2025	Unpaid
🧩 UiPath Activities Used

Open Browser

Navigate To

Type Into

Click

Get Text

Data Scraping

Write Range (Excel)

Close Tab

📸 Screenshots

Add the following screenshots to improve your GitHub repository:

1️⃣ UiPath workflow
2️⃣ Automation execution
3️⃣ Data extraction process
4️⃣ Excel output results

Example:

Screenshots/workflow.png
Screenshots/output.png
🚀 Advantages of the System

✔ Saves time
✔ Reduces manual work
✔ Improves accuracy
✔ Easy to scale for bulk data extraction
✔ Useful for RPA learning projects

⚠ Limitations

CAPTCHA may interrupt automation

Website structure changes may require bot updates

Internet connection required

🔮 Future Enhancements

Future improvements may include:

CAPTCHA handling using AI

Email notification of bill details

Integration with database systems

Automated bill payment

Scheduling automation using UiPath Orchestrator

📚 Learning Outcomes

From this project, you will learn:

UiPath workflow development

Web automation techniques

Data extraction from websites

Excel integration in RPA

Error handling in automation

📜 License

This project is created for educational and research purposes.

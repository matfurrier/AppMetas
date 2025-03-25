<p align="right">
  <b>[EN]</b> | <a href="#pt-versão-em-português">[PT]</a>
</p>

# 🎯 Metas APP

## 📝 Table of Contents
- [Description](#description)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Contributions](#contributions)
- [License](#license)
- [Contact](#contact)

## 📖 Description

**Metas APP** is a web application developed to facilitate the process of filling out and tracking annual goals for employees. Through this application, it is possible to assess the performance of each employee and department, optimizing management and providing a clearer view of the results achieved.

## 🛠 Technologies

The following technologies were used in the development of this project:
- CSS3
- JavaScript
- React
- Node.js
- Express
- MySQL

## ⚙ Installation

### Prerequisites

Make sure you have Node.js and NPM installed on your machine before proceeding with the steps.

### Step-by-Step

Follow the steps below to set up and run the project locally:

## 🎮 Usage

To use the Metas APP, follow the steps below:

1. Log in with your corporate email and the password provided by the company.
![Login](https://user-images.githubusercontent.com/30526394/228895020-0f223d31-43e3-4229-99de-d4f61cc37af8.png)

2. Administrators will have access to all functionalities, such as adding employees, French year, departments, etc.
![WelcomeAdmin](https://user-images.githubusercontent.com/30526394/228895043-55143220-3b26-42ad-9061-ab8be7d94031.png)

3. Department heads will see an additional shortcut on the left called "MY TEAM'S GOALS." Other employees will have access to "MY GOALS" and "DEPARTMENT GOALS."
![WelcomeResponsible](https://user-images.githubusercontent.com/30526394/228895521-88904fc9-d850-453b-b84d-489b30921e58.png)

4. All employees can add their own goals. However, only the department head can create department goals.

5. Department employees can only view department goals.

### Rules and flows of the app:
- When creating the individual goal, it must be sent for approval by the immediate superior.
- An email flow is triggered at the end of each step.
- Only the immediate superior can create/edit department goals. Employees can view them.
- Goals can only be created/edited/deleted within the active period of the French year.
- Once the goal is approved/saved and sent, the original goal cannot be modified.
- Only the immediate superior can fill in the goal's result.

### Step-by-step:

1. After filling out the individual goals, the employee must click the "SEND FOR VALIDATION" button to send it to the immediate superior.
![MetasIndividuais](https://user-images.githubusercontent.com/30526394/228895028-85002c1e-4b50-43a1-a986-b4623d8d0ba1.png)

2. The employee can generate a PDF file of the goals by clicking the "GENERATE PDF" button.
![PDFIndividualGoals](https://user-images.githubusercontent.com/30526394/228896408-6dd2bac0-b4ea-44cb-8558-3657f1b0f634.png)

3. Department heads, when accessing "MY TEAM'S GOALS," will be able to view their team's goals and their status.
![MetasdoMeuTime](https://user-images.githubusercontent.com/30526394/228895025-63d2fce2-b3ec-4dbe-b654-49832785a42d.png)

4. By clicking the "VIEW" button, the department head will see the details of the employee's goal.
![DetalhesMetasdoMeuTime](https://user-images.githubusercontent.com/30526394/228895013-474c9c65-5a3c-44ab-b4ac-021e594d5405.png)

5. If necessary, the head can click the "EDIT" button and change the status of the goal to "IN PROGRESS" again, providing the reason. Then click "UPDATE."
![EditarMetasdoMeuTime](https://user-images.githubusercontent.com/30526394/228895017-8e1a2e30-c92f-46a3-ab14-23ec4a7746d2.png)

6. For the employee, the unapproved goal status returns to "IN PROGRESS," and a new button "REJECTION REASON" appears. The "EDIT" and "SEND FOR VALIDATION" buttons are available again.
![BotaoMotivoRecusa](https://user-images.githubusercontent.com/30526394/228895007-24197973-bb4f-44ea-8949-b6fff10cb0a6.png)

7. By clicking on "REJECTION REASON," the manager's message with the justification will appear for the employee, who can adjust the goal and resend it for approval.
![VerMotivoRecusa](https://user-images.githubusercontent.com/30526394/228895041-3bae4d3f-0176-4e1c-b2df-417184c2666c.png)

8. In the department goals, the option to print in PDF has also been added.
![MetasdoDepartamento](https://user-images.githubusercontent.com/30526394/228895021-7e72edb1-4a6d-42f4-8e7b-688ddc34b1cf.png)
![PDFDepartmentGoal](https://user-images.githubusercontent.com/30526394/228896399-8eddb6b2-e6e5-4351-9e1c-eb10fbb27f88.png)

9. Goal Evaluation

The "EVALUATE" button will be available for the area manager at the end of the French year, allowing them to assess whether their team members met the proposed goals. This helps with performance analysis and decision-making for the next year.

![Avaliar](https://user-images.githubusercontent.com/30526394/231195186-b6fb85cc-b3ff-4d06-bf1c-0d5c3669e035.png)

The manager will be able to verify each goal, analyze the results achieved, and then click the "EVALUATE" button to confirm whether the goal was met or not. After evaluating all goals, the manager will have an overview of the team's performance, aiding in analysis and planning for the next period.

![AvaliacaoMeta](https://user-images.githubusercontent.com/30526394/231195182-51292975-ea4c-49bd-bf73-c8641d86ac6d.png)

When a goal is evaluated, the employee will be able to check the achieved percentage and the justification.
![DetalhesMetasAvaliada](https://user-images.githubusercontent.com/30526394/231191773-473dbcd3-9e2c-41c4-8705-0f1b79120ed6.png)

10. Additional registration screens for administrators.

Users:
![Users](https://user-images.githubusercontent.com/30526394/228895037-b05d37cb-7ffd-4e83-97a7-8af5819538ff.png)

Departments:
![Departamentos](https://user-images.githubusercontent.com/30526394/228895011-d1ccbedd-b667-476d-9dd0-bd11552ed6bc.png)

Responsible:
![Responsaveis](https://user-images.githubusercontent.com/30526394/228895032-0595e8be-ec4c-4da1-98ac-a22060b8158a.png)

French Year:
![AnoFrances](https://user-images.githubusercontent.com/30526394/228894998-8a72de6e-1b45-4831-b86d-6f1d25f3cb4f.png)

All set! Now you're ready to use the Metas APP and achieve your goals! 🚀

## 🤝 Contributions
Contributions are always welcome!

## 📄 License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## 📬 Contact
Mateus Furrier - matfurrier@gmail.com

Project Link: [https://github.com/matfurrier/AppMetaNew](https://github.com/matfurrier/AppMetaNew)

Feel free to reach out with any questions, suggestions, or feedback. And don't forget to ⭐️ this project to help spread the word! 😄


# AppMetaDS

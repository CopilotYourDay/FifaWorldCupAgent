# FifaWorldCupAgent

Follow these steps to set up and configure your World Cup Prediction Agent.

### 1. Initial Setup
1. Download the **zip solution** and the **worldcuppredictions.xlsx** file.
2. Navigate to your environment and **Import** the zip solution.
   <img width="533" height="255" alt="image" src="https://github.com/user-attachments/assets/25913499-1ccd-44aa-a6d9-2bff0737662d" />
3. Upload the `worldcuppredictions.xlsx` file to your **OneDrive**. The Admin will need to add the played results here in the column Matches Master RealScoreA and B, the Excel will then automatically calculate the points.
4. 
   <img width="264" height="309" alt="image" src="https://github.com/user-attachments/assets/6eab56f1-c39b-4800-a85f-c50659b4395f" />

### 2. Configure Power Automate Flows
4. Go to **Topics** -> **Quiz Start** and open the flow named **Create Predictions**.
   <img width="173" height="179" alt="image" src="https://github.com/user-attachments/assets/819f7e69-5699-44fb-9f54-318309c8d4fc" />
5. Configure the **4 Excel Connections** to reference the file you uploaded to OneDrive in Step 3.
   <img width="540" height="518" alt="image" src="https://github.com/user-attachments/assets/ef5a9636-5d34-4632-8750-4a6c93df73b1" />
6. Once configured, ensure the flow is turned on.
   <img width="662" height="176" alt="image" src="https://github.com/user-attachments/assets/b1a12385-0274-44ac-9730-a8294add9c5e" />

### 3. Update Tools & Secondary Flows
Repeat the Excel connection configuration for the following components:

*   **Flow: List Open Games**
    <img width="546" height="650" alt="image" src="https://github.com/user-attachments/assets/81accb0a-bb21-472e-bfbe-20431b736839" />
*   **Tool: List Results and Upcoming Games**
    <img width="688" height="705" alt="image" src="https://github.com/user-attachments/assets/9710690d-dc8d-4be6-afc5-beb8856d51b1" />
*   **Tool: List Leaderboard**
    <img width="682" height="708" alt="image" src="https://github.com/user-attachments/assets/ed60bef5-6c09-46ca-8c7e-5295d6280416" />
*   **Tool: List User Tipps**
    <img width="670" height="710" alt="image" src="https://github.com/user-attachments/assets/0146ee77-6bec-4cd2-87d5-74883acda5f7" />
*   **Tool: Update User Tips**
    <img width="665" height="871" alt="image" src="https://github.com/user-attachments/assets/c0e3b48f-ed52-4a01-968e-725251cf0aad" />

### 4. Testing & Deployment
7. You are now ready! Test your agent in the test window to ensure all data is being pulled correctly.
   <img width="1129" height="855" alt="image" src="https://github.com/user-attachments/assets/d6f09ca8-293d-4202-86f4-5c7595309aba" />
8. **Publish** your agent to Copilot or Microsoft Teams and share it with your teammates. Who will be the best guesser?

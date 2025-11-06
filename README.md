# Source-Code-Management-Project-2

STEP 1: Clone your GitHub Repository
POWERSHELL: git clone git@github.com:samuel730/Source-Code-Management-Project-3.git
cd Source-Code-Management-Project-3
<img width="793" height="118" alt="Cloning 1" src="https://github.com/user-attachments/assets/fbc24bde-e379-45ce-acaf-97be45ad42f3" />

STEP 2: Add the Form.html and style.css given to you by your client
<img width="690" height="17" alt="cloning 2" src="https://github.com/user-attachments/assets/2fb5bb0e-0f8a-4092-a46c-ec0cae2c1aee" />

STEP 3: Commit the staged files with a message:
Git commit -m "Initial commit for simple form"
<img width="1012" height="75" alt="cloning 3" src="https://github.com/user-attachments/assets/68c96ebb-8356-4559-8637-cf22a2d0b4fc" />

STEP 4: Push the initial commit to the remote repository:
Git push origin main
<img width="648" height="154" alt="cloning 4" src="https://github.com/user-attachments/assets/8574d584-4fd2-4101-b671-062d1e38e847" />

STEP 5: Your client requests some updates to the form. You modify form.html to include an additional field for a phone number and update the styling in style.css.

After making these changes, stage and commit the updated files with a message:
git add form.html style.css
git commit -m "Added phone number field and updated styles"
<img width="632" height="107" alt="cloning 5" src="https://github.com/user-attachments/assets/ed113d71-a17e-43f1-8671-a1818694faa8" />

STEP 6: Push your latest changes to the remote repository:
git push origin main
<img width="577" height="36" alt="cloning 6" src="https://github.com/user-attachments/assets/2336c9c0-acd6-4c75-b1ea-16e278cd7611" /> 

STEP 7: After working on several features and fixes, view the Git history to check all the changes you've made:

git log
<img width="671" height="325" alt="cloning 7" src="https://github.com/user-attachments/assets/a81e35b5-945c-4613-8ce3-bee222c11ba6" />

STEP 8: Your client wants to experiment with adding a CAPTCHA feature to the form. Create a new branch called feature-add-captcha and switch to it:

git checkout -b feature-add-captcha

<img width="888" height="154" alt="cloning 8" src="https://github.com/user-attachments/assets/d451a207-878a-408f-810f-1a26cf6cf5d3" />

STEP 9: Make the necessary changes for the CAPTCHA feature, then stage and commit them:

git add form.html
git commit -m "Added CAPTCHA feature"
<img width="557" height="224" alt="cloning 9" src="https://github.com/user-attachments/assets/7f98ed32-9d5b-4ca6-8b06-6f6533827588" />

STEP 10: Merge the changes back into the main branch:

git checkout main
git merge feature-add-captcha
<img width="710" height="101" alt="cloning 10" src="https://github.com/user-attachments/assets/4fad6f4a-ef9f-4cba-8682-e57b74813359" />

STEP 11: After merging, push the updated main branch to the remote repository:

git push origin main
<img width="565" height="45" alt="cloning 11" src="https://github.com/user-attachments/assets/b74c7b01-3d3a-4930-9f0d-c0c8d0147851" />

STEP 12: You accidentally made some unwanted changes to style.css that you haven’t committed yet. Discard these local changes and revert the file to its previous state:

git checkout -- style.css
<img width="585" height="30" alt="cloning 12" src="https://github.com/user-attachments/assets/6ad07409-49af-4c74-92ca-b50b9421080a" />




# MailingToolScript
## Microsoft Power Automate
1. Invite to [MS.Team](https://teams.microsoft.com/l/team/19%3a1v_VYAogWAGLoSv6-n7AP46vvuSrfzENr7qVKgZp4bQ1%40thread.tacv2/conversations?groupId=594ad3dd-194f-4182-82d0-29ff336ef0c2&tenantId=9bc585f9-a8b8-431c-9013-efa7b2b40cdf)
2. Duplicate "Sample Data" in Share Point
3. Rename File to "Sample Data_YourName" and Change Your Email
4. Create New Flow "Example Mailing from Excel"
5. Set Trigger Flow to "Manually trigger a flow"
6. Add Step "List rows present in a table"
   1. Set Location "Group - Power Automate Sample Training"
   2. Set Document Library "เอกสาร"
   3. Set File "/General/Sample Data_YourName.xlsx"
   4. Set Table "student"
7. Add Step Send Email in Outlook.com -> Auto add "Apply to Each"
   1. Email for Testing in [Docfile](https://docs.google.com/document/d/12KetF_QpCYyIX6aZp-d1_pc5-ti5CQxtynkj_WtITcY/edit?usp=sharing)
   2. การเพิ่ม White List Email ป้องกัน Spam https://webmail.mahidol.ac.th/owa/#path=/options/blocksenders
   3. Add Template Email + Mapping data position
8. Test Send Email
## Google Apps Script
1. Copy [Google Sheet](https://docs.google.com/spreadsheets/d/1tqj3L_JKPAG06DEd7eHa9QMVOYxfnzn8mqrrg2LEHiw/copy) to Your Drive
2. Change Your Email
3. Open Apps Script from Menu "Tool->Script Editor"
4. Change select function to "sendMails"
5. Click Run

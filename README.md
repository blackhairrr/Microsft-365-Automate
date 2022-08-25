# Microsft-365-Automate

## Sending approval by using Microsoft Form
![flow](https://user-images.githubusercontent.com/37354986/186581141-ba910731-c56f-49ff-80dd-7d41f46ce18b.PNG)

## 1. Create a form

![create 1](https://user-images.githubusercontent.com/37354986/186581212-0cf061f9-d110-4b40-808d-3f143c8237f5.PNG)
- Click on dot and click on the Mic Form icon.


![create 2](https://user-images.githubusercontent.com/37354986/186581349-d03ab54b-dc48-4557-88bd-92f1261817eb.PNG)
- Create new form unless you have a form that you want to make an approval

![create 3](https://user-images.githubusercontent.com/37354986/186581515-fcd4c1d0-2d40-450f-93eb-5ccf29c361e5.PNG)
- Create some questions.

## 2. Open Microsoft Sharepoint to create a database


![create 4](https://user-images.githubusercontent.com/37354986/186581609-45c8c2ef-0b82-40a2-92ba-713573b068fc.PNG)

![create 5](https://user-images.githubusercontent.com/37354986/186581758-29c64872-578e-43fc-aa3b-dd02c23fa823.PNG)
- Click on new, then list.


![create 6](https://user-images.githubusercontent.com/37354986/186587433-aa71a852-2764-4be4-9c2b-3553ca25b9ca.PNG)
- Choose a blank list

![create 7](https://user-images.githubusercontent.com/37354986/186587515-a144e1d0-9fb8-4a1d-b0e0-164eb0398872.PNG)
- Enter the database name.


![create 9](https://user-images.githubusercontent.com/37354986/186589071-9fda3d9e-a719-4eef-bfe9-05bf2d900219.PNG)
- Add column and choose the data type.



![create 10](https://user-images.githubusercontent.com/37354986/186589162-51d463f4-24ba-4e9d-bad5-2e8b5af2e2f9.PNG)

## 3. Open the Microsoft Power Automate
![Automate 1](https://user-images.githubusercontent.com/37354986/186589548-cb760866-41ae-4a2d-b1b7-c0d05cd5847e.PNG)

![Automate 2](https://user-images.githubusercontent.com/37354986/186590706-5b18b5bd-c016-4226-b7c6-b134b2e90ee5.PNG)
- Click on create tab, choose approval template.

![Automate 3](https://user-images.githubusercontent.com/37354986/186591332-a49494e4-187b-43f9-a933-8f3fa4258e5f.PNG)
- Make sure all the connection connected before contionue.

![Automate 4](https://user-images.githubusercontent.com/37354986/186591195-171b7c16-2d23-4d3e-8945-de7a8cc4765b.PNG)
- Configure the automation.

## 4. Configuring Automation
![Automate 5](https://user-images.githubusercontent.com/37354986/186593956-46a9202a-1db0-4e7a-9210-ce9e96b2a5e9.PNG)
- Select your form's name

![Automate 6](https://user-images.githubusercontent.com/37354986/186594097-b5d0f843-5f11-4182-8966-521dc9930860.PNG)
- Choose the same name

![Automate 7](https://user-images.githubusercontent.com/37354986/186594162-32c89a3c-6da5-4519-bd79-5753c1be2004.PNG)
- Put your message that will sending by the requestor to the approver.

![Automate 8](https://user-images.githubusercontent.com/37354986/186594325-aaae01eb-fad9-4c44-a27b-b0c050b1f844.PNG)
- Select the database location from the sharepoint

![Automate 9](https://user-images.githubusercontent.com/37354986/186594426-daab75b8-a739-4bf4-9924-ad05e4f36df4.PNG)
- Select the database name that you created

![Automate 10](https://user-images.githubusercontent.com/37354986/186594549-8cc640a0-5878-49b3-a3a7-311397943446.PNG)
- Link all the column with the form's data

![Automate 11](https://user-images.githubusercontent.com/37354986/186594609-03d79f78-d5f1-440d-ba2a-d95142f1c4e5.PNG)

Next,

![Automate 12](https://user-images.githubusercontent.com/37354986/186594701-abf9bc54-57b0-498f-b29b-e29caf8a490f.PNG)
- Enter the message that will sending by the approver to the requester.

![Automate 16](https://user-images.githubusercontent.com/37354986/186600131-4ec50094-e8b2-43fd-a460-f08139662311.PNG)
- Add step to email the requestor for the approved status. Search profile and choose Get My Profile V2

![Automate 17](https://user-images.githubusercontent.com/37354986/186600257-487f14f6-4f4f-4f20-953f-20642dd45e18.PNG)
- Click on advance and add Mail


![Automate 18](https://user-images.githubusercontent.com/37354986/186600495-216bb1ec-c68a-4a8e-80c6-c08766d0318b.PNG)
- add step and search send an email. And choose that action.

![Automate 19](https://user-images.githubusercontent.com/37354986/186600673-eba38d7b-8ca4-49e9-82bd-81c5cdadd636.PNG)

![Automate 20](https://user-images.githubusercontent.com/37354986/186600697-5813b068-0159-493b-a563-1ab2a8ff72bc.PNG)
- Fill out the message that you want to email to the requester.

![Automate 13](https://user-images.githubusercontent.com/37354986/186601320-aeb211a1-da97-47d8-a5dd-5c832a683a38.PNG)
- Save and set the flow name.

## 5. Lets test
![test 1](https://user-images.githubusercontent.com/37354986/186602077-8dd85436-6a08-470c-b8c6-1510fa23011d.PNG)
- Fill out the form

![test 2](https://user-images.githubusercontent.com/37354986/186602122-afb78a1d-f06f-4ec5-b6e5-7e4b49ac92a0.PNG)
- Approver will get an email


![test 3](https://user-images.githubusercontent.com/37354986/186602173-c97f3fd3-40f4-4ec5-8fdb-26b3a7ed0fe9.PNG)
- Approver approved

![test 7](https://user-images.githubusercontent.com/37354986/186602271-3fc121bd-7888-4aa9-b001-2b85dec5ee52.PNG)
- Requestor will get the request status approved

![test 5](https://user-images.githubusercontent.com/37354986/186602486-8cf87d01-b643-4fd6-965e-e85565ed9cf4.PNG)
- Lets test other option, if the approver reject.

![test 6](https://user-images.githubusercontent.com/37354986/186602603-d5acb93b-87da-403c-9d97-c56e2d5c7a2b.PNG)
- Requester will get the request status rejected.

![test 4](https://user-images.githubusercontent.com/37354986/186602734-a4dd0385-3e48-4105-a2a1-8a58a0af6518.PNG)
- Ony approved status will be recorded.

The flow is successfull.

# ๐ **Week 0 โ Billing and Architecture**

## **Required Tasks**

### โ Install AWS CLI

- _Since AWS CLI was already installed I used the following command to update to the latest version via Powershell_

  ```yml
  msiexec.exe /i https://awscli.amazonaws.com/AWSCLIV2.msi
  ```

- _Ran into error with installer because my Nvidia Overlay was onโIn order to continue with installer I manually close Nvidia Containers in Windows Task Managers_

- _Problem solved โ_

- _To verify CLI has been updated_

  ```yml
  aws --version
  ```

  ![CLI](assets/cli.png)

โฎโฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฏ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉโฎ

### โ Create Admin user

- _Created new user added to group with ***AdministratorAccess***_

  ![user](assets/user.png)

โฎโฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฏ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉโฎ

### โ Generated AWS Credentials

- _Generated credentials via bash_

  ```yml
  aws sts get-caller-identity
  ```

  ![cred](assets/cred.png)

โฎโฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฏ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉโฎ

### โ Budget & Billing Alarm

- _Decided to create a $5 budget instead because 5 is my favorite number_

  ![budget](assets/budget.png)

- _Billing alarm already created prior_

  ![alarm](assets/billalarm.png)

โฎโฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฏ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉโฎ

### โ Recreated Conceptual Diagram

- _I sprinkled some glitter on the conceptual diagram we did in live session_

- _Click image for full size chart_

  [![concept diagram](assets/conceptual-diagram.png "Click here!")](https://lucid.app/lucidchart/954486e7-37fe-42e1-b36c-396429e373b3/edit?viewport_loc=-213%2C-446%2C2394%2C1585%2C0_0&invitationId=inv_c3e6b972-6424-4e6b-a446-96fd68152c60)

โฎโฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฏ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉโฎ

### โ Recreated Logical Architecture Diagram

- _Click image for full size chart_

  [![logical diagram](assets/logical-diagram.png "Click here!")](https://lucid.app/lucidchart/b57a32f7-a918-4f8f-9c30-182bbfc4b9bc/edit?viewport_loc=-20%2C-206%2C3090%2C2046%2C0_0&invitationId=inv_55974d3b-a3b4-4e91-a720-0a81a38e7572)

โฎโฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฏ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉโฎ

## **Challenges** โจ

### โ Support Ticket for Service Limits

- _To create a support ticket for service limit increase I utilized OpenAI latest chatbot_

- Open [ChatGPT](https://chat.openai.com/chat)
- Enter "how to request service limit increase in aws"
- AI provided instruction
- Go back to aws console and followed instructions to create a request

  ![ChatGPT](assets/openai.png)

  ![support ticket](assets/ticket.png)

โฎโฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฏ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉ ๐ ๐ โฌฉโฎ

# RDP
Building a free RDP (Remote Desktop Protocol) server using Ngrok is a process that involves using Ngrok to expose a local RDP server to the internet, allowing remote access to the computer.

1. <a href="https://github.com/0xAKXVAU/aws-rdp/blob/main/README.md#how-to-use-it">How to use it?</a>
2. <a href="https://github.com/0xAKXVAU/aws-rdp/blob/main/README.md#screenshots">Screenshots.</a>
3. <a href="https://github.com/0xAKXVAU/aws-rdp/blob/main/README.md#-tutorial-video">Video tutorial.</a>
4. <a href="https://github.com/0xAKXVAU/aws-rdp/blob/main/README.md#%EF%B8%8F-warning--use-fake-github-account-otherwise-sometimes-the-account-may-get-flagged">Warnings.</a>

## How to use it?

#### First Step
1. Press the <a href="https://github.com/0xAKXVAU/aws-rdp/fork">**fork**</a> button  
2. Login or signup to ngrok: https://ngrok.com
3. Now visit here for token: https://dashboard.ngrok.com/auth/your-authtoken
> You'll get token from here. It'll be needed to the next step.

#### Second Step
1. In your forked repo: **Go to Settings > Secrets > Action > New Repository Secret**
2. In the name section, enter this text: **NGROK_AUTH_TOKEN**
3. In the value section, enter the **ngrok token**
4. Then press **Add Secret**
5. Now go to **Action > AWS (Left Menu) > Run Workflow**
6. Refresh the page and go to **AWS > build** option
7. You'll get IP, Username & Password from **Connect to RDP** section.

#### Third Step (Android)
1. Download <a href="https://play.google.com/store/apps/details?id=com.microsoft.rdc.androidx">**Remote Desktop**</a> app.
2. Open Remote Desktop app and click add pc
3. Put IP without **tcp://** and enter Username & click **Connect**.
4. Later on, put the password for credential/auth.
<img src="https://i.ibb.co/QmR8xgr/603fe841d06f.png" alt="ss" width="40%"/>
5. Click continue then connect.

#### Third Step (Windows)
1. Search **Remote Desktop Connection** from Windows Start Menu and open.
2. Put IP without **tcp://** and enter Username & click **Connect**.
3. Later on, put the password for credential/auth.
<img src="https://i.ibb.co/8jwLMqg/90b4c297945f.png" alt="ss" width="40%"/>

## Screenshots
<img src="https://raw.githubusercontent.com/0xAKXVAU/aws-rdp/main/.assets/Screenshot_20230414-021950.jpg" alt="ss" width="90%"/>
<img src="https://raw.githubusercontent.com/0xAKXVAU/aws-rdp/main/.assets/Screenshot_20230414-022043.jpg" alt="ss" width="90%"/>

## <a href="https://t.me/Toxinum/561"> **Tutorial Video**
### Don't forgot to follow my GitHub & hit the star button.

## ⚠️ Warning : Use fake github account. Otherwise sometimes the account may get flagged

# Thanks ❤️

File Limit Changer, Pagination, and Server Sorting! for Pterodactyl
Feel free to donate to my Paypal at: classicheroestv@gmail.com

YOU CAN NOT USE BOTH AT THE SAME TIME  
Pagination completely bypasses the file limit, and after every 250 files a new page is created  
You need to have followed https://pterodactyl.io/community/customization/panel.html
atleast once.



Installation Guide  
File limit changer:  

Download FileLimitChanger.sh  
run *chmod +x FileLimitChanger.sh*  
then run *./FileLimitChanger.sh (new filelimit)*  
then run *yarn build:production*  
Do this as root to have proper permissions  


Pagination:  
Download FileManagerContainer.tsx  
Replace /var/www/pterodactyl/resources/scripts/components/server/files/FileManagerContainer.tsx with the downloaded file  
then run *yarn build:production*  
(or use the installer)

Server Sort:  
Download DashboardContainer.tsx
Replace /var/www/pterodactyl/resources/scripts/components/dashboard/DashboardContainer.tsx with the downloaded file  
then run *yarn add react-beautiful-dnd*
then run *yarn add @types/react-beautiful-dnd --dev*
then *yarn build:production*  
(or use the installer)

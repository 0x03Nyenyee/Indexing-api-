<div align="center">
  <img height="150" src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif"  />
</div>

###

<p align="left">1. Setting up the Indexing API: creating a service account and JSON key Let's start by setting up access in the Indexing API console. Go to Google Cloud Platform and create a service account</p>

###

<div align="center">
  <img height="200" src="https://i.ibb.co/8gm2yGfc/1.png"  />
</div>

###

<p align="left">Here you can enter the desired project name or leave the suggested one. We leave the location as it is, editing is optional.</p>

###

<div align="center">
  <img height="200" src="https://i.ibb.co/gMfgNsMG/2.png"  />
</div>

###

<p align="left">We continue to create a service account: you should see the following window in front of you (you will have a different project name):</p>

###

<div align="center">
  <img height="200" src="https://i.ibb.co/jv76VBQP/3.png"  />
</div>

###

<p align="left">1. Next, enter another arbitrary name.<br>2. Assign the role of this account - Owner.</p>

###

<div align="center">
  <img height="200" src="https://i.ibb.co/GQwkWgRZ/4.png"  />
</div>

###

<p align="left">Next, create a new key and download it to your computer.</p>

###

<div align="center">
  <img height="200" src="https://i.ibb.co/5hGCGMc3/5-1.png"  />
</div>

###

<div align="center">
  <img height="200" src="https://i.ibb.co/jPTZ6G1K/6.png"  />
</div>

###

<p align="left">The ready key is needed to run the scanning script<br>The script will be in the form of a folder, one of the files of which will be called service_account.</p>

###

<div align="center">
  <img height="200" src="https://i.ibb.co/LXbcMWyf/7.jpg"  />
</div>

###

<p align="left">Next, you need to replace the content of the service_account file with the content of your downloaded JSON key. As a result, the service_account file in the script folder will look something like this:</p>

###

<div align="center">
  <img height="200" src="https://i.ibb.co/zt1bZwM/8.jpg"  />
</div>

###

<p align="left">The script is ready. Now it needs to be linked to Google Search Console.</p>

###

<div align="center">
  <img height="200" src="https://i.ibb.co/WpybXyfn/10.png"  />
</div>

###

<p align="left">enable indexing api on console google</p>

###

<div align="center">
  <img height="200" src="https://i.ibb.co/HT67CCkZ/9.jpg"  />
</div>

###

<p align="left">and linked email key and select owner</p>

###

<div align="center">
  <img height="200" src="https://i.ibb.co/tw2q8zNh/11.jpg"  />
</div>

###

<p align="left">Last part run script "node index.js"</p>

###

<p align="left">DONE!!!<br>If you have any questions, ask.<br><br>Thanks For  Create By<br>https://github.com/swalker-888</p>

###

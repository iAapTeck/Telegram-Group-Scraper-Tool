<p align="center">
  <img src="https://raw.githubusercontent.com/iAapTeck/Telegram-Group-Scraper-Tool/master/image/20191203_205322.jpg" width="470" height="150">
</p>

<p align="center"><img src="https://img.shields.io/badge/Version-3.1-brightgreen"></p>
<p align="center">
  <a href="https://github.com/iAapTeck">
    <img src="https://img.shields.io/github/followers/iAapTeck?label=Follow&style=social">
  </a>
  <a href="https://github.com/iAapTeck/Telegram-Group-Scraper-Tool">
    <img src="https://img.shields.io/github/stars/iAapTeck/Telegram-Group-Scraper-Tool?style=social">
  </a>
</p>
<p align="center">
  Telegram Group Scrapper
</p>
<p align="center">
</p>

---

## • API Setup
* Go to http://my.telegram.org  and log in.
* Click on API development tools and fill the required fields.
* put app name you want & select other in platform Example :
* copy "api_id" & "api_hash" after clicking create app ( will be used in setup.py )

## • How To Install and Use

`$ pkg install -y git python`

`$ git clone https://github.com/iAapTeck/Telegram-Group-Scraper-Tool.git`

`$ cd TeleGram-Scraper`

* Install requierments

`$ python3 setup.py -i`

* setup configration file ( apiID, apiHASH )

`$ python3 setup.py -c`

* To Genrate User Data

`$ python3 scraper.py`

* To Transfer User Members Data from Members.csv file to Your Telegam Groups/Channels

`$ python3 add2groups.py members.csv`


* ( members.csv is default if you changed name use it )
* Send Bulk sms To Collected Data 

`$ python3 smsbot.py members.csv`

* Update Tool

`$ python3 setup.py -u`


##### Any Queries? or Feedback, please let me know by opening a [new issue](https://github.com/iAapTeck/Telegram-Group-Scraper-Tool/issues/new)!

## Contact
#### Sanjay Chintamani Patel, Founder/CEO at iAapTeck Software Labs
* :globe_with_meridians: Website: [iaapteck.com](http://www.iaapteck.com "iAapTeck Software Labs")
* :email: e-mail: contact@iaapteck.com
* :mag_right: LinkedIn: [iAapTeck](https://www.linkedin.com/company/iaapteck "iAapTeck Software Labs on LinkedIn")
* :thumbsup: Twitter: [@iaapteck](https://twitter.com/iaapteck "iAapTeck Software Labs on twitter")    
* :camera: Instagram: [@iaapteck](https://www.instagram.com/iaapteck/ "iAapTeck Software Labs on Instagram")   

> If you appreciate my work, consider buying me a cup of :coffee: to keep me recharged :metal: by [PayPal](https://www.paypal.me/iaapteck)

License
-------

    Copyright 2021 iAapTeck Software Labs

    Licensed under the GNU GENERAL PUBLIC LICENSE, Version 3.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       https://fsf.org

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
	The GNU General Public License is a free, copyleft license for software and other kinds of works.

  The licenses for most software and other practical works are designed to take away your freedom to share and change the works.  By contrast, the GNU General Public License is intended to guarantee your freedom to share and change all versions of a program--to make sure it remains free software for all its users.  
  We, the Free Software Foundation, use the GNU General Public License for most of our software; it applies also to any other work released this way by its authors.  You can apply it to your programs, too. When we speak of free software, we are referring to freedom, not price.  Our General Public Licenses are designed to make sure that you have the freedom to distribute copies of free software (and charge for them if you wish), that you receive source code or can get it if you want it, that you can change the software or use pieces of it in new free programs, and that you know you can do these things.
	

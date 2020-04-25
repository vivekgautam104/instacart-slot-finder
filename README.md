# Instacart Delivery Slot Finder
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
A cross platform tool that finds available delivery slots for Instacart delivery website.

****
Users in United States can use our other tool for the ["Amazon Fresh" delivery tool](https://github.com/ojasvi92/Amazon-Fresh-Delivery-Slot-Notifier-COVID-19)

Users in India can use our tool for the [“BigBasket” Delivery](https://github.com/vivekgautam104/bigbasket-slot-finder)
****
V1.0 : 04/24/2020 
Initial Version
****


## Pre-requisites: 

1. Please make sure that you have Google Chrome browser installed on your system. The tool works only with Google Chrome.

2. Turn up the volume of your system for the voice notification.

3. Fill up your cart with your complete order before running the process so as to quickly proceed with checkout as soon as a slot is found. However, you can fill up your cart after launching the application as well.

## Option 1 - Download and run the executables

1. Download the respective executable file for MAC OS and Windows OS:
	* MAC - Click [here](https://github.com/vivekgautam104/instacart-slot-finder/files/4533938/instacart_slot_finder_mac.zip)
	* Windows - Click [here](https://github.com/vivekgautam104/instacart-slot-finder/files/4533935/instacart_slot_finder_win.zip)

2. Unzip the file

3. Run the respective executable file.

## Option 2 - Execution of Source Code 

1. Make sure Python 3.x is installed on your system

2. Clone the repo

3. Run `pip3 install -r requirements.txt`

4. Run `python3 instacart_slot_finder.py`

## Instructions:

1. Run the executable file. Click on “Launch Instacart” to proceed

![1LaunchInstacart](https://raw.githubusercontent.com/vivekgautam104/instacart-slot-finder/master/images/1LaunchInstacart.png)

2. A new incognito Google Chrome window will be launched and redirected to Instacart website. Click Login

![2LaunchPage](https://raw.githubusercontent.com/vivekgautam104/instacart-slot-finder/master/images/2LaunchPage.png)

3. Login to your Instacart account

![3LoginPage](https://raw.githubusercontent.com/vivekgautam104/instacart-slot-finder/master/images/3LoginPage.png)

4. Select your delivery location and the store

![4KeyStore](https://raw.githubusercontent.com/vivekgautam104/instacart-slot-finder/master/images/4KeyStore.png)

5. Fill up your Instacart cart with your complete order, reach the checkout page which would look like this:

![5Cart](https://raw.githubusercontent.com/vivekgautam104/instacart-slot-finder/master/images/5Cart.png)

6. DO NOT click "Go to Checkout" Page. Click on “Notify Me” button on the tool and turn up the volume of your system

![6NotifyMe](https://raw.githubusercontent.com/vivekgautam104/instacart-slot-finder/master/images/6NotifyMe.png)

7. The application will keep running in the background, checking for available slots. The voice notification will be sent out once a slot is found

8. Once you're notified, quickly select a slot and finish checking out because available slots disappear almost instantly

## Inspiration and idea behind this tool:

The Coronavirus 2019 pandemic caused a surge in demand for grocery delivery services, making it nearly impossible to find an open delivery slot. My intention in providing this tool is to help people get the essentials at their doorsteps without having to step out of home. The idea sprang up when I saw my friends and family struggling to get groceries and essentials due to unavailability of slots.

## Notes:
1. The script will stop running if you navigate elsewhere from the checkout page. You need to re-run the tool and re-login for the code to continue finding the slots.

2. If you are logged out due to inactive session, you need to re-run the tool.


## Disclaimer:
The tool does not guarantee a definite slot. It avoids the manual work of having to check for slots countless number of times in order to get one. The tool runs in background and checks for available slots for you and alerts you when a slot is found.

Please keep trying and eventually a slot should work! 

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/ojasvi92"><img src="https://avatars3.githubusercontent.com/u/4646567?v=4" width="100px;" alt=""/><br /><sub><b>Ojasvi Maleyvar</b></sub></a><br /><a href="#design-ojasvi92" title="Design">🎨</a> <a href="#infra-ojasvi92" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="#maintenance-ojasvi92" title="Maintenance">🚧</a></td>
    <td align="center"><a href="https://github.com/shivangimgupta"><img src="https://avatars3.githubusercontent.com/u/32472018?v=4" width="100px;" alt=""/><br /><sub><b>shivangimgupta</b></sub></a><br /><a href="#userTesting-shivangimgupta" title="User Testing">📓</a> <a href="https://github.com/vivekgautam104/bigbasket-slot-finder/commits?author=shivangimgupta" title="Documentation">📖</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

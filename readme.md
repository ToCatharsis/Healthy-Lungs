## Authors ✍️
- [Kacper Kilianek](https://github.com/Kkilianek)
- [Adam Piszczek](https://github.com/AdamPiszczek)
- [Mateusz Cegielski](https://github.com/MateuszCegielski)
- [Ivan Ryzhankow](https://github.com/ToCatharsis)
- [Alina Yermakova](https://github.com/AlinaYermakova)

# Healthy-Lungs 🌬️ 🌳🌲🌳 🌎
A web application that allows the user to check air pollution in his area and selected location (course: web application programming). Our product intends to create a site that would allow for instant pollution of the air checking without searching for helpful information from third-party sites.

<p align="center">
  <img width="500" height="500" src="https://github.com/AdamPiszczek/Healthy-Lungs/blob/main/media/logo.png">
</p>

## Website view ⛰️
- [ ]

## Setup 🛠️
- Linux 🐧 / macOS 🍎 version
```sh
>
```
- Windows ☁️ version
```sh
>
```
<ins>Before the first run, ensure that you have on and active ...</ins>

## How to Run 🚀
- Linux 🐧 / macOS 🍎 version
```sh
>
```
- Windows ☁️ version
```sh
>
```

## Dependiencies 🦺 (also attached in ./requirements.txt)
- ...
- ...
- ...

## Design 📚
Our web application is largely based on the components provided by Flask framework, and more of its basic operations are used.

## About 📙
The app itself is designed to provide interested parties with an immediate overview of air pollution details in their area and beyond, without searching for scrap information from various websites. In a simple and very intuitive way, we visualized the air condition through appropriate animations and the use of colors signaling optimal or health-threatening weather conditions. Despite this, it is possible to check the history of the recorded pollution measurements by selecting the date of the day that interests us. The data, on the other hand, is downloaded from the website [under the given link](https://weather.com). The business logic itself is on the back-end, which is responsible for the correct data download and processing. The user should be able to change the city on request or go back in the history of air quality up to one week. The login itself is preceded by a request to provide the user's location, thanks to which the meteorological status will be displayed in accordance with the area in which the customer is located. The back-end itself is responsible for both archiving logins and processing all kinds of information related to user authorization. As for the front-end, it is the page on which individual pollutant data and the air condition are visible. Much of the app's focus is on lung animation, which represents the state of the air in a representative way.

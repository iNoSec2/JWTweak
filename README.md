# JWTweak
[![GitHub stars](https://img.shields.io/github/stars/rishuranjanofficial/JWTweak?logoColor=blue&style=social)](https://github.com/rishuranjanofficial/JWTweak/stargazers)   [![GitHub forks](https://img.shields.io/github/forks/rishuranjanofficial/JWTweak?logoColor=blue&style=social)](https://github.com/rishuranjanofficial/JWTweak/network)

## Introduction
With the global increase in JSON Web Token (JWT) usage, the attack surface has also increased significantly. Having said that, this utility is designed with the aim to generate the new JWT token with little or no time which would help security enthusiasts to find security flaws in JWT implementation like Algorithm confusion attacks. This tool is designed to automate the process of modifying the JWT algorithm of input JWT Token and then generate the new JWT based on the new algorithm.

## Requirements
- Python 3 (tested and working fine in python-3.7.7/Kali and python-3.8.2/Windows 10)
- pip3 install pycryptodomex

## Features
- Detects the algorithm of the input JWT Token 
- Base64 decode the input JWT Token 
- Generate new JWT by changing the algorithm of the input JWT to 'none' 
- Generate new JWT by changing the algorithm of the input JWT to 'HS256' 
- Generate new JWT by changing the algorithm of the input JWT to 'HS384' 
- Generate new JWT by changing the algorithm of the input JWT to 'HS512'  
- Generate new JWT by changing the algorithm of the input JWT to 'RS256' 
- Generate new JWT by changing the algorithm of the input JWT to 'RS384' 
- Generate new JWT by changing the algorithm of the input JWT to 'RS512'   

## Download Link 
**[JWTweak.py](https://rishuranjanofficial.github.io/JWTweak/JWTweak.py)**

## POC
![jwtweak](https://user-images.githubusercontent.com/51092706/86468710-9fdaae00-bd55-11ea-8272-8169ee29d431.png)

## Issues and Suggestions
[![GitHub issues](https://img.shields.io/github/issues/rishuranjanofficial/JWTweak?label=Contribution&style=social)](https://github.com/rishuranjanofficial/JWTweak/issues)

## Author
**Rishu Ranjan**   
> [![](https://img.shields.io/twitter/follow/secureit_rrj?style=social)](https://twitter.com/intent/follow?screen_name=secureit_rrj)   [![](https://static-exp1.licdn.com/sc/h/95o6rrc5ws6mlw6wqzy0xgj7y)](https://www.linkedin.com/in/rishuranjan/)

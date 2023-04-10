# Integrating-ChatGPT-into-Line

### Introduction:

In today's fast-paced world, it is crucial to have quick and efficient access to information. As the consumption of video content continues to grow exponentially, finding a way to extract key information from these videos becomes increasingly important. This guide will explore the innovative integration of ChatGPT with Apple's Siri voice assistant, focusing on the automatic generation of video content summaries. By combining the advanced language processing capabilities of ChatGPT with Siri's user-friendly voice interface, we unlock a powerful solution for streamlining information retrieval.

### Steps for Integrating ChatGPT into Line

**Step 1 Create an account/login to account** [ChatGPT Website](https://chat.openai.com/auth/login)
1. When using chatGPT for the first time, go to the chatGPT website to create an account

![Github Octocat mascot](https://github.com/JiaxiongWeng-Conor/Integrating-ChatGPT-to-siri/blob/f1d2e83ecaab9697e5c99dbefbf21963fa44e586/Image/WX20230324-143335.png)

2. Click on "Sign up" to register account, or "Log in" if you have one.

![Github Octocat mascot](https://github.com/JiaxiongWeng-Conor/Integrating-ChatGPT-to-siri/blob/f1d2e83ecaab9697e5c99dbefbf21963fa44e586/Image/WX20230324-143253.png)

**Step 2 Access to ChatGPT API**
1. Once logged in, go to this website for API claims:(https://platform.openai.com/account/api-keys)
2. Login to account and click on "Create New Security Key" to create the API key.

![Github Octocat mascot](https://github.com/JiaxiongWeng-Conor/Integrating-ChatGPT-to-siri/blob/4adb3d68c622b29b0963f103fb00953b836b82b0/Image/WX20230324-144724.png)
**Notice:** The key will only be displayed once!!! Remember to keep it safe! If the key is not saved in time, it will have to be recreated!

**Notice:** Every API comes with limited free quota, for details please see [API documentation](https://openai.com/pricing).

**Step 3 Access to Line API**
1. Creat an account and login [Line Develop](https://developers.line.biz/en/)
![Github Octocat mascot](https://github.com/JiaxiongWeng-Conor/Integrate-ChatGPT-into-LINE/blob/5b63a62bc8af74dd0ac78f8c378039853021bac0/picture/WX20230410-103518@2x.png)
2.Click "Create a new provider".
![Github Octocat mascot](https://github.com/JiaxiongWeng-Conor/Integrate-ChatGPT-into-LINE/blob/94f20fb293cbd42f27dbfd03906789432e24c46f/picture/WX20230410-155844@2x.png)
3.Click "Create a Messaging API channel" in Channel and fill in all the basic information
![Github Octocat mascot](https://github.com/JiaxiongWeng-Conor/Integrate-ChatGPT-into-LINE/blob/f6e0b2f160b5f2b94eea5dcd27e2c732c41e0296/picture/WX20230410-160137@2x.png)
4.There is a Channel Secret under Basic Setting, press Issue, which will be generated as LINE_CHANNEL_SECRET
![Github Octocat mascot](https://github.com/JiaxiongWeng-Conor/Integrate-ChatGPT-into-LINE/blob/668fb8c00179d9b26674e36b32ec45bc40d7b761/picture/WX20230410-161519@2x.png)
5.Under the Messaging API, there is a Channel access token -> press Issue, which is generated as LINE_CHANNEL_ACCESS_TOKEN
![Github Octocat mascot](https://github.com/JiaxiongWeng-Conor/Integrate-ChatGPT-into-LINE/blob/88bad0eade65a50f1aa30ab6d84b2973048ba522/picture/WX20230410-161928@2x.png)


### Support Me with a Cup of Coffee ☕
If you think this small application useful and would like to show your appreciation, please consider buying me a cup of coffee to support my efforts! Your generosity will not only fuel my motivation to continue working on this project, but also help me cover the costs associated with development and maintenance.

To buy me a coffee, simply scan or clik below:

![Github Octocat mascot](https://github.com/JiaxiongWeng-Conor/Integrating-ChatGPT-to-siri/blob/353dc1ae3fdcc5ca2f2e4a8f8c017fddb3a051b1/Image/IMG_6200.jpg)

[Link of venmo](https://account.venmo.com/u/Jiaxiong-Weng)


Thank you for your support! 🙏

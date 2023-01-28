# Intro

Flutter version of the popular Dutch TV game show 'Twee voor 12'. You will get 12 questions. The first letters of the answers will form a word, but the letters are not yet in the right order. After answering the questions, you are allowed to ask where in the word a letter belongs. The goal is to guess the word as fast as possible (with asking the minimum number of letters).

![](assets/1_for_12_animated.gif) ![](assets/1_for_12_dutch_animated.gif)

# Tech Stack

The iOS / Android App was built using Google Flutter. For the backend game API multiple versions were written in NodeJs / Typescript and .NET 7 / C#. The backend APIs can be deployed to various Serverless Platforms: AWS Lambda, Google Cloud Serverless and Microsoft Azure Functions.   

# Repositories

| Description |Repo  |
| ------- | --- |
| Verdaccio - local NPM registry / cache | https://github.com/one-for-twelve/verdaccio |
| NPM package with Core Game Api - nodejs / typescript | https://github.com/one-for-twelve/dnw-one-for-twelve-nodejs-core |
| NPM package with Auth Api - nodejs / typescript | https://github.com/one-for-twelve/dnw-one-for-twelve-nodejs-auth |
| AWS Lambda backend - nodejs / typescript | https://github.com/one-for-twelve/dnw-one-for-twelve-nodejs-aws-sam |
| Goole Firebase Function backend - nodejs / typescript | https://github.com/one-for-twelve/dnw-one-for-twelve-nodejs-firebase |
| AWS Lambda backend - .NET 7 Native AOT C# | https://github.com/one-for-twelve/Dnw.OneForTwelve.Aws.MinimalApi |
| AWS Lambda backend - .NET 7 C# | https://github.com/one-for-twelve/Dnw.OneForTwelve.Aws |
| Microsoft Azure Function backend - .NET 7 C# | https://github.com/one-for-twelve/one-for-twelve-Dnw.OneForTwelve.Azure |
| NuGet package with Core Game Api - .NET 7 C# | https://github.com/one-for-twelve/Dnw.OneForTwelve.Core |
| Front iOS / Android App - Flutter | https://github.com/one-for-twelve/dnw-one-for-twelve-flutter |
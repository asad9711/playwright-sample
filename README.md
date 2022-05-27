# Playwright Cloud ![pw](https://user-images.githubusercontent.com/70570645/169813479-9713557e-4430-42ea-91f4-70c6cb72ec0b.PNG)

<img height="300" src="https://user-images.githubusercontent.com/70570645/169812365-4141efe0-918e-4bfc-a2d5-bf3da9571d2b.png">

*Playwright is a Node.js library that uses a single API to automate Chromium, Firefox, and WebKit. It is designed to enable powerful, reliable, and efficient [automated browser testing](https://www.lambdatest.com/automated-browser-testing). Playwright can also automate Microsoft Edge since it is built on the open-source Chromium web framework. LambdaTest allows you to run Playwright tests across 40+ real browsers and operating system combinations.* 

*Learn the basics of [Playwright testing on the LambdaTest platform](https://www.lambdatest.com/support/docs/playwright-testing/).*

## Table of Contents:
***

* [Pre-requisites](#pre-requisites)
* [Running Your First Playwright Test](#running-your-first-playwright-test)
* [Parallel Testing](#parallel-testing)
* [Migrate Playwright Tests](https://github.com/LambdaTest/playwright-sample/blob/main/pw-docs/migrate-playwright-tests.md)
* [Test Execution Setup](https://github.com/LambdaTest/playwright-sample/blob/main/pw-docs/test-execution-setup.md)
* [Local Testing](https://github.com/LambdaTest/playwright-sample/blob/main/pw-docs/local-testing.md)
* [Integrate With Playwright Test Runner](https://github.com/LambdaTest/playwright-sample/blob/main/pw-docs/playwright-test-runner.md)
* [Integrate With Cucumber.js](https://github.com/LambdaTest/playwright-sample/blob/main/pw-docs/cucumberjs.md)
* [Playwright Testing With CI/CD](https://github.com/LambdaTest/playwright-sample/blob/main/pw-docs/playwright-with-cicd.md)
***

## Pre-requisites

1. Clone the [LambdaTest-Playwright repository](https://github.com/LambdaTest/playwright-sample) on your system.

2. Install the npm dependencies.

```
npm install
```

3. In order to run your Playwright tests, you will need to set your LambdaTest username and access key in the environment variables. Click the **Access Key** button at the top-right of the Automation Dashboard to access it.

<img height="300" src="https://user-images.githubusercontent.com/70570645/169819599-127dd293-347d-45b6-9651-e46f2b038583.png"/>

**Windows**

```js
set LT_USERNAME="YOUR_LAMBDATEST_USERNAME"
set LT_ACCESS_KEY="YOUR_LAMBDATEST_ACCESS_KEY"
```

**macOS/Linux**

```js
export LT_USERNAME="YOUR_LAMBDATEST_USERNAME"
export LT_ACCESS_KEY="YOUR_LAMBDATEST_ACCESS_KEY"
```

## Run Your First Playwright Test
* * *

Shown below are the steps on running Playwright tests on the LambdaTest platform. 

1. Clone the [LambdaTest-Playwright GitHub repository](https://github.com/LambdaTest/playwright-sample) and switch to the cloned directory.

```js
git clone https://github.com/LambdaTest/playwright-sample.git
cd playwright-sample
```

2. Ensure you have npm dependencies installed. 

3. Configure your LambdaTest authentication credentials.

Once you are done with the above-mentioned steps, you can initiate your first Playwright test on LambdaTest. 

**Test Scenario**: Check out [playwright-single.js](https://github.com/LambdaTest/playwright-sample/blob/main/playwright-single.js) file to view the sample test script.


4. Pass the below command to run the test.

```
node playwright-single.js
```

## View your Playwright test results
***

The LambdaTest Automation Dashboard is where you can see the results of your Playwright tests after running them on the LambdaTest platform. 

The below screenshot of LambdaTest Automation Dashboard shows the Playwright build on the left and the build sessions associated with the selected build on the right.

<img height="400" src="https://user-images.githubusercontent.com/70570645/169819291-57072893-32a4-48bc-b7a3-6c442911eb31.png"/>

On clicking the session name of the respective test, you can view the details of Playwright test session that you just executed. For example, the below screenshot shows a test execution details of Playwright test like Test Name, Test ID, selected configurations, test logs, basic info, input config, and test session video. 

<img height="400" src="https://user-images.githubusercontent.com/70570645/169819492-9b89a3ec-3db3-44f7-8ced-11eb747b9f2c.png"/>

## Parallel Testing With Playwright
* * *

LambdaTest allows you to perform parallel testing with Playwright across 40+ browsers and OS to automate your several test cases simultaneously. You can run one test case across various browsers, or you can run multiple test case scenarios in the same browser with different browser versions.


Shown below are the steps on running parallel tests with Playright on the LambdaTest platform. 

1. Clone the [LambdaTest-Playwright GitHub repository](https://github.com/LambdaTest/playwright-sample) and switch to the cloned directory.

```js
git clone https://github.com/LambdaTest/playwright-sample.git
cd playwright-sample
```

2. Ensure you have npm dependencies installed. 

3. Configure your LambdaTest authentication credentials.

Once you are done with the above-mentioned steps, you can run your parallel tests with Playwright on LambdaTest. 

**Test Scenario**: Check out [playwright-parallel.js](https://github.com/LambdaTest/playwright-sample/blob/main/playwright-parallel.js) file to view the sample test script.

4. Pass the below command to run the test.

```
node playwright-parallel.js
```

## Run Playwright Tests In Gitpod
***

Select the button below to try this demo in [Gitpod](https://www.gitpod.io/)

[<img alt="Run in Gitpod" width="200px" align="center" src="https://user-images.githubusercontent.com/70570645/169987363-1408c494-4e2a-4f12-8828-c931eac716b0.png" />](https://gitpod.io/#https://github.com/LambdaTest/playwright-sample)

* After the Gitpod session launches, navigate to the terminal and run the following commands to save your [LambdaTest Credentials](https://accounts.lambdatest.com/detail/profile) to Gitpod as environment variables:

```
eval $(gp env -e LT_USERNAME=******)
eval $(gp env -e LT_ACCESS_KEY=******)
  ```

* Click the following link if you're unsure how to [access your LambdaTest credentials.](https://www.lambdatest.com/support/docs/using-environment-variables-for-authentication-credentials/). Also, if you start a new terminal in Gitpod, you have to run the following command to reset envrionment variables:
```
 eval $(gp env -e)
```
For more information, refer to [Gitpod documentation](https://www.gitpod.io/docs/47_environment_variables/)

## LambdaTest Community :busts_in_silhouette:
***
The [LambdaTest Community](https://community.lambdatest.com/) allows people to interact with tech enthusiasts. Connect, ask questions, and learn from tech-savvy people. Discuss best practises in web development, testing, and DevOps with professionals from across the globe.

## Documentation & Resources :books:
***
      
If you want to learn more about the LambdaTest's features, setup, and usage, visit the [LambdaTest documentation](https://www.lambdatest.com/support/docs/). You can also find in-depth tutorials around test automation, mobile app testing, responsive testing, manual testing on [LambdaTest Blog](https://www.lambdatest.com/blog/) and [LambdaTest Learning Hub](https://www.lambdatest.com/learning-hub/).     
      
 ## About LambdaTest
***
[LambdaTest](https://www.lambdatest.com) is a leading test execution and orchestration platform that is fast, reliable, scalable, and secure. It allows users to run both manual and automated testing of web and mobile apps across 3000+ different browsers, operating systems, and real device combinations. Using LambdaTest, businesses can ensure quicker developer feedback and hence achieve faster go to market. Over 500 enterprises and 1 Million + users across 130+ countries rely on LambdaTest for their testing needs.

[<img height="70" src="https://user-images.githubusercontent.com/70570645/169649126-ed61f6de-49b5-4593-80cf-3391ca40d665.PNG">](https://accounts.lambdatest.com/register)
      
## We are here to help you :headphones:
***
* Got a query? we are available 24x7 to help. [Contact Us](mailto:support@lambdatest.com)
* For more info, visit - https://www.lambdatest.com

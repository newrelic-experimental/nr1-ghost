[![New Relic Experimental header](https://github.com/newrelic/opensource-website/raw/master/src/images/categories/Experimental.png)](https://opensource.newrelic.com/oss-category/#new-relic-experimental)

# Ghost Accounts

This application shows you which accounts across your Organisation have no data reporting for the purposes of removing them

## Value 

|Metrics | Events | Logs | Traces | Visualization | Automation |
|:-:|:-:|:-:|:-:|:-:|:-:|
|:x:|:x:|:x:|:x:|:x:|:white_check_mark:|


## Installation

Clone repo then:
 - `npm install`
 - `nr1 nerdpack:uuid -gf`

To publish to your account:
 - `nr1 nerdpack:publish`
  
To serve locally:
 - `nr1 nerdpack:serve`

## Getting Started

Simply open the app and it will start running queries on all the accounts in New Relic that your user has access
## Usage

Features include:
 - Update query period using the TimePicker
 - Download account data as a CSV for further admin tracking


## Support

New Relic has open-sourced this project. This project is provided AS-IS WITHOUT WARRANTY OR DEDICATED SUPPORT. Issues and contributions should be reported to the project here on GitHub.

>We encourage you to bring your experiences and questions to the [Explorers Hub](https://discuss.newrelic.com) where our community members collaborate on solutions and new ideas.


## Contributing

We encourage your contributions to improve [Project Name]! Keep in mind when you submit your pull request, you'll need to sign the CLA via the click-through using CLA-Assistant. You only have to sign the CLA one time per project. If you have any questions, or to execute our corporate CLA, required if your contribution is on behalf of a company, please drop us an email at opensource@newrelic.com.

**A note about vulnerabilities**

As noted in our [security policy](../../security/policy), New Relic is committed to the privacy and security of our customers and their data. We believe that providing coordinated disclosure by security researchers and engaging with the security community are important means to achieve our security goals.

If you believe you have found a security vulnerability in this project or any of New Relic's products or websites, we welcome and greatly appreciate you reporting it to New Relic through [HackerOne](https://hackerone.com/newrelic).

## License

nr1-ghost is licensed under the [Apache 2.0](http://apache.org/licenses/LICENSE-2.0.txt) License.

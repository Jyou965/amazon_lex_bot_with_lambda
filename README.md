# amazon_lex_bot_with_lambda
Challenge 15

This is a bot that recommends retirement investment plans by using AWS Lex and Lambda.

---

## Libraries and Dependancies

* [datetime](https://docs.python.org/3/library/datetime.html) - supplies classes for manipulating dates and times.

* [dateutil.relativedelta](https://dateutil.readthedocs.io/en/stable/relativedelta.html) - designed to be applied to an existing datetime and can replace specific components of that datetime, or represents an interval of time.

---

## Usage

The bot is generated in the following steps:

1. Configure the initial robo advisor by using Amazon Lex bot with a single intent that establishes a conversation about requirements to suggest an investment portfolio for retirement.

2. Build and test the robo advisor to make sure that the bot works and accurately responds during the conversation with the user.  See results below:
[

https://user-images.githubusercontent.com/80657579/124700652-ed768300-dea1-11eb-8b63-4d9f040b8a2e.mov

]

3. Enhance the robo advisor with an Amazon Lambda function by creating an Amazon Lambda function that validates the user's input and returns the investment portfolio recommendation. This includes testing the Amazon Lambda function and integrating it with the bot.  See results below:
[

https://user-images.githubusercontent.com/80657579/124700728-18f96d80-dea2-11eb-9209-11d53123a595.mov

]

By using the bot, people can get a quick recommendation of how they should position their portfolio for retirement.

---

## Contributors

Jackie You with the support of FinTech Boot Camp Staff

---

## License

Berkeley
# Create your AWS account

Do this before the session. Sign-up takes about 15 minutes, and AWS can take up to 24 hours to activate a new account.

## Status

These steps follow the AWS documentation for [Sign up for AWS (advanced)](https://docs.aws.amazon.com/accounts/latest/reference/getting-started.html), read on 2026-11-17. Nobody has yet run the [README](README.md) steps on a new Free plan account made this way. This page will say when someone has.

## Use the advanced sign-up

AWS has two sign-up pages. Use this one:

**<https://signin.aws.amazon.com/signup?request_type=register>**

Do not use **Sign up for AWS (new)**, the option that signs you in with an AWS Builder ID. An account made that way cannot choose its AWS Region. It also cannot use cross-Region features, and the model this workshop uses needs one ([AWS documentation](https://docs.aws.amazon.com/accounts/latest/reference/supported-services-sign-up-new.html)).

## What you need

- An email address you can read now. It becomes your sign-in name.
- A phone that can receive a text message or a call.
- A credit or debit card. AWS does not let you finish sign-up without one.

## Steps

1. Open the sign-up page above.
2. Enter your email address and an account name, such as `firstname-lastname-learning`. Choose **Verify email address**.
3. Enter the code from the email, and choose **Verify**.
4. Make a password and save it in a password manager. Choose **Continue**.
5. Choose your account plan: **Free plan**. See [Choosing a plan](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/free-tier-plans.html) for the difference.
6. Enter your contact information, read the AWS Customer Agreement, and accept it.
7. Enter your card details.
8. Confirm your phone number. Enter the code that AWS sends you.
9. For the support plan, choose **Basic support (free)**.
10. Choose **Complete sign up**.
11. Wait for the activation email. Check your spam folder.

## After the activation email

1. Sign in at <https://console.aws.amazon.com> with your email address and password.
2. In the top-right corner, set the Region to **Canada (Central) ca-central-1**.
3. Set up multi-factor authentication (MFA) on your account. Follow [Multi-factor authentication for AWS account root user](https://docs.aws.amazon.com/IAM/latest/UserGuide/enable-mfa-for-root.html).
4. Set a budget alert. Follow [Before you start: set a budget alert](README.md#before-you-start-set-a-budget-alert) in the README.

That is all. Do not deploy anything before the session.

## If something goes wrong

- **No activation email after 24 hours:** see [Troubleshoot your AWS account](https://docs.aws.amazon.com/accounts/latest/reference/troubleshooting.html).
- **Your account is already on the new sign-up:** come anyway. Tell the presenter at the start.

**Summary**
- Use the advanced sign-up page, not the Builder ID option.
- You need an email address, a phone and a card.
- Choose the Free plan and Basic support.
- After activation, select ca-central-1, turn on MFA and set a budget alert.
- Do not deploy anything before the session.

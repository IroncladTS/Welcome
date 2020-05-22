# Getting Started with GitHub at Ironclad


## 1. Your GitHub account

**If you already have a GitHub account**, please [add your work email to your profile](https://github.com/settings/emails) as your primary email. You do not need to create a separate GitHub account for work. We'll just add you to the team.

**If you are new to GitHub**, please [sign up](https://github.com/join) for a GitHub account. You'll want to add both your work email and personal email into this account as you'll likely use this account in other contexts, jobs, personal projects, etc...


## 2. Complete your profile

Include the following:

- Name: Your first or first and last name.
- Company: Your government agency. (If you also use GitHub for personal projects, consider specifying &ldquo;<code>agency</code> (work) + personal projects&rdquo; to make it clear that some of your GitHub projects may be personal in nature.)
- Location: Your primary work location (city, state).
- Photo: A headshot photo, or an image that is unique to you.

## 3. Set up two-factor authentication

[Enable two-factor authentication (2FA)](https://github.com/settings/security):

- [Use your work email](https://help.github.com/articles/setting-your-email-in-git) rather than your personal email for work-related commits. This only applies to people with more than one email address tied to their GitHub account. Note that this is different than [setting notifications to go to a specific email address](https://help.github.com/articles/choosing-the-delivery-method-for-your-notifications/). If you make commits via GitHub&rsquo;s web interface, it will use your &ldquo;primary&rdquo; email address for those commits, so check your [email settings](https://github.com/settings/emails) before making web commits.

- If you're using your work computer for personal projects on GitHub and want your personal email tied to those commits, you can set your GSA email as part of the global `.gitconfig`, then [override on a repository level](http://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration) with your personal email, or use a tool like [karn](https://github.com/prydonius/karn). If you have both emails in your [GitHub settings](https://github.com/settings/emails), they will both be tied to your GitHub account anyway.


## 4. Turn notifications on

**[Turn notifications on](https://github.com/settings/notifications)** and adjust the settings as needed. Some people watch every repo; others only watch when they're mentioned.

You will get a lot of emails when you turn notifications on. To help stem the tide, you can set up a Gmail filter to automatically archive emails from `notifications@github.com`. However, you probably want to let through those emails that contain your GitHub username or are posted to a repo you're watching. Since on GitHub, each repo is considered its own mailing list, checking for that identifier is one reliable way to allow these notifications through. For example, if the repo name in GitHub is `ironcladts/welcome`, the mailing list will be `welcome.ironcladts.github.com`. You can also find this by opening an email from the desired repo, clicking the "more info" arrow in the "To" field, and copying the bracketed address in the "mailing list" field. Adding `list:(welcome.ironcladts.github.com)` to your filter's exceptions will allow any issues posted to that repo to reach your inbox.

## 4. Get added to the Ironclad Team

Send your GitHub username to [jim.bates@ironcladts.com](mailto:jim.bates@ironcladts.com). We'll add you as a contributor in our repo (~24hrs). Once we do, you should receive an email.

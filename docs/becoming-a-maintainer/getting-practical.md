---
id: getting-practical
title: "চলুন হাতে-কলমে শুরু করি: আপনার প্রজেক্ট চালু করা"
sidebar_label: "হাতে-কলমে শুরু"
keywords: ["হাতে-কলমে ওপেন সোর্স প্রজেক্ট শুরু", "প্রথম ওপেন সোর্স প্রজেক্ট তৈরি", "ওপেন সোর্স রিপোজিটরি তৈরি", "README টেমপ্লেট", "CONTRIBUTING টেমপ্লেট", "ইস্যু ফর্ম তৈরি", "ওপেন সোর্স প্রজেক্টের প্রচার", "ওপেন সোর্স মেইনটেইনার টিউটোরিয়াল", "ওপেন সোর্স মেইনটেইনার", "Open Source", "Open Source Community"]
---

কোর্সটি শেষ করে এবং একজন সফল মেইনটেইনার হতে কী লাগে তা বুঝে ফেলার পর চলুন হাতে-কলমে শুরু করি এবং মেইনটেইনার হিসেবে আপনার প্রথম ওপেন সোর্স প্রজেক্ট চালু করি!

## পূর্বশর্ত

আপনার লাগবে:

- একটি [GitHub অ্যাকাউন্ট](https://github.com)

## আপনার প্রজেক্ট বেছে নেওয়া

কখনো কখনো সবচেয়ে কঠিন অংশ হলো ঠিক করা, কী নিয়ে কাজ করবেন। শুরু করার জন্য কয়েকটি সাধারণ ধারণা:

- ওপেন সোর্স কমিউনিটির কোনো সমস্যা বা প্রয়োজন শনাক্ত করুন।
- এমন কোনো বিষয়ের কথা ভাবুন, যা নিয়ে আপনি আবেগী এবং যাতে অন্যরাও আগ্রহী হতে পারেন।
- এমন কোনো সমস্যার কথা ভাবুন, যা আপনাকে সমাধান করতে হয়েছে এবং যা থেকে অন্যরাও উপকৃত হতে পারেন।

আপাতত খুব বেশি ভাববেন না। আপনি সবসময় পরে ফিরে এসে বিষয়গুলো হালনাগাদ করতে পারবেন। এখনকার জন্য কোথা থেকে শুরু করবেন বুঝতে না পারলে আসুন আপনার প্রিয় ওপেন সোর্স রিসোর্সগুলোর জন্য একটি রিপোজিটরি তৈরি করি।

## আপনার রিপোজিটরি তৈরি করা

GitHub-এ কীভাবে আপনার প্রজেক্ট সেটআপ করবেন, তা আমরা ধাপে ধাপে দেখাব। প্রজেক্ট শুরু করার এটিই একমাত্র উপায় নয়, তবে এই প্রদর্শনীতে আমরা এটিই ব্যবহার করব।

- [GitHub](https://github.com)-এ গিয়ে সাইন ইন করুন।
- ওপরের ডান কোণের "+" আইকনে ক্লিক করে "New repository" বেছে নিন।
- রিপোজিটরির একটি নাম ও বর্ণনা দিন এবং রিপোজিটরিটি পাবলিক হবে নাকি প্রাইভেট, তা বেছে নিন।
- একটি README ফাইল দিয়ে রিপোজিটরি শুরু করুন এবং একটি লাইসেন্স যোগ করুন।
- "Create repository" বোতামে ক্লিক করুন।

![রিপোজিটরি সেট আপ করা](../_assets/gifs/set-up-repo.gif)

আমাদের শুরুর ধারণাটি ব্যবহার করলে আপনি এটি দিতে পারেন (নাম ও বর্ণনা ইংরেজিতেই রাখা হয়েছে, কারণ এটি রিপোজিটরির নাম ও বর্ণনা হিসেবে বসবে। বর্ণনার অর্থ: "আমার সবচেয়ে সহায়ক মনে হওয়া রিসোর্সগুলোর একটি Markdown ফাইল"):

    - Name: favorite-open-source-resources
    - Description: A markdown file of resources I've found most helpful.

## রিপোজিটরির ডকুমেন্টেশন যোগ করা

রিপোজিটরি তৈরি হয়ে গেছে, এখন আপনি সরাসরি GitHub-এ এটি সম্পাদনা করতে পারেন, কিংবা প্রজেক্টটি ক্লোন করে লোকালিও কাজ করতে পারেন। "[আপনার ওপেন সোর্স প্রজেক্ট কীভাবে সেটআপ করবেন](how-to-setup-your-project.md)" অধ্যায়ে আমরা আগে শিখেছি কীভাবে বিস্তারিত README, কন্ট্রিবিউটিং গাইড ও আচরণবিধি তৈরি করতে হয়। মনে করিয়ে নেওয়ার দরকার হলে সেই অধ্যায়টি আবার দেখুন।

### আপনার README তৈরি করা

আপনার প্রজেক্টে ইতোমধ্যে একটি README ফাইল আছে, তবে তাতে প্রজেক্ট সম্পর্কে তথ্য দিয়ে হালনাগাদ করা ভালো। এখানে আপনি ব্যবহার করতে পারেন এমন একটি টেমপ্লেট দেওয়া হলো (টেমপ্লেটটি আপনার রিপোজিটরিতে কপি করার জন্য, তাই ইংরেজিতেই রাখা হয়েছে):

```markdown
# Project Name

## Overview

Provide a brief, high-level overview of your project. Include the goals and core values of the project. Explain how it contributes to the open source community and any specific problems it aims to solve.

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Usage](#usage)
- [Contributing to the Project](#contributing-to-the-project)
- [Acknowledgments](#acknowledgments)
- [License](#license)

## Getting Started

### Installation

Instructions on how to install the project. Include any prerequisites or dependencies.

### Usage

Guide on how to use the project, including any configuration steps or basic examples.

## Contributing to the Project

General instructions on how to submit contributions to the project, with a link to your CONTRIBUTING.md file. Also, include information on how to engage with the community and maintainers.

## Acknowledgments

Show appreciation for the community's contributions, including developers, writers, and any other contributors.

## License

State the license under which the project is released and provide a link to the full license text.
```


### লাইসেন্স যোগ করা

আপনার প্রজেক্ট লাইসেন্সসহ শুরু করা উচিত ছিল। তা না করে থাকলে আপনি রিপোজিটরির রুটে `LICENSE` নামে একটি নতুন ফাইল তৈরি করে লাইসেন্স যোগ করতে পারেন। আপনার প্রজেক্টের জন্য সঠিক লাইসেন্স বেছে নিতে [Choose a License](https://choosealicense.com/) ওয়েবসাইট সাহায্য করতে পারে।

### অবদান রাখার নির্দেশিকা তৈরি করা

আপনার প্রজেক্টের অবদানের নির্দেশিকা সম্ভবত অন্য প্রজেক্টগুলোর মতোই হবে। নির্দেশিকা তৈরি করতে ও একটি টেমপ্লেট দিতে আপনি এই ধাপগুলো অনুসরণ করতে পারেন। তবে নির্দিষ্ট কোনো উদাহরণ দরকার হলে আপনি সবসময় [OpenSauced Contributing Guidelines](https://opensauced.pizza/docs/contributing/introduction-to-contributing/) দেখতে পারেন। নির্দ্বিধায় সেই নির্দেশিকা ব্যবহার করুন এবং নিজের প্রজেক্টের জন্য যেভাবে ঠিক মনে করেন, সেভাবে হালনাগাদ করুন।

- [ ] আপনার রিপোজিটরির রুটে `CONTRIBUTING.md` নামে একটি নতুন ফাইল তৈরি করুন।
- [ ] ইস্যু ও পুল রিকোয়েস্ট জমা দেওয়ার প্রক্রিয়ার রূপরেখা দিন।
- [ ] কোডিং মানদণ্ড, স্টাইল গাইড বা বিশেষ কোনো প্রয়োজনীয়তা অন্তর্ভুক্ত করুন।
- [ ] কন্ট্রিবিউটররা কীভাবে সাহায্য বা ব্যাখ্যা চাইতে পারেন, তা উল্লেখ করুন।

#### কন্ট্রিবিউটিং গাইডলাইন টেমপ্লেট

```markdown
# Contributing to [Project Name]

Welcome to [Project Name]! We're thrilled you're considering contributing to our project. Every contribution, whether it's code, bug reports, feature requests, documentation, or community engagement, plays a significant role in its success.

## How to Contribute

We value all forms of contributions, not just code. Here's how you can contribute:

- **Code Contributions**: Check our issues labeled `good first issue` or `help wanted`.
- **Documentation**: Improvements to documentation, tutorials, or guides.
- **Community**: Participating in discussions, helping others, and sharing your experiences with the project.

## Getting Started

1. **Setting Up**: Here's how you can set up [Project Name] for development...
2. **Making Changes**: A guide to making changes and testing them.
3. **Submitting Contributions**: Steps to submit your contributions via Pull Requests.

## Community and Communication

- **Code of Conduct**: We have a Code of Conduct that all contributors are expected to adhere to.
- **Where to Ask Questions**: Join our Slack/Discord or post questions in our forums.

## Review Process

After you submit your contribution, here's what happens next...

## Recognition

We believe in recognizing all contributions, not just code. Here's how we do it...

## Additional Resources

- **FAQs**
- **Learning Resources**

Thank you for contributing to [Project Name]!
```


### আচরণবিধি যোগ করা

আপনার প্রজেক্টে প্রত্যেকে যেন স্বাগত ও নিরাপদ বোধ করেন, তা নিশ্চিত করতে একটি আচরণবিধি থাকা অত্যাবশ্যক। আপনার প্রজেক্টে একটি যোগ করার দুটি উপায় আছে:

1. **টেমপ্লেট ব্যবহার করুন**। GitHub দ্রুত একটি সেট আপ করতে সাহায্য করার জন্য সাধারণ আচরণবিধির টেমপ্লেট দেয়। আপনার প্রজেক্টে একটি যোগ করতে [তাদের ডকুমেন্টেশনের নির্দেশনা](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-code-of-conduct-to-your-project#adding-a-code-of-conduct-using-a-template) পড়তে পারেন।

2. **ম্যানুয়ালি যোগ করুন**। অন্য আচরণবিধি থেকে কপি বা মানিয়ে নিতে চাইলে আপনাকে এই ধাপগুলো অনুসরণ করে ম্যানুয়ালি আপনার আচরণবিধি যোগ করতে হবে:

   - [ ] আপনার রিপোজিটরির রুটে `CONTRIBUTING.md` নামে একটি নতুন ফাইল তৈরি করুন।
   - [ ] আপনি যে আচরণবিধি ব্যবহার করতে চান, সেটি কপি করে পেস্ট করুন। আমরা [Contributor Covenant](https://www.contributor-covenant.org/) ব্যবহারের পরামর্শ দিই।
   - [ ] আপনার README ও CONTRIBUTING ফাইলে আচরণবিধির একটি লিংক যোগ করুন।

   :::note

   আচরণবিধির মূল লেখককে অবশ্যই কৃতিত্ব দিন।

   :::

### ইস্যু ফর্ম, পুল রিকোয়েস্ট টেমপ্লেট ও লেবেল ব্যবহার করা

ভালো ইস্যু তৈরি করা এবং লেবেল ব্যবহার করা একটি মজবুত প্রজেক্ট গড়তে সাহায্য করবে। প্রথম ইস্যু তৈরি করার আগে আপনার কন্ট্রিবিউটরদের জন্য ইস্যু জমা দেওয়ার প্রক্রিয়া স্পষ্ট করতে ইস্যু টেমপ্লেট তৈরি দিয়ে শুরু করুন।

#### ইস্যু ফর্ম তৈরি করা

এই অংশে আমরা বাগ রিপোর্টের জন্য একটি ইস্যু টেমপ্লেট তৈরি করব। ফিচারের অনুরোধ, প্রশ্ন বা ডকুমেন্টেশনের অনুরোধের মতো অন্যান্য ধরনের ইস্যুর জন্যও আপনি টেমপ্লেট তৈরি করতে পারেন।

নিচে টেমপ্লেট তৈরির ধাপগুলো দেওয়া হলো। ধাপগুলোর পর আমরা OpenSauced-এ যা ব্যবহার করি তা আপনাদের সাথে ভাগ করব। নির্দ্বিধায় সেই তথ্য আপনার রিপোজিটরিতে কপি-পেস্ট করুন এবং প্রয়োজনমতো হালনাগাদ করুন।

##### বাগ রিপোর্ট

- [ ] আপনার রিপোজিটরির রুটে `.github` নামে একটি নতুন ফোল্ডার তৈরি করুন।
- [ ] সেই ফোল্ডারের ভেতরে `ISSUE_TEMPLATE` নামে একটি নতুন ফোল্ডার তৈরি করুন।
- [ ] `.github/ISSUE_TEMPLATE` ডিরেক্টরিতে `bug_report.yml` নামে একটি নতুন ফাইল তৈরি করুন।
- [ ] টেমপ্লেটে একটি নাম (🐛 Bug report), বর্ণনা (Create a bug report to help us improve Open Sauced 🍕) এবং শিরোনাম ("Bug: ") যোগ করুন।
- [ ] এই ইস্যু তৈরি হলে স্বয়ংক্রিয়ভাবে নির্দিষ্ট কোনো লেবেল যুক্ত হোক চাইলে সেগুলো টেমপ্লেটে যোগ করুন। (`labels: [👀 needs triage, 🐛 bug]`)
- [ ] এরপর আপনি বডি যোগ করবেন, যাতে প্রতিটি অংশের জন্য ধরন ও অ্যাট্রিবিউট থাকে। এতে সাধারণত বাগ পুনরুৎপাদনের ধাপগুলোর একটি চেকলিস্ট থাকে। এই অংশের জন্য আপনাকে:
  - [ ] প্রত্যাশিত আচরণ ও প্রকৃত আচরণের জন্য একটি অংশ যোগ করতে হবে।
  - [ ] বাগ পুনরুৎপাদনের ধাপগুলোর একটি চেকলিস্ট যোগ করতে হবে।
  - [ ] প্রযোজ্য হলে স্ক্রিনশটের জন্য একটি অংশ যোগ করতে হবে।
  - [ ] প্রযোজ্য হলে বাড়তি প্রেক্ষাপটের জন্য একটি অংশ যোগ করতে হবে।
- [ ] সবশেষে আচরণবিধি ও কন্ট্রিবিউটিং ডকুমেন্টেশনের জন্য একটি অংশ যোগ করুন।

OpenSauced-এ আমরা যা ব্যবহার করি:

```yml
name: 🐛 Bug report
description: Create a bug report to help us improve Open Sauced 🍕
title: "Bug: "
labels: [👀 needs triage, 🐛 bug]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
  - type: textarea
    attributes:
      label: Describe the bug
      description: A clear and concise description of what the bug is.
    validations:
      required: true
  - type: textarea
    attributes:
      label: Steps to reproduce
      description: Describe how to reproduce the behavior.
      placeholder: |
        1. Go to '...'
        2. Click on '...'
        3. Scroll down to '...'
        4. See error
    validations:
      required: true
  - type: dropdown
    attributes:
      multiple: true
      label: Browsers
      description: Select the browsers where the issue can be reproduced (that you know of).
      options:
        - "Chrome"
        - "Firefox"
        - "Safari"
        - "Edge"
        - "Opera"
        - "Other (add additional context)"
  - type: input
    id: context
    attributes:
      label: Additional context (Is this in dev or production?)
      description: Add any other context about the problem or helpful links here.
  - type: checkboxes
    id: terms
    attributes:
      label: Code of Conduct
      description: By submitting this issue, you agree to follow our [Code of Conduct](https://opensauced.pizza/docs/contributing/code-of-conduct/)
      options:
        - label: I agree to follow this project's Code of Conduct
          required: true
  - type: checkboxes
    id: contribution
    attributes:
      label: Contributing Docs
      description: If you plan on contributing code please read - [Contribution Guide](https://opensauced.pizza/docs/contributing/introduction-to-contributing/)
      options:
        - label: I agree to follow this project's Contribution Docs
          required: false
```


##### ফিচারের অনুরোধ

এবার চলুন একই প্রক্রিয়া অনুসরণ করে একটি ফিচার রিকোয়েস্ট টেমপ্লেট বানাই।

- [ ] `.github/ISSUE_TEMPLATE` ডিরেক্টরিতে `feature_request.yml` নামে একটি নতুন ফাইল তৈরি করুন।
- [ ] টেমপ্লেটে একটি নাম (🚀 Feature request), বর্ণনা (Suggest an idea for this project 💡) এবং শিরোনাম ("Feature: ") যোগ করুন।
- [ ] এই ইস্যু তৈরি হলে স্বয়ংক্রিয়ভাবে নির্দিষ্ট কোনো লেবেল যুক্ত হোক চাইলে সেগুলো টেমপ্লেটে যোগ করুন। আমরা 👀 needs triage ও 💡 feature ব্যবহার করি।
- [ ] এরপর আপনি বডি যোগ করবেন, যাতে প্রতিটি অংশের জন্য ধরন ও অ্যাট্রিবিউট থাকে। এতে সাধারণত বাগ পুনরুৎপাদনের ধাপগুলোর একটি চেকলিস্ট থাকে। এই অংশের জন্য আপনাকে:
  - [ ] প্রত্যাশিত আচরণ ও প্রকৃত আচরণের জন্য একটি অংশ যোগ করতে হবে।
  - [ ] ফিচারের অনুরোধের ধরনের জন্য একটি ড্রপডাউন যোগ করতে হবে।
  - [ ] প্রস্তাবিত সমাধানের জন্য একটি অংশ যোগ করতে হবে।
  - [ ] প্রযোজ্য হলে স্ক্রিনশটের জন্য একটি অংশ যোগ করতে হবে।
  - [ ] প্রযোজ্য হলে বাড়তি প্রেক্ষাপটের জন্য একটি অংশ যোগ করতে হবে।
- [ ] সবশেষে আচরণবিধি ও কন্ট্রিবিউটিং ডকুমেন্টেশনের জন্য একটি অংশ যোগ করুন।

OpenSauced-এ আমরা যা ব্যবহার করি:

```yml
name: 🚀 Feature request
description: Suggest an idea for this project 💡
title: "Feature: "
labels: [👀 needs triage, 💡 feature]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this feature request!
  - type: dropdown
    attributes:
      multiple: false
      label: Type of feature
      description: Select the type of feature request, the lowercase should also be the PR prefix.
      options:
        - "🍕 Feature"
        - "🐛 Fix"
        - "📝 Documentation"
        - "🎨 Style"
        - "🧑‍💻 Refactor"
        - "🔥 Performance"
        - "✅ Test"
        - "🤖 Build"
        - "🔁 CI"
        - "📦 Chore"
        - "⏩ Revert"
    validations:
      required: true
  - type: textarea
    attributes:
      label: Current behavior
      description: Is your feature request related to a problem? Please describe.
    validations:
      required: true
  - type: textarea
    attributes:
      label: Suggested solution
      description: Describe the solution you'd like.
  - type: input
    id: context
    attributes:
      label: Additional context
      description: Add any other context about the problem or helpful links here.
  - type: checkboxes
    id: terms
    attributes:
      label: Code of Conduct
      description: By submitting this issue, you agree to follow our [Code of Conduct](https://opensauced.pizza/docs/contributing/code-of-conduct/)
      options:
        - label: I agree to follow this project's Code of Conduct
          required: true
  - type: checkboxes
    id: contribution
    attributes:
      label: Contributing Docs
      description: If you plan on contributing code please read - [Contribution Guide](https://opensauced.pizza/docs/contributing/introduction-to-contributing/)
      options:
        - label: I agree to follow this project's Contribution Docs
          required: false
```


#### আপনার প্রথম ইস্যু লেখা

- আপনার রিপোজিটরিতে "Issues" ট্যাবে এবং তারপর "New issue" বোতামে ক্লিক করুন।

  ![ইস্যু তৈরি](../_assets/images/create-issue.png)

- আপনি কোন ধরনের ইস্যু তৈরি করতে চান, তা বেছে নিন। এই উদাহরণে আমরা Feature Request বেছে নেব।
- আপনার ইস্যু লিখুন। উদাহরণটি অনুসরণ করলে আমরা একটি নতুন রিসোর্সের জন্য ফিচারের অনুরোধ লিখব:

  ```markdown
  **Type of feature:** 🍕 Feature
  **Current behavior:** I'd like to see a new resource for #100DaysOfOSS.
  **Suggested solution:** Add a new resource that introduces people to open source through [#100DaysOfOSS](https://opensauced.pizza/docs/community/100-days-of-oss/).
  **Code of Conduct:** I agree to follow this project's Code of Conduct.
  **Contributing Docs:** I agree to follow this project's Contribution Docs.
  ```


- ইস্যু পূরণ করা হলে "Submit new issue"-তে ক্লিক করুন।

  ![feature-form.png](../_assets/images/feature-form.png)

### আপনার প্রজেক্টের প্রচার

প্রজেক্ট সেট আপ হয়ে গেছে, এবার এর প্রচারের সময়! শুরু করার জন্য কয়েকটি ধারণা:

- আপনার প্রজেক্ট সোশ্যাল মিডিয়া, ফোরাম ও প্রাসঙ্গিক কমিউনিটিতে শেয়ার করুন।
- আপনার প্রজেক্ট নিয়ে ব্লগ পোস্ট বা টিউটোরিয়াল লিখুন।
- মিটআপ, সম্মেলন বা অনলাইন ওয়েবিনারে আপনার প্রজেক্ট উপস্থাপন করুন।
- পেশাগত দৃশ্যমানতার জন্য LinkedIn, X (Twitter) বা Mastodon-এ আপনার প্রজেক্ট নিয়ে পোস্ট করুন।
- বন্ধু, পরিবার ও সহকর্মীদের সাথে আপনার প্রজেক্ট শেয়ার করুন।
- আপনার নেটওয়ার্কের কাছ থেকে মতামত চান।

### অবদানের স্বীকৃতি

কন্ট্রিবিউটররা যেখানে মূল্যবান বোধ করেন, এমন একটি সুস্থ প্রজেক্ট বজায় রাখতে অবদানের স্বীকৃতি দেওয়া গুরুত্বপূর্ণ। এটি করার কয়েকটি উপায়:

- বিভিন্ন ধরনের অবদানের স্বীকৃতি দিতে [All Contributors](https://allcontributors.org) বটের মতো টুল ব্যবহার করুন।
- আপনার README-তে বা প্রজেক্টের ওয়েবসাইটে কন্ট্রিবিউটরদের তুলে ধরুন।
- ধন্যবাদ জানিয়ে এবং তাঁদের PR বা ইস্যুর লিংক দিয়ে কন্ট্রিবিউটরদের অর্জন সোশ্যাল মিডিয়ায় শেয়ার করুন।
- কন্ট্রিবিউটরদের কাজের জন্য প্রকাশ্যে ধন্যবাদ জানান।

### আপনার প্রজেক্ট পর্যবেক্ষণ

আপনার প্রজেক্ট চালু হয়ে গেলে এর সুস্থতা ও কার্যকলাপ পর্যবেক্ষণ করা গুরুত্বপূর্ণ। এটি করার কয়েকটি উপায়:

- আপনার প্রজেক্টের কার্যকলাপ ট্র্যাক করতে একটি OpenSauced [Workspace](https://opensauced.pizza/docs/features/workspaces/) তৈরি করুন।
- নতুন ইস্যু ও পুল রিকোয়েস্টের জন্য নোটিফিকেশন সেট আপ করুন।
- ডিসকাশন বা জরিপের মাধ্যমে ব্যবহারকারী ও কন্ট্রিবিউটরদের কাছ থেকে মতামত নিন।
- প্রজেক্টের দিকনির্দেশনা নিয়ে ভাবুন এবং প্রয়োজনমতো সমন্বয় করুন।

OpenSauced দিয়ে কীভাবে একটি সফল প্রজেক্ট গড়বেন, তা আমাদের [Maintainers Guide to OpenSauced](https://opensauced.pizza/docs/maintainers/maintainers-guide-to-open-sauced/)-এ আরও জানতে পারবেন।

---

আপনার প্রথম প্রজেক্ট তৈরির জন্য অভিনন্দন! এখন আপনি এটি আমাদের [মেইনটেইনারদের অতিথি-খাতা](maintainers-guestbook.md) পাতায় শেয়ার করতে পারেন।

:::tip

মনে রাখবেন, এই ধাপগুলো নির্দেশিকা মাত্র। একটি সুস্থ ওপেন সোর্স প্রজেক্টের চাবিকাঠি হলো একটি উন্মুক্ত, অন্তর্ভুক্তিমূলক ও সহযোগিতামূলক পরিবেশ গড়ে তোলা।

:::

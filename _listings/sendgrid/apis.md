---
name: SendGrid
x-slug: sendgrid
description: SendGrid is a cloud-based email service that delivers email on behalf
  of companies to increase deliverability and improve customer communications integration
  with new or existing email systems is done via SMTP or through a REST API, providing
  metrics on outgoing email, and handles unsubscribe links, abiding by anti-spam regulations.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sendgrid-logo.png
x-kinRank: "9"
x-alexaRank: ""
tags: Spam
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/spam/master/_listings/sendgrid/apis.md
specificationVersion: "0.14"
apis:
- name: SendGrid Get Mail Settings Forward Spam
  x-api-slug: sendgrid
  description: "**This endpoint allows you to retrieve your current Forward Spam mail
    settings.**\n\nEnabling the forward spam setting allows you to specify an email
    address to which spam reports will be forwarded.\n\nMail settings allow you to
    tell SendGrid specific things to do to every email that you send to your recipients
    over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
    or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sendgrid-logo.png
  humanURL: https://sendgrid.com/
  baseURL: https://api.sendgrid.com//v3//mail_settings/forward_spam
  tags: Email,Mail, Settings, Forward, Spam
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/spam/master/_listings/sendgrid/mail-settingsforward-spam-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/spam/master/_listings/sendgrid/mail-settingsforward-spam-get-openapi.md
- name: SendGrid Patch Mail Settings Forward Spam
  x-api-slug: sendgrid
  description: "**This endpoint allows you to update your current Forward Spam mail
    settings.**\n\nEnabling the forward spam setting allows you to specify an email
    address to which spam reports will be forwarded.\n\nMail settings allow you to
    tell SendGrid specific things to do to every email that you send to your recipients
    over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
    or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sendgrid-logo.png
  humanURL: https://sendgrid.com/
  baseURL: https://api.sendgrid.com//v3//mail_settings/forward_spam
  tags: Email,Mail, Settings, Forward, Spam
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/spam/master/_listings/sendgrid/mail-settingsforward-spam-patch-openapi.md
- name: SendGrid Get Mail Settings Spam Check
  x-api-slug: sendgrid
  description: "**This endpoint allows you to retrieve your current Spam Checker mail
    settings.**\n\nThe spam checker filter notifies you when emails are detected that
    exceed a predefined spam threshold.\n\nMail settings allow you to tell SendGrid
    specific things to do to every email that you send to your recipients over SendGrid\u2019s
    [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP
    Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sendgrid-logo.png
  humanURL: https://sendgrid.com/
  baseURL: https://api.sendgrid.com//v3//mail_settings/spam_check
  tags: Email,Mail, Settings, Spam, Check
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/spam/master/_listings/sendgrid/mail-settingsspam-check-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/spam/master/_listings/sendgrid/mail-settingsspam-check-get-openapi.md
- name: SendGrid Patch Mail Settings Spam Check
  x-api-slug: sendgrid
  description: "**This endpoint allows you to update your current spam checker mail
    settings.**\n\nThe spam checker filter notifies you when emails are detected that
    exceed a predefined spam threshold.\n\nMail settings allow you to tell SendGrid
    specific things to do to every email that you send to your recipients over SendGrid\u2019s
    [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP
    Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sendgrid-logo.png
  humanURL: https://sendgrid.com/
  baseURL: https://api.sendgrid.com//v3//mail_settings/spam_check
  tags: Email,Mail, Settings, Spam, Check
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/spam/master/_listings/sendgrid/mail-settingsspam-check-patch-openapi.md
- name: SendGrid Delete Suppression Spam Reports
  x-api-slug: sendgrid
  description: "**This endpoint allows you to delete your spam reports.**\n\nThere
    are two options for deleting spam reports: \n\n1) You can delete all spam reports
    by setting \"delete_all\" to true in the request body. \n2) You can delete some
    spam reports by specifying the email addresses in an array in the request body.\n\n[Spam
    reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient
    indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html)
    and then their email provider reports this to SendGrid.\n\nFor more information,
    please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html)."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sendgrid-logo.png
  humanURL: https://sendgrid.com/
  baseURL: https://api.sendgrid.com//v3//suppression/spam_reports
  tags: Email,Suppression, Spam, Reports
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/spam/master/_listings/sendgrid/suppressionspam-reports-delete-openapi.md
- name: SendGrid Get Suppression Spam Reports
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to retrieve all spam reports.**

    [Spam reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html) and then their email provider reports this to SendGrid.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sendgrid-logo.png
  humanURL: https://sendgrid.com/
  baseURL: https://api.sendgrid.com//v3//suppression/spam_reports
  tags: Email,Suppression, Spam, Reports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/spam/master/_listings/sendgrid/suppressionspam-reports-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/spam/master/_listings/sendgrid/suppressionspam-reports-get-openapi.md
- name: SendGrid Delete Suppression Spam Reports Email
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to delete a specific spam report.**

    [Spam reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html) and then their email provider reports this to SendGrid.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sendgrid-logo.png
  humanURL: https://sendgrid.com/
  baseURL: https://api.sendgrid.com//v3//suppression/spam_reports/{email}
  tags: Email,Suppression, Spam, Reports, Email
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/spam/master/_listings/sendgrid/suppressionspam-reportsemail-delete-openapi.md
- name: SendGrid Get Suppression Spam Reports Email
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to retrieve a specific spam report.**

    [Spam reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html) and then their email provider reports this to SendGrid.

    For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sendgrid-logo.png
  humanURL: https://sendgrid.com/
  baseURL: https://api.sendgrid.com//v3//suppression/spam_reports/{email}
  tags: Email,Suppression, Spam, Reports, Email
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/spam/master/_listings/sendgrid/suppressionspam-reportsemail-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/spam/master/_listings/sendgrid/suppressionspam-reportsemail-get-openapi.md
- name: SendGrid
  x-api-slug: sendgrid
  description: SendGrids cloud-based email infrastructure relieves businesses of the
    cost and complexity of maintaining custom email systems. SendGrid provides reliable
    delivery, scalability and real-time analytics along with flexible APIs that make
    custom integration a breeze.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sendgrid-logo.png
  humanURL: https://sendgrid.com/
  baseURL: https://api.sendgrid.com//v3
  tags: Spam
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/spam/master/_listings/sendgrid/openapi.md
x-common:
- type: x-net-library
  url: https://sendgrid.com/docs/Code_Examples/csharp.html
- type: x-base
  url: https://api.sendgrid.com
- type: x-blog
  url: http://blog.sendgrid.com/
- type: x-blog-rss
  url: http://feeds.feedburner.com/sendgrid/CDXr
- type: x-contact-form
  url: https://sendgrid.com/contact
- type: x-crunchbase
  url: http://www.crunchbase.com/company/sendgrid
- type: x-developer
  url: https://sendgrid.com/developers
- type: x-documentation
  url: https://sendgrid.com/docs/index.html
- type: x-forum
  url: http://support.sendgrid.com/forums
- type: x-github
  url: https://github.com/sendgrid
- type: x-go-library
  url: https://sendgrid.com/docs/Code_Examples/go.html
- type: x-ios-library
  url: https://sendgrid.com/docs/Code_Examples/ios.html
- type: x-java-library
  url: https://sendgrid.com/docs/Code_Examples/java.html
- type: x-labs
  url: http://labs.sendgrid.com/
- type: x-nodejs-library
  url: https://sendgrid.com/docs/Code_Examples/nodejs.html
- type: x-partners
  url: https://sendgrid.com/partners
- type: x-perl-library
  url: https://sendgrid.com/docs/Code_Examples/perl.html
- type: x-php-library
  url: https://sendgrid.com/docs/Code_Examples/php.html
- type: x-pricing
  url: https://sendgrid.com/transactional-email/pricing
- type: x-privacy
  url: https://sendgrid.com/privacy
- type: x-python-library
  url: https://sendgrid.com/docs/Code_Examples/python.html
- type: x-ruby-library
  url: https://sendgrid.com/docs/Code_Examples/ruby.html
- type: x-security
  url: https://sendgrid.com/security
- type: x-selfservice-registration
  url: https://sendgrid.com/user/signup
- type: x-terms-of-service
  url: https://sendgrid.com/tos
- type: x-twitter
  url: https://twitter.com/SendGrid
- type: x-website
  url: https://sendgrid.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
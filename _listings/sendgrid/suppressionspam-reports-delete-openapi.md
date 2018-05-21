---
swagger: "2.0"
x-collection-name: SendGrid
x-complete: 0
info:
  title: SendGrid Delete Suppression Spam Reports
  description: "**This endpoint allows you to delete your spam reports.**\n\nThere
    are two options for deleting spam reports: \n\n1) You can delete all spam reports
    by setting \"delete_all\" to true in the request body. \n2) You can delete some
    spam reports by specifying the email addresses in an array in the request body.\n\n[Spam
    reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient
    indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html)
    and then their email provider reports this to SendGrid.\n\nFor more information,
    please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html)."
  version: 1.0.0
host: api.sendgrid.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /mail_settings/forward_spam:
    get:
      summary: Get Mail Settings Forward Spam
      description: "**This endpoint allows you to retrieve your current Forward Spam
        mail settings.**\n\nEnabling the forward spam setting allows you to specify
        an email address to which spam reports will be forwarded.\n\nMail settings
        allow you to tell SendGrid specific things to do to every email that you send
        to your recipients over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
        or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
      operationId: mail_settings.forward_spam.get
      x-api-path-slug: mail-settingsforward-spam-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Mail
      - Settings
      - Forward
      - Spam
    patch:
      summary: Patch Mail Settings Forward Spam
      description: "**This endpoint allows you to update your current Forward Spam
        mail settings.**\n\nEnabling the forward spam setting allows you to specify
        an email address to which spam reports will be forwarded.\n\nMail settings
        allow you to tell SendGrid specific things to do to every email that you send
        to your recipients over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
        or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
      operationId: mail_settings.forward_spam.patch
      x-api-path-slug: mail-settingsforward-spam-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Mail
      - Settings
      - Forward
      - Spam
  /mail_settings/spam_check:
    get:
      summary: Get Mail Settings Spam Check
      description: "**This endpoint allows you to retrieve your current Spam Checker
        mail settings.**\n\nThe spam checker filter notifies you when emails are detected
        that exceed a predefined spam threshold.\n\nMail settings allow you to tell
        SendGrid specific things to do to every email that you send to your recipients
        over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
        or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
      operationId: mail_settings.spam_check.get
      x-api-path-slug: mail-settingsspam-check-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Mail
      - Settings
      - Spam
      - Check
    patch:
      summary: Patch Mail Settings Spam Check
      description: "**This endpoint allows you to update your current spam checker
        mail settings.**\n\nThe spam checker filter notifies you when emails are detected
        that exceed a predefined spam threshold.\n\nMail settings allow you to tell
        SendGrid specific things to do to every email that you send to your recipients
        over SendGrid\u2019s [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html)
        or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html)."
      operationId: mail_settings.spam_check.patch
      x-api-path-slug: mail-settingsspam-check-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Mail
      - Settings
      - Spam
      - Check
  /suppression/spam_reports:
    delete:
      summary: Delete Suppression Spam Reports
      description: "**This endpoint allows you to delete your spam reports.**\n\nThere
        are two options for deleting spam reports: \n\n1) You can delete all spam
        reports by setting \"delete_all\" to true in the request body. \n2) You can
        delete some spam reports by specifying the email addresses in an array in
        the request body.\n\n[Spam reports](https://sendgrid.com/docs/Glossary/spam_reports.html)
        happen when a recipient indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html)
        and then their email provider reports this to SendGrid.\n\nFor more information,
        please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html)."
      operationId: suppression.spam_reports.delete
      x-api-path-slug: suppressionspam-reports-delete
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Suppression
      - Spam
      - Reports
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---
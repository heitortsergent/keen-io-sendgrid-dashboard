# Keen IO / SendGrid Dashboard

Ever wanted to create a cool dashboard showing your outbound email event data that you can look at while drinking some coffee? :)

![final-dashboard](https://dl.dropboxusercontent.com/u/1053748/keen-dashboard-airpair.png)

This is a dashboard built using [Keen IO](https://keen.io/), [SendGrid's](https://sendgrid.com/) [Event Webhook Data](https://sendgrid.com/docs/API_Reference/Webhooks/event.html), and the [Keen IO's Dashboards](https://github.com/keen/dashboards) project.

It's the final result of following a tutorial I wrote that can be found [here](https://www.airpair.com/sendgrid/posts/making-a-dashboard-with-keen-io-sendgrid-events).

It displays:

- A column chart for all email events for the last 30 days
- A bar chart showing an activation funnel (Emails that were delivered -> opened -> read -> clicked)
- A metric with the all-time emails sent value
- A metric with spam reports for the last 30 days. It displays a green background when that is 0, and red when it's more than 0.
- A piechart with a conversion rate %. It compares total number of emails delivered with total number of emails opened.


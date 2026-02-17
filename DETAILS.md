# Detailed Monitoring Information

## What is being checked?

The monitoring checks at regular intervals (currently every 15 minutes) whether a server responds at a specific web address (URL). For each monitored address, a status code is defined that is considered normal.

The monitoring is considered "in order" if exactly the expected status code is returned. In this case, **UP** is displayed. As soon as an unexpected status code is returned or the connection has failed, **DOWN** is displayed.

*Response time*: The monitoring measures how long the server takes to respond. This serves only as an indication of potential technical problems, not as a performance benchmark.

## What is explicitly not being checked?

The monitoring does not check:

1. **Website content**: The monitoring does not check whether texts, metadata or images, transcriptions and comments are displayed correctly and complete. It does not check whether the "correct" page is being delivered. A page may be technically accessible (status "OK") even if content is missing or incorrect.

2. **Functionality of web applications**: The monitoring does not behave like a human user and performs no interactions. Search or filter functions, viewers, etc., are not checked.

3. **Subject-specific or semantic correctness**: Only whether the service responds is checked, not what it delivers in terms of content.

4. **Display in the browser**: The monitoring does not use a web browser. A page may be "UP" even if it appears faulty in a browser.

## Monitoring service from the University Library of Bern

Initially, this service was established as part of a service of the University Library Bern (LINK to be added soon) for research projects with digital editions. However, it is also used for additional technical services and websites.

For websites for which research projects have a contractual agreement with the University Library (visually marked, tbd), a notification is sent to the University Library (Open Science, Research Data Management) if an unexpected status code occurs.

Part of this agreement is that, in the event of a problem and after consultation with the Data Science Lab, the University Library will contact the project management and/or the responsible institute management if a resolution is necessary.

## Support

For support or to report issues, please contact the Digital Humanities team at the University of Bern.

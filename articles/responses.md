# Reponses
{:.no_toc}

- TOC
{:toc}

As a publisher, once you've sent a questionnaire to authors, you can view and manage the status of their responses.

OAQ workflows depend on updated **response statuses** for the communication of data between publishers and libraries. It's important for publishers to keep response statuses current.

## Managing responses

1. Click **Questionnaires** in the top bar to view a list of all your organization's questionnaires.
2. Find the name of the questionnaire that has the author responses you want to manage.
3. Under **Actions**, click **Responses**.

The **Responses for questionnaire** page will show a list of each author who has been invited to the questionnaire, along with the date it was last modified and the [status](#response-statuses) of the response.

Note that each email address in the **Author Email** column is a hyperlink; if you click the link, your default mail program will open with the author's address, a subject line, and a message body already filled in. The message will include the unique URL to the questionnaire. Feel free to modify this email before sending it, or you can use this feature as a way to access the questionnaire URL for later correspondence.

As a publisher, there may be times where you want to work on a questionnaire on behalf of an author. If you click **Start a new response to <name of questionnaire>** at the top of the page, you can begin a questionnaire without generating an email to an author. You can then either submit the questionnaire yourself or share the URL with the author later. You can also work on an author's in-progress questionnaire by clicking **Edit** next to its name in the list.

## Response statuses

Here’s an explanation of the **Status** dropdown menu options:

| Status | Meaning |
|--|--|
|Sent|The questionnaire has been sent to the author, but the author has not saved any progress yet.|
|In Progress|The author has accessed the questionnaire and saved some amount of work.|
|Author Submitted|The author has gone through each section of the questionnaire and clicked **Submit answers** at the end.|
|Accepted|The publisher has marked the questionnaire as **Accepted** using the Status dropdown menu. This action makes the response visible to any [partner libraries](account_management#partnering-with-libraries).|
|Not Sent|The publisher has created the questionnaire but not yet sent it to authors.|
|Library In Progress*|A partner library has received the accepted questionnaire and begun processing it. Note that when a library takes this action, it locks the questionnaire for further editing by publishers and authors.|
|Library Complete*|A partner library has received the accepted questionnaire and finished processing it.|
|Not processed*|A partner library has received the accepted questionnaire but has not begun processing it yet.|

*These actions are taken by library users in a separate OAQ environment, not by publishers.

You can see the history of events that have been performed on each response by clicking **Status History** under **Actions**. Clicking this link will pop up a window that shows:

* The email address of the user who changed the status
* The updated status
* The timestamp of the status change

If a response's status has never been changed, the popup window will be blank.

## Accepting a response

Once you have determined a response is complete, you can use the Status dropdown menu to mark it as **Accepted**. This action locks the questionnaire for editing by authors or staff members. It also makes the questionnaire response visible to any [partner libraries](account_management#partnering-with-libraries) with your organization.

Additionally, a popup window will prompt you to enter an [ISBN](#associating-responses-with-isbns). You can enter an ISBN-10 or ISBN-13 and click **Add**, whereupon OAQ will validate the ISBN. Alternatively, you can click **Skip Add ISBN**, or you can click **Close** to discard your changes.

If you need to undo an **Accepted** status, you can change the status as long as two conditions are met:

1. You haven't ended your browser session by leaving the page, refreshing the page, or logging out of OAQ.

2. A library has not changed the status of the response on their end.

Once either of these events has happened, you will not be able to change the **Accepted** status. Contact your OAQ site admin if you have reason to change an **Accepted** status and are unable to.

## Exporting response data

The **Responses for questionnaire** page provides you with the option to **Export all responses**. If you click this button, a CSV file containing all responses in the list will begin downloading.

You can also download individual responses by clicking the **Download** dropdown next to any response and choosing to download either a **CSV** or **PDF** file.

## Associating responses with ISBNs

It's good practice to associate each response with an ISBN if you have it available. Adding an ISBN will allow you to uniquely identify the work in exported data.

1. On the **Responses for questionnaire** page, find the response you want to add an ISBN to.
2. Under **Actions**, click **Add/Edit ISBN**.
3. On the page that opens, click **Add another ISBN**.
4. Enter an ISBN-10 or ISBN-13. OAQ will validate the ISBN before accepting it.
5. Click **Save**.

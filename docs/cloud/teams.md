- Remove default team
- Combine Remove a Team Member and Leave a Team
- Make each section more robust
- Add an Activity Page
- -> ### Managing Team Settings
- Reviewing Team Activity

---

# Teams

> Intro

![Teams](images.webp)

[[toc]]

## Creating a Team

![Create Team](https://cdn.directus.io/docs/v9/cloud/accounts-and-teams/accounts-and-teams-20220228A/creating-a-team-20220225A.webp)

Teams are how you organize Projects and share them across multiple accounts. They're free, so create as many as you'd
like! To create a new team...

1. Sign in to the Cloud Dashboard.
2. Open the Team Menu in the Dashboard Header.
3. In the dropdown, click <span mi icon prmry>add</span> to create Team.
4. Enter a Team Name, Team Slug, and click **"Save"**.

## Managing a Team

![Managing a Team](https://cdn.directus.io/docs/v9/cloud/accounts-and-teams/accounts-and-teams-20220228A/managing-a-team-20220225A.webp)

After signing in to the Dashboard, you will be taken to your default Team (see Account Settings).

1. Sign in to the Cloud Dashboard.
2. Open the Team Menu in the Dashboard Header.
3. In the dropdown, select the Team you wish to manage.
4. Navigate to the Settings page.
5. Toggle <span mi icon prmry>edit</span> to allow edits.
6. Make your changes as desired.
7. Click the **"Save"** button.

## Inviting a Team Member

![Inviting a Team Member](https://cdn.directus.io/docs/v9/cloud/accounts-and-teams/accounts-and-teams-20220228A/inviting-a-team-member-20220225A.webp)

All members of a Team can invite new Members via email. Each invited user will be emailed with a link to accept the
invitation and join the Team.

1. Sign in to the Cloud Dashboard.
2. Open the Team Menu in the Dashboard Header.
3. Select the appropriate Team from the dropdown.
4. Navigate to the Members page.
5. Scroll down to the Invite New Members section.
6. Enter one or more email(s), comma separated.
7. Click **"Send Invites"**.

::: tip Adding Members to Projects

By default, Team members are not given user access to the Team's Projects. To manage a Project's users, log in to the
project as an administrator and navigate to the User Directory.

:::

## Removing a Team Member

![Removing a Team member](https://cdn.directus.io/docs/v9/cloud/accounts-and-teams/accounts-and-teams-20220228A/leaving-a-team-20220225A.webp)

All team members have the ability to remove other members or invites from the team.

1. Sign in to the Cloud Dashboard.
2. Open the Team Menu in the Dashboard Header.
3. Select the appropriate Team from the dropdown.
4. Navigate to the "Members" page.
5. Click <span mi icon>exit_to_app</span> or <span icon>close</span> button for your account.
6. Click confirm to remove.

## Leaving a Team

![Leaving a Team](https://cdn.directus.io/docs/v9/cloud/accounts-and-teams/accounts-and-teams-20220228A/leaving-a-team-20220225A.webp)

You can leave a team if you no longer want access, but you cannot get access again without being re-invited by another
member. To leave a team, follow these steps:

1. Sign in to the Cloud Dashboard.
2. Open the Team Menu in the Dashboard Header.
3. Select the appropriate Team from the dropdown.
4. Navigate to the "Members" page.
5. Click <span mi icon>exit_to_app</span> for your account.
6. Confirm and exit group.

## Destroying a Team

![Destroying a Team](https://cdn.directus.io/docs/v9/cloud/accounts-and-teams/accounts-and-teams-20220228A/destroy-a-team-20220225A.webp)

This action is permanent and irreversible. Destroying a Directus Cloud Team completely removes all its data from our
platform (for all team members). To destroy a Directus Cloud Team, follow these steps:

1. Sign in to the Cloud Dashboard.
2. Open the Team Menu in the Dashboard Header.
3. Select the team you wish to destroy from the dropdown.
4. Navigate to the **Settings** page.
5. Scroll down to the "Destroy this Team" section.
6. Toggle <span mi icon dngr>local_fire_department</span> and an input box will appear.
7. Enter the team name into the input box.
8. Click **"Destroy Team"**.

::: tip

You cannot destroy a Team if it contains one or more Projects. So you must destroy any contained Projects before
destroying your Team.

:::

::: danger DANGER!

Action is permanent and irreversible, proceed with caution.

:::
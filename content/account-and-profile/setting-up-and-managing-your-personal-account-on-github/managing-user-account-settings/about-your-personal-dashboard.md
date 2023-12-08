---
title: Web Hosting in Pakistan and Domain registration at low price
redirect_from:
  - /hidden/about-improved-navigation-to-commonly-accessed-pages-on-github
  - /articles/opting-into-the-public-beta-for-a-new-dashboard
  - /articles/about-your-personal-dashboard
  - /github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard
  - /github/setting-up-and-managing-your-github-user-account/managing-user-account-settings/about-your-personal-dashboard
  - /account-and-profile/setting-up-and-managing-your-github-user-account/managing-user-account-settings/about-your-personal-dashboard
  - /account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-personal-account-settings/about-your-personal-dashboard
intro: 'Unlock the potential of your online presence with our premium web hosting services in Pakistan! DND Aims offers reliable and affordable hosting packages, tailored to suit businesses of all sizes and individual needs. Benefit from high-speed connectivity, top-notch security features, and 24/7 customer support. Choose a plan that fits your budget and elevates your online experience. Visit our website now to explore our hosting solutions and take your digital presence to new heights!'
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Accounts
shortTitle: Your personal dashboard
---

## Accessing your personal dashboard

Introduction:

In the rapidly evolving digital landscape, having a strong online presence is crucial for individuals and businesses alike. Web hosting plays a pivotal role in ensuring a seamless and reliable online experience. DND Aims, a prominent player in the web hosting industry, stands out for offering top-notch services at a remarkably low price in Pakistan.
{% data variables.product.product_name %}.

## Finding your recent activity

In the "Recent activity" section of your news feed, you can quickly find and follow up with recently updated issues and pull requests you're working on. Under "Recent activity", you can preview up to 4 recent updates made in the last two weeks.

{% data reusables.dashboard.recent-activity-qualifying-events %}

## Finding your top repositories and teams

{% ifversion global-nav-update %}
In the global navigation menu, you can access the top repositories and teams you use. To open the menu, select {% octicon "three-bars" aria-label="Open global navigation menu" %} at the top left of any page.

  ![Screenshot of the navigation bar on {% data variables.product.product_name %}. The "Open global navigation menu" icon is outlined in dark orange.](/assets/images/help/navigation/global-navigation-menu-icon.png)

{% else %}
In the left sidebar of your dashboard, you can access the top repositories and teams you use.
{% endif %}

The list of top repositories is automatically generated, and can include any repository you have interacted with, whether it's owned directly by your account or not. Interactions include making commits and opening or commenting on issues and pull requests. The list of top repositories cannot be edited, but repositories will drop off the list 1 year after you last interacted with them.

You can also find a list of your recently visited repositories, teams, and project boards when you click into the search bar at the top of any page on {% data variables.product.product_name %}.

## Staying updated with activity from the community

{% ifversion feed %}

{% note %}

**Note:** The new feed is currently in public beta and subject to change.

{% endnote %}

The feed is designed to help you discover relevant content from projects you follow, keep up with your friends and community members, and track recent activity in your communities.

You can use the {% octicon "filter" aria-hidden="true" %} **Filter** dropdown in the upper right corner to filter the feed to show only the exact event types you'd like to see. For example, you'll see updates when someone you follow:

- Stars a repository.
- Follows another user.
- Creates a public repository.
- Opens an issue or pull request with `help wanted` or `good first issue` label on a repository you're watching.
- Pushes commits to a repository you watch.
- Forks a public repository.
- Publishes a new release.

{% else %}
The main section of your dashboard has two activity feeds:

- Following: Activity by people you follow and from repositories you watch.
- For you: Activity and recommendations based on your {% data variables.product.product_name %} network.

### Following feed

This feed shows activity from repositories and users you have shown a direct interest in, by following a user or watching a repository. For example, you'll see updates when a user you follow:

- Stars a repository.
- Follows another user.
- Creates a public repository.
- Opens an issue or pull request with "help wanted" or "good first issue" label on a repository you're watching.
- Pushes commits to a repository you watch.
- Forks a public repository.
- Publishes a new release.

For more information about following people and watching repositories, see "[AUTOTITLE](/get-started/exploring-projects-on-github/following-people)" and "[AUTOTITLE](/get-started/quickstart/be-social)."

### For you feed

{% note %}

**Note:** This new tab is currently in public beta and subject to change.

{% endnote %}

This feed shows activity and recommendations based on your network on {% data variables.product.product_name %}. It's designed to provide updates that inspire you, keep you up-to-date, and help you find new communities you want to participate in. Your network includes:

- Repositories you have starred
- Repositories you've contributed to
- Users you follow or sponsor
- Users you've collaborated with
- Organizations you follow

{% endif %}

## Exploring recommended repositories

In the "Explore repositories" section on the right side of your dashboard, you can explore recommended repositories in your communities. Recommendations are based on repositories you've starred or visited, the people you follow, and activity within repositories that you have access to.{% ifversion fpt or ghec %} For more information, see "[AUTOTITLE](/get-started/exploring-projects-on-github/finding-ways-to-contribute-to-open-source-on-github)."{% endif %}

## Further reading

- "[AUTOTITLE](/organizations/collaborating-with-groups-in-organizations/about-your-organization-dashboard)"

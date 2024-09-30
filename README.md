# Google Summer of Code'24 @ Mautic


![GSoC'24 Mautic](/Image/Report.png)


The report provides an overview of my contributions at mautic. My experience has been both rewarding and enlightening with the mautic. I had the privilege of getting the opportunity to showcase my skills and contribute to mautic marketplace. The report describes about my experience with the community and project.

## Project Overview :

- **Project Name:** Expand the Mautic Marketplace: Ratings, reviews and UX improvements.
- **Project Repository:** mautic-marketplace
- **Contributor:** Ketu Patel
- **Mentors:** John Linhart, Rahul Shinde, Simran Sethi

Mautic Marketplace provides users with access to plugins sourced from Packagist. And the Packagist API has many limitations. The Marketplace lacks critical features such as ratings, reviews, and advanced search capabilities, limiting user engagement and discoverability. Moreover, the user interface could benefit from optimization to improve usability and navigation.

This project will expand the features of our Marketplace to make it more user-friendly to the marketer. It will enable the marketer to rate and review the plugins they use, and also to interact more smoothly with those plugins available in the Marketplace.


### Contribution (Key Milestone) to Mautic Marketplace 🌟

#### ✅ Migrated the data from Packagist to Supabase.
- The marketplace uses the Packagist API and it has some limitations, so we successfully migrated our data from Packagist to Supabase to enhance the functionality and performance of our marketplace. This transition was necessary due to the limitations of the Packagist API. The migration was executed using Supabase Edge Functions developed with Deno and typescript, which allowed for efficient data handling and integration.

#### ✅ Replaced the API KEY 
- We used the DB Functions to make the inbuilt REST API more promised. There are Two DB Functions who include the List View and Detail View of the Marketplace. The new API KEY provide Functionalities to search by any parameter, the user can sort the plugins or themes. We also enabled the DB Function that highlight the verified plugins, this option is done in backend side although it will be implemented to front end side by community.

#### ✅ Introducing the rating and review feature
- Marketers can rate their experiences on a scale, helping us understand their satisfaction levels. Along with ratings, they can leave detailed reviews, offering insights into what they loved or areas for improvement.

#### ✅ Enable the auth0 for authentication
- To ensure the integrity and reliability of our rating and review system, we have implemented Auth0, a robust authentication platform. This enhancement requires users to authenticate themselves before they can rate or review plugins or themes, effectively preventing spam and ensuring the authenticity of user feedback.

#### 🔳 Enable the edit option for rating and review
- We will also enable the edit option so marketers can easily modify their existing reviews to reflect any new experiences or changes related to the new version of the plugin or the theme. As per changes, marketers can adjust their reviews to provide the most current feedback.

## 🎓 DELIVERABLES

| TASKS                         |             STATUS                  |               commits                   |
| :--------------: | :-------------------------------------------: |  :------------------------------------------------------------------: |
| Solving the API limitations |            DONE                     |     [MarketPlace](https://github.com/mautic/mautic-marketplace)                                  |
| Enabling the rating and review features |           DONE            |      [Rating_Reviews](https://github.com/mautic/marketplace-frontend)                                  |

<details>

<summary> <h1>Weekly Blogs
🖊️</h1> </summary>
<br>

- [Week 0](https://community.mautic.org/assemblies/gsoc/f/61/posts/13)
- [Week 1](https://community.mautic.org/assemblies/gsoc/f/61/posts/14)
- [Week 2](https://community.mautic.org/assemblies/gsoc/f/61/posts/33)
- [Week 3](https://community.mautic.org/assemblies/gsoc/f/61/posts/34)
- [Week 4](https://community.mautic.org/assemblies/gsoc/f/61/posts/37)
- [Week 5](https://community.mautic.org/assemblies/gsoc/f/61/posts/38)
- [Week 6](https://community.mautic.org/assemblies/gsoc/f/61/posts/39)
- [Week 7](https://community.mautic.org/assemblies/gsoc/f/61/posts/40)
- [Week 8](https://community.mautic.org/assemblies/gsoc/f/61/posts/41)
- [Week 9](https://community.mautic.org/assemblies/gsoc/f/61/posts/45)
- [Week 10](https://community.mautic.org/assemblies/gsoc/f/61/posts/47)
- [Week 11](https://community.mautic.org/assemblies/gsoc/f/61/posts/48)
- [Week 12](https://community.mautic.org/assemblies/gsoc/f/61/posts/50)
- [Week 13](https://community.mautic.org/assemblies/gsoc/f/61/posts/52)
- [Week 14](https://community.mautic.org/assemblies/gsoc/f/61/posts/53)

</details>

## Future Goals 

Utilize analytics to gather insights on user behavior and preferences, allowing us to make informed decisions for future updates and features. Implementing the testing of edge function so we can ensure it's workability.

## Acknowledgement

I would like to express my heartfelt gratitude to my mentors: John Linhart, Rahul Shinde, Simran Sethi, Ruth Cheesley, whose guidance and support have been invaluable throughout my journey. Their wisdom and insights have inspired me to push my boundaries and strive for excellence. Thank you for being my sounding board, providing constructive feedback, and encouraging me during challenging times. Special thanks to Google for this amazing program and giving me the opportunity. The whole mautic community is very welcoming and supportive. Continuing my contributions to the Mautic organization ...

***
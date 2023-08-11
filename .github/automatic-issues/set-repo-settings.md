
For more information on these settings see instructions in [Using C-MOOR_Template](https://github.com/C-MOOR/C-MOOR_Template/wiki/Using-C%E2%80%90MOOR_Template) and [Starting a new OTTR course](https://www.ottrproject.org/getting_started.html#starting-a-new-ottr-course).

- [ ] This course repository is set to `public`.
- [ ] [Add the `jhudsl-robot` as a collaborator to your repository.](https://www.ottrproject.org/getting_started.html#5_Add_jhudsl-robot_as_a_collaborator).

- [ ] If your repository does not belong to the C-MOOR organization, [set the Github secret `GH_PAT`](https://www.ottrproject.org/getting_started.html#6_Set_up_your_GitHub_personal_access_token)
  - `Name`:  `GH_PAT`
  - `value`: A personal access token [following these instructions](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token#creating-a-token).
  - Underneath `Select scopes`, check both `repo` and `workflow`.
  - Then copy the PAT and save as the value.
  
- [ ] GitHub pages is turned on
  - [ ] Go to `Settings` > `Pages`. Underneath `Source`, choose `main` for the branch and select the `docs` folder. Then click `Save`.  
  - [ ] Check `Enforce HTTPS`.
  - [ ] Go back to the repo root.  In the About section (on the right) click the gear icon to edit, then check the box to use your GitHub pages site as the website for the repository.

- [ ] [Customize GitHub actions](https://www.ottrproject.org/customize-robots.html) for what you will need in this course.

# Project_1

- This project collected GitHub users in Tokyo with more than 200 followers and their repositories.
- The analysis revealed that most Tokyo-based GitHub users work in similar fields, with certain languages being significantly more popular.
- Developers in Tokyo could improve visibility by focusing on more popular languages and contributing to public repositories.

### Scrapping Data Process
Using the GitHub API, I retrieved user profiles and repositories by iterating through API pages, saving each user's relevant details to `users.csv` and repositories to `repositories.csv`.

### Key Findings
- Tokyo GitHub users favor certain companies and technologies, with a notable trend in language popularity like JavaScript.
- Certain types of repositories tend to attract higher star ratings.
- array(['none', 'true'], dtype=object), the unique values of hireable were true and none, not false.
- From this project, I learned how to work with a paginated API that returns up to 30 results per call by default and how to use the `per_page` parameter to retrieve up to 100 results in a single call.

### Recommendations
Developers should focus on contributing to repositories in trending languages to increase visibility and followers.

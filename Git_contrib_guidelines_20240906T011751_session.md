
# Git contribution guidelines

>  It's a good practice is to use a consistent format for Git commit messages, which helps in organizing and understanding the history of a project. Therefore, please adhere to the following commit message template for various types of code changes.
> 
> ```
> <type>: <short description>
> <BLANK LINE>
> <longer description if needed>
> <BLANK LINE>
> <footer>(optional) issues closed by this commit>
> ```
> 
> Here’s how you can define each part:
> 
> - **`<type>`**: This is a brief summary of the change and should be one of the following:
>   - `feat`: (feature) A new feature.
>   - `fix`: (bug fix) A bug fix.
>   - `perf`: (performance) A code change that improves performance.
>   - `refactor`: A code change that neither fixes a bug nor adds a feature.
>   - `style`: Changes that do not affect the meaning of the code (e.g., formatting, missing semi-colons, etc).
>   - `docs`: Documentation only changes.
>   - `test`: Adding missing or correcting existing tests.
>   - `chore`: Other changes that do not modify src or test files.
> 
> - **`<short description>`**: A concise description of the change (less than 50 characters).
> 
> - **`<longer description if needed>`**: This is an optional field where you can provide more details about the change, especially for `feat`, `fix`, and `perf`. Keep it short and to the point.
> 
> - **`<footer>(optional) issues closed by this commit>`**: If your commit closes any issues in the issue tracker, you can mention them here in the format `Closes #123` (replace 123 with the issue number). This will automatically close the issue when the pull request is merged.
> 
> ### Example Templates:
> 
> #### Feature Addition
> ```
> feat: add new user registration feature
> ```
> 
> #### Bug Fix
> ```
> fix: correct spelling mistake in documentation
> ```
> 
> #### Performance Improvement
> ```
> perf: optimize database queries for faster response times
> ```
> 
> #### Code Refactoring
> ```
> refactor: simplify conditional logic in the main module
> ```
> 
> #### Style Changes
> ```
> style: format code with prettier and enforce consistent style
> ```
> 
> #### Documentation Update
> ```
> docs: update user manual to reflect latest changes
> ```
> 
> #### Test Improvement
> ```
> test: add unit tests for new API endpoint
> ```
> 
> #### Miscellaneous Change
> ```
> chore: upgrade dependencies to their latest versions
> ```
> 
> This template helps in maintaining a clear and structured commit history, which is beneficial when reviewing code or when you need to look back at the changes later.
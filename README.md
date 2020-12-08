# Thompson sampling in Qualtrics

## Using Github API to store 

In Github

1. Create a Github personal acces token: https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/creating-a-personal-access-token
2. Create a repository and add a file the data can be written to, for example "data.txt" BETTER TO HAVE SOME KIND OF CSV FILE

In Qualtrics

3. Create embedded variables in your Qualtrics survey to store data up to this point, and data including the new data point. Let's call these "old_data" and "new_data" respectively
4. Use the "Web Service" feature by Qualtrics to get current data via the Github API (with the GET method). Screenshot below
5. JavaSCript
6. Github API using PUT method

## Thompson sampling with binary outcome

## Other types of adaptive experimentation

# Acknowledgments

This repository build on previous work by @taffakur, ...


# Notes

https://stackoverflow.com/questions/9590225/is-there-a-library-to-generate-random-numbers-according-to-a-beta-distribution-f
